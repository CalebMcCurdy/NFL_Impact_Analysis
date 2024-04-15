# Predictive Analytics for NFL Game Outcomes

This project is a part of the ADS-599 Capstone course in the Applied Data Science Program at the University of San Diego. 

**-- Project Status: Completed**

## Installation
To use this project, first clone the repository onto your local machine using the following commands:

git init

git clone https://github.com/CalebMcCurdy/House-Sales-Regression.git

## Overview:

This project delves into the intricacies of team building and gameplay strategies within the National Football League (NFL). As the NFL landscape evolves, teams adopt diverse approaches to roster construction and game plans. Some emphasize a robust running game, while others prioritize passing. The central hypothesis driving this endeavor is that teams built around a strong passing game tend to enjoy greater success in the regular season. Our objective is to pinpoint the factors with the most significant impact on winning in the NFL.

Through meticulous analysis of NFL data and trends, this project aims to provide insights to NFL teams for enhancing personnel and system development to bolster their chances of success. Furthermore, it seeks to explore whether there exists an unfair competitive imbalance within the league that warrants reform.

Within this repository, you'll find code and documentation for a predictive modeling project centered on the NFL. Our goal is to scrutinize various in-game statistics and factors influencing game outcomes, ultimately crafting predictive models for game results and scoring.

## Team Members:

Caleb McCurdy  https://github.com/CalebMcCurdy

UE Wang  https://github.com/UE-Wang

## Data Source:

https://www.kaggle.com/datasets/cviaxmiwnptr/nfl-team-stats-20022019-espn/data

Our dataset gives a variety of stats from NFL games over the course of 22 seasons. The data is a 998-kilobytes .csv file consisting of 5929 rows and 53 columns. Contained within the dataset are breakdowns of offensive stats categories by play type such as passing or rushing attempt. Additionally, the data is broken down by the team on offense by using the home and away teams to organize these. There are no missing or null values for any of the columns so we do not need to perform imputation to address any of them. 

## Exploration

<img width="930" alt="Screenshot 2024-03-04 at 5 46 05 PM" src="https://github.com/UE-Wang/MSADS599-Capstone-Project/assets/108497911/d0cd9824-ed73-4288-8af7-c7c221cf1515">

![Unknown](https://github.com/CalebMcCurdy/NFL_Impact_Analysis/assets/108497911/1e8c68b3-d79c-4f45-85ab-4a126787c822)

![Unknown](https://github.com/CalebMcCurdy/NFL_Impact_Analysis/assets/108497911/9dfa4d82-808f-4a7f-818e-d0ad232128e6)

## Methodology

Data Exploration: Analyze historical NFL data to identify key factors influencing game outcomes.
Feature Engineering: Engineer new features and preprocess data to enhance model performance.
Modeling: Train and evaluate various machine learning models, including Logistic Regression, Random Forest, Gradient Boosting, Support Vector Machine (SVM), and Gaussian Naive Bayes, for both classification and regression tasks.
Evaluation: Assess model performance using metrics such as accuracy, precision, recall, F1-score, mean squared error (MSE), and mean absolute error (MAE).

## Technologies

Python (Jupyter Notebook)

## Results and Findings

Logistic Regression emerges as the top-performing model for predicting game outcomes.
Linear regression models effectively predict scoring based on passing yards per attempt, rushing yards per attempt, and sacks.
Schedule adjustments are recommended to address rest imbalances and improve competitive fairness.

![Unknown](https://github.com/CalebMcCurdy/NFL_Impact_Analysis/assets/108497911/d75344fb-abe2-4672-891b-eff4a722754f)

![Unknown](https://github.com/CalebMcCurdy/NFL_Impact_Analysis/assets/108497911/2395cef1-3e66-41cf-80b4-b65fe966a46f)

## Conclusion

In summary, this project provides valuable insights into the factors influencing NFL game outcomes and scoring. By leveraging predictive modeling techniques, teams can make informed decisions regarding roster construction, strategic planning, and scheduling to maximize their chances of success in the league. These findings contribute to a deeper understanding of the complexities within the NFL and offer opportunities for further exploration in this domain.

## Future Work

Refine models to address overfitting and improve generalization capability.
Explore ensemble methods and advanced feature selection algorithms to enhance model robustness.
Incorporate external data sources and first-half only data for more accurate predictions.

## References:

Gifford, M., & Bayrak, T. (2023). A predictive analytics model for forecasting outcomes in 		National Football League games using decision tree and logistic regression. Decision 		Analytics Journal, 8, 100296. DOI: https://doi.org/10.1016/j.dajour.2023.100296.

Joash Fernandes, C., Yakubov, R., Li, Y., Prasad, A. K., & Chan, T. C. Y. (2020). Predicting 		plays in the National Football League. Journal of Sports Analytics, 6(1), 35–43. 			https://doi.org/10.3233/JSA-190348.

NFL Team Stats 2002 - Feb. 2024 (ESPN). (n.d.). Www.kaggle.com. Retrieved April 8, 2024, 		from https://www.kaggle.com/datasets/cviaxmiwnptr/nfl-team-stats-20022019-espn/data.

Pantle, I. (2022). Analyzing the Predictive Power of NFL Statistics. Dartmouth Sports Analytics. 		Retrieved from: https://sites.dartmouth.edu/sportsanalytics/2022/02/01/analyzing-the-	
predictive-power-of-nfl-statistics/.

Pelechrinis, K., & Papalexakis, E. (2016, December 22). The Anatomy of American Football: 		Evidence from 7 Years of NFL Game Data. PLOS ONE. DOI: 
https://doi.org/10.1371/journal.pone.0168716.

Roumani, Y. F. (2023). Sports analytics in the NFL: classifying the winner of the Super Bowl. 		Annals of Operations Research, 325(1), 715–730. DOI: 
https://doi.org/10.1007/s10479-022-05063-x.

## License
This dataset is dedicated to the public domain under a CC0: Public Domain license.









## Project Intro/Objective

The purpose of this project is to develop a regression model that is able to predict house sales price dependent on an array of characteristics. After performing exploratory and correlation analysis, we use dimensional analysis to reduce the computational time while maintaining the accuracy. These results can be used to evaluate whether a house on the market is being undervalued, overvalued, or listed at a fair price.

### Partner(s)/Contributor(s)  
•	Caleb McCurdy, Gabi Rivera, Loza Mengitsu

•	https://www.sandiego.edu/engineering/graduate/ms-applied-data-science.php 

### Methods Used
•	Predictive Modeling 

•	Data Visualization

•	Programming 

•	Data Manipulation

### Technologies
•	Python

•	Jupyter Notebook

## Project Description
Our dataset for this project can be downloaded from Kaggle at https://www.kaggle.com/datasets/harlfoxem/housesalesprediction. The data is in a .csv format with a size of 2.5 MB. There are 21,613 entries with 21 total columns for each: 20 predictors and 1 target variable. There are 4 columns with missing data so we will need to perform imputation on these records before continuing.

There are many factors that help determine the price of a house on the market. Among them are location, number of bedrooms, and size in square feet. With a predictive regression model that utilizes only the most important factors, we are able to give an estimate for the price a home with certain characteristics should expect to sell for. While there are other factors that cannot be added into the model, it can be used as a baseline for appraisals. While a similar strategy can be implemented in the future, more recent data is recommended to accurately depict the changes in the housing market.







