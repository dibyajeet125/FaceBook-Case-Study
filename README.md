# FaceBook-Case-Study
Developed a graph-based machine learning model to predict user connections on a social network dataset of 1.78M nodes and 7.55M edges, achieving a test F1 score of up to 0.85 using Random Forest and 0.71 with XGBoost.


This project involves developing and evaluating machine learning models to predict connections between users in a large social network. The dataset consists of a directed graph with 1.78 million nodes and 7.55 million edges, representing users and their connections.

Project Overview

The goal of this project is to leverage graph-based features and machine learning techniques to accurately predict whether two users are connected. This involves:

Data Preprocessing: Cleaning and preparing the dataset for analysis.

Feature Engineering: Developing graph-based features such as:

Adamic/Adar Index: Measures the similarity between two nodes based on their common neighbors.

Follows Back: Checks if a user follows another user back.

Shortest Path Length: Calculates the shortest path between two nodes.

Weight Features: Computes node-specific weights based on followers and followees.

Centrality Measures: Includes PageRank, Katz Centrality, and HITS scores.

SVD Features: Extracts latent representations from the adjacency matrix.

Model Development: Implementing and tuning two primary models:

Random Forest Classifier: Achieved a test F1 score of up to 0.85.

XGBoost Classifier: Achieved a test F1 score of up to 0.71.

Model Evaluation: Assessing model performance using metrics such as F1 score, confusion matrices, and ROC curves.

Key Findings

Feature Importance: PageRank scores, Katz Centrality, SVD vectors, and weight-based features were identified as critical contributors to model performance.

Model Comparison: Random Forest outperformed XGBoost in this case study, but both models demonstrated the potential for predicting user connections.

Future Work

Ensemble Methods: Exploring techniques like stacking or voting classifiers to combine the strengths of Random Forest and XGBoost.

Hyperparameter Tuning: Further refining hyperparameters to improve model generalization on unseen data.

This project showcases the application of graph-based machine learning techniques to real-world social network data, highlighting the importance of feature engineering and model selection in achieving high predictive accuracy.
