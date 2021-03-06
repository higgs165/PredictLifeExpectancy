# Description
A Multivariable Regression model that predicts life expectancy given other variables. Used a Kaggle dataset that has data on many countries, regarding GDP, population, infant/adult mortality, life expectancy etc. It was an attempt to try out the machine learning knowledge that I have been teaching myself. Some variables seemed to have very high P-Values so I removed some from the model and compared the BIC and R-Squared values to the original full model and got a better BIC result with a slightly lower R-Squared value.

# BIC and R-Squared
<strong>For original full model:</strong>

BIC: 7204.271948131657   
<br>
R-Squared: 0.8375967031163584

<strong>For reduced model:</strong>

BIC: 7164.046187986783   
<br>
R-Squared: 0.8372414639834214

# Screenshots
<h3>P-Values</h3>
<img src="pvalues.PNG" alt="pvalues list" height="500">

<h3>Actual vs Predicted Life Expectancy</h3>
<img src="scatterplot.PNG" alt="Life Expectancy Graph" width="500">
 
<h3>Actual and Predicted Values</h3>
<img src="values.PNG" alt="Actual and Predicted Values" height="300">

