# IMDb Sentiment Analysis

## Project Overview

This project analyzes IMDb movie reviews and builds a machine learning model to classify reviews as **Positive** or **Negative**.

The project focuses on text data preprocessing, Natural Language Processing (NLP), feature extraction using TF-IDF, and sentiment classification using Logistic Regression.

## Project Objectives

* Analyze movie review text data
* Clean and preprocess text data
* Apply Natural Language Processing techniques
* Convert text into numerical features using TF-IDF
* Build a sentiment classification model
* Evaluate the classification model using standard performance metrics
* Visualize model results using a Confusion Matrix

## Dataset

The project uses the **IMDb Dataset**, which contains movie reviews labeled as:

* Positive
* Negative

For faster experimentation, a sample of **20,000 reviews** is used from the dataset.

## Data Preprocessing

Several preprocessing techniques are applied to the review text:

* Removing mentions
* Removing hashtags
* Removing URLs
* Removing numbers
* Removing emojis and special characters
* Converting text to lowercase
* Removing punctuation
* Tokenization
* Removing English stopwords
* Stemming using Porter Stemmer
* Lemmatization using WordNet Lemmatizer

The cleaned text is stored in a new column called `clean_review`.

## Feature Extraction

### TF-IDF

The main feature extraction technique used in the project is **TF-IDF (Term Frequency–Inverse Document Frequency)**.

A maximum of 5,000 features is used to represent the cleaned movie reviews numerically.

The project also includes a **Bag of Words (BoW)** approach for comparison.

## Machine Learning Model

### Logistic Regression

Logistic Regression is used as the main classification model.

The dataset is divided into:

* 80% Training Data
* 20% Testing Data

The model predicts whether each movie review is positive or negative.

A Linear Regression experiment is also included for comparison, with a 0.5 threshold used to convert continuous predictions into binary classes.

## Model Evaluation

The Logistic Regression model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

The Confusion Matrix is used to visualize the model's correct and incorrect predictions for both sentiment classes.

## Technologies & Libraries

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## NLP Techniques

The project demonstrates practical NLP techniques including:

* Text Cleaning
* Tokenization
* Stopword Removal
* Stemming
* Lemmatization
* TF-IDF Feature Extraction
* Sentiment Classification

## Project Workflow

```text
IMDb Dataset
      ↓
Data Loading
      ↓
Data Exploration
      ↓
Text Cleaning
      ↓
Tokenization
      ↓
Stopword Removal
      ↓
Stemming & Lemmatization
      ↓
TF-IDF Feature Extraction
      ↓
Train / Test Split
      ↓
Logistic Regression
      ↓
Model Evaluation
      ↓
Confusion Matrix
```

## Project Structure

```text
IMDB_project/
│
├── IMDb Sentiment Analysis-Copy1.ipynb
├── README.md
└── IMDB Dataset.csv
```

## Key Skills Demonstrated

* Python Data Analysis
* Natural Language Processing
* Text Data Preprocessing
* Feature Engineering
* Machine Learning
* Binary Classification
* Model Evaluation
* Data Visualization

## Author

**Abdelrahman Ahmed Abdelshafi**

مشروع خاص بتحليل اراء عن الافلام
