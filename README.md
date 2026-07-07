<!-- ████████████████████████████████████████████████ -->
<!--           HAMZA SHAHID — GITHUB PROFILE         -->
<!-- ████████████████████████████████████████████████ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:FF6F00,100:0d1117&height=220&section=header&text=Hamza%20Shahid&fontSize=72&fontAlignY=38&fontColor=FFFFFF&desc=Machine%20Learning%20Engineer%20%E2%80%A2%20AI%20Researcher%20%E2%80%A2%20Deep%20Learning%20Architect&descSize=17&descAlignY=62&descAlign=50&animation=fadeIn" width="100%"/>

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=3000&pause=800&color=FF6F00&center=true&vCenter=true&multiline=false&width=750&lines=Building+xLSTM+%26+Transformer+Systems+%E2%9A%A1;Vision+Transformers+for+Sign+Language+AI+%F0%9F%A4%9F;Zero-Shot+Financial+Forecasting+%F0%9F%93%88;End-to-End+ML+Pipelines+%F0%9F%8F%AD;Open+to+Collaborate+on+Ambitious+AI+Projects+%F0%9F%A4%9D)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hamza-shahid-56a008372)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hamza-Shahid555)
&nbsp;
[![Profile Views](https://komarev.com/ghpvc/?username=Hamza-Shahid555&style=for-the-badge&color=FF6F00&label=PROFILE+VIEWS)](https://github.com/Hamza-Shahid555)

</div>

<div align="center">
  <sub>
    <a href="#-whoami">whoami</a> ·
    <a href="#-flagship-projects">Flagship Projects</a> ·
    <a href="#-complete-project-index-auto-synced">Full Project Index</a> ·
    <a href="#%EF%B8%8F-tech-arsenal">Tech Arsenal</a> ·
    <a href="#-github-analytics">Analytics</a> ·
    <a href="#-lets-collaborate">Collaborate</a>
  </sub>
</div>

---

<img align="right" width="38%" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif" alt="coding gif"/>

## 🧬 `whoami`

```python
class HamzaShahid:

    name       = "Hamza Shahid"
    title      = "Data Science Undergraduate"
    location   = "Pakistan 🇵🇰"

    interests  = [
        "Sequence Modeling (xLSTM, RNNs)",
        "Vision Transformers (ViT, ViViT)",
        "Zero-Shot & Transfer Learning",
        "Financial Time-Series Forecasting",
        "Accessibility AI (Sign Language)",
        "End-to-End ML Pipelines",
    ]

    currently  = "Pushing the frontier of AI, one commit at a time"
    open_to    = "Research collaborations & ambitious AI/ML projects"

    def motto(self):
        return "Engineering the next wave of AI — line by line. 🚀"
```

<br clear="right"/>

<div align="center">

<!-- SNAKE-START -->
<img src="https://raw.githubusercontent.com/Hamza-Shahid555/Hamza-Shahid555/output/github-contribution-grid-snake-dark.svg" width="100%" alt="contribution snake animation"/>
<!-- SNAKE-END -->

</div>

---

## 🌌 Flagship Projects

> Handpicked milestones — from research prototypes to production pipelines. Every new repo I push also lands automatically in the [full index](#-complete-project-index-auto-synced) below, so this section is reserved for the work I'm proudest of.

---

### 🔬 FLAGSHIP — Vision AI for Accessibility

<table>
<tr>
<td>

### 🤟 [OmniGesture — ASL Sign Language Recognition](https://github.com/Hamza-Shahid555/OmniGesture)

**The Vision:** Millions use sign language daily. What if AI could understand them?

OmniGesture reads **American Sign Language (ASL)** gestures directly from video using a **Vision Video Transformer (ViViT)** — trained on the **WLASL dataset** (100 ASL classes).

```
📹 Video Clip  →  🧩 16-frame Tubelet Embeddings
      →  🔍 ViViT spatiotemporal attention
      →  🏷️ Predicted ASL word label
```

**2-Stage Training:**
- Stage 1 — Freeze backbone, train head → ~45–55% accuracy
- Stage 2 — Unfreeze top attention blocks, fine-tune → ~65–75% accuracy

> Prevents **catastrophic forgetting** while learning ASL-specific patterns.

`PyTorch` `HuggingFace ViViT` `OpenCV` `MediaPipe` `Gradio` `einops` `Colab T4`

</td>
<td align="center" width="200px">

⭐ **1 Star**

`Computer Vision`
`ViViT`
`Sign Language`
`Accessibility AI`
`Video Transformer`

[![View](https://img.shields.io/badge/View_Repo-FF6F00?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hamza-Shahid555/OmniGesture)

</td>
</tr>
</table>

---

### ⚡ RESEARCH — Extended LSTM Benchmarking

<table>
<tr>
<td>

### 🧠 [xLSTM-Bench — sLSTM & mLSTM from Scratch](https://github.com/Hamza-Shahid555/xLSTM-Bench)

Full PyTorch implementation of **xLSTM** — next-gen recurrent architecture that rivals Transformers using **linear O(N) inference complexity**.

**Two architectures built from scratch:**

| Architecture | Innovation |
|---|---|
| **sLSTM** | Exponential gating → eliminates vanishing gradients |
| **mLSTM** | Matrix memory (KV pairs) → Transformer-like capacity |

**Results on Tiny Shakespeare:**

| Model | Loss (1k steps) | Convergence |
|---|---|---|
| Vanilla LSTM | ~1.81 | Slower |
| **xLSTM (Ours)** | **~1.66 ✅** | **Faster ✅** |

Also includes **MatrixMind** — an xLSTM-based generative agent + Gradio demo.

`PyTorch` `Gradio` `Matplotlib` `Custom RNN Architectures`

</td>
<td align="center" width="200px">

🆕 **Research Level**

`xLSTM`
`sLSTM / mLSTM`
`Sequence Modeling`
`Benchmarking`
`Generative AI`

[![View](https://img.shields.io/badge/View_Repo-FF6F00?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hamza-Shahid555/xLSTM-Bench)

</td>
</tr>
</table>

---

### 📈 RESEARCH — Zero-Shot Financial Forecasting

<table>
<tr>
<td>

### 💹 [Zero-Shot Financial Forecasting with Transformers](https://github.com/Hamza-Shahid555/Zero-Shot-Financial-Forecasting-with-Transformers)

A Transformer-based deep learning framework that forecasts volatile **cryptocurrency prices** by transferring knowledge from **S&P 500 market dynamics** — with no crypto-specific fine-tuning.

- ✅ Low MSE on completely **unseen** crypto data
- ✅ Rigorous EDA before any model fitting
- ✅ Tackles real ML failure modes: volatility blindness, blind model fitting

**Pipeline:** Raw Data → EDA → Feature Engineering → Transformer → Zero-Shot Prediction

`PyTorch` `HuggingFace Transformers` `Pandas` `NumPy` `Matplotlib` `Seaborn`

</td>
<td align="center" width="200px">

🆕 **Frontier AI**

`Zero-Shot Learning`
`Transformers`
`Time Series`
`Finance ML`
`S&P500 → Crypto`

[![View](https://img.shields.io/badge/View_Repo-FF6F00?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hamza-Shahid555/Zero-Shot-Financial-Forecasting-with-Transformers)

</td>
</tr>
</table>

---

### 🏭 ENGINEERING — Production-Grade ML Pipeline

<table>
<tr>
<td>

### ⚙️ [End-to-End APS Failure Detection](https://github.com/Hamza-Shahid555/End_to_End_APS_ML_Project)

A production-style ML system for detecting **Air Pressure System (APS) failures** in heavy-duty trucks. Structured as a real-world engineering project, not just a notebook.

**Pipeline:** Data Ingestion → Validation → Transformation → Training → Evaluation → Packaging

`Scikit-learn` `MLOps Patterns` `Pipeline Engineering` `Fault Detection`

</td>
<td align="center" width="200px">

🏗️ **MLOps Style**

`Production ML`
`Fault Detection`
`Safety Systems`
`End-to-End`

[![View](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hamza-Shahid555/End_to_End_APS_ML_Project)

</td>
</tr>
</table>

---

### 💬 INTERACTIVE — Live Prediction Dashboard

<table>
<tr>
<td>

### 📊 [Customer Churn Prediction Dashboard](https://github.com/Hamza-Shahid555/Customer-Churn-Prediction-using-ANN)

Live ML dashboard predicting bank customer churn via two models: **ANN** (deep learning) + **Random Forest** (ensemble). Enter customer details → get real-time churn probability.

`TensorFlow/Keras` `Scikit-learn` `Streamlit` `Pandas` `Neural Nets`

</td>
<td align="center" width="200px">

🖥️ **Interactive**

`ANN`
`Random Forest`
`Streamlit`
`Banking ML`

[![View](https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hamza-Shahid555/Customer-Churn-Prediction-using-ANN)

</td>
</tr>
</table>

---

### 📚 FOUNDATIONS — Learning & Coursework

<details>
<summary><b>📖 Click to expand Foundation Projects</b></summary>

<br>

**[🔬 Deep Learning Collection](https://github.com/Hamza-Shahid555/Deep-learning)**
Structured deep dive — CNNs, RNNs, autoencoders, bridging theory and practice.
`TensorFlow` `Keras` `PyTorch`

**[📗 Machine Learning A to Z](https://github.com/Hamza-Shahid555/Machin_learning_A_to_Z)** ⭐ 2 Stars
Classical ML mastery — preprocessing to model evaluation, all modular.
`Scikit-learn` `Pandas` `NumPy`

**[🎓 Neural Networks & Deep Learning — Andrew Ng](https://github.com/Hamza-Shahid555/Neural-Networks-and-Deep-Learning)**
DeepLearning.AI Specialization assignments — backprop, optimization, NN math from scratch.
`NumPy` `Coursera` `DeepLearning.AI`

</details>

---

## 📦 Complete Project Index (Auto-Synced)

> 🤖 Everything below refreshes itself daily via GitHub Actions — pulls straight from the GitHub API. Push a new repo, and it shows up here within a day (or instantly if I trigger the workflow manually). Zero manual editing.

<!-- PROJECTS-START -->
| Project | Description | Language | ⭐ Stars | Last Updated |
|---|---|---|---|---|
| [Hamza-Shahid555-](https://github.com/Hamza-Shahid555/Hamza-Shahid555-) | — | JavaScript | 0 | 2026-07-07 |
| [Agentic-AI-](https://github.com/Hamza-Shahid555/Agentic-AI-) | 🤖 Agentic AI framework for building autonomous, tool-using agents powered by LLMs. | Roff | 0 | 2026-07-07 |
| [GenAI-using-LangChain-](https://github.com/Hamza-Shahid555/GenAI-using-LangChain-) | we will work on LangChain using in GenAi Generative AI with LangChain means building applications that use Large Language Models (LLMs) like GPT, but in a structured and powerful way.  🔹 What LangChain Does  LangChain acts as a bridge between LLMs and real-world data/tools.  | Python | 0 | 2026-07-06 |
| [EEG-Based-Epileptic-Seizure-Detection-and-Classification](https://github.com/Hamza-Shahid555/EEG-Based-Epileptic-Seizure-Detection-and-Classification) | This project applies machine learning and deep learning techniques to detect and classify epileptic seizures from EEG (electroencephalogram) signals. Raw EDF (European Data Format) EEG recordings from 6 patients (p10–p15) are preprocessed, segmented, and labeled into seizure types | Jupyter Notebook | 0 | 2026-05-17 |
| [A-To-Z-PyTorch](https://github.com/Hamza-Shahid555/A-To-Z-PyTorch) | For ML DL and for LLM as well as for GenAI we must required  PyTorch so in this repository we will go deepdown in  PyTorch library a to z | Jupyter Notebook | 0 | 2026-05-01 |
| [-LangChain-Models-Indepth-Tutorial-with-Code-Demo](https://github.com/Hamza-Shahid555/-LangChain-Models-Indepth-Tutorial-with-Code-Demo) | in repo deferent models on which we working in langChain  you can discover how to apply or download deferent model through api  as well as manually  | Python | 0 | 2026-05-01 |
| [-LangChain-Models-Indepth-Tutorial-with-Code-Demo-](https://github.com/Hamza-Shahid555/-LangChain-Models-Indepth-Tutorial-with-Code-Demo-) |  LangChain Models \| Indepth Tutorial with Code Demo/ | — | 0 | 2026-04-29 |
| [-LangChain-Models-with-code-](https://github.com/Hamza-Shahid555/-LangChain-Models-with-code-) |  LangChain Models \| Indepth Tutorial with Code Demo | — | 0 | 2026-04-28 |
| [QA-System-using-RAG](https://github.com/Hamza-Shahid555/QA-System-using-RAG) | An advanced NLP project that builds an intelligent Question Answering System using Retrieval-Augmented Generation (RAG). This system retrieves relevant medical knowledge and generates accurate, context-aware answers using deep learning and modern AI techniques. | Jupyter Notebook | 0 | 2026-04-25 |
| [RNN-using-PyTorch-Question-Answering-System-using-PyTorch](https://github.com/Hamza-Shahid555/RNN-using-PyTorch-Question-Answering-System-using-PyTorch) | This project demonstrates how to build a simple Question Answering (QA) system using a Recurrent Neural Network (RNN) in PyTorch. The goal is to create a model that can understand a question and return the most relevant answer from a dataset, or respond with "I don't know" if the question is unfamiliar. | — | 0 | 2026-04-24 |
| [Neural-Network-Training-Pipeline-in-PyTorch](https://github.com/Hamza-Shahid555/Neural-Network-Training-Pipeline-in-PyTorch) | This project demonstrates a complete end-to-end neural network training pipeline using PyTorch on a real-world dataset (Breast Cancer Classification). It covers the full workflow — from data preprocessing to model evaluation — helping you understand how deep learning models are built and trained from scratch our focus not on Accuracy remember this | Jupyter Notebook | 0 | 2026-04-21 |
| [-Machine-Learning-with-Python-and-Scikit-Learn](https://github.com/Hamza-Shahid555/-Machine-Learning-with-Python-and-Scikit-Learn) | A comprehensive repository featuring implementations of key machine learning algorithms using Python and Scikit-Learn. Includes practical examples and real-world problem-solving scenarios for regression, classification, clustering, and more. Ideal for beginners and practitioners to learn, experiment, and apply ML concepts | Jupyter Notebook | 0 | 2026-04-20 |
| [project_with_Transformer](https://github.com/Hamza-Shahid555/project_with_Transformer) | applying A to Z concept of transformer i have done here in one of a unique project  | Jupyter Notebook | 0 | 2026-04-19 |
| [A-to-Z-Transformer](https://github.com/Hamza-Shahid555/A-to-Z-Transformer) | A comprehensive implementation and explanation of the Transformer architecture, covering self-attention, multi-head attention, positional encoding, and practical PyTorch implementation | Jupyter Notebook | 0 | 2026-04-17 |
| [research-Based-](https://github.com/Hamza-Shahid555/research-Based-) | nnU-Net v2 Kidney Stone Segmentation — Research Pipeline Automated kidney stone segmentation from CT images using nnU-Net v2's self-configuring deep learning framework on the KSSD2025 dataset. Features 5-fold cross-validation, comprehensive evaluation metrics (Dice, F1, IoU/Jaccard, Precision, Recall, Sensitivity, Specificity, HD95, AUC-ROC) | Jupyter Notebook | 0 | 2026-03-09 |
| [CropDoc-AI](https://github.com/Hamza-Shahid555/CropDoc-AI) | CropDoc is an end-to-end deep learning solution designed to bridge the gap between complex computer vision research and practical agricultural application. | Jupyter Notebook | 0 | 2026-02-03 |
| [HCI_project](https://github.com/Hamza-Shahid555/HCI_project) | Capstone-2 is a modern front-end web application built using React and Vite. It was developed as part of a capstone or portfolio project to demonstrate web development skills including responsive UI design, component-based architecture, and deployment readiness. | JavaScript | 0 | 2026-01-29 |
| [RNN-Sentiment-Analysis](https://github.com/Hamza-Shahid555/RNN-Sentiment-Analysis) | A comparative study of Sentiment Analysis on the IMDB dataset using SimpleRNN. This project contrasts the performance of raw Integer Encoding against Word Embeddings to demonstrate the importance of dense vector representations in Natural Language Processing. | Jupyter Notebook | 0 | 2025-12-14 |
| [Visualizing-Convolutional-Neural-Networks-CNNs-](https://github.com/Hamza-Shahid555/Visualizing-Convolutional-Neural-Networks-CNNs-) | This repository contains a complete implementation and analysis of Convolutional Neural Network (CNN) visualizations, demonstrating how deep learning models interpret and learn features from images. The notebook included explores multiple techniques to visualize internal CNN layers, feature maps, filters, and activation patterns. | Jupyter Notebook | 0 | 2025-12-12 |
| [Cat-Vs-Dog-Image-Classification-Project-](https://github.com/Hamza-Shahid555/Cat-Vs-Dog-Image-Classification-Project-) | 🐱🐶 Cat vs Dog Image Classification (CNN \| TensorFlow \| Keras)  This project builds a Convolutional Neural Network (CNN) that automatically classifies images as Cat or Dog using deep learning. The model is trained on the popular Microsoft Cats vs Dogs dataset and includes a complete workflow from data loading to final predictions. | Jupyter Notebook | 0 | 2025-12-12 |
<!-- PROJECTS-END -->

<div align="right">
<sub>Last synced automatically — see <a href="#">Actions</a> tab for run history</sub>
</div>

---

## 🛠️ Tech Arsenal

<div align="center">

**Languages & Environments**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)

**Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Data & Vision**

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

**Deployment**

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logo=gradio&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-00897B?style=for-the-badge&logo=google&logoColor=white)

**Core Strengths**

![Deep Learning](https://img.shields.io/badge/Deep_Learning-Expert-FF6F00?style=flat-square)
![Vision Transformers](https://img.shields.io/badge/Vision_Transformers-Advanced-9C27B0?style=flat-square)
![xLSTM & RNNs](https://img.shields.io/badge/xLSTM_Sequence_Models-Research-7928D1?style=flat-square)
![Zero-Shot AI](https://img.shields.io/badge/Zero--Shot_Learning-Frontier-1565C0?style=flat-square)
![End-to-End ML](https://img.shields.io/badge/End--to--End_Pipelines-Mastered-2CA02C?style=flat-square)
![Computer Vision](https://img.shields.io/badge/Computer_Vision-Proficient-E91E63?style=flat-square)

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Hamza-Shahid555&show_icons=true&count_private=true&include_all_commits=true&theme=dark&bg_color=0d1117&title_color=FF6F00&icon_color=FF6F00&text_color=c9d1d9&border_color=FF6F00&border_radius=12" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hamza-Shahid555&layout=compact&langs_count=6&theme=dark&bg_color=0d1117&title_color=FF6F00&text_color=c9d1d9&border_color=FF6F00&border_radius=12" />

<br/>

<img width="70%" src="https://streak-stats.demolab.com?user=Hamza-Shahid555&theme=dark&background=0d1117&border=FF6F00&ring=FF6F00&fire=FF6F00&currStreakLabel=FF6F00&sideLabels=FF6F00&dates=c9d1d9&border_radius=12" />

<br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Hamza-Shahid555&bg_color=0d1117&color=FF6F00&line=FF6F00&point=ffffff&area=true&area_color=FF6F0033&hide_border=false&border_color=FF6F00&radius=12)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🏆 GitHub Trophies

<div align="center">

[![Trophies](https://github-profile-trophy.vercel.app/?username=Hamza-Shahid555&theme=darkhub&column=7&margin-w=8&margin-h=8&no-bg=true)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 🤝 Let's Collaborate

<div align="center">

| Domain | What I Bring |
|---|---|
| 🧬 Sequence Modeling | xLSTM / RNN research, novel architectures, benchmarking |
| 📈 Time Series | Transformer zero-shot & transfer learning for finance |
| 🤟 Accessibility AI | Sign language CV, assistive technology |
| 🏭 ML Engineering | End-to-end pipelines, production packaging |
| 🧠 Deep Learning Research | Custom architectures, ablation studies, reproducible experiments |

<br/>

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hamza-shahid-56a008372)
&nbsp;&nbsp;
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hamza-Shahid555)

<br/>

> ⭐ **Star anything that sparks ideas — let's inspire each other and build the future of AI together.** 🌌

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:FF6F00,100:0d1117&height=130&section=footer&text=Building%20Tomorrow%2C%20One%20Model%20at%20a%20Time&fontSize=20&fontColor=ffffff&fontAlignY=65&animation=fadeIn" width="100%"/>

</div>
