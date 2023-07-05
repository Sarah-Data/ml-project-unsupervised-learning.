# Machine_Learning_Project-Unsupervised-Learning

## Project Outcomes
- Unsupervised Learning: perform unsupervised learning techniques on a wholesale data dataset. The project involves four main parts: exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and PCA.
### Duration:
Approximately 1 hour and 40 minutes
### Project Description:
In this project, we will apply unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.
The project will involve the following tasks:

-	Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.
-	Unsupervised learning: We will use the Wholesale Data dataset to perform k-means clustering, hierarchical clustering, and principal component analysis (PCA) to identify patterns and group similar data points together. We will determine the optimal number of clusters and communicate the insights gained through data visualization.

The ultimate goal of the project is to gain insights from the data sets and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked."

## Conclusions
### EDA
* The histograms show an exponential decline in the number of orders for the respected products and very high skewness with was normalized with Logarithmic transformation.

* The strongest positive correlation between Detergents paper and Grocery products which indicates that consumers would often spend money on these two types of products and any marketing or sales strategy centres around these 2 products will be profitable for the business. 

### K-MEANS/DENDOGRAM 
* Optimal number of clusters was determined using the "Elbow Curve" and the same number was used in Agglomerative Clustering

### PCA
* From the above output, we can observe that the principal component 1 holds about 45% of the information while the principal component 2 holds about 28% , 3 holds only about 10% and 4 holds 9% of the information.

* Top 4 features was determined using Random Forest which are 'Frozen', 'Fresh', 'Milk', 'Grocery' in order of importance.
