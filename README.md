# Spam Filter 
This project aims to build a spam filter using a Naive Bayes classifier to classify SMS messages as spam or ham (non-spam). The dataset used contains a collection of SMS messages labeled as either spam or ham.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Usage](#usage)
- [Results](#results)

## Introduction
The goal of this project is to create a machine learning model that can accurately classify SMS messages as spam or ham. The model is trained using a labeled dataset of SMS messages and employs natural language processing (NLP) techniques to preprocess the text data.

## Dataset
The dataset used for this project is provided in a CSV file named `spam.csv`. It contains the following columns:
- `label`: The label of the message, either "spam" or "ham".
- `text`: The text content of the SMS message.

## Usage
1. Clone the repository:
   ```
    git clone https://github.com/your-username/Spam_filter.git
    cd Spam_filter
   ```
2. Install dependencies:
   ```
    pip install -r requirements.txt
   ```
   
## Results
The model achieved an accuracy of 97% on the test set.
Below is the classification report:

| Label | Precision | Recall | F1-Score | Support |
|-------|------------|--------|----------|---------|
| 0     | 0.97       | 1.00   | 0.98     | 975     |
| 1     | 1.00       | 0.78   | 0.88     | 140     |
| **Accuracy**    |            |        | 0.97     | 1115   |
| **Macro Avg**   | 0.98       | 0.89   | 0.93     | 1115   |
| **Weighted Avg**| 0.97       | 0.97   | 0.97     | 1115   |

