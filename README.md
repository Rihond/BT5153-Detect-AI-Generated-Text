# BT5153 AI-Generated Text Detection Project

## Overview

The proliferation of large language models (LLMs) has raised concerns about the authenticity and trustworthiness of text content. Our project aims to address the challenge of distinguishing AI-generated text from human-written content to combat issues such as fake news, impersonation, and academic dishonesty.

## Running the Code

To run the code, follow these steps:

Data Preprocessing: Execute Data_Preprocessing.ipynb.

Lingtuistics Feture and Logistic Regression: Run 5153_linguistics features statistics+logReg.ipynb

TF-IDF Logistic Regression: Run 5153_tfidf_logReg.ipynb               

KNN-SVM: Open and execute KNN-SVM.ipynb.

DistilBERT: Run DistilBERT.ipynb.

## File Descriptions

Data_Preprocessing.ipynb: This notebook contains the code for data preprocessing.

Lingtuistics Feture and Logistic Regression: This code preprocesses text data, extracts linguistic features, trains a logistic regression model, evaluates its performance, and visualizes the text feature distribution using PCA.

5153_tfidf_logReg.ipynb: This notebook implements TF-IDF and Logistic Regression.

KNN-SVM.ipynb: Contains code for implementing K-Nearest Neighbors (KNN) and Support Vector Machines (SVM).

DistilBERT.ipynb: Implements the DistilBERT model.
## Dataset Description

The dataset consists of introductory paragraphs from Wikipedia, both human-written and AI-generated using the GPT (Generative Pre-trained Transformer) variant known as 'Curie'. It includes attributes such as title, text content, length measurements, and labels indicating human-written or AI-generated.

## Preprocessing

The dataset undergoes preprocessing to separate human-written and AI-generated text, balance the dataset, and prepare it for model training. Features such as lexical diversity, sentence complexity, and readability scores are calculated and added to the dataset.

## Statistical Analysis

A comprehensive statistical analysis is conducted to uncover differences between human-authored and AI-generated texts. Analysis includes lexical diversity, readability scores, average sentence length, and frequency distribution of parts of speech.

## Traditional Machine Learning Models

Several traditional machine learning models are trained and evaluated, including logistic regression using TF-IDF and linguistic feature analysis. Logistic regression achieves the highest accuracy, precision, and recall among the evaluated models.

## Neural-Based Methods

Linguistic features-based classifiers using SVM and KNN are implemented, showing slightly lower performance compared to logistic regression. DistilBERT, a neural network model, demonstrates strong performance with high accuracy, precision, recall, and F1 score, indicating its effectiveness in distinguishing between human-written and AI-generated texts.

## Conclusion

Logistic regression with TF-IDF implementation achieves the highest accuracy, while DistilBERT offers a robust alternative with deeper linguistic analysis. Future work will focus on refining model structures, expanding training datasets, and real-time detection of AI-generated content.

