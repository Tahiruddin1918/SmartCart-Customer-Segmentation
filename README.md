# 🛒 SmartCart Customer Segmentation

An unsupervised machine learning project that segments customers based on demographic information, purchasing behaviour, and engagement metrics. This project applies data preprocessing, dimensionality reduction, and clustering techniques to identify meaningful customer groups for targeted business strategies.

---

## 📌 Project Overview

Customer segmentation helps businesses understand different customer groups based on their characteristics and purchasing behaviour. This project uses machine learning to discover customer segments without predefined labels automatically.

The workflow includes data preprocessing, feature engineering, Principal Component Analysis (PCA), and clustering algorithms to identify meaningful customer groups.

---

## 🎯 Objectives

- Clean and preprocess customer data
- Perform feature engineering
- Reduce dimensionality using PCA
- Compare multiple clustering algorithms
- Analyse and interpret customer segments
- Generate business insights from discovered clusters

---

## 📂 Dataset

The dataset contains customer demographic information, purchasing behaviour, and engagement-related features.

**Features include:**

- Customer demographics
- Purchase history
- Spending patterns
- Engagement metrics
- Shopping behaviour

> The dataset is not included in this repository. Add your dataset inside the `data/` directory before running the notebook.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## 🔄 Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. One-Hot Encoding
6. Feature Scaling
7. Principal Component Analysis (PCA)
8. K-Means Clustering
9. Agglomerative Clustering
10. Cluster Evaluation
11. Customer Segment Analysis

---

## 🤖 Machine Learning Techniques

### Dimensionality Reduction

- Principal Component Analysis (PCA)

### Clustering Algorithms

- K-Means Clustering
- Agglomerative Clustering

---

## 📊 Results

The clustering algorithms successfully identified distinct customer segments with different purchasing and engagement patterns.

Agglomerative Clustering was selected for the final analysis after comparing clustering quality and interpretability.

---

## 📁 Repository Structure

```
SmartCart-Customer-Segmentation/
│
├── notebooks/
│   └── SmartCart_Customer_Segmentation.ipynb
│
├── images/
│
├── data/
│
├── requirements.txt
│
└── README.md
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/Tahiruddin1918/SmartCart-Customer-Segmentation.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run

Open the notebook inside the `notebooks` folder using:

- Jupyter Notebook
- Google Colab

---

## 📈 Future Improvements

- Hyperparameter tuning
- Additional clustering algorithms
- Interactive cluster visualization
- Deployment as a web application
- Automated customer profiling

---
