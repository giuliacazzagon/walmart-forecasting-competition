# Walmart competition: store sales forecasting

Link to the competition page: https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting

The project's aim is to predict store sales usng historical sales data for 45 Walmart stores located in different regions. Each store contains many departments, and sales must be forecasted for each department in each store.

I have used a combination of three different models:
- hybrid machine learning model composed of linear regression and XGBoost
- exponential smoothing for seasonal time series
- seasonal and trend decomposition using loess

The separate predictions from the three models are averaged to create the final submission for the competition. The final scores are 2832 (private score) and 2725 (public score), and the position on the leaderboard is ~60.
