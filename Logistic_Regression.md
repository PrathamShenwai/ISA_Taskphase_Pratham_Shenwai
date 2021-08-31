## Logistic Regression

* Logistic regression is one of the most popular Machine Learning algorithms,  
    which comes under the Supervised Learning technique.  It is used for  
    predicting the categorical
    dependent variable using a given set of independent variables.
* Logistic regression predicts the output of a categorical dependent variable.  
  Therefore the outcome must be a categorical or discrete value.
    It can be either Yes or No,  
    0 or 1, true or False, etc. but instead of giving the exact value as 0 and 1,  
    _**it gives the probabilistic values which lie between 0 and 1**.
* Logistic Regression is much similar to the Linear Regression except that  
  how they are used. Linear Regression is used for solving Regression problems,   
   whereas Logistic regression is used for solving the **classification problems**.  
* In Logistic regression, instead of fitting a regression line,
  we fit an "**S**" shaped logistic function, which predicts  
  two maximum values (0 or 1).           
* The curve from the logistic function indicates the likelihood of something such  
  as whether the cells are cancerous or not, a mouse is obese or not based on its weight, etc.  
* Logistic Regression can be used to classify the observations using different  
types of data and can easily determine the most effective variables used  
  for the classification. The below image is showing the logistic function:  
  ![Logistic Regression](https://static.javatpoint.com/tutorial/machine-learning/images/logistic-regression-in-machine-learning.png)
  
### Sigmoid Function
  
* The sigmoid function is a mathematical function used to map the predicted values to probabilities.
* It maps any real value into another value within a range of 0 and 1.
* The value of the logistic regression must be between 0 and 1, which cannot go beyond  
this limit, so it forms a curve like the "S" form. The S-form curve is called  
the Sigmoid function or the logistic function.
* In logistic regression, we use the concept of the threshold value, which defines the  
probability of either 0 or 1. Such as values above the threshold value tends to 1,  
and a value below the threshold values tends to 0.

### Assumptions for Logistic Regression:
* The dependent variable must be categorical in nature.
* The independent variable should not have multi-collinearity.

### Logistic Regression Equation:
The Logistic regression equation can be obtained from the Linear Regression equation.  
The mathematical steps to get Logistic Regression equations are given below:
* We know the equation of the straight line can be written as:  
![](https://static.javatpoint.com/tutorial/machine-learning/images/logistic-regression-in-machine-learning2.png)
* In Logistic Regression y can be between 0 and 1 only, so for this let's   
divide the above equation by (1-y):  
![](https://static.javatpoint.com/tutorial/machine-learning/images/logistic-regression-in-machine-learning3.png)
* But we need range between -[infinity] to +[infinity], then take  
logarithm of the equation it will become:  
![](https://static.javatpoint.com/tutorial/machine-learning/images/logistic-regression-in-machine-learning4.png)

### Where can Logistic Regression be used?

* In Fraud detection
* Disease diagnosis
* Emergency Detection
* Classifying the emails as '**spam**' or '**no spam**'