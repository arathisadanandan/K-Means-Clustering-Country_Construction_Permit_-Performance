# K-Means-Clustering-Country_Construction_Permit_-Performance

## 📌 Project Overview
This project uses the K-Means Clustering algorithm to group countries based on similarities in construction-permit regulatory performance indicators.

## 🎯 Objectives
- Explore and analyze the dataset.
- Perform data cleaning and preprocessing.
- Visualize numerical features.
- Find the optimal number of clusters using the Elbow Method.
- Apply the K-Means Clustering algorithm.
- Analyze and interpret the clusters.
- Evaluate clustering performance using the Silhouette Score.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📂 Dataset
The project uses `main_data.csv`, which contains country-related information and construction-permit performance indicators.

## ⚙️ Workflow
1. Load the dataset.
2. Explore the data using Pandas.
3. Clean unnecessary columns.
4. Select numerical features.
5. Visualize feature distributions.
6. Apply the Elbow Method.
7. Train the K-Means model.
8. Analyze cluster assignments.
9. Evaluate the model using the Silhouette Score.
10. Interpret the clustering results.

## 🤖 Algorithm Used

### K-Means Clustering
K-Means is an unsupervised machine learning algorithm that groups similar data points into clusters.

**Model Parameters:**
- Number of clusters: 3
- Random state: 42

### Elbow Method
The Elbow Method helps identify a suitable number of clusters by analyzing the Within-Cluster Sum of Squares (WCSS).

### Silhouette Score
The Silhouette Score evaluates how well the data points fit within their assigned clusters.

## 📊 Results
The notebook interprets the clusters as follows:

- **Cluster 1:** Highest regulatory performance.
- **Cluster 0:** Moderate regulatory performance.
- **Cluster 2:** Lowest regulatory performance.

