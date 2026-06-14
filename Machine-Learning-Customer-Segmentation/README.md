# Customer Segmentation Using Distance Geometry and Clustering

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-KMeans-success)
![Dataset-H&M-orange](https://img.shields.io/badge/Dataset-H%26M-red)
![Status-Completed](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## Overview

This project explores customer segmentation using concepts from:

- Linear Algebra
- Distance Geometry
- Machine Learning
- Clustering Theory

Customers are represented as vectors in a feature space derived from transactional data. Similarity between customers is measured using Euclidean distance and clustering is performed using the K-Means algorithm.

The objective is to discover meaningful customer groups that support targeted marketing and data-driven business decisions.

---

## Dataset

This project uses customer transaction data from **H&M**, the global fashion retailer.

The dataset was transformed into customer-level behavioral features before clustering.

### Features Used

- Recency
- Frequency
- Monetary Value
- Quantity Purchased
- Average Order Value

---

## Mathematical Foundations

The project applies:

- Euclidean Distance
- Vector Spaces
- Norms
- Inner Products
- Quadratic Optimization

The K-Means objective function minimizes within-cluster variance:

J = Σ ||x - μ||²

where μ represents the cluster centroid.

---

## Machine Learning Pipeline

1. Data Cleaning
2. Feature Engineering
3. Feature Scaling
4. K-Means Clustering
5. Cluster Evaluation
6. Visualization
7. Business Interpretation

---

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib
- PCA

---

## Results

The model successfully identified customer segments such as:

- Loyal High-Value Customers
- Regular Customers
- Low-Spend Customers
- At-Risk Customers

These insights can support:

- Customer Retention
- Personalized Marketing
- Recommendation Systems
- Revenue Optimization

---

## Repository Structure

```text
Machine-Learning-Customer-Segmentation/
│
├── README.md
├── customer_segmentation_clustering.pdf
├── code/
├── output/
└── data/
```

---

## Authors

- Aditya Raj
- Aditya Vikram Meda
- Ketan Reddy

---

## Institution

Mahindra University
Department of Mathematics
