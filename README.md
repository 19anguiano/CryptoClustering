# CryptoClustering
![crypto_coins](https://user-images.githubusercontent.com/119361768/234443273-18b684c6-b7ab-495c-8e1e-3ea50bcb75d9.jpg)

# Prompt
You’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

# Process
## Prepare the Data
  - Read CSV file in and normalized data using StandardScaler() from scikit-learn
  - Created a DataFrame with the scaled data and set the coin_id as the index
 
## Analysis (Two Approaches)
### K-means Approach
  - Used elbow method to find the best value for k
  - Clustered the cryptocurrencies for the best value for k on the original scaled data
  - Created a copy of the original data and added column with predicted clusters
  - Plotted results on regular and 3D scatter plots
  
### Principal Component Analysis (PCA) Approach
  - Utilized the original scaled data to perform PCA and reduce the features
  - Created new DataFrame with PCA data
  - Used elbow method to find the best value for k
  - Clustered the cryptocurrencies for the best value for k on the PCA data
