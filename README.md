# Customer Segmentation using Machine Learning

An end-to-end Machine Learning project that segments mall customers into different groups based on their purchasing behavior using clustering algorithms.

This project demonstrates the complete workflow of customer segmentation, from data preprocessing and exploratory data analysis (EDA) to K-Means Clustering, Hierarchical Clustering, PCA, and business insights.

---

## Project Overview

Customer segmentation helps businesses understand different types of customers so they can create targeted marketing strategies instead of treating every customer the same.

In this project, customers are grouped according to:

- Age
- Annual Income
- Spending Score

using unsupervised machine learning algorithms.

---

## Dataset

**Dataset:** Mall Customers Dataset

Features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

Target:

- No target variable (Unsupervised Learning)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

## Project Workflow

1. Data Loading
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Scaling
5. K-Means Clustering
6. Elbow Method
7. Silhouette Score
8. PCA (Principal Component Analysis)
9. Hierarchical Clustering
10. Business Insights

---

## Machine Learning Techniques

### K-Means Clustering

Used to group customers into similar segments.

### Elbow Method

Used to determine the optimal number of clusters.

### Silhouette Score

Used to evaluate clustering quality.

### Principal Component Analysis (PCA)

Reduced data from three dimensions to two for visualization.

### Hierarchical Clustering

Compared with K-Means using dendrogram analysis.

---

## Business Insights

The model identified different customer groups such as:

- High Income – High Spending (VIP Customers)
- High Income – Low Spending
- Low Income – High Spending
- Low Income – Low Spending
- Average Customers

These customer segments can be used for:

- Personalized marketing
- Customer retention
- Loyalty programs
- Product recommendations
- Targeted advertisements

---

## Project Structure

```
customer-segmentation/
│
├── app/
├── data/
│   └── Mall_Customers.csv
│
├── images/
├── models/
├── notebooks/
│   └── customer_segmentation.ipynb
│
├── requirements.txt
└── README.md
```

---

## Future Improvements

- Deploy using Streamlit
- Save trained clustering models
- Add interactive dashboards
- Compare additional clustering algorithms
- Hyperparameter tuning

---

## Author

**Mohammed Haneef**

GitHub:
https://github.com/haneef333