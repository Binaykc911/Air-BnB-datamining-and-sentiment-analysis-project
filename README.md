# Air-BnB-datamining-and-sentiment-analysis-project
Analyzes Airbnb data using machine learning to predict rental prices and sentiment analysis on reviews to reveal key guest experience insights. Helps optimize pricing strategies and improve satisfaction through data-driven exploration and modeling.

# Airbnb Data Mining and Sentiment Analysis Project

## Project Overview
This project applies advanced data mining and machine learning techniques to analyze Airbnb datasets, focusing on predicting accommodation prices and understanding guest sentiment. The objective is to provide valuable insights that help hosts optimize pricing strategies and improve guest experiences.

## Features
- Data import, cleaning, and preparation for reliable modelling
- Exploratory Data Analysis (EDA) including geospatial and categorical insights
- Feature engineering and final dataset construction
- Price prediction using XGBoost regression model with tuned hyperparameters
- Sentiment analysis of guest reviews using VADER and aspect-based sentiment scoring
- Visualization of model results and sentiment distributions

## Methodology
- Imported Airbnb datasets and performed quality checks to clean and prepare data
- Explored features with histograms, scatter plots, and geospatial maps to understand data distributions and relationships
- Engineered new features like host listing count and review rate per month to improve predictions
- Built and tuned an XGBoost model to predict accommodation prices with an RMSE around 377.75
- Conducted thematic and aspect-based sentiment analysis on guest reviews to identify drivers of positive and negative experiences

## Challenges and Considerations
- Addressed missing and non-numeric data issues
- Managed the subjectivity of sentiment analysis with NLP tools
- Ensured privacy by excluding personally identifiable information
- Acknowledged limitations such as review sarcasm and data biases

## Usage
- The project code and notebooks can be used to replicate the analysis or adapt the models for other datasets.
- Insights from the project can help Airbnb hosts optimize pricing and improve guest satisfaction.

## References
1. Airbnb dataset: https://insideairbnb.com/get-the-data  
2. Chen, T. & Guestrin, C. (2016). XGBoost: A Scalable Tree Boosting System.  
3. Safari, A. (2025). Sentiment Analysis of Airbnb Reviews.  
4. Zhu, L., So, K.K., Hudson, S. (2020). Sentiment and guest satisfaction with peer-to-peer accommodations.  
5. Shahani, N.M., et al. (2021). Developing an XGBoost Regression Model for Predicting Influences in Renewable Energy.  
6. Baltazar, D. (2021). An Aspect Based Sentiment Analysis Approach to Airbnb Review Data.

## Requirements
Python 3.8+
Jupyter Notebook or IDE
Relevant Python packages: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, nltk, vaderSentiment
Tools Used
Python for data processing and modeling
XGBoost for regression modeling
VADER for sentiment analysis
Data visualization with Matplotlib and Seaborn
Jupyter Notebook for interactive development

*Project by Binayak K C*  
*November 2025*
