
# Customer Segmentation & Classification Toolkit

This repository contains two interconnected machine learning projects aimed at improving customer understanding through segmentation and predictive modeling.

---

## 📊 Project 1: Unsupervised Customer Segmentation (Clustering)

We apply unsupervised learning techniques to segment customers based on demographic and behavioral patterns. Several clustering algorithms (K-Means, DBSCAN, GMM, Hierarchical) are compared using PCA and silhouette scores. The goal is to uncover actionable groups for targeted marketing.

**Key highlights:**
- Data cleaning, normalization, and dimensionality reduction (PCA)
- Clustering with K-Means, DBSCAN, GMM, Hierarchical
- Visual analysis of cluster separation
- Behavioral profiling of each cluster

---

## 🔮 Project 2: Predictive Customer Classification (Neural Networks)

Building on the previous clustering, this project trains neural networks to classify new customers into one of the discovered clusters. Based on early purchase activity and demographic features, the model helps automate client onboarding with segment-specific strategies.

**Key highlights:**
- Labeling via previous clustering
- Input features: simulated 30-day activity + demographics
- Classification via TensorFlow Sequential models
- Use case: fast targeting, LTV prediction, campaign personalization

---

## 🛠️ Tools & Techniques

- Clustering: K-Means, DBSCAN, GMM, Hierarchical
- Dimensionality Reduction: PCA
- Neural Networks: TensorFlow (Sequential API)
- Evaluation: Silhouette Score, Cluster Profiling, Accuracy
- Data handling: Pandas, NumPy, Matplotlib, Seaborn

---

## 🧩 Applications

- Personalized marketing and campaign targeting
- Early-stage customer profiling
- Strategic segmentation for product positioning

---

> These projects demonstrate a complete pipeline: from unsupervised discovery to real-time prediction of customer types — ready to be integrated into data-driven marketing platforms.
