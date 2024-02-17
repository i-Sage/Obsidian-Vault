14-01-2024 <=> 19:34
=> Type : Note
=> Tags : #Calculus #Differentiation #Differential #Equations 

---
# FORMULAS
>[!summary]
>1. GROWTH AND DECAY PROBLEMS $$\frac{dN}{dt}-KN = 0$$
>2. TEMPERATURE PROBLEMS $$\frac{dT}{dt} + kT = kT_m \quad T_m \text{: temperature of surrounding }$$
>3. FALLING BODY PROBLEMS $$F = m\frac{dv}{dt}$$
>$$mg - kv = m\frac{dv}{dt}$$
>$$\frac{dv}{dt} + \frac{k}{m}v = g$$
>If air resistance is negligible or nonexistent, then $k = 0$ and we have:$$\frac{dv}{dt} = g$$
>4. DILUTION PROBLEMS $$\frac{dQ}{dt} + \left( \frac{f}{V_0 + (e - f)t}Q \right) = be$$
>5. ELECTRICAL CIRCUITS $$\frac{dI}{dt} + \frac{R}{L}I = \frac{E}{L} \quad \quad \text{For RL}$$
>$$\frac{dq}{dt} + \frac{1}{RC}q = \frac{E}{R} \quad \quad \text{For RC}$$
>$$\text{The relationship between q and I is  } I = \frac{dq}{dt}$$
>6. ORTHOGONAL TRAJECTORIES $$\frac{dy}{dx} = - \frac{1}{f(x, y)}$$
>

---

## GROWTH AND DECAY PROBLEMS
Let $N(t)$ denote the amount of substance (or population) that is either growing or decaying. If we assume that $dN/dt$, the time rate of change of this amount of substance, is proportional to the amount of substance present, then $dN/dt = KN$, or$$\frac{dN}{dt} - KN = 0$$
where $K$ is the constant of proportionality.
We are assuming that $N(t)$ is a differentiable, hence continuous, function of time. For population problems, where $N(t)$ is actually discrete and integer-valued, this assumption is incorrect. Nonetheless, the above equation still provides a good approximation on the physical laws governing such system.

---
## TEMPERATURE PROBLEMS
Newton's law of cooling, which is equally applicable to heating, states that *the time rate of change of the temperature of a body is proportional to the temperature difference between the body and its surrounding medium.* Let $T$ denote the temperature of the body and let $T_m$ denote the temperature of the surrounding medium. The the time rate of change of the temperature of the body is $dT/dt$, and Newton's law of cooling can be formulated as$$\frac{dT}{dt} + kT = kT_m$$
where $k$ is a positive constant of proportionality. Once k is chosen positive, the minus sign is required in Newton's law to make $dT/dt$ negative in a cooling process, when $T$ is greater than $T_m$, and positive in heating process.

---
## FALLING BODY PROBLEMS
Consider a vertically falling body of mass $m$ that is being influenced only by gravity $g$ and air resistance that is proportional to the velocity of the body. Assume that both gravity and mass remain constant and, for convenience, choose the downward direction as the positive direction

**Newton's second law of motion**: The net force acting on a body is equal to the time rate of change of the momentum of the body; or, for constant mass, $$F = m\frac{dv}{dt} \quad \quad \quad \ldots \quad(i)$$
*where $F$ is the net force on the body and $v$ is the velocity of the body, both at $t$*.

For the problem at hand, there are two forces acting on the body:
- The force due to gravity given by the weight of the body, which equals $mg$, and
- The force due to air resistance given by $-kv$, where $k \ge 0$ is a constant of proportionality. The minus sign is required because this force opposes the velocity; that is, it acts in the upward, or negative direction.
The net force $F$ on the body is, therefore, $F = mg - kv$. Substituting this result into eqn (i), we obtain $$mg - kv = m \frac{dv}{dt}\quad \quad \quad \ldots \quad (ii)_{i}$$
or $$\frac{dv}{dt} + \frac{k}{m}v = g \quad \quad \quad \ldots \quad (ii)_{ii}$$
as the equation of motion for the body. If air resistance is negligible or nonexistent, then $k = 0$ and eqn (ii) simplifies to:$$\frac{dv}{dt} = g \quad \quad \quad \ldots \quad (iii)$$
When $k>0$, the limiting velocity $v_l$ is defined by$$v_l = \frac{mg}{k} \quad \quad \quad \ldots \quad (iv)$$
>[!caution]
>Equations $(ii)$, $(iii)$, and $(iv)$, are valid only if the given conditions are satisfied. These equations are not valid if, for example, air resistance is not proportional to velocity but to the velocity squared, or if the upward direction is taken to be the positive direction.

