# Cryptocurrency Challenge

## Overview of Project

1. Describe the differences between supervised and unsupervised learning, including real-world examples of each.
2. Preprocess data for unsupervised learning.
3. Cluster data using the K-means algorithm.
4. Determine the best number of centroids for K-means using the elbow curve.
5. Use PCA to limit features and speed up the model.

Software: Jupyter Notebook, Pandas, HVPlot, Plotly, Sklearn

## Purpose

Using unsupervised machine learning, analyze the cryptocurrency market for a client. The client is a bank who is interested in offering a new cryptocurrency to customers, but they want an analysis on a vast range of cryptocurrencies and how they are performing in the stock market. The bank would like a classification system of the currently traded cryptocurrency so they can choose what is best for their customers. The data must be processed, reduced, clustered, and then visualized in order to give the best presentation to the clieant

## Results

### Preprocessing the Data 

![Deliverable_1_DataFrame](https://user-images.githubusercontent.com/88064181/144536019-dcd05a0e-8d0f-4aa6-959d-d015c37981cf.png)
![Deliverable_1_Get_Dummies_Df](https://user-images.githubusercontent.com/88064181/144536023-3fe943b8-2bf1-4880-badb-01a37454054e.png)
![Deliverable_1_Standardize_Data](https://user-images.githubusercontent.com/88064181/144536031-dcddea67-e085-48ea-a808-4c746c3e09ae.png)


### Reducing Data Dimensions with PCA
![Deliverable_2](https://user-images.githubusercontent.com/88064181/144536061-db37175b-ef48-49ed-a5bb-78b3c1394beb.png)


### Using K-Means to Cluster Cryptocurrencies

![Deliverable_3_Elbow_Curve](https://user-images.githubusercontent.com/88064181/144536069-a045e7cd-ed83-4731-ac5f-c236bc3e7c5a.png)
![Deliverbale_3_Predictions](https://user-images.githubusercontent.com/88064181/144536083-85a519de-2dab-483f-a5be-7f48fd26f637.png)
![Deliverable_3_Clustered_Df](https://user-images.githubusercontent.com/88064181/144536085-21af802c-0f52-4c77-af7b-25c9eac6191f.png)

## Visualizing the Results
![Deliverable_4_3D_Scatter](https://user-images.githubusercontent.com/88064181/144536094-e57413d5-4ccf-4b7d-abeb-2f193f995866.png)
![Deliverable_4_hvplot_table](https://user-images.githubusercontent.com/88064181/144536106-7ec7271e-099a-46c6-89f5-a8afc0980099.png)

![Deliverable_4_new_df](https://user-images.githubusercontent.com/88064181/144536117-2332a19e-3ac2-4f1c-a15c-d38c2a13bf30.png)
![Deliverable_4_Scatter_Plot](https://user-images.githubusercontent.com/88064181/144536120-2babd23a-0083-4416-bbb7-21c979d7cd89.png)


## Summary 
From the analysis above, and using the 3D Scatter Plot as a basis, there are three groups of cryptocurrencies. Two of the groups are very closer together and lie on similar planes. The third group is a bit more spread out and farther away from the others. This shows that many of the cryptocurrencies may perform similarly, while there will be select outliers in that performance. This data does not show if the third group of cryptocurrencies is over performing or underperforming their peers, so more analysis would have to be done to draw a sound conclusion. 
