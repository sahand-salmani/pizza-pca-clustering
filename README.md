# Pizza Data Set Analysis

This project involves exploratory data analysis (EDA), Principal Component Analysis (PCA), and clustering on a pizza data set containing various nutritional and brand information. Below is a detailed explanation of the steps undertaken and the libraries used throughout the analysis.

## Data Set Description

The pizza data set consists of 300 observations and the following columns:

| #   | Column | 
| --- | ------ | 
| 0   | brand  | 
| 1   | id     | 
| 2   | mois   | 
| 3   | prot   | 
| 4   | fat    | 
| 5   | ash    | 
| 6   | sodium | 
| 7   | carb   | 
| 8   | cal    | 

## Libraries Used

The following Python libraries were used in this project:

- `warnings`: To handle warnings during the execution.
- `numpy`: For numerical operations.
- `pandas`: For data manipulation and analysis.
- `seaborn`: For data visualization.
- `plotly`: For interactive visualizations.
- `matplotlib`: For plotting graphs.
- `sklearn.decomposition.PCA`: For performing Principal Component Analysis.
- `sklearn.metrics.silhouette_score`: To evaluate the clustering.
- `sklearn.preprocessing.StandardScaler`: For data standardization.
- `sklearn.cluster.KMeans`: For performing k-means clustering.

## Steps Undertaken

### 1. Exploratory Data Analysis (EDA)

- Loaded the data and checked for null values.
- Performed summary statistics to understand the distribution of the data.
- Visualized the data using seaborn and matplotlib.

### 2. Data Preprocessing

- Standardized the data using `StandardScaler`.
  
### 3. Principal Component Analysis (PCA)

- Conducted PCA using `PCA` to reduce the dimensionality of the data.
- Visualized the principal components.

### 4. Clustering

- Determined the optimal number of clusters using the elbow method.
- Applied k-means clustering using `KMeans`.
- Evaluated the clustering using the silhouette score.

### 5. Visualization

- Used `matplotlib` and `seaborn` for static visualizations.
- Employed `plotly` for interactive plots.


## Contributors

- [Sahand Salmani](https://github.com/sahand-salmani)