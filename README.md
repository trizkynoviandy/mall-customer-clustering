# Mall Customer Clustering

This repository contains the implementation of clustering customers of a shopping mall using K-means algorithm. The data used for this implementation is a sample data consisting of customers' demographic information like age, gender, income and spending score. The aim of this project is to group mall customers by K-Means Cluster Analysis. By doing this, we can analysis what is our customer segmentation, our target, and the insight can be given to marketing team so they can plan the strategy for customers.

## Dataset

The dataset used in this project is a sample dataset containing information about customers of a shopping mall. The dataset consists of the following columns:

| Column Name        | Description                                                           |
| ------------------ | --------------------------------------------------------------------  |
| cust_id            | Unique identifier for each customer                                   |
| gender             | Gender of the customer                                                |
| age                | Age of the customer                                                   |
| income             | Annual income of the customer in thousands of dollars                 |
| spend_score        | Score assigned by the mall based on customer behavior and spending nature (1-100) |


Dataset source: [here](https://github.com/SteffiPeTaffy/machineLearningAZ/blob/master/Machine%20Learning%20A-Z%20Template%20Folder/Part%204%20-%20Clustering/Section%2025%20-%20Hierarchical%20Clustering/Mall_Customers.csv)

## Result

After running the K-means clustering algorithm on the dataset, we get the following clusters:

* Cluster 1: High income, high spending score
* Cluster 2: Low income, high spending score
* Cluster 3: Average income, average spending score
* Cluster 4: Low income, low spending score
* Cluster 5: High income, low spending score

## Requirements

In order to rerun the python script and notebook, you will need to have the following packages installed:

* matplotlib
* numpy
* pandas
* scikit-learn