# Real-Or-Fake-News-Detector

## Overview
The **Real-Or-Fake-News-Detector** is a Python-based machine learning project that aims to classify news articles as either *Real* or *Fake*. This project utilizes natural language processing (NLP) techniques and machine learning algorithms to analyze the text of news articles and predict their authenticity. 

## Features
- **Data Preprocessing:** Cleans and prepares the news data for modeling.
- **Feature Extraction:** Converts text into numerical features using techniques like TF-IDF.
- **Model Training:** Trains a machine learning model to distinguish between real and fake news.
- **Evaluation:** Provides performance metrics such as accuracy, precision, recall, and F1 score.
- **Prediction:** Allows users to input new news articles and receive predictions on whether they are real or fake.

## Dataset
This project uses the [Kaggle Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset). The dataset consists of two CSV files:
- `True.csv`: Contains real news articles.
- `Fake.csv`: Contains fake news articles.

### Prerequisites
- Python 3.x
- The following Python libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `nltk`
  - `matplotlib` (for optional visualization)
  
