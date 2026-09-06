<div align="center">

# Hi, I'm Isaak Alemu 👋
### Computer Science Student @ Addis Ababa University · AI & Machine Learning Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Isaak_Alemu-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/isaak-alemu-492414329)
[![GitHub](https://img.shields.io/badge/GitHub-IsaakAlemu-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/IsaakAlemu)
[![Email](https://img.shields.io/badge/Gmail-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:isaak.alemu.cs@gmail.com)

<p align="center">
  <b>Building production-grade Machine Learning, Graph Neural Networks, and Domain-Specific Generative AI systems.</b><br/>
  INSA Ethiopia Summer Camp (Emerging AI Track) · Stanford / DeepLearning.AI Machine Learning Specialization
</p>

</div>

---

### 🚀 Featured AI & Machine Learning Systems

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">🌾 <a href="https://github.com/IsaakAlemu/amharic-agri-advisor">Amharic Agricultural Advisory Assistant</a></h3>
      <p><b>Hybrid RAG (Dense + BM25 + RRF) · Guardrails · Groq LLM · Streamlit</b></p>
      <ul>
        <li>Bilingual (Amharic/English) RAG system delivering agronomic advice across <b>9 Ethiopian agricultural domains</b> (Teff, Maize, Coffee, Wheat, etc.).</li>
        <li>Architected <b>Hybrid RRF Retrieval</b> (<code>multilingual-e5-small</code> + BM25 with Ethiopic normalization), prompt-injection guards, and out-of-scope crop refusal.</li>
        <li>Achieved <b>96.3% Top-3 retrieval accuracy</b> and 100% out-of-scope refusal on held-out naturalistic benchmark evaluation.</li>
      </ul>
      <p align="right">
        <a href="https://github.com/IsaakAlemu/amharic-agri-advisor"><b>Explore Repository →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">🕸️ <a href="https://github.com/IsaakAlemu/Money-laundering-detection-on-a-transaction-graph">Bitcoin AML & Graph Neural Networks</a></h3>
      <p><b>PyTorch Geometric · GCN · XGBoost · NetworkX · Drift Diagnosis</b></p>
      <ul>
        <li>Comparative benchmark on the <b>Elliptic Data Set</b> (203k transactions, 234k edges across 49 discrete time steps).</li>
        <li>Evaluated Tabular XGBoost against hand-built topological graph features and 2-layer Graph Convolutional Networks (GCNs).</li>
        <li>Diagnosed adversarial temporal distribution shift at Step 43 ($p < 10^{-65}$ KS test) and model confidence collapse ($0.933 \to 0.040$).</li>
      </ul>
      <p align="right">
        <a href="https://github.com/IsaakAlemu/Money-laundering-detection-on-a-transaction-graph"><b>Explore Repository →</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">🛡️ <a href="https://github.com/IsaakAlemu/fraud-anomaly-detection">FastAPI Fraud & Gaussian Anomaly Engine</a></h3>
      <p><b>FastAPI · Docker · Pydantic · Density Estimation · Pytest</b></p>
      <ul>
        <li>Dual-model risk scoring API combining an unsupervised <b>from-scratch Gaussian density estimator</b> in log-space with a supervised baseline classifier.</li>
        <li>Automated artifact serialization, custom probability thresholds, and full unit/integration test suite.</li>
        <li>Containerized for production deployment with Docker and interactive Swagger OpenAPI documentation.</li>
      </ul>
      <p align="right">
        <a href="https://github.com/IsaakAlemu/fraud-anomaly-detection"><b>Explore Repository →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">🤖 <a href="https://github.com/IsaakAlemu/amharic-rag-assistant">Amharic RAG AI Assistant</a></h3>
      <p><b>LangChain · ChromaDB · Vector Search · Low-Resource NLP</b></p>
      <ul>
        <li>End-to-end Retrieval-Augmented Generation (RAG) pipeline tailored for <b>Amharic language</b> documents.</li>
        <li>Custom text chunking, multilingual semantic vector embeddings, and contextual question-answering with LLMs.</li>
        <li>Interactive Streamlit UI for grounded document search and real-time response generation.</li>
      </ul>
      <p align="right">
        <a href="https://github.com/IsaakAlemu/amharic-rag-assistant"><b>Explore Repository →</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">👁️ <a href="https://github.com/IsaakAlemu/amharic-character-recognition">Amharic Script OCR & Vision</a></h3>
      <p><b>PyTorch / TensorFlow · CNNs · Computer Vision · Image Processing</b></p>
      <ul>
        <li>Deep learning classification pipeline for Ethiopic / Fidel handwritten and printed character recognition.</li>
        <li>Custom image pre-processing, binarization, noise reduction, and Convolutional Neural Network architectures.</li>
      </ul>
      <p align="right">
        <a href="https://github.com/IsaakAlemu/amharic-character-recognition"><b>Explore Repository →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">🏡 <a href="https://github.com/IsaakAlemu/addis-ababa-house_rental-prediction">Addis Ababa Rent Price Prediction</a></h3>
      <p><b>Scikit-Learn · XGBoost · Feature Engineering · Pandas</b></p>
      <ul>
        <li>Real estate valuation regression model estimating residential rental prices across Addis Ababa sub-cities.</li>
        <li>Geospatial cleaning, localized feature engineering, outlier treatment, and cross-validated ensemble models.</li>
      </ul>
      <p align="right">
        <a href="https://github.com/IsaakAlemu/addis-ababa-house_rental-prediction"><b>Explore Repository →</b></a>
      </p>
    </td>
  </tr>
</table>

---

### 📊 Data Intelligence, APIs & Software Systems

- **🎨 [Color Palette API](https://github.com/IsaakAlemu/color-palette-api)**: FastAPI microservice providing color extraction, palette generation algorithms, and structured JSON schemas for design workflows.
- **🎬 [Netflix Content Intelligence](https://github.com/IsaakAlemu/netflix-content-intelligence)**: SQL + Python exploratory data analysis uncovering global catalog growth trends, director collaboration networks, and genre distribution shifts.
- **🛒 [Retail Customer & Sales Analytics](https://github.com/IsaakAlemu/customer_sales_analysis)**: Customer transaction analytics, RFM segmentation, and seasonal purchase trends across 500k+ records using Pandas and Matplotlib.
- **📧 [NLP Spam Email Classifier](https://github.com/IsaakAlemu/spam-email-detection)**: Text preprocessing, TF-IDF vectorization, and Naive Bayes/SVM classification for spam filtering.
- **☕ [Cafeteria Management System](https://github.com/IsaakAlemu/mini-cafeteria-project)**: Java Object-Oriented application implementing menu state, order processing, and transactional billing logic.

---

### 🛠️ Technical Stack & Tools

<p align="center">
  <b>Machine Learning & Deep Learning</b><br/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch_Geometric-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-025B8C?style=flat-square" />
  <img src="https://img.shields.io/badge/LightGBM-2E7D32?style=flat-square" />
  <img src="https://img.shields.io/badge/NetworkX-000000?style=flat-square" />
</p>

<p align="center">
  <b>Generative AI, NLP & Search</b><br/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square" />
  <img src="https://img.shields.io/badge/Groq_API-F55036?style=flat-square" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
</p>

<p align="center">
  <b>Backend, Data Engineering & Tools</b><br/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
</p>

---

### 📈 GitHub Activity & Stats

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=IsaakAlemu&theme=tokyonight&hide_border=true" alt="Isaak's GitHub Streak" />
</div>

---

### 🎓 Education & Certifications

- **B.Sc. in Computer Science** — Addis Ababa University (AAU)
- **INSA Ethiopia Summer Camp** — Emerging Track: AI Engineering
- **Machine Learning Specialization** — *DeepLearning.AI & Stanford Online (Coursera)*
  - ✅ **Course 1**: *Supervised Machine Learning: Regression and Classification* (Linear/Logistic Regression, Cost Functions, Regularization)
  - ✅ **Course 2**: *Advanced Learning Algorithms* (Multi-layer Neural Networks, Decision Trees, Random Forests, XGBoost)
  - ✅ **Course 3**: *Unsupervised Learning, Recommenders, Reinforcement Learning* (Anomaly Detection, Recommender Systems, PCA, Reinforcement Learning)

---

<div align="center">
  <sub>⭐ Open to machine learning internships, research collaborations, and software engineering opportunities.</sub>
</div>
