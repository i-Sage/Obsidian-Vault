24-12-2023 <=> 12:58
=> Type : Note
=> Tags : #Regression
=> Graphics: [[Linear Regression graphical]]

---
Regression is a statistical technique used to model the relationship between a dependent variable (or outcome) and one or one independent variables (or predictors), using very simple algebra to be specific. It aims to understand and quantify how the independent variables are related to the dependent variable.

When we talk about how "good" a regression model is, we are actually comparing it to another specific model.

##### Basic Example
Let's assume that you are a small restaurant owner or a very business minded server / waiter at a nice restaurant. In the U.S, "tips" are a very important part of a waiter's pay. Most of the time the dollar amount of the tip is related to the dollar amount of the total bill.

As a waiter or owner, you would like to develop a model that will allow you to make a prediction about what amount of tip to expect for any given bill amount. There fore one evening, you collect data for six meals.

| Meal $ | Tip amount(\$) |
| ------ | -------------- |
| 1      | 5.00           | 
| 2      | 17.00          |
| 3      | 11.00          |
| 4      | 8.00           |
| 5      | 14.00          |
| 6      | 5.00           |

Unfortunately when you begin to look at your data, you realize you only collected data for the tip amount and not the meal amount also. so this is the best data you have.

So how might you predict the tip amount for future meals using only this data ?

---
So the first thing we are going to do is visualize our data.
![[Pasted image 20231224132759.png]]
Using this data, how would you predict the tip for meal 7 would be, is it going to be like meal 6 with $5 or meal 2 with $17. How would you come up with the best guess for the next meal using only one variable ?

Well you would use its mean. The mean for all six tips is:
$$\bar{y} = \frac{5 + 17 + 11 + 8 + 14 + 5}{6} = \$10$$
With only one variable, the best estimate (prediction) for any given meal tip is $10 dollars. So for this model, that is our "best-fit line".
![[Pasted image 20231224133855.png]]
Looking on this chat, our tips do not fall on the $10 line, our tips are scattered around it, still, it's the mean, so this is our best estimate.

>[!note] Simple Linear Regression
>With only one variable, and no other information, the best prediction for the next measurement is the mean of the sample itself. The variability in the tip amounts can only be explained by the tips themselves

#### Goodness of Fit for the tips
Obviously, the data points do not fall on the $10 line, some are above and some fall below it, so that tells us how good this line fits these observed data points.

One way we can do that is to measure the distance from the data points to this best-fit line. We did to some degree when we were taking about standard deviation. Remember we are taking about the distance each data point is form the mean. And here we are finding the distance from each data point is form the best fit line which is actually just the mean line.

![[Screenshot_20231225-092944.jpg]]

The distance between the best-fit-line which in this case $10, to the observed values are called  **Residuals** or sometimes the **Error**

>[!note] 
>If you add up the residuals above the best-fit-line (7 + 1 + 4) = +12 and the sum of residuals below the best-fit-line (-5 -2 - 5) = -12. The Residuals always add up to Zero.

Like in standard deviation where we took the square of the deviations, we are also doing the same here, taking the square of the residuals

| $Meal$# | $Residual$ | $Residual^2$ |
| ------- | ---------- | ------------ |
| 1       | -5         | 25           |
| 2       | +7         | 49           |
| 3       | +1         | 1            |
| 4       | -2         | 4            |
| 5       | +4         | 16           |
| 6       | -5         | 25           |

Summing the $Residual^2$ gives the $\text{Sum of squared errors (SSE) = 120}$

>[!info]
>We square the residuals to make them positive and to emphasize larger deviations.

>[!attention] 
>The goal of simple linear regression is to create a linear model that minimizes the sum of squares of the residual / error (SSE).
><br>
> If our regression model is significant, it will "eat up" much of the raw SSE we had when we assumed (like this problem) that the independent variable did not even exist. The regression line will / should literally "fit" the data better. It will minimize the residuals.

When we introduce the independent variable of bill amount, We will create a different best-fit-line through our data, and what it will do, it will eat up this some of this sum of square error. So when we do regression, we will have sum of squares regression, and sum of square error.

>[!note]
> When conducting simple linear regression with TWO variables, we will determine how good that line "fits" the data by comparing it to THIS TYPE; Where we pretend the second variable does not exist.
> <br>
> If a two variable regression model looks like this example, what does the other variable do to help explain the dependent variable? 
> <br>
> **NOTHING**


>[!attention] 
>So when we say a linear regression model is "good", what we are saying is that it reduces the sum square errors by a large amount. Which is another way of saying we are comparing the other best fit line to this one we are looking at here.
><br>
>Simple linear regression is always a comparison to what we would have if we only had the dependent variable.

---
### Summary
- Simple linear regression is really a comparison of two models: 
	 - One is where the independent variable does not even exist
	 - And the other uses the best fit regression line
-  If there is only one variable, the best prediction for other values is the mean of the "dependent" variable
- The difference between the best-fit line and the observed value is called the residual (or error)
- The residuals are squared and then added together to generate sum of squares (LITERALLY) residuals / error, SSE.
- Simple linear regression is designed to find the best fitting line through the data that minimizes SSE.

---
### References

---