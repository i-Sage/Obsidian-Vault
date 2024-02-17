17-01-2024 <=> 17:31
=> Type : NOTE
=> Tags : #Calculus #Differential #Equations #NumericalMethods

---
### 1. Picard's Iterative Method
Consider the first order equation $\frac{dy}{dx} = f(x, y) \quad \text{ with } y(x_0) = y$
The picard's iterative method is a sequence of functions that converges to the solution. It is defined Recursively by:$$y_0(x) = y_0$$
$$y_1(x) = y_0 + \int_{x_0}^{x} f(x, y_0) dx$$
and $$y_n(t) = y_0 + \int_{x_0}^{x}f(x, y_{n - 1})dx$$
>[!note]
>Picard's method is of considerable theoretical value, but can be applied only to a limited class of equations in which the successive integrations can be performed easily. The method can be extended to simultaneous equation and equations of higher order. 

#### Example
Using Picard's process of successive approximations, obtain a solution up to the fifth approximation of the equation $dy/dx = y + x$, such that $y = 1$ when $x = 0$. Check your answer by finding the exact particular solution.
##### Solution
We have $y = 1 + \int_{x_0}^{x} (x + y)dx$
*First approximation*. Put $y = 1$ in $y + x$, giving$$y_1 = 1 + \int_{x_0}^{x}(1 + x)dx = 1 + x + \frac{x^2}{2}$$
*Second approximation*. Put $y = 1 + 

---



---
### References

---
17-01-2024 <-> 17:31