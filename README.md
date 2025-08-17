# SMS Spam Classification

This project focuses on classifying SMS messages into **Spam** or **Ham (non-spam)** categories using Natural Language Processing (NLP) techniques and Machine Learning.

## Project Overview
The goal of this project is to build a machine learning model capable of detecting spam messages automatically.  
By applying text preprocessing techniques and training classification models, the system can filter out unwanted or malicious SMS messages.

## What I Did
- Collected and used a labeled dataset (`spam.csv`) containing SMS messages tagged as spam or ham.  
- Developed a Jupyter Notebook (`spam-vs-ham-sms-classification-with-nlp.ipynb`) that:
  - Loads and explores the dataset.
  - Cleans and preprocesses the text (removing stopwords, tokenization, lemmatization, etc.).
  - Converts text into numerical features using **TF-IDF vectorization**.
  - Trains and evaluates multiple machine learning models.
  - Assesses model performance using **accuracy, precision, recall, and F1-score**.
- Published the project publicly on GitHub/Kaggle for others to use and learn from.

## Why SMS Spam Classification?
SMS spam detection is an essential application of NLP because it:
- Enhances user experience by filtering irrelevant or harmful messages.
- Reduces the risk of fraud and phishing attempts.
- Helps telecom companies and apps improve communication quality.

## Tools & Libraries
- **Python**
- **Pandas & NumPy** – Data manipulation and analysis  
- **Scikit-learn** – Machine learning models and evaluation metrics  
- **NLTK** – Text preprocessing and NLP techniques  
- **Matplotlib & Seaborn** – Data visualization  
- **Jupyter Notebook** – Development environment  

