# Fake News Detector

A deep learning project for detecting fake news using Natural Language Processing (NLP) and TensorFlow/Keras. This project processes text data from live online datasets, builds a text classification model with LSTM and Convolutional layers, and visualizes text patterns using WordClouds.

---

## Dataset

This model automatically pulls training data directly from online CSV sources using raw GitHub links:
* **Fake News:** [Fake.csv](https://raw.githubusercontent.com/laxmimerit/fake-real-news-dataset/refs/heads/main/data/Fake.csv)
* **True News:** [True.csv](https://raw.githubusercontent.com/laxmimerit/fake-real-news-dataset/refs/heads/main/data/True.csv)

No manual downloading or local `data/` folder setup is required—the code handles fetching the data streams directly.

---

## Features
* **Direct Data Streaming:** Fetches training datasets dynamically via URL links.
* **Text Preprocessing:** Tokenization and sequence padding using TensorFlow Keras.
* **Deep Learning Architecture:** Sequential model combining Embedding layers, 1D Convolutions (`Conv1D`), Max Pooling (`MaxPool1D`), and Long Short-Term Memory (`LSTM`) networks.
* **Exploratory Data Analysis (EDA):** Generates high-resolution WordClouds to visualize common terms in fake news articles.
* **Model Evaluation:** Splits data into training and testing sets, evaluating performance with accuracy scores and detailed classification reports.

---

## Prerequisites & Installation

Make sure you have Python installed along with the required libraries:

```bash
pip install -r requirements.txt
