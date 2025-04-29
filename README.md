# SMS Spam Detection 📄
A machine learning project for classifying SMS messages as spam or ham using Logistic Regression.

## Project Overview
This project builds two models:
- A Logistic Regression model using scikit-learn
- A custom Logistic Regression model implemented from scratch with NumPy
The goal is to detect spam messages accurately while understanding the inner workings of logistic regression.
## Dataset
- Source: [UCI Machine Learning Repository - SMS Spam Collection](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)
- 5,572 SMS messages labeled as 'ham' or 'spam'.
## How to Run
1. Install required libraries:
`pip install numpy pandas matplotlib scikit-learn`
2. Open and run `spam_detection.ipynb` 
## Results
- Achieved up to **99% accuracy** on the test set.
- High precision (98%) and recall (91%) for spam detection.
