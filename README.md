Sentiment Analysis using Machine Learning

## Project Overview
This project performs Sentiment Analysis on Instagram comments using Machine Learning. It classifies text into:
Positive 
Negative 
Neutral 
The system also includes a simple UI built in Jupyter Notebook to allow users to input text and analyze sentiment instantly.

## Features
Text preprocessing (cleaning, stopword removal)
Feature extraction using TF-IDF Vectorizer
Classification using Logistic Regression
Interactive UI for sentiment prediction
Visualization using graphs

## Technologies Used
Python 
Pandas & NumPy
Scikit-learn
Matplotlib & Seaborn
Jupyter Notebook

## Dataset
The dataset used contains Instagram comments with labeled sentiments.
Example:
Comment	Sentiment
"I love this!"	Positive
"This is bad"	Negative
"Okay product"	Neutral

## Data Visualization
1️. Sentiment Distribution Graph
Shows how many comments belong to each sentiment class.
<img width="721" height="492" alt="image" src="https://github.com/user-attachments/assets/41ea42a7-b9f9-4c0e-9669-f72836c8cf8e" />

2. Confusion Matrix
Displays model performance by comparing predicted vs actual values.
<img width="654" height="496" alt="image" src="https://github.com/user-attachments/assets/d4bb6f6a-6af9-486a-ae52-d7103619d146" />

3️. Most Frequently Used Words
<img width="907" height="585" alt="image" src="https://github.com/user-attachments/assets/b0ec25ca-6476-4d0b-a9a3-5105630dc4bf" />

4. Distribution of post lengths
<img width="697" height="489" alt="image" src="https://github.com/user-attachments/assets/d7a76d61-e61f-4d10-adf0-33a0153cc3e8" />

Displays predicted sentiment
Example:

Input:
"I really love this product!"

Output:
Positive 😊
