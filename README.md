# Amazon Fine Food Reviews - Sentiment Analysis

## Overview
This project analyzes 500K+ Amazon food reviews to build a sentiment classification model that predicts ratings (1-5 stars) from text data. The goal is to automatically tag reviews as positive/negative and identify key sentiment drivers.

## Key Features
- **Data**: 500,000+ reviews with scores, summaries, and text (2002-2012)
- **Preprocessing**: HTML stripping, contractions handling, lemmatization, TF-IDF/CountVectorizer
- **Models**: Random Forest (69.1% accuracy) with hyperparameter tuning
- **Visualizations**: Word Clouds, confusion matrices, feature importance
- **Business Impact**: Identifies product improvement opportunities through sentiment trends

## Results
- Achieved **69.1% accuracy** with Random Forest (n_estimators=21)
- Key findings: Model performs best at extreme ratings (1/5 stars), struggles with neutral (3-star) reviews
- Top predictive features: "delicious", "awful", "taste", "disappointed"


