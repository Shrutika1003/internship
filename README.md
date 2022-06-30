# Sentiment analysis of women's clothes reviews 

## General info

The project concerns sentiment analysis of clothes reviews to determine whether the product is recommended or not. Moreover it includes data analysis, data preparation, text mining and build model by using virtue different machine learning and deep learning algorithms. The project also includes EDA analysis and sentiment analysis by using Vader and TextBlob methods.

**I have created the web application in Flask based on this project and code for this app is available [here](https://github.com/aniass/sentiment-app).**

### Dataset
The dataset comes from Woman Clothing Review that can be find at [Kaggle](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews). 

## Motivation
The goal of the project is sentiment analysis of clothes reviews by using the various methods and determine possible recommendation. We have build model to predict if the review is positive or negative. We used different machine learning algorithms and a pre-trained Glove word embeddings with Bidirectional LSTM to get more accurate predictions. The Vader and TextBlob methods have been also used to analyze the sentiment of reviews and to compare their relevance.

## Project includes:
* EDA analysis - ***EDA_sentiment.ipynb***
* Sentiment analysis with ML algorithms - ***Sentiment_analysis.ipynb***
* Sentiment analysis with Glove embeddings and LSTM - ***Sentiment_glove.ipynb***
* Sentiment analysis with Vader and TextBlob - ***Sentiment_vader.ipynb***
* Sentiment analysis based on customer rating - ***Sentiment_two.ipynb***
* Python script to clean data - ***clean_data.py*** 
* Python script to use sentiment model with smote method ***sentiment_model.py***
* data - data used in the project.

#### The project is created with:
* Python 3.6
* libraries: pandas, numpy, scikit-learn, keras, tensorflow, nltk, wordcloud, Vader, TextBlob.

#### Running the project:
To run this project use Jupyter Notebook or Google Colab.
