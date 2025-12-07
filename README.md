**Project: Customer Segmentation Using Unsupervised Learning (K-Means)**

**Goal**: Group customers based on their purchasing behaviour to discover hidden patterns (segments).

**Dataset**: Mall Customers dataset from kaggle https://www.kaggle.com/code/tanmay111999/unsupervised-learning-3-6-clusters-k-means-eda?select=Mall_Customers.csv

1. **Problem Statement:** A retail store wants to understand different types of customers to improve marketing and personalize promotions.

  The aim is to use unsupervised learning to find natural groups of customers.

**2. Dataset Example (Mall Customer Dataset**

  Typical columns:

  CustomerID

  Gender

  Age

  Annual Income (k$)

  Spending Score (1–100)

**3️. Data Preprocessing Steps**

  -Clean missing values
  -Select useful features: (Age, Annual Income, Spending Score)
  -Scale the features (StandardScaler)

**4️. Choose the Model — K-Means Clustering**

  Why K-Means?

  Simple and effective

  Great for segmentation

  Works well with numerical data

**5️. Find Optimal k (Number of Clusters)**
  Use the Elbow Method and Silhouette Score.

**6️. Train the Model**

  Use K-Means to cluster customers into groups like:

  Cluster 0 → Low income, low spending

  Cluster 1 → High income, high spending

  Cluster 2 → Medium income, moderate spending
  (Your results may differ)

**7️. Visualizations**

  Create:
  -Scatter plot of clusters
  -3D plot (optional)
  -Cluster distribution bar chart
