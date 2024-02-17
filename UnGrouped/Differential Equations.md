26-12-2023 <=> 11:10
=> Type : Note
=> Tags : #Calculus #Differentiation #Equations


---
>[!summary]
>- ORDER: The of an ODE refers to the highest derivative in the equation
>- DEGREE: The degree of an ODE refers to the highest power of the highest derivative present in the equation.

---
A *differential Equation* is a relationship between an independent variable, $x$, a dependent variable $y$, and one or more derivatives of $y$ with respect to $x$. eg. $$x^2\frac{dy}{dx} = y \sin x = 0$$
$$xy \frac{d^2y}{dx^2} + y\frac{dy}{dx} + e^{3x} = 0$$
Differential Equations represent dynamic relationships, ie. quantities that change, and are thus frequently occurring in scientific and engineering problems.

The *order* of a differential equation is given by the highest derivative involved in the equation.

$$x\frac{dy}{dx} - y^2 = 0 \quad \text{is an equation of the 1st order}$$
$$xy\frac{d^2y}{dx^2} - y^2 \sin x = 0 \quad \text{is an equation of the 2nd order}$$
$$\frac{d^3y}{dx^3} - y\frac{dy}{dx} + e^{4x} = 0 \quad \text{is an equation of the 3rd order}$$

---
#### Formation of differential equations
Differential equations may be formed in practice from a consideration of the physical problems to which they refer. Mathematically, they can occur when arbitrary constants are eliminated from a given function. Here are a few examples:

###### Example 1
Consider $y = A \sin x + B \cos x$, where $A$ and $B$ are two arbitrary constants. If we differentiate, we get:
$$\frac{dy}{dx} = A \cos x - B \sin x$$
and $$\frac{d^2y}{dx^2} = - A \sin x - B \cos x$$
Which is identical to the original equation, but with the sign changed.
ie $$\frac{d^2y}{dx^2} = -y \quad \quad \therefore  \frac{d^2y}{dx^2} + y = 0$$
>[!note]
>Some functions give 1st-order equations, some give 2nd-order equations.
>One thing to note about this behavior is:
>- A function with 1 arbitrary constant gives a 1st-order equation.
>- A function with 2 arbitrary constants gives a 2nd-order equation.
>Generalizing this: <br>
>**An nth-order differential equation is derived form a function having n arbitrary constants**

---
### Solution to differential equation
To solve a differential equation, we have to find the function for which the equation is true. This means that we have to manipulate the equation so as to eliminate all the derivatives and leave the relationship between y and x.

--- 
#### Method 1: By direct integration
If the equation can be arranged in the form $\frac{dy}{dx} = f(x)$, then the equation can be solved by simple integration.

###### Example 1 $$\frac{dy}{dx} = 3x^2 - 6x + 5$$
Then $$y = \int(3x^2 - 6x + 5)dx = x^3 - 3x^2 + 5x + c$$
ie $y = x^3 - 3x^2 + 5x + c$
As always, of course, the con26stant of integration must be included. Here it provides the one arbitrary constant which we always get when solving a first-order differential.

###### Example 2
Find the particular solution of the equation $e^x\frac{dy}{dx} = 4$ given that $y = 3$ when $x = 0$.

First rewrite the equation in the form $\frac{dy}{dx} = \frac{4}{e^x} = 4e^{-x}$.
Then $$y = \int4e^{-x}dx$$
Knowing that when $x = 0, y = 3$, we can evaluate $c$ in this case, so that the required particular solution is $$y = -4e^{-x} + 7$$

---
#### Method 2: By separating the Variables
If the given equation is of the form:$$\frac{dy}{dx} = f(x, y)$$
The variable y on the RHS prevents solving the by direct integration. We therefore have to devise some other method of solution.

Let us consider equations of the form $\frac{dy}{dx} = f(x)F(y)$ and of the form $\frac{dy}{dx} = \frac{f(x)}{F(y)}$,
ie. equations in which the RHS cad be expressed as products or quotients of functions of x or y

