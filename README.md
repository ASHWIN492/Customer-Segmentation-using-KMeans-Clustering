

### Problem Statement:  
The objective of this project is to segment customers based on their **Annual Income** and **Spending Score** using **K-Means Clustering**. The aim is to identify distinct customer groups that share similar purchasing power and spending behavior. Businesses can use these customer segments to enhance their marketing strategies, target high-value customers, and improve customer retention.

### Theory 

#### K-Means Clustering:
K-Means is a popular unsupervised algorithm that classifies data points into **K distinct clusters** based on the similarity of their features. Each data point belongs to the cluster with the nearest centroid, which represents the mean of the cluster.

#### Elbow Method:
To determine the optimal number of clusters, the **Elbow Method** is used. It evaluates the **Within-Cluster Sum of Squares (WCSS)** for different values of K (number of clusters). The point at which the decrease in WCSS slows down is known as the "elbow," suggesting the optimal number of clusters.

---

### Key Steps (Updated):

1. **Data Preprocessing**:
   - Drop irrelevant features like `CustomerID`.
   - Only focus on **Annual Income** and **Spending Score** for clustering.

2. **Optimum Number of Clusters**:
   - Use the **Elbow Method** to determine the ideal number of clusters by plotting WCSS against the number of clusters (K). The "elbow" point helps to identify the best K value.

3. **K-Means Clustering**:
   - Apply the K-Means algorithm to the dataset with the chosen number of clusters.
   - Assign each customer to a cluster based on their **Annual Income** and **Spending Score**.

4. **Visualizing the Clusters**:
   - Plot the clusters using a scatter plot of `Annual Income` vs. `Spending Score`. Each point represents a customer, and the color represents the cluster they belong to.
   - The centroids of each cluster can also be plotted to show the center of each group.

---

### Applications of Customer Segmentation (Updated):
- **Personalized Marketing**: Tailor marketing strategies to target specific income or spending score segments.
- **Business Insights**: Identify high-income, high-spending customers and low-income, low-spending customers to design different offers.
- **Loyalty Programs**: Reward high-value customers and create strategies to encourage low-value customers to spend more.

This focused approach on **Annual Income** and **Spending Score** provides insight into how financially different groups of customers interact with the business.
