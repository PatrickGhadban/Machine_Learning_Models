* Ran a Linear Regression Model against hthe Boston Housing Dataset and the Diabetes Dataset

# Boston Housing DataSet
* Used a heatmap to create a correlation matrix that measures the relationships between the variables.
    * Price is strong and positively correlated with RM (avg. number of rooms) and is strong and negatively correlated with  LSTAT (% lower status of population)
    * However, it is important to keep in mind to avoid features that have multi-collinearity because independent variables should be independent from each other.
* I made two models and compared the results. In the first model, I simply selected the two features we previously determined from analyzing the data. In the second model, I selected all of the thirteen features to see whether it has any effect on the prediction. Even though I did get a better result based on the RSME for the first model, the difference in RSME values was not very significant. 
* Ran a polynomial Regression model on the LSTAT vs Price data as it seemed to be polynomially related to the price than linearly. Found when a 2nd degree polynomial was passed to the model, the RMSE value with this model came down to 3.78482, which was a signiﬁcant decrease.
