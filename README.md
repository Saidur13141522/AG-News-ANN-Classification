# AG News ANN Text Classification - Proposal Version

## Project Overview

This project investigates whether an Artificial Neural Network (ANN) can classify news articles into four categories using TF-IDF text features.

The four categories are:

- World
- Sports
- Business
- Sci/Tech

## Research Question

Can an Artificial Neural Network using TF-IDF features accurately classify AG News articles into their respective news categories?

## Dataset

The project uses the publicly available AG News Topic Classification Dataset.

Dataset source:
https://huggingface.co/datasets/sh0416/ag_news

Original dataset information:
http://www.di.unipi.it/~gulli/AG_corpus_of_news_articles.html

## Method

The project will:

1. Load the news dataset.
2. Combine the title and description fields.
3. Clean the text.
4. Convert text into numerical TF-IDF features.
5. Train an Artificial Neural Network.
6. Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.

## Tools

- Python
- Google Colab
- Pandas
- Scikit-learn
- TensorFlow/Keras
- Git
- GitHub

## Project Structure

```text
data/
notebooks/
README.md
proposal.md
CONFLICT_NOTES.md
.gitignore
requirements.txt
