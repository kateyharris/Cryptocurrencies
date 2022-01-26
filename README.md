# Cryptocurrencies

## Overview

Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data we will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what we is looking for, we have decided to use unsupervised learning. To group the cryptocurrencies, we decided on a clustering algorithm. We’ll use data visualizations to share the findings.

This challenge consists of four technical analysis deliverables:

- Deliverable 1: Preprocessing the Data for PCA
- Deliverable 2: Reducing Data Dimensions Using PCA
- Deliverable 3: Clustering Cryptocurrencies Using K-means
- Deliverable 4: Visualizing Cryptocurrencies Results

## Results
Visualized Cryptocurrencies Results:<br>

### **Elbow Curve**<br>
![ElboCurve](https://user-images.githubusercontent.com/90797036/151260220-a894bd94-5dab-4cfe-8f79-4557e313483c.png)<br>

### **3-D Cluster**<br>
![3d](https://user-images.githubusercontent.com/90797036/151095688-89825c48-f98b-41c1-a5c2-390dde41deea.png)<br>
 - On hover:<br>
  ![3dhover](https://user-images.githubusercontent.com/90797036/151262091-ab9247f2-0da4-47e8-abfe-118240eb6cc6.png)

### **Scatter Plot**<br>
![2d](https://user-images.githubusercontent.com/90797036/151095695-753cb35d-123f-4cce-9647-39d0bbb12931.png)<br>
  - On hover:<br>
  ![2dhover](https://user-images.githubusercontent.com/90797036/151262153-d5a390cf-2bbc-4067-a6a7-2bd9ae1c51bd.png)

## Summary
Preprocessing of data required removal of nulls, filter for traderable currencies, removal of unneeded columns and conversion of text data to numeric data. There are 532 tradable cryptocurrencies. The best k-mean value for clustering cryptocurrencies determined on a Elbow Curve chart was 4. Though fun to rotate the 3D chart, the 2D chart proved more readible for this data set.