##### Example 1
Solve $$\frac{dy}{dx} = \frac{2x}{y + 1}$$
We can rewrite this as $$(y + 1)\frac{dy}{dx} = 2x$$
Now integrate both sides with respect to x:$$\int(y + 1)\frac{dy}{dx}dx = \int 2xdx$$
$$\int(y+1)dy = \int 2xdx$$
and this gives $$\frac{y^2}{2} + y = x^2 + c$$
>[!note] Solutions to initial value problems
>The solution to an initial value problem can be obtained by solving the equation:$$\int_{x_0}^x A(x) dx + \int_{y_0}^y B(y) dy = 0$$

>[!warning]
> Without initial values; the above equation becomes:
> $$\int A(x)dx + \int B(y) dy = C$$

---
#### Method 3: Homogeneous equations - by substituting y = vx
Here is an equation: $$\frac{dy}{dx} = \frac{x + 3y}{2x}$$This looks simple enough, but we find that we cannot express the RHS in the form of 'x-factors' and 'y-factors', so we cannot solve by the method of separating the variables.

In this case we make the substitution y = vx, where v is a function of x. So y = vx

Differentiation with respect to x (using the product rule):
$$\therefore \frac{dy}{dx} = v.1 + x\frac{dv}{dx} = v + x\frac{dv}{dx}$$
Also $$\frac{x + 3y}{2x} = \frac{x + 3vx}{2x} = \frac{1 + 3v}{2}$$
The equation now becomes $$v + x\frac{dv}{dx} = \frac{1 + 3v}{2}$$
$$\therefore x\frac{dv}{dx} = \frac{1 + 3v}{2} - v = \frac{1 + 3v -2v}{2} = \frac{1 + v}{2}$$
$$\therefore x\frac{dv}{dx} = \frac{1 + v}{2}$$
The given equation is now expressed in terms of v and x, and in this form we find that we can solve by separating the variables. Here goes:
$$\int \frac{2}{1 + v}dv = \int \frac{1}{x}dx$$
$$\therefore 2 \ln(1 + v) = \ln x + C = \ln x + \ln A$$
$$(1 + v)^2 = Ax$$
But $$y = vx \quad \therefore v = \left\{ \frac{y}{x} \right\} \quad \therefore \left( 1 + \frac{y}{x} \right)^2 = Ax$$
Which gives $(x + y)^2 = Ax^3$

##### Example 1: solve $$\frac{dy}{dx} = \frac{x^2 + y^2}{xy}$$
Here, all terms of the RHS are of degree 2, ie. the equation is homogeneous, $\therefore$ we substitute $y = vx$ (where v is a function of  x) $$\therefore \frac{dy}{dx} = v + x\frac{dv}{dx}$$
and $$\frac{x^2 + y^2}{xy} = \frac{x^2 + v^2x^2}{vx^2} = \frac{1 + v^2}{v}$$
The equation now becomes:$$v + x\frac{dv}{dx} = \frac{1 + v^2}{v}$$
$$\therefore x\frac{dv}{dx} = \frac{1 + v^2}{v} - v \quad = \quad \frac{1 + v^2 - v^2}{v} \quad = \quad \frac{1}{v}$$
$$\therefore x\frac{dv}{dx} = \frac{1}{v}$$
Separating the variables and integrating gives:$$\frac{v^2}{2} = \ln x + C$$
Now all that remains is to express $v$ back in terms of $x$ and $y$. The substitution we used was $$y = vx \quad \therefore v = \frac{y}{x}$$
$$\therefore \frac{1}{2} \left(\frac{y}{x} \right)^2 = \ln x + C$$
$$y^2 = 2x^2(\ln x + C)$$
---
#### Method 4: Linear equations - use of integrating factor
Consider the equation $\frac{dy}{dx} + 5y = e^{2x}$
This is clearly an equation of the first order, but different from those we have dealt with so far. In fact, none of our previous methods could be used to solve this one, so we have to find a further method of attack.

In this case, we start by multiplying both sides by $e^{5x}$. This gives $$e^{5x}\frac{dy}{dx} + y5e^{5x} = e^{2x} \cdot e^{5x} = e{^7x}$$
We now find that the LHS is, in fact, the derivative $y\cdot e^{5x}$
$$\therefore \frac{d}{dx} \left\{ y\cdot e^{5x}\right\} = e^{7x}$$
Now, of course, the rest is easy. Integrate both sides with respect to x:
$$\therefore y \cdot e^{5x} = \int e^{7x}dx = \frac{e^{7x}}{7} + C$$
$$\therefore y = \frac{e^2x}{7} + Ce^{-5x}$$
The equation we have just solved is an example of a set of equations of the form: $$\frac{dy}{dx} + Py = Q$$
Where $P$ and $Q$ are functions of x(or constants). This equation is called a *linear equation of the first order* and to solve any such equation, we multiply both sides by an *integrating factor* which is always:$$e^{\int Pdx}$$
This converts the LHS into the derivative of a product.

