<h1 align="center">Hi 👋 I'm Divy Shah</h1>

## 💫 About Me
I’m a third-year **Mathematics student with a Computer Science minor at the University of Waterloo**, interested in building **high-performance systems and algorithms used in modern finance and hedge funds**.

I enjoy working at the intersection of:
- **Computer systems**
- **data-driven decision making**
- **quantitative problem solving**

My focus is on applying **core CS concepts (algorithms, systems, data pipelines)** to **financial technology and quantitative engineering**.

---

## 🚀 Current Focus
- 📊 Designing and implementing **data pipelines for financial and market data**
- ⚙️ Exploring **algorithmic and systems-level problems** relevant to trading and risk
- 🤖 Applying **machine learning and statistical models** to real-world datasets
- 🧠 Strengthening fundamentals in **algorithms, data structures, and performance**
- 🗂️ Actively developing a **full-stack file management system**, with emphasis on **SDLC best practices** such as API design, authentication, database modeling, testing, CI/CD, and cloud deployment

---

## 🚀 Featured Projects

### [F1 Race Prediction ML System](https://github.com/divyshah03/f1-race-prediction-machine-learning-system)
A machine learning pipeline that predicts Formula 1 race finishing order from qualifying results, historical telemetry pulled via FastF1, and engineered race-weekend features. Benchmarks Gradient Boosting, XGBoost, LightGBM, and CatBoost against a naive "predict qualifying order" baseline using a time-aware walk-forward split, with SHAP-based explainability, MLflow experiment tracking, and a Dockerized FastAPI serving layer.
**Stack:** Python, pandas, scikit-learn, XGBoost, LightGBM, CatBoost, FastF1, SHAP, MLflow, FastAPI, Docker
**Result:** Best model (Gradient Boosting) cut prediction error by ~68% vs. the baseline (2.60s MAE vs. 8.01s), from a reproducible walk-forward benchmark you can regenerate with `python -m f1_predictor.unified`.

### [Agentic RAG System with Telemetry & Evaluation Harness](https://github.com/divyshah03/agentic-rag-system-with-telemetry-and-evaluation-harness)
A PDF question-answering RAG system built around measuring and improving retrieval quality: hybrid BM25 + dense retrieval fused with Reciprocal Rank Fusion, a local cross-encoder re-ranking stage, and confidence-gated agentic query routing that widens the retrieval pool when the top result looks unreliable. Includes a standalone evaluation harness that scores every pipeline change against a ground-truth question set.
**Stack:** Python, FastAPI, Inngest, Qdrant, OpenAI (embeddings + LLM), LlamaIndex, BM25, ONNX cross-encoder (fastembed), Streamlit
**Result:** The evaluation harness traced the pipeline's one remaining accuracy gap to a single reproducible chunking bug — a list item getting orphaned from its section header — closed by joining PDF pages before splitting rather than by retrieval tuning.

### [Secure Cloud File Management Platform](https://github.com/divyshah03/secure-cloud-file-management-platform)
A file-sharing platform with per-file RBAC (owner/editor/viewer roles enforced at the service layer), expiring anonymous share links, direct-to-S3 transfer via presigned URLs, and real ClamAV malware scanning on every upload (a hand-rolled INSTREAM client, not a stub), backed by a full audit trail.
**Stack:** Spring Boot 3 (Java 17), Spring Security/JWT, PostgreSQL + Flyway, AWS SDK v2 (S3 + Presigner), MinIO, ClamAV, React 18, Chakra UI, Vite
**Result:** A k6 load test showed presigned-URL direct-to-storage transfer cuts average request latency ~58% vs. proxying bytes through the backend (74.3ms → 30.9ms).

### [C++ Terminal Chess Engine](https://github.com/divyshah03/cpp-terminal-chess-engine)
A terminal-based chess engine in modern C++20 with full rules support — check/checkmate/stalemate detection, castling, en passant, pawn promotion, undo, and a custom board setup mode — plus an optional X11 graphical board and four heuristic-based computer difficulty levels, from random legal moves up to threat-aware, capture-seeking play.
**Stack:** C++20, Makefile, optional X11

---

## 🛠 Technical Interests
- Backend & systems programming  
- Quantitative data analysis  
- Scalable services and low-latency systems  
- Financial infrastructure and analytics

---


## 🌐 Connect with me:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/divyshah03)


# 💻 Tech Stack:
Languages: 
![Python](https://img.shields.io/badge/python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white) 
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white) 
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) 
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/sql-%2307405e.svg?style=for-the-badge&logo=postgresql&logoColor=white) 
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) 
![CSS](https://img.shields.io/badge/css-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) 
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) 
![VHDL](https://img.shields.io/badge/VHDL-%234C709D.svg?style=for-the-badge&logo=V&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)

Developer Tools: 
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) 
![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) 

Data/ML:
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=for-the-badge&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge&logoColor=black)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)


Libraries/Frameworks: 
![AWS](https://img.shields.io/badge/AWS-%23232F3E.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) 
![ReactJS](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) 
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) 
![Spring Boot](https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot) 
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) 
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white) 
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) 
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-1B1B1B?style=for-the-badge&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
