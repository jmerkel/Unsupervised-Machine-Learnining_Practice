# jmerkel_Module_18
## Unsupervised Learning Challenge

### Project Description
This project covered Unsupervised Machine Learning to group cryptocurrencies together. This was done through a process of Preprocessing to clean the data, Reduce Dimensions using PCA (limit the amount of factors that contribute to grouping), Clustering via K-Means (create the groups), and Visualizing using the data via Plotly Express and hvplot.

### Project Summary
After cleaning the cryptocurrency options from the dataset to only those with valid data and are trading, the K-Means method from the sklearn library determined that there were 4 different groups. Upon further review, the groups are really '3' + 1 outlier (BitTorrent).

Though the groupings are clear, the visuals of the Total Coin Supply to Total Coins Mined require additional work to be legible. Due to the large differences in Supply/Mining of each cryptocurrency, the axis of the 2D scatterplots are skewed to a few outliers.

In summary, Accountability Accounting can easily offer 4 different classification groups of cryptocurrencies (In reality, a group of 1 can be risky, 3 groups is more realistic). From this grouping and the scatterplots of supply & mining, Accountability Accounting can subject each cryptocurrency group to additional review and determine if the outliers (in supply/mining) are subject to additional risk.
