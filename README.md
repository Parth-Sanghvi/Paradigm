# Paradigm
Complete Machine Learning workflow to provide a Asset Intelligence product for Paradigm, a Fin-Tech startup based out of California.

# Executive Summary

The project is geared towards developing a model that predicts the influence of news articles on cryptocurrency prices using sentiment analysis on a single article basis. The model is to serve as the back-end technology for Paradigm, a platform that automates Over-The-Counter (OTC) crypto trading for institutional crypto traders within a native chat application.

The solution consists of a min-max scaling of the absolute value of predicted daily price movements based onsentiment andnews articletext as predictors, producing a scoring for each article. The scoring of each article then reflects its likelihood of impact on price. The solution was developed using recurrent neural networks for conducting sentiment analysis, along with NLP and customized dictionaries, and random forest and gradient boosting for analyzing the time-series price data and predicting the price change for eacharticle. Thefinal model allows eacharticletobe rated on a scale of 0-10 in terms of predicted significance of each article to the movement of cryptocurrency asset price.  
