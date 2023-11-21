# Machine Learning : Unsupervised Learning

## Project Outcomes
- This project was carried out using Unsupervised Learning. The objective of the project is to perform unsupervised learning techniques on a wholesale data dataset with the aim of understanding hidden patterns in the dataset and communicate findings using appropriate visualizations. The project involves four main parts: exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and PCA.

### Project Description:

The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.
The following tasks were carried out in the course of the project:

-	Exploratory data analysis and pre-processing: The datset was imported alongside necessary libraries and initial exploratory analysis was carried out on the data. The following was done:
  - Used a heat map to understand and visualize the relationships between the different variables.
 	- Identify and handle missing values.
 	- Used a box plot to identify outliers and z-score to handle outliers,
 	- Used a histogram to understand the current data distribution and applied log transformation to handle long-tailed data distributions.
 	- Standardized the dataset to a mean of 0 and a variance of 1.
 	- Used PCA analysis to highlight important variables and reduce noise in the dataset.
  
-	KMeans Clustering: The goal here is to group similar products together into clusters based on their attributes. The following was carried out:
  - Used the Elbow method to determine the optimal number of clusters.
 	- Initialized the centroids and assigned data points to clusters.
 	- Used decriptive statistics to understand the characteristics of each cluster.

- Hierarchical Clustering: The goal here is to identify patterns and group similar data points together in a hierarchy. The following was carried out:
  - Created a dendogram to understand the patterns in the data and see grouping of datasets.

- PCA Analysis:
  - Created a scatter plot to draw conclusions about the underlying structure of the data.

**Conclusions**
As earlier highlighted, the ultimate goal of the project is to gain insights from the data sets and communicate these insights using appropriate visualizations and metrics. The following was deduced from the unsupervised learning of the dataset:

- No noise was identified. All available columns within the dataset provides some insights to the entire story as observed by carried out PCA Analysis.
- In line with the PCA Analysis, optimal number of clusters could not be defined. As observed by the Elbow graph, the data points does not converge at any specific point.
- Also, there was no observable correlation between the descriptive statistics (mean etc) of each cluster of the features in the dataset. This tells us that there is no cleary defined clusters in the dataset.
- The dendogram reveals that at a high level, there are two broad grouping of data.
- In summary, we are unable to highlight any patterns from the dataset. 
