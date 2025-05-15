
# Sentiment Analysis Project

## Overview
This project performs sentiment analysis on a dataset of customer reviews using TF-IDF vectorization and Logistic Regression. The goal is to classify reviews as either positive or negative.

## Files
- `sentiment_dataset.csv`: Contains sample customer reviews and sentiment labels.
- `sentiment_analysis.ipynb`: Jupyter Notebook with code for data preprocessing, modeling, and evaluation.
- `README.md`: This file.

## Dataset Description
The dataset contains two columns:
- `review`: Text of the customer review.
- `sentiment`: Label indicating sentiment (1 = positive, 0 = negative).

## Requirements
- Python 3.x
- pandas
- scikit-learn
- Jupyter Notebook

## Steps Performed
1. Data Cleaning: Lowercasing, punctuation removal, and stopword removal.
2. Feature Extraction: TF-IDF vectorization.
3. Model Training: Logistic Regression.
4. Evaluation: Accuracy, precision, recall, F1-score, and confusion matrix.

## Conclusion
The model achieved strong performance, demonstrating that TF-IDF with Logistic Regression is effective for basic sentiment analysis tasks.

