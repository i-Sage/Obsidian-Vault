25-12-2023 <=> 12:56
=> Type : Note
=> Tags : #statistics 
=> Graphical: [[Linear Regression graphical]]

---
## Continuing with the example in the previous note:
Let's assume that you are a small restaurant owner or a very business minded server / waiter at a nice restaurant. In the U.S. "Tips" are a very important part of a waiter's pay. Most of the time the dollar amount of tip is related to the dollar amount of the total bill.

As the waiter or owner, you would like to develop a model that will allow you make a prediction about what amount of tip to expect. Therefore one evening, you collect data for six meals.

Now we are working with two variables that are a matched pair.
![[Pasted image 20231225144408.png]]
You want to know to what degree the tip amount can be predicted by the bill. So the tip is the Dependent variable; bill is the independent variable.

### Least Squares Criterion
$$min \text{ }\Sigma (y_i - \hat{y_i})^2$$
$y_i$ = observed values of dependent variable (tip amount)
$\hat{y_i}$ = estimated(predicted) value of the dependent variable (predicted tip amount)

>[!note] 
>Plain English. The goal is to minimize the sum of the squared differences between the observed value for the dependent variable ($y_i$) and the estimated / predicted value of the dependent variable ($\hat{y_i}$) that is provided by the regression line. Sum of the squared residuals.
><br>
>Not only that, but the sum of the squared residuals should be much smaller than when we just used the dependent variable alone; $\beta_1 = 0$, $\hat{y} = 10$ for all values of $x$. That sum of squared residuals was 120.


#### STEP1: SCATTER PLOT

![[Pasted image 20231225151214.png]]

#### STEP2: LOOK FOR A VISUAL LINE
Does the data seem to fall along a line ?
In this case, YES! Proceed.
If not ..if it's a BLOB with no linear pattern, then stop.
![[Pasted image 20231225151702.png]]

#### STEP3: CORRELATION (OPTIONAL)
What is the correlation coefficient, $\tau$ ?.
In this case, $\tau = 0.866$.

Is the relationship strong ?, in this case, YES!

#### STEP4: DESCRIPTIVE STATISTICS / CENTROID
![[Pasted image 20231225152352.png]]

#### STEP 5: CALCULATIONS
$$\hat{y_1} = b_o + b_1x_i$$
- Slope$$b_1 = \frac{\Sigma(x_i - \bar{x})(y_i - \bar{y})}{\Sigma(x_i - \bar{x}^2)}$$
where:
$\bar{x}$ = mean of the x (independent) variable 
$\bar{y}$ = mean of the y (dependent) variable
$x_i$ = value of the independent variable for a point
$y_i$ = value of the dependent variable for a point

- Intercept $$b_0 = \bar{y} - b_1\bar{x}$$
#### Numerator $\Sigma(x_i - \bar{x})(y_i - \bar{y})$
1. For each data point.
2. Take the x-value and subtract the mean x.
3. Take the y-value and subtract the mean y.
4. Multiply step 2 and step 3
5. Add up all the products.

#### Denominator $\Sigma (x_i - \bar{x})^2$
1. For each data point.
2. Take the x-value and subtract the mean x
3. Square step 2
4. Add up all the products


| Meal | Total Bill (\$) | Tip amount(\$) | Bill deviation  | Tip Deviations  | Deviation Products               | Bill Deviations Squared |
| ---- | --------------- | -------------- |:--------------- | --------------- | -------------------------------- | ----------------------- |
|      | x               | y              | $x_i - \bar{x}$ | $y_i - \bar{y}$ | $(x_i - \bar{x})(y_i - \bar{y})$ | $(x_i - \bar{x})^2$     |
| 1    | 34              | 5              |-40             |    -5             |    200                              |    1600                     |
| 2    | 108             | 17             | 34              |    7             |        238                          |     1156                    |
| 3    | 64              | 11             |-10             |     1            |         -10                         |        100                 |
| 4    | 88              | 8              | 14              |     -2            |         -28                         |       196                  |
| 5    | 99              | 14             | 25              |      4           |           100                       |        625                 |
| 6    | 51              | 5              |-23             |       5          |            115                      |          529               |
|      | $\bar{x} = 74$  | $\bar{y} = 10$ |                 |                 |      $\Sigma = 615$                            |      $\Sigma = 4206$                   |


#### Calculations: (SLOPE)
$$b_1 = \frac{\Sigma(x_i - \bar{x})(y_i - \bar{y})}{\Sigma (x_i - \bar{x})^2} = \frac{615}{4206} = 0.1462$$
##### Calculations: (Y-INTERCEPT)
$$b_0 = \bar{y} - b_1\bar{x} = 10 - 0.1462(74) = -0.8188$$
#### Your Regression line
$$\hat{y_i} =0.1462x -0.8188$$
![[Pasted image 20231225155440.png]]

#### Fit and Coefficient of Determination
It is important to note that a regression model is unique to the data it models, and adding and removing data points will most certainly change the regression model. The model is also only valid for the range of data points under analysis.

So once a regression line is calculated, how much better is it than using only the mean of the dependent variable alone. To answer this question, we have to calculate the sum of squares errors, however, this time we will do so using the regression line. We will also be able to quantify the fit of the regression model using a simple ration called the coefficient of determination.

Continuing with our waiter /business owner example, previously we discovered with only the mean of the dependent variable was $10, and using this as our regression line, we found the errors to be the difference between the mean line and that data point, we then summed these errors up and squared them, giving us an SSE = 120.

>[!note]
>With only the dependent variable, the only sum of squares is due to error. Therefore it is also the total, and MAXIMUM sum of squares for the data under analysis.

so SSE = SST = 120

>[!note]
>With both the Independent variable and the Dependent variable, the total sum of squares remains the same. But (ideally) the error sum of squares will be reduced significantly. The difference between SST and SSE is due to regression, SSR.


| mean | Observed total bill ($) | Observed tip amount ($) | $\hat{y}_i$ (predicted tip amount) | Error: (observed - predicted) ($y - \hat{y}_i$) | Squared Error |
| ---- | ---- | ---- | ---- | ---- | ---- |
|  | x | y |  |  |  |
| 1 | 34 | 5 | 4.1505 | 0.8495 | 0.7217 |
| 2 | 108 | 17 | 14.9693 | 2.0307 | 4.1237 |
| 3 | 64 | 11 | 8.5365 | 2.4635 | 6.0688 |
| 4 | 88 | 8 | 12.0453 | -4.0453 | 16.3645 |
| 5 | 91 | 14 | 13.6535 | 0.3465 | 0.1201 |
| 6 | 51 | 5 | 6.6359 | -1.6359 | 2.6762 |
|  |  |  |  |  |  |
|  | $\bar{x} = 74$ | $\bar{y} = 10$ |  |  | SSE = 30.075 |

#### Sum of Squared Errors Comparison
D.V (Tip amount) ONLY
SSE = 120

D.V and I.V (tip amount as function of meal amount)
SSE = 30.075

So, when we conducted the regression, the SSE decreased from 120 to 30.075. That is, 30.075 of the sum of squares was explained or allocated to ERROR.

Where did the other 89.925 go?

The 89.925 is the sum of squares due to REGRESSION.

SST = SSR + SSE
120 = 86.925 + 30.0725

#### Coefficient of Determination
How well does the estimated regression equation fit our data ?

This is where regression begins to look a lot like ANOVA; the total sum of squares is partitioned or allocated to SSE and SSR.

---
### References

---