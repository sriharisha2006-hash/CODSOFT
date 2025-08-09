🎬 Movie Genre Classification
CODSOFT Internship – Task 1

📌 Project Overview
This project is part of my CODSOFT Machine Learning Internship.
The goal is to predict the genre of a movie based on its plot summary using Natural Language Processing (NLP) techniques and a machine learning classification model.

The dataset contains movie titles, genres, and descriptions. We transform the descriptions into numerical features using TF-IDF Vectorization, then train a Logistic Regression model to classify movies into their respective genres.

📂 Dataset
Source: IMDB Genre Classification Dataset – Kaggle

ID – Unique identifier for the movie.

TITLE – Name of the movie.

GENRE – Target variable (class label).

DESCRIPTION – Plot summary of the movie.

🛠️ Technologies Used
Python

Pandas, NumPy – Data handling

Scikit-learn – Model building & evaluation

Matplotlib, Seaborn – Visualization

TF-IDF Vectorizer – Text feature extraction

🚀 Steps Followed
Data Loading & Exploration

Load the dataset and inspect the first few rows.

Check the distribution of genres.

Data Preprocessing

Handle missing values.

Remove unnecessary columns (ID, TITLE).

Split data into training and testing sets.

Text Feature Extraction

Convert movie descriptions into numerical vectors using TF-IDF.

Model Training

Train a Logistic Regression model for multi-class classification.

Evaluation

Calculate Accuracy, Precision, Recall, and F1-score.

Plot the confusion matrix for visualization.

Testing with Custom Input

Predict the genre for a custom plot summary.

📊 Results
Accuracy: ~54% (Baseline model without hyperparameter tuning)

High accuracy for common genres like drama and documentary.

Struggles with rare genres due to class imbalance.

📈 Future Improvements
Apply n-gram features (bigrams, trigrams) for better context.

Use class weighting to handle imbalanced data.

Experiment with Naive Bayes, Random Forest, and BERT-based models for higher accuracy.

Remove very rare genres or merge similar categories to reduce label sparsity.
