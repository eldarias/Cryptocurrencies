# Cryptocurrencies
Module 18: Unsupervised Machine Learning and Cryptocurrencies

---
## Overview
The purpose of this challenge is to use Machine Learning to create a report for cryptocurrencies that are on the trading market and group them to create a classification system.  

The challenge consists of the following 4 Deliverables:
- Deliverable 1: Preprocessing the Data for PCA
    - This deliverable required preprocessing the dataset in order to perform PCA in Deliverable 2
- Deliverable 2: Reducing Data Dimensions Using PCA
    - This deliverable consists of using **PCA** algorithm to reduce the dimensions to three principal components and place these dimensions in a new DataFrame.
- Deliverable 3: Clustering Cryptocurrencies Using K-means
    - This deliverable consists creating an **Elbow Curve** using **hvPlot** to find the best value for K and then use **K-means** algorithm to predict the K clusters for the cryptocurrencies' data.
- Deliverable 4: Visualizing Cryptocurrencies Results
    - This deliverable consists of visualizing the results using scatter plots with **Plotly Express** and **hvplot**.
---

## Results:
Below are the results from each deliverable:
- **Deliverable 1:** Deliverable 1: Preprocessing the Data for PCA
    - <image src="./Results/Deliverable1_cryptocurrency_names_df.PNG"></p>
        - The above image shows the new DataFrame created to hold only the cryptocurrencies names.
    - <image src="./Results/Deliverable1_cleaned-crypto_df.PNG"></p>
        - The above image shows the new cleaned crypto DataFrame.
- **Deliverable 2:** Reducing Data Dimensions Using PCA
    - <image src="./Results/Deliverable2_DataFrame-with-3-principal-components.PNG"></p>
        - The above image shows the new DataFrame with the three principal components after using **PCA** to reduce the data dimensions.
- **Deliverable 3:** Clustering Cryptocurrencies Using K-means
    - <image src="./Results/Deliverable3_Elbow-Curve.PNG"></p>
        - The above image shows the **Elbow Curve** output.
- **Deliverable 4:** Visualizing Cryptocurrencies Results
    - <image src="./Results/Deliverable4_3D-ScatterPlot-with-PCA-data-and-clusters.PNG"></p>
        - The above image shows the 3D scatter plot with **Plotly Express**
    - <image src="./Results/Deliverable4_hvplot_scatter-plot.PNG"></p>
        - The above image shows the scatter plot using **hvplot**.

---

## Summary:
In summary, the challenge was successfully completed by preprocessing the provided data, reduce the data dimensions, determine the K-means and visualize the results.