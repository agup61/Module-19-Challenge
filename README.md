# Module-19-Challenge

**Overview**
The main objective of the Crypto Clustering project is to utilize unsupervised learning methods, specifically K-means clustering, to forecast whether cryptocurrencies are influenced by price fluctuations within a 24-hour or 7-day period. Moreover, the project investigates how dimensionality reduction techniques like Principal Component Analysis (PCA) affect the clustering process.

**Steps**
1. Load and preprocess the data.
2. Scale the data using StandardScaler.
3. Determine the optimal value for k by utilizing the elbow method.
4. Cluster the cryptocurrencies using K-means with the original scaled data.
5. Apply Principal Component Analysis (PCA) to reduce the features to three principal components.
6. Identify the best value for k using the PCA-transformed data.
7. Cluster the cryptocurrencies using K-means with the PCA-transformed data.
8. Visualize and compare the outcomes using hvPlot.

**Conclusion**
The project investigates how reducing the number of features affects the clustering process with K-means. By comparing the clustering outcomes of the original data and the PCA-transformed data, it aims to gain insights into the influence of dimensionality reduction on clustering.

**Dependencies**
- Python
- pandas
- NumPy
- scikit-learn
- hvPlot
