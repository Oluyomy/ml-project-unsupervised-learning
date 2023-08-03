# machine_learning_project-unsupervised-learning

## Introduction:
unsupervised learning techniques is applied to a real-world data set and data visualization tools to communicate the insights gained from the analysis.

## Project  Goals
- The goal of this unsupervised learning techniques on a wholesale data dataset is to identify patterns and correlation between variables.
- To perform k-means clustering, hierarchical clustering, and principal component analysis (PCA) to identify patterns and group similar data points together
- To determine the optimal number of clusters and communicate the insights gained through data visualization.


# Process
Step 1: Obtaining data
This dataset is originally  fron Kaggle unsupervised learning machine learning project on a "Wholesale Data" dataset containing information about various products sold by a grocery store.
[Kaggle Dataset](https://www.kaggle.com/datasets/binovi/wholesale-customers-data-set)

Step 2: Loading and understanding the dataset.
- Working with Wholesale_Data.csv data to understand  each feature in the dataset.
- Having a general understanding and information about the relationship between various features .

Step 3: Exploratory data analysis and pre-processing 
- clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers.
- Create a displot, histplot,Densityplot, scatterplot and pairplot to look at the distributions of different variables and their correlation.
- summary statistics such as mean, median, and standard deviation for each column of the dataset. 
- Learn the trend and detect outlier or possible factor that can affect the data output.
- Create heatmap to take a closer look at the corellation.
- Detect and handle outliers.
- Structure the data for efficient analysis.
- Split the into training and testing for appropriate training .
- Scale the data 

Step 4: Performed k-means clustering:
- To perform the k-means clustering analysis,we will pre-process the dataset
- Determine the optimal number of clusters.
- Initialize the centroids.
- Assign data points to clusters..
- Update the centroids and repeat until convergence.

step 5: Hierarchical clustering.
- The'ward' linkage method in hierachical clustering was used to minimizes the variance of distances between clusters. 
- Then we created a dendrogram to visualize the hierarchical structure of the data.
- Determine the optimum number of clusters based on the vertical lines (threshold_distance) where it forms distinct clusters.

step 6: principal component analysis (PCA): was done to identify patterns, reduce the dimensionality of the data set, group similar data points together.
-  Determine the optimal number of clusters.
-  Communicate the insights gained through data visualization.



## Results
- There are no missing values in the dataset.
- From the dataset, two columns where remove for obvious reasons(Channel and Region).
- It was observed that the variables were not normal distributed. They are skewed to the right indicating outliers.
- Based on the correlation coefficient, we can interpret thus that  there is almost no linear correlation between 'Fresh' and 'Grocery' spending which is  -0.012
- There is a weak positive  correlation between Detergents_paper and Delicassen 0.069.
- There is a significant relationship  between Milk and Detergents_paper 0.66, meaning as the sales of milk increases, so is the sales of Detergents_paper.
- There is a strong positive correlation between Grocery and Detergent_paper this indicates that as Grocery sales increases so is Detergents_paper.
- Based on the elbow plot in Kmeans,the inertia drops very quickly as we increase k up to 4.
- Analyzing the dendrogram plot shows the relationship  of different feature,threshold_distance is selected based on the height of the dendrogram where it is clear to separate the clusters and this is around 4.
- The first 3 principal components captured most of the variance in the data giving approximately 90% of the model prediction which accounts for the larger part of the model that can be retained.
## conclusion
 Based on the Elbow plot, the Hierarchical clustering dendogram, we can ascertain that the optimum number of clusters most likely is 4.
 ## Challenges
   Time constraint to explore more on the principal component.