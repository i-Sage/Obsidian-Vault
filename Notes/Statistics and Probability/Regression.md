31-12-2023 <=> 11:31
=> Type : Note
=> Tags : #statistics #LinearRegression #Regression 

---
#### LEAST-SQUARES ESTIMATION OF THE PARAMETERS
The parameters $\beta_0$ and $\beta_1$ are unknown and must be estimated using sample data. Suppose that we have n pairs of data say (y1, x1), (y2, x2), ....., (yn, xn).

###### Estimation of $\beta_0$ and $\beta_1$
We estimate $\beta_0$ and $\beta_1$ so that the sum of the squares of the differences between the observations $y_i$  and the straight line is minimum. The least-squares criterion is: $$S(\beta_0, \beta_1) = \sum_{i = 1}^{n}(y_i - B_0 - B_ix_i)^2$$
<p align="center"> // snip //</p>

The solutions to the least-square normal equations are: $$\hat{\beta_0} = \bar{y} - \beta_1 \bar{x}$$
and 
$$\hat{\beta_1} = \frac{\sum_{i = 1}^ny_ix_i - \frac{\left(  \sum_{i = 1}^ny_i \right)    \left(  \sum_{i = 1}^n x_i \right)}{n}} {\sum_{i = 1}^n x_i^2 - \frac{\left( \sum_{i = 1}^nx_i \right)^2}{n}}$$
where $$\bar{y} = \frac{1}{n}\sum_{i = 1}^n y_i \quad and \quad \bar{x} = \frac{1}{n}\sum_{i = 1}^n x_i$$
are the averages of $y_i$ and $x_i$ respectively. Therefor $\hat{\beta_0}$ and $\hat{\beta_1}$ above are the least-square estimators of the intercept and slope, respectively. The fitted simple linear regression model is then $$\hat{y} = \hat{\beta_0} + \hat{\beta_1}x$$
We may write these quantities in a more compact notation as:
$$S_{xx} = \sum_{i=1}^n x_i^2 - \frac{\left( \sum_{i=1}^n x_i\right)^2}{n} = \sum_{i=1}^n(x_i - \bar{x})^2$$
and $$S_{xy} = \sum_{i=1}^{n}y_ix_i - \frac{ \left( \sum_{i = 1}^ny_i  \right) \left( \sum_{i = 1}^n x_i  \right)   }{n} = \sum_{i = 1}^n y_i (x_i - \bar{x})$$
Thus, a convenient way to write $\hat{\beta_1}$ is: $$\hat{\beta_1} = \frac{S_{xy}}{S_{xx}}$$
The difference between the observed value $y_i$ and the corresponding fitted value $\hat{y}_i$ is a *residual*. Mathematically the $ith$ residual is: $$e_i = y_i - \hat{y}_i = y_i - (\hat{\beta}_0 + \hat{\beta}_1x_i), \quad i = 1, 2, \dots, n$$
Residuals play an important role in investigating model adequacy and in detecting departures form the underlying assumptions.

#### Properties of the least-squares estimator and the fitted regression model.
The least-squares estimators $\hat{\beta_0}$ and $\hat{\beta_1}$ have several important properties. First, note from eqn



---
### References

---
31-12-2023 <-> 11:31