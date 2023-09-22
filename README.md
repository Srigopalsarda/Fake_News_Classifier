# Fake News Classifier

## Overview
The Fake News Classifier is a project that uses Natural Language Processing (NLP) techniques to classify news articles as either fake or real. This repository contains two Jupyter Notebook files that demonstrate two different approaches to accomplish this task:

1. **FakeNewsClassifier TFIDF.ipynb**: This notebook implements a fake news classifier using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization as a feature extraction technique.

2. **FakeNewsCount_vectorizer.ipynb**: This notebook implements a fake news classifier using Count Vectorization as a feature extraction technique.

## Motivation
The proliferation of fake news has become a significant concern in today's digital age. This project aims to provide a tool to distinguish between fake and real news articles automatically. It utilizes machine learning and NLP techniques to create a classifier capable of identifying potentially deceptive news sources.

## Usage
To use the Fake News Classifier notebooks, follow these steps:

1. Clone the repository to your local machine:

```bash 
git clone https://github.com/yourusername/fake-news-classifier.git
cd fake-news-classifier
```

2. Open and run the Jupyter Notebook of your choice:

- **FakeNewsClassifier TFIDF.ipynb**: This notebook uses TF-IDF vectorization. Follow the instructions in the notebook to execute the code and train the classifier.

- **FakeNewsCount_vectorizer.ipynb**: This notebook uses Count Vectorization. Similar to the previous notebook, follow the instructions within to run the code and train the classifier.

3. Customize the classifier as needed and apply it to your own dataset or use cases.

## Dependencies
Ensure you have the following libraries installed in your Python environment:

- `numpy`
- `pandas`
- `scikit-learn`
- `nltk` (Natural Language Toolkit)
- `matplotlib` (for data visualization)

You can install these libraries using pip:
``` bash
pip install numpy pandas scikit-learn nltk matplotlib
```
