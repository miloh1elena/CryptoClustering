# CryptoClustering README

This project utilizes Python and unsupervised learning to predict how cryptocurrencies are influenced by 24-hour or 7-day price changes. 

**Instructions:**
- Load and analyze "crypto_market_data.csv."
- Normalize the data using StandardScaler.
- Find the optimal cluster count (k) with the elbow method for both original and PCA data.
- Perform K-means clustering on original data.
- Conduct Principal Component Analysis (PCA) to reduce features to three principal components.
- Find the optimal cluster count (k) for PCA data.
- Perform K-means clustering on PCA data.

**Important Questions:**
- What is the best value for k in both original and PCA data?
- How does the best k value for PCA data compare to that of the original data?
- What is the impact of using fewer features when clustering the data with K-means?

Refer to the Jupyter Notebook "Crypto_Clustering.ipynb" in this repository.