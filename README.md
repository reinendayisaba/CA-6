 **A brief description of the purpose of the program and what it is doing.**
 
This program performs customer segmentation using the K-means clustering algorithm in order to better understand the different types of customers in a given dataset. The dataset has 5 attributes and 200 entries with each entry containing information on the customer ID, gender, age, annual income in thousands of dollars, and the spending score ranging from 1-100 based on customer behavior and spending nature – a high score indicates high spending. 

Before clustering, exploratory data analysis is conducted to detect any missing values, duplicates, and to comprehend the distribution of each feature. The data is scaled and prepared for clustering using Sklearn's StandardScaler. The Silhouette method is implemented to determine the optimal number of clusters. Two sets of features are used for clustering, one using annual income and spending score, while the other uses age and spending score. The first set results in 5 clusters, while the second set yields 2 clusters.

The clustering outcomes are assessed and compared, followed by a comprehensive report that outlines the entire process and makes recommendations.

**The Needed libraries, modules, and classes**

•	The numpy library is imported as it provides a wide range of tools for data analysis and working with data in Python
•	The Pandas library is needed to load the CSV file from the URL into a DataFrame object. 
•	The matplotlib.pyplot library is needed for the different visualizations that are used in the program, such as histograms and the bar graph.
•	The seaborn library is also needed for data visualization, especially for visualizing the correlations among several columns in the dataset.
•	The standardScaler class is imported from the ‘preprocessing’ module in scikit-learn. This class is used to scale data to have a mean of zero and standard deviation of one.
•	The kMeans class  is imported from the cluster module in scikit-learn. It is used for clustering the dataset into a specified number of clusters.
•	The silhouette_score function is imported from the metrics module in scikit-learn, and it is used to evaluate the quality of a clustering solution where a higher silhouette score indicates a better clustering solution.

**How to install and run the code along with datasets to be able to run the program successfully.**

•	To be able to install and run the code successfully, the dataset must be read as a csv file into the notebook and all the needed libraries and modules need to be installed/imported. Each block of code must also be run individually and in a sequential order (one after another). 

**Acknowledgement**

The path used to access the data was provided by Prof. Arin Brahma (GitHub username: ArinB) using the link “https://github.com/ArinB/MSBA-CA-Data/raw/main/CA06/Mall_Customers.csv”


