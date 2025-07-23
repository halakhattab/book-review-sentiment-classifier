# Book Review Sentiment Classifier

This repository contains my final machine learning project for Cornell’s **Machine Learning Foundations** course.

## Project Overview

The goal of this project was to build a supervised machine learning model that can classify book reviews as positive or not, based on their textual content. I used TF-IDF vectorization and trained a logistic regression model, achieving an F1-score of 0.82 with balanced precision and recall.

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn (TF-IDF, Logistic Regression, Naive Bayes)
- Seaborn, Matplotlib (for data visualization)

## Dataset
The dataset used is `bookReviewsData.csv`, which contains book review text and a binary label indicating whether the review was positive.

## Final Results
- **Logistic Regression** achieved:
  - **Accuracy:** 82%
  - **F1-score:** 0.82
- **Multinomial Naive Bayes** was also tested and yielded comparable results.

## File Descriptions
- `BookReviewClassifier.ipynb`: Jupyter Notebook containing the full machine learning pipeline.
- `bookReviewsData.csv`: Dataset used for training and evaluation.

## Notes
This repository is part of my Cornell portfolio and is set to private to comply with academic integrity policies.
