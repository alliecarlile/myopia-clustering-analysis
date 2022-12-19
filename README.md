
Background

For this project, I used unsupervised machine learning to determine the likelihood of myopia (or nearsightedness) cases among groups of patients. I was provided with raw data, so I first needed to process it to fit the machine learning models. I used several clustering algorithms to explore whether the patients can be placed into distinct groups. Then, I created a visualization to share your findings with your team and other key stakeholders.


This project was completed using the following workflow: 

Part 1: Prepare the Data.

Part 2: Apply Dimensionality Reduction.

Part 3: Perform a Cluster Analysis with K-means.

Part 4: Make a Recommendation.

Part 1: Prepare the Data
Read myopia.csv into a Pandas DataFrame.


Remove the "MYOPIC" column from the dataset.


Part 2: Apply Dimensionality Reduction
Perform dimensionality reduction with PCA. How did the number of the features change?

Create a scatter plot of the t-SNE output. Are there distinct clusters?

Part 3: Perform a Cluster Analysis with K-means
Create an elbow plot to identify the best number of clusters. Make sure to do the following:

Use a for loop to determine the inertia for each k between 1 through 10.

If possible, determine where the elbow of the plot is, and at which value of k it appears.

Part 4: Make a Recommendation
Based on your findings, write up a brief (one or two sentences) recommendation for your supervisor in your Jupyter Notebook. Can the patients be clustered? If so, into how many clusters?

**Methods used:** 

Pandas

Matplotlib

StandardScaler

PCA

Kmeans

T-SNE

Jupyter Notebooks
