# Objective:
  To build prediction model for the stock market of six major technology companies namely Google, Amazon, Facebook, Apple, Tesla and Microsoft.


# Data Sources:					
  1.Yahoo finance library
	
  2.New York Times API (https://developer.nytimes.com/) 
	
  3.Reuters (https://www.reuters.com/) 
	
  4.Technewsworld (https://www.technewsworld.com/)

# Overview
 Built a machine learning model by performing sentiment analysis via Natural Language Processing (NLP) on the archived news headlines/article snippets and trained the data using Random Forest Classifier after combining it with the stock market data to predict a rise or drop in the stock prices of six major tech companies. Amazon web Services (S3 buckets) was used to store the data and then was loaded in Spark data frame after which NLP was performed and data was trained. Also, the accuracy of the model was compared with the Recurrent Neural Network (RNN) model which was trained using historical stock price data collected from Yahoo Finance. The insights were presented through an interactive website. 

Stock prediction analysis : https://stock-prediction-project.herokuapp.com/
