📱 Spam SMS Detection
CODSOFT Internship – Task 4

📌 Project Overview
This project aims to classify SMS messages as either "Spam" or "Ham" (Not Spam) using Natural Language Processing (NLP) techniques and a machine learning classification model.

SMS spam detection helps in automatically filtering unwanted promotional or fraudulent messages, improving user experience and security.

We use the SMS Spam Collection Dataset and apply TF-IDF vectorization along with a Naive Bayes classifier for efficient text classification.

📂 Dataset
Source: SMS Spam Collection Dataset – Kaggle


label – Target variable (ham or spam)

message – SMS message text

🛠️ Technologies Used
Python

Pandas – Data handling

Scikit-learn – ML algorithms, model evaluation

TF-IDF Vectorizer – Text feature extraction

🚀 Steps Followed
Data Loading & Exploration

Load dataset and check label distribution.

Data Preprocessing

Convert labels to binary (ham=0, spam=1).

Clean and prepare text for vectorization.

Feature Extraction

Use TF-IDF Vectorizer to transform SMS text into numerical vectors.

Model Training

Train a Multinomial Naive Bayes classifier.

Evaluation

Accuracy score

Precision, Recall, and F1-score

Confusion Matrix

Custom Testing

Predict spam/ham for a sample SMS.

📊 Results
Accuracy: ~96%

High precision and recall for both spam and ham messages.

Fast training time due to Naive Bayes efficiency.

📈 Future Improvements
Use n-grams for better context capture.

Apply deep learning models (LSTM, BERT) for advanced text understanding.

Include more diverse datasets to improve generalization.**
