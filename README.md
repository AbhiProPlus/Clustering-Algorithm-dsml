# Clustering-Algorithm-dsml

# Clustering Algorithms on the Iris Dataset

This project involves implementing and analyzing clustering techniques using the **Iris dataset**. The focus is on applying **KMeans Clustering** and **Hierarchical Clustering**, visualizing their results, and deriving insights from the clusters.

## Objective
To evaluate clustering techniques and understand their application to a real-world dataset. Specifically, the project includes:
- Implementing KMeans and Hierarchical Clustering.
- Visualizing clusters.
- Interpreting results.

## Dataset
The dataset used is the Iris dataset, which is available in the `sklearn` library. The dataset contains the following features:
- `sepal length (cm)`
- `sepal width (cm)`
- `petal length (cm)`
- `petal width (cm)`

## Key Components

### 1. Preprocessing
- Loaded the Iris dataset using `sklearn`.
- Checked for missing values, duplicates, skewness, and outliers.
- Addressed outliers using the **IQR method**.
- Normalized the data using **Min-Max Scaling**.

### 2. KMeans Clustering
- Determined the optimal number of clusters using the **Elbow Method** and **Silhouette Score**.
- Applied KMeans clustering with the optimal `K=3`.
- Visualized the clusters in a 2D space using **PCA**.

### 3. Hierarchical Clustering
- Used the **Ward linkage method** for agglomerative clustering.
- Visualized the dendrogram to determine the optimal number of clusters.
- Applied Hierarchical Clustering with `n_clusters=3`.
- Visualized the clusters in a 2D space using **PCA**.

## Visualizations
1. **Boxplots and Histograms**:
   - Explored the distribution of each feature.
2. **Elbow Method**:
   - Determined the optimal number of clusters for KMeans.
3. **Dendrogram**:
   - Observed the hierarchical merging of clusters.
4. **Cluster Visualizations**:
   - Visualized clusters formed by both KMeans and Hierarchical Clustering in reduced 2D space using PCA.

## Results
1. Both KMeans and Hierarchical Clustering identified three clusters corresponding to the natural grouping of the Iris dataset.
2. The clusters show clear separations based on petal length and width, which are highly distinguishing features in the Iris dataset.

## How to Run
1. Clone the repository.
2. Open the provided Jupyter Notebook file (`Clustering_Iris.ipynb`).
3. Install necessary dependencies using:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
4. Run all the cells step by step to reproduce the results.

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## File Structure
```
.
├── Clustering_Iris.ipynb    # Jupyter Notebook containing the code and analysis
├── README.md                # This file
```

## Acknowledgements
- The Iris dataset is a classic dataset for machine learning, available in the `sklearn` library.
- Special thanks to Dr. Jitha P Nair for the assignment outline.

---

Feel free to explore the code and leave feedback or suggestions!
