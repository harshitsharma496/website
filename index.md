## Linear Regression
  It is type of supervised learning used when ouput of variable is <u> continuous </u> in nature
  
### It can be divides in two types
    * Simple Linear 
    * Multiple Linear 
   
  Simple Linear Regression - This is the most basic type of regression technique where we explain replationship between dependent and independent line using a staright                                line.

   RSS                     - The best-fit line is found by minimising the expression of RSS (Residual Sum of Squares) which is equal to the sum of squares of the                                      residual for each data point in the plot. Residuals for any data point is found by subtracting predicted value of dependent variable from                                actual value of dependent variable.
   
### The strength of the linear regression model can be assessed using 2 metrics:
   1. R2 or Coefficient of Determination - Explains what portion of the given data variation is explained by the developed model. It always takes a value between 0 & 1.
   2. Residual Standard Error (RSE)      - It is the measure of the difference between the expected and the actual output.
 

  
  Multiple Linear Regression - Multiple linear regression is a statistical technique to understand the relationship between one dependent variable and several                                          independent variables
  
  Adjusted R square          -  R-squared always increases if additional variables are added into the model, even if they are not related to the dependent variable. R-                                 squared thus is not a reliable metric for model accuracy. Adjusted R-squared, on the other hand, penalises R-squared for unnecessary                                   addition of variables. So, if the variable added does not increase the accuracy adequately, adjusted R-squared decreases although R-                                   squared might increase.
  
  
  ## Logistic Regression
     
     It is a type of supervised learining used when output is a categorical
     
   #### In it we use signmoid curve (S-shaped one)
   
   Likelihood -   To find out the best fit sigmoid curve, vary β0 and β1 until you get the combination of beta values
                  that maximises the likelihood.
                  
   Odds        -  To find out probability of things to happen against not happening it's log is called as log odds   
   
   Accuracy    -  It is a ratio of corrected predicted to total number
   
   Senstivity  - It is a ratio of corrected predicted yes to total number of yes
   
   Specificity  - It is a ratio of corrected predicted no to total number of no
   
   
   