>[!note]
>In determining $\int Pdx$, we do not include a constant of integration. This omission is purely for convenience, for a constant of integration here would in practice give a constant factor on both sides of the equation, which would subsequently cancel. This is one of the rare occasions when we do not write down the constant of integration.
>#### So: To solve a differential equation of the form
>$$\frac{dy}{dx} + Py = Q$$
>*where P and Q are constants or functions of x, multiply both sides by the integrating factor*: $$e^{\int Pdx}$$
>y $\cdot$ IF = $\int Q.IFdx$ where IF = $e^{\int Pdx}$
##### Example 1
To solve $\frac{dy}{dx} - y = x$
If we compare this with $\frac{dy}{dx} + Py = Q$, we see that in this case
$$P = -1 \quad \text{} \quad Q = x$$
The integrating factor is always $$e^{\int Pdx}$$and here P = -1

$$\therefore \int Pdx = -x$$ and the integrating factor is: $$e^{-x}$$
$$\therefore e^{-x}\frac{dy}{dx} - ye^{-x} = xe^{-x}$$
$$\frac{d}{dx} \left\{ e^{-x}y\right\} =  xe^{-x} \quad \therefore \quad ye^{-x} = \int xe^{-x}dx$$
The RHS integral can now be determined using integration by parts or DI method:

| sign | $dx$ | $\int$    |
| ---- | ---- | --------- |
| +    | x    | $e^{-x}$  |
| -    | 1    | $-e^{-x}$ |
| +    | 0    | $e^{-x}$  |
This gives: $$ye^{-x} = -xe^{-x} - e^{-x} + c$$
Solving for y:$$y = Ce^{x} -x - 1$$

---
### Bernoulli's Equation
The differential equation:$$\frac{dy}{dx} + P(x)y = Q(x)y^n$$
is known as Bernoulli's equation and it is solved as follows:
- Divide both sides by $y^n$. This gives:$$y^{-n}\frac{dy}{dx}+ Py^{1 -n}= Q$$
- Now put $z = y^{1-n}$
So that differentiating gives: $$\frac{dz}{dx} = (1 - n)y^{-n}\frac{dy}{dx}$$
So we have:$$\frac{dy}{dx} + Py = Qy^n \quad \quad \dots \quad (1)$$
$$\therefore y^{-n}\frac{dy}{dx} + Py^{1-n} = Q \quad \quad \ldots \quad (2)$$
Put $z = y^{1-n}$ so that $\frac{dz}{dx} = (1-n)y^{-n}\frac{dy}{dx}$
If we now multiply (2) by (1-n) we shall convert this first term into $\frac{dz}{dx}$.
$$(1-n)y^{-1}\frac{dy}{dx}+(1-n)Py^{1-n} = (1 -n)Q$$
Remembering that $z = y^{1}$ and that $\frac{dz}{dx} = (1-n)y^{-n}\frac{dy}{dx}$, this last line can now be written $$\frac{dz}{dx} + P_1z = Q_1$$ with $P_1$ and $Q_1$ functions of x.
This we can solve by use of an integrating factor in the normal way.
Finally, having found z, we convert back to y using $$z = y^{1-n}$$
##### Example
Solve $\frac{dy}{dx} + \frac{1}{x}y = xy^2$
- Dividing through by $y^2$, giving $$y^{-2}\frac{dy}{dx} + \frac{1}{x}y^{-1} = x$$
- Now put $z = y^{1 - n}$, ie, in this case $z = y^{1 - 2} = y^{-1}$
$$z = y^{-1} \quad \therefore \frac{dz}{dx} = -y^{-2}\frac{dy}{dx}$$
- Multiply through by (-1), to make the first term $\frac{dz}{dx}$ so that:$$\frac{dz}{dx} - \frac{1}{x}z = -x$$
which is of the form $\frac{dz}{dx} + Pz = Q$ so that you can now solve the equation by the normal integrating factor method.

