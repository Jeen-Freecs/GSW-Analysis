# GSW-Analysis
Stephen Curry's influence on Golden State Warriors(GSW) Performance and Predicting the Golden State Warriors(GSW) WIN/LOSS for 2012-2021 period games.
**In the analysis notebook**, I have conducted an analytical research on Stephen Curry's influence on Golden State Warriors(GSW) Performance by researching the following questions:
1. How had the win rate of GSW changed throughout the 2003-2021 period, and what is difference between GSW(2015) and GSW(2019) in average points per game?
2. What is the relationship between the mean game-time of Steph Carry and win-rate of GSW for each season between 2009-2021?
3. How had the trend of average 3-point field goal(%) adjusted from 2014 to 2021 for Golden State Warriors and Cleveland, and what is difference between GSW(2015) and GSW(2019) in 3-point field goal(%)

In the modeling notebook, I tried to predict whether GSW will win or loss on NBA games betweem 2012 and 2021. We examined 3 models such as Gradient Boosting, Logistic Regression and K Nearest Neighbors on predictig the GSW WIN/LOSS as our target value. We have used GridSearchCV for hyperparameter tuning to see which set of parameters will give the most reliable results.Also Validation curves and Learning curves were plotted for each model, to show whether model overfits/underfits relating to hyperparameters and size of training set.Evaluation was done by ROC-AUC metric, as it is more reliable in terms of unbalanced data.

If this research project will be continued, we'd like to research linearity/non-linearity of data, and also collinearity, as it might be reason of model relatively good/poor performance.

Furthermore, I also wanted to analyze how each feature is contributed to a model performance.


