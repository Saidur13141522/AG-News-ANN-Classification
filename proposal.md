# Project Proposal: AG News Topic Classification Using an Artificial Neural Network

## 1. Research Question

Can an Artificial Neural Network using TF-IDF text features accurately classify news articles into four categories: World, Sports, Business, and Sci/Tech?

## 2. Project Objective

The objective of this project is to develop a basic Natural Language Processing classification system that can automatically categorize news articles.

The project will use TF-IDF to convert text into numerical features and an Artificial Neural Network to perform the classification.

## 3. Dataset

The project will use the AG News Topic Classification Dataset.

The dataset contains four categories:

- World
- Sports
- Business
- Sci/Tech

The standard training dataset contains 120,000 news articles, with 30,000 articles per category.

Dataset source:

https://huggingface.co/datasets/sh0416/ag_news

Original dataset information:

http://www.di.unipi.it/~gulli/AG_corpus_of_news_articles.html

The dataset contains the article title and description, which will be combined into a single text feature.

## 4. Planned Method

The project will follow these steps:

1. Load the dataset.
2. Inspect the data and target labels.
3. Combine the title and description.
4. Clean and preprocess the text.
5. Split the data into training and testing sets.
6. Convert the text into TF-IDF features.
7. Build an Artificial Neural Network.
8. Train the model.
9. Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.
10. Analyze the factors that may affect classification performance.

## 5. Two-Source Scan of Existing Work

### Source 1: Zhang, Zhao and LeCun (2015)

Zhang, Zhao and LeCun introduced the AG News dataset as part of their research on character-level convolutional neural networks for text classification. Their work compared neural approaches with traditional text classification methods including bag-of-words, n-grams and TF-IDF-based approaches.

Reference:

Xiang Zhang, Junbo Zhao, and Yann LeCun. "Character-level Convolutional Networks for Text Classification." Advances in Neural Information Processing Systems, 2015.

https://arxiv.org/abs/1509.01626

### Source 2: AG News Dataset Documentation

The AG News dataset documentation describes the construction of the topic classification dataset from the original AG news corpus. Four large categories were selected: World, Sports, Business, and Sci/Tech. The standard training set contains 120,000 examples and the test set contains 7,600 examples.

Reference:

https://huggingface.co/datasets/sh0416/ag_news

## 6. Expected Outcome

The expected outcome is a trained ANN model capable of classifying unseen news articles into one of the four AG News categories.

The project will also analyze the model's strengths and limitations and identify factors that influence classification accuracy.
