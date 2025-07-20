
# 🛍️ Mall Customer Segmentation using K-Means Clustering

[![Kaggle Badge](https://img.shields.io/badge/Dataset-Kaggle-blue?logo=kaggle)](https://www.kaggle.com/datasets/amisha0528/mall-customers-dataset)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/M-Z-5474/mall-customer-segmentation/blob/main/data-analysis/mall_customers_segmentation.ipynb)
![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Last Commit](https://img.shields.io/github/last-commit/M-Z-5474/mall-customer-segmentation)
![Repo Size](https://img.shields.io/github/repo-size/M-Z-5474/mall-customer-segmentation)



This project performs **customer segmentation** on mall customer data using **unsupervised machine learning** (K-Means Clustering). The goal is to identify distinct customer groups based on demographics and spending behavior to help with **targeted marketing** and **personalized business strategies**.

---

## 📁 Repository Structure

```bash
Customer_Segmentation_KMeans
|
├── dataset/
│   └── Mall_Customers.csv              # Raw dataset used for clustering
|   └── README.md                       # Dataset description
│
├── data-analysis/
│   └── customer_segmentation.ipynb     # Full analysis: EDA, clustering, visualizations
│   └── README.md                       # Notebook-specific documentation
│
├── images/
│   ├── elbow_plot.png                  # Elbow Method for optimal clusters
│   ├── pca_clusters.png                # Final customer segments using PCA
│   ├── age_vs_spending.png            # Age vs Spending Score plot
│   └── visualize_t-SNE.png            # Customer segments visualized with t-SNE
│
├── requirements.txt                   # Python dependencies (optional if using Colab)
├── README.md                          # You are here! Main project overview

````

---

## 📦 Dataset Information

- **Source**: [Kaggle - Mall Customers Dataset](https://www.kaggle.com/datasets/amisha0528/mall-customers-dataset)
- **Records**: 200 customers
- **Features**: CustomerID, Gender, Age, Annual Income (k$), Spending Score (1–100)
- **No missing values**

---

## 🔍 What’s Inside the Analysis

The notebook in `data-analysis/` performs the following tasks:

- 🔹 Data Cleaning & Encoding  
- 🔹 Exploratory Data Analysis (EDA)  
- 🔹 Feature Scaling using `StandardScaler`  
- 🔹 K-Means Clustering with Elbow Method  
- 🔹 PCA & t-SNE Visualizations  
- 🔹 Silhouette Score Evaluation  
- 🔹 Cluster-Based Marketing Strategy Suggestions

### 🖼️ Key Visualizations

### 📌 Elbow Method for Optimal Clusters
![Elbow Method](images/elbow_plot.png)

### 📌 Final Customer Segments (PCA)
![PCA Clustering](images/pca_clusters.png)

### 📌 Age vs Spending Score
![Age vs Spending](images/age_vs_spending.png)

### 📌 Customer Segments Visualized Using t-SNE
![Visualized Using t-SNE](images/visualize_t-SNE.png)

---

## 📈 Key Techniques Used

| Category         | Tools & Libraries                      |
|------------------|----------------------------------------|
| Data Handling    | `pandas`, `numpy`                      |
| Visualization    | `matplotlib`, `seaborn`                |
| Clustering       | `scikit-learn` (KMeans, PCA, t-SNE)    |
| Evaluation       | `silhouette_score`                     |

---

## 📌 Objective

Group mall customers into clusters based on:
- **Age**
- **Annual Income**
- **Spending Score**
- **Gender**

Then interpret these clusters to design **personalized marketing strategies**.

---

## 📬 Author

**Muhammad Zain Mushtaq**  
📌 GitHub: [@M-Z-5474](https://github.com/M-Z-5474)

---

> 💡 Tip: Explore the `data-analysis` folder for the complete interactive notebook and detailed clustering insights.



