# Book Recommender System
## Overview
This project implements a book recommendation system using a Neural Collaborative Filtering (NCF) model. The model predicts ratings that users would give to books, and based on these predictions, it can recommend books to users. The system leverages a dataset of book ratings and book information to learn and make predictions.

## Dataset
The project uses the Goodbooks-10k dataset, which contains:
* ratings.csv: User ratings for books.
* books.csv: Metadata about the books.

## Model Architecture
The NeuralCollaborativeFiltering class defines the NCF model, consisting of:
* Embedding layers for users and books (i.e. each user and book is represented as a dense vector)
* Fully connected layers to learn interactions between users and books.
* Dropout layers for regularization.
