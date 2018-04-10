# Predictions-with-Machine-Learning-in-Python
This post includes how I make predictions for a review count of PokemonGo on certain day in the future. 
From 1000+ HTML files downloaded from real-time websites, I scraped 11 variables over a ten-day period every 10 min. 
Working with the web-scraped data, I generated correlations between each variables. 
I chose pandas scatter_matrix, seaborn heat map to visually visualize the relationship between data. 
Correlation Coefficients with numpy is checked in the process to directly show the highly correlated variables. 
Based on these statistical preparation, I transformed time series to supervised learning, 
before I made the forecasts with regression in machine learning. 
