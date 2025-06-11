# Customer Segmentation via Clustering Techniques

This repository presents a clustering-based customer segmentation analysis aimed at refining marketing strategies for a credit card company. Using behavioral and demographic features of 9000+ customers, the project applies multiple unsupervised learning methods to identify distinct customer groups.

---

##  Dataset

- Source: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- Description: Contains 18 behavioral and demographic variables such as transaction frequency, credit limit, income, and loyalty.

---

##  Methods

###  Data Preprocessing
- **Missing Values**: Removed ~1,690 NA entries.
- **Outlier Handling**: Handled using IQR (Interquartile Range) method.
- **Dimensionality Reduction**: Principal Component Analysis (PCA) applied to improve clustering quality.

###  Clustering Algorithms
- **K-Means Clustering**: Optimal number of clusters found using the Elbow and Silhouette methods (K=3).
- **Hierarchical Clustering**: Dendrogram-based optimal cutoff at 4 clusters.
- **PCA + Clustering**: Enhanced interpretability and cluster separation using first 2 principal components.

---

##  Results

| Method                 | Silhouette Score |
|------------------------|------------------|
| K-Means                | 0.53             |
| Hierarchical Clustering| 0.56             |
| PCA + Hierarchical     | 0.56             |

---

##  File Structure

- `Report.pdf`: Full methodology, visualizations, and discussion.
- `Suplementary.pdf`: Supporting visuals including box plots, elbow plots, and PCA projections.
- `Merged.pdf`: Combined version for print-ready or presentation use.

---

##  Author

**Seyed Mohammad Mehdi Hassani Najafabadi**  
STATS/CSE 780 – McMaster University  
March 2023

---

##  License

This project is licensed under the MIT License.
