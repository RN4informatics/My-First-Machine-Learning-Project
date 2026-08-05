# Machine Learning Project

Using a dataset of 200 shopping mall customers, mall management wants some summary information about customer spending.  


The data is found in the file “mallcustomers.csv”


Modules used:  numpy, pandas, matplotlib

Classes used: KMeans, StandardScaler, PCA




Each customer record consists of a unique identifier (CustomerID), gender
(Gender), age (Age), annual salary (Income), and an assigned score, between 1 and 100,
based on the customer’s purchase habits and several other factors (SpendingScore). 

Preprocessing:  
Preview the dataset and make note of the data types for each variable. 
Convert Income to a numeric value by removing the substrings “,” and “USD” from the data. 
The model will be using only Income and SpendingScore, so other features that aren’t useful for segmentation are excluded.
Segment customers based on Income and SpendingScore. 
Run some summary statistics for Income and SpendingScore. 
(Since there appears to be a significant difference in the scale of the Income and SpendingScore features), normalize this data using the z-score normalization approach.

Data Clustering: 
Apply k-means to cluster the data using the Elbow Method to determine an optimal number of clusters. 
Visualize the results. (Random seed is 42 so that results can be replicated).
Name the clusters based upon their respective locations on the visualization. 

Report spending habits for the clusters to mall management regarding age, gender & spending patterns.
Use the features Gender and Age to determine the gender distribution and mean age for each cluster
Create two dummy variables—Male and Female—to represent the Gender feature to note additional information about each cluster

***** This was my first Machine Learning Project 
