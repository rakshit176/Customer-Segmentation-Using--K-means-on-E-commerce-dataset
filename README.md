# Customer-Segmentation-Using--K-means-E-commerce-dataset

## What is Customer Segmentation 

Customer segmentation involves grouping customers into specific marketing groups, perhaps narrowing them down by gender, interests, buying habits or demographic.

## Kmeans  Clustering 

Kmeans algorithm is an iterative algorithm that tries to partition the dataset into K pre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group. It tries to make the intra-cluster data points as similar as possible while also keeping the clusters as different (far) as possible. It assigns data points to a cluster such that the sum of the squared distance between the data points and the cluster’s centroid is at the minimum. The less variation we have within clusters, the more homogeneous (similar) the data points are within the same cluster.

The way kmeans algorithm works is as follows:
Specify number of clusters K.
Initialize centroids by first shuffling the dataset and then randomly selecting K data points for the centroids without replacement.
Keep iterating until there is no change to the centroids. i.e assignment of data points to clusters isn’t changing.
   Compute the sum of the squared distance between data points and all centroids.
   Assign each data point to the closest cluster (centroid).
   Compute the centroids for the clusters by taking the average of the all data points that belong to each cluster.


### Dataset used:
E-commerce is one of the fastest growing economic sectors worldwide. Typically e-commerce datasets are proprietary and consequently hard to find among publicly available data.
However, The UCI Machine Learning Repository has made this dataset containing actual transactions from 2010 and 2011.

### Content:

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts and home décor .“

### Attribute Information:

InvoiceNo : Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction.StockCode : Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.Description : Product (item) name. Nominal.Quantity : The quantities of each product (item) per transaction. Numeric.InvoiceDate : Invice Date and time. Numeric, the day and time when each transaction was generated.UnitPrice : Unit price. Numeric, Product price per unit in sterling.CustomerID : Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.Country : Country name. Nominal, the name of the country where each customer resides.
TotalPrice : Total price is multiplied from UnitPrice and Quantity of products.

