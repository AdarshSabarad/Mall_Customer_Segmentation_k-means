# Mall_Customer_Segmentation_k-means

Content:
You are owing a supermarket mall and through membership cards , you have some basic data about your customers like Customer ID, age, gender, annual income and spending score.
Spending Score is something you assign to the customer based on your defined parameters like customer behavior and purchasing data.

Problem Statement:
You own the mall and want to understand the customers like who can be easily converge [Target Customers] so that the sense can be given to marketing team and plan the strategy accordingly.

Mall Customer Segmentation using K-Means Clustering
This project demonstrates the process of clustering customers based on their annual income and spending score using the K-Means clustering algorithm. It helps identify different customer segments and understand their behavior for targeted marketing strategies.

Dependencies:
1. numpy
2. pandas
3. matplotlib
4. seaborn
5. scikit-learn

Data Collection and Analysis:
1. Import the necessary libraries: numpy, pandas, matplotlib, seaborn, and scikit-learn.
2. Load the customer data from a CSV file into a pandas DataFrame.
3. Analyze the data by displaying the first 5 rows, shape, and information about the dataset.
4. Check for missing values in the dataset.

Choosing the Annual Income & Spending Score columns:
1. Select the 'Annual Income' and 'Spending Score' columns as the features for clustering.
2. Store the selected features in a variable X.

Choosing the Number of Clusters:
1. Find the Within Clusters Sum of Squares (WCSS) value for different numbers of clusters (1 to 10).
2. Plot an Elbow Graph to determine the optimum number of clusters.

Training the K-Means Clustering Models:
1. Train a K-Means clustering model with the optimum number of clusters determined in the previous step.
2. Predict the cluster labels for each data point.

Visualizing all the Clusters:
1. Plot all the clusters and their centroids using a scatter plot.
2. Assign different colors to each cluster.
3. Display the centroids as cyan-colored points.
4. Add labels and title to the plot.

Usage:
1. Install the required dependencies.
2. Download the 'Mall_Customers.csv' file and place it in the same directory as the Python script.
3. Run the Python script.
4. Observe the output plot, which shows the customer groups and their corresponding centroids.
