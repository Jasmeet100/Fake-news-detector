# Fake News Detector

A deep learning project for detecting fake news using Natural Language Processing (NLP) and TensorFlow/Keras. This project processes text data from news datasets, builds a text classification model with LSTM and Convolutional layers, and visualizes text patterns using WordClouds.

---

## Features
* **Text Preprocessing:** Tokenization and sequence padding using TensorFlow Keras.
* **Deep Learning Architecture:** Sequential model combining Embedding layers, 1D Convolutions (`Conv1D`), Max Pooling (`MaxPool1D`), and Long Short-Term Memory (`LSTM`) networks.
* **Exploratory Data Analysis (EDA):** Generates high-resolution WordClouds to visualize common terms in fake news articles.
* **Model Evaluation:** Splits data into training and testing sets, evaluating performance with accuracy scores and detailed classification reports.

---

## Prerequisites & Installation

Make sure you have Python installed along with the required libraries:

```bash
pip install pandas numpy matplotlib seaborn nltk wordcloud scikit-learn tensorflow
