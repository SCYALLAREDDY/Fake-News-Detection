# Fake News Detection

## Overview

This project aims to classify news articles as either REAL or FAKE using machine learning. The model is trained using a dataset of news articles and labels. It leverages Natural Language Processing (NLP) techniques, specifically TF-IDF for text vectorization and a Passive Aggressive Classifier for classification.

## Requirements

To run this project, you need the following Python packages:
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `wordcloud`

You can install these packages using pip.

## Usage

1. **Load and Preprocess Data:** 
   - The dataset `news.csv` is loaded and split into training and test sets. The text content and labels are extracted for model training.

2. **Feature Extraction and Model Training:**
   - The TF-IDF Vectorizer converts text data into numerical features. A Passive Aggressive Classifier is used to train the model on the processed data.

3. **Model Evaluation:**
   - The model's performance is evaluated using accuracy, a classification report, and a confusion matrix. This helps to understand how well the model distinguishes between REAL and FAKE news.

4. **Additional Visualizations:**
   - A word cloud visualizes the most common words in the dataset, providing insight into prevalent terms.
   - A bar plot of the top features shows the most important words used by the model for classification.

