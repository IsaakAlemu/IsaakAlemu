<div align="center">

# Hi, I'm Isaak Alemu 👋
### Computer Science Student @ Addis Ababa University · Aspiring AI/ML Engineer, focused on NLP

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Isaak_Alemu-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/isaak-alemu-492414329)
[![GitHub](https://img.shields.io/badge/GitHub-IsaakAlemu-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/IsaakAlemu)
[![Email](https://img.shields.io/badge/Gmail-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alemuisaak@gmail.com)

<p align="center">
  <b>Building machine learning systems end to end: retrieval, graph models, recommenders, and tested APIs, with a focus on Amharic NLP.</b><br/>
  INSA Ethiopia Summer Camp (Emerging AI Track) · Stanford / DeepLearning.AI Machine Learning Specialization
</p>

</div>

---

### 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">🤖 <a href="https://github.com/IsaakAlemu/amharic-rag-assistant">Amharic RAG: Hybrid Retrieval for a Low-Resource Language</a></h3>
      <p><b>ChromaDB · BM25 · Reciprocal Rank Fusion · Streamlit · Gemini / Groq</b></p>
      <ul>
        <li>Hybrid retrieval combining dense embeddings with a custom Ethiopic BM25 via Reciprocal Rank Fusion: Hit@1 77.51% and Hit@3 92.10% on a 329-question holdout (dense-only Hit@1: 72.64%).</li>
        <li>Bilingual prompt-injection defense, grounded refusal on out-of-scope questions, and an honestly documented re-ranker investigation (tested, too slow on CPU, left disabled).</li>
        <li>Live demo with streaming answers and inline source citations; 29 tests and CI.</li>
      </ul>
      <p align="right">
        <a href="https://amharic-rag-assistant.streamlit.app/"><b>Live Demo →</b></a> · <a href="https://github.com/IsaakAlemu/amharic-rag-assistant"><b>Repository →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">🕸️ <a href="https://github.com/IsaakAlemu/bitcoin-aml-graph-detection">Bitcoin AML: Graph Neural Networks vs Tabular Models</a></h3>
      <p><b>PyTorch Geometric · GCN · XGBoost · NetworkX · KS Drift Test</b></p>
      <ul>
        <li>Benchmark on the Elliptic Bitcoin dataset (203k transactions, 234k edges, 49 time steps) with a strict temporal split.</li>
        <li>Compared tabular XGBoost, hand-built graph features, and a 2-layer GCN.</li>
        <li>Diagnosed a collapse at time step 43 as distribution shift (KS test p &lt; 10⁻⁶⁵), with model confidence falling from 0.933 to 0.040.</li>
      </ul>
      <p align="right">
        <a href="https://github.com/IsaakAlemu/bitcoin-aml-graph-detection"><b>Explore Repository →</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">🎬 <a href="https://github.com/IsaakAlemu/two-tower-movie-recommender">Two-Tower Movie Recommender</a></h3>
      <p><b>PyTorch · FAISS · FastAPI · Streamlit · Docker</b></p>
      <ul>
        <li>Two-tower retrieval model on MovieLens 100K with a per-user temporal split: Hit@10 of 56.6% vs 27.7% for a from-scratch matrix factorization baseline and 39.3% for popularity, under the same protocol.</li>
        <li>Documented the six bugs fixed on the way from a 2.54% first run, including loss bias, false negatives, vocabulary leakage, and an unfair baseline.</li>
        <li>FAISS index served through FastAPI with a Streamlit demo; tests, Docker, and CI.</li>
      </ul>
      <p align="right">
        <a href="https://github.com/IsaakAlemu/two-tower-movie-recommender"><b>Explore Repository →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">🛡️ <a href="https://github.com/IsaakAlemu/fraud-anomaly-detection">Fraud Detection: Dual-Model API with MLOps Tooling</a></h3>
      <p><b>MLflow · Optuna · Evidently AI · FastAPI · Docker</b></p>
      <ul>
        <li>Risk API comparing a from-scratch Gaussian anomaly model against a supervised baseline, with honest benchmarking (PR-AUC, ROC-AUC).</li>
        <li>MLflow experiment tracking, Optuna hyperparameter tuning, and Evidently AI drift monitoring.</li>
        <li>Containerized and CI-tested, 18/18 tests passing.</li>
      </ul>
      <p align="right">
        <a href="https://github.com/IsaakAlemu/fraud-anomaly-detection"><b>Explore Repository →</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">🕵️ <a href="https://github.com/IsaakAlemu/financial-risk-triage-agent">Financial Risk Triage Agent</a></h3>
      <p><b>LangGraph · ReAct Agent · Pydantic v2 · SQLite</b></p>
      <ul>
        <li>Cyclic LangGraph ReAct agent that investigates alerts with tool calls across KYC, transaction-velocity, and sanctions data.</li>
        <li>Dual-mode design: live LLM reasoning (Gemini / Groq) with a deterministic fallback scoring engine that needs no API.</li>
        <li>Pydantic-validated verdicts with auditable JSON execution traces; 23/23 tests passing.</li>
      </ul>
      <p align="right">
        <a href="https://github.com/IsaakAlemu/financial-risk-triage-agent"><b>Explore Repository →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">👁️ <a href="https://github.com/IsaakAlemu/amharic-character-recognition">Amharic Handwritten Character Recognition</a></h3>
      <p><b>TensorFlow / Keras · CNN · NumPy · scikit-learn</b></p>
      <ul>
        <li>CNN reaching 95.8% test accuracy on the 33 base Fidel characters (3-seed range 95.4–96.5%), vs 86.3% for a dense network and 82.4% for logistic regression.</li>
        <li>Forward pass first written by hand in NumPy; error analysis traced the main confusion (ደ → ጸ) through a manual review of 342 images, and two class-imbalance fixes were tested.</li>
        <li>Extended to the full 238-class syllabary: 86.86% (single seed).</li>
      </ul>
      <p align="right">
        <a href="https://github.com/IsaakAlemu/amharic-character-recognition"><b>Explore Repository →</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">🏡 <a href="https://github.com/IsaakAlemu/addis-ababa-house-rental-prediction">Addis Ababa Rent Price Prediction</a></h3>
      <p><b>Selenium · CatBoost · scikit-learn · Pandas · 5-fold CV</b></p>
      <ul>
        <li>Scraped 5,046 listings across 10 sub-cities (99.98% success) with a resumable two-stage Selenium pipeline, then cleaned them with per-sub-city outlier detection.</li>
        <li>CatBoost model with R² of 0.826 ± 0.006 (5-fold CV, log scale) and MAE of about 40,800 ETB.</li>
        <li>Per-location results and limitations documented openly.</li>
      </ul>
      <p align="right">
        <a href="https://github.com/IsaakAlemu/addis-ababa-house-rental-prediction"><b>Explore Repository →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">🎨 <a href="https://github.com/IsaakAlemu/color-palette-api">Color Palette Extraction API</a></h3>
      <p><b>FastAPI · NumPy · Pillow · Docker · pytest</b></p>
      <ul>
        <li>K-means implemented from scratch (vectorized, multi-restart) to extract dominant color palettes from uploaded images.</li>
        <li>Also returns a web-optimized compressed image (73–77% size reduction on test photos).</li>
        <li>24 tests, including regression tests for bugs found along the way; Dockerized.</li>
      </ul>
      <p align="right">
        <a href="https://github.com/IsaakAlemu/color-palette-api"><b>Explore Repository →</b></a>
      </p>
    </td>
  </tr>
</table>

---

### 🗂️ More Projects

- **📧 [Spam Detection](https://github.com/IsaakAlemu/spam-email-detection)**: SMS/email classifier comparing Naive Bayes, Logistic Regression, and Linear SVM on TF-IDF features; Linear SVM won (F1 0.908) and is served in a Streamlit app.
- **☕ [Cafeteria Management System](https://github.com/IsaakAlemu/mini-cafeteria-project)**: Java and SQL Server course project covering menu management, order processing, and billing.

---

### 🛠️ Technical Stack & Tools

<p align="center">
  <b>Machine Learning & Deep Learning</b><br/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch_Geometric-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-025B8C?style=flat-square" />
  <img src="https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square" />
  <img src="https://img.shields.io/badge/LightGBM-2E7D32?style=flat-square" />
  <img src="https://img.shields.io/badge/NetworkX-000000?style=flat-square" />
</p>

<p align="center">
  <b>Generative AI, NLP & Search</b><br/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square" />
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square" />
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Groq_API-F55036?style=flat-square" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
</p>

<p align="center">
  <b>Backend, MLOps & Tools</b><br/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Optuna-3B6FB6?style=flat-square" />
  <img src="https://img.shields.io/badge/Evidently_AI-ED0500?style=flat-square" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
</p>

---

### 📈 Top Languages

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=IsaakAlemu&layout=compact&hide=html,jupyter%20notebook&theme=tokyonight&hide_border=true" alt="Top languages" />
</div>

---

### 🎓 Education & Certifications

- **B.Sc. in Computer Science**, Addis Ababa University (expected 2028)
- **INSA Ethiopia Summer Camp**, Emerging Track: AI Engineering
- **Machine Learning Specialization**, *DeepLearning.AI & Stanford Online (Coursera)* ✅
  Regression and classification, neural networks, decision trees, unsupervised learning, recommender systems, and reinforcement learning
- **5M Ethiopian Coders (Udacity)**: AI Fundamentals and Data Analysis Fundamentals
- **DeepLearning.AI short courses**: text embeddings, advanced RAG, LangChain for data chat, and prompt engineering

---

<div align="center">
  <sub>⭐ Open to machine learning internships, research collaborations, and software engineering opportunities.</sub>
</div>
