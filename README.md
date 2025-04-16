# Naive Bayes SMS Spam Classification

This project implements a Multinomial Naive Bayes classifier from scratch to detect spam SMS messages.

## Project Overview
- Developed a text classifier using the Naive Bayes algorithm
- Implemented from scratch using only NumPy and basic Python libraries
- Achieved 98% accuracy on the test dataset

## Dataset
The SMS Spam Collection Dataset from Kaggle was used, containing labeled SMS messages (spam/ham).

## Implementation Details
- Text preprocessing (tokenization, stop word removal)
- Bag-of-words vectorization
- Multinomial Naive Bayes algorithm with Laplace smoothing
- Logarithmic probability calculation for numerical stability
- Comprehensive evaluation metrics

## Results
- Accuracy: 0.9874
- Precision: 0.9720
- Recall: 0.9329
- F1-score: 0.9842

## Theoretical Foundation
Includes detailed explanation of Bayes' Theorem and its application to text classification.

## File Structure
- `naive_bayes_sms_classification.ipynb`: Main implementation notebook

## Requirements
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
