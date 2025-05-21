# Fake News Detection Using Support Vector Machine (SVM)

# Project Description:
This project aims to develop a machine learning model that can accurately detect fake news using the Support Vector Machine (SVM) algorithm. In today’s digital era, the rapid spread of misinformation and fake news through online platforms has become a significant concern. To combat this issue, the project leverages Natural Language Processing (NLP) techniques to preprocess and analyze textual data from news articles and social media posts.

The system is trained on a labeled dataset consisting of both fake and real news articles. Key NLP techniques such as tokenization, stopword removal, stemming/lemmatization, and vectorization (e.g., TF-IDF) are applied to convert raw text into numerical features suitable for classification.

SVM is chosen due to its effectiveness in handling high-dimensional data and its ability to find the optimal hyperplane that separates different classes. The model is trained and validated to distinguish between fake and real news with a focus on achieving high accuracy and generalizability.

# DataSets
Here i have used two different datasets Fake.csv and True.csv

Title: Fake News Articles
Description:
This file contains 23,481 fabricated or misleading news articles. Each entry includes:
Title: Headline used in the article    
Text: Main content of the article
Subject: Thematic label of the article (e.g., conspiracy, political bias)
Date: Assigned or published date

Title: True News Articles
Description
This file contains 21,417 real news articles sourced from reliable outlets. Each entry includes:
Title: Headline of the article
Text: Full body content of the news piece
Subject: Topic/category of the news (e.g., politics, world, tech)
Date: Publication date of the article

# Key Features:
Data preprocessing using NLP techniques

Text vectorization using TF-IDF or Count Vectorizer

Fake news classification using SVM

Evaluation using metrics such as accuracy, precision, recall, and F1-score

Optional GUI or web interface for user interaction

# Technologies Used:
Python

Scikit-learn

Pandas, NumPy

NLTK / spaCy

Matplotlib / Seaborn (for data visualization)

# Applications:
Enhancing social media monitoring tools

Assisting fact-checking platforms

Supporting media literacy initiatives



