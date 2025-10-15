# Spam Detection using Machine Learning

## Project Overview

This project focuses on building a machine learning model to classify
messages as **spam** or **ham** (not spam).
The objective is to automatically detect spam messages based on their
textual content using classical text classification methods.

## Dataset

The dataset contains labeled SMS messages with two main columns: -
**Category** -- The target variable indicating whether a message is
"spam" or "ham"\
- **Message** -- The actual text content of the SMS

## Steps and Methodology

### 1. Data Loading

The dataset was loaded using **pandas** for initial inspection. The data
was examined for structure, missing values, and class distribution.

### 2. Data Cleaning

Unnecessary characters, punctuation, and symbols were removed.\
Text normalization techniques were applied to standardize the message
content, including: - Lowercasing all text\
- Removing punctuation and stopwords\
- Applying stemming using **PorterStemmer**

### 3. Exploratory Data Analysis

EDA was performed to visualize: - The distribution of spam vs ham
messages\
- The most frequent words in both categories using **WordClouds** and
**bar plots**

### 4. Data Preprocessing

Categorical labels were encoded into numerical format using
**LabelEncoder**.\
The textual data was transformed into numerical features using: -
**CountVectorizer**\
- **TF-IDF Vectorizer**

### 5. Train-Test Split

The dataset was divided into training and testing sets to evaluate model
performance and generalization.

### 6. Model Training

The **Multinomial Naive Bayes** classifier was trained on the vectorized
text data. This model is well-suited for text classification tasks where
features represent word frequencies.

### 7. Model Evaluation

The model's performance was evaluated using: - **Accuracy Score**\
- **Precision and Recall**\
- **Confusion Matrix**

These metrics ensured balanced performance between spam and ham
classification.

### 8. Results

The model achieved high accuracy and effectively distinguished spam from
legitimate messages.\
TF-IDF vectorization combined with Multinomial Naive Bayes yielded
strong predictive results, confirming the model's suitability for
real-world spam detection tasks.

## Conclusion

This project demonstrates how Natural Language Processing can be applied
to real-world text classification problems.\
The approach combines efficient text preprocessing, feature extraction,
and probabilistic modeling to accurately detect spam messages.
