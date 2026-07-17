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
### Naming the Segments

Based on the average Age, Annual Income, and Spending Score per cluster:

- **Cluster 2 — VIP Customers**: highest income (86.1) and highest spending score (81.5). The most valuable segment — has the means and the willingness to spend.
- **Cluster 3 — Conservative High Earners**: same high income as Cluster 2 (86.1) but the lowest spending score (19.4). Income isn't the barrier here — spending behavior is; a segment that needs a different marketing approach than Cluster 2 despite similar earnings.
- **Cluster 1 — Young High Spenders**: youngest group (25.2) with a high spending score (62.2) despite only moderate income (41.1). Spends beyond what income alone would predict — likely lifestyle-driven.
- **Cluster 0 — Budget Customers**: lowest income (26.75) and lowest spending score (18.35). Limited discretionary budget across the board.
- **Cluster 4 — Standard Customers**: oldest group (55.6), with income and spending both sitting in the middle — a stable, moderate segment.

**Business takeaway:** Clusters 2 and 3 both have high income, but only Cluster 2 converts that into spending — this distinction alone justifies different marketing strategies for what would otherwise look like a single "high income" group if segmented on income alone.

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