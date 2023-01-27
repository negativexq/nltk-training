# nltk-training

# Project Title: Stress Analysis in Social Media

This project uses a dataset collected from the Reddit platform that contains grouped messages with and without stress. The goal of this project is to use natural language processing techniques to preprocess the data, and then use machine learning algorithms to predict whether the messages in the dataset contain stress.

## Dataset
The dataset used in this project can be found on [Kaggle](https://www.kaggle.com/datasets/monishakant/dataset-for-stress-analysis-in-social-media).

## Preprocessing
The data set is preprocessed by performing the following steps:
- Removing stop words from the sentences
- Lemmatizing the sentences to convert words into their root form
- Using the Porter stemmer to further root the words

## Vectorization
TF-IDF Vectorizer is used to digitize the sentences, which turns the sentences into a specific sequence of numbers that reflect the contents of the sentences.

## Machine Learning
The numerical data obtained from the preprocessing and vectorization steps is then tested using Logistic Regression ,Random Forest and SVM algorithms. Hyperparameter search is added to these algorithms to determine the most appropriate parameters for the algorithms to give more accurate results.

## Requirements
- Python 3.x
- pandas
- nltk
- sklearn
- matplotlib

## Usage
1. Clone the repository
2. Install the requirements
3. Run the jupyter notebook
