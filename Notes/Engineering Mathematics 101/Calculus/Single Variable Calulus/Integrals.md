02-01-2024 <=> 18:09
=> Type : Reference
=> Tags : #Calculus #Integrals 

---
### Methods for solving Integrals
1. Variable Substitution: This is a five step process
- Declare a variable $u$ and set it equal to an algebraic expression that appears in the integral, and then substitute $u$ for the expression in the integral.
- Differentiate $u$ to find $\frac{du}{dx}$, and then isolate all the x variables on one side of the $=$ sign.
- Make another substitution to change $dx$ and all other occurrences of $x$ in the integral to an expression that includes $du$
- Integrate by using $u$ as your new variable of integration.
- Express this answer in terms of $x$
##### Example: integrate $\sin 2xdx$
- Let $u = 2x$ 
- substitute: $$\int \sin 2x dx = \int \sin u dx$$
- differentiate the function $u = 2x$ and isolate the $x$ terms on one side of the equal sign: $$\frac{du}{dx} = 2 \quad \therefore du = 2dx \quad \therefore \frac{1}{2}du = dx$$
- Substitute $\frac{1}{2}du$ for $dx$ in the integral: $$\int \sin u \left(\frac{1}{2} du \right) = \frac{1}{2} \int \sin u\ du$$
- At this point, you have an expression that you know how to evaluate:$$-\frac{1}{2} \cos u + c$$
- The last step is to substitute $2x$ back in for $u$:$$-\frac{1}{2} \cos 2x + c$$
2. By Parts:
- Decompose the entire integral including $dx$ into two factors.
- Let the factor without $dx$ equal $u$ and the factor with $dx$ equal $dv$
- Differentiate $u$ to find $du$, integrate $dv$ to find $v$
- Use the formula $$\int udv = uv - \int v du$$
- Evaluate the right side of this equation to solve the integral.
When to integrate by Parts:
- The logarithmic function $\ln x$
- The first four inverse trig functions: $(\arcsin x, \arccos x, \arctan x \text{ and } arccot x)$

#### Example: $\int x \ln x dx$
- Decompose the integral into $\ln x$ and $xdx$
- Let $u = \ln x$ and $dv = xdx$
- Differentiate $\ln x$ to find $du$ and integrate $xdx$ to find $v$
$$\frac{du}{dx} = \frac{1}{x} \quad \quad \quad \int xdx = \int xdx$$
$$du = \frac{1}{x}dx \quad \quad \quad v = \frac{1}{2}x^2$$
- Using these values for $u, du, v \text{ and } dv$, plug into the formula and solve: $$\int x \ln x dx = \ln x \left( \frac{1}{2}x^2 \right) - \int \frac{1}{2}x^2 \cdot \frac{1}{x}dx$$
- Simplifying with algebra gives:$$\frac{1}{2}x^2 \ln x - \frac{1}{2} \int x dx$$
- Evaluating the integral on the right:$$\frac{1}{2}x^2\ln x - \frac{1}{2}\cdot\frac{1}{2}x^2 + c$$
$$\frac{1}{2}x^2\ln x - \frac{1}{4}x^2 + c$$
3. By Partial Fractions


---
### References

---
02-01-2024 <-> 18:09