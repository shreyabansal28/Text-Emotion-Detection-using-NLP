# Text-Emotion-Detection-Using-NLP

### Problem Statement

In the era of abundant textual data on the internet, handling and analyzing emotions expressed in text become challenging. This project aims to address this challenge by building a sentiment analysis model using Natural Language Processing (NLP) and basic machine learning techniques. The goal is to create a model that accurately identifies human sentiments in text.

### Dataset

The dataset consists of 40,000 labeled tweets, spanning 13 different human sentiments. For simplicity, we focus on two sentiments: 'happiness' and 'sadness,' comprising approximately 10,000 tweets. The dataset can be obtained [https://data.world/crowdflower/sentiment-analysis-in-text](link).

### Preprocessing the Data

Textual data requires preprocessing before applying machine learning models. The steps include converting text to lowercase, removing punctuation, and eliminating stop words to bring uniformity and clarity to the dataset. 

### Feature Extraction

To perform mathematical operations on text, we employ feature extraction techniques. Two methods are considered in this project: TF-IDF (Term Frequency-Inverse Document Frequency) and Count Vectors. These techniques transform the text into numeric data, enabling the use of mathematical models.

### Training Our Models

With clean and numerical representations of tweets, we train four machine learning models: Logistic Regression, Random Forest, Naive Bayes, and linear SVM. These models serve as classifiers to determine whether a given tweet is 'happy' or 'sad.' The accuracy of the models is evaluated.

### Results

Using TF-IDF features, the best model (Logistic Regression) achieved an accuracy of 54.43%, indicating room for improvement. However, by utilizing count vectors, there was a significant performance boost. The linear SVM model achieved an accuracy of 79.28%, suggesting a better fit for this specific dataset where emotion is heavily influenced by the presence of specific adjectives.

### Conclusion

This project provides a practical implementation of sentiment analysis on textual data using NLP and machine learning. The README file aims to guide users through the code structure, dataset utilization, and model training for those interested in exploring or extending the project.
