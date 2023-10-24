# Final-Project-Unsupervised-Learning

## Project/Goals
In this project, I am following the instructions in the 'Unsupervised Learning - Project' notebook. This project is a single-day project to apply what we have learned about ML, specifically, unsupervised learning. I will be attempting to create a machine learning algorithm that will identify
and group similar data points from the [Wholesale Customer Dataset](https://www.kaggle.com/datasets/binovi/wholesale-customers-data-set).

## Process

- Imported the data
- Visualized the data, ensured there were no null, missing or incorrect values present in the dataset, and looked at correlations.
- Removed outliers
- Standerized the data
- Created two unsupervised learning algorithms (Kmeans and Hierarchical clustering) and analyzed the results.
- Created a PCA for feature selection

## Results

- The dataset was very clean, it contained no null, missing, or incorrect data.
- Several features had a high positive correlation with eachother. There were also outliers in most of the features which I briefly removed.
- For the clustering process, I used 'Fresh' and 'Milk' columns. From the elbow rule analysis, 3 clusters is the ideal amount. Both Kmeans and Hierarchichal clustering provided similar results and were able to cluster the data into 3 clusters. 
- From the PCA Analysis, I found out that the first three components contain about 70% of the variance ('Channel', 'region', and 'Fresh' columns).

## Challenges 
Main challenge has been time as this was a single-day project.

## Future Goals
Use a larger range of machine learning algorithms and compare results. 


