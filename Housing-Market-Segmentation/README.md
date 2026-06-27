#  Housing Market Segmentation using Agglomerative Clustering

## About the Project

This project applies **Agglomerative Hierarchical Clustering** to housing market data to identify groups of houses with similar characteristics. The aim is to discover meaningful patterns in the dataset without using any predefined labels.

The project also uses **PCA (Principal Component Analysis)** for cluster visualization and evaluates cluster quality using the **Silhouette Score**.


## Dataset Information

The dataset contains information about housing properties, including:

- Average Area Income
- Average House Age
- Average Number of Rooms
- Average Number of Bedrooms
- Area Population
- Price


## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- SciPy


## Project Workflow

1. Data Loading and Exploration
2. Data Cleaning
3. Feature Scaling using StandardScaler
4. Hierarchical Clustering
5. Dendrogram Analysis
6. Agglomerative Clustering
7. PCA-based Cluster Visualization
8. Silhouette Score Evaluation
9. Cluster Interpretation



## Techniques Implemented

### Agglomerative Clustering
Used to group similar housing records into clusters based on feature similarity.

### Dendrogram
Used to determine the optimal number of clusters.

### Principal Component Analysis (PCA)
Reduced the dimensionality of the dataset for visualization.

### Silhouette Score
Used to evaluate clustering performance.



## Results

- Successfully segmented housing data into **5 clusters**
- Visualized clusters using PCA
- Generated cluster-wise summaries for interpretation
- Evaluated clustering quality using the Silhouette Score


## Key Insights

- Houses were grouped based on similarities in income, population, house age, rooms, and price.
- Different clusters represented distinct housing market segments.
- PCA visualization helped understand cluster separation and structure.


## Future Improvements

- Compare with K-Means Clustering
- Perform Hyperparameter Tuning
- Create Interactive Visualizations
- Deploy using Streamlit
- Explore Advanced Clustering Techniques


## Author

**Sanjivani Kadam**  
B.Tech Robotics and Artificial Intelligence  
COEP Technological University

---

⭐ If you found this project interesting, feel free to explore the code and analysis.
