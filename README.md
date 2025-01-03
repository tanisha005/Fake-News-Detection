# Fake-News-Detection

## Overview
This project aims to detect fake news in Hindi using machine learning models. It processes datasets of real and fake news articles, trains classifiers, and evaluates performance based on accuracy and other metrics.

## Features
- Preprocesses Hindi text using custom cleaning functions.
- Implements models: Logistic Regression, Naive Bayes, SVM, Decision Tree, KNN, and Random Forest.
- Provides metrics for performance evaluation.
- Visualizes data insights using word clouds and confusion matrices.

## Datasets
The dataset was collected and combined from two different sources:
1. https://raw.githubusercontent.com/Siddhartha15/Hindi-Fake-News-Detection/main/Data/fake_news.csv
   https://raw.githubusercontent.com/Siddhartha15/Hindi-Fake-News-Detection/main/Data/true_news.csv
2. http://www.iitp.ac.in/~ai-nlp-ml/resources/data/TALLIP-FakeNews-Dataset.zip

## Conclusion
1. Among the tested models, Random Forest achieved the highest accuracy of 85.7% , indicating its effectiveness in this task.
2. The classification report and confusion matrix show promising results, although there is scope for improvement in distinguishing between real and fake news, particularly for borderline cases.
3. Preprocessing techniques such as text cleaning and feature engineering (e.g., TfidfVectorizer, Stop word removal) played a crucial role in enhancing model performance.
4. Limitations include:
   The relatively small dataset size, which might impact model generalization.
   The challenge of dealing with regional dialects and variations in Hindi language usage.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/<tanisha005>/Fake-News-Detection.git
   cd Fake-News-Detection

