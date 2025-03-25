3 Problem Statement
1.Retail Shelf Space Optimization Challenge
2.Data Analytics and Insights in the Global Toothpaste Market
3.NLP Sentiment Analysis and Topic Modeling for Amazon Customer Feedback

Sentiment Analysis of Amazon Oral Care Product Reviews

Overview

This project aims to analyze customer sentiment from Amazon reviews of oral care products using multiple machine learning and NLP models. The objective is to classify customer reviews into positive, negative, or neutral sentiments and visualize the results in a Power BI dashboard.

Hackathon Problem Statement

E-commerce platforms receive vast amounts of customer feedback daily. Understanding customer sentiment helps brands improve products, address concerns, and enhance user experience. The challenge is to develop an automated solution to process and analyze thousands of product reviews efficiently and generate meaningful insights for decision-making.

Dataset

Source: Amazon oral care product reviews dataset

Size: 1000+ reviews

Attributes:

Id: Unique identifier for each review

ProductId: Unique product identifier

UserId: Unique user identifier

ProfileName: Reviewer's name

HelpfulnessNumerator and HelpfulnessDenominator: Measures of review helpfulness

Score: User-provided rating (1-5 stars)

Time: Timestamp of the review

Summary: Short description of the review

Text: Full review text

Sentiment Analysis Models Used

VADER (Valence Aware Dictionary and sEntiment Reasoner) - A rule-based model for sentiment analysis.

TextBlob - A lexicon-based approach for polarity detection.

BERT (Bidirectional Encoder Representations from Transformers) - A deep learning-based NLP model for contextual sentiment analysis.

Other ML models (if applicable) - Additional models such as logistic regression, SVM, or LSTM-based sentiment classifiers.

Expected Results and Insights

Sentiment Distribution: Percentage of positive, negative, and neutral reviews.

Model Performance Comparison: Accuracy, precision, recall, and F1-score for each model.

Product Sentiment Trends: Time-based sentiment trends for different oral care products.

Common Keywords & Topics: Frequently occurring words and phrases in positive and negative reviews.

Helpfulness Score Analysis: Relationship between sentiment and review helpfulness ratings.

Power BI Visualization: Interactive dashboard to explore sentiment trends, word clouds, and review insights.

Implementation Steps

Data Preprocessing: Cleaning, tokenization, and feature extraction from review text.

Sentiment Classification: Applying multiple models to classify sentiment.

Result Aggregation: Consolidating outputs from different models for comparison.

Exporting Results: Saving analysis results into a CSV file for Power BI integration.

Visualization in Power BI: Creating graphs, charts, and dashboards for data-driven insights.

Technologies Used

Python: Data processing and sentiment analysis

NLTK, TextBlob, Transformers (Hugging Face): NLP libraries

Pandas, NumPy: Data handling and manipulation

Matplotlib, Seaborn: Data visualization in Python

Power BI: Interactive dashboard creation

How to Use

Run the Jupyter Notebook or Colab script to perform sentiment analysis.

Generate the all_model_results.csv file.

Load the CSV file into Power BI.

Explore insights using the Power BI dashboard.

Conclusion

This project provides a scalable approach to analyze customer sentiment using multiple NLP models. The insights help businesses understand user feedback, improve product quality, and enhance customer satisfaction. Future enhancements could include advanced deep learning models, real-time sentiment tracking, and multilingual sentiment analysis.
