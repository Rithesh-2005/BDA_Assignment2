# BDA_Assignment2
Big Data Analysis course work  - Assignment2

This repository consists of three parts:
1. Digit Classification with PySpark Random Forest
   This project showcases multi-class classification of handwritten digit images using the Random Forest classifier from PySpark MLlib, trained on the popular digits dataset from Scikit-learn.
   What It Does?
     1. Loads the digits dataset using sklearn.datasets.load_digits
     2. Converts the data into a PySpark DataFrame
     3. Assembles pixel values into feature vectors using VectorAssembler
     4. Splits data into training and testing sets
     5. Trains a Random Forest model with 100 trees
     6. Evaluates the model using accuracy metric
     7. Optionally plots the confusion matrix for performance insight
2. KMeans Clustering on Synthetic Blob Data using PySpark
  This project demonstrates how to apply KMeans clustering on synthetically generated data using PySpark. It showcases the integration of Spark MLlib with Pandas, Scikit-learn, and Seaborn for end-to-end clustering and visualization.
  What It Does?
    1. Generates synthetic 2D data using make_blobs() from sklearn.datasets.
    2. Converts the dataset into a PySpark DataFrame.
    3. Prepares feature vectors using VectorAssembler.
    4. Applies KMeans clustering using PySpark MLlib.
    5. Converts results back to Pandas for easy visualization.
    6. Plots clustered data vs original labels using matplotlib and seaborn
3. Movie Recommendation System using PySpark ALS
  This project builds a movie recommendation system using the Alternating Least Squares (ALS) algorithm from PySpark MLlib, based on the MovieLens 100K dataset.
  What It Does?
    1. Loads user ratings and movie metadata from the MovieLens 100K dataset
    2. Trains a collaborative filtering model using the ALS algorithm
    3. Predicts movie ratings on a test set and evaluates using Root Mean Squared Error (RMSE)
    4. Generates and displays Top 10 personalized movie recommendations for each user

If you feel comfortable using Colab visit https://colab.research.google.com/drive/1A0oGVCABZRP4GVfifdvXttQL0IzpYQut?usp=sharing
