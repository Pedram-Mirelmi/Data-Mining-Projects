# This HW also consists of two parts
## The first part:
#### The goal of this part is to use the following model:
- Multi-Layer Perceptron Neural Network 
#### The data set of this part can be downloaded with `sklearn.datasets.fetch_lfw_people` 
### And here's the steps:
-   Load and split the dataset into 25-75 ratio for train and test
-   Use PCA to decrease the number of features
-   Apply the Multi-Layer Perceptron model 
-   Report the results and plot the confusion matrix
## The second part:
#### The second part is a bit longer. There's 3 datasets downloadable with the following link. The goal of this part is to use the following models:
-   K-Means
-   Fuzzy C-Means
-   DBSCAN
#### The link for the datasets: https://drive.google.com/drive/folders/1U0S_moZdepxK3WOYuOOjEdBFu17KjGeJ
### And here's the steps
##### K-Means part:
-   Use K-Means and choose all centroids completely random 
-   Use different amounts of K and report SSE Error for each.
-   Plot the K-Error graph to see the knee-point and find the perfect K
-   Report the perfect amount(s) of "K"
##### Fuzzy C-Means
-   repeate the previous steps with Fuzzy C-Means model
##### DBSCAN
-   Apply the DBSCAN on all three datasets
-   Report the results
### And at the end compare the results for the three model.
