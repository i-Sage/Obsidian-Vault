22-12-2023 <=> 19:05
=> Type : Note
=> Tags : #math

---
The behavior of an electronic circuit can be described by a [[05 system of equations]]. However, that system is often large and nonlinear. It is often impractical to find the exact algebraic solution to these systems. Engineers often make use of **algebraic approximations** when it's safe to do so. 

For the next few sections of approximations, we'll consider this simple function $y(x)$ as an example to explore a few approximation techniques:
$$y(x) = \frac{1}{1+x}$$
This equation is not a linear relationship, but it (or a similar looking fraction) often comes out of many circuit networks. From this function, we can make three types of algebraic approximations:
- Large Asymptotic Approximation: $|x| \gg 1$
- Small Asymptotic Approximation: $|x| \ll 1$
- Intermediate Asymptotic Approximation: $|x| \approx 1$
---
### Large Asymptotic Approximation
For "large" $x$, we really mean $|x| \gg 1$ (read as "the absolute value of x is much greater that 1") in this case. That's because the denominator of $y(x)$ is $1 + x$, and: $$1 + x \approx x \quad \text{ for } x \gg 1$$
Putting a "hat" over our original function $y(x)$ so that we call our approximation $\hat y(x)$. Plugging our approximated denominator back into our formula to get an estimate for the fraction: $$\hat{y}_{1}(x) = \frac{1}{x}$$
This is only an approximation for the original function $y(x)$, but it's an increasingly good one as $x \rightarrow \infty$ 
#### Error in Large Asymptotic Approximation
How good is this approximation? We can consider the approximation error $e_{1}(x)$: 
$$e_{1}(x) = \hat{y}_{1}(x) - y(x)$$
$$= \left(  \frac{1}{x} \right) - \left(   \frac{1}{1 + x}  \right)$$
$$=\frac{ (1+x) }{x(1+x)} - \frac{x}{(1+x)x} $$
$$= \frac{(1+x)-x}{x(1+x)}$$
$$= \frac{1}{x(1+x)}$$
$$= \frac{1}{x + x^2}$$

With this, we can actually use or approximation technique again on the error function. Since we are assuming that $x \gg 1$, then $x^2 \gg x$. In regards to the denominator of $e_1(x)$, we can then say that $x + x^2 \approx x^2$, and the error is approximately: $$\hat{e_{1}}(x) = \frac{1}{x^2}$$
This means that if $x = 1000$ then our approximation error due to using $\hat{y}_1(x)$ instead of $y(x)$ is about one part in a million. Whether that's close enough for any particular situation is for you to determine, but in many practical cases, being off by only one part in a million is much better that any manufacturing tolerances or noise sources, so using the approximation may be a very reasonable choice.
#### Limit of Large Asymptotic Approximation
In fact, depending on the structure of our equations and for really huge values of $x$, it might be appropriate (thought usually is not!) to take the full limit of $x \rightarrow \infty$: $$ \lim_{{x \to \infty}} \hat{y}(x) = \lim_{{x \to \infty }} \frac{1}{x} = 0$$
Note that the limit of the original $y(x)$ is also the limit of the approximation $\hat{y}_1(x)$ However, if you're not very careful in taking approximations, it is very dangerous to remove this much information. Your approximations will quickly mislead you if you always assume that $\frac{1}{1 + x} \approx 0$ - be warned!
#### Approximations Gone Wrong
If you look closely, the idea above that $$x^2 + x \approx x^2 \quad \text{  for  } x \rightarrow \infty$$
may seem a bit strange. In fact, the absolute error in this approximation itself actually grows as $x \rightarrow \infty$. That's because we're speaking about the approximation colloquially in the context of the overall problem, rather than strictly in a mathematical sense. 

The generally accepted and more strict definition of a good asymptotic approximation involves a limit (in the calculus sense) and a fraction: $$ \hat{y}(x) \approx y(x) \quad \text{for } x \rightarrow \infty  \quad \text{if and only if} \quad \lim_{{x \to \infty}} \frac{\hat{y}(x)}{y(x)} = 1$$


### Small Asymptotic Approximation
For "small" $x$, by which we really mean $|x| \ll 1$, a new approximation is needed for our function $y(x) = \frac{1}{1 + x}$. 
At $x = 0$: $$y(x = 0) = \frac{1}{1 + 0} = 1$$
But what happens if $x$ is not exactly zero, but is simply small? Suppose $x = \frac{1}{100}$: $$y\left(x = \frac{1}{100} \right) = \frac{1}{1 + \frac{1}{100}} $$
$$y\left(x = \frac{1}{100} \right) = \frac{100}{100 + 1}$$
$$y \left(x = \frac{1}{100} \right) = \frac{100}{101}$$
$$y\left(x = \frac{1}{100}\right) = 0.9900990099 \ldots$$

Using calculus, the simplest way to get a linear approximation near $x = 0$ is to take the derivative of $y(x)$ there and use it to construct a tangent line: $$ y'(x) = \frac{dy}{dx} $$
$$y'(x) = \frac{d}{dx}\left(\frac{1}{1 + x}\right)$$

$$y'(x) = \frac{d}{dx}(1 + x)^{-1}$$
$$y'(x) = -(1 + x)^{-2}$$
$$y'(x) = - \frac{1}{(1+x)^2}$$
$$y'(0) = - \frac{1}{(1 + 0)^2}$$
$$y'(0) = -1 $$
Now that we have the point value $y(0) = 1$ and the derivative value $y'(0) = -1$ we can construct the tangent line:$$\hat{y}_2(x) = y(0) + y'(0) \cdot (x-0)$$
$$\hat{y}_2(x) = 1+(-1) \cdot (x - 0)$$
$$\hat{y}_2(x) = 1-x$$
At the end of the day, we now have the approximation that:
$$\frac{1}{1+x} \approx 1 - x \quad \text{for } |x| \ll 1$$
This is a very useful approximation and we might see it in other formats. For one example, consider the ratio of resistances:
$$z = \frac{R_1}{R_1 + R_2}$$
This fraction comes up in the analysis of every resistor divider. We can factor out $R_1$ from the denominator and find: $$z = \frac{R_1}{R_1\left(  1 + \frac{R_2}{R_1} \right)}$$
$$z = \frac{1}{1+ \frac{R_2}{R_1}}$$$$z = \frac{1}{1+ x}$$
If we simply define $x = \frac{R_2}{R_1}$, the ratio of resistances, then our function $y(x)$ and all the approximations developed above apply to the resistor divider problem.

Suppose, for a practical example, that $R_1$ represents the input impedance of one amplifier stage, and $R_2$ represents the output impedance of the previous stage. In that case, $z$ represents the voltage transfer ratio between stages, and we might want to make sure it was as close to 1 as reasonably possible.

For example, if we knew that $x = \frac{R_2}{R_1} = 0.01 = 1\%$ (i.e. that there was a 100X ration between the resistances), we could now quickly estimate the voltage transfer ration as approximately: $$\hat{z} = 1 - 0.01 = 0.99 = 99\%$$
This is just an easier and more intuitive calculation to reason about than using the full exact form: $$z = \frac{1}{1+ 0.01}$$
which, for most people, is harder to think about directly!

### Intermediate Approximation at a Point
After handling the "extremes" at $|x| \ll 1$ and $|x| \gg 1$, suppose we want to find a simplified approximation at some intermediate point that is neither very large nor very small.

One easy way to do that is by using the same tangent line approach used for the small asymptotic approximation, but instead of using $x= 0$ as our anchor point, use the $x$ value in the middle of the range we want to approximate.

For example, suppose again we are looking at a resistor divider but now we have the case where $R_1 \approx R_2$, so $x \approx \frac{R_2}{R_1} \approx 1$. Perhaps, due to imperfect manufacturing or biasing tolerances, the resistances are not exactly equal, but are close, and we want a simplified formula to describe the voltage transfer ratio in these cases.

The exact formula is still the same: $$y(x) = \frac{1}{1 + x}$$
But, for values of $x$ close to 1, we can not approximate this fraction with a simpler expression that doesn't have an $x$ in the denominator. Here's how we can construct the tangent line around point $x = 1$: $$\hat{y}_2(x) = y(1) + y'(1) \cdot (x-1)$$
$$\hat{y}_2(x) = \frac{1}{2} + \left( -\frac{1}{4}\right) \cdot (x - 1)$$
$$\hat{y}_2(x) = \frac{3}{4} - \frac{1}{4}x$$
### Other Approximation Techniques
The tangent line approximation minimizes the approximation error to 0 at one particular point, but does not necessary optimize behavior at other points.

If we had to approximate some nonlinear function $f(x)$ (possibly even experimentally derived rather than algebraic) over some bounded range of input values $[x_1, x_2]$, there are several ways we could imagine doing it:

1. Compute the tangent line at the midpoint $x_{mid} = \frac{x_1 + x_2}{2}$. This would minimize error in the *middle* of the range, but does nothing to guarantee good approximation over the rest of the range.
2. Linear interpolation between the two endpoints. If we have $y_1 = f(x_1) \quad and \quad y_2 = f(x_2)$ then we can just draw a line between these two points: $$\hat{y}(x) = y_1 + (x - x_1) \cdot \left( \frac{y_2 - y_1}{x_2 - x_1} \right)$$
	This would minimize error to zero at the two endpoints, but does nothing to guarantee good approximation in the middle of the range.
3. Some line that is anchored neither at the endpoints nor midpoints. For example, if we want to minimize approximation error over the entire range, we may have to construct a line different from either #1 or #2. This could be done numerically (for example, a linear least squares approach might work) or graphically. This approximation may be "better" in a practical way; for example, our approximation in #1 and #2 may be off by $20\%$ at some point along the curve, but our approximation in #3 might be off b only $5\%$ at its worst.

>[!ttodo] Plot the three different approximation for:
>$g(x) = (x-3)^3 \quad \text{for } 3 \leq x \leq 5$
---


>[!note] The midpoint tangent line, endpoint linear interpolation, and linear least squares approximations over this range are:
>$\hat{y_1}(x) = 3x - 11$
>$\hat{y_2}(x) = 4x - 12$
>$\hat{y_3}(x) = 3.606x - 12.414$
>

---
## Summary

- When the solution to a problem becomes too impractical and expensive to solve, Engineers often use numerical methods to approximate the answers to their problems within a contained error.



---
### References
- [ultimate electronics](https://ultimateelectronicsbook.com/)

---

22-12-2023 <-> 19:05