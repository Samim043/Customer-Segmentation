Customer-Segmentation
========================


Customer Segmentation is one the most important applications of unsupervised learning. With the help of clustering techniques, **B2C** (Business to customers) companies can identify the several segments of customers that share a similarity in different ways that are relevant to marketing such as gender, age, interests, and miscellaneous spending habits.This will allow them to target the potential user base. 

\- In this Data Science Project, we will perform one of the most essential applications of machine learning – Customer Segmentation. In this project, we will implement customer segmentation in python. Whenever you need to find your best customer, customer segmentation is the ideal methodology.


1. **Exploratory data analysis**
-------------------------------
We will start our customer segmentation project by exploring the data. Our data consists of one .csv file containing the following features that describe each customer:
* CustomerIDs. 
* Age.
* Gender.
* Annual Income.
* Spending Score.

Dataset is **mall_customer.csv** and the exploration of data is given in the **Customer Segmentation.ipynb**


2. **K-means Clustering**
-------------------------------

After exploring each feature of our dataset, now it's time to segment the customers based on their features. In order to do that, we will use k-means clustering. This algorithm starts by selecting k objects from dataset randomly that will serve as the initial centers for our clusters  known as centroids. Then at each step, the algorithm seek to minimize the intra distance which is the distance between individuals within each cluste and maximize the inter-distance which is the distance between clusters.

* **Determining Optimal number of Clusters:**

While working with clusters, we need to specify the number of clusters to use. Thus we need to find the optimal number of clusters, to do that we will use the Silhouette method.
 * **Average Silhouette Method:**

 With the help of the average silhouette method, we can measure the quality of our clustering operation. With this, we can determine how well within the cluster is the data object. If we obtain a high average silhouette width, it means that we have good clustering. The average silhouette method calculates the mean of silhouette observations for different k values. With the optimal number of k clusters, one can maximize the average silhouette over significant values for k clusters.
 
 
 3. **Visualization**
 ----------------------
 
 
 
   \- **Cluster 0 and 5** – The two cluster consists of  customers with medium PCA2 and a high PCA1.

  \- **Cluster 1** – This cluster represents customers having a high PCA2 and a low PCA1.

  \- **Cluster 2** - This cluster consists of customers with medium PCA1 and medium PCA2 score.

  \- **Cluster 3** – This comprises of customers with a high PCA2 and a medium annual spend of income.

  \- **Cluster 4** – In this cluster, there are customers with a medium PCA1 and a low PCA2 score.



\- With the help of clustering, we can understand the variables much better, prompting us to take careful decisions. With the identification of customers, companies can release products and services that target customers based on several parameters like income, age, spending patterns, etc. Furthermore, more complex patterns like product reviews are taken into consideration for better segmentation.
