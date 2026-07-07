# Hi, I'm Hamza Shahid 👋

<!-- Write your intro / bio / skills here. This part is NOT touched by automation. -->

I'm a developer who loves building things. Here's a bit about me:

- 🔭 Currently working on: ...
- 🌱 Learning: ...
- 💬 Ask me about: ...
- 📫 Reach me: ...

---

## 🚀 Projects

<!-- PROJECTS-START -->
<!-- This section is auto-generated. Do not edit manually — it will be overwritten. -->
<!-- PROJECTS-END -->

---

## 📊 GitHub Stats

![Hamza's GitHub stats](https://github-readme-stats.vercel.app/api?username=Hamza-Shahid555&show_icons=true&theme=default)

<!-- Last updated automatically by GitHub Actions -->



name: Update Projects Section

on:
  schedule:
    - cron: "0 6 * * *"
  workflow_dispatch: {}
  push:
    branches: [main]

permissions:
  contents: write

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repo
        uses: actions/checkout@v4

      - name: Set up Node
        uses: actions/setup-node@v4
        with:
          node-version: "20"

      - name: Update projects table
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          GH_USERNAME: Hamza-Shahid555
        run: node scripts/update-projects.js

      - name: Commit changes if README updated
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "github-actions[bot]@users.noreply.github.com"
          git add README.md
          if ! git diff --cached --quiet; then
            git commit -m "chore: auto-update projects list"
            git push
          else
            echo "No changes to commit."
          fi


          const fs = require("fs");
const path = require("path");

const USERNAME = process.env.GH_USERNAME || "Hamza-Shahid555";
const TOKEN = process.env.GITHUB_TOKEN;
const README_PATH = path.join(__dirname, "..", "README.md");

const START_MARKER = "<!-- PROJECTS-START -->";
const END_MARKER = "<!-- PROJECTS-END -->";

async function fetchRepos() {
  const repos = [];
  let page = 1;

  while (true) {
    const res = await fetch(
      `https://api.github.com/users/${USERNAME}/repos?per_page=100&page=${page}&sort=updated`,
      {
        headers: {
          Accept: "application/vnd.github+json",
          ...(TOKEN ? { Authorization: `Bearer ${TOKEN}` } : {}),
        },
      }
    );

    if (!res.ok) {
      throw new Error(`GitHub API error: ${res.status} ${await res.text()}`);
    }

    const data = await res.json();
    if (data.length === 0) break;

    repos.push(...data);
    page++;
  }

  return repos.filter(
    (r) => !r.fork && r.name.toLowerCase() !== USERNAME.toLowerCase()
  );
}

function buildTable(repos) {
  if (repos.length === 0) {
    return "_No public projects yet — check back soon!_";
  }

  const header =
    "| Project | Description | Language | ⭐ Stars | Last Updated |\n" +
    "|---|---|---|---|---|\n";

  const rows = repos.map((r) => {
    const name = `[${r.name}](${r.html_url})`;
    const desc = (r.description || "—").replace(/\|/g, "\\|");
    const lang = r.language || "—";
    const stars = r.stargazers_count;
    const updated = new Date(r.updated_at).toISOString().split("T")[0];
    return `| ${name} | ${desc} | ${lang} | ${stars} | ${updated} |`;
  });

  return header + rows.join("\n");
}

function updateReadme(table) {
  const readme = fs.readFileSync(README_PATH, "utf8");

  const startIdx = readme.indexOf(START_MARKER);
  const endIdx = readme.indexOf(END_MARKER);

  if (startIdx === -1 || endIdx === -1) {
    throw new Error(
      "Could not find PROJECTS-START / PROJECTS-END markers in README.md"
    );
  }

  const before = readme.slice(0, startIdx + START_MARKER.length);
  const after = readme.slice(endIdx);

  const newReadme = `${before}\n${table}\n${after}`;
  fs.writeFileSync(README_PATH, newReadme);
}

(async () => {
  console.log(`Fetching repos for ${USERNAME}...`);
  const repos = await fetchRepos();
  console.log(`Found ${repos.length} project(s).`);

  const table = buildTable(repos);
  updateReadme(table);

  console.log("README.md updated.");
})().catch((err) => {
  console.error(err);
  process.exit(1);
});
