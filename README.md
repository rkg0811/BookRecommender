# BookRecommender
## Deployment of Book Recommendation System using Flask
### Overview
A recommendation system is a type of information filtering system which is used to predict the “ratings” or “preferences” a user would given to an item. It tries to recommend items to the user according to his/her needs and taste. Recommender systems can be loosely broken down into three categories: content based systems, collaborative filtering systems, and hybrid systems (which use a combination of the other two).  
(1).Content-based filtering :- It involves recommending those items to a user which are similar in content to the items that have already been used by him/her.   
(2).Collaborative filtering :- It approach builds a model from a user’s past behaviours as well as similar decisions made by other users.  
(3).Hybrid filtering :- It approach combines the previous two approaches to obtain accurate and faster recommendations. 

### Project Work
This project proposes the use of KNN Algorithm. The k-nearest neighbors (KNN) algorithm is a simple, easy-to-implement supervised machine learning algorithm that can be used to solve both classification and regression problems. KNN will calculate the “distance” between the target book and every other book in its database, then it ranks its distances and returns the top K nearest Neighbor books as the most similar book recommendations. For finding nearest neighbors, we use ‘brute’ algorithm and ‘cosine’ metric  to calculate similarity between vectors.  
Dataset is taken from [Kaggle](https://www.kaggle.com/ra4u12/bookrecommendation)

### Requirements 
1. Libraries like
   - Pandas
   - Numpy
   - metplotlib
   - flask-ngrok
2. Google Colab.
3. Dataset - Download and save in this folder.

### Future-Work
1. Recommender fails to recommend new or less-known items.  
2. If we do spell mistake in input entry then it fails to recognise.
