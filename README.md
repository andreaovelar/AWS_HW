
# Amszon Web Services_HW- HW 9
# Clustering Crypto -AWS

### Clustering Crypto
#### 1.Data Preprocessing: Prepare data for dimension reduction with PCA and clustering using K-Means.
* Raw input obtained from https://min-api.cryptocompare.com/data/all/coinlist.

![table](https://github.com/andreaovelar/AWS_HW/blob/master/pre.PNG "pre")

#### 2.Reducing Data Dimensions Using PCA: Reduce data dimension using the PCA algorithm from sklearn.
* Selecting first three principal components 

![table](https://github.com/andreaovelar/AWS_HW/blob/master/pca.PNG "pca")
* Constructing elbow curve, we can see that for k=4 inertia starts to drop and there is not too much benefit on extending the clusters further. 

![table](https://github.com/andreaovelar/AWS_HW/blob/master/curve.PNG "curve")

#### 3.Clustering Cryptocurrencies Using K-Means: Predict clusters using the cryptocurrencies data using the KMeans algorithm from sklearn.
* hvplot to show the clusters and the 3 pc coordinates 
![table](https://github.com/andreaovelar/AWS_HW/blob/master/plot.PNG "plot")

#### 4.Visualizing Results: Create some plots and data tables to present your results. 

* table of coins information 
![table](https://github.com/andreaovelar/AWS_HW/blob/master/table.PNG "table")

* Plots coins mined vs total coins 
![table](https://github.com/andreaovelar/AWS_HW/blob/master/plot2.PNG "plot2")

#### 5.Challenge: Deploy your notebook to Amazon SageMaker. 

