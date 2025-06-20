# Fake News Detection Project

The project aims to develop a machine‑learning model capable of identifying and classifying any news article as fake or not. The distribution of fake news can potentially have highly adverse effects on people and culture. This project involves building and training a model to classify news as fake news or not using a diverse dataset of news articles. Four techniques are used to determine the model's results:

* Logistic Regression
* Decision Tree Classifier
* Gradient Boost Classifier
* Random Forest Classifier ([github.com][1])

## Project Overview

Fake news has become a significant issue in today's digital age, where information spreads rapidly through various online platforms. This project leverages machine learning algorithms to automatically determine the authenticity of news articles, providing a valuable tool to combat misinformation. ([github.com][1])

## Dataset

A labeled dataset containing news articles with tags “True” (genuine news) or “False” (fake/fabricated) is used. ([github.com][1])

## System Requirements

* **Hardware**: 4 GB RAM, i3 Processor, 500 MB free space
* **Software**: Python 3 (via Anaconda recommended)
* **Dependencies**:

  * pandas
  * numpy
  * matplotlib
  * scikit-learn
  * seaborn
  * re ([github.com][1])

## Usage

1. Clone the repository:
   `git clone https://github.com/kapilsinghnegi/Fake-News-Detection.git`
2. Navigate to the directory:
   `cd fake-news-detection`
3. Run a classifier script, e.g.:
   `python random_forest_classifier.py`
   The scripts will train the model, output evaluation metrics, and predict whether a given news article is true or false. ([github.com][1])

## Results

Evaluation metrics such as accuracy, precision, recall, and F1 score are documented within the project files. ([github.com][1])

## Model Deployment

After selecting a well-performing classifier, you can deploy it in a real-world application or integrate it into a larger system for automated fake news detection. ([github.com][1])
