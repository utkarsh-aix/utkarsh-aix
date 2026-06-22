<div align="center">

<!-- NEURAL WAVE ANIMATION -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7B61FF,100:00FFA3&height=120&section=header&animation=fadeIn" width="100%"/>

<!-- ANIMATED NAME -->
<a href="https://github.com/utkarsh-aix">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=36&duration=3000&pause=1000&color=00FFA3&center=true&vCenter=true&width=600&height=70&lines=Utkarsh+Raj;AI+Engineer;Building+Real+AI+Products" alt="Typing SVG" />
</a>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=4000&pause=500&color=7B61FF&center=true&vCenter=true&width=700&lines=M.Tech+Applied+AI+%40+NFSU+Gandhinagar;RAG+Systems+·+LLM+Agents+·+ML+APIs+in+Production;Open+to+AI%2FML+Engineer+Roles" alt="Subtitle" />
</p>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-utkarshraj3535-7B61FF?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/utkarshraj3535)
[![GitHub](https://img.shields.io/badge/GitHub-utkarsh--aix-00FFA3?style=for-the-badge&logo=github&logoColor=black)](https://github.com/utkarsh-aix)
[![Email](https://img.shields.io/badge/Email-teamutkarsh22%40gmail.com-FF6B6B?style=for-the-badge&logo=gmail&logoColor=white)](mailto:teamutkarsh22@gmail.com)
[![Location](https://img.shields.io/badge/📍-Ahmedabad%2C_India-8B949E?style=for-the-badge)](https://github.com/utkarsh-aix)

</div>

---

<!-- WHAT I BUILD -->
<div align="center">
<h2>⚡ What I Build</h2>
</div>

<table align="center" width="100%">
<tr>
<td align="center" width="33%">

### 🤖 AI Agents
Deterministic multi-step agentic pipelines using LangGraph & Gemini. Built systems that automate clinical workflows, scrape e-commerce at scale, and make decisions with zero hallucination guarantees.

</td>
<td align="center" width="33%">

### 🔍 RAG Systems
Production-grade retrieval pipelines with FAISS, LangChain & HuggingFace. Offline embedding pipelines with sub-2s latency. Grounded responses — no hallucinations, no quota dependencies.

</td>
<td align="center" width="33%">

### 🚀 ML APIs
End-to-end ML systems deployed as Dockerized FastAPI services. XGBoost engines with SHAP explainability, sub-50ms inference, and 4-tier risk classification — production-ready from day one.

</td>
</tr>
</table>

---

<!-- IMPACT NUMBERS -->
<div align="center">
<h2>📊 By The Numbers</h2>
</div>

<div align="center">

| Metric | Value | Project |
|--------|-------|---------|
| 🎯 ROC-AUC Score | **0.972** | FraudShield Pro |
| 📋 Transactions Analysed | **590,000+** | FraudShield Pro |
| 🏥 Clinical Field Accuracy | **85.7%** | CliniDraft AI |
| 🔒 Hallucination Rate | **0%** | CliniDraft AI |
| ⚡ Inference Latency | **<50ms** | FraudShield Pro API |
| 📉 Manual Effort Reduced | **70%** | Petpooja LLM Pipeline |
| 📄 Documents Indexed | **50+** | RAG Knowledge Assistant |
| ☁️ Google Cloud Badges | **33** | Skills Boost |

</div>

---

<!-- FEATURED PROJECTS -->
<div align="center">
<h2>🔬 Featured Projects</h2>
</div>

<details open>
<summary><b>🏥 CliniDraft AI — Automated Clinical Discharge Summary Generation</b></summary>
<br/>

> *"Zero fabricated clinical values. 85.7% field extraction accuracy. 14 clinical section types."*

**The problem:** Doctors spend hours writing discharge summaries from scattered, degraded medical records.

**What I built:** A deterministic multi-step agentic pipeline using **Google Gemini 2.5 Flash** that ingests raw, multi-document patient records and outputs structured, clinical-grade discharge summaries.

**Engineering highlights:**
- 🔧 4-layer fallback OCR pipeline: `pdfplumber → PyPDF2 → Tesseract → EasyOCR → Gemini Vision`
- 🛡️ **Hallucination Shield** — cross-references all numeric medical tokens against source PDFs. 100% safety rate.
- 🔄 Doctor-correction feedback loop that reduces edit distance by **31.5%** over subsequent runs
- 📏 Avg Normalized Edit Distance: **0.0254**

`Python` `Google Gemini API` `Flask` `Tesseract OCR` `EasyOCR` `ReportLab`

[![Repo](https://img.shields.io/badge/View_Repo-00FFA3?style=flat-square&logo=github&logoColor=black)](https://github.com/utkarsh-aix/clinical-discharge-agent)

</details>

<details>
<summary><b>🛡️ FraudShield Pro — Enterprise Real-Time Fraud Detection</b></summary>
<br/>

> *"ROC-AUC 0.972. 91% Precision. 590K transactions. Sub-50ms inference."*

**What I built:** End-to-end fraud detection system with XGBoost + 445 engineered features, Explainable AI verdicts, and a production FastAPI service.

**Engineering highlights:**
- 📊 445 engineered features: time signals, card frequency, statistical aggregates, email domain risk binning
- 🧠 SHAP-powered explainability with human-readable verdicts (`Impossible Velocity`, `Extreme Amount`)
- ⚖️ Class imbalance handled via `scale_pos_weight (~27)` + threshold optimisation at 0.531
- 🐳 Dockerized FastAPI REST API with 4-tier risk classification

`XGBoost` `FastAPI` `Docker` `Scikit-learn` `SHAP` `Pandas`

[![Repo](https://img.shields.io/badge/View_Repo-00FFA3?style=flat-square&logo=github&logoColor=black)](https://github.com/utkarsh-aix/transaction-fraud-detection)

</details>

<details>
<summary><b>🔍 RAG Knowledge Assistant — Petpooja Domain</b></summary>
<br/>

> *"50+ documents. Sub-2s latency. Zero hallucinations. Fully offline embedding pipeline."*

**What I built:** Production-ready RAG chatbot using LangChain + FAISS + Gemini for domain-specific Q&A with a polished Streamlit UI.

**Engineering highlights:**
- 📦 Offline embedding pipeline with HuggingFace SentenceTransformers — no API quota dependency
- ⚡ Sub-2s response latency on local inference
- 🎨 Custom Streamlit UI: fixed input bar, auto-scroll, dark/light mode, chat export

`LangChain` `FAISS` `Google Gemini` `HuggingFace` `Streamlit`

[![Repo](https://img.shields.io/badge/View_Repo-00FFA3?style=flat-square&logo=github&logoColor=black)](https://github.com/utkarsh-aix/rag-based-petpooja-domain-assistant)

</details>

---

<!-- TECH STACK -->
<div align="center">
<h2>🛠️ Tech Stack</h2>
</div>

<div align="center">

**AI & LLMs**

![LangChain](https://img.shields.io/badge/LangChain-00FFA3?style=for-the-badge&logo=chainlink&logoColor=black)
![LangGraph](https://img.shields.io/badge/LangGraph-7B61FF?style=for-the-badge&logo=graphql&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD700?style=for-the-badge&logo=huggingface&logoColor=black)
![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

**ML & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=xgboost&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Deployment & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

</div>

---

<!-- GITHUB STATS -->
<div align="center">
<h2>📈 GitHub Stats</h2>
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=utkarsh-aix&show_icons=true&theme=dark&bg_color=0D1117&title_color=00FFA3&icon_color=7B61FF&text_color=E6EDF3&border_color=7B61FF&hide_border=false&count_private=true" height="180"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=utkarsh-aix&layout=compact&theme=dark&bg_color=0D1117&title_color=00FFA3&text_color=E6EDF3&border_color=7B61FF&langs_count=6" height="180"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=utkarsh-aix&theme=dark&background=0D1117&ring=00FFA3&fire=7B61FF&currStreakLabel=00FFA3&border=7B61FF" width="60%"/>
</div>

<br/>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=utkarsh-aix&bg_color=0D1117&color=00FFA3&line=7B61FF&point=00FFA3&area=true&hide_border=false&border_color=7B61FF" width="95%"/>
</div>

---

<!-- CERTIFICATIONS -->
<div align="center">
<h2>🏆 Certifications & Achievements</h2>
</div>

<div align="center">

| Certification | Issuer | Year |
|--------------|--------|------|
| Machine Learning with Python V2 | Coursera | 2026 |
| Machine Learning with Python | IBM | 2026 |
| Introduction to Statistics | Stanford University | 2026 |
| 5-Day AI Agents Intensive | Google × Kaggle | 2025 |
| Build AI Apps with Gemini & Imagen | Google | 2024 |
| **33 Google Cloud Skill Badges** | Google Skills Boost | 2024–2026 |

</div>

> ☁️ 19 courses · 157 hands-on labs · 133 lessons — covering Vertex AI, BigQuery, Generative AI & Cloud Security

---

<!-- CURRENTLY -->
<div align="center">
<h2>🔭 Currently</h2>
</div>

```python
utkarsh = {
    "role"        : "Data Science Trainee @ Petpooja",
    "building"    : ["LLM scrapers", "POS data pipelines", "AI agents"],
    "learning"    : ["LangGraph multi-agent systems", "Fine-tuning (LoRA/QLoRA)", "Vertex AI"],
    "seeking"     : "Full-time AI/ML Engineer role",
    "open_to"     : ["Remote", "Hybrid", "Ahmedabad", "Bangalore", "Mumbai"],
    "contact"     : "teamutkarsh22@gmail.com"
}
```

---

<!-- FOOTER -->
<div align="center">

<br/>

*"I don't just use AI tools — I build the systems underneath them."*

<br/>

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-7B61FF?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/utkarshraj3535)
[![Email](https://img.shields.io/badge/Hire_Me-00FFA3?style=for-the-badge&logo=gmail&logoColor=black)](mailto:teamutkarsh22@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FFA3,100:7B61FF&height=100&section=footer" width="100%"/>

</div>
