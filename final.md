# Final Review
If you have trouble, flag and come back to bottom of page.

## Questions

### 1
#### 1.1
Q: Suppose you gather the following data (all at noon on sunny days):
	
Ambient temperature (in F):  60, 76, 80, 90, 95, 100
Power from solar panels  (% of max power):  100, 100, 99, 98, 97, 95 

Q: T/F: The correlation r, between these variables, is negative.
A: True
E: positive correlation = both variables moving in tandem | negative correlation is one variable moving the opposite direction

#### 1.2 
Q: The regression line is generally more accurate near the means of X and Y.
A: True
E: A regression line **always** goes through the means of X and Y, as it's designed to do so. The regression line is considered the "line of best fit", and so it's meant to go through and pass through the point of means.


#### 1.3
Q: Although regression is affected by outliers, correlation is not.
A: False
E: Correlation coefficient and the regression line are linked, so if the correlation is affected, regression line is as well.

#### 1.4
Q: If your P-value is less than 5%, then your results are always significant.
A: False
E: Depends entirely on the significance level. Let's say you had a P-value of 0.04, which is not significant for a = 0.01, but is for 0.05 and 0.10. Again, let's say you have a P-value of 0.009, which is significant at all levels of a.

#### 1.5 
Q: T/F: when we set the significance level, we set the the Type 2 error of a Test. 
A: False
E: Significance level relates to Type 1 error and the probability of it, not Type 2. a = probability of Type 1 error occurring


### 2
#### A
Q: Calculate the regression line to predict blood pressure.  Interpret the slope of this line in ONE sentence.  (2  pts for calculations, 1 pt for interpretation)
E: Initially, we're given r (correlation coefficient) = 0.7,  mean & stddev for both varibles. We're also given the age, but we'll use that for Question C.
We'll deem both variables (x1=24, s1=5.5), (x2=135, s2=9).

So, using the slope formula, we can get: 
m = r(s2/s1) ==> 0.7(9/5.5) => 1.1454 ≈ 1.15
intercept = x2 - b(x1) ==> 135 - 1.15(24) => 107.4 

with these two, it's essentially y = mx + b
m = 1.15 & b = 107.4 
y = 1.15x + 107.4

To interpret this, all we need to talk about is the slope, not the intercept. So:
On average, for every increase in cigarettes smoked per day, blood pressure tends to go up by 1.15mmHg.

Note: We say "for every increase" because it's a positive increment. 

#### B
Q: Predict the blood pressure of a man age 28 who smokes 30 cigarettes per day.
E: Using our previous regression line, we can think of it as:
y = 1.15(30) + 107.4 => 141.9

#### C
Q: Your grandma Ethel really gets after it.  She is 84 years old, she loves her wine and cigarettes.  In fact, she smokes and rolls 25 cigarettes per day. You calculate (based on the regression line from B) that her blood pressure is 136.15 mmHG. Is this a reasonable guess?
E: Let's keep in mind that this statistic was meant for **20-40 year old men**. So your grandma doesn't really fit into this demographic. 
A: No, because this regression line is meant for 20-40 year old men, and Ethel doesn't fit into this demographic.

#### D
Q: Calculate the R^2 value.
E: You just square your R value. `(R)^2 is equivalent to (0.7)^2, which equates to 0.49`. 
This value is your coefficient of determination, otherwise known as goodness of fit of a regression model.
It ranges between 0 and 1, and respectively conveys if it doesn't fit or if it perfectly does.
R^2, is a statistical measure that indicates how well a regression model fits the data. It represents the proportion of the variability in the dependent variable that can be explained by the independent variable(s) in the model. An R-squared value of 0.49 means that approximately 49% of the variance in the dependent variable is accounted for by the independent variable(s) in the model.









