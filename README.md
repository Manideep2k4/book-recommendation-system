The Book Recommendation System is a machine learning-based project that suggests books similar to a given book using the k-Nearest Neighbors (k-NN) algorithm.
The system analyzes book features such as ratings, language, and number of reviews to find the most relevant recommendations.

Finds similar books based on user input.
Uses k-NN (k-Nearest Neighbors) for book similarity measurement.
Analyzes book ratings, language, and review counts to determine recommendations.
Visualizes book data with Seaborn and Matplotlib.

 Dataset contains:
Title
Authors
Average Rating
Number of Pages
Ratings Count
Language

Data Cleaning & Preprocessing:
  Handles missing values.
  Converts rating data into categorical bins.
  One-hot encodes categorical variables (e.g., language, rating groups).
Feature Scaling:
  Uses MinMaxScaler to normalize data.
Building the Recommendation Model:
  Trains a k-Nearest Neighbors (k-NN) model using the Ball Tree algorithm.
Generating Recommendations:
  Finds books similar to a given book title based on k-NN distance metrics.
  
