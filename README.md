# Mall Customer Segmentation Analysis

## Project Description
This project aims to segment mall customers based on characteristics such as age, annual income, and spending score. Segmentation is performed using three different clustering methods: **K-Means**, **Agglomerative Hierarchical Clustering**, and **DBSCAN**. The clustering results are used to understand customer patterns and design more effective marketing strategies.

## Dataset
The dataset used is **Mall Customer Segmentation Data** from [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python). The dataset consists of 200 rows and 5 columns:
- `CustomerID`: Unique identifier for each customer.
- `Gender`: Gender of the customer (Male/Female).
- `Age`: Age of the customer.
- `Annual Income (k$)`: Annual income of the customer (in thousands of dollars).
- `Spending Score (1-100)`: Spending score of the customer (1-100).

## Project Steps
1. **Data Exploration**:
   - Descriptive statistical analysis.
   - Data distribution visualization.
   - Outlier identification and correlation analysis.

2. **Data Preprocessing**:
   - Handling missing values and duplicate data.
   - Encoding categorical variables (`Gender`).
   - Normalization/standardization of numerical data.

3. **Clustering Modeling**:
   - **K-Means**: Determining the optimal number of clusters using the Elbow Method.
   - **Agglomerative Hierarchical Clustering**: Using the same number of clusters as K-Means.
   - **DBSCAN**: Using predefined `eps` and `min_samples` parameters.
   - Model evaluation using the Silhouette Score.

4. **Result Analysis**:
   - Visualization of clustering results.
   - Comparison of model performance.
   - Insights from clustering results.

## Results
- **K-Means** and **Agglomerative Clustering** produced well-defined clusters (Silhouette Score: 0.45).
- **DBSCAN** was less effective for this dataset (Silhouette Score: 0.20).
- Scatter plot visualizations show the distribution and patterns of clusters.

## Contribution
If you would like to contribute to this project, please open an issue or submit a pull request. All contributions are welcome!

## License
This project is licensed under the MIT License.

## Author
Michael Angello Qadosy Riyadi
