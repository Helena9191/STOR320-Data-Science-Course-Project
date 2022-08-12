# STOR320-Data-Science-Course-Project

This is the final project of STOR 320 in fall 2021. In this project, we analyzed the shared pattern of top 200 Spotify songs. In the EDA.rmd, we did exploratory data analysis (EDA) to identify worthwhile questions for further investigation. After this EDA, we had two major questions in concern: 
1. Could musical components predict song popularity on Spotify? 
2. Could musical genre predict song popularity on Spotify? 

We used the shrinkage method to build a model for the first question, while using K-nearest Neighbor algorithem to answer the second question. For the first question, we found that the variable `artist` was the biggest predictor of popularity. The shrinkage model was unfortunately not able to tell us if internal factors/musical components could truly predict song popularity. Based on this, we concluded that song popularity is driven more by external factors such as listener preferences, global trends, song marketing, and current events surrounding singers. For the second question, after using both a logistic regression model and a K-Nearest Neighbors algorithm, we concluded that we could use the model to predict whether or not a song was popular with 8% more accuracy. However, our confusion matrix told us that there is a high false negative rate among our analysis of the data, telling us that we actually underestimate the number of songs that are popular.

For complete report, please see the Final Report.html attached to this folder.
