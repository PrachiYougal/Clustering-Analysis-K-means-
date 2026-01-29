# 📊 Task 3: Clustering Analysis using K-Means

## 📝 Overview
This project focuses on implementing **K-Means clustering**, an unsupervised machine learning technique used to group similar data points based on feature similarity. The task aims to uncover hidden patterns and structures within the dataset without relying on predefined labels.

---

## 🎯 Objectives
- Standardize the dataset to ensure all features contribute equally to the clustering process.
- Apply the **K-Means clustering algorithm** to group similar data points.
- Determine the optimal number of clusters using the **Elbow Method**.
- Visualize the resulting clusters using **2D scatter plots**.

---

## 🧠 Methodology
1. **Data Loading**  
   The dataset is loaded and relevant numerical features are selected for clustering.

2. **Feature Scaling**  
   Since K-Means is a distance-based algorithm, the features are standardized using `StandardScaler` to eliminate scale-related bias.

3. **Optimal Cluster Selection**  
   The Elbow Method is applied by calculating inertia values for different numbers of clusters. The point where inertia reduction slows indicates the optimal number of clusters.

4. **K-Means Clustering**  
   The K-Means algorithm is trained using the optimal number of clusters, and each data point is assigned to a cluster.

5. **Visualization**  
   Clusters are visualized using 2D scatter plots to analyze cluster separation and grouping behavior.

---

## 🛠 Tools & Technologies
- **Python**
- **pandas**
- **scikit-learn**
- **matplotlib**
- **seaborn**

---

## 📂 Project Structure
Clustering-Analysis-KMeans/
│
├── data/
│   └── Stock Prices Data Set.csv
│
├── notebooks/
│   └── ClusteringAnalysis.ipynb
│
├── images/
│   ├── elbow_method.png
│   └── cluster_visualization.png
│
├── README.md

## Author 
Prachi Yougal

