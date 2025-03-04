# Amsterdam-riots-prediction


This repository contains the code and resources for predicting the 2024 Amsterdam riots using machine learning. The project leverages historical data related to protests, riots, and sports events, along with sentiment analysis, to build predictive models.

## Project Overview

The 2024 Amsterdam riots, which occurred during a UEFA Europa League football match, were fueled by geopolitical tensions related to the Israel–Hamas war. This project aims to predict such riots using machine learning models trained on historical data. The models incorporate features such as demographic data, sentiment analysis, and protest patterns.

## Code Files

The repository contains the following code files:

1. **Data Exploration and Feature Engineering**  
   - This script performs exploratory data analysis (EDA) and prepares the dataset for modeling.  
   - Key tasks:  
     - Cleaning and preprocessing the data.  
     - Feature engineering.  
     - Visualizing trends and patterns in the data.  

2. **Sentiment Analysis Feature**  
   - This script performs sentiment analysis on news reports and social media data to create a sentiment feature.  
   - Key tasks:  
     - Scraping text data.  
     - Applying sentiment analysis using libraries like `TextBlob`.  
     - Integrating sentiment scores into the dataset.  

3. **Modeling**  
   - This script trains and evaluates machine learning models for predicting riots.  
   - Key tasks:  
     - Splitting the data into training and testing sets.  
     - Training models (e.g., Decision Tree, Random Forest, XGBoost).  
     - Evaluating model performance using metrics like accuracy, precision, recall, and F1-score.  
     - Generating SHAP values for model interpretability.  
