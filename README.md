SMS Spam Classifier
A machine learning web application that classifies email and SMS messages as Spam or Not Spam using Natural Language Processing (NLP). The model is developed in Google Colab and integrated into an interactive Streamlit application for real-time predictions.
\
Dataset used for model Training: sms spam classifier on Kaggle

Features:

Classifies messages as Spam or Not Spam.

Preprocesses text using NLTK.

Converts text into numerical features using TF-IDF vectorization.

Uses a trained machine learning model (naive bayes) to predict message categories.

Provides an interactive interface built with Streamlit.

Deploys the application on Streamlit Community Cloud.

Tech Stack
Python — Core programming language

Google Colab — Model development and training

Pandas & NumPy — Data handling and numerical operations

NLTK — Text preprocessing

Scikit-learn — TF-IDF feature extraction and machine learning

Streamlit — Web application and deployment

GitHub — Version control and project hosting

How It Works

Message Input: The user enters an email or SMS message.

Text Preprocessing: The message is cleaned and tokenized using NLP techniques.

Feature Extraction: The TF-IDF vectorizer transforms the processed text into numerical features.

Prediction: The trained machine learning model classifies the message.

Result: The application displays whether the message is Spam or Not Spam.

demo - https://my-spam-classifier-1000.streamlit.app/
