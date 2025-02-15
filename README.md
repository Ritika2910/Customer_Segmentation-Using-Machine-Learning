**📌 Customer Segmentation using Machine Learning**
**🔧 Technologies Used**

🐍 Python

📚 Scikit-Learn

🐼 Pandas

🔢 NumPy

📊 Seaborn

📉 Matplotlib

**🚀 Project Overview**

This project focuses on customer segmentation using machine learning techniques to categorize customers into distinct groups based on their purchasing behavior.

**🔍 Key Features**

1. Data Preprocessing & Analysis: Cleaned, transformed, and analyzed data to extract meaningful insights for targeted marketing.
2. Customer Segmentation Model: Developed a data-driven clustering model to identify 5 distinct customer groups within the dataset.
3. Optimization & Performance Tuning: Fine-tuned model parameters iteratively, improving segmentation accuracy by 20%.

**📊 Clustering Techniques**

*📌 K-Means Clustering*

✅ Partitioned customers into k distinct clusters based on similarities.

✅ Used Elbow Method to determine the optimal number of clusters.

✅ Improved segmentation accuracy by adjusting cluster centroids iteratively.

*📌 DBSCAN Clustering*

✅ Identified density-based clusters of customers with arbitrary shapes.

✅ No need to predefine the number of clusters.

✅ Used epsilon (ε) and minimum points to define core points and outliers.

✅ Effective in detecting noise and outlier customers.

✅ Achieved a Silhouette Score of 0.41 for well-defined clusters.
**📊 Results & Comparison**

📌 K-Means is effective when the number of clusters is known and data is well-separated.

📌 DBSCAN is better at identifying noise and irregularly shaped clusters, making it suitable for datasets with varying density.

📌 Silhouette Score for DBSCAN was 0.41, indicating moderate cluster separation.

📌 K-Means performed better for structured datasets with well-defined clusters, while DBSCAN excelled in detecting anomalies and non-uniform distributions.

📌 Overall, the choice depends on the dataset: K-Means for structured clustering and DBSCAN for anomaly detection & irregular clustering.
