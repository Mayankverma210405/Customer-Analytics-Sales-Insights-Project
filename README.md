# 📊 Customer Analytics & Sales Insights Platform

An end-to-end **Customer Analytics and Machine Learning platform** designed to analyze customer behavior, uncover revenue drivers, predict customer conversion, and segment customers for actionable business insights.

This project simulates a **real-world production analytics system** used by Sales and Marketing teams to make data-driven decisions.

---

## 🚀 Project Overview

Modern businesses collect large volumes of customer and sales data but often fail to convert it into meaningful insights.  
This project addresses that challenge by building a **fully deployed analytics pipeline** that transforms raw data into business intelligence.

The platform:
- Ingests raw customer and sales data
- Stores structured data in a relational database
- Performs analytics and feature engineering
- Trains machine learning models for prediction and segmentation
- Serves insights through APIs and dashboards

---

## 🧠 Key Features

- Automated data ingestion and cleaning pipeline  
- SQL-based analytics for revenue and customer behavior  
- Feature engineering using RFM (Recency, Frequency, Monetary) analysis  
- Customer conversion prediction using classification models  
- Revenue prediction using regression models  
- Customer segmentation using K-Means clustering  
- REST APIs for real-time predictions  
- Business-ready dashboards for decision-making  

---

## 🏗️ System Architecture

Raw Data (CSV / API)
↓
Data Ingestion Layer
↓
Relational Database (PostgreSQL / MySQL)
↓
ETL & Feature Engineering
↓
Machine Learning Models
↓
Saved Model Artifacts
↓
FastAPI Backend
↓
Dashboard (Streamlit / Excel)

yaml
Copy code

---

## 🛠️ Tech Stack

### Data & Backend
- Python
- Pandas, NumPy
- SQL (PostgreSQL / MySQL)
- SQLAlchemy

### Machine Learning
- Scikit-learn
- Joblib

### API & Visualization
- FastAPI
- Streamlit / Excel Dashboards

### DevOps & Deployment
- Docker
- GitHub
- Render / Railway / AWS EC2

---

## 📁 Project Structure

customer-analytics-platform/
│
├── data/
│ ├── raw/
│ ├── processed/
│
├── database/
│ ├── schema.sql
│ ├── seed.sql
│
├── etl/
│ ├── ingest.py
│ ├── clean.py
│ ├── features.py
│
├── models/
│ ├── train_classification.py
│ ├── train_regression.py
│ ├── train_clustering.py
│ ├── artifacts/
│
├── api/
│ ├── main.py
│ ├── routes/
│
├── dashboard/
│ ├── app.py
│
├── docker/
│ ├── Dockerfile
│
├── tests/
├── requirements.txt
├── README.md

yaml
Copy code

---

## 🔄 Data Pipeline

### 1. Data Ingestion
- Accepts CSV or API-based customer and sales data
- Performs schema validation and logging
- Stores raw data for traceability and auditing

### 2. Data Cleaning
- Handles missing values and duplicates
- Normalizes numerical fields
- Converts date formats
- Ensures consistency across datasets

### 3. Feature Engineering
Key engineered features include:
- **Recency** – Days since last purchase  
- **Frequency** – Total number of purchases  
- **Monetary** – Total customer spend  
- **Average Order Value (AOV)**  

---

## 🤖 Machine Learning Models

### 🔹 Customer Conversion Prediction (Classification)
- Logistic Regression
- Random Forest Classifier

**Evaluation Metrics**
- Accuracy
- Precision
- Recall
- ROC-AUC

---

### 🔹 Revenue Prediction (Regression)
- Linear Regression
- Random Forest Regressor

**Evaluation Metrics**
- RMSE
- R² Score

---

### 🔹 Customer Segmentation (Clustering)
- K-Means clustering on RFM features
- Elbow method for optimal cluster selection

**Customer Segments**
- High-value loyal customers
- Price-sensitive customers
- One-time buyers
- Churn-risk customers

---

## 🌐 API Endpoints

| Endpoint | Description |
|--------|------------|
| `/predict/conversion` | Predicts customer conversion probability |
| `/predict/revenue` | Predicts expected customer revenue |
| `/customers/segment` | Returns customer segment |
| `/analytics/summary` | Returns key business KPIs |

---

## 📊 Dashboards & Insights

- Revenue trends and growth analysis
- Customer segmentation visualization
- Conversion funnel analysis
- KPI monitoring for business teams

Dashboards are designed to be **non-technical stakeholder friendly**.

---

## 🐳 Deployment

- Containerized using Docker
- Deployed on cloud platforms such as Render, Railway, or AWS EC2
- Supports scalable API-based inference and dashboard access

---

## 📌 Business Impact

- Identifies high-value customers driving the majority of revenue
- Enables targeted marketing strategies through customer segmentation
- Predicts customer behavior to improve conversion rates
- Provides actionable insights through visual analytics

---

## 🔮 Future Enhancements

- Real-time data ingestion using streaming pipelines
- Model monitoring and data drift detection
- Automated retraining workflows
- Role-based access control for dashboards

---

## 👤 Author

**Mayank Verma**  
Aspiring Data Analyst / Data Scientist  

📧 Email: *(mayankverma210405@gmail.com)*  
🔗 LinkedIn: *(Mayankverma210405)*  
💻 GitHub: *(Mayankverma210405)*  

---

## ⭐ If you find this project useful, please give it a star!
