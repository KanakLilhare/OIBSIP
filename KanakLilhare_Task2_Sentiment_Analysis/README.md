# Sentiment Analysis of Google Play Store User Reviews

## Overview
This project focuses on Sentiment Analysis using Natural Language Processing (NLP) and Machine Learning techniques. The objective is to classify user reviews from the Google Play Store into Positive, Negative, and Neutral sentiments.

## Dataset
Google Play Store User Reviews Dataset

Features used:
- App
- Translated_Review
- Sentiment
- Sentiment_Polarity
- Sentiment_Subjectivity

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- WordCloud

## Project Workflow

### 1. Data Loading
- Loaded Google Play Store user review dataset.

### 2. Data Cleaning
- Removed missing values.
- Processed textual review data.

### 3. Exploratory Data Analysis
- Sentiment distribution analysis.
- Review frequency analysis.

### 4. Text Preprocessing
- Lowercasing text.
- Removing special characters.
- Removing stopwords.
- Text normalization.

### 5. Feature Engineering
- TF-IDF Vectorization.

### 6. Machine Learning Models
#### Logistic Regression
Accuracy: **91.29%**

#### Naive Bayes
Accuracy: **73.99%**

### 7. Visualizations
- Sentiment Distribution
- Positive Review Word Cloud
- Negative Review Word Cloud
- Sentiment Polarity Distribution
- Top Reviewed Apps
- Confusion Matrix

## Results

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 91.29% |
| Naive Bayes | 73.99% |

Logistic Regression achieved the highest accuracy and performed best for sentiment classification.

## Key Insights
- Positive reviews dominate the dataset.
- Logistic Regression significantly outperformed Naive Bayes.
- Sentiment analysis provides valuable insights into customer opinions and feedback.
- Frequently occurring words reveal major strengths and weaknesses perceived by users.

## Recommendations
- Monitor negative reviews regularly.
- Use sentiment analysis for customer feedback management.
- Improve application features based on user concerns.
- Track sentiment trends over time for better decision-making.

## Conclusion
This project successfully implemented sentiment analysis using NLP and Machine Learning techniques. Logistic Regression achieved an accuracy of 91.29%, demonstrating strong performance in classifying user reviews into Positive, Negative, and Neutral sentiments.

## Author
Kanak Lilhare