# Phishing-Emails-Detection-Using-Machine-Learning-And-Deep-Learning-Algorithms
 
## Introduction
This project aims to develop a machine learning solution to detect phishing attempts, a prevalent issue aimed at deceiving individuals and acquiring personal information or account details through deceptive emails or messages. As a part of my graduation project, I have conducted a comprehensive literature review on identity theft attacks and explored contemporary solutions to address this challenge.

## Dataset
The dataset used in this project contains:
- 12498 Normal emails
- 5142 Fake emails
- 19190 Harassment emails
- 5323 Suspicious emails

## Data Preprocessing
To prepare the dataset for model training, several preprocessing steps were undertaken:
- Added features such as CSS control, external resources, HTML form control, language errors, and blacklist keywords.
- Applied data preprocessing techniques, including data cleansing, word segmentation, and stemming.

## Text Representation Methods
Various text representation methods were employed to convert textual data into numerical form, including:
- Bag-of-words
- TF-IDF
- Word2Vec

## Machine Learning and Deep Learning Algorithms
Six machine learning algorithms were implemented to identify phishing emails:
- Logistic Regression
- Random Forest
- Long Short-Term Memory (LSTM)
- Support Vector Machine (SVM)
- Naive Bayes
- Convolutional Neural Networks (CNN)

## Model Evaluation
Model performance was evaluated using metrics such as F1-score, accuracy, precision, and recall.

## Development Environment
The project was developed using the following tools and platforms:
- Google Colab
- Jupyter Notebook
- Python programming language

## Conclusion
This project represents a significant effort in leveraging machine learning techniques to combat email phishing attempts. By utilizing various preprocessing steps, text representation methods, and machine learning algorithms, we aim to enhance the detection of deceptive emails and ultimately contribute to the prevention of identity theft and fraud.

For more details and code implementation, please refer to the respective Jupyter Notebook files in this repository.
