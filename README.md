# Countries

Our objective in this project is to define how to use financial resources effectively by categorizing the countries based on health and socio-economic factors that influence the overall development of the country. Thus, the HELP organization can deliver those resources to the country that needs the most aid. In this project, we cluster countries by using K-means clustering. The Principal Component Analysis (PCA) will be utilized for dimension reduction and anomaly detection.  

# Dataset Information 

The dataset is collected from [the Kaggle website](https://www.kaggle.com/rohan0301/unsupervised-learning-on-country-data?select=data-dictionary.csv). The data contains 167 columns and 10 variables. 

# The Result 

The end result can be viewed in this link : https://rpubs.com/Fib_Gro/Clustering_Countries

# Attachment 

- File csv
- Rmd file
- Picture png

# Conclusion 

1. The dimension reduction is performed in this dataset by using PCA. We choose 5 PCs to represent the original dataset. With these PCs, we reduce approximately 45% of the dimension from the original dataset while retaining almost 95% of the information. The result from PCA can be utilized for machine learning applications.
2. The optimum number of clusters is obtained by using Elbow, Silhouette and Gap Statistic. The majority rule suggests that the optimum k is 4 (four).
3. The goodness of fit suggests that the clusters fairly represent the distribution of the original dataset.
Cluster I contains countries associated with high levels of child mortality and population growth. This makes cluster 1 as a priority cluster to get assistance from the HELP organization. Furthermore, based on the value of child mortality, Haiti can be categorized as the country with the most in need of financial aid.

