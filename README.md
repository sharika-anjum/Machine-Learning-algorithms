# Machine-Learning-algorithms
Self made algorithms to know how the algorithms work.

# User defined Algorithm to perform Naive Bayes' 

**Probability based concept**
Starting out with the prior probability (or believe) P(A) , when given a likelihood) P(B | A) and evidence P(B) we arrive at the posterior probability P(A | B) .
The Bayes' Theorem formula is, posterior = likelihood times prior, over evidence

**P(A | B)= (P(B | A)⋅P(A))/(P(B))**

**User defined Algorithm to perform Gaussian Naive Bayes' (for numerical data handling)**

**Probability based concept**
Gaussian Naive Bayes formula for this dataset cause data is normally distributed¶
Formula used : 
**f(x) = (1/(sd * sqrt(2 * pi))) * pow(e, ((-1/2) * pow(((x-m)/sd), 2))) ; where, sd = standard deviation ; m = mean ; f(x) = probability for the point x**

# User-defined-algorithm-to-perform-Linear-Regression using OLSR concept
**Statistics based**

**A straight line equation is y=m*x + b where m is the slope of the line and b is the y-intercept.**

**m = (Σ (xi - mean_x)(yi - mean_y))/ (Σ (xi - mean_x)^2)**

**b = mean_y - (m*mean_x)** ; 
Here xi and yi denotes the term of x and y at position i, where i ranges from 0 to the ending range of x and y.
For regression based problem, accuracy is found using R2_score function.

# User defined algorithm to perform Linear Regression using Gradient Descent concept.
**Calculus based.**

**Steps for Gradient Descent**

**1.First initialization of m and b value. (By assuming, with m=1 and b=0 for the very first time)
2.Assuming a Learning rate and then calculating the step-size for calculating the next m and b value.
3.Calculating the next value with m and b.
4.Repeating the entire steps for all the new values of m and b unill step size <= 0.001, i.e more or less 1000 times.**

*Formulae to be used :*
**Equation of a straight line : y=mx + b** ; here m = slope of the line and b is the intercept of the line
**Equation of the SS of a particular line : Σ(pyi-ayi)^2** ; i ranges from 1 to n where n is the total no of y points.

yi = the y value for the ith point.
pyi = predicted yi value of the best fit line.
ayi = actual yi value.
SS = Sum of the squared distance
from the equation of the SS line we will see that SS = f(m,b) i.e. SS is a function of m and b

**Calculation of b:**
differentiate f(m,b) with respect to b.
Then follow the 4 steps of Gradient descent as mentioned above for just b value.

**Calculation of m:**
differentiate f(m,b) with respect to m.
Then follow the 4 steps of Gradient descent as mentioned above for just m value.

**#User defined algorithm to perform Logostic Regression.
Geometric concept**
