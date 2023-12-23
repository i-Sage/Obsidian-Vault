22-12-2023 <=> 22:41
=> Type : Note
=> Tags : #Differentiation
=> Graphical Notes: [[Introduction to the derivative]]

---
## Introduction
Given a value - the price of gas, the pressure in a tank, or your distance from Boston - how can we describe changes in that value ? Differentiation is a valuable technique for answering questions like this.

### What is a Derivative ?
The derivative represents the rate at which a function changes with respect to its independent variable. It essentially measures how a function's output changes concerning the input. Geometrically, the derivative at a specific point on a curve gives the slope of the tangent line to the curve at that point.

##### Geometric interpretation
- Finding the tangent line to $y = f(x)$ at $P = (x_0, y_0)$

slope $m = f'(x_0)$
>[!note] The derivative
>$f'(x_0)$, the derivative of f at $x_0$ is the slope of the tangent line to $y = f(x)$ at the point $P$
>

$y_0 = f(x_0)$

$y = f(x)$

$$f'(x_0) = \lim_{{\delta x \to \infty}} \frac{f(x_0 + \delta x) - f(x_0)}{\delta x}$$
The above formula is called a difference quotient


#### Examples
1. $f(x) = \frac {1}{x}$
Plugin the function into the difference quotient
$$\frac{\Delta f}{\Delta x} =  \frac  { \frac{1}{x_0 + \Delta x} - \frac{1}{x_0} }{\Delta x}$$
Rewriting RHS of the above equation, yields:
$$\frac{1}{\Delta x} \cdot \left(  \frac{x_0 - (x_0 + \Delta x)}{(x_0 + \Delta x) \cdot x_0}  \right) = \frac{1}{\Delta x} \cdot \left(  \frac{- \Delta x}{(x_0 + \Delta x)\cdot x_0}  \right) = \frac{-1}{(x_0 + \Delta x) \cdot x_0}$$
Taking the limit of this new RHS yields:
$$\lim_{{\Delta x \to 0}} \frac{-1}{(x_0 + \Delta x) \cdot x_0} = \frac{1}{x_0^2}$$
Putting the above solution back, we get: $$f'(x_0) = \frac{-1}{x_0^2}$$

2. Find areas of triangles enclosed by axes and tangent to $y = \frac{1}{x}$
We know the equation of a line is $y - y_0 = m(x - x_0)$.
From the diagram, we can see that the x-intercept($y = 0$) gives the base of the triangle, and the y-intercept($x = 0$) gives the height of the triangle.

- Finding the x-intercept (y = 0)
	$0 - \frac{1}{x_0} = \frac{-1}{x_0^2}(x - x_0)$

	$$\frac{-1}{x_o} = \frac{-x}{x_0^2} + \frac{1}{x_0}$$
 Multiplying through by $x_0^2$:
 $$-x_0 = -x + x_0$$
 Solving for x:
 $$x = 2x_0$$
 - Short cut to the y-intercept (use symmetry) $2y_0$: 
 we can just use symmetry by trading $(x, y) \rightarrow (y, x)$

 - Symmetry Explanation:
	$$y = \frac{1}{x} <=> xy = 1 <=> x = \frac{1}{y}$$
 or we can just get the y-intercept by plugging $x = 0$ into the equation of the line.

 - Area of the triangle:
 $$Area = \frac{1}{2} \cdot (2y_0)(2x_0) = 2x_0y_0 = 2$$


### Example 2 $f(x) = x^n, \quad n = 1, 2, 3 \ldots$ find the derivative $\frac{d}{dx}x^n$ $$\frac{\Delta f}{\Delta x} = \frac{(x + \Delta x)^n - x^n}{\Delta x}$$
To solve this, we need the nth power of a sum, This says:
$$(x + \Delta x)^n = (x+ \Delta x) \quad \ldots \quad (x + \Delta x)$$
$$ = x^n + x^{n - 1} \Delta x + junk $$
This junk is known as $$O((\Delta x)^2)$$
We now have: $$\frac{\Delta f}{\Delta x} = \frac{1}{\Delta x} \cdot \left( (x + \Delta x)^n - x^n \right)$$
$$= \frac{1}{\Delta x} \cdot (x^n + nx^{n -1} + O((\Delta x)^2) - x^n)$$
The $x^n$ cancel out leaving:$$\frac{1}{\Delta x} (nx^{n - 1}\Delta x + O((\Delta x)^2) = nx^{n - 1} + O((\Delta x)^2)$$
This tends to $nx^{x - 1}$ as $\Delta x \rightarrow 0$, leaving:$$\frac{d}{dx}x^n = nx^{n - 1}$$
The above equation extends to polynomials.


### More Notations
- $y = f(x), \quad \Delta y = \Delta f$
- $f' = \frac{df}{dx} = \frac{dy}{dx} = \frac{d}{dx}f = \frac{d}{dx}y$

where $f'$ is Newton's and the rest are Leibniz.


___
### Summary
- The Tangent line is the limit of the Secant line.
- The General equation of a Tangent line is: $y - y_0 = m(x - x_0)$
- The derivative can also be evaluated using the difference quotient:$$f'(x_0) = \lim_{{\Delta x \to \infty}} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}$$ 
- The derivative of any polynomial function can be found using the power rule: $$\frac{d}{dx}x^n = nx^{n - 1}$$
- The derivative of a function tells us how the dependent variable $y$ changes with respect to the independent variable $x$
- Derivatives allow us to analyze functions, solve optimization problems, understand rates of change in various fields like physics and engineering.
- The derivative has many notations, these are: $$f' = \frac{df}{dx} = \frac{dy}{dx} = \frac{d}{dx}f = \frac{d}{dx}y$$

---
### References
[ChatGPT 3.5](https://chat.openai.com)
[MIT OPEN COURSEWARE](https://ocw.mit.edu/courses/18-01sc-single-variable-calculus-fall-2010/)

---