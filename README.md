# Recommendation System
This repository contains implementations of multiple recommendation systems for movies using different approaches and datasets.

## Recommendation Systems Implemented

### Recommendation System 1: Collaborative Model
**Description:**  This model is a recommendation system for MovieLens dataset using TensorFlow Recommenders (TFRS). 

**Dataset:** Movielens 100k dataset.

**Features:**

1. Loads and preprocesses MovieLens 100k dataset for user-movie ratings.
  
2. Defines a custom recommendation model using TensorFlow Recommenders (TFRS).
 
4. Trains the model with Adagrad optimizer and evaluates using Factorized Top-K metrics.

5. Implements brute-force search for efficient movie retrieval based on learned embeddings.

6. Provides personalized movie recommendations for users based on their preferences.


### Recommendation System 2: Matrix Factorization Based Model
**Description:**  A recommendation system technique that decomposes user-item interaction data into latent factors to predict missing values, used for collaborative filtering.

**Dataset:** Movielens 100k dataset.

**Features:**

1. Loads MovieLens 100k dataset, extracts user IDs, movie titles, and ratings, preparing them for training a recommender model.

2. Constructs a Matrix Factorization model using TensorFlow, consisting of user and movie embedding layers optimized with Adagrad for collaborative filtering.

3. Defines evaluation functions to assess model performance using RMSE, NDCG, and MRR, ensuring accurate recommendation quality measurement.

4. Trains the model on ratings data to learn embeddings, evaluates its effectiveness in recommending movies based on user preferences.

5. Generates top-k movie recommendations for users by leveraging learned embeddings and ranking scores, enhancing personalized user experiences in recommendation systems.


### Recommendation System 3: Neural Collaborative Filtering Model
**Description:** NCF models leverage neural networks to learn user-item interactions for enhanced collaborative filtering, providing personalized recommendations based on user preferences and item characteristics."

**Dataset:** Movielens 100k dataset.

**Features:**

1. Loads and preprocesses MovieLens 100k dataset for ratings and movie titles using TensorFlow Datasets.

2. Defines embeddings and vocabularies for user IDs and movie titles.

3. Constructs a Neural Collaborative Filtering (NCF) model using TensorFlow Recommenders for personalized movie recommendations.

4. Trains the model with rating prediction and evaluates using metrics like Root Mean Squared Error, NDCG, and MRR.

5. Provides top movie recommendations for a given user based on learned embeddings and user-item interactions.


Datasets:
The Movielens datasets (ml-100k) are used. You can download them from the Movielens website.

Dataset Dependencies:
TensorFlow, TensorFlow Recommenders, TensorFlow Datasets, NumPy, Keras

## Author : 
[Karthikeyan B](https://github.com/bKarthi22)
