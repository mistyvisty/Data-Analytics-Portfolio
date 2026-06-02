# 📊 Data Analytics Portfolio
**Preeti Bhardwaj** | Data Analyst & ML Engineer | Python • SQL • Power BI • ML • GenAI

[![Portfolio](https://img.shields.io/badge/🌿_Portfolio-mistyvisty.github.io-2e7d32?style=flat-square)](https://mistyvisty.github.io)
[![Email](https://img.shields.io/badge/📧_Email-bhardwajpreeti357@gmail.com-D44638?style=flat-square)](mailto:bhardwajpreeti357@gmail.com)

---

## 🗂️ Projects

### 🩺 1. PCOS Detection & Risk Prediction
- **Domain:** Medical AI / Healthcare
- **Tech:** Python, scikit-learn, XGBoost, SHAP, SMOTE, ImbPipeline, 5-Fold CV
- **Highlights:** SMOTE inside ImbPipeline (zero data leakage), Threshold Tuning for 90%+ recall, SHAP Explainability, Outlier justification with medical references
- **Result:** Random Forest — Mean AUC 0.97 across 5 folds

🔗 [View Notebook](https://github.com/mistyvisty/Data-Analytics-Portfolio/blob/main/PCOS_Detection_Medical.ipynb)

---

### 🏦 2. Bank Customer Churn Prediction
- **Domain:** Banking / BFSI
- **Tech:** Python, XGBoost, SHAP, SHAP Beeswarm, ImbPipeline, SMOTE, 5-Fold CV
- **Highlights:** Removed 0.996-correlated feature (data leak), SMOTE inside ImbPipeline, Threshold tuning for business recall, SHAP Beeswarm shows feature impact direction
- **Result:** XGBoost — ROC-AUC 0.847, Mean CV AUC ~0.87 | Germany: 32.4% churn identified

🔗 [View Notebook](https://github.com/mistyvisty/Data-Analytics-Portfolio/blob/main/Bank_Customer_Churn_Prediction.ipynb)

---

### 🛒 3. Superstore Sales Analysis (SQL + Power BI)
- **Domain:** Retail / E-Commerce
- **Tech:** Python, SQLite, 12 SQL queries, Power BI Dashboard
- **Highlights:** Window Functions, Discount impact analysis, Interactive Power BI dashboard with map
- **Result:** Identified $125K in annual losses from high discounts — recommended 20% discount cap

🔗 [View Notebook](https://github.com/mistyvisty/Data-Analytics-Portfolio/blob/main/Superstore_Sales_SQL_Analysis.ipynb)

**Dashboard Preview:**

![Superstore Dashboard](Superstore_PowerBI_Dashboard.png)

---

### 🤖 4. Medical RAG Assistant — PCOS Clinical Literature
- **Domain:** Medical AI / Generative AI
- **Tech:** Python, LangChain, FAISS, HuggingFace (MiniLM), Groq (LLaMA 3.1), Google Colab
- **Highlights:** RAG pipeline grounded in real PCOS research papers, hallucination-aware prompt (refuses to answer if context is missing), source citations with page numbers on every answer
- **Result:** Answers clinical PCOS questions with cited evidence from uploaded research papers

🔗 [View Notebook](https://github.com/mistyvisty/Data-Analytics-Portfolio/blob/main/Medical_RAG_Assistant.ipynb)

---

### 📊 5. AI CSV Analyst — Chat with Your Data
- **Domain:** Generative AI / Data Analysis
- **Tech:** Python, Streamlit, Groq (LLaMA 3.1), Pandas, Matplotlib
- **Highlights:** Upload any CSV and ask questions in plain English, AI generates insights and auto-renders charts, deployed live on Streamlit Cloud
- **Result:** Fully deployed live app — anyone can use it with their own CSV

🔗 [View Repo](https://github.com/mistyvisty/ai_csv_analyst) · 🚀 [Live Demo](https://preeti-ai-csv-analyst.streamlit.app/)

---

## 🔧 Skills

**Languages:** Python, SQL

**ML Libraries:** scikit-learn, XGBoost, SHAP, imbalanced-learn

**GenAI & RAG:** LangChain, FAISS, HuggingFace Embeddings, Groq API, LLaMA 3.1

**Deployment:** Streamlit Cloud, Google Colab

**Visualization:** matplotlib, seaborn, Power BI, Plotly

**Techniques:** EDA, Feature Engineering, SMOTE Pipeline, Cross Validation, SHAP, Threshold Tuning, RAG, Prompt Engineering
