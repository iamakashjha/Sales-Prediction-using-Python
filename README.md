# Sales-Prediction-using-Python
Objective: The project aims to predict sales based on advertising spending on different platforms, specifically TV advertising.

I loaded and inspected the advertising dataset for missing values and outliers. The data was clean and required no significant preprocessing.

I performed univariate and bivariate analyses to explore the relationships between advertising spend across various platforms and sales. Through scatter plots and a correlation heatmap, I observed a strong positive correlation between TV advertising and sales.

I built a simple linear regression model using the statsmodels library, where TV advertising served as the predictor variable and sales as the target variable. I trained the model on 70% of the data using the Ordinary Least Squares (OLS) method.

To evaluate the model's performance, I used metrics like R-squared, F-statistic, and conducted residual analysis. The model achieved an R-squared value of 0.816, explaining 81.6% of the variance in sales. The F-statistic and its significance confirmed that the model fit was statistically sound, while residual analysis validated the normality of error terms.

I used the model to make predictions on the remaining 30% of the data (test set). The Root Mean Squared Error (RMSE) was calculated to assess the accuracy of these predictions. I also computed the R-squared value on the test data to evaluate the model’s generalization ability.

I visualized the relationship between TV advertising and sales using scatter plots, overlayed with the regression line. The plots demonstrated how well the model fit both the training and test data.

Conclusion:

I successfully developed a simple linear regression model to predict sales based on TV advertising spend. The model exhibited strong predictive power and explained a significant portion of the variance in sales, highlighting the positive impact of TV advertising on sales.
