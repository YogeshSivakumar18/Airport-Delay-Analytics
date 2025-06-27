
# ✈️ Airport Delay Analytics: Machine Learning & Passenger Feedback Insights

**Classifying Airport Delays and Recommending Improvements Using ML and NLP**  
_By Prasanth Ramaswamy & Yogesh Sivakumar_

---

## 📌 Overview

This project tackles the persistent issue of flight delays across U.S. airports using advanced machine learning and natural language processing (NLP). By analyzing operational and weather data alongside over 6,000 passenger reviews, the study provides:

- Delay classification (Low, Moderate, High)
- Insightful recommendations for airport-specific improvements
- A hybrid ML framework combining XGBoost with Deep Learning

---

## 🎯 Objectives

- **Classify** U.S. airports into low, moderate, and high delay categories.
- **Analyze** delay patterns using structured (operational/weather) and unstructured (text reviews) data.
- **Recommend** targeted improvements using sentiment and keyword analysis.

---

## 🧠 Techniques & Tools Used

### 🔬 Machine Learning Models
- **Support Vector Machine (SVM)**
- **Random Forest**
- **XGBoost & Gradient Boosting**
- **K-Means Clustering (Unsupervised)**
- **Feature-Interaction Enhanced XGBoost + Deep Learning**

### 🔍 NLP Techniques
- Sentiment Analysis using **TextBlob**
- Keyword Extraction using **TF-IDF**
- Topic insights from **passenger reviews**

---

## 🗂️ Dataset Summary

- **Flight Delay Data (2013–2023)**  
  Delay types, durations, and causes from U.S. airports

- **Weather Data**  
  Scraped via **Selenium** from Weather Underground (temperature, precipitation, wind, etc.)

- **Passenger Review Data**  
  Structured ratings + unstructured review text covering queuing, cleanliness, staff, etc.

---

## 📊 Model Performance (Classification)

| Model | Accuracy | Highlight |
|-------|----------|-----------|
| SVM | 84.1% | High recall for "High Delay" airports |
| Random Forest | 83.86% | Balanced precision-recall |
| XGBoost | 85.08% | Best among standard models |
| **Hybrid Model (FNN + XGBoost)** | **88%** | Best overall performance |

> 🏆 The hybrid model leveraged feature interaction and deep learning-generated probabilities to outperform all traditional models.

---

## 📈 Clustering Results

- **K-Means** (k=2) achieved highest silhouette score (~0.34)
- Airports were grouped as high-delay vs low-delay for segment-based strategy

---

## 💬 NLP-Driven Recommendations

Used structured + unstructured passenger feedback to identify issues at high-delay airports:

- **Common issues**: staff courtesy, terminal hygiene, long queues
- Generated **airport-specific suggestions** using sentiment polarity & keyword clustering

---

## 📁 Repository Contents

```
📦 airport-delay-analytics/
├── 📘 airport_delay_analytics.ipynb         # Colab notebook with full pipeline
├── 📄 Airport_Delay_Analytics_Report.pdf    # Full IEEE-style project report
├── 🧪 data/                                 # Sample or reference data (if added)
├── 📊 images/                               # Visualizations, charts (optional)
├── 📜 README.md                             # Project overview
└── .gitignore                               # Ignored files list
```

---

## 📥 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/airport-delay-analytics.git
   ```
2. Open the notebook in [Google Colab](https://colab.research.google.com) or Jupyter.
3. Follow the pipeline from data loading to model evaluation and insights.

---

## 📄 Project Report

📘 [Read the Full IEEE-Style Report](./Airport_Delay_Analytics_Report.pdf)

---

## 🚀 Future Work

- Incorporate **live flight data** and hourly patterns
- Explore **RNNs/LSTMs** for time series delay prediction
- Build a **real-time dashboard** for airport delay insights

---

## 📌 Keywords

`Machine Learning` · `Airport Delay` · `NLP` · `XGBoost` · `Sentiment Analysis` · `Flight Analytics`

---

## 👥 Authors

- **Prasanth Ramaswamy** (24134252@studentmail.ul.ie)  
- **Yogesh Sivakumar** (24150029@studentmail.ul.ie)

---
