# Machine Learning Exercises
Exercises going through Regression, Classification, Clustering, Recommenders and Deep learning...
#### Marcelo Povoa

<hr>

# Foundation Examples

### 1.1 Estimating House Prices (Regression)
Regression estimating house prices based on previous house sales, using features like house size (sqft), number of bathrooms and so on...
It uses a King County House Sales dataset. 

### 1.2 Product sentiment analysis (Classification)
Analysis of Amazon product reviews estimating if the reviews were positive or negative, as well as picking the most positive and most negative reviews.

### 1.3 Which Wikipedia article would be similar to one you just read (Clustering)
Clustering wikipedia articles of people aiming at finding the ones most similar to each one.

### 1.4 Product recommender: songs (Recommender)
Based on a dataset of songs listed by users, get song recommendations per user and also check which songs are being recommended the most.

### 1.5 Deep learning for image retrieval (Deep learning)
Using a dataset with animals, compare raw pixel vs deep learning classifiers. Then use nearest neighbor models to get predictions and calculate its accuracy.



# Regression
Multiple ways go to through regression estimating house prices based on previous house sales, using features like house size (sqft), number of bathrooms and so on...

### 2.1 Estimating House Prices (Simple Regression) - Manual calculation
This time the simple linear model and RSS are manually calculated instead of using a model from a python package.


### 2.2 Estimating House Prices (Multiple Regression) - Manual calculation
We calculate the linear model and RSS manually for a multiple regression case instead of using python packages.


### 2.3 Estimating House Prices (Multiple Regression) - Feature Selection and Lasso
We go over feature selection and Lasso.

### 2.4 Overfitting demo using Ridge Lasso Regression
On a synthetic dataset of sinusoidal form, see the weight behavior with different polynomial degrees. Then using Ridge regression, see the behavior of the lambda penalty (l2 penalty). Finally using Lasso see how it impacts overfitting.

### 2.5 Overfitting demo using Ridge Regression with cross validation
We'll test L2 values and pick the best one using cross validation

### 2.6 Estimating House Prices (Multiple Regression) - Manual Gradient Descent Calculation
We manually calculate the Gradient Descent of the regression algorithm for multiple regression cases.

### 2.7 Estimating House Prices (Multiple Regression) - Feature Selection and Lasso
Feature selection with Lasso.

### 2.8 Estimating House Prices (Multiple Regression) - Lasso with coordinate descent solver
We build our own lasso solver using coordinate descent.

### 2.9 Estimating House Prices (Multiple Regression) - Nearest Neighbor Kernel Regression
We build our own nearest k-neighbor kernel regression.



# Classification - Product Reviews


### 3.1 Product sentiment analysis (Classification) - logistic from scratch
Analysis of Amazon product reviews estimating if the reviews were positive or negative, as well as picking the most positive and most negative reviews.
For this case, a logistic regression sentiment analysis was created from scratch.

### 3.2 Product sentiment analysis (Classification) - logistic with L2
For this case, a logistic regression sentiment analysis with L2



### 4.1 Identifying safe loans with decision trees
Using a loan dataset we'll estimate if loans are safe or risky.

### 4.2 Identifying safe loans with decision trees - Binary decision trees
Identifying safe loans using binary decision trees

### 4.3 Avoiding overfitting decision trees
Testing how to avoid overfitting decision trees



### 5.1 Boosting 
We explore emsemble methods / boosting

### 5.2 Boosting a decision stump
We explore boosting a decision stump.




# Precision and Recall

### 6.1 Exploring precision and recall
Using a Amazon product review dataset, we aim to understaind precision-recall in the context of classifiers.



# Clustering and Retrieval

### 7.1 Improving Nearest Neighbors with Locality Sensitive Hashing
Implementing a LSH algorithm for approximate nearest neighbor search using a wikipedia people dataset.

### 7.2 K-Means with text data
Clustering wikipedia articles with k-means, exploring random initialization and impact of number of clusters.

### 7.3 Fitting Gaussian Mixture Models with EM
Implementing an EM algorithm for a Gaussian mixture model.

### 7.4 Fitting a diagonal covariance Gaussian mixture model to text data
Using an EM implementation to fit a Gaussian mixture model with diagonal covariances to a subset of the wikipedia dataset.

### 7.5 Latent Dirichlet Allocation (LDA) for Text Data
Using the wikipedia dataset, fit a LDA model and explore results.

### 8.1 Hierarchical clustering
Recursively bipartition data using k-means.
