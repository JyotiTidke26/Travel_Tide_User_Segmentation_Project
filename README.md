# 🌍 Travel_Tide Customer Segmentation Project

## 📌 Project Overview

The **Travel_Tide Project** aims to improve customer retention for an e-booking platform by analyzing user behavior and developing a personalized rewards program. The project leverages **unsupervised machine learning** techniques to segment customers into distinct personas, each with specific preferences and behaviors. This allows for more targeted marketing and engagement strategies.

> 🎯 **Goal**: Enhance customer satisfaction, increase loyalty, and boost business performance through data-driven insights.

---

## 💡 Motivation

The travel and hospitality industry faces growing competition and high customer churn. In such a landscape, **personalization is key**. This project was initiated to better understand customer behavior and create strategies tailored to different user groups.

By applying **customer segmentation**, we provide Travel_Tide with actionable insights to enhance engagement and run more effective marketing campaigns.

---

## 🛠️ Technologies Used

- **Programming**: Python for data analysis and modeling  
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Development Environment**: Jupyter Notebooks
- **Machine Learning**:
  - `KMeans` clustering for customer segmentation
  - `PCA` (Principal Component Analysis) for dimensionality reduction
  - `Silhouette Score` for clustering performance evaluation

---

## 🧹 Data Collection & Cleaning

Data was collected from multiple sources and focused on session-level behavioral attributes.

### Cleaning Steps:
- Merged relevant tables at **session-level granularity**
- Filtered for users with **≥ 7 sessions** after **January 4, 2023**
- Handled **missing/inconsistent values** to ensure data quality

---

## 🔍 Methodology

### Steps:
1. **Preprocessing**: Standardized all features
2. **Dimensionality Reduction**: Applied PCA
3. **Clustering**: Used K-Means on PCA-transformed data
4. **Evaluation**: Determined optimal cluster count using Silhouette Score

---

## 👥 Customer Segmentation Analysis

| Group | Segment Name           | Description |
|-------|------------------------|-------------|
| 0     | Family Travelers       | Moderate travelers, typically female, preferring family-oriented perks |
| 1     | Loyal Deal Seekers     | Infrequent but loyal travelers, responsive to promotions and upgrades |
| 2     | Smart Saver Travelers  | Budget-conscious, regional travelers who prioritize discounts |
| 3     | Luxury Travelers       | High spenders seeking premium, long-distance experiences |

---

## 📊 Key Findings

- **Family Travelers**: Prefer group bookings and family-centric offers
- **Loyal Deal Seekers**: Respond well to loyalty perks and free upgrades
- **Smart Saver Travelers**: Value discounts and short, regional trips
- **Luxury Travelers**: Prioritize comfort and premium services

---

## 🧠 Recommendations

- **Optimize UX/UI**: Improve booking experience for mid-tier users
- **Refine Segmentation Models**: Use real-time data to retrain clusters
- **A/B Testing**: Tailor engagement strategies for each customer group

---

## ⚠️ Limitations & Challenges

- **Incomplete Data**: Missing or inconsistent entries required cleaning
- **Complex Segmentation**: Choosing the right number of clusters was tricky
- **Seasonality**: Temporal patterns in travel behavior not fully captured

---

## 📚 Credits

- **Data Source**: Travel_Tide User Data

---


## 📓 Project Notebook

You can explore the full analysis and implementation in the Jupyter Notebook:  
👉 [Mastery_Project_Travel_Tide.ipynb](./Mastery_Project_Travel_Tide.ipynb)


