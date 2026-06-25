# 🛡️ FinShield AI – AI-Powered Financial Crime Intelligence Platform

## 📌 Overview

**FinShield AI** is an end-to-end Anti-Money Laundering (AML) and Financial Crime Intelligence Platform that leverages **Machine Learning, Graph Analytics, Explainable AI, and Risk Scoring** to identify suspicious financial transactions and detect potential money laundering activities.

The platform analyzes transaction behavior, identifies complex laundering patterns such as **Fan-In, Fan-Out, Circular Transactions, and Mule Accounts**, and provides investigators with explainable insights through SHAP-based visualizations and AI-generated investigation reports.

---

# 🚀 Key Features

* 🔍 Anti-Money Laundering (AML) Detection
* 🤖 XGBoost-Based Machine Learning Model
* 📊 Explainable AI using SHAP
* ⚖️ Risk Scoring Engine
* 🌐 Graph-Based Transaction Network Analysis
* 🔄 Fan-In & Fan-Out Pattern Detection
* 🔁 Circular Transaction Detection
* 👤 Mule Account Detection
* 📈 Interactive Dashboard
* 📄 AI Investigation Report Generation
* ☁️ Deployable Streamlit Web Application

---

# 🧠 Technologies Used

### Programming Language

* Python

### Machine Learning

* XGBoost
* Scikit-learn
* SMOTE (Imbalanced-Learn)

### Explainable AI

* SHAP

### Data Analysis

* Pandas
* NumPy

### Visualization

* Matplotlib
* Plotly
* PyVis

### Graph Analytics

* NetworkX

### Web Framework

* Streamlit
* FastAPI

### Version Control

* Git & GitHub

---

# 📂 Project Structure

```
FinShield-AI/

│
├── data/
├── notebooks/
├── models/
├── dashboard/
├── backend/
├── reports/
├── assets/
├── requirements.txt
└── README.md
```

---

# 📒 Project Workflow (11 Notebooks)

## 📓 Notebook 1 — Data Understanding & Cleaning

* Load IBM AML Dataset
* Explore dataset structure
* Handle missing values
* Remove duplicates
* Correct data types
* Data quality checks

---

## 📓 Notebook 2 — Exploratory Data Analysis (EDA)

* Fraud vs Normal Analysis
* Transaction Distribution
* Payment Method Analysis
* Currency Analysis
* Time-based Analysis
* Correlation Analysis
* Visualizations

---

## 📓 Notebook 3 — Data Preprocessing

* Label Encoding
* One-Hot Encoding
* Feature Scaling
* Train-Test Split
* Feature Selection
* SMOTE for Class Balancing

---

## 📓 Notebook 4 — Feature Engineering

* Transaction Count
* Total Amount Sent
* Total Amount Received
* Average Transaction Amount
* Fan-In Features
* Fan-Out Features
* Velocity Features
* Transaction Frequency
* Account Behaviour Features

---

## 📓 Notebook 5 — Graph Analytics & Network Intelligence

* Build Transaction Graph
* Graph Construction using NetworkX
* Degree Analysis
* Centrality Measures
* Community Detection
* Circular Transaction Detection
* Fan-In Detection
* Fan-Out Detection
* Graph Visualization

---

## 📓 Notebook 6 — Risk Scoring Engine

* Rule-Based Risk Engine
* Dynamic Risk Calculation
* Risk Categories
* High-Risk Account Ranking
* Suspicious Pattern Aggregation

---

## 📓 Notebook 7 — XGBoost AML Detection Model

* Train XGBoost Classifier
* Hyperparameter Tuning
* Prediction
* Model Evaluation
* Precision
* Recall
* F1 Score
* ROC-AUC Analysis

---

## 📓 Notebook 8 — Explainable AI (SHAP)

* SHAP Explainer
* Global Feature Importance
* Local Prediction Explanation
* Waterfall Plots
* Force Plots
* Decision Visualization

---

## 📓 Notebook 9 — AI Investigation Report Generation

* Automated Investigation Summary
* Suspicious Pattern Explanation
* Risk Interpretation
* Case Summary Generation
* AI-Based Narrative Report

---

## 📓 Notebook 10 — Streamlit Dashboard

* Upload Transaction Dataset
* Risk Dashboard
* High-Risk Alerts
* Network Visualization
* Account Investigation
* SHAP Visualizations
* AI Report Viewer

---

## 📓 Notebook 11 — Deployment & Productionization

* FastAPI Integration
* Streamlit Integration
* Model Serialization
* GitHub Repository Setup
* Streamlit Cloud Deployment
* Production Workflow
* End-to-End Testing

---

# 🏗️ System Architecture

```
User Upload CSV
        │
        ▼
Streamlit Dashboard
        │
        ▼
FastAPI Backend
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Graph Analytics
        │
        ▼
Risk Scoring Engine
        │
        ▼
XGBoost Prediction
        │
        ▼
Explainable AI (SHAP)
        │
        ▼
AI Investigation Report
        │
        ▼
Interactive Dashboard
```

---

# 📊 Machine Learning Pipeline

```
IBM AML Dataset
      │
      ▼
Data Cleaning
      │
      ▼
EDA
      │
      ▼
Preprocessing
      │
      ▼
Feature Engineering
      │
      ▼
SMOTE
      │
      ▼
XGBoost Model
      │
      ▼
SHAP Explainability
      │
      ▼
Risk Scoring
      │
      ▼
Prediction
```

---

# 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix

---

# 🎯 Future Enhancements

* Real-Time Transaction Monitoring
* Kafka Streaming Pipeline
* Graph Neural Networks (GNN)
* Large Language Model (LLM) Investigator
* Neo4j Graph Database Integration
* Cloud Deployment on AWS
* Real-Time Alert Notification System

---

# 🎓 Learning Outcomes

This project demonstrates practical implementation of:

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Machine Learning
* Explainable AI
* Graph Analytics
* Risk Intelligence
* Financial Crime Detection
* Dashboard Development
* API Development
* Cloud Deployment

---

# 👩‍💻 Developed By

**Tanya Jain**

**Project:** FinShield AI – AI-Powered Financial Crime Intelligence Platform

Final Year B.Tech (Data Science)

---

## ⭐ If you found this project useful, consider giving it a Star!