- Solving this gives: $$y = (Cx - x^2)^{-1}$$
---
#### Exact First-order Differential Equations
A differential equation $$M(x, y)dx + N(x, y)dy = 0 \quad \ldots \quad (i)$$
is exact if there exists a function g(x, y) such that$$dg(x, y) = M(x, y)dx + N(x, y)dy \quad \ldots \quad (ii)$$
**Test for exactness**: If $M(x, y)$ and $N(x, y)$ are continuous functions and have continuous first partial derivatives on some rectangle of the $xy$ plane, then eqn i above is exact if and only if: $$\frac{\partial M(x, y)}{\partial x} = \frac{\partial N(x, y)}{\partial x} \quad \ldots (iii)$$
#### Method of solution
To solve equation (i), assuming that it is exact, first solve the equations: $$\frac{\partial g(x, y)}{\partial x} = M(x, y) \quad \ldots (iv)$$
$$\frac{\partial g(x, y)}{\partial y} = N(x, y)$$
for g(x, y), the solution to eqn i is then given implicitly by:$$g(x, y) = c$$
where $c$ represents an arbitrary constant.

---
## Second-Order Differential Equations

### Second-Order Homogeneous Differential Equations
Many Practical problems in engineering give rise to second-order differential equations of the form: $$a\frac{d^2y}{dx^2} + b\frac{dy}{dx} + cy = f(x)$$
where $a$, and $b$ and $c$ are constant coefficients and $f(x)$ is a given function of $x$. The solution to differential equations of this form is seen to be
>[!note]
>$$y = Ae^{m_1x} + Be^{m_2x}$$
>Where $A$ and $B$ are two arbitrary constants and $m_1$ and $m_2$ are the roots of the quadratic equation $am^2 + bm + c = 0$.
>This quadratic equation is called the auxiliary equation and is obtained directly from the equation $$a\frac{d^2y}{dx^2} + b\frac{dy}{dx} + cy = 0$$
>by writing $m^2$ for $\frac{d^2y}{dx^2}$, $m$ for $\frac{dy}{dx}$, $1$ for $y$.

> [!summary]
>The solution to the differential equation we get, depends on the roots of the auxiliary equation:
> - *Roots real and different* $m = m_1$ and $m = m_2$ $$y = Ae^{m_1x} + Be^{m_2x}$$
> - *Real and equal roots* $m = m_1$ (twice) $$y = e^{m_1x}(A + Bx)$$
> - *Complex roots* $m = \alpha \pm i \beta$
$$y = e^{\alpha x}(A \cos \beta x + B \sin \beta x)$$	
In each case, we use the auxiliary equation to establish the values of $m$ and substitute in the appropriate form of the result.

#### A Special Case
There is a special case when b is 0:$$a \frac{d^2y}{dx^2} + b\frac{dy}{dx} + cy = 0$$
ie:$$a \frac{d^2y}{dx^2} + cy = 0 \quad \text{ie} \quad \frac{d^2y}{dx^2} + \frac{c}{a}y = 0$$
which can be written as:$$\frac{d^2y}{dx^2} \pm n^2y = 0$$
To cover the two cases when the coefficient of y is $+$ or $-$
>[!note]
>Solutions to differential equations of this type have general solutions as:
>- if $$\frac{d^2y}{dx^2} + n^2y \quad \quad m^2 + n^2 = 0 \quad \therefore m^2 = -n^2$$
> $$y = A \cos nx + B \sin nx$$
> - if $$\frac{d^2y}{dx^2} - n^2y \quad \quad m^2 - n^2 = 0 \quad \therefore m^2 = n^2 \quad \quad m = \pm n$$
> $$y = A \cosh nx + B \sinh nx$$
> 

---
### In-Homogeneous Differential Equations


---
### Linear Differential Equations: Theory of Solutions
An nth order linear differential equation has the form $$b_n(x)y^{(n)} + b_{n - 1}(x)y^{(n - 1)} + \ldots + b_2(x)y'' + b_1(x)y' + b_0(x)y = g(x)$$
where $g(x)$ and the coefficients $b_j(x)$ $j = 0, 1, 2, \ldots, n$ depend solely on the variable x. In other words, they do not depend on $y$ or any derivative of $y$. If $g(x) \equiv 0$ then the above equation is *homogeneous*; if not, is is *non-homogeneous*.



---
### References

---