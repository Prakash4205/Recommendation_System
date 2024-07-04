# Movie Recommendation System

This project is a movie recommendation system built using the [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/). It explores three different approaches to recommend movies based on user preferences.

## Models Implemented

### 1. Universal Sentence Encoder Model

- **Description**: This model uses the Universal Sentence Encoder from TensorFlow Hub to generate embeddings for movie titles. It calculates user embeddings by averaging the embeddings of the movies each user has rated. Movie recommendations are made by computing the similarity between user embeddings and movie embeddings.
  
### 2. BERT-based Embeddings Model

- **Description**: An alternative approach using BERT-based embeddings for movie representations. It utilizes a pre-trained BERT model from TensorFlow Hub to generate embeddings for movie titles. User embeddings are computed similarly by averaging the embeddings of the movies each user has rated.
  
### 3. TensorFlow Recommenders Model

- **Description**: This model leverages TensorFlow Recommenders to build a recommendation system with user and movie embeddings. It uses embedding layers and dense layers to create user and movie representations, then applies a retrieval task to recommend movies based on user preferences.

## Usage

Open Colab notebook the given **recommendation.ipynb** file in Google Colab to explore the models.

## Dependencies

Ensure you have access to Google Colab with TensorFlow, TensorFlow Hub, TensorFlow Datasets, and TensorFlow Recommenders installed.

## Author

- [@Poorna Prakash S ](https://github.com/Prakash4205/)
