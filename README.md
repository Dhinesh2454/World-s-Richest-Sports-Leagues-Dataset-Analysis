# World-s-Richest-Sports-Leagues-Dataset-Analysis

This project involves analyzing a dataset containing information on over 700 of the world's most expensive sports leagues. The dataset provides key attributes such as league name, country, sports type, revenue, player salaries, top teams, and more, which can be used to derive insights into various aspects like market size, player salary trends, and league growth potential.

# Introduction
This repository provides an analysis of the "World Richest Sports Leagues" dataset. It includes several analyses to understand the dynamics of global sports leagues, including their market size, player salaries, growth potential, and more. The project leverages data visualization and machine learning to provide insights into the sports industry's financial landscape.

# Dataset
The dataset consists of 700+ entries representing the world's most expensive sports leagues. Each entry contains 11 columns:

League Name: The name of the league.
Country: The country where the league is based.
Sports: The type of sport (e.g., Football, Basketball, Baseball, etc.).
Revenue: The total revenue of the league.
Average Player Salary: The average salary of players in the league.
Top Team: The top-performing team in the league.
Total Teams: The number of teams in the league.
Founded Year: The year the league was founded.
Membership: The membership size or number of teams involved.
Growth Rate: A calculated attribute indicating the growth rate of the league over the years.
Market Size: An estimated figure showing the financial size of the league’s market.
The dataset can be found in the data/ folder in CSV format.

Analysis Overview
Market Size Comparison
This analysis compares the market sizes of various sports leagues across the world. It uses revenue and membership size as key indicators to visualize which leagues dominate the market and which are emerging.

Player Salary Trends
We explore the trends in player salaries across different leagues and sports types. This includes visualizing the average player salary by league, country, and sport, as well as examining salary growth over time.

League Growth Potential
By analyzing the growth rate and league founding years, we assess which leagues are expected to grow rapidly in the coming years. This can be cross-referenced with market size, revenue, and membership data to predict future trends.

# Weaver Shape Pattern
This analysis investigates the structural patterns within the data to find any cyclical or periodic trends in league revenues, player salaries, and growth. Using data visualization, we uncover any repeating patterns in league dynamics.

# Machine Learning
In this section, machine learning models are trained using the dataset to predict various outcomes, such as:

Revenue Prediction: Predicting future revenue based on past performance, number of teams, and other features.
Player Salary Prediction: Using historical data to predict average player salaries in different sports leagues.
League Growth Classification: Predicting whether a league is likely to experience high growth based on factors like founding year, total teams, and market size.
Models Used
Linear Regression: For predicting continuous variables such as revenue and player salaries.
Decision Trees: For classifying leagues into categories based on their growth potential.
Random Forests & XGBoost: For improving the accuracy of predictions and handling complex, nonlinear relationships in the dataset.
K-Means Clustering: For grouping similar leagues together based on attributes like market size, revenue, and growth rate.
Training & Evaluation
The dataset is split into training and testing sets. Models are evaluated using standard metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and accuracy (for classification tasks)


