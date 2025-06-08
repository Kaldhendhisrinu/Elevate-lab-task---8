# Mall Customers Segmentation Using K-Means Clustering

This project performs customer segmentation on the Mall Customers dataset using **K-Means Clustering**, an unsupervised machine learning technique. The goal is to group customers into distinct clusters based on their demographics and spending behavior to enable targeted marketing strategies.

---

## Dataset

The dataset `Mall_Customers.csv` contains data for 200 customers with the following features:

- **CustomerID**: Unique identifier for each customer  
- **Gender**: Gender of the customer (Male/Female)  
- **Age**: Age of the customer  
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars  
- **Spending Score (1-100)**: A score assigned by the mall based on customer spending behavior  

---

## Project Overview

- **Data preprocessing:**  
  - Handle categorical variables by encoding Gender.  
  - Scale features using StandardScaler for better clustering results.

- **Dimensionality reduction:**  
  - Use PCA to reduce feature space to 2 dimensions for visualization.

- **K-Means Clustering:**  
  - Determine the optimal number of clusters (k) using the Elbow method.  
  - Perform clustering with optimal k and assign cluster labels.

- **Evaluation:**  
  - Visualize clusters in PCA space.  
  - Calculate the Silhouette Score to assess cluster quality.  
  - Provide cluster profi