---

## DILUTION PROBLEMS
Consider a tank which initially holds $V_0$ gal of brine that contains $a$ Ib of salt. Another brine solution, containing $b$ Ib of salt per gallon, is poured into the tank at the rate of $e$ gal/min while, simultaneously, the well-stirred solution leaves the tank at the rate of $f$ gal/min. The problem is to find the amount of salt in the tank at any time $t$.

Let $Q$ denote the amount (in pounds) of salt in the tank at any time $t$. The time rate of change of $Q$, $dQ/dt$, equals the rate at which salt enters the tank minus the rate at which salt leaves the tank. Salt enters the tank at the rate of $be$ Ib/min. To determine the rate at which salt leaves the tank, we first calculate the volume of brine in the tank at any time $t$, which is the initial volume $V_0$ plus the volume of brine added $et$ minus the volume of brine removed $ft$. Thus the volume of brine at any time is $$V_0 + et - ft \quad \quad \quad \ldots \quad (i)$$
The concentration of salt in the tank at any time is $Q/(V_0 + et - ft)$, from which it follows that salt leaves the tank at the rate of $$f\left( \frac{Q}{V_0 + et - ft} \right) \text{ Ib/min}$$
Thus, $$\frac{dQ}{dt} = be - f \left( \frac{Q}{V_0 + et - ft} \right)$$
or $$\frac{dQ}{dt} + \frac{f}{V_0 + (e - f)t}Q = be $$

---

## ELECTRICAL CIRCUITS
The basic equation governing the amount of current $I$ (in amperes) in a simple $RL$ circuit consisting of a resistance $R$ (in ohms), an inductor $L$ (in heneries), and an electromotive force (abbreviated emf) $E$ (in volts) is:$$\frac{dI}{dt} + \frac{R}{L}I = \frac{E}{L} \quad \quad \quad \ldots \quad (i)$$
For an RC circuit consisting of a resistance, a capacitance $C$ (in farads), an emf, and no inductance the equation governing the amount of electrical charge $q$ (in coulombs) in the capacitor is: $$\frac{dq}{dt} + \frac{1}{RC}q = \frac{E}{R} \quad \quad \quad \ldots \quad (ii)$$
The relationship between $q$ and $I$ is $$I = \frac{dq}{dt} \quad \quad \quad \ldots \quad (iii)$$

---
## ORTHOGONAL TRAJECTORIES
Consider a one-parameter of family of curves in the $xy$-plane defined by $$F(x, y, c) = 0 \quad \quad \quad \ldots \quad (i)$$
where $c$ denotes the parameter. The problem is to find another one-parameter family of curves, called the *orthogonal trajectories* of the family $(i)$ and given analytically by: $$G(x, y, k) = 0\quad \quad \quad \ldots \quad (ii)$$
Such that every curve in this new family intersects at right angles every curve in the original family. We first implicitly differentiate $(i)$ with respect to $x$, then eliminate $c$ between this derived equation and $eqn (i)$ . This gives an equation connecting $x, y$ and $y'$, which we solve for $y'$ to obtain a differential equation of the form: $$\frac{d\dot{y}}{dx} = f(x, y)\quad \quad \quad \ldots \quad (iii)$$
The orthogonal trajectories of $eqn (i)$ are the solutions of $$\frac{dy}{dx} = -\frac{1}{f(x, y)}\quad \quad \quad \ldots \quad (iv)$$
For many families of curves, one cannot explicitly solve for $dy/dx$ and obtain a differential equation of the form $eqn (iii)$.

---
### References

---
14-01-2024 <-> 19:34