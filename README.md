# Cryptocurrencies-Unsupervised Machine Learning

## Project Overview
This project aims to create a cryptocurrencies report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for new investment in the cryptocurrency market.

Unsupervised Machine Learning is used to analyze a database of cryptocurrencies where traded cryptocurrencies are classified in groups according to their features.

This proejct involved four technical analysis deliverables.
  a. Deliverable 1: Preprocessing the Data for PCA
  
  b. Deliverable 2: Reducing Data Dimensions Using PCA
  
  c. Deliverable 3: Clustering Cryptocurrencies Using K-means
  
  d. Deliverable 4: Visualizing Cryptocurrencies Results

## Results
Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.

![tradable_crypto.png](https://github.com/Shikharbhd/Cryptocurrencies/blob/main/Resources/Images/tradable_crypto.png)

### Clustering Crytocurrencies Using K-Means - Elbow Curve
 ![elbow_curve.png](https://github.com/Shikharbhd/Cryptocurrencies/blob/main/Resources/Images/elbow_curve.png)

The elbow curve shows that inertia significantly drops up to k=4 followed by gradual drops thereafter. Hence an output of 4 clusters, k=4, was used to categorize the crytocurrencies.

### 3-D Clustered Scatter Plot
![3D_plot.png](https://github.com/Shikharbhd/Cryptocurrencies/blob/main/Resources/Images/3D_plot.png)

This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.



### 2-D Scatter Plot -Total Coins Mined vs Total Supply
![2D_plot.png](https://github.com/Shikharbhd/Cryptocurrencies/blob/main/Resources/Images/2D_plot.png)

This scatterplot compares the Total Coins Mined versus the Total Supply. 
