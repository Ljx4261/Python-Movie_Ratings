# Crime-Analysis-in-Boston-
<h1 align="center">Hi 👋, I'm Jessie</h1>
<h3 align="center">A passionate data scientist</h3>

- 🔭 I’m currently working on Movie Recommendations


<h3> Motivation: </h3>

As a website to watch movies, we will make more money if more customers are able to find their favorite films through our services, so a good recommendation system will be the key to our success. Based on this idea, I tried myself to build a simple recommendation system using the data from GroupLens (https://grouplens.org/datasets/movielens/latest/) to understand how a recommendation system is constructed. In this way, I will be prepared when I become a data scientist for a movie service company in the future.

Author: Jessie

 
<h3> Steps:</h3>

- Data exploration (EDA): obtain the general information about the data, including the total number of users, total number of movies and the list of unrated movies .etc; OLAP analysis to find the genres, all movie categories and number of movies in each category.
- Data preprocessing: keep only the userId, movieId and rating columns; change the data type from string to numeric; separate the data to 80% training and 20% testing.
 -   Model building: fit the alternative least square (ALS) model on the training data; select the hyper-parameters through grid search and 4-fold cross validation; evaluate the tuned model on testing data.
 -   Model application: apply the model on the whole rating data to see the performance; use the model to make recommendations to users with given userIds; use one of the model output: item factor to find similar movies for movies with given movieIds.
<h3>Output and conclusion: </h3>

- The best model for ALS has the parameters to be: maxIter=10, regParam=0.1, rank=5, alpha=0.1. The rooted mean squared error (RMSE) on the testing data is 0.88 and on the whole dataset is 0.69.
- As mentioned in the steps, the ALS model is not only able to provide recommendations, but also able to mine latent information, which is the latent variable in matrix factorization. This latent information is helpful that it can help us gain some deeper insight. In this project, this information was used to measure the difference between any two movies so that we are able to find similar movies .



<h3 align="left">Connect with me:</h3>  https://www.linkedin.com/in/jessielan/
<p align="left">
</p>
