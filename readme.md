Peter asked for three different methods to meet Boston house price forecasts.
The first method is a linear regression algorithm
We used the Boston house price data set obtained from the database for model training and forecasting.
The scatter plot shows how the model is used to predict some house prices.
Where, the abscissa of each point represents the median of the real price of the same type of house, and the ordinate represents the result predicted by the linear regression model according to the characteristics.
We need to give the model an optimization goal, so that the resulting parameters can make the predicted value as close to the true value as possible.
This real value is usually used to reflect the size of the model error.

The second method is the random forest algorithm
A random forest is a model composed of many decision trees. This model is not simply a prediction of the average tree, but rather
The training data points are randomly sampled during tree construction, and the random feature subsets are considered during node segmentation.
Random forests combine hundreds or thousands of decision trees, training each on slightly different training sets,
Consider a finite number of features and split the nodes in each tree. The final prediction of the random forest is made by averaging the predictions of each tree.

The third method is elastic network regression
The linear regression becomes elastic network after the combination of L1 norm and L2 norm of coefficient of independent variables is added to the loss function of linear regression.


This assignment was completed by combining the knowledge taught by teachers and using the Internet for reference. We also encountered many problems in the process of trying.
For example, some of the function names in Python3 have changed and need to be up to date.
During the visual execution, the program repeatedly reported errors, searched for solutions on the Internet, and tried several approaches, all of which failed.
Finally, before the report, I found a solution to the problem with the help of my classmates.
The wrong application of the code led to the constant error reporting of the program, and I still need to continue to learn and improve.     
Thanks to Peter's teaching

-M105120306  张婉如