<div align="center">

# Hi, I'm Ilay Rakotondravao 👋

### Applied AI Student · I build ML systems end to end and measure whether they actually work

<p>
  <img src="https://img.shields.io/badge/B.Sc.%20Applied%20AI-TH%20Rosenheim-0A66C2?style=flat-square" alt="B.Sc. Applied AI at TH Rosenheim" />
  <img src="https://img.shields.io/badge/Graduating-Nov%202027-555?style=flat-square" alt="Graduating November 2027" />
  <img src="https://img.shields.io/badge/Based%20in-Rosenheim%2C%20Germany-555?style=flat-square" alt="Based in Rosenheim, Germany" />
</p>

<p>
  <a href="https://ipelo.github.io"><img src="https://img.shields.io/badge/Portfolio-ipelo.github.io-111?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/ilay-rakotondravao-322412161/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

</div>

---

## 🧠 About Me

I like understanding things from the maths up, then building them properly: tested, evaluated honestly, and runnable by someone else.

- 🎓 Teaching assistant for **Mathematics 1** and **Linear Algebra** at TH Rosenheim
- 💼 **Open to internships and working student (Werkstudent) roles** in AI/ML engineering, data science, and software engineering
- 🌍 Malagasy (native) · English (B2) · French (B2) · German (B1, telc)

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### ⚖️ [GermanLawRAG](https://github.com/iPelo/domain-rag-agent)

Hybrid search and cited answers over German federal law (30 laws, 15,174 sections). Answers that cite unretrieved sources are rejected.

📊 96-question eval: dense retrieval beats plain hybrid on colloquial and multi-section questions; a cross-encoder reranker closes the gap (**nDCG@10 0.738**)

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Qdrant](https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square)
![bge-m3](https://img.shields.io/badge/-bge--m3%20·%20BM25-444?style=flat-square)
![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

</td>
<td width="50%" valign="top">

### ⚡ [EnergyPriceMLOps](https://github.com/iPelo/mlops-pipeline)

Day-ahead electricity price forecasting on German SMARD data. Reproducible DVC pipeline, served through FastAPI in a slim Docker image.

📊 6-month rolling backtest: LightGBM had the lowest error in every fold (**MAE 27.2 €/MWh** vs 32.9 for the previous-day baseline)

![LightGBM](https://img.shields.io/badge/-LightGBM-02569B?style=flat-square)
![Lightning](https://img.shields.io/badge/-PyTorch%20Lightning-792EE5?style=flat-square&logo=lightning&logoColor=white)
![DVC](https://img.shields.io/badge/-DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white)
![ONNX](https://img.shields.io/badge/-ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚆 [BahnDelayStory](https://github.com/iPelo/domain-data-story)

49.7M Deutsche Bahn stop events analysed with DuckDB, presented in a Streamlit dashboard.

📊 On a stable panel of 107 stations, trains 6+ min late rose from **14.4% (Jan) to 21.9% (Oct 2025)**; regional services caused two thirds of the extra late stops

![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![pandas](https://img.shields.io/badge/-pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

</td>
<td width="50%" valign="top">

### 🗄️ [bitcask-rs](https://github.com/iPelo/bitcask-rs)

A Bitcask-style key-value store in Rust using only the standard library: append-only log, CRC-checked records, hint files, background compaction, crash recovery, and a concurrent TCP server.

📊 Checked against a HashMap model with property tests that include **crashes and reopens**

![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![proptest](https://img.shields.io/badge/-proptest%20·%20criterion-444?style=flat-square)

</td>
</tr>
</table>

### 🔧 More Work

| Project | Description |
| --- | --- |
| 🛡️ [Tank Reinforcement Learning](https://github.com/iPelo/Tank-Reinforcement-Learning) | Hidden-information PPO tanks trained through self-play, opponent pools, and evaluation-driven progression |
| 📈 [Linear Regression](https://github.com/iPelo/Linear-Regression-from-Scratch) | From scratch with NumPy: gradient descent, normal equation, evaluation plots |
| 🎯 [Logistic Regression](https://github.com/iPelo/Logistic_Regression) | From scratch: sigmoid, cross-entropy, full visualisations |
| 🌳 [Decision Tree Classifier](https://github.com/iPelo/Decision-tree-Classifier) | From scratch: information gain, recursive splits |

---

## 🧰 Tech Stack

<div align="center">

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=python,rust,postgres,java,ts&theme=dark" alt="Python, Rust, SQL, Java, TypeScript" />

**ML / DL**<br/>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Lightning](https://img.shields.io/badge/Lightning-792EE5?style=for-the-badge&logo=lightning&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**LLM / Retrieval**<br/>
![RAG](https://img.shields.io/badge/RAG-444?style=for-the-badge)
![sentence-transformers](https://img.shields.io/badge/sentence--transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge)
![BM25](https://img.shields.io/badge/BM25%20·%20Reranking-444?style=for-the-badge)

**Data**<br/>
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=for-the-badge&logo=apacheparquet&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**MLOps / Backend**<br/>
<img src="https://skillicons.dev/icons?i=fastapi,docker,githubactions,git,linux&theme=dark" alt="FastAPI, Docker, GitHub Actions, Git, Linux" />
<br/>
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=for-the-badge&logo=dvc&logoColor=white)
![Hydra](https://img.shields.io/badge/Hydra-89B8CD?style=for-the-badge)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)

</div>

---

## 🎓 Teaching Experience

**Teaching Assistant · TH Rosenheim**

- **Mathematics 1** (Apr–Jul 2026): Led weekly 90-minute tutorials, supported students with exercises, graded quizzes
- **Linear Algebra** (Oct 2025–Jan 2026): Co-led tutorials, guided students through problem sets, tracked assessment results

---

<div align="center">

### 📫 Let's Connect

Looking for an **intern** or **Werkstudent** in AI / ML / Data Science? Feel free to reach out.

<a href="https://www.linkedin.com/in/ilay-rakotondravao-322412161/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://ipelo.github.io"><img src="https://img.shields.io/badge/Portfolio-111?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>

*"From first principles, or not at all."*

</div>
