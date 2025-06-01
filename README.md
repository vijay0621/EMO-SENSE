# Sentiment Analysis System

The **Sentiment Analysis System** is a machine learning-based application that analyzes text data to determine whether a tweet expresses **positive, negative, or no emotion** toward a brand or product.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Description
The **Sentiment Analysis System** processes text data from tweets and classifies them into different sentiment categories. It utilizes **Natural Language Processing (NLP)** techniques such as **TF-IDF vectorization** and machine learning models (**Logistic Regression, Random Forest**) to analyze emotions directed at brands or products.

## Features
- 📝 **Preprocesses text** by removing punctuation, stopwords, and converting to lowercase
- 📊 **Extracts features** using **TF-IDF vectorization** with n-grams
- 🤖 **Implements Logistic Regression and Random Forest models** for sentiment classification
- ✅ **Evaluates models** using cross-validation, accuracy score, and confusion matrix
- ☁ **Generates word clouds** for each sentiment category
- ⚡ **Allows real-time sentiment prediction** for user-input tweets

## Installation
To run the **Sentiment Analysis System** locally, follow these steps:

### **1. Clone the repository:**
```sh
git clone https://github.com/your-username/sentiment-analysis.git
```

### **2. Navigate to the project directory:**
```sh
cd sentiment-analysis
```

### **3. Install dependencies:**
```sh
pip install -r requirements.txt
```

### **4. Run the script:**
```sh
python sentiment_analysis.py
```

## Usage
Once the application is running:

1. 📥 **The system will load and preprocess the dataset.**
2. 🏗 **It will train Logistic Regression and Random Forest models to classify sentiments.**
3. 📊 **A confusion matrix and word clouds will be displayed for sentiment analysis visualization.**
4. 💬 **The user can enter a tweet, and the system will predict whether the sentiment is**:
   - **Positive** 😊
   - **Negative** 😠
   - **No Emotion** 😐
