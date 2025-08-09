# 🛍️ Customer Segmentation Using Clustering

This project applies unsupervised machine learning techniques to segment customers based on their **Annual Income** and **Spending Score**. The goal is to identify distinct customer groups that can inform targeted marketing strategies and business decisions.

## 📁 Dataset

- **Source:** [Mall Customer Dataset on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)
- **Features Used:**  
  - `Annual Income (k$)`  
  - `Spending Score (1–100)`

## 🧠 Techniques Used

- Data preprocessing and feature scaling (`StandardScaler`)
- **K-Means Clustering**
  - Elbow Method to determine optimal clusters
  - Silhouette Score for cluster quality
- **DBSCAN Clustering**
  - Density-based clustering with noise detection
  - Parameter tuning (`eps`, `min_samples`)
- Cluster visualization using `Matplotlib` and `Seaborn`
- Cluster interpretation and business insights

## 📊 Results

- **K-Means Clustering**
  - Optimal clusters: 5
  - Silhouette Score: `0.555`
  - Clear segmentation into interpretable customer profiles

- **DBSCAN Clustering**
  - Silhouette Score (excluding noise): `0.388`
  - Identified core clusters and noise points

## 🔍 Business Insights

- High-income, high-spending customers are ideal for premium targeting.
- Low-income, high-spending customers may respond well to promotions.
- Wealthy but low-spending customers could be engaged with exclusive offers.

## 📌 Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 📁 Folder Structure

