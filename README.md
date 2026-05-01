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

---

## 🌌 Project Universe — Complete AI/ML Journey

> From classical algorithms to cutting-edge research. Each project is a milestone.

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

## 🤝 Open to Collaborate

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
