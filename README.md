# **Cryptocurrencies**
## **Overview**
The purpose of this analysis was to use data from CryptoCompare to provide a report and visualization of currently traded cryptocurrencies that can be grouped together to create a new classification system. 

Since the data does not have any known outcome, we needed to preprocess it to fit an unsupervised Machine Learning model that will enable us to run a clustering algorithm that will allow us to group the cryptocurrencies.

In this analysis we learned and applied:

**1) Data Preprocessing:**

The process of helping to prepare data for Machine Learning Algorithms.

**2) Elbow Curve**

In this method is to determine the best number of clusters needed for the algorithm to group the objects by.

**3) Principal Component Analysis (PCA)**

Statistical technique to speed up machine learning algorithms when the number of features is too high.

**4) Clustering Algorithms (KMeans)**

The process of grouping similar objects/data points into clusters.

**5) Visualization (hvPlot, Plotly)** 

Graphic libraries that allows us to create 2D and 3D graphs such as, scatter plots.

## **Resources**
* Dataset from [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist)
* Software: Python and Jupyter Notebooks
* Libraries: `Scikit-learn`, `Plotly`, `hvPlot`, `Pandas`

## **Results**

The original dataset contained 1252 entries, however only 1144 cryptocurrencies were currently trading. After Data Preprocessing, the final results identified 532 tradable cryptocurrencies.

![cluster table](https://user-images.githubusercontent.com/96033163/167334254-3cbddeb9-6dd7-4782-9383-1c0a95b0270c.png)


The Elbow Curve method showed the slope at 4. This is the number of clusters that was used for the KMeans algorithm.

![elbow curve](https://user-images.githubusercontent.com/96033163/167334249-c484c7e2-2ed3-438b-af39-4dcd125fd36c.png)


The clusters are plotted in a 3D scatter plot for visualization.

![cluster 3D](https://user-images.githubusercontent.com/96033163/167334252-56d65130-e682-40b2-921c-f2efe0f2a2c4.png)
