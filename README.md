# Rubix-Cube

Problem Statement 10: Revolutionizing Wealth Management: Insights and Predictions for Mutual Funds**


*Description:* The problem domain concerns wealth management for the common middle-class people, focusing on Mutual Funds. Now why this topic there are very limited techniques for wealth management like FDs, Stocks Trading, Crypto, Estate Planning, Corporate Bonds etc. However, all of them require time, focus, significant capital, involve risk factors, and offer limited interest rates. Mutual funds are investment vehicles that pool money from multiple investors to invest in a diversified portfolio of securities such as stocks, bonds, money market instruments, where they are managed by an asset management company (AMC).

The expected solution for this problem statement includes: We have live web scraped data of Mutual Funds India, our goal is to present descriptive analysis to understand this data and their patterns, then make predictions on the given data to forecast the future performance of specific mutual funds, develop a dashboard to display past data and projections (frontend development not required). Finally, create an AI-based recommendation system for selected inputs: AMC Name, Category, Amount Invested, Tenure.


Solution-

Our project is a Mutual Fund Recommendation System implemented in Python using various data analysis and machine learning techniques. Here's a brief summary of what we have done:

1. Data Analysis and Visualization:

We loaded mutual fund data from a CSV file given by the Hackhive Team and performed exploratory data analysis.
Visualized the mean returns for different categories, subcategories, AMC names, and ratings using bar plots.
Implemented interactive widgets for dynamically plotting graphs based on user-selected columns and subcategories.

2. Data Preprocessing:

Applied label encoding to categorical columns like 'category', 'sub_category', 'scheme_name', 'amc_name', and 'fund_manager'.
Filled missing values with the mean.
Normalized numerical columns like 'risk_level', 'returns_1yr', 'returns_3yr', and 'returns_5yr'.

3. Machine Learning Modeling:

Built Random Forest Regression models to predict mutual fund returns for different time periods (1yr, 3yr, 5yr).
Evaluated model performance using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared.
Identified the best-performing model based on the lowest MSE and MAE and the highest R-squared value.

4. Mutual Fund Recommendation System:

Developed a recommendation system using cosine similarity to suggest similar mutual funds based on user input such as category, risk level, and returns.
Implemented interactive widgets for users to input their preferences and receive recommendations for the best mutual funds.
