---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
SIGNALS AND SYSTEMS ^Mt3iORSe

SIGNALS ^XUg0OY1d

SYSTEMS ^4XLU6e3e

Anything that carries information can be called a signal. ^BBBvqQAe

A signal can be defined as a single-valued function of one or more
independent variables which contain some information. A signal may also
be defined as any physical quantity that varies with time, space or
any other independent variable. A signal may be represented in time 
domain or frequency domain. ^DCawoYhH

Human speech is a familiar example of a signal. Electric current and
voltage are also examples of signals. A signal can be a function of one
or more independent variables. A signal may be a function of time,
temperature, position, pressure, distance, e.t.c.

if a signal depends on only one independent variable, it is called a 
ONE-DIMENSIONAL SIGNAL, and if a signal depends on two independent
variables, it is called a TWO-DIMENSIONAL SIGNAL. And if the signal 
depends on more independent variables, it is a MULTI-DIMENSIONAL
SIGNAL. ^nDp9dE86

REPRESENTATIONS OF DISCRETE-TIME SIGNALS ^2GPgj5Nu

INTRODUCTION ^AS7iAguG

In General signals may be CONTINUOUS-TIME SIGNALS or DISCRETE-TIME SIGNALS.
Continuous-time signals are defined for all instants of time, whereas  discrete-time
signals are defined only at discrete instants of time. Continuous time signals are 
represented by x(t) and discrete-time signals are represented by x[n] where t and n are
independent variables in time domain. Continuous-time signals are represented by a 
function or a graph.

    There are four ways of representing discrete-time signals. They are:
    1.  Graphical Representation                      2. Functional Representation
    3. Tabular representation                        4. Sequence Representation.

 ^M3e1lYQJ

GRAPHICAL REPRESENTATION ^J8azZA9D

consider a signal x[n] with values
x[-2] = -3, x[-1] = 2, x[0] = 0, x[1] = 3, x[2] = 1 and x[3] = 2 ^s4cSsZiP

The discrete-time signal can be represented graphically as: ^HALzwb2B

-3 ^2LHNxZxV

-2 ^zX0OO6XJ

-1 ^miY9pMz0

0 ^RDMLnVUL

1 ^B0nzOHzg

2 ^LZo5HEy6

3 ^6ckbJvxn

TABULAR REPRESENTATION ^s3Gb97ud

In this, the sampling instant n and the magnitude of the signal at the sampling
instant are represented in tabular form. The signal given in the graphical 
representation can be represented in tabular form as: ^wkqVoL8J

n   -2   -1   0   1   2  3 ^HNrzgz4O

x[n] ^lIRN2XpA

-3   2   0   3   1   2 ^4PyJDg2o

FUNCTIONAL REPRESENTATION ^O9ovJZgI

In this, the amplitude of the signal is written against the value of n.
The signal in the graphical and tabular form can be represented in 
functional form as: ^ctn0A12D

-3   for n = -2
2    for n = -1
0    for n = 0
3    for n = 1
1     for n = 2
2    for n = 3 ^7VyQHDWb

x[n] =  ^LYhk8aC2

Another example is: ^EspxTUrJ

2+4n   for n >= 0
0       for n < 0 ^5Y93IgUw

x[n] =  ^gpbBNqs7

SEQUENCE REPRESENTATION ^drQd2fRL

A finite duration sequence of the signal can be represented as: ^tXuc5zHx

x[n] = {-3, 2, 0, 3, 1, 2} ^4W0vlvyH

Another example is ^ILVq7f5h

x[n] = {..., 2, 3, 0, 1, -2,...} ^rTSufl0D

The arrow mark denotes the n = 0 term. When no arrow is indicated
the first term corresponds to n = 0 ^CrPsvSpW

SUM AND PRODUCT OF DISCRETE-TIME SEQUENCES ^iKE4Pbso

The sum of two discrete-time sequences is obtained by adding the corresponding
elements of the sequence.

        {Cn} = {An} + {Bn}     Cn = An + Bn ^3W58LqmA

The product of two discrete-time sequences is obtained by multiplying the 
corresponding elements of the sequence.

        {Cn} = {An} * {Bn}     Cn = AnBn ^XOXsBDPj

The multiplication of a sequence by a constant K is obtained by multiplying each
element of the sequence by that constant.
        
        {Cn} = K{An}      Cn = KAn ^uIUbUbgt

ELEMENTARY SIGNALS ^8wr318yy

There are several elementary signals which play vital role in the study of signals
and systems. These elementary signals serve as basic building blocks for the construction
of more complex signals. Infact, these elementary signals may be used to model a large
number of physical signals which occur in nature. These elementary signals are also called
STANDARD SIGNALS.
    The standard signals are:

1. Unit step function                2. Unit ramp function
3. Unit parabolic function           4. Unit impulse function
5 Sinusoidal function                6. Real exponential function
7. Complex exponential function, e.t.c ^hbcT5xX9

THE UNIT STEP FUNCTION ^u6eWS3zS

The unit step function exists only for positive time and is zero for negative time.
It is equivalent to applying a signal whose amplitude suddenly changes and remains
constant forever after application.

If a step function has unity magnitude, then it is called a unit step function.
The usefulness of the unit-step function lies in the fact that if we want a signal
to start at t = 0, so that it may have a value of zero for t < 0, we only need to
multiply the given signal with the unit step function u(t). A unit step function is 
useful as a test signal because the response of the system for a unit step reveals
a great deal about how quickly the system responds to a sudden change in the input
signal.

The continuous-time unit step function u(t) is defined as: ^iH84Z19X

u(t) =  ^gvapIfMt

1   for t >= 0


0  for t < 0 ^XzXaeFdf

The shifted unit step function u(t - a) is defined as: ^jP7wnNQI

u(t - a) =  ^FpBWxSh3

1   for t >= a


0   for t < a ^d0wncx0V

It is zero if the argument (t - a) < 0 and equals to 1 if the argument (t - a) >= 0.
The graphical representation of u(t) and u(t - a) are shown below: ^4JZBI8uw

1 ^iV8VaLRr

1 ^CIsbPdVo

t ^J2wvphY7

t ^m22jDC3K

u(t) ^JJZthLdp

u(t - a) ^4QvPOnHG

unit step function ^y6V77l5d

Delayed unit step function ^qcp7lsD2

The discrete-time unit step sequence u[n] is defined as: ^P2hQUn6d

u[n] =  ^SPB1Pjs4

1   for n >= 0

0  for n < 0 ^uPZgvehY

The shifted version for the discrete-time unit step function u[n - k] is defined as:  ^T7SWZYOh

u[n - k] =  ^qJd8bJXX

1   for n >= k

0  for n < k ^aiAI1mUm

n ^Dd03hIlw

1 ^3Fj6HO2F

u[n] ^fVF8gAg7

0 ^RPydHwim

1 ^E2z3I17l

2 ^OhLKPYbL

3 ^tLJMNvsW

-3 ^QNQdov2X

-2 ^fDWGeMbb

-1 ^3k7NY22x

u[n - k] ^4VpA6ABI

n ^jdSZpUS5

0 ^2lXewbsC

1 ^32CVoy43

k ^XEze4K9R

k+1 ^xYZL0sep

k+2 ^6W8fKXpI

k+3 ^ocInMthw

Discrete-time unit step function ^t1Wzy83t

Discrete-time shifted unit step function ^FOVrWccv

THE UNIT RAMP FUNCTION ^dN1IPN4s

The continuous-time unit ramp function r(t) is a function which starts at t = 0 and
increases linearly with time and is defined as: ^lehXIxT9

r(t) =  ^7ApIGltu

t   for t >= 0

0   for t < 0 ^F0nUyzq1

OR

The unit ramp function has unit slop. It is a signal whose amplitude varies linearly.
It can be obtained by INTEGRATING THE UNIT STEP FUNCTION. That means, a
unit step signal can be obtained by DIFFERENTIATING THE UNIT RAMP SIGNAL. ^whq8eA9l

ie. ^DpOYDh0F

r(t) =    u(t)dt =   dt  = t     for t >= 0 ^JzJHIz7K

u(t) =  d ^lALheTSQ

dt ^bAXjQ0v6

r(t) ^qnvAdlOs

The delayed unit ramp signal r(t - a) is given by: ^iYe100yM

r(t - a) =  ^bcDEwR63

t - a   for t >= a

0       for t < a ^hTiAcDMo

OR ^WYRNbeVB

r(t - a) = (t - a)u(t - a) ^elp1j5Mk

The graphical representations of r(t) and r(t - a) are shown below: ^WEh6ADMv

r(t) ^4gJfcZJO

t ^tVnxtG8Q

0 ^YXmOu4l9

slope = 1 ^KvdTvjsO

slope = 1 ^UZLTYDzn

t ^JSn8Gxgq

a ^sy0KJFbK

0 ^wFcBp92x

r(t - a) ^EQWrYWcW

unit ramp signal ^x7XgxfEe

Delayed unit time signal ^JKhh9yTQ

The discrete-time unit ramp sequence r(n) is defined as: ^mtcn2Ocb

r[n] =  ^OFQAl7IU

n   for n >= 0

0  for  n < 0 ^O95oBwAd

                or    r[n] = n*u[n] ^chs9bSFl

The shifted version of the discrete-time unit ramp sequence r(n - k) is defined as ^59nHrgs3

r[n - k] =  ^F8xlfXY0

n - k   for n >= 0

0       for n < k ^ymn0WSxw

        or    r[n - k] = [n -k]*u[n - k] ^pL3OGigq

The graphical representation of r[n] and r[n - 2] are shown below ^V5QoENc8

r[n] ^iEBzLLqF

r[n - 2] ^siqxJr7N

0 ^vozEYIqO

1 ^4ZEDf3Lr

2 ^WgyNlM0D

3 ^Iohw5pbE

4 ^KJI1GBR5

-1 ^rFNzsJ2P

-2 ^wv5Nvg4I

-3 ^Szi7YDT2

0 ^GWXAg0CF

1 ^a27ceYv7

2 ^pPUaCe4I

3 ^9yFctAgd

4 ^SHJV6YWa

5 ^Ptm3v4aM

6 ^5e7HWWdr

-1 ^htNWltqC

n ^NGw8ZGGX

n ^ULVcWp69

THE UNIT IMPULSE FUNCTION ^1dmNPRUN

The unit impulse function is the most widely used elementary function in the analysis of signals and systems. The continuous-
time unit impulse function  (t) also called Dirac delta function, plays an important role in signal analysis. It is defined as: ^jivfDg5v

(t) dt = 1 ^Uyoe2kiI

and ^io9WM03u

(t) = 0   for t != 0 ^crKrSj4i

ie, as ^Jo6sQB2K

(t) =  ^VZetwckk

1    for t = 0 ^hhtlLm8T

0   for t != 0 ^Gy9zYtCk

That is, the impulse function has zero amplitude everywhere except at t = 0, At t = 0, the amplitude is infinity so that
the area under the curve is unity.  (t) can be represented as a limiting case of a rectangle pulse function. ^OHjyVQSZ

A delayed unit impulse function   (t - a) is defined as: ^Ex9VSF4s

(t - a) =  ^KVDO6Gp6

1    for t = a

0    for t != a ^nTcrJ9hK

The graphical representation of   (t)  and   (t - a) are shown below: ^c8J9gXDe

0 ^F2DYYKPK

x(t) ^D18Ca5uA

t ^zJSVhQ8f

1 /  ^MBMrol0m

0 ^Me4FA285

t ^Cr6jNGxc

1 ^FyL7tzU7

(t) ^LDOxNojP

a ^X5qWmd2Z

0 ^hDlEXOfL

t ^lK7XNaJP

1 ^o3dlzsbZ

(t - a) ^e1KYbaHN

(t) As a limiting case of a pulse ^AUtI4HIo

Unit impulse ^9uJ4VFXf

Delayed unit impulse ^js7g15UA

If the unit impulse function is assumed in the form of a pulse, then the following points may be observed about the unit impulse
function: ^rKYJJPhl

1. The width of the pulse is zero. This means the pulse exists only at t = 0
2. The height of the pulse the to infinity.
3. The area under the pulse is always unity.
4. the height of arrow indicates the total area under the impulse. ^ivsu2vEB

The integral of the unit impulse function is a unit step function and the derivative of unit step function is a unit impulse
function: ^O1oipscA

u(t) =  ^mBTQRlQF

u(t) ^kAFAlUUq

(t) dt ^6dJIgo4b

d ^BvUQapzT

dt ^TkAqdEUz

(t) =  ^62zS6P9q

and: ^qPgnsmUL

PROPERTIES OF CONTINUOUS-TIME UNIT IMPULSE FUNCTION ^E77RbNdZ

1. It is an even function of time t, i.e,   (t) =   (-t) ^T8XlxnLG

2. ^hodIcEDd

(t) dt = x(0); ^CgpusKyt

x(t) ^MpPLEC5V

(t - to) dt = x(to) ^r9xn1SVB

x(t) ^sB1XeCW4

3. ^TczP3JWl

(at) =  1 ^465LRtCB

|a| ^M0wa47m9

(t) ^KfJUoMAE

The discrete-time unit impulse function   [n], also called unit sample sequence, is defined as: ^1IBqd2hO

[n] =  ^L6sO5gQI

1   for n = 0

0  for n != 0 ^ISCTgalB

The shifted unit impulse function  [n - k] is defined as: ^NGSyDtT5

[n - k] =  ^VFNtIkV5

1   for n = k

0  for n != k ^QQTnyRzm

The graphical representation of   [n] and   [n - 3] are shown below: ^kmeA2PeF

PROPERTIES OF DISCRETE-TIME UNIT SAMPLE SEQUENCE ^txxMPsdJ

1 ^QuouKirz

1 ^3m4ajBwB

[n] ^PmaCaMsE

[n - 3] ^v7XfHOAx

0 ^0C9goRS4

1 ^cW52dHVj

2 ^iZBDS1zb

-1 ^TlA7zd4e

-2 ^UI73ASBg

n ^wdvN2zVp

n ^CCshRla6

-1 ^Tbg12d4T

0 ^LZM8Yle1

1 ^dqC801Lu

2 ^bb6O7wdA

3 ^AaMVBPYv

4 ^8ZJwIjOr

[n] = u[n] - u[n - 1] ^OYyKMZ7U

[n - k] =  ^k4RBylN8

x[n]    [n - no] = x[no] ^f70y0saV

[n - k] ^qiJ7XiUs

1. ^f7PgNdo9

1  for n = k

0 for n != k ^670EGwcb

x[n] =  ^eHrl2IE6

x[k] ^SgAD8UNj

2. ^r1AjENTd

4. ^O7neNGxr

3. ^z26NGnhv

k = - ^IJvEcpHO

n = - ^MssiayQj

4  x(t)   (t - to) = x(to)   (t - to)  = x(to);   x(t)   (t) = x(0)   (t) = x(0) ^T1kRy3Lf

5.  x(t) =       x(T)   (t - T) dT ^jjv4MEb4

RECTANGULAR PLUSE FUNCTION ^LP9PvMR9

The unit rectangular pulse function    (t/T) shown below is defined as: ^eg7HQCnM

t ^Nowo0RUB

T ^2ygf6jxk

 =  ^L8Z3w9jd

1  for |t| <= T / 2

0 otherwise ^eFzlanvU

It is an even function of t ^wKiIsok4

0 ^EGbQHl0d

T/2 ^4alS2hNg

-T/2 ^sBrxbXge

1 ^bXn9u0mL

(t / T) ^Irtk3633

t ^1qOnQQv7

Rectangular Pulse Function ^FOasrDAp

TRIANGULAR PULSE FUNCTION ^0rBlc7E7

The unit triangular pulse function    (t/T) shown below is defined as: ^P2OIgc42

t ^6UQOHEdR

T ^BQ8rQfRm

=  ^mzjKYW2S

1 - 2( |t| / T)   for |t| < (T/2)

0                for |t| > (T/2) ^7sp2VWxT

it is an even function of t. ^1lJQuxBv

1 ^81Z5TDqG

t ^BRL0ArZe

T/2 ^rHHph2Wk

-T/2 ^Uclg5rDA

0 ^vo0pbYQo

Triangular Pulse Function ^vwtfV6Sq

(t / T) ^mULYKlQN

SIGNUM FUNCTION ^4rGL31gI

The unit signum function sgn (t) shown below is defined as: ^7lxnPlfM

sgn(t) =  ^3f8WVgBW

1   for t > 0

-1 for  t < 0 ^YF5Nglqi

1 ^VGCoE2AO

-1 ^7ccrwVzX

0 ^tmZ9g261

t ^S1vcSOq2

Signum Function ^WEMqcPJf

The signum function can be expressed in terms of unit step function as:
                
                sgn(t) = -1 + 2u(t) ^FQYzfP1c

BASIC OPERATIONS ON SIGNALS ^j5mQkC5w

When we process a signal, this signal may undergo several manipulations involving the independent variable or the 
amplitude of the signal. The basic operations on signals are:

1. Time shifting                           2. Time reversal
3. Time scaling                           4. Amplitude scaling
5. Signal addition                         6 Signal multiplication

The first three operations correspond to transformation in independent variable t or n of a signal. The last there
operations correspond to transformation on amplitude of a signal. ^oT5HNN7F

TIME SHIFTING ^q5i6hbh0

Mathematically, the time shifting of a continuous-time signal x(t) or discrete time signal
x[n] can be represented by
                            y(t) = x(t - T)
OR
                            y[n] = x[n - T]

The time shifting of a signal may result in time delay or time advance. In the above equation
if T POSITIVE the shift is to the right and the shifting DELAYS the signal, and if T is
NEGATIVE the shift is to the left and then the shifting ADVANCES the signal. An arbitrary
signal x(t), its delayed version and advanced version are shown. Shifting a signal in time means
that a signal may be either advanced in the time axis or delayed in the time axis. ^fTNlmq7E

0 ^ad1Nv3cY

0 ^IzXpoJev

0 ^2ymECnB7

-T ^0Jbed7dH

-T + 6 ^TURDSxWZ

T + 6 ^a357eMck

T ^MNJPDXbL

6 ^TxuoOrsa

x(t) ^aCbwoLFU

x(t - T) ^apzTP7Ys

x(t + T) ^LSHnORAY

t ^gmbL9Vd1

t ^y1yOBH5p

t ^YCoFf75I

The same applies for discrete time signals ^78pIJFru

TIME REVERSAL ^QwHaLUPk

Time reversal, also called time folding of a signal x(t) can be obtained by folding the signal about t = 0.
This operation is very useful in CONVOLUTION. It is denoted by x(-t). It is obtained by replacing the 
independent variable t by (-t). Folding is also called REFLECTION of the signal about the time origin t = 0.
The figure below shows an arbitrary signal x(t) and its reflection: ^Sdo69CuJ

t ^a64uKK7w

t ^5vJlJeKj

x(-t) ^9o3ILhTq

A ^pY4JBO6g

A ^ixkhO7N1

x(t) ^qdaTxjgj

0 ^VgqpIsHr

1      2     3     4 ^9Crr21YV

-4    -3     -2    -1    0 ^SEAkas03

The signal x(-t + 3) obtained by shifting the reversed signal x(-t) to the right by 3 units (delay by 3 units)
is whown below. the signal x(-t - 3) obtained by shifting the reversed signal x(-t) to the left by 3 units
(advance by 3 units) is also shown below: ^NtgY17Tn

t ^TzcUfqjx

A ^K3UZb0D2

x(-t + 3) ^Pdztu4vS

0 ^KHChKOlG

1      2     3     4 ^XzwAB7z2

-1 ^RXYZJO7l

t ^Cp6H1tnj

x(-t - 3) ^dIt2fVlR

A ^aajgyalN

-4    -3     -2    -1    0 ^xzWCUtqx

-7    -6    -5 ^OB9WmbDQ

The same applies for discrete time signals ^AWGCZUo7

CLASSIFICATION OF SIGNALS ^ohK8RKAR

PERIODIC AND NON-PERIODIC SIGNALS ^IIoiFsFt

A periodic continuous-time signal satisfies
                x(t) = x(t + nT

Where
 n is an integer
 T is the period of the signal

A periodic signal is on that repeats itself every T seconds.


A popular example of a periodic signal is the sinusoid:
                x(t) = Asin(wt +  )
Where
A is the amplitude of the signal
w  is the angular frequency in radians per second
   is the phase in radians


A non periodic signal is one which does not repeat itself after T seconds. An
is the ramp function ^IlNcL5zs

ANALOG AND DIGITAL SIGNALS ^myRnOhgY

If a continuous time signal x(t) can assume any value in the range of -   < t  <   , then it is 
called an analog signal. Although all analog signals are continuous-time signals, not all continuous
time signals are analog signals.

If a discrete-time signal assumes only finite values, then it is called a digital signal.


    An ANALOG SIGNAL is a continuous-time signal in which the variations withe time is analogous
     (or proportional) to some physical phenomena. ^6M2ZQosr

A DIGITAL SIGNAL is a discrete-time signal that can have a finite number of values (usually binary). ^YieOTteI

A digital signal can assume only finite number of values. The difference between analog and digital
signals is that analog is a continuous electric signal, whereas digital is a discrete electric signal. ^0YBzISwn

ENERGY AND POWER SIGNALS ^f0nBBq5p

For continuous-time signals x(t), the normalized energy E of x(t) (assuming x(t) is real) is: ^zTtCcZQl

x(t)  dt ^qXl8f47u

2 ^lFcr209R

E =  ^oFcBDWzZ

If x(t) is complex valued, The above equation can be generalized: ^rmXKKUPX

| x(t) |  dt ^ySw2k17w

2 ^shvHdiQA

E =  ^CaJ1Xtev

Where |x(t)| is the magnitude of x(t). The normalized power P for real x(t) is: ^FEkJOveu

x(t)  dt ^m64ZnkJB

2 ^2WUxSGaj

P = lim  ^Bymc7IAW

T/2 ^2f8bArm8

T/2 ^5BmJTXhE

1 ^5CrbbMMe

T ^rPZKHwOV

T ^94xUPpPJ

This can be generalized for complex values x(t) as: ^pCpwyQAR

| x(t) |  dt ^8ZUw0C9y

2 ^oicN13Cb

P = lim  ^SJ2cWVna

T/2 ^nocNyVjO

T/2 ^5OtleyKn

1 ^w0CsDPgu

T ^60L5kf41

T ^HcVbjWmZ

Similarly, for a discrete-time signal x[n], the normalized energy E of x[n] is ^MBvcLUZb

E =    | x[n] | ^jGEynDIW

2 ^wSiJVrUT

n = - ^0GqIUjYs

While the normalized power P is: ^ekYSSSl8

        | x[n] | ^W8te6slb

2 ^8aQvqLAg

n = - ^uhC4Y6Id

N ^IheiWA3h

N ^sMLYC0gH

N ^OjU9aqxc

2N + 1 ^YKEJKgq8

1 ^8lcpFKhh

lim ^jxQsg3T1

P =  ^o5QI9qIv

Based on the definitions of E and P in the equation above, we define the following: ^VFAC5hWq

A signal x(t) or x[n] is an ENERGY SIGNAL if and only if  0 < E <    consequently P = 0 ^2X0aFDYW

A signal x(t) or x[n] is a POWER SIGNAL if and only if 0 < P <    and consequently E =  ^PHnbCuq6

Or in otherwords, A POWER SIGNAL HAS INFINITE ENERGY AND AN ENERGY SIGNAL HAS ZERO AVERAGE POWER ^ivPeyMjy

EVEN AND ODD SYMMETRY ^0v2LcOl2

By definition, a signal is even if  ^Tle7gDTc

x(t) = x(-t) ^iBSjoApS

A function is even if its plot is symmetric about the vertical axis; that is the signal for t < 0 is the mirror
image of the signal for t > 0. Examples are cos, t, t^2, and t^4. ^XAuk5Gav

By definition a signal is odd if ^sODkHIyR

x(t) = -x(-t) ^W2uCA9QH

The plot of an odd function is antisymmetrical about the vertical axis. Exaples of odd functions are t, t^3,
and sin t ^wtb09GSU

Any signal x(t) can be represented as the sum of even and odd signals as: ^Ro58bEX2

x(t) = x (t)  + x (t) ^aXDwpugQ

e ^mJCvbNXo

o ^GWkCogvm

Where x (t)  = 


and  x (t) =  ^g7weE1Om

e ^WOxVQg8N

o ^JJoKnIse

[x(t) + x(-t)] ^g1Jh6m50

2 ^eN0lV6fB

[x(t) - x(-t)] ^Erni9UgD

2 ^pnfbXc5B

PROPERTIES OF EVEN AND ODD FUNCTIONS ^wWtMHVcR

1. The product of two even functions is also an even function.
2. The product of two odd functions is an even function.
3. The product of an even function and an odd function is an odd function.
4. The sum (or difference) of two even functions is also an even function.
5. The sum (or difference) of two odd functions is an odd function.
6. the sum (or difference) of an even function and an odd function is neither even or odd. ^f9o1s29V

SINUSOIDAL FUNCTION ^avlbZdEg

A continuous-time sinusoidal signal in the most general form is given by ^MEIb6i7u

x(t) = A sin (wt +  ) ^iPe6y59F

Where
    A = Amplitude
    w = Angular frequency in radians
      = Phase angle in radians ^fPFgAIT0

TIME SCALING ^0wtb5j5S

Time scaling involves the compression or expansion of a signal in time. Given a continuous-time signal x(t), the time-scalled
form x(t) is x(at), where a is a constant. The scaled signal x(at) will be compressed is |a| > 1 or expanded if |a| < 1;
a negative value of a yields time reversal as well as compression or expansion.

Again, we can obtain x(at) from a signal by replacing every t with at and simplifying. Notice that the time reversal can be
considered a special case of time scaling with the scaling factor a = -1 ^D7TtYJdm

y(t) = x(at)  Time Scaling ^PQgDxRDh

t ^Ko38g0lS

x(t) ^LxVv1e6V

1 ^36SRqa2L

1 ^tS1Lys66

0 ^OEs8xQZS

-1 ^fJXcVHxk

t ^01bhP3pj

y(x) = x(2t) ^dF0RJV9L

1 ^mkMeK9Vi

1/2 ^Fv6L3DzZ

0 ^Lo0VUx7h

-1/2 ^s6CDBvhj

t ^1OaspUVV

y(x) = x(1/2t) ^Jmd8DxtL

1 ^FdKBTS7M

2 ^WBej0l0M

0 ^T5yBxp2E

-2 ^adW6fpGe

a < 1 (signal expanded) ^H8HEUoFY

a > 1 (signal compressed ^fl2G5gyB

AMPLITUDE SCALING ^4U3xo1Wj

Amplitude transformations take the general form: ^h8iGeDiC

y(t) = Ax(t) + B ^ZDFxISKV

Where A and B are constants. For example, let ^aUbf9I0L

y(t) = -2x(t) + 4 ^GP3GP2X3

We notice that A = -2 means amplitude reversal (-x(t) implies reflection about the horizontal axis) and amplitude scaling
(|A| = 2). Also B = 4 shifts vertically the amplitude of the signal. ^MT8NiQCx

THE UNIT PARABOLIC FUNCTION ^rvqrmFw6

The continuous-time unit parabolic function p(t), also called unit acceleration signal starts at t = 0, and
is defined as:
 ^cJchVIt7

p(t) =  ^YYIGU6FW

t ^RBr8cAc2

2 ^eBAW4pxk

for t >= 0 ^SCSSanET

2 ^xMBFe1tC

0      for t < 0 ^nAdhbswR

t ^FV71CyYV

2 ^7wf9PFsV

2 ^tzOTN5HT

OR ^iq1trtgD

p(t) =  ^QHUy5vCk

u(t) ^57mVA6m5

The shifted version of the unit parabolic sequence p(t - a) is given by ^ET7FP59O

p(t - a) =  ^XPUDYBI6

for t >= a ^KOAF4bgB

(t - a) ^NR9ndnOr

2 ^R0GfB58S

2 ^lVu18gtY

0      for t < a ^GBMG4EUQ

(t - a) ^LpMiOcfZ

2 ^NDGgzcbh

2 ^ucOkFdZg

OR ^yVd1ekta

p(t - a) =  ^sE4FxUEJ

u(t - a) ^olrpKV8a

The graphical representations of p(t) and p(t - a) are shown below: ^wTxyvsl6

0 ^bljhlHfo

a ^gn4z02NS

t ^145U9vB2

t ^oDsoocav

0 ^1wWqXFif

p(t) ^ZbGINOX0

p(t - a) ^M1BCkwdc

The unit parabolic function can be obtained by integrating the unit ramp function or double
integrating the unit step function ^ab4cVO59

p(t) =     u(t) dt =   r(t) dt =   tdt =          for t >= 0 ^Py0kh4Jh

t ^HYPzD8XW

2 ^2lfW7OCe

2 ^sNh8bB0p

The ramp function is the derivative of the parabolic function and step function is double derivative
of the parabolic function ^fjlPvrf1

r(t) =     p(t);      u(t) =      p(t) ^JuW0iiuc

d ^Ad0zILn3

dt ^QuXxbG4b

2 ^9jyl4b2x

d ^K8wlFZmL

dt ^WYysiwdj

2 ^ZC938EFW

The same applies for discrete time parabolic signals ^FzDSaYBI

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.0.13",
	"elements": [
		{
			"type": "text",
			"version": 253,
			"versionNonce": 925104880,
			"isDeleted": false,
			"id": "Mt3iORSe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -177.86318120152958,
			"y": -999.3140394888518,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 501.93115234375,
			"height": 51.81649780273436,
			"seed": 1215469583,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097074,
			"link": null,
			"locked": false,
			"fontSize": 41.45319824218749,
			"fontFamily": 1,
			"text": "SIGNALS AND SYSTEMS",
			"rawText": "SIGNALS AND SYSTEMS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "SIGNALS AND SYSTEMS",
			"lineHeight": 1.25,
			"baseline": 35
		},
		{
			"type": "text",
			"version": 123,
			"versionNonce": 962685968,
			"isDeleted": false,
			"id": "XUg0OY1d",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -438.50673974335075,
			"y": -812.0719746041212,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 88.97993469238281,
			"height": 25,
			"seed": 1597494369,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "SIGNALS",
			"rawText": "SIGNALS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "SIGNALS",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 181,
			"versionNonce": 415702256,
			"isDeleted": false,
			"id": "4XLU6e3e",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 332.2478771302542,
			"y": -830.1631872854828,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 91.67991638183594,
			"height": 25,
			"seed": 238775009,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "SYSTEMS",
			"rawText": "SYSTEMS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "SYSTEMS",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "rectangle",
			"version": 187,
			"versionNonce": 276392464,
			"isDeleted": false,
			"id": "KcMVt1diolcb-rVzRO3yl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -477.54691831477925,
			"y": -820.2163162091714,
			"strokeColor": "#846358",
			"backgroundColor": "transparent",
			"width": 164.84259033203125,
			"height": 41.80216979980469,
			"seed": 1897015617,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "0kEcwzinIpSxonfqsjuxT",
					"type": "arrow"
				}
			],
			"updated": 1703931097075,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 139,
			"versionNonce": 1572208368,
			"isDeleted": false,
			"id": "6JCLdN0cZsoAberlyzhal",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 303.96241570447296,
			"y": -840.0470068655609,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 151.43438720703125,
			"height": 44.95707702636719,
			"seed": 548896993,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "B7CP8qdlRFiuxA6VYjH29",
					"type": "arrow"
				}
			],
			"updated": 1703931097075,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 86,
			"versionNonce": 2145495056,
			"isDeleted": false,
			"id": "YsoFR7sEu73GUNO6GS-L1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -196.87510870958954,
			"y": -1019.8483374319671,
			"strokeColor": "#6741d9",
			"backgroundColor": "transparent",
			"width": 538.6961059570312,
			"height": 74.13972473144531,
			"seed": 716124207,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "B7CP8qdlRFiuxA6VYjH29",
					"type": "arrow"
				},
				{
					"id": "0kEcwzinIpSxonfqsjuxT",
					"type": "arrow"
				}
			],
			"updated": 1703931097075,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 59,
			"versionNonce": 645439728,
			"isDeleted": false,
			"id": "B7CP8qdlRFiuxA6VYjH29",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 77.59962273572296,
			"y": -938.6101324759125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 287.88299560546875,
			"height": 92.28028869628906,
			"seed": 929756033,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YsoFR7sEu73GUNO6GS-L1",
				"focus": 0.3445863804019655,
				"gap": 7.098480224609375
			},
			"endBinding": {
				"elementId": "6JCLdN0cZsoAberlyzhal",
				"focus": 0.5178781922511188,
				"gap": 6.2828369140625
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					287.88299560546875,
					92.28028869628906
				]
			]
		},
		{
			"type": "arrow",
			"version": 270,
			"versionNonce": 328345104,
			"isDeleted": false,
			"id": "0kEcwzinIpSxonfqsjuxT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 52.75904063278304,
			"y": -939.398844023764,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 425.3884230719351,
			"height": 112.11097935267856,
			"seed": 1956170177,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YsoFR7sEu73GUNO6GS-L1",
				"focus": -0.353353007325735,
				"gap": 6.3097686767578125
			},
			"endBinding": {
				"elementId": "KcMVt1diolcb-rVzRO3yl",
				"focus": -0.5171775364020458,
				"gap": 7.0715484619140625
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-425.3884230719351,
					112.11097935267856
				]
			]
		},
		{
			"type": "text",
			"version": 333,
			"versionNonce": 1117192944,
			"isDeleted": false,
			"id": "BBBvqQAe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -765.5630859827132,
			"y": -662.3371869628686,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 674.9027709960938,
			"height": 30.322393073740457,
			"seed": 1764960033,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"fontSize": 24.257914458992367,
			"fontFamily": 1,
			"text": "Anything that carries information can be called a signal.",
			"rawText": "Anything that carries information can be called a signal.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Anything that carries information can be called a signal.",
			"lineHeight": 1.25,
			"baseline": 21
		},
		{
			"type": "text",
			"version": 548,
			"versionNonce": 411231248,
			"isDeleted": false,
			"id": "DCawoYhH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -794.3873570485616,
			"y": -618.9145969796098,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 801.8811645507812,
			"height": 143.30593443582745,
			"seed": 366873921,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"fontSize": 22.92894950973239,
			"fontFamily": 1,
			"text": "A signal can be defined as a single-valued function of one or more\nindependent variables which contain some information. A signal may also\nbe defined as any physical quantity that varies with time, space or\nany other independent variable. A signal may be represented in time \ndomain or frequency domain.",
			"rawText": "A signal can be defined as a single-valued function of one or more\nindependent variables which contain some information. A signal may also\nbe defined as any physical quantity that varies with time, space or\nany other independent variable. A signal may be represented in time \ndomain or frequency domain.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A signal can be defined as a single-valued function of one or more\nindependent variables which contain some information. A signal may also\nbe defined as any physical quantity that varies with time, space or\nany other independent variable. A signal may be represented in time \ndomain or frequency domain.",
			"lineHeight": 1.25,
			"baseline": 135
		},
		{
			"type": "text",
			"version": 812,
			"versionNonce": 1352213744,
			"isDeleted": false,
			"id": "nDp9dE86",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -800.3663696741195,
			"y": -450.47022180522356,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 831.6767578125,
			"height": 289.5282915782418,
			"seed": 312759439,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"fontSize": 23.162263326259346,
			"fontFamily": 1,
			"text": "Human speech is a familiar example of a signal. Electric current and\nvoltage are also examples of signals. A signal can be a function of one\nor more independent variables. A signal may be a function of time,\ntemperature, position, pressure, distance, e.t.c.\n\nif a signal depends on only one independent variable, it is called a \nONE-DIMENSIONAL SIGNAL, and if a signal depends on two independent\nvariables, it is called a TWO-DIMENSIONAL SIGNAL. And if the signal \ndepends on more independent variables, it is a MULTI-DIMENSIONAL\nSIGNAL.",
			"rawText": "Human speech is a familiar example of a signal. Electric current and\nvoltage are also examples of signals. A signal can be a function of one\nor more independent variables. A signal may be a function of time,\ntemperature, position, pressure, distance, e.t.c.\n\nif a signal depends on only one independent variable, it is called a \nONE-DIMENSIONAL SIGNAL, and if a signal depends on two independent\nvariables, it is called a TWO-DIMENSIONAL SIGNAL. And if the signal \ndepends on more independent variables, it is a MULTI-DIMENSIONAL\nSIGNAL.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Human speech is a familiar example of a signal. Electric current and\nvoltage are also examples of signals. A signal can be a function of one\nor more independent variables. A signal may be a function of time,\ntemperature, position, pressure, distance, e.t.c.\n\nif a signal depends on only one independent variable, it is called a \nONE-DIMENSIONAL SIGNAL, and if a signal depends on two independent\nvariables, it is called a TWO-DIMENSIONAL SIGNAL. And if the signal \ndepends on more independent variables, it is a MULTI-DIMENSIONAL\nSIGNAL.",
			"lineHeight": 1.25,
			"baseline": 281
		},
		{
			"type": "rectangle",
			"version": 558,
			"versionNonce": 2091639312,
			"isDeleted": false,
			"id": "m_9ZTAhWuxGc4zIqckasC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -859.7893613450003,
			"y": -765.5521967066958,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 929.3381129673547,
			"height": 973.5773620605466,
			"seed": 2132095681,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 165,
			"versionNonce": 1577518832,
			"isDeleted": false,
			"id": "2GPgj5Nu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -728.4592860628576,
			"y": -110.79433859381561,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 673.0664672851562,
			"height": 32.45109610504534,
			"seed": 2036740961,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"fontSize": 25.960876884036267,
			"fontFamily": 1,
			"text": "REPRESENTATIONS OF DISCRETE-TIME SIGNALS",
			"rawText": "REPRESENTATIONS OF DISCRETE-TIME SIGNALS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "REPRESENTATIONS OF DISCRETE-TIME SIGNALS",
			"lineHeight": 1.25,
			"baseline": 22
		},
		{
			"type": "text",
			"version": 99,
			"versionNonce": 788865040,
			"isDeleted": false,
			"id": "AS7iAguG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -799.373440115592,
			"y": -729.159695039128,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 223.3731689453125,
			"height": 33.83894828515952,
			"seed": 127913025,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"fontSize": 27.071158628127616,
			"fontFamily": 1,
			"text": "INTRODUCTION",
			"rawText": "INTRODUCTION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "INTRODUCTION",
			"lineHeight": 1.25,
			"baseline": 24
		},
		{
			"type": "text",
			"version": 993,
			"versionNonce": 124299504,
			"isDeleted": false,
			"id": "M3e1lYQJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -820.7960170198888,
			"y": -45.920620332096746,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 881.5391235351562,
			"height": 300,
			"seed": 1046554415,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "ckQXNxQsunZp-vW9nhS3e",
					"type": "arrow"
				},
				{
					"id": "ULLmPUoIxmP0p7KOr_UXW",
					"type": "arrow"
				}
			],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "In General signals may be CONTINUOUS-TIME SIGNALS or DISCRETE-TIME SIGNALS.\nContinuous-time signals are defined for all instants of time, whereas  discrete-time\nsignals are defined only at discrete instants of time. Continuous time signals are \nrepresented by x(t) and discrete-time signals are represented by x[n] where t and n are\nindependent variables in time domain. Continuous-time signals are represented by a \nfunction or a graph.\n\n    There are four ways of representing discrete-time signals. They are:\n    1.  Graphical Representation                      2. Functional Representation\n    3. Tabular representation                        4. Sequence Representation.\n\n",
			"rawText": "In General signals may be CONTINUOUS-TIME SIGNALS or DISCRETE-TIME SIGNALS.\nContinuous-time signals are defined for all instants of time, whereas  discrete-time\nsignals are defined only at discrete instants of time. Continuous time signals are \nrepresented by x(t) and discrete-time signals are represented by x[n] where t and n are\nindependent variables in time domain. Continuous-time signals are represented by a \nfunction or a graph.\n\n    There are four ways of representing discrete-time signals. They are:\n    1.  Graphical Representation                      2. Functional Representation\n    3. Tabular representation                        4. Sequence Representation.\n\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "In General signals may be CONTINUOUS-TIME SIGNALS or DISCRETE-TIME SIGNALS.\nContinuous-time signals are defined for all instants of time, whereas  discrete-time\nsignals are defined only at discrete instants of time. Continuous time signals are \nrepresented by x(t) and discrete-time signals are represented by x[n] where t and n are\nindependent variables in time domain. Continuous-time signals are represented by a \nfunction or a graph.\n\n    There are four ways of representing discrete-time signals. They are:\n    1.  Graphical Representation                      2. Functional Representation\n    3. Tabular representation                        4. Sequence Representation.\n\n",
			"lineHeight": 1.25,
			"baseline": 290
		},
		{
			"type": "line",
			"version": 115,
			"versionNonce": 2139528720,
			"isDeleted": false,
			"id": "x_VRkByhSiF3Qj0GnnO1S",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -804.7707484652013,
			"y": -69.46105612311231,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 837.621154785156,
			"height": 0,
			"seed": 1913885121,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					837.621154785156,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 42,
			"versionNonce": 407243504,
			"isDeleted": false,
			"id": "LebYcxtTnAU4Vt7zsj7Kx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -815.8128474642248,
			"y": -687.0654262402998,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 250.81312561035145,
			"height": 0,
			"seed": 1452343535,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					250.81312561035145,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 212,
			"versionNonce": 2133351440,
			"isDeleted": false,
			"id": "J8azZA9D",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1638.5939601351226,
			"y": 50.64673196282513,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 314.9797058105469,
			"height": 25,
			"seed": 137072719,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "GRAPHICAL REPRESENTATION",
			"rawText": "GRAPHICAL REPRESENTATION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "GRAPHICAL REPRESENTATION",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "arrow",
			"version": 500,
			"versionNonce": 723987696,
			"isDeleted": false,
			"id": "nEGb27pyS3EmZkzuJd-zd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -793.102444021842,
			"y": 157.91437112298138,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 265.01013183593716,
			"height": 111.99838256835938,
			"seed": 1283150607,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097075,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-145.1246337890624,
					-82.02691650390625
				],
				[
					-265.01013183593716,
					-111.99838256835938
				]
			]
		},
		{
			"type": "text",
			"version": 280,
			"versionNonce": 1608669712,
			"isDeleted": false,
			"id": "s4cSsZiP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1777.846462576529,
			"y": 102.56253396477814,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 661.2791748046875,
			"height": 50,
			"seed": 1459631073,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "consider a signal x[n] with values\nx[-2] = -3, x[-1] = 2, x[0] = 0, x[1] = 3, x[2] = 1 and x[3] = 2",
			"rawText": "consider a signal x[n] with values\nx[-2] = -3, x[-1] = 2, x[0] = 0, x[1] = 3, x[2] = 1 and x[3] = 2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "consider a signal x[n] with values\nx[-2] = -3, x[-1] = 2, x[0] = 0, x[1] = 3, x[2] = 1 and x[3] = 2",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "text",
			"version": 149,
			"versionNonce": 1234439920,
			"isDeleted": false,
			"id": "HALzwb2B",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1778.8077662874666,
			"y": 190.49182473626252,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 581.9593505859375,
			"height": 25,
			"seed": 1115468239,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The discrete-time signal can be represented graphically as:",
			"rawText": "The discrete-time signal can be represented graphically as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The discrete-time signal can be represented graphically as:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 122,
			"versionNonce": 1420597264,
			"isDeleted": false,
			"id": "ugKb4fuMq5go8j2dyEcyU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1738.981197683951,
			"y": 405.56586038079377,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 559.9915466308591,
			"height": 0,
			"seed": 482038401,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					559.9915466308591,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 147,
			"versionNonce": 202682608,
			"isDeleted": false,
			"id": "eHgaZOZQvuMWe_M1B6S1n",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1634.8700526644197,
			"y": 500.21240579095,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 15.774383544921875,
			"height": 17.351806640625,
			"seed": 1014808271,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 164,
			"versionNonce": 1904154128,
			"isDeleted": false,
			"id": "yiPvHurXa2gNbCsG2LcsS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1576.553570120475,
			"y": 327.48089944329377,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 15.774383544921875,
			"height": 17.351806640625,
			"seed": 707252655,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 129,
			"versionNonce": 976294640,
			"isDeleted": false,
			"id": "0r5MatAFAIUZa3LCipaeb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1491.8498652864905,
			"y": 397.7031284472,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 15.774383544921875,
			"height": 17.351806640625,
			"seed": 1565993089,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 145,
			"versionNonce": 189912080,
			"isDeleted": false,
			"id": "d4lMQsngNz_75jrycyJjN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1403.5821040560213,
			"y": 267.04144631829377,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 15.774383544921875,
			"height": 17.351806640625,
			"seed": 1085582145,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 145,
			"versionNonce": 1785804016,
			"isDeleted": false,
			"id": "FMi9CFJeNW1P2GM9yet8b",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1319.8076899935213,
			"y": 349.12567483391877,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 15.774383544921875,
			"height": 17.351806640625,
			"seed": 386112911,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 143,
			"versionNonce": 404541968,
			"isDeleted": false,
			"id": "Nu2enqSCyR697JsEajHWs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1226.3852046419588,
			"y": 311.63238870110627,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 15.774383544921875,
			"height": 17.351806640625,
			"seed": 280789665,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 135,
			"versionNonce": 576526064,
			"isDeleted": false,
			"id": "Spy-wWRRUPg8HzZUqIBd0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1630.1377223421541,
			"y": 500.2122837206375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 0,
			"height": 91.4915771484375,
			"seed": 570840111,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-91.4915771484375
				]
			]
		},
		{
			"type": "line",
			"version": 169,
			"versionNonce": 249040912,
			"isDeleted": false,
			"id": "UdkFd7VNo6xSIrLY37zSC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1567.3288008650786,
			"y": 408.7207065722,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 0,
			"height": 60.57189679034059,
			"seed": 1009136527,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-60.57189679034059
				]
			]
		},
		{
			"type": "line",
			"version": 157,
			"versionNonce": 1987885296,
			"isDeleted": false,
			"id": "5CMXYeY5nQU5tkbasyIQ9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1396.7933699568755,
			"y": 400.83356057610627,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 0,
			"height": 113.19152569659059,
			"seed": 80465057,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-113.19152569659059
				]
			]
		},
		{
			"type": "line",
			"version": 192,
			"versionNonce": 1199279632,
			"isDeleted": false,
			"id": "uN7ovN5fz_4DJWYoe7qBG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1311.8641707381255,
			"y": 403.9884067675125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 0,
			"height": 35.64269757159059,
			"seed": 1332288047,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-35.64269757159059
				]
			]
		},
		{
			"type": "line",
			"version": 151,
			"versionNonce": 710417136,
			"isDeleted": false,
			"id": "g354Ymf1eElkOm8gTcz__",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1219.5257307967192,
			"y": 402.8945373209219,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 0,
			"height": 72.562255859375,
			"seed": 1465042945,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-72.562255859375
				]
			]
		},
		{
			"type": "text",
			"version": 102,
			"versionNonce": 1526680592,
			"isDeleted": false,
			"id": "2LHNxZxV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1605.4693568636385,
			"y": 496.29486428704377,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 21.8399658203125,
			"height": 25,
			"seed": 277350127,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-3",
			"rawText": "-3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-3",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 1349991664,
			"isDeleted": false,
			"id": "zX0OO6XJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1656.6949733187166,
			"y": 411.18207131829377,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 22.459976196289062,
			"height": 25,
			"seed": 171856783,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-2",
			"rawText": "-2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 93,
			"versionNonce": 56314384,
			"isDeleted": false,
			"id": "miY9pMz0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1575.8077662874666,
			"y": 411.6046177050125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 13.639984130859375,
			"height": 25,
			"seed": 993500495,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-1",
			"rawText": "-1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 1784815344,
			"isDeleted": false,
			"id": "RDMLnVUL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1492.6949428011387,
			"y": 419.6046177050125,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 1088224975,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 100,
			"versionNonce": 2072479760,
			"isDeleted": false,
			"id": "B0nzOHzg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1397.9626735140293,
			"y": 411.1400180956375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 32577473,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 103,
			"versionNonce": 144752880,
			"isDeleted": false,
			"id": "LZo5HEy6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1318.7370875765293,
			"y": 414.13995706048127,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 14.239990234375,
			"height": 25,
			"seed": 2111483713,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 100,
			"versionNonce": 1601963536,
			"isDeleted": false,
			"id": "6ckbJvxn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1227.272426931998,
			"y": 416.29486428704377,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 13.619979858398438,
			"height": 25,
			"seed": 1115457217,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097076,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "3",
			"rawText": "3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 135,
			"versionNonce": 1790649072,
			"isDeleted": false,
			"id": "s3Gb97ud",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -734.8549159456701,
			"y": 361.37564431634075,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e9ecef",
			"width": 296.0797119140625,
			"height": 25,
			"seed": 961824321,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "TABULAR REPRESENTATION",
			"rawText": "TABULAR REPRESENTATION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "TABULAR REPRESENTATION",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "rectangle",
			"version": 82,
			"versionNonce": 204522512,
			"isDeleted": false,
			"id": "PFXzwi8TscwuGgF7R8S-H",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1829.684894888541,
			"y": -36.93917501959666,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 736.6649398803709,
			"height": 577.3433837890623,
			"seed": 5537935,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 308,
			"versionNonce": 523846896,
			"isDeleted": false,
			"id": "wkqVoL8J",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -987.1191981722324,
			"y": 410.037326445247,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 788.3391723632812,
			"height": 75,
			"seed": 1748410671,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "In this, the sampling instant n and the magnitude of the signal at the sampling\ninstant are represented in tabular form. The signal given in the graphical \nrepresentation can be represented in tabular form as:",
			"rawText": "In this, the sampling instant n and the magnitude of the signal at the sampling\ninstant are represented in tabular form. The signal given in the graphical \nrepresentation can be represented in tabular form as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "In this, the sampling instant n and the magnitude of the signal at the sampling\ninstant are represented in tabular form. The signal given in the graphical \nrepresentation can be represented in tabular form as:",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "rectangle",
			"version": 118,
			"versionNonce": 2141045264,
			"isDeleted": false,
			"id": "fU1AVShIvn6oCa6Hcpedm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1021.9104808260408,
			"y": 329.8453098436845,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 907.0285873413084,
			"height": 306.0235595703124,
			"seed": 93858511,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "T3Np1dXP18TzCR58R3m-X",
					"type": "arrow"
				}
			],
			"updated": 1703931097077,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 227,
			"versionNonce": 597894896,
			"isDeleted": false,
			"id": "T3Np1dXP18TzCR58R3m-X",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -794.7589381624666,
			"y": 189.4530979296221,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 282.95044159497604,
			"height": 115.15319824218747,
			"seed": 525102575,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "fU1AVShIvn6oCa6Hcpedm",
				"gap": 25.239013671874943,
				"focus": 0.5940831594582919
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-127.77273559570312,
					42.59091186523432
				],
				[
					155.17770599927292,
					115.15319824218747
				]
			]
		},
		{
			"type": "text",
			"version": 85,
			"versionNonce": 951779344,
			"isDeleted": false,
			"id": "HNrzgz4O",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -733.2202418734042,
			"y": 528.4463535448565,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 262.47967529296875,
			"height": 25,
			"seed": 1048661345,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "n   -2   -1   0   1   2  3",
			"rawText": "n   -2   -1   0   1   2  3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "n   -2   -1   0   1   2  3",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 31,
			"versionNonce": 75548912,
			"isDeleted": false,
			"id": "lIRN2XpA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -747.2892726351229,
			"y": 560.5019260546221,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40.39996337890625,
			"height": 25,
			"seed": 129158273,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x[n]",
			"rawText": "x[n]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x[n]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 68,
			"versionNonce": 394296848,
			"isDeleted": false,
			"id": "4PyJDg2o",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -693.8666346956697,
			"y": 563.5019870897784,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 233.11968994140625,
			"height": 25,
			"seed": 1814180449,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-3   2   0   3   1   2",
			"rawText": "-3   2   0   3   1   2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-3   2   0   3   1   2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 79,
			"versionNonce": 2103061232,
			"isDeleted": false,
			"id": "gYUABEBJJKI7P3GePta8J",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -797.223629324576,
			"y": 553.0153537889971,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 388.05047607421864,
			"height": 0,
			"seed": 2013533871,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					388.05047607421864,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 95,
			"versionNonce": 1021721616,
			"isDeleted": false,
			"id": "psUDODvLs243jDv24x_q_",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -795.9547795802265,
			"y": 592.1885370032538,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 388.05047607421864,
			"height": 0,
			"seed": 535229441,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					388.05047607421864,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 96,
			"versionNonce": 414665968,
			"isDeleted": false,
			"id": "uZTQfcPX2rHY7I3Wkf5ph",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -799.6164006739765,
			"y": 513.2727655188789,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 388.05047607421864,
			"height": 0,
			"seed": 82276559,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					388.05047607421864,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 56,
			"versionNonce": 1793341968,
			"isDeleted": false,
			"id": "yzg1dmtFrNVGaQYo2Vsuv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -696.2673610140291,
			"y": 612.9580722948565,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.57745361328125,
			"height": 110.42083740234364,
			"seed": 1582638977,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.57745361328125,
					-110.42083740234364
				]
			]
		},
		{
			"type": "line",
			"version": 64,
			"versionNonce": 1344286448,
			"isDeleted": false,
			"id": "eLNLEkxGmvH-OtX8w3F_I",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -754.438491243832,
			"y": 607.8229624340338,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.57745361328125,
			"height": 110.42083740234364,
			"seed": 1119079265,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.57745361328125,
					-110.42083740234364
				]
			]
		},
		{
			"type": "line",
			"version": 60,
			"versionNonce": 1685223440,
			"isDeleted": false,
			"id": "V8ymUWP7GHFrPlL-jTUfp",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -655.0580285973476,
			"y": 612.2741648266119,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.57745361328125,
			"height": 110.42083740234364,
			"seed": 1876105071,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.57745361328125,
					-110.42083740234364
				]
			]
		},
		{
			"type": "line",
			"version": 50,
			"versionNonce": 740086000,
			"isDeleted": false,
			"id": "NYLJxMS4rajaOhezUN5S-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -617.325698275082,
			"y": 613.3162180492682,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.57745361328125,
			"height": 110.42083740234364,
			"seed": 581144257,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.57745361328125,
					-110.42083740234364
				]
			]
		},
		{
			"type": "line",
			"version": 55,
			"versionNonce": 1300821520,
			"isDeleted": false,
			"id": "gTO3dodDak7htiflD6VJF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -571.9031518883633,
			"y": 613.5838572094244,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.57745361328125,
			"height": 110.42083740234364,
			"seed": 1395364367,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.57745361328125,
					-110.42083740234364
				]
			]
		},
		{
			"type": "line",
			"version": 67,
			"versionNonce": 1681208048,
			"isDeleted": false,
			"id": "bBPb-zBBibN7TTzuPv-n0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -535.1707910485195,
			"y": 610.8516184398932,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.57745361328125,
			"height": 110.42083740234364,
			"seed": 527250977,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.57745361328125,
					-110.42083740234364
				]
			]
		},
		{
			"type": "line",
			"version": 50,
			"versionNonce": 186627088,
			"isDeleted": false,
			"id": "BD--sNF-TP2BG0IRZLqjV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -499.325698275082,
			"y": 615.3162180492682,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.57745361328125,
			"height": 110.42083740234364,
			"seed": 247687343,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.57745361328125,
					-110.42083740234364
				]
			]
		},
		{
			"type": "line",
			"version": 50,
			"versionNonce": 2129745136,
			"isDeleted": false,
			"id": "gFo4L7rrQSSI_lke076MS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -455.325698275082,
			"y": 615.3162180492682,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.57745361328125,
			"height": 110.42083740234364,
			"seed": 6439297,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.57745361328125,
					-110.42083740234364
				]
			]
		},
		{
			"type": "text",
			"version": 120,
			"versionNonce": 590262800,
			"isDeleted": false,
			"id": "O9ovJZgI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1215.2505458284822,
			"y": 747.5591465136065,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 330.39971923828125,
			"height": 25,
			"seed": 2145987919,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "FUNCTIONAL REPRESENTATION",
			"rawText": "FUNCTIONAL REPRESENTATION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "FUNCTIONAL REPRESENTATION",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 198,
			"versionNonce": 1910060784,
			"isDeleted": false,
			"id": "ctn0A12D",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1366.6697352816072,
			"y": 809.5019260546221,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 695.4793090820312,
			"height": 75,
			"seed": 551166401,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097077,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "In this, the amplitude of the signal is written against the value of n.\nThe signal in the graphical and tabular form can be represented in \nfunctional form as:",
			"rawText": "In this, the amplitude of the signal is written against the value of n.\nThe signal in the graphical and tabular form can be represented in \nfunctional form as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "In this, the amplitude of the signal is written against the value of n.\nThe signal in the graphical and tabular form can be represented in \nfunctional form as:",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "text",
			"version": 113,
			"versionNonce": 481161232,
			"isDeleted": false,
			"id": "7VyQHDWb",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1104.6697352816072,
			"y": 923.5019260546221,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 155.37979125976562,
			"height": 150,
			"seed": 2051245455,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-3   for n = -2\n2    for n = -1\n0    for n = 0\n3    for n = 1\n1     for n = 2\n2    for n = 3",
			"rawText": "-3   for n = -2\n2    for n = -1\n0    for n = 0\n3    for n = 1\n1     for n = 2\n2    for n = 3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-3   for n = -2\n2    for n = -1\n0    for n = 0\n3    for n = 1\n1     for n = 2\n2    for n = 3",
			"lineHeight": 1.25,
			"baseline": 141
		},
		{
			"type": "rectangle",
			"version": 59,
			"versionNonce": 1098176752,
			"isDeleted": false,
			"id": "4wSVwYAqCnaToWy8buKUe",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1121.5233119417635,
			"y": 911.5439792772784,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 194.0252685546874,
			"height": 176.67340087890625,
			"seed": 264917729,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 63,
			"versionNonce": 1603628560,
			"isDeleted": false,
			"id": "LYhk8aC2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1214.7976649691072,
			"y": 983.2342258593096,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 72.73991394042969,
			"height": 25,
			"seed": 1241255151,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x[n] = ",
			"rawText": "x[n] = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x[n] = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 66,
			"versionNonce": 558643952,
			"isDeleted": false,
			"id": "EspxTUrJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1314.6831935335604,
			"y": 1120.1786838671221,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 188.5797882080078,
			"height": 25,
			"seed": 1488020815,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Another example is:",
			"rawText": "Another example is:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Another example is:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 62,
			"versionNonce": 350039056,
			"isDeleted": false,
			"id": "5Y93IgUw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1043.6697352816072,
			"y": 1175.5019260546221,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 183.4197998046875,
			"height": 50,
			"seed": 2072366031,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2+4n   for n >= 0\n0       for n < 0",
			"rawText": "2+4n   for n >= 0\n0       for n < 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2+4n   for n >= 0\n0       for n < 0",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "text",
			"version": 85,
			"versionNonce": 333929712,
			"isDeleted": false,
			"id": "gpbBNqs7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1166.490864126822,
			"y": 1187.8890720507159,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 72.73991394042969,
			"height": 25,
			"seed": 1939715777,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x[n] = ",
			"rawText": "x[n] = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x[n] = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "rectangle",
			"version": 69,
			"versionNonce": 108866064,
			"isDeleted": false,
			"id": "mKUKIa1Agf89sA_-_d5mZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1062.2842372347322,
			"y": 1167.9109836718096,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 222.41918945312477,
			"height": 59.9427490234375,
			"seed": 385221569,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 82,
			"versionNonce": 181288688,
			"isDeleted": false,
			"id": "_6JyrP45yxSBUMCGH24Gv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1448.545162527701,
			"y": 693.5658603807941,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 807.6497802734373,
			"height": 586.8080749511718,
			"seed": 1870000449,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 177,
			"versionNonce": 2137876496,
			"isDeleted": false,
			"id": "XUfhWtqTfSR4i-9JW_S2k",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -287.2825587679355,
			"y": 162.10123025384104,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 578.0942687988281,
			"height": 608.8922729492185,
			"seed": 1500928943,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-45.74578857421875,
					77.2946166992187
				],
				[
					138.81478881835938,
					123.04040527343744
				],
				[
					257.1228942871094,
					288.6716918945312
				],
				[
					225.57406616210938,
					533.1750488281248
				],
				[
					-143.54711914062494,
					608.8922729492185
				],
				[
					-320.97137451171875,
					571.0336303710935
				]
			]
		},
		{
			"type": "text",
			"version": 65,
			"versionNonce": 109633776,
			"isDeleted": false,
			"id": "drQd2fRL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -294.71349748863855,
			"y": 888.3891330858721,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 306.1396789550781,
			"height": 25,
			"seed": 2068199951,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "SEQUENCE REPRESENTATION",
			"rawText": "SEQUENCE REPRESENTATION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "SEQUENCE REPRESENTATION",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 122,
			"versionNonce": 732292624,
			"isDeleted": false,
			"id": "tXuc5zHx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -439.6697352816073,
			"y": 952.5019260546221,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 631.9793701171875,
			"height": 25,
			"seed": 1990206113,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A finite duration sequence of the signal can be represented as:",
			"rawText": "A finite duration sequence of the signal can be represented as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A finite duration sequence of the signal can be represented as:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 59,
			"versionNonce": 916407024,
			"isDeleted": false,
			"id": "4W0vlvyH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -264.66973528160736,
			"y": 1023.5019260546221,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 252.9397430419922,
			"height": 25,
			"seed": 101568815,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x[n] = {-3, 2, 0, 3, 1, 2}",
			"rawText": "x[n] = {-3, 2, 0, 3, 1, 2}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x[n] = {-3, 2, 0, 3, 1, 2}",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 60,
			"versionNonce": 2015274000,
			"isDeleted": false,
			"id": "ILVq7f5h",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -437.1326869417635,
			"y": 1082.5019260546221,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 183.7397918701172,
			"height": 25,
			"seed": 392987617,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Another example is",
			"rawText": "Another example is",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Another example is",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 77,
			"versionNonce": 429483248,
			"isDeleted": false,
			"id": "rTSufl0D",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -277.4155238558261,
			"y": 1140.5019260546221,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 277.3397216796875,
			"height": 25,
			"seed": 1650578753,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x[n] = {..., 2, 3, 0, 1, -2,...}",
			"rawText": "x[n] = {..., 2, 3, 0, 1, -2,...}",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x[n] = {..., 2, 3, 0, 1, -2,...}",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "arrow",
			"version": 34,
			"versionNonce": 1926210064,
			"isDeleted": false,
			"id": "z3RTosvuvAHYeFcAlRAi1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -106.58056291832611,
			"y": 1079.4311863085284,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 31.548828125,
			"seed": 1227945647,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-31.548828125
				]
			]
		},
		{
			"type": "arrow",
			"version": 34,
			"versionNonce": 486491888,
			"isDeleted": false,
			"id": "n0XeAjTXdefCz8jUkn-79",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -93.96099504723236,
			"y": 1196.1618381639971,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 31.548828125,
			"seed": 2023110831,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-31.548828125
				]
			]
		},
		{
			"type": "text",
			"version": 149,
			"versionNonce": 716234768,
			"isDeleted": false,
			"id": "CrPsvSpW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -449.52831682457605,
			"y": 1220.6432834764971,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 678.4393310546875,
			"height": 50,
			"seed": 116992815,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The arrow mark denotes the n = 0 term. When no arrow is indicated\nthe first term corresponds to n = 0",
			"rawText": "The arrow mark denotes the n = 0 term. When no arrow is indicated\nthe first term corresponds to n = 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The arrow mark denotes the n = 0 term. When no arrow is indicated\nthe first term corresponds to n = 0",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "rectangle",
			"version": 76,
			"versionNonce": 1029236976,
			"isDeleted": false,
			"id": "sP4r80g4dhOfI3e3Hfyrw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -488.770748465201,
			"y": 834.6332126757159,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 755.5942382812498,
			"height": 460.61273193359375,
			"seed": 1548143599,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "mKCEWYh-kMltPqrsGNSX8",
					"type": "arrow"
				}
			],
			"updated": 1703931097078,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 120,
			"versionNonce": 263872016,
			"isDeleted": false,
			"id": "mKCEWYh-kMltPqrsGNSX8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 18.05414167151764,
			"y": 188.14499246087223,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 113.57574462890625,
			"height": 629.3989868164061,
			"seed": 1994432353,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "sP4r80g4dhOfI3e3Hfyrw",
				"focus": -0.3950283450923148,
				"gap": 17.0892333984375
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					41.013427734375,
					102.53366088867188
				],
				[
					88.336669921875,
					276.0521850585937
				],
				[
					61.52020263671875,
					575.7659912109374
				],
				[
					-25.23907470703125,
					629.3989868164061
				]
			]
		},
		{
			"type": "text",
			"version": 167,
			"versionNonce": 640568048,
			"isDeleted": false,
			"id": "iKE4Pbso",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1689.1938576436237,
			"y": -629.9737867091749,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 550.5394287109375,
			"height": 25,
			"seed": 1075145185,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097078,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "SUM AND PRODUCT OF DISCRETE-TIME SEQUENCES",
			"rawText": "SUM AND PRODUCT OF DISCRETE-TIME SEQUENCES",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "SUM AND PRODUCT OF DISCRETE-TIME SEQUENCES",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 228,
			"versionNonce": 1390681104,
			"isDeleted": false,
			"id": "3W58LqmA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1774.2897438740924,
			"y": -572.0444959376905,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 793.459228515625,
			"height": 100,
			"seed": 1455037775,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The sum of two discrete-time sequences is obtained by adding the corresponding\nelements of the sequence.\n\n        {Cn} = {An} + {Bn}     Cn = An + Bn",
			"rawText": "The sum of two discrete-time sequences is obtained by adding the corresponding\nelements of the sequence.\n\n        {Cn} = {An} + {Bn}     Cn = An + Bn",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The sum of two discrete-time sequences is obtained by adding the corresponding\nelements of the sequence.\n\n        {Cn} = {An} + {Bn}     Cn = An + Bn",
			"lineHeight": 1.25,
			"baseline": 91
		},
		{
			"type": "arrow",
			"version": 69,
			"versionNonce": 1376218352,
			"isDeleted": false,
			"id": "-EMtbf5qYP0ym6QHFEwBO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1487.944651100655,
			"y": -486.04959237323743,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 33.126251220703125,
			"height": 1.57745361328125,
			"seed": 1399457665,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					33.126251220703125,
					1.57745361328125
				]
			]
		},
		{
			"type": "text",
			"version": 215,
			"versionNonce": 1176902160,
			"isDeleted": false,
			"id": "XOXsBDPj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1782.2897438740924,
			"y": -427.04449593769056,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 740.0391845703125,
			"height": 100,
			"seed": 111979361,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The product of two discrete-time sequences is obtained by multiplying the \ncorresponding elements of the sequence.\n\n        {Cn} = {An} * {Bn}     Cn = AnBn",
			"rawText": "The product of two discrete-time sequences is obtained by multiplying the \ncorresponding elements of the sequence.\n\n        {Cn} = {An} * {Bn}     Cn = AnBn",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The product of two discrete-time sequences is obtained by multiplying the \ncorresponding elements of the sequence.\n\n        {Cn} = {An} * {Bn}     Cn = AnBn",
			"lineHeight": 1.25,
			"baseline": 91
		},
		{
			"type": "arrow",
			"version": 88,
			"versionNonce": 711741168,
			"isDeleted": false,
			"id": "tdjR-GmEHApBo4RHvScMp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1494.0416758052943,
			"y": -340.83588563077757,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 33.126251220703125,
			"height": 1.57745361328125,
			"seed": 409751841,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					33.126251220703125,
					1.57745361328125
				]
			]
		},
		{
			"type": "text",
			"version": 231,
			"versionNonce": 1014519824,
			"isDeleted": false,
			"id": "uIUbUbgt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1775.2897438740924,
			"y": -240.0444959376906,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 796.1591796875,
			"height": 100,
			"seed": 795468385,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The multiplication of a sequence by a constant K is obtained by multiplying each\nelement of the sequence by that constant.\n        \n        {Cn} = K{An}      Cn = KAn",
			"rawText": "The multiplication of a sequence by a constant K is obtained by multiplying each\nelement of the sequence by that constant.\n        \n        {Cn} = K{An}      Cn = KAn",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The multiplication of a sequence by a constant K is obtained by multiplying each\nelement of the sequence by that constant.\n        \n        {Cn} = K{An}      Cn = KAn",
			"lineHeight": 1.25,
			"baseline": 91
		},
		{
			"type": "arrow",
			"version": 100,
			"versionNonce": 669315312,
			"isDeleted": false,
			"id": "N0DGqHfAJ_Vf4YrlVMAT1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1550.5473521735107,
			"y": -154.6321384256347,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 33.126251220703125,
			"height": 1.57745361328125,
			"seed": 963033263,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					33.126251220703125,
					1.57745361328125
				]
			]
		},
		{
			"type": "rectangle",
			"version": 123,
			"versionNonce": 1775425040,
			"isDeleted": false,
			"id": "U0JdJMAM-3DqmTHmT2dq-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1845.038919899483,
			"y": -665.8778394435499,
			"strokeColor": "#c2255c",
			"backgroundColor": "transparent",
			"width": 878.6346130371091,
			"height": 545.7945556640624,
			"seed": 502077007,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "LZqw4tTnv_rc1u0dDHAnB",
					"type": "arrow"
				},
				{
					"id": "B6nNheSaMhPzhQHMlz_3m",
					"type": "arrow"
				}
			],
			"updated": 1703931097079,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 182,
			"versionNonce": 1912165104,
			"isDeleted": false,
			"id": "LZqw4tTnv_rc1u0dDHAnB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -798.8739418721393,
			"y": -88.29367196308124,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 146.70201110839844,
			"height": 302.86868286132807,
			"seed": 993121217,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "U0JdJMAM-3DqmTHmT2dq-",
				"focus": -0.26659391977585617,
				"gap": 20.82835388183605
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-111.99832153320312,
					-89.91412353515625
				],
				[
					-113.57574462890625,
					-216.1094360351562
				],
				[
					-110.42086791992188,
					-294.98147583007807
				],
				[
					-146.70201110839844,
					-302.86868286132807
				]
			]
		},
		{
			"type": "text",
			"version": 284,
			"versionNonce": 1127060496,
			"isDeleted": false,
			"id": "8wr318yy",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1691.7158030734076,
			"y": -1286.8782565171173,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 232.67979431152344,
			"height": 25,
			"seed": 739406095,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "ELEMENTARY SIGNALS",
			"rawText": "ELEMENTARY SIGNALS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "ELEMENTARY SIGNALS",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 1036,
			"versionNonce": 2133947632,
			"isDeleted": false,
			"id": "hbcT5xX9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1959.2443766322062,
			"y": -1230.4259550901797,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 890.299072265625,
			"height": 275,
			"seed": 1603637057,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "There are several elementary signals which play vital role in the study of signals\nand systems. These elementary signals serve as basic building blocks for the construction\nof more complex signals. Infact, these elementary signals may be used to model a large\nnumber of physical signals which occur in nature. These elementary signals are also called\nSTANDARD SIGNALS.\n    The standard signals are:\n\n1. Unit step function                2. Unit ramp function\n3. Unit parabolic function           4. Unit impulse function\n5 Sinusoidal function                6. Real exponential function\n7. Complex exponential function, e.t.c",
			"rawText": "There are several elementary signals which play vital role in the study of signals\nand systems. These elementary signals serve as basic building blocks for the construction\nof more complex signals. Infact, these elementary signals may be used to model a large\nnumber of physical signals which occur in nature. These elementary signals are also called\nSTANDARD SIGNALS.\n    The standard signals are:\n\n1. Unit step function                2. Unit ramp function\n3. Unit parabolic function           4. Unit impulse function\n5 Sinusoidal function                6. Real exponential function\n7. Complex exponential function, e.t.c",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "There are several elementary signals which play vital role in the study of signals\nand systems. These elementary signals serve as basic building blocks for the construction\nof more complex signals. Infact, these elementary signals may be used to model a large\nnumber of physical signals which occur in nature. These elementary signals are also called\nSTANDARD SIGNALS.\n    The standard signals are:\n\n1. Unit step function                2. Unit ramp function\n3. Unit parabolic function           4. Unit impulse function\n5 Sinusoidal function                6. Real exponential function\n7. Complex exponential function, e.t.c",
			"lineHeight": 1.25,
			"baseline": 265
		},
		{
			"type": "rectangle",
			"version": 261,
			"versionNonce": 1530068208,
			"isDeleted": false,
			"id": "DOfM1hI5A0MC6AWsUQ4Zb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2120.2599600238736,
			"y": -1351.9598573000003,
			"strokeColor": "#099268",
			"backgroundColor": "transparent",
			"width": 1209.3714735243057,
			"height": 438.1781684027778,
			"seed": 1626770799,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "w2AKJz5ByXIbaBESKzCIJ",
					"type": "arrow"
				},
				{
					"id": "_L-zlhOGSIF-EKKSaDcVE",
					"type": "arrow"
				},
				{
					"id": "dknBSVLuqmd_00LEBU8yf",
					"type": "arrow"
				},
				{
					"id": "gXcmVqd8vDGnjJ7uiei3B",
					"type": "arrow"
				},
				{
					"id": "LyBrbQDYJDeeONRPjzse2",
					"type": "arrow"
				},
				{
					"id": "0z4j4BTpfLEGj5M3euFAl",
					"type": "arrow"
				},
				{
					"id": "4lXWzC-yfpfZeQr_QwGYN",
					"type": "arrow"
				}
			],
			"updated": 1703932062023,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 105,
			"versionNonce": 890590960,
			"isDeleted": false,
			"id": "BDeA9yD-yELx_oHgi_2zS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -905.4038673589462,
			"y": -692.7829502904544,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 613.4493001302085,
			"height": 182.28203667534717,
			"seed": 596544961,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-161.24945746527783,
					-70.10837131076391
				],
				[
					-525.813666449653,
					-80.62472873263891
				],
				[
					-613.4493001302085,
					-182.28203667534717
				]
			]
		},
		{
			"type": "text",
			"version": 145,
			"versionNonce": 1388564496,
			"isDeleted": false,
			"id": "u6eWS3zS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3019.4250432578183,
			"y": -870.3625318025365,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 525.6094970703125,
			"height": 46.033809076434096,
			"seed": 875087969,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"fontSize": 36.82704726114728,
			"fontFamily": 1,
			"text": "THE UNIT STEP FUNCTION",
			"rawText": "THE UNIT STEP FUNCTION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "THE UNIT STEP FUNCTION",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "text",
			"version": 954,
			"versionNonce": 137165040,
			"isDeleted": false,
			"id": "iH84Z19X",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3155.1898737574516,
			"y": -772.6498738414657,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 850.8192138671875,
			"height": 325,
			"seed": 1783515521,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The unit step function exists only for positive time and is zero for negative time.\nIt is equivalent to applying a signal whose amplitude suddenly changes and remains\nconstant forever after application.\n\nIf a step function has unity magnitude, then it is called a unit step function.\nThe usefulness of the unit-step function lies in the fact that if we want a signal\nto start at t = 0, so that it may have a value of zero for t < 0, we only need to\nmultiply the given signal with the unit step function u(t). A unit step function is \nuseful as a test signal because the response of the system for a unit step reveals\na great deal about how quickly the system responds to a sudden change in the input\nsignal.\n\nThe continuous-time unit step function u(t) is defined as:",
			"rawText": "The unit step function exists only for positive time and is zero for negative time.\nIt is equivalent to applying a signal whose amplitude suddenly changes and remains\nconstant forever after application.\n\nIf a step function has unity magnitude, then it is called a unit step function.\nThe usefulness of the unit-step function lies in the fact that if we want a signal\nto start at t = 0, so that it may have a value of zero for t < 0, we only need to\nmultiply the given signal with the unit step function u(t). A unit step function is \nuseful as a test signal because the response of the system for a unit step reveals\na great deal about how quickly the system responds to a sudden change in the input\nsignal.\n\nThe continuous-time unit step function u(t) is defined as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The unit step function exists only for positive time and is zero for negative time.\nIt is equivalent to applying a signal whose amplitude suddenly changes and remains\nconstant forever after application.\n\nIf a step function has unity magnitude, then it is called a unit step function.\nThe usefulness of the unit-step function lies in the fact that if we want a signal\nto start at t = 0, so that it may have a value of zero for t < 0, we only need to\nmultiply the given signal with the unit step function u(t). A unit step function is \nuseful as a test signal because the response of the system for a unit step reveals\na great deal about how quickly the system responds to a sudden change in the input\nsignal.\n\nThe continuous-time unit step function u(t) is defined as:",
			"lineHeight": 1.25,
			"baseline": 315
		},
		{
			"type": "text",
			"version": 28,
			"versionNonce": 401559056,
			"isDeleted": false,
			"id": "gvapIfMt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2937.5860800834066,
			"y": -350.3340643796603,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.05990600585938,
			"height": 25,
			"seed": 60798529,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "PBUK1OOk9_AvOijlWNxP5",
					"type": "arrow"
				},
				{
					"id": "UZhTh-Xw9GFA1GqueRrQy",
					"type": "arrow"
				}
			],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "u(t) = ",
			"rawText": "u(t) = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "u(t) = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 64,
			"versionNonce": 469785328,
			"isDeleted": false,
			"id": "XzXaeFdf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2799.041361658927,
			"y": -383.6205362763617,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 141.91983032226562,
			"height": 100,
			"seed": 118932367,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "PBUK1OOk9_AvOijlWNxP5",
					"type": "arrow"
				},
				{
					"id": "UZhTh-Xw9GFA1GqueRrQy",
					"type": "arrow"
				}
			],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1   for t >= 0\n\n\n0  for t < 0",
			"rawText": "1   for t >= 0\n\n\n0  for t < 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1   for t >= 0\n\n\n0  for t < 0",
			"lineHeight": 1.25,
			"baseline": 91
		},
		{
			"type": "arrow",
			"version": 45,
			"versionNonce": 1727728656,
			"isDeleted": false,
			"id": "PBUK1OOk9_AvOijlWNxP5",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2810.4574111923475,
			"y": -376.32364771299365,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 56.08679877387158,
			"height": 33.30152723524304,
			"seed": 428427663,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "XzXaeFdf",
				"focus": 0.9943710260168899,
				"gap": 11.416049533420392
			},
			"endBinding": {
				"elementId": "gvapIfMt",
				"focus": 0.486320899647979,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-56.08679877387158,
					33.30152723524304
				]
			]
		},
		{
			"type": "arrow",
			"version": 49,
			"versionNonce": 1662483696,
			"isDeleted": false,
			"id": "UZhTh-Xw9GFA1GqueRrQy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2813.9628297578856,
			"y": -302.70975611143115,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 49.07596164279539,
			"height": 33.30152723524304,
			"seed": 462224193,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "XzXaeFdf",
				"focus": -0.9086722300348763,
				"gap": 14.921468098958485
			},
			"endBinding": {
				"elementId": "gvapIfMt",
				"focus": -0.6890632500898307,
				"gap": 4.487382676866218
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-49.07596164279539,
					-33.30152723524304
				]
			]
		},
		{
			"type": "text",
			"version": 79,
			"versionNonce": 434047504,
			"isDeleted": false,
			"id": "jP7wnNQI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3102.0305245278514,
			"y": -209.2229532685493,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 532.8994140625,
			"height": 25,
			"seed": 835915425,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The shifted unit step function u(t - a) is defined as:",
			"rawText": "The shifted unit step function u(t - a) is defined as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The shifted unit step function u(t - a) is defined as:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 30,
			"versionNonce": 1056595696,
			"isDeleted": false,
			"id": "FpBWxSh3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2930.9194134167406,
			"y": -109.2229532685493,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 111.61984252929688,
			"height": 25,
			"seed": 1875476943,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "u(t - a) = ",
			"rawText": "u(t - a) = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "u(t - a) = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 60,
			"versionNonce": 194201616,
			"isDeleted": false,
			"id": "d0wncx0V",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2769.2134807995535,
			"y": -147.6423461721954,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 141.49981689453125,
			"height": 100,
			"seed": 196061409,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "t-gooOjnjcvq-F1QPWEzj",
					"type": "arrow"
				},
				{
					"id": "4T5utkmgzRWRvM4dZx-4i",
					"type": "arrow"
				}
			],
			"updated": 1703931097079,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1   for t >= a\n\n\n0   for t < a",
			"rawText": "1   for t >= a\n\n\n0   for t < a",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1   for t >= a\n\n\n0   for t < a",
			"lineHeight": 1.25,
			"baseline": 91
		},
		{
			"type": "arrow",
			"version": 39,
			"versionNonce": 540082416,
			"isDeleted": false,
			"id": "t-gooOjnjcvq-F1QPWEzj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2788.1734756454734,
			"y": -131.36481253504235,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 33.3015272352427,
			"height": 28.043416341145758,
			"seed": 1285587681,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "d0wncx0V",
				"focus": 0.9971599651346177,
				"gap": 18.959994845919937
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-33.3015272352427,
					28.043416341145758
				]
			]
		},
		{
			"type": "arrow",
			"version": 35,
			"versionNonce": 2014299664,
			"isDeleted": false,
			"id": "4T5utkmgzRWRvM4dZx-4i",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2784.668057079935,
			"y": -70.01986895865355,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 36.80694580078125,
			"height": 24.5379638671875,
			"seed": 1340228641,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "d0wncx0V",
				"focus": -0.87573434458891,
				"gap": 15.454576280381389
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-36.80694580078125,
					-24.5379638671875
				]
			]
		},
		{
			"type": "text",
			"version": 219,
			"versionNonce": 641950448,
			"isDeleted": false,
			"id": "4JZBI8uw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3144.486579215351,
			"y": -11.273056350147272,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 854.5791625976562,
			"height": 50,
			"seed": 424121697,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "It is zero if the argument (t - a) < 0 and equals to 1 if the argument (t - a) >= 0.\nThe graphical representation of u(t) and u(t - a) are shown below:",
			"rawText": "It is zero if the argument (t - a) < 0 and equals to 1 if the argument (t - a) >= 0.\nThe graphical representation of u(t) and u(t - a) are shown below:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "It is zero if the argument (t - a) < 0 and equals to 1 if the argument (t - a) >= 0.\nThe graphical representation of u(t) and u(t - a) are shown below:",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "arrow",
			"version": 138,
			"versionNonce": 1548518416,
			"isDeleted": false,
			"id": "TyLSopxh3Yo4oa6OviWEz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3245.2696341866376,
			"y": 393.06046582700185,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 287.444864908854,
			"seed": 1143908559,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "JJZthLdp",
				"focus": 1.8324293249749335,
				"gap": 15.699598524306566
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-287.444864908854
				]
			]
		},
		{
			"type": "arrow",
			"version": 221,
			"versionNonce": 1069122800,
			"isDeleted": false,
			"id": "kAXOgJjxVW1EEYq7a449o",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3293.064264449225,
			"y": 360.8138973591197,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 382.8999401393885,
			"height": 0,
			"seed": 1275997295,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "J2wvphY7",
				"focus": 2.185340711805552,
				"gap": 14.8167588975694
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					382.8999401393885,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 134,
			"versionNonce": 1447133712,
			"isDeleted": false,
			"id": "rjj18XRBiikFa4fP_PHcf",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3242.2356104778714,
			"y": 250.39302604835592,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 210.32548692491355,
			"height": 0,
			"seed": 273499201,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					210.32548692491355,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 174,
			"versionNonce": 1243309808,
			"isDeleted": false,
			"id": "xa7S3bhyN59lo6dyw6O-i",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2580.936919345788,
			"y": 391.2168870070553,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 287.444864908854,
			"seed": 1250092161,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-287.444864908854
				]
			]
		},
		{
			"type": "arrow",
			"version": 206,
			"versionNonce": 82231312,
			"isDeleted": false,
			"id": "ftiA4K0ZiBuXsEAcYH-pV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2628.7315496083756,
			"y": 358.97031853917315,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 429.51800620866425,
			"height": 0,
			"seed": 1016376417,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "m22jDC3K",
				"focus": 1.9266500509215803,
				"gap": 11.583125636519753
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					429.51800620866425,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 211,
			"versionNonce": 837880048,
			"isDeleted": false,
			"id": "p7Z_sBkD07Wuy13Zz49ez",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2495.5254406674044,
			"y": 245.0440625712913,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 210.32548692491355,
			"height": 0,
			"seed": 1021474881,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					210.32548692491355,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 82,
			"versionNonce": 1748254224,
			"isDeleted": false,
			"id": "1wp-RfYnf_7RZ9soSVazy",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2491.9164513858223,
			"y": 244.57884836406117,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 113.92632378472217,
			"seed": 1762485295,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					113.92632378472217
				]
			]
		},
		{
			"type": "text",
			"version": 45,
			"versionNonce": 314731248,
			"isDeleted": false,
			"id": "iV8VaLRr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2608.08547807853,
			"y": 234.0588966496514,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 966323151,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 74,
			"versionNonce": 1092746256,
			"isDeleted": false,
			"id": "CIsbPdVo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3275.297693404301,
			"y": 232.54804178186282,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 226835375,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 89,
			"versionNonce": 1461161200,
			"isDeleted": false,
			"id": "J2wvphY7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2928.161479889761,
			"y": 375.6306562566891,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 686018625,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "kAXOgJjxVW1EEYq7a449o",
					"type": "arrow"
				}
			],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 49,
			"versionNonce": 1906833936,
			"isDeleted": false,
			"id": "m22jDC3K",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2194.282716576795,
			"y": 370.5534441756929,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 553917185,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "ftiA4K0ZiBuXsEAcYH-pV",
					"type": "arrow"
				}
			],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 76,
			"versionNonce": 1484287728,
			"isDeleted": false,
			"id": "JJZthLdp",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3229.570035662331,
			"y": 104.51954514557815,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.71995544433594,
			"height": 25,
			"seed": 1953331457,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "TyLSopxh3Yo4oa6OviWEz",
					"type": "arrow"
				}
			],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "u(t)",
			"rawText": "u(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "u(t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 49,
			"versionNonce": 1555970064,
			"isDeleted": false,
			"id": "4QvPOnHG",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2552.2325456783583,
			"y": 95.51417822517226,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 79.27989196777344,
			"height": 25,
			"seed": 837766063,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "u(t - a)",
			"rawText": "u(t - a)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "u(t - a)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 48,
			"versionNonce": 2137854192,
			"isDeleted": false,
			"id": "y6V77l5d",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3180.047879313736,
			"y": 408.9163489118132,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 175.89979553222656,
			"height": 25,
			"seed": 455222273,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "unit step function",
			"rawText": "unit step function",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "unit step function",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 51,
			"versionNonce": 1180481040,
			"isDeleted": false,
			"id": "qcp7lsD2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2507.1988990703467,
			"y": 419.51223983729415,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 262.73968505859375,
			"height": 25,
			"seed": 1039813953,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097080,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Delayed unit step function",
			"rawText": "Delayed unit step function",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Delayed unit step function",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "rectangle",
			"version": 271,
			"versionNonce": 1669165808,
			"isDeleted": false,
			"id": "GR0ouguJ0H8RzGgqmxOCR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3323.453793620377,
			"y": -942.083054821661,
			"strokeColor": "#ff0000",
			"backgroundColor": "transparent",
			"width": 1172.1600224421572,
			"height": 2200.044668344351,
			"seed": 1355379791,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "w2AKJz5ByXIbaBESKzCIJ",
					"type": "arrow"
				}
			],
			"updated": 1703931097081,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 67,
			"versionNonce": 863728656,
			"isDeleted": false,
			"id": "5jbT7yPFWTvoCw12DhrQh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3126.621365641864,
			"y": -814.8883010280921,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 732.9033484825723,
			"height": 0,
			"seed": 1423293359,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					732.9033484825723,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 59,
			"versionNonce": 1798411504,
			"isDeleted": false,
			"id": "U0IkJuu7glJYmIjQo975N",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -788.6182481538838,
			"y": 390.6362257146949,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 400.4272930438701,
			"height": 0,
			"seed": 1950097903,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					400.4272930438701,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 59,
			"versionNonce": 1242722832,
			"isDeleted": false,
			"id": "DCeVVRi3ZukUBT0DolLOj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1253.5340665883787,
			"y": 776.5464946449833,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 417.41511418269226,
			"height": 0,
			"seed": 944625455,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					417.41511418269226,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 56,
			"versionNonce": 1813083888,
			"isDeleted": false,
			"id": "ZcDZ6cNocD8Kr84Atbbhr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -361.03214163345103,
			"y": 927.0101740320026,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 439.2566387469951,
			"height": 0,
			"seed": 2095029839,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					439.2566387469951,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 57,
			"versionNonce": 823767056,
			"isDeleted": false,
			"id": "L57xbodlG-9gCBVM-b4-E",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1667.7039884633775,
			"y": 79.78408103320464,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 364.0248460036057,
			"height": 0,
			"seed": 487186799,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					364.0248460036057,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 57,
			"versionNonce": 1252333808,
			"isDeleted": false,
			"id": "2Preg_gifwXN4Pu1tiPhc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1726.1421927151785,
			"y": -600.0657255322986,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 609.1348501352163,
			"height": 0,
			"seed": 1077295809,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					609.1348501352163,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 50,
			"versionNonce": 1888038416,
			"isDeleted": false,
			"id": "HyelPkQx-Pqg1vvsUrxME",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1758.6260418738336,
			"y": -1254.5852849523685,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 373.732205904447,
			"height": 0,
			"seed": 1717324257,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					373.732205904447,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 124,
			"versionNonce": 443841264,
			"isDeleted": false,
			"id": "P2hQUn6d",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3054.923130203447,
			"y": 543.2708416861885,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 560.3994750976562,
			"height": 25,
			"seed": 662378017,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The discrete-time unit step sequence u[n] is defined as:",
			"rawText": "The discrete-time unit step sequence u[n] is defined as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The discrete-time unit step sequence u[n] is defined as:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 75,
			"versionNonce": 1364782096,
			"isDeleted": false,
			"id": "SPB1Pjs4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2791.923130203447,
			"y": 617.2708416861886,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 72.85990905761719,
			"height": 25,
			"seed": 724154895,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "u[n] = ",
			"rawText": "u[n] = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "u[n] = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 96,
			"versionNonce": 1040686320,
			"isDeleted": false,
			"id": "uPZgvehY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2663.923130203447,
			"y": 600.2708416861886,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139.9598388671875,
			"height": 75,
			"seed": 356680865,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "J5i_Wm0A7Lov7DfgAI8Az",
					"type": "arrow"
				},
				{
					"id": "Wslo9qQ153AhGN6pH9IF2",
					"type": "arrow"
				}
			],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1   for n >= 0\n\n0  for n < 0",
			"rawText": "1   for n >= 0\n\n0  for n < 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1   for n >= 0\n\n0  for n < 0",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "arrow",
			"version": 166,
			"versionNonce": 1031858704,
			"isDeleted": false,
			"id": "J5i_Wm0A7Lov7DfgAI8Az",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2679.0444070589156,
			"y": 611.4559613150949,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.900634765625,
			"height": 17.35186767578125,
			"seed": 2120002255,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "uPZgvehY",
				"focus": 0.90663654315047,
				"gap": 15.12127685546875
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-48.900634765625,
					17.35186767578125
				]
			]
		},
		{
			"type": "arrow",
			"version": 147,
			"versionNonce": 115769072,
			"isDeleted": false,
			"id": "Wslo9qQ153AhGN6pH9IF2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2672.7345926057906,
			"y": 660.3566571158761,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 47.3232421875,
			"height": 22.08416748046875,
			"seed": 1442870625,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "uPZgvehY",
				"focus": -0.8460292158987552,
				"gap": 8.81146240234375
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-47.3232421875,
					-22.08416748046875
				]
			]
		},
		{
			"type": "text",
			"version": 164,
			"versionNonce": 536422416,
			"isDeleted": false,
			"id": "T7SWZYOh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3157.5106851350874,
			"y": 729.2994061393138,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 835.2191772460938,
			"height": 25,
			"seed": 1602263329,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The shifted version for the discrete-time unit step function u[n - k] is defined as: ",
			"rawText": "The shifted version for the discrete-time unit step function u[n - k] is defined as: ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The shifted version for the discrete-time unit step function u[n - k] is defined as: ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 97,
			"versionNonce": 1436098800,
			"isDeleted": false,
			"id": "qJd8bJXX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2944.280124832353,
			"y": 800.3903485221259,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 110.81985473632812,
			"height": 25,
			"seed": 1099935407,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "vHrN-3HasDz_p3Mocdtxk",
					"type": "arrow"
				}
			],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "u[n - k] = ",
			"rawText": "u[n - k] = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "u[n - k] = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 103,
			"versionNonce": 1153017360,
			"isDeleted": false,
			"id": "aiAI1mUm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2776.844120193681,
			"y": 777.0805951041572,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 135.93983459472656,
			"height": 75,
			"seed": 2359503,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "1yFvleZSmn2NQGxPQPfK_",
					"type": "arrow"
				},
				{
					"id": "vHrN-3HasDz_p3Mocdtxk",
					"type": "arrow"
				}
			],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1   for n >= k\n\n0  for n < k",
			"rawText": "1   for n >= k\n\n0  for n < k",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1   for n >= k\n\n0  for n < k",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "arrow",
			"version": 178,
			"versionNonce": 967279344,
			"isDeleted": false,
			"id": "1yFvleZSmn2NQGxPQPfK_",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2791.96539704915,
			"y": 788.2194398228565,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.900634765625,
			"height": 17.398142585988126,
			"seed": 682168047,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097081,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "aiAI1mUm",
				"focus": 0.90663654315047,
				"gap": 15.12127685546875
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-48.900634765625,
					17.398142585988126
				]
			]
		},
		{
			"type": "arrow",
			"version": 165,
			"versionNonce": 951739408,
			"isDeleted": false,
			"id": "vHrN-3HasDz_p3Mocdtxk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2785.655582596025,
			"y": 837.2793398431061,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 46.8046875,
			"height": 21.919109456618344,
			"seed": 900159759,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "aiAI1mUm",
				"focus": -0.8460292158987552,
				"gap": 8.81146240234375
			},
			"endBinding": {
				"elementId": "qJd8bJXX",
				"focus": -0.6228364786753524,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-46.8046875,
					-21.919109456618344
				]
			]
		},
		{
			"type": "arrow",
			"version": 152,
			"versionNonce": 295281904,
			"isDeleted": false,
			"id": "R2DfRWz-E_SHoxcSzhTpz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3287.6403238069624,
			"y": 1088.0299969596258,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 527.1195068359375,
			"height": 0,
			"seed": 292608161,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					527.1195068359375,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 162,
			"versionNonce": 703816208,
			"isDeleted": false,
			"id": "1cCyFMVOoEwQesx5NpFfu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2639.805374737763,
			"y": 1098.0401073830467,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 459.03530883789017,
			"height": 0,
			"seed": 1034922735,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "2lXewbsC",
				"focus": -1.3260661661263475,
				"gap": 4.075827076579344
			},
			"endBinding": {
				"elementId": "jdSZpUS5",
				"focus": 1.7012858926888659,
				"gap": 8.766073658610821
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					459.03530883789017,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 81,
			"versionNonce": 720865008,
			"isDeleted": false,
			"id": "7LhvOVHrHNHaHVcDTT12j",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2625.6739846956343,
			"y": 1124.1427899283758,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 244.50335693359352,
			"seed": 651628065,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "2lXewbsC",
				"focus": 1.4371578276177541,
				"gap": 3.0076446533203125
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-244.50335693359352
				]
			]
		},
		{
			"type": "ellipse",
			"version": 62,
			"versionNonce": 1197252624,
			"isDeleted": false,
			"id": "tZ-EoPTtBSotoPif65FJQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3259.3776895296187,
			"y": 1080.710172740876,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 1353443937,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 68,
			"versionNonce": 1648961776,
			"isDeleted": false,
			"id": "pAEroceYj4SG1Oo1VIgma",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3199.540119339189,
			"y": 1079.3692608756417,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 1445682671,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 87,
			"versionNonce": 552476176,
			"isDeleted": false,
			"id": "iKii42V6nr38t7wkPRdCo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3134.343097854814,
			"y": 1079.2144757193917,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 1240371265,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 79,
			"versionNonce": 1125550832,
			"isDeleted": false,
			"id": "G0upXzcv_B7J4kvu7-V0i",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3086.6949655305953,
			"y": 1000.3271466178292,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 1762117775,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 66,
			"versionNonce": 127917072,
			"isDeleted": false,
			"id": "zoq_ZM1olzDVGepwINtQn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3035.5400583040328,
			"y": 998.6369610709542,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 1076316065,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 96,
			"versionNonce": 669494512,
			"isDeleted": false,
			"id": "3AZRSA2PFxmnYIZn6w2J3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2983.455890823564,
			"y": 998.6369610709542,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 1940754223,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 91,
			"versionNonce": 1835653648,
			"isDeleted": false,
			"id": "FamfoJsA7nb1sySEFHtug",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2924.3717843782515,
			"y": 1000.5241681022042,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 52519681,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 21,
			"versionNonce": 1514442480,
			"isDeleted": false,
			"id": "Dd03hIlw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2832.2867471468066,
			"y": 1102.7354412955635,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 9.339996337890625,
			"height": 25,
			"seed": 1111939009,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "n",
			"rawText": "n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "n",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 44,
			"versionNonce": 1162090512,
			"isDeleted": false,
			"id": "nalINdSt9xI4fo9XWwb_I",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3077.9719278108687,
			"y": 1019.1899701041574,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 64.67504882812489,
			"seed": 161603919,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					64.67504882812489
				]
			]
		},
		{
			"type": "line",
			"version": 46,
			"versionNonce": 850735344,
			"isDeleted": false,
			"id": "XjYSb6VJyozZIcnI-x-8I",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3028.2640220124636,
			"y": 1016.2825344602237,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 64.67504882812489,
			"seed": 718721775,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					64.67504882812489
				]
			]
		},
		{
			"type": "line",
			"version": 53,
			"versionNonce": 1663473168,
			"isDeleted": false,
			"id": "_1mllvzBAMQ5XQnxykQD_",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2974.1091758210573,
			"y": 1016.0148342649112,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 64.67504882812489,
			"seed": 352725825,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					64.67504882812489
				]
			]
		},
		{
			"type": "line",
			"version": 65,
			"versionNonce": 952210160,
			"isDeleted": false,
			"id": "o2rljzXhx9-JeUgc7hqFY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2915.6866294343386,
			"y": 1016.1697414914737,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 64.67504882812489,
			"seed": 988421519,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					64.67504882812489
				]
			]
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 1544115216,
			"isDeleted": false,
			"id": "3Fj6HO2F",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3110.286747146806,
			"y": 1004.7354412955636,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 420593345,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 23,
			"versionNonce": 1123136752,
			"isDeleted": false,
			"id": "fVF8gAg7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3038.286747146806,
			"y": 961.7354412955636,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 40.51995849609375,
			"height": 25,
			"seed": 1615882831,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "u[n]",
			"rawText": "u[n]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "u[n]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 31,
			"versionNonce": 1709462032,
			"isDeleted": false,
			"id": "RPydHwim",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3084.173954178056,
			"y": 1097.8482342643135,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 385140033,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 22,
			"versionNonce": 382572272,
			"isDeleted": false,
			"id": "E2z3I17l",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3022.4416238557906,
			"y": 1102.7354412955635,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 719035585,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 28,
			"versionNonce": 934252560,
			"isDeleted": false,
			"id": "OhLKPYbL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2979.7514077913374,
			"y": 1102.580534069001,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 14.239990234375,
			"height": 25,
			"seed": 2128262209,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097082,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 28,
			"versionNonce": 148715760,
			"isDeleted": false,
			"id": "tLJMNvsW",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2919.709293533525,
			"y": 1099.115934459626,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 13.619979858398438,
			"height": 25,
			"seed": 617745345,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "3",
			"rawText": "3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 34,
			"versionNonce": 1768099344,
			"isDeleted": false,
			"id": "QNQdov2X",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3263.5123483430953,
			"y": 1108.8482342643135,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 21.8399658203125,
			"height": 25,
			"seed": 1230059201,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-3",
			"rawText": "-3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-3",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 30,
			"versionNonce": 480811760,
			"isDeleted": false,
			"id": "fDWGeMbb",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3208.483707596025,
			"y": 1109.8482342643135,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 22.459976196289062,
			"height": 25,
			"seed": 479321633,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-2",
			"rawText": "-2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 38,
			"versionNonce": 1408683024,
			"isDeleted": false,
			"id": "3k7NY22x",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3131.173954178056,
			"y": 1103.6933880729073,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 13.639984130859375,
			"height": 25,
			"seed": 1771956609,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-1",
			"rawText": "-1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 27,
			"versionNonce": 616021232,
			"isDeleted": false,
			"id": "4VpA6ABI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2599.286747146806,
			"y": 871.7354412955636,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 78.47990417480469,
			"height": 25,
			"seed": 294143777,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "u[n - k]",
			"rawText": "u[n - k]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "u[n - k]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 31,
			"versionNonce": 1902299664,
			"isDeleted": false,
			"id": "jdSZpUS5",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2184.4837075960254,
			"y": 1106.8061810416575,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 9.339996337890625,
			"height": 25,
			"seed": 900029135,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "1cCyFMVOoEwQesx5NpFfu",
					"type": "arrow"
				}
			],
			"updated": 1703931097083,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "n",
			"rawText": "n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "n",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 30,
			"versionNonce": 1653776112,
			"isDeleted": false,
			"id": "2lXewbsC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2642.4416238557906,
			"y": 1102.115934459626,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 632432481,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "1cCyFMVOoEwQesx5NpFfu",
					"type": "arrow"
				},
				{
					"id": "7LhvOVHrHNHaHVcDTT12j",
					"type": "arrow"
				}
			],
			"updated": 1703931097083,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "ellipse",
			"version": 49,
			"versionNonce": 1017055248,
			"isDeleted": false,
			"id": "MUryEiZAxh8q_us511SdB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2874.096531082353,
			"y": 1039.3700238150948,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 11.042083740234375,
			"height": 9.46466064453125,
			"seed": 971600193,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 52,
			"versionNonce": 650199280,
			"isDeleted": false,
			"id": "J3NPNrU3uBetfbMZCDoge",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2846.8077890169234,
			"y": 1038.5805645865792,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 11.042083740234375,
			"height": 9.46466064453125,
			"seed": 1666040993,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 51,
			"versionNonce": 295929360,
			"isDeleted": false,
			"id": "QXxFC1dcN-v7LQBQ-YRUj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2821.8077890169234,
			"y": 1037.003110973298,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 11.042083740234375,
			"height": 9.46466064453125,
			"seed": 1096852015,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 73,
			"versionNonce": 1892393712,
			"isDeleted": false,
			"id": "JuGp9fJ8RVvvv4E449MKW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2580.1596566927046,
			"y": 1089.059507457673,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 1083523471,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 69,
			"versionNonce": 224936976,
			"isDeleted": false,
			"id": "VFIjuItuDk0LbmtJdgk4k",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2525.4272653352828,
			"y": 1090.6369610709542,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 143662753,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 67,
			"versionNonce": 255444208,
			"isDeleted": false,
			"id": "tzrnDuweI2Bed0q2Xkcel",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2469.9626657259078,
			"y": 1088.7918072623604,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 649029679,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 66,
			"versionNonce": 1843741200,
			"isDeleted": false,
			"id": "upFbjH6shF7IwQ5-scz67",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2411.9626657259078,
			"y": 1011.2144146842354,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 472111617,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 73,
			"versionNonce": 1066641136,
			"isDeleted": false,
			"id": "CStaRiWQ0AHl5DpdbK3UR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2356.3852121126265,
			"y": 1009.9467144889229,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 444426959,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 86,
			"versionNonce": 1913815056,
			"isDeleted": false,
			"id": "ixIO_FMvl6S8NIsBjY3u2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2300.7656442415328,
			"y": 1011.8339215201729,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 790002017,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 97,
			"versionNonce": 1314998512,
			"isDeleted": false,
			"id": "m23hkA0fpICCtwAUfZBBG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2244.2589914095015,
			"y": 1009.5662213248604,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffc9c9",
			"width": 17.351837158203125,
			"height": 17.35186767578125,
			"seed": 1142278511,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 25,
			"versionNonce": 971505168,
			"isDeleted": false,
			"id": "32CVoy43",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2440.019046951494,
			"y": 1010.4256268424388,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 1974923425,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 83,
			"versionNonce": 925543152,
			"isDeleted": false,
			"id": "Fwe2eRg4N9EguZR3Avnr5",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2402.4478723221405,
			"y": 1028.6758036752638,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 64.67504882812489,
			"seed": 381123023,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					64.67504882812489
				]
			]
		},
		{
			"type": "line",
			"version": 69,
			"versionNonce": 643677200,
			"isDeleted": false,
			"id": "6Mtjw1WzOLf5AS8rHJaof",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2348.7576867752655,
			"y": 1026.2111430307325,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 64.67504882812489,
			"seed": 1948555873,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					64.67504882812489
				]
			]
		},
		{
			"type": "line",
			"version": 67,
			"versionNonce": 1148701936,
			"isDeleted": false,
			"id": "VaYYSRjuZ9byZ5RL-bOvC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2294.1802331619842,
			"y": 1024.6336894174513,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 64.67504882812489,
			"seed": 1864792175,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097083,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					64.67504882812489
				]
			]
		},
		{
			"type": "line",
			"version": 79,
			"versionNonce": 963361296,
			"isDeleted": false,
			"id": "SYVB8D3-o1hUEheB_iZIr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2233.8704797440155,
			"y": 1029.3659892221388,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 64.67504882812489,
			"seed": 682819009,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					64.67504882812489
				]
			]
		},
		{
			"type": "text",
			"version": 36,
			"versionNonce": 802205424,
			"isDeleted": false,
			"id": "XEze4K9R",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2408.1318399202437,
			"y": 1102.651273815095,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 9.739990234375,
			"height": 25,
			"seed": 800202575,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "k",
			"rawText": "k",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "k",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 41,
			"versionNonce": 1980364816,
			"isDeleted": false,
			"id": "xYZL0sep",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2360.6385537874316,
			"y": 1106.0738202018138,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 27.65997314453125,
			"height": 25,
			"seed": 213346465,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "k+1",
			"rawText": "k+1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "k+1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 1102926064,
			"isDeleted": false,
			"id": "6W8fKXpI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2308.470218826494,
			"y": 1107.6377850455638,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 36.47996520996094,
			"height": 25,
			"seed": 2134333839,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "k+2",
			"rawText": "k+2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "k+2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 57,
			"versionNonce": 1076917776,
			"isDeleted": false,
			"id": "ocInMthw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2247.7513467561816,
			"y": 1108.86343201822,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 35.859954833984375,
			"height": 25,
			"seed": 626356399,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "k+3",
			"rawText": "k+3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "k+3",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 59,
			"versionNonce": 1908781808,
			"isDeleted": false,
			"id": "t1Wzy83t",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3153.286747146806,
			"y": 1162.7354412955635,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 316.05963134765625,
			"height": 25,
			"seed": 1135906767,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Discrete-time unit step function",
			"rawText": "Discrete-time unit step function",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Discrete-time unit step function",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 79,
			"versionNonce": 1020736528,
			"isDeleted": false,
			"id": "FOVrWccv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2591.780033279619,
			"y": 1156.1158734244698,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 394.51959228515625,
			"height": 25,
			"seed": 408476481,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Discrete-time shifted unit step function",
			"rawText": "Discrete-time shifted unit step function",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Discrete-time shifted unit step function",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 208,
			"versionNonce": 108123376,
			"isDeleted": false,
			"id": "dN1IPN4s",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4380.375425779268,
			"y": -868.9636183270618,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 493.0722961425781,
			"height": 43.13815945747102,
			"seed": 1810514721,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"fontSize": 34.510527565976815,
			"fontFamily": 1,
			"text": "THE UNIT RAMP FUNCTION",
			"rawText": "THE UNIT RAMP FUNCTION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "THE UNIT RAMP FUNCTION",
			"lineHeight": 1.25,
			"baseline": 30
		},
		{
			"type": "line",
			"version": 217,
			"versionNonce": 838218256,
			"isDeleted": false,
			"id": "3w4TiGZyQSpPwD1g1n6m9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4344.822752439426,
			"y": -816.9002231447698,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 423.280029296875,
			"height": 0,
			"seed": 515104367,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					423.280029296875,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 254,
			"versionNonce": 894023408,
			"isDeleted": false,
			"id": "lehXIxT9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4526.11787776494,
			"y": -784.8272454429471,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 840.7591552734375,
			"height": 50,
			"seed": 1568538511,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The continuous-time unit ramp function r(t) is a function which starts at t = 0 and\nincreases linearly with time and is defined as:",
			"rawText": "The continuous-time unit ramp function r(t) is a function which starts at t = 0 and\nincreases linearly with time and is defined as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The continuous-time unit ramp function r(t) is a function which starts at t = 0 and\nincreases linearly with time and is defined as:",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "text",
			"version": 148,
			"versionNonce": 1720021008,
			"isDeleted": false,
			"id": "7ApIGltu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4243.390067165354,
			"y": -694.9824899812252,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 67.29991149902344,
			"height": 25,
			"seed": 127046415,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "iNmUNfKep8Pd4-x3mGAKn",
					"type": "arrow"
				}
			],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r(t) = ",
			"rawText": "r(t) = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "r(t) = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 192,
			"versionNonce": 1121278192,
			"isDeleted": false,
			"id": "F0nUyzq1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4137.962495550771,
			"y": -724.4662139395587,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 147.79981994628906,
			"height": 75,
			"seed": 580588577,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "iNmUNfKep8Pd4-x3mGAKn",
					"type": "arrow"
				},
				{
					"id": "Gtz0EY-iUr1tyL6PQwP9p",
					"type": "arrow"
				}
			],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t   for t >= 0\n\n0   for t < 0",
			"rawText": "t   for t >= 0\n\n0   for t < 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t   for t >= 0\n\n0   for t < 0",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "arrow",
			"version": 488,
			"versionNonce": 41741840,
			"isDeleted": false,
			"id": "iNmUNfKep8Pd4-x3mGAKn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4144.0262086245,
			"y": -722.3441061736662,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 38.71898304332399,
			"height": 27.2467041015625,
			"seed": 984899887,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "F0nUyzq1",
				"focus": 1.0239649576364371,
				"gap": 6.063713073729559
			},
			"endBinding": {
				"elementId": "7ApIGltu",
				"focus": 0.17638447881768846,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-38.71898304332399,
					27.2467041015625
				]
			]
		},
		{
			"type": "arrow",
			"version": 321,
			"versionNonce": 580696816,
			"isDeleted": false,
			"id": "Gtz0EY-iUr1tyL6PQwP9p",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4151.196396834728,
			"y": -664.9826004918482,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 30.11474609375,
			"height": 17.208473899147748,
			"seed": 1789562625,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "F0nUyzq1",
				"focus": -0.9002348882802961,
				"gap": 13.233901283957493
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-30.11474609375,
					-17.208473899147748
				]
			]
		},
		{
			"type": "text",
			"version": 384,
			"versionNonce": 1859431440,
			"isDeleted": false,
			"id": "whq8eA9l",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4491.380001682029,
			"y": -622.2461170046327,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 836.17919921875,
			"height": 125,
			"seed": 382141505,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "OR\n\nThe unit ramp function has unit slop. It is a signal whose amplitude varies linearly.\nIt can be obtained by INTEGRATING THE UNIT STEP FUNCTION. That means, a\nunit step signal can be obtained by DIFFERENTIATING THE UNIT RAMP SIGNAL.",
			"rawText": "OR\n\nThe unit ramp function has unit slop. It is a signal whose amplitude varies linearly.\nIt can be obtained by INTEGRATING THE UNIT STEP FUNCTION. That means, a\nunit step signal can be obtained by DIFFERENTIATING THE UNIT RAMP SIGNAL.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "OR\n\nThe unit ramp function has unit slop. It is a signal whose amplitude varies linearly.\nIt can be obtained by INTEGRATING THE UNIT STEP FUNCTION. That means, a\nunit step signal can be obtained by DIFFERENTIATING THE UNIT RAMP SIGNAL.",
			"lineHeight": 1.25,
			"baseline": 116
		},
		{
			"type": "text",
			"version": 142,
			"versionNonce": 388488432,
			"isDeleted": false,
			"id": "DpOYDh0F",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4493.351229154507,
			"y": -465.9207663299171,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 20.799972534179688,
			"height": 25,
			"seed": 395583183,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "ie.",
			"rawText": "ie.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "ie.",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 158,
			"versionNonce": 897886736,
			"isDeleted": false,
			"id": "JzJHIz7K",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4295.925456227482,
			"y": -405.8824806409964,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 442.85955810546875,
			"height": 25,
			"seed": 1707815343,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r(t) =    u(t)dt =   dt  = t     for t >= 0",
			"rawText": "r(t) =    u(t)dt =   dt  = t     for t >= 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "r(t) =    u(t)dt =   dt  = t     for t >= 0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 4684,
			"versionNonce": 1375649520,
			"isDeleted": false,
			"id": "Fm8rMkbj2i-vzdM4BzMRY",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4208.041939334898,
			"y": -414.93327543942314,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 1001117345,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 4678,
			"versionNonce": 1636100112,
			"isDeleted": false,
			"id": "VVrw_MKDXTdmaLVMI-uNV",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4091.9249925076165,
			"y": -418.2263926158255,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 1324126721,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097084,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 225,
			"versionNonce": 329867504,
			"isDeleted": false,
			"id": "lALheTSQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4281.073910373434,
			"y": -328.46892861684864,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 91.43988037109375,
			"height": 25,
			"seed": 1781153231,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "u(t) =  d",
			"rawText": "u(t) =  d",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "u(t) =  d",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 221,
			"versionNonce": 1590519312,
			"isDeleted": false,
			"id": "bAXjQ0v6",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4207.155952720735,
			"y": -297.07311007991666,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 22.679977416992188,
			"height": 25,
			"seed": 276833281,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dt",
			"rawText": "dt",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dt",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 227,
			"versionNonce": 1269809904,
			"isDeleted": false,
			"id": "qnvAdlOs",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4172.0595171738605,
			"y": -317.21393483133716,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 34.9599609375,
			"height": 25,
			"seed": 424415151,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r(t)",
			"rawText": "r(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "r(t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 122,
			"versionNonce": 1515594768,
			"isDeleted": false,
			"id": "4bQA4wbvtaZxRLBaeFGTx",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4209.19760644055,
			"y": -305.1356877610249,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 25.81265536221599,
			"height": 0,
			"seed": 399640879,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					25.81265536221599,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 185,
			"versionNonce": 949609712,
			"isDeleted": false,
			"id": "iYe100yM",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4487.436020858166,
			"y": -224.06429882281645,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 484.8394470214844,
			"height": 25,
			"seed": 689330881,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The delayed unit ramp signal r(t - a) is given by:",
			"rawText": "The delayed unit ramp signal r(t - a) is given by:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The delayed unit ramp signal r(t - a) is given by:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 124,
			"versionNonce": 571941392,
			"isDeleted": false,
			"id": "bcDEwR63",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4226.834547136576,
			"y": -132.24611700463493,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 108.85984802246094,
			"height": 25,
			"seed": 1519809999,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r(t - a) = ",
			"rawText": "r(t - a) = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "r(t - a) = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 133154544,
			"isDeleted": false,
			"id": "hTiAcDMo",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4092.749741561292,
			"y": -152.06706205079945,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 188.9397430419922,
			"height": 75,
			"seed": 598144225,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "Y3rTNnQcORN7z0UTLJ5oz",
					"type": "arrow"
				},
				{
					"id": "nASAvVEQ8HAJVb3GwDhLb",
					"type": "arrow"
				}
			],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t - a   for t >= a\n\n0       for t < a",
			"rawText": "t - a   for t >= a\n\n0       for t < a",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t - a   for t >= a\n\n0       for t < a",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "arrow",
			"version": 240,
			"versionNonce": 84434960,
			"isDeleted": false,
			"id": "Y3rTNnQcORN7z0UTLJ5oz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4101.298935897229,
			"y": -143.43530379440745,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 17.208418412642004,
			"height": 17.208418412642004,
			"seed": 1275045217,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hTiAcDMo",
				"focus": 0.9993743729572224,
				"gap": 8.549194335937045
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-17.208418412642004,
					17.208418412642004
				]
			]
		},
		{
			"type": "arrow",
			"version": 247,
			"versionNonce": 1983473904,
			"isDeleted": false,
			"id": "nASAvVEQ8HAJVb3GwDhLb",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4096.9967896791895,
			"y": -96.11208380150993,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 27.246759588068016,
			"height": 18.64252263849403,
			"seed": 2116901761,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hTiAcDMo",
				"focus": -0.8419857608677564,
				"gap": 4.247048117897521
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-27.246759588068016,
					-18.64252263849403
				]
			]
		},
		{
			"type": "text",
			"version": 113,
			"versionNonce": 857857552,
			"isDeleted": false,
			"id": "WYRNbeVB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4428.652728954758,
			"y": -63.15520791372455,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 28.079971313476562,
			"height": 25,
			"seed": 895352321,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "OR",
			"rawText": "OR",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "OR",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 137,
			"versionNonce": 1862191856,
			"isDeleted": false,
			"id": "elp1j5Mk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4242.2890925911215,
			"y": -16.79157155008852,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 256.05963134765625,
			"height": 25,
			"seed": 382313775,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r(t - a) = (t - a)u(t - a)",
			"rawText": "r(t - a) = (t - a)u(t - a)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "r(t - a) = (t - a)u(t - a)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 122,
			"versionNonce": 492542992,
			"isDeleted": false,
			"id": "WEh6ADMv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4458.153033431457,
			"y": 60.549308289302985,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 670.3192749023438,
			"height": 25,
			"seed": 218755183,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The graphical representations of r(t) and r(t - a) are shown below:",
			"rawText": "The graphical representations of r(t) and r(t - a) are shown below:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The graphical representations of r(t) and r(t - a) are shown below:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "arrow",
			"version": 52,
			"versionNonce": 751299824,
			"isDeleted": false,
			"id": "qhqlxKo6cHyJfiCoJi9Da",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4424.483020003722,
			"y": 384.1115031135216,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 263.4326171874999,
			"seed": 191823823,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YXmOu4l9",
				"focus": -1.9609226248232652,
				"gap": 6.61114501953125
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-263.4326171874999
				]
			]
		},
		{
			"type": "arrow",
			"version": 63,
			"versionNonce": 1437440528,
			"isDeleted": false,
			"id": "rGW3ip38ubHY9u6VOkkis",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4451.299517806457,
			"y": 366.7596964728966,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 323.3753967285156,
			"height": 0,
			"seed": 1125238529,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					323.3753967285156,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 54,
			"versionNonce": 1495060208,
			"isDeleted": false,
			"id": "Rdh_MO8gCDOZnsZqIi2De",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3938.8031399866522,
			"y": 386.0982217335091,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 0,
			"height": 263.4326171874999,
			"seed": 424100321,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "wFcBp92x",
				"focus": -2.2203340815642507,
				"gap": 8.395895129414384
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-263.4326171874999
				]
			]
		},
		{
			"type": "arrow",
			"version": 67,
			"versionNonce": 1863309328,
			"isDeleted": false,
			"id": "AzkbhESrv7WTA65RQIWrv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3965.6196377893866,
			"y": 368.7464150928841,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 323.3753967285156,
			"height": 0,
			"seed": 1638292929,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					323.3753967285156,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 110,
			"versionNonce": 746942704,
			"isDeleted": false,
			"id": "kjUKWRm6ZN3XMqiymO1TR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4427.131182845519,
			"y": 367.69231366039674,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 238.19357299804688,
			"height": 189.29290771484364,
			"seed": 1630022063,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					238.19357299804688,
					-189.29290771484364
				]
			]
		},
		{
			"type": "line",
			"version": 65,
			"versionNonce": 1568298512,
			"isDeleted": false,
			"id": "Uj52hc9-6_4q7__6CH042",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3837.1648437341914,
			"y": 367.69231366039674,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 175.09594726562455,
			"height": 175.0959472656249,
			"seed": 192726863,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					175.09594726562455,
					-175.0959472656249
				]
			]
		},
		{
			"type": "text",
			"version": 23,
			"versionNonce": 243913456,
			"isDeleted": false,
			"id": "4gJfcZJO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4394.674914534972,
			"y": 118.08464764477185,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 34.9599609375,
			"height": 25,
			"seed": 1607519567,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097085,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r(t)",
			"rawText": "r(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "r(t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 1441076240,
			"isDeleted": false,
			"id": "tVnxtG8Q",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4132.674914534972,
			"y": 383.08464764477174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 753577007,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 43,
			"versionNonce": 900855024,
			"isDeleted": false,
			"id": "YXmOu4l9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4417.871874984191,
			"y": 376.887687195553,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 1322845441,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "qhqlxKo6cHyJfiCoJi9Da",
					"type": "arrow"
				}
			],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 29,
			"versionNonce": 776475152,
			"isDeleted": false,
			"id": "KvdTvjsO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4220.674914534972,
			"y": 261.08464764477185,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 85.7598876953125,
			"height": 25,
			"seed": 358571329,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "O77JoO_-h4G1Tcmv16sKg",
					"type": "arrow"
				}
			],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "slope = 1",
			"rawText": "slope = 1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "slope = 1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "arrow",
			"version": 37,
			"versionNonce": 1199953648,
			"isDeleted": false,
			"id": "O77JoO_-h4G1Tcmv16sKg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4226.242266829894,
			"y": 269.8909830939906,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 42.590911865234375,
			"height": 23.66162109375,
			"seed": 361194159,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "KvdTvjsO",
				"focus": -0.6393199581626526,
				"gap": 5.567352294921875
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-42.590911865234375,
					-23.66162109375
				]
			]
		},
		{
			"type": "text",
			"version": 36,
			"versionNonce": 1033588752,
			"isDeleted": false,
			"id": "UZLTYDzn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3670.9859397124364,
			"y": 282.0322287845374,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 85.7598876953125,
			"height": 25,
			"seed": 1283680033,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "xjtFTGNbPUcb1eRh-AVvL",
					"type": "arrow"
				}
			],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "slope = 1",
			"rawText": "slope = 1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "slope = 1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "arrow",
			"version": 59,
			"versionNonce": 2022537456,
			"isDeleted": false,
			"id": "xjtFTGNbPUcb1eRh-AVvL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3676.5532920073583,
			"y": 290.83856423375613,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 42.590911865234375,
			"height": 23.66162109375,
			"seed": 1017895681,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "UZLTYDzn",
				"focus": -0.6393199581626526,
				"gap": 5.567352294921875
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-42.590911865234375,
					-23.66162109375
				]
			]
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 1003933200,
			"isDeleted": false,
			"id": "JSn8Gxgq",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3635.6749145349727,
			"y": 381.08464764477174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 1241621281,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 31,
			"versionNonce": 743496432,
			"isDeleted": false,
			"id": "sy0KJFbK",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3843.7170287927847,
			"y": 376.46514080883424,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 13.339981079101562,
			"height": 25,
			"seed": 1705094127,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "a",
			"rawText": "a",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "a",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 29,
			"versionNonce": 569543696,
			"isDeleted": false,
			"id": "wFcBp92x",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3930.407244857238,
			"y": 375.0425944221155,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 913683553,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "Rdh_MO8gCDOZnsZqIi2De",
					"type": "arrow"
				}
			],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 358087920,
			"isDeleted": false,
			"id": "EQWrYWcW",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3919.871874984191,
			"y": 109.62004803539685,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 76.5198974609375,
			"height": 25,
			"seed": 2061320239,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r(t - a)",
			"rawText": "r(t - a)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "r(t - a)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 45,
			"versionNonce": 166103568,
			"isDeleted": false,
			"id": "x7XgxfEe",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4390.055377181457,
			"y": 437.4650797736783,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 154.03981018066406,
			"height": 25,
			"seed": 1777374127,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "unit ramp signal",
			"rawText": "unit ramp signal",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "unit ramp signal",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 63,
			"versionNonce": 1428872944,
			"isDeleted": false,
			"id": "JKhh9yTQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3903.6462890466914,
			"y": 440.8876871955533,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 235.69972229003906,
			"height": 25,
			"seed": 1175511055,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Delayed unit time signal",
			"rawText": "Delayed unit time signal",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Delayed unit time signal",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "rectangle",
			"version": 265,
			"versionNonce": 246073360,
			"isDeleted": false,
			"id": "tFJXLMdXeIN0EypMMFij_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4708.7665871599565,
			"y": -957.9634432558664,
			"strokeColor": "#0c8599",
			"backgroundColor": "transparent",
			"width": 1285.6145222981772,
			"height": 2297.136183870998,
			"seed": 689393615,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "_L-zlhOGSIF-EKKSaDcVE",
					"type": "arrow"
				}
			],
			"updated": 1703931097086,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 79,
			"versionNonce": 475103472,
			"isDeleted": false,
			"id": "mtcn2Ocb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4577.0676600925835,
			"y": 555.2841817314372,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 554.3794555664062,
			"height": 25,
			"seed": 886796816,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The discrete-time unit ramp sequence r(n) is defined as:",
			"rawText": "The discrete-time unit ramp sequence r(n) is defined as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The discrete-time unit ramp sequence r(n) is defined as:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 45,
			"versionNonce": 741819920,
			"isDeleted": false,
			"id": "OFQAl7IU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4288.595843075982,
			"y": 637.7841817314372,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.09991455078125,
			"height": 25,
			"seed": 1525619952,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r[n] = ",
			"rawText": "r[n] = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "r[n] = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 56,
			"versionNonce": 1247011568,
			"isDeleted": false,
			"id": "O95oBwAd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4178.0676600925835,
			"y": 607.7841817314372,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 143.8798370361328,
			"height": 75,
			"seed": 936842768,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "mr0_Le7cp1H2gQKbeUxh-",
					"type": "arrow"
				},
				{
					"id": "jmcL5FpkyeOPhgA_m7o3B",
					"type": "arrow"
				}
			],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "n   for n >= 0\n\n0  for  n < 0",
			"rawText": "n   for n >= 0\n\n0  for  n < 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "n   for n >= 0\n\n0  for  n < 0",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "arrow",
			"version": 35,
			"versionNonce": 528745488,
			"isDeleted": false,
			"id": "mr0_Le7cp1H2gQKbeUxh-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4185.418276547662,
			"y": 618.655344145988,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 33.52062225341797,
			"height": 21.689834594726562,
			"seed": 34581744,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "O95oBwAd",
				"focus": 0.9272466361815106,
				"gap": 7.350616455078125
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-33.52062225341797,
					21.689834594726562
				]
			]
		},
		{
			"type": "arrow",
			"version": 34,
			"versionNonce": 230294768,
			"isDeleted": false,
			"id": "jmcL5FpkyeOPhgA_m7o3B",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4185.418276547662,
			"y": 664.00679220507,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 33.52062225341797,
			"height": 17.746200561523438,
			"seed": 929167376,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "O95oBwAd",
				"focus": -0.8030597522740243,
				"gap": 7.350616455078125
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-33.52062225341797,
					-17.746200561523438
				]
			]
		},
		{
			"type": "text",
			"version": 93,
			"versionNonce": 1183384080,
			"isDeleted": false,
			"id": "chs9bSFl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4435.727610348931,
			"y": 703.0303822929606,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 349.95953369140625,
			"height": 25,
			"seed": 1899828240,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "                or    r[n] = n*u[n]",
			"rawText": "                or    r[n] = n*u[n]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "                or    r[n] = n*u[n]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 113,
			"versionNonce": 67888880,
			"isDeleted": false,
			"id": "59nHrgs3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4545.629726668336,
			"y": 768.9586179689385,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 814.5391845703125,
			"height": 25,
			"seed": 1008367344,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097086,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The shifted version of the discrete-time unit ramp sequence r(n - k) is defined as",
			"rawText": "The shifted version of the discrete-time unit ramp sequence r(n - k) is defined as",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The shifted version of the discrete-time unit ramp sequence r(n - k) is defined as",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 34,
			"versionNonce": 4079632,
			"isDeleted": false,
			"id": "F8xlfXY0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4308.23842232051,
			"y": 847.2194875341559,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 108.05986022949219,
			"height": 25,
			"seed": 764112400,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r[n - k] = ",
			"rawText": "r[n - k] = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "r[n - k] = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 73,
			"versionNonce": 1506904304,
			"isDeleted": false,
			"id": "ymn0WSxw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4194.533269891842,
			"y": 825.1129254587481,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 181.83978271484375,
			"height": 75,
			"seed": 1710658064,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "n - k   for n >= 0\n\n0       for n < k",
			"rawText": "n - k   for n >= 0\n\n0       for n < k",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "n - k   for n >= 0\n\n0       for n < k",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "text",
			"version": 67,
			"versionNonce": 211533328,
			"isDeleted": false,
			"id": "pL3OGigq",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4384.760161450945,
			"y": 930.6977484037211,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 393.6595458984375,
			"height": 25,
			"seed": 1925568528,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "        or    r[n - k] = [n -k]*u[n - k]",
			"rawText": "        or    r[n - k] = [n -k]*u[n - k]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "        or    r[n - k] = [n -k]*u[n - k]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 90,
			"versionNonce": 1788013296,
			"isDeleted": false,
			"id": "V5QoENc8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4543.89059623355,
			"y": 992.4368788385035,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 661.1192626953125,
			"height": 25,
			"seed": 633627888,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The graphical representation of r[n] and r[n - 2] are shown below",
			"rawText": "The graphical representation of r[n] and r[n - 2] are shown below",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The graphical representation of r[n] and r[n - 2] are shown below",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "arrow",
			"version": 111,
			"versionNonce": 1821998096,
			"isDeleted": false,
			"id": "-8QbEwp-QJrWNsrXXtyhM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4654.780674570849,
			"y": 1280.3624796367376,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 467.8919253141994,
			"height": 0,
			"seed": 507708144,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "MDybL3Clq8RT-j1EE_aj4",
				"focus": 0.17746049907830963,
				"gap": 3.859055402087046
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					467.8919253141994,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 77,
			"versionNonce": 1624771824,
			"isDeleted": false,
			"id": "UyNhiwKCI5VSdcaKDFjrx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4599.755039805221,
			"y": 1269.683184884699,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 1580019440,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 65,
			"versionNonce": 1110407696,
			"isDeleted": false,
			"id": "oqqE6LJQGPHGNqorhzxDg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4552.193911769385,
			"y": 1269.4475626445494,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 229676048,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 37,
			"versionNonce": 1445523184,
			"isDeleted": false,
			"id": "F1uVX0nmqQI8ABgUsCffv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4447.772896568977,
			"y": 1221.0959364556907,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 874117360,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 47,
			"versionNonce": 810924048,
			"isDeleted": false,
			"id": "zEmxYagUKwOFplVrK6kaT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4393.3942875336525,
			"y": 1166.2152469176472,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 1921124880,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 42,
			"versionNonce": 1930268912,
			"isDeleted": false,
			"id": "S5fYxOmiY2fBEL1dKaE4f",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4339.714026833924,
			"y": 1116.613461506642,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 1041261296,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 37,
			"versionNonce": 990131728,
			"isDeleted": false,
			"id": "5-NQrdLDFahOe3bVe4us3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4287.772896568977,
			"y": 1061.0959364556911,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 397000720,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 37,
			"versionNonce": 252572400,
			"isDeleted": false,
			"id": "Y9nRvBO7Qgkl4Vim0oAMd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4501.685940047239,
			"y": 1270.6611538469951,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 1858374896,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 42,
			"versionNonce": 657650704,
			"isDeleted": false,
			"id": "MDybL3Clq8RT-j1EE_aj4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4651.018401197035,
			"y": 1269.0567253483541,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 68232944,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "-8QbEwp-QJrWNsrXXtyhM",
					"type": "arrow"
				}
			],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 244,
			"versionNonce": 1353848048,
			"isDeleted": false,
			"id": "OsYykFB7dEqOd_Z2z4xUN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4023.8640855987637,
			"y": 1281.1764232508679,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 467.8919253141994,
			"height": 0,
			"seed": 1182758640,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "PkvDbw9Y5KdbOybri4dCn",
				"focus": 0.17746049907830966,
				"gap": 3.85905540208614
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					467.8919253141994,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 132,
			"versionNonce": 1524232720,
			"isDeleted": false,
			"id": "e8STXU1Zl7Y0CWm_KL74I",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3968.838450833135,
			"y": 1270.4971284988294,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 659757296,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 120,
			"versionNonce": 1300362992,
			"isDeleted": false,
			"id": "ReANDC7dZdNJ9N84ZGBkn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3921.2773227973,
			"y": 1270.26150625868,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 828537584,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 92,
			"versionNonce": 1022439440,
			"isDeleted": false,
			"id": "e14lyj5IXOoCKYyrnP6XQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3816.856307596891,
			"y": 1221.909880069821,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 1194695920,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 102,
			"versionNonce": 705009904,
			"isDeleted": false,
			"id": "4zkEJVdif4QlmqS2zfKL_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3762.4776985615667,
			"y": 1167.0291905317774,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 978616048,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 97,
			"versionNonce": 359706128,
			"isDeleted": false,
			"id": "yap9gGOGD46YpBIaUkNh9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3708.7974378618387,
			"y": 1117.427405120772,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 1799823600,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 92,
			"versionNonce": 969210608,
			"isDeleted": false,
			"id": "2BTE2yAMmaZ-Gm2EIYjK4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3656.856307596891,
			"y": 1061.9098800698214,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 1771406064,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 92,
			"versionNonce": 1833987088,
			"isDeleted": false,
			"id": "o7wQqledweeb1YFQLsIAR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3870.769351075153,
			"y": 1271.4750974611254,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 331850992,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 97,
			"versionNonce": 524819696,
			"isDeleted": false,
			"id": "PkvDbw9Y5KdbOybri4dCn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4020.10181222495,
			"y": 1269.8706689624844,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 16.460252844768547,
			"height": 19.20362389605998,
			"seed": 929400560,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "OsYykFB7dEqOd_Z2z4xUN",
					"type": "arrow"
				}
			],
			"updated": 1703931097087,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 24,
			"versionNonce": 1854433808,
			"isDeleted": false,
			"id": "iEBzLLqF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4489.1079875379055,
			"y": 1106.3499223167644,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 37.75996398925781,
			"height": 25,
			"seed": 1819738640,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097087,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r[n]",
			"rawText": "r[n]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "r[n]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 27,
			"versionNonce": 1813446384,
			"isDeleted": false,
			"id": "siqxJr7N",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3940.4123353639916,
			"y": 1104.6107918819816,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 80.21990966796875,
			"height": 25,
			"seed": 863237872,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "r[n - 2]",
			"rawText": "r[n - 2]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "r[n - 2]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 1141942288,
			"isDeleted": false,
			"id": "vozEYIqO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4495.194944059643,
			"y": 1302.0020962298076,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 606747888,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 27,
			"versionNonce": 1085907184,
			"isDeleted": false,
			"id": "4ZEDf3Lr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4439.040663106857,
			"y": 1299.7974533120089,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 1198925552,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 43,
			"versionNonce": 2044798480,
			"isDeleted": false,
			"id": "WgyNlM0D",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4392.1206563133765,
			"y": 1303.7412266645897,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 14.239990234375,
			"height": 25,
			"seed": 1920151280,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 45,
			"versionNonce": 1823998704,
			"isDeleted": false,
			"id": "Iohw5pbE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4337.2400463864105,
			"y": 1301.1325310124164,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 13.619979858398438,
			"height": 25,
			"seed": 1387017968,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "3",
			"rawText": "3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 30,
			"versionNonce": 1559356432,
			"isDeleted": false,
			"id": "KJI1GBR5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4283.829136484916,
			"y": 1297.7889190049434,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 1780563696,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "4",
			"rawText": "4",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 33,
			"versionNonce": 244983024,
			"isDeleted": false,
			"id": "rFNzsJ2P",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4552.855599205704,
			"y": 1301.9289071163566,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 13.639984130859375,
			"height": 25,
			"seed": 986859248,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-1",
			"rawText": "-1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 40,
			"versionNonce": 1530585616,
			"isDeleted": false,
			"id": "wv5Nvg4I",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4607.307370817455,
			"y": 1303.7661183935304,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 22.459976196289062,
			"height": 25,
			"seed": 1104670960,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-2",
			"rawText": "-2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 23,
			"versionNonce": 870844144,
			"isDeleted": false,
			"id": "Szi7YDT2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4656.970669051152,
			"y": 1302.4310406931231,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 21.8399658203125,
			"height": 25,
			"seed": 504584944,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-3",
			"rawText": "-3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-3",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 46,
			"versionNonce": 1672749072,
			"isDeleted": false,
			"id": "mMqDmMBbtg-vh58eRGgKF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4438.236989321192,
			"y": 1245.142169259699,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 0,
			"height": 35.66385020380426,
			"seed": 173594352,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					35.66385020380426
				]
			]
		},
		{
			"type": "line",
			"version": 100,
			"versionNonce": 2032773360,
			"isDeleted": false,
			"id": "Wz2aSmqdL7VzFS3vFC5ky",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4382.243089656939,
			"y": 1188.9029432916284,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 0,
			"height": 87.32229906971224,
			"seed": 853873392,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					87.32229906971224
				]
			]
		},
		{
			"type": "line",
			"version": 168,
			"versionNonce": 1180016144,
			"isDeleted": false,
			"id": "knNVTgIabxa04Iq20rDhk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4331.342794565228,
			"y": 1135.4071414488974,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 0,
			"height": 145.39887801460577,
			"seed": 2019823632,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					145.39887801460577
				]
			]
		},
		{
			"type": "line",
			"version": 175,
			"versionNonce": 703007472,
			"isDeleted": false,
			"id": "GcP5CWFa9CxtlktCqcb6L",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4278.9727198369665,
			"y": 1080.5396408120087,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 0,
			"height": 200.2663786514945,
			"seed": 1487617264,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					200.2663786514945
				]
			]
		},
		{
			"type": "line",
			"version": 52,
			"versionNonce": 337075216,
			"isDeleted": false,
			"id": "moPbGBy5dHYODvm2pc76J",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3807.827965675967,
			"y": 1244.4685974904164,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 0,
			"height": 35.66385020380426,
			"seed": 1082861072,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					35.66385020380426
				]
			]
		},
		{
			"type": "line",
			"version": 180,
			"versionNonce": 1621634288,
			"isDeleted": false,
			"id": "eOUINaPWmt2V2AJjvQknZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3700.4058783797705,
			"y": 1139.227942230147,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 0,
			"height": 142.65553350033974,
			"seed": 1887525904,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					142.65553350033974
				]
			]
		},
		{
			"type": "line",
			"version": 179,
			"versionNonce": 2129746448,
			"isDeleted": false,
			"id": "CmXXMrvPiUtJvOF5eCuYO",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3648.6725860903684,
			"y": 1084.3604415932582,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 0,
			"height": 197.52303413722825,
			"seed": 923513072,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					197.52303413722825
				]
			]
		},
		{
			"type": "line",
			"version": 143,
			"versionNonce": 653594352,
			"isDeleted": false,
			"id": "cB0VyndcwTT0hYL5vnBTJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3754.1842199218904,
			"y": 1187.2370019702962,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 0,
			"height": 94.64647376019025,
			"seed": 1547648016,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					94.64647376019025
				]
			]
		},
		{
			"type": "text",
			"version": 27,
			"versionNonce": 970692624,
			"isDeleted": false,
			"id": "GWXAg0CF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3968.6058804981653,
			"y": 1301.9654751360572,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 272021744,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 54,
			"versionNonce": 357937392,
			"isDeleted": false,
			"id": "a27ceYv7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3917.4362080711953,
			"y": 1300.888018869073,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 1968881904,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 36,
			"versionNonce": 1489901072,
			"isDeleted": false,
			"id": "pPUaCe4I",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3873.357732782473,
			"y": 1299.0874286856495,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 14.239990234375,
			"height": 25,
			"seed": 1144703216,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097088,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 29,
			"versionNonce": 1934758640,
			"isDeleted": false,
			"id": "9yFctAgd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3814.729405039606,
			"y": 1296.2460033289917,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 13.619979858398438,
			"height": 25,
			"seed": 1054265584,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "3",
			"rawText": "3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 38,
			"versionNonce": 817943568,
			"isDeleted": false,
			"id": "SHJV6YWa",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3760.816335024321,
			"y": 1298.8546989811655,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 657381616,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "4",
			"rawText": "4",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 32,
			"versionNonce": 1467102448,
			"isDeleted": false,
			"id": "Ptm3v4aM",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3705.1275930915763,
			"y": 1292.363689725052,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 12.3599853515625,
			"height": 25,
			"seed": 1061347568,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "5",
			"rawText": "5",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "5",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 27,
			"versionNonce": 934007312,
			"isDeleted": false,
			"id": "5e7HWWdr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3648.9118258531253,
			"y": 1296.8462177481497,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 1225976048,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "6",
			"rawText": "6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 1195251440,
			"isDeleted": false,
			"id": "htNWltqC",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4023.1557064152853,
			"y": 1299.3817242868724,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 13.639984130859375,
			"height": 25,
			"seed": 111079664,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-1",
			"rawText": "-1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 1686573072,
			"isDeleted": false,
			"id": "NGw8ZGGX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3536.0645092770383,
			"y": 1292.4368788385027,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 9.339996337890625,
			"height": 25,
			"seed": 1234286096,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "n",
			"rawText": "n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "n",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 1463662832,
			"isDeleted": false,
			"id": "ULVcWp69",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4190.84711797269,
			"y": 1299.3934005776332,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 9.339996337890625,
			"height": 25,
			"seed": 862841872,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "n",
			"rawText": "n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "n",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 320,
			"versionNonce": 256544272,
			"isDeleted": false,
			"id": "1dmNPRUN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4456.43156323008,
			"y": -4310.6853497831,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 802.38525390625,
			"height": 62.31850063671178,
			"seed": 791801360,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"fontSize": 49.854800509369426,
			"fontFamily": 1,
			"text": "THE UNIT IMPULSE FUNCTION",
			"rawText": "THE UNIT IMPULSE FUNCTION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "THE UNIT IMPULSE FUNCTION",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "rectangle",
			"version": 282,
			"versionNonce": 1257839344,
			"isDeleted": false,
			"id": "HGurlKY2fWES5yDTmKYwa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4731.910613165244,
			"y": -4336.376060222552,
			"strokeColor": "#f08c00",
			"backgroundColor": "transparent",
			"width": 1306.460923071585,
			"height": 3307.1083537509444,
			"seed": 371157744,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "dknBSVLuqmd_00LEBU8yf",
					"type": "arrow"
				}
			],
			"updated": 1703931097089,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 104,
			"versionNonce": 1357794320,
			"isDeleted": false,
			"id": "c35gLVT5faZEncA2sHV9N",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4530.4957815110865,
			"y": -4239.1387793645445,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 894.17607796116,
			"height": 0,
			"seed": 976996368,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					894.17607796116,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 323,
			"versionNonce": 888683760,
			"isDeleted": false,
			"id": "jivfDg5v",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4694.69734596833,
			"y": -4209.396409724938,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1244.858642578125,
			"height": 50,
			"seed": 123962896,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The unit impulse function is the most widely used elementary function in the analysis of signals and systems. The continuous-\ntime unit impulse function  (t) also called Dirac delta function, plays an important role in signal analysis. It is defined as:",
			"rawText": "The unit impulse function is the most widely used elementary function in the analysis of signals and systems. The continuous-\ntime unit impulse function  (t) also called Dirac delta function, plays an important role in signal analysis. It is defined as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The unit impulse function is the most widely used elementary function in the analysis of signals and systems. The continuous-\ntime unit impulse function  (t) also called Dirac delta function, plays an important role in signal analysis. It is defined as:",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "line",
			"version": 3218,
			"versionNonce": 1667910160,
			"isDeleted": false,
			"id": "i_g5yKy9_xWwW-Y7TDjlM",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4440.496598783267,
			"y": -4183.720524779669,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1737220336,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3303,
			"versionNonce": 381886192,
			"isDeleted": false,
			"id": "6NEvkAWhKg4vpjg01p2eN",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4137.343335246089,
			"y": -4142.6260243846355,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 402497776,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3332,
			"versionNonce": 28739600,
			"isDeleted": false,
			"id": "SA_o0_y_gxI_rK7pLXA8U",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4135.877728705946,
			"y": -4082.5365815453706,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 607133712,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 4687,
			"versionNonce": 14794992,
			"isDeleted": false,
			"id": "ynUkfP46raBxsQ3mxZZrp",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4159.266252007116,
			"y": -4137.278111464925,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 1099688464,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 152,
			"versionNonce": 1204487696,
			"isDeleted": false,
			"id": "aeX6EOJoMjOYCk1iVQDQr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4167.9620784098115,
			"y": -4084.1459250575817,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.724738906051243,
			"height": 0,
			"seed": 1008045584,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					11.724738906051243,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3290,
			"versionNonce": 853287664,
			"isDeleted": false,
			"id": "MgJnNJj-NWtlaHhL4fglv",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4114.1776725390655,
			"y": -4122.0867092429135,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 963273456,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 98,
			"versionNonce": 312460304,
			"isDeleted": false,
			"id": "Uyoe2kiI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4103.519622529814,
			"y": -4118.3864236682975,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 96.79988098144531,
			"height": 25,
			"seed": 1738358288,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t) dt = 1",
			"rawText": "(t) dt = 1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t) dt = 1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 24,
			"versionNonce": 993674480,
			"isDeleted": false,
			"id": "io9WM03u",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4663.085477403977,
			"y": -4057.0574019279034,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 34.059967041015625,
			"height": 25,
			"seed": 882373360,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "and",
			"rawText": "and",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "and",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3350,
			"versionNonce": 1613546000,
			"isDeleted": false,
			"id": "4MOkjjk-oskjcOTDQHow1",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4224.321000488287,
			"y": -4045.4187201504965,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 810164240,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097089,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3323,
			"versionNonce": 394536688,
			"isDeleted": false,
			"id": "XIHcU4KYAhK5EvuGxDcmL",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4265.804405881262,
			"y": -3917.623767387811,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1710370032,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 795475984,
			"isDeleted": false,
			"id": "crKrSj4i",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4204.303963012799,
			"y": -4046.969387545627,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 205.17974853515625,
			"height": 25,
			"seed": 349623312,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t) = 0   for t != 0",
			"rawText": "(t) = 0   for t != 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t) = 0   for t != 0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 25,
			"versionNonce": 1413597424,
			"isDeleted": false,
			"id": "Jo6sQB2K",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4656.6447889822375,
			"y": -3933.3961842304902,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 54.65992736816406,
			"height": 25,
			"seed": 1118020624,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "ie, as",
			"rawText": "ie, as",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "ie, as",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 1615822352,
			"isDeleted": false,
			"id": "VZetwckk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4246.98368128746,
			"y": -3917.3998879938576,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 58.699920654296875,
			"height": 25,
			"seed": 1694521072,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "GYKnjA9gnGXl-AxsvbqHv",
					"type": "arrow"
				},
				{
					"id": "jmZWHUPLFCNpoFG933W4w",
					"type": "arrow"
				}
			],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t) = ",
			"rawText": "(t) = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t) = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 53,
			"versionNonce": 754658032,
			"isDeleted": false,
			"id": "hhtlLm8T",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4146.508941908312,
			"y": -3936.7219532590784,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 142.21981811523438,
			"height": 25,
			"seed": 987315728,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "GYKnjA9gnGXl-AxsvbqHv",
					"type": "arrow"
				}
			],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1    for t = 0",
			"rawText": "1    for t = 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1    for t = 0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 61,
			"versionNonce": 332741648,
			"isDeleted": false,
			"id": "Gy9zYtCk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4146.508941908312,
			"y": -3878.755757463416,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 146.47982788085938,
			"height": 25,
			"seed": 329571344,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "jmZWHUPLFCNpoFG933W4w",
					"type": "arrow"
				}
			],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0   for t != 0",
			"rawText": "0   for t != 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0   for t != 0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "arrow",
			"version": 35,
			"versionNonce": 741887216,
			"isDeleted": false,
			"id": "GYKnjA9gnGXl-AxsvbqHv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4157.047967556006,
			"y": -3934.39136413111,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 30.77751051281757,
			"height": 19.05274325299297,
			"seed": 233263632,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hhtlLm8T",
				"focus": 1.074195651472327,
				"gap": 10.539025647693961
			},
			"endBinding": {
				"elementId": "VZetwckk",
				"focus": 0.26130561507958644,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-30.77751051281757,
					19.05274325299297
				]
			]
		},
		{
			"type": "arrow",
			"version": 48,
			"versionNonce": 200489488,
			"isDeleted": false,
			"id": "jmZWHUPLFCNpoFG933W4w",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4149.719991562838,
			"y": -3869.9051867327357,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 36.63987996584274,
			"height": 32.243088699186956,
			"seed": 1862908656,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Gy9zYtCk",
				"focus": -0.8268549269450549,
				"gap": 3.2110496545255955
			},
			"endBinding": {
				"elementId": "VZetwckk",
				"focus": -0.6462480587326971,
				"gap": 1.9238891044824413
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-36.63987996584274,
					-32.243088699186956
				]
			]
		},
		{
			"type": "text",
			"version": 270,
			"versionNonce": 1266757360,
			"isDeleted": false,
			"id": "OHjyVQSZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4682.592753860969,
			"y": -3834.474368366519,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1210.7388916015625,
			"height": 50,
			"seed": 1645550832,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "That is, the impulse function has zero amplitude everywhere except at t = 0, At t = 0, the amplitude is infinity so that\nthe area under the curve is unity.  (t) can be represented as a limiting case of a rectangle pulse function.",
			"rawText": "That is, the impulse function has zero amplitude everywhere except at t = 0, At t = 0, the amplitude is infinity so that\nthe area under the curve is unity.  (t) can be represented as a limiting case of a rectangle pulse function.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "That is, the impulse function has zero amplitude everywhere except at t = 0, At t = 0, the amplitude is infinity so that\nthe area under the curve is unity.  (t) can be represented as a limiting case of a rectangle pulse function.",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "line",
			"version": 3291,
			"versionNonce": 195131408,
			"isDeleted": false,
			"id": "x9Xr0S2nqbw8q3Wh-O9cA",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4336.477769990473,
			"y": -3806.4115903399097,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 38907408,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 97,
			"versionNonce": 324915440,
			"isDeleted": false,
			"id": "Ex9VSF4s",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4679.595873441802,
			"y": -3758.6935788025326,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 544.2794189453125,
			"height": 25,
			"seed": 1489543408,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A delayed unit impulse function   (t - a) is defined as:",
			"rawText": "A delayed unit impulse function   (t - a) is defined as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A delayed unit impulse function   (t - a) is defined as:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3347,
			"versionNonce": 920122896,
			"isDeleted": false,
			"id": "D25KkZ77T9YIkPJgpGfO3",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4362.282879285557,
			"y": -3756.6455011629882,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 620042480,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3372,
			"versionNonce": 995504880,
			"isDeleted": false,
			"id": "6lovKxamWlv8pu_8gWoIj",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4267.9393515840775,
			"y": -3680.2414129526433,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 198452976,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 102,
			"versionNonce": 1921954832,
			"isDeleted": false,
			"id": "KVDO6Gp6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4249.118626990275,
			"y": -3680.017533558689,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.25985717773438,
			"height": 25,
			"seed": 1049741552,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "TVv_Bd3tizsbtYJJ6nRNr",
					"type": "arrow"
				}
			],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t - a) = ",
			"rawText": "(t - a) = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t - a) = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 132,
			"versionNonce": 1240618224,
			"isDeleted": false,
			"id": "nTcrJ9hK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4090.020079665778,
			"y": -3699.339598823911,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 156.05979919433594,
			"height": 75,
			"seed": 1296771824,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "QOagFjdd81aVPQ2VBCMn8",
					"type": "arrow"
				},
				{
					"id": "TVv_Bd3tizsbtYJJ6nRNr",
					"type": "arrow"
				}
			],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1    for t = a\n\n0    for t != a",
			"rawText": "1    for t = a\n\n0    for t != a",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1    for t = a\n\n0    for t != a",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "arrow",
			"version": 47,
			"versionNonce": 1153282576,
			"isDeleted": false,
			"id": "QOagFjdd81aVPQ2VBCMn8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4096.511243943465,
			"y": -3694.7658573224144,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 60.08941448549194,
			"height": 27.846354140077437,
			"seed": 1133913840,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "nTcrJ9hK",
				"focus": 0.9787451622667912,
				"gap": 6.4911642776869485
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-60.08941448549194,
					27.846354140077437
				]
			]
		},
		{
			"type": "arrow",
			"version": 34,
			"versionNonce": 884618992,
			"isDeleted": false,
			"id": "TVv_Bd3tizsbtYJJ6nRNr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4095.0456374033224,
			"y": -3642.0044188300917,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 52.76143849232312,
			"height": 16.12155852647993,
			"seed": 1517843472,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "nTcrJ9hK",
				"focus": -0.7370626046644866,
				"gap": 5.025557737544204
			},
			"endBinding": {
				"elementId": "KVDO6Gp6",
				"focus": -0.2245810643252322,
				"gap": 1.051693916894692
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-52.76143849232312,
					-16.12155852647993
				]
			]
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 878506000,
			"isDeleted": false,
			"id": "c8J9gXDe",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4666.798114340254,
			"y": -3599.412968440523,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 692.2593383789062,
			"height": 25,
			"seed": 1535118864,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The graphical representation of   (t)  and   (t - a) are shown below:",
			"rawText": "The graphical representation of   (t)  and   (t - a) are shown below:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The graphical representation of   (t)  and   (t - a) are shown below:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3379,
			"versionNonce": 3528944,
			"isDeleted": false,
			"id": "3RtBUQyjUwi6-HyLQEDM4",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4337.511661978862,
			"y": -3599.6156700304173,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1101870832,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097090,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3390,
			"versionNonce": 694447632,
			"isDeleted": false,
			"id": "qZUAg0cfnZRYrngMK9Ln9",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4225.627502546796,
			"y": -3597.077100002324,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1900620816,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 167,
			"versionNonce": 1609382640,
			"isDeleted": false,
			"id": "QQy6wFe7VcUr4JCkJVy29",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4652.246754146165,
			"y": -3263.2051128363814,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 260.0432009905371,
			"seed": 1649176304,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "F2DYYKPK",
				"focus": -1.836909451590171,
				"gap": 5.757934728299915
			},
			"endBinding": {
				"elementId": "D18Ca5uA",
				"focus": 0.2621240956170263,
				"gap": 1.2962411294170124
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-260.0432009905371
				]
			]
		},
		{
			"type": "arrow",
			"version": 199,
			"versionNonce": 1288449040,
			"isDeleted": false,
			"id": "WiN0emEOab4qAK-OhMYo3",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4670.73309814095,
			"y": -3277.8610648227186,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 214.8084225772218,
			"height": 0,
			"seed": 1081368592,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "lleJ4vu0mxjqCMAJw9w8e",
				"focus": 1.0079842446766538,
				"gap": 19.085202385851517
			},
			"endBinding": {
				"elementId": "zJSVhQ8f",
				"focus": 1.2587339093982883,
				"gap": 6.974175864193967
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					214.8084225772218,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 66,
			"versionNonce": 1449680112,
			"isDeleted": false,
			"id": "baiAJ80sbjbhDWEuYDtIQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4321.106097327913,
			"y": -3293.109787667363,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 349.49729008686154,
			"height": 0,
			"seed": 2042294512,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "Cr6jNGxc",
				"focus": 1.5787562361462188,
				"gap": 7.234452951827734
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					349.49729008686154,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 69,
			"versionNonce": 1754016272,
			"isDeleted": false,
			"id": "ehHf0_QZUew31XbGY80b-",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3836.371725776854,
			"y": -3291.0778102227846,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 355.59322242059716,
			"height": 0,
			"seed": 1261020912,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					355.59322242059716,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 84,
			"versionNonce": 1429159664,
			"isDeleted": false,
			"id": "lleJ4vu0mxjqCMAJw9w8e",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4651.647895755098,
			"y": -3453.3073278356196,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 111.75785530244684,
			"height": 174.74864504343077,
			"seed": 1852584688,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "QQy6wFe7VcUr4JCkJVy29",
					"type": "arrow"
				},
				{
					"id": "WiN0emEOab4qAK-OhMYo3",
					"type": "arrow"
				}
			],
			"updated": 1703931097091,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 43,
			"versionNonce": 1201432592,
			"isDeleted": false,
			"id": "F2DYYKPK",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4646.488819417865,
			"y": -3267.0434363444133,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 2020707568,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "QQy6wFe7VcUr4JCkJVy29",
					"type": "arrow"
				}
			],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 57,
			"versionNonce": 1556734192,
			"isDeleted": false,
			"id": "D18Ca5uA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4666.118806511744,
			"y": -3549.5445549563356,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.59996032714844,
			"height": 25,
			"seed": 950585872,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "QQy6wFe7VcUr4JCkJVy29",
					"type": "arrow"
				}
			],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(t)",
			"rawText": "x(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 45,
			"versionNonce": 368371216,
			"isDeleted": false,
			"id": "zJSVhQ8f",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4448.950499699534,
			"y": -3274.62689095524,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 1107117584,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "WiN0emEOab4qAK-OhMYo3",
					"type": "arrow"
				}
			],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 584,
			"versionNonce": 482362096,
			"isDeleted": false,
			"id": "oH57xWrbWSWhW8HJD93o9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.71238898038469,
			"x": -4545.78472009963,
			"y": -3276.037500943601,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.90116710998715,
			"height": 26.529784455391564,
			"seed": 1965288688,
			"groupIds": [
				"Z0xqzDnFyMLnPj1N-3ImK"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					26.529784455391564
				],
				[
					17.90116710998715,
					14.149218376208834
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 21,
			"versionNonce": 1083024400,
			"isDeleted": false,
			"id": "MBMrol0m",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4616.063603265934,
			"y": -3476.665004872614,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.419952392578125,
			"height": 25,
			"seed": 451693072,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1 / ",
			"rawText": "1 / ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1 / ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 589,
			"versionNonce": 328885488,
			"isDeleted": false,
			"id": "HmxFrt_bDyQHwpP4nYMs6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.71238898038469,
			"x": -4581.207963884672,
			"y": -3478.632028302015,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.914482782687228,
			"height": 16.369975854183394,
			"seed": 831994896,
			"groupIds": [
				"QLC8ARcJxCNGs-q6D77_l"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					16.369975854183394
				],
				[
					15.914482782687228,
					8.730653788897811
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 58,
			"versionNonce": 1432265232,
			"isDeleted": false,
			"id": "fLCtVdj1Dl7XybHTlG3Zt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4160.000044280541,
			"y": -3292.9688189864664,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 134.10948926028323,
			"seed": 1617390832,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Me4FA285",
				"focus": 0.053393866480651,
				"gap": 3.029608003458634
			},
			"endBinding": {
				"elementId": "LDOxNojP",
				"focus": 1.9946191286733317,
				"gap": 13.1090652427647
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-134.10948926028323
				]
			]
		},
		{
			"type": "text",
			"version": 33,
			"versionNonce": 786450160,
			"isDeleted": false,
			"id": "Me4FA285",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4167.2473911886955,
			"y": -3289.939210983008,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 289637904,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "fLCtVdj1Dl7XybHTlG3Zt",
					"type": "arrow"
				}
			],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 24,
			"versionNonce": 1667227664,
			"isDeleted": false,
			"id": "Cr6jNGxc",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3977.891072967848,
			"y": -3285.8753347155352,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 45078544,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "baiAJ80sbjbhDWEuYDtIQ",
					"type": "arrow"
				}
			],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 25,
			"versionNonce": 1796860144,
			"isDeleted": false,
			"id": "FyL7tzU7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4189.290985385347,
			"y": -3443.7719719662286,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 1010548240,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 35,
			"versionNonce": 1518951952,
			"isDeleted": false,
			"id": "LDOxNojP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4146.890979037777,
			"y": -3445.6043289530094,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.359970092773438,
			"height": 25,
			"seed": 2037248752,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "fLCtVdj1Dl7XybHTlG3Zt",
					"type": "arrow"
				}
			],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t)",
			"rawText": "(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3382,
			"versionNonce": 1942964976,
			"isDeleted": false,
			"id": "eejInkhzkvaCCMA5bg7N4",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4161.310373683929,
			"y": -3445.608595836279,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 2008066064,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 83,
			"versionNonce": 1808997392,
			"isDeleted": false,
			"id": "LccYcF7bVxUvZnISnVNaF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3639.3641279100502,
			"y": -3297.941286754743,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 128.01355692654715,
			"seed": 967807504,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "X5qWmd2Z",
				"focus": -0.09413220504629953,
				"gap": 12.556001000788456
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-128.01355692654715
				]
			]
		},
		{
			"type": "line",
			"version": 42,
			"versionNonce": 1133014256,
			"isDeleted": false,
			"id": "TOE4mDXIiSvocTahWrC0x",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3724.5400840231914,
			"y": -3290.9368415418876,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 95.50223230002939,
			"seed": 605161712,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-95.50223230002939
				]
			]
		},
		{
			"type": "text",
			"version": 36,
			"versionNonce": 1765087760,
			"isDeleted": false,
			"id": "X5qWmd2Z",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3645.406257532475,
			"y": -3285.3852857539546,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.339981079101562,
			"height": 25,
			"seed": 1767087856,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "LccYcF7bVxUvZnISnVNaF",
					"type": "arrow"
				}
			],
			"updated": 1703931097091,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "a",
			"rawText": "a",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "a",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 26,
			"versionNonce": 1137528560,
			"isDeleted": false,
			"id": "hDlEXOfL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3732.945449727291,
			"y": -3283.4985225612677,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 293016080,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 18,
			"versionNonce": 631724048,
			"isDeleted": false,
			"id": "lK7XNaJP",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3479.926165670955,
			"y": -3273.139250745631,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 69803248,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 18,
			"versionNonce": 1831203056,
			"isDeleted": false,
			"id": "o3dlzsbZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3660.2654414796825,
			"y": -3431.580185920442,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 1340335632,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3387,
			"versionNonce": 1428280848,
			"isDeleted": false,
			"id": "3_oTcdiCRRvwjN-skMact",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -3625.0460526337583,
			"y": -3439.367370628967,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 254627344,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 37,
			"versionNonce": 1729778416,
			"isDeleted": false,
			"id": "e1KYbaHN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3605.5283169019062,
			"y": -3439.363260989067,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 67.91990661621094,
			"height": 25,
			"seed": 533924080,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t - a)",
			"rawText": "(t - a)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t - a)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 77,
			"versionNonce": 1822200848,
			"isDeleted": false,
			"id": "AUtI4HIo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4689.9580020575195,
			"y": -3219.1458873064003,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 322.9996032714844,
			"height": 25,
			"seed": 944413424,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t) As a limiting case of a pulse",
			"rawText": "(t) As a limiting case of a pulse",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t) As a limiting case of a pulse",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3446,
			"versionNonce": 674395376,
			"isDeleted": false,
			"id": "9KQuVV8TclzGNMXAeOUjK",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4705.502984054621,
			"y": -3215.8841307799094,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 2096489200,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 48,
			"versionNonce": 34574864,
			"isDeleted": false,
			"id": "9uJ4VFXf",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4216.595628244466,
			"y": -3259.477160571731,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 114.61985778808594,
			"height": 25,
			"seed": 125075696,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Unit impulse",
			"rawText": "Unit impulse",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Unit impulse",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 48,
			"versionNonce": 368465648,
			"isDeleted": false,
			"id": "js7g15UA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3736.610399565906,
			"y": -3247.1401602740525,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 198.53976440429688,
			"height": 25,
			"seed": 1440670736,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Delayed unit impulse",
			"rawText": "Delayed unit impulse",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Delayed unit impulse",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 213,
			"versionNonce": 745721872,
			"isDeleted": false,
			"id": "rKYJJPhl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4709.770194906002,
			"y": -3142.0571680816297,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1273.7786865234375,
			"height": 50,
			"seed": 993572368,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "If the unit impulse function is assumed in the form of a pulse, then the following points may be observed about the unit impulse\nfunction:",
			"rawText": "If the unit impulse function is assumed in the form of a pulse, then the following points may be observed about the unit impulse\nfunction:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "If the unit impulse function is assumed in the form of a pulse, then the following points may be observed about the unit impulse\nfunction:",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "text",
			"version": 328,
			"versionNonce": 619575536,
			"isDeleted": false,
			"id": "ivsu2vEB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4679.199725191336,
			"y": -3077.741327775266,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 766.3192138671875,
			"height": 100,
			"seed": 1751276560,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1. The width of the pulse is zero. This means the pulse exists only at t = 0\n2. The height of the pulse the to infinity.\n3. The area under the pulse is always unity.\n4. the height of arrow indicates the total area under the impulse.",
			"rawText": "1. The width of the pulse is zero. This means the pulse exists only at t = 0\n2. The height of the pulse the to infinity.\n3. The area under the pulse is always unity.\n4. the height of arrow indicates the total area under the impulse.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1. The width of the pulse is zero. This means the pulse exists only at t = 0\n2. The height of the pulse the to infinity.\n3. The area under the pulse is always unity.\n4. the height of arrow indicates the total area under the impulse.",
			"lineHeight": 1.25,
			"baseline": 91
		},
		{
			"type": "text",
			"version": 186,
			"versionNonce": 1673416208,
			"isDeleted": false,
			"id": "O1oipscA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4706.686455872533,
			"y": -2950.614780697036,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1215.078857421875,
			"height": 50,
			"seed": 1980457488,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The integral of the unit impulse function is a unit step function and the derivative of unit step function is a unit impulse\nfunction:",
			"rawText": "The integral of the unit impulse function is a unit step function and the derivative of unit step function is a unit impulse\nfunction:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The integral of the unit impulse function is a unit step function and the derivative of unit step function is a unit impulse\nfunction:",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "text",
			"version": 96,
			"versionNonce": 2023840496,
			"isDeleted": false,
			"id": "mBTQRlQF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4203.790239259375,
			"y": -2877.4447234878467,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.05990600585938,
			"height": 25,
			"seed": 2080718864,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "u(t) = ",
			"rawText": "u(t) = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "u(t) = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 126,
			"versionNonce": 1625951248,
			"isDeleted": false,
			"id": "kAFAlUUq",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4045.5264651560624,
			"y": -2785.5746829757704,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.71995544433594,
			"height": 25,
			"seed": 453122800,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "u(t)",
			"rawText": "u(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "u(t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3365,
			"versionNonce": 60325104,
			"isDeleted": false,
			"id": "I0ECnQadh657w3mT81zDs",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4090.179943332576,
			"y": -2896.038977395771,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 117040656,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3394,
			"versionNonce": 2112752144,
			"isDeleted": false,
			"id": "6pjcZAC9L1A2keXnVryYI",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4088.7143367924327,
			"y": -2835.949534556507,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 1223861264,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 4749,
			"versionNonce": 660299504,
			"isDeleted": false,
			"id": "ehGD6wTWxtEc77jsErtMa",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4112.102860093602,
			"y": -2890.6910644760615,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 153330192,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 214,
			"versionNonce": 365053968,
			"isDeleted": false,
			"id": "b6KFQw1Rc_WeUQCwoGDfR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4120.798686496299,
			"y": -2837.558878068718,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.724738906051243,
			"height": 0,
			"seed": 1451548688,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					11.724738906051243,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3352,
			"versionNonce": 1416757488,
			"isDeleted": false,
			"id": "oEGiU8NfhYmFlE32qLBoL",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4067.0142806255517,
			"y": -2875.49966225405,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 554589712,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 165,
			"versionNonce": 1683932688,
			"isDeleted": false,
			"id": "6dJIgo4b",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4056.356230616302,
			"y": -2871.799376679434,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 59.03993225097656,
			"height": 25,
			"seed": 431496208,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097092,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t) dt",
			"rawText": "(t) dt",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t) dt",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 56,
			"versionNonce": 711222000,
			"isDeleted": false,
			"id": "BvUQapzT",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4075.588584353877,
			"y": -2794.9557268390377,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.379989624023438,
			"height": 25,
			"seed": 1328978160,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "d",
			"rawText": "d",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "d",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 62,
			"versionNonce": 1723565072,
			"isDeleted": false,
			"id": "TkAqdEUz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4074.391569202254,
			"y": -2766.7251170867685,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 22.679977416992188,
			"height": 25,
			"seed": 860422896,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dt",
			"rawText": "dt",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dt",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 65,
			"versionNonce": 398099696,
			"isDeleted": false,
			"id": "pUSboBGhsm-B0QcTtuNv1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4086.843075328283,
			"y": -2769.4765347542834,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 38.60725696025338,
			"height": 0,
			"seed": 267354640,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					38.60725696025338,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3403,
			"versionNonce": 986743312,
			"isDeleted": false,
			"id": "eH64t8MZL2DVicr6A40To",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4163.820376499541,
			"y": -2775.6794232057173,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1374276848,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 50,
			"versionNonce": 2046584560,
			"isDeleted": false,
			"id": "62zS6P9q",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4146.020670452502,
			"y": -2777.9603361768227,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 58.699920654296875,
			"height": 25,
			"seed": 1256445168,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t) = ",
			"rawText": "(t) = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t) = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 19,
			"versionNonce": 2140520464,
			"isDeleted": false,
			"id": "qPgnsmUL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4681.425042588235,
			"y": -2816.9626345449033,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 38.89996337890625,
			"height": 25,
			"seed": 118301936,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "and:",
			"rawText": "and:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "and:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 136,
			"versionNonce": 1035077872,
			"isDeleted": false,
			"id": "E77RbNdZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4423.309060007585,
			"y": -2684.4520144076373,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 660.9393920898438,
			"height": 25,
			"seed": 60675088,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "PROPERTIES OF CONTINUOUS-TIME UNIT IMPULSE FUNCTION",
			"rawText": "PROPERTIES OF CONTINUOUS-TIME UNIT IMPULSE FUNCTION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "PROPERTIES OF CONTINUOUS-TIME UNIT IMPULSE FUNCTION",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 96,
			"versionNonce": 889404944,
			"isDeleted": false,
			"id": "jP7g3ulNsmEV27bDfdMwC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4464.460537519084,
			"y": -2648.8450199158056,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 773.1760100224883,
			"height": 0,
			"seed": 2098998512,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					773.1760100224883,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 103,
			"versionNonce": 2120444656,
			"isDeleted": false,
			"id": "T8XlxnLG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4656.064825231848,
			"y": -2621.3318496183742,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 524.99951171875,
			"height": 25,
			"seed": 844182032,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1. It is an even function of time t, i.e,   (t) =   (-t)",
			"rawText": "1. It is an even function of time t, i.e,   (t) =   (-t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1. It is an even function of time t, i.e,   (t) =   (-t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3436,
			"versionNonce": 470875152,
			"isDeleted": false,
			"id": "fthQebbS2ZC2JJfblrJYM",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4257.628951977402,
			"y": -2617.5972835565394,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 997052432,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3445,
			"versionNonce": 647531760,
			"isDeleted": false,
			"id": "NJ5DCdRVwPLgTArZERti4",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4179.790264193651,
			"y": -2621.7857090050347,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1821211888,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 17,
			"versionNonce": 381090320,
			"isDeleted": false,
			"id": "hodIcEDd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4656.646593005612,
			"y": -2562.7106161167017,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.719985961914062,
			"height": 25,
			"seed": 174609648,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2.",
			"rawText": "2.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2.",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3396,
			"versionNonce": 265907952,
			"isDeleted": false,
			"id": "CuIXy31HcuEypqHhuut_f",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4582.842470846396,
			"y": -2579.4880386721443,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 144272112,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3425,
			"versionNonce": 132986896,
			"isDeleted": false,
			"id": "HXORr30jeTi8eRd_Fup_N",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4581.376864306253,
			"y": -2519.3985958328803,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 2047773936,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 4780,
			"versionNonce": 581832944,
			"isDeleted": false,
			"id": "6PavZmi82N7J_hw-7LGXU",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4604.765387607423,
			"y": -2574.140125752435,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 76508912,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 245,
			"versionNonce": 866891280,
			"isDeleted": false,
			"id": "9YBQGgBrRN09DIjiD_k3K",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4613.461214010119,
			"y": -2521.0079393450915,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.724738906051243,
			"height": 0,
			"seed": 279187696,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					11.724738906051243,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3397,
			"versionNonce": 1990095600,
			"isDeleted": false,
			"id": "SDXseyFL5CDIFD4POZ_nb",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4524.927339178001,
			"y": -2563.2924439154945,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 903115504,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 229,
			"versionNonce": 518681616,
			"isDeleted": false,
			"id": "CgpusKyt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4512.097428976215,
			"y": -2563.9357946918935,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 136.59983825683594,
			"height": 25,
			"seed": 1520997616,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t) dt = x(0);",
			"rawText": "(t) dt = x(0);",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t) dt = x(0);",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 62,
			"versionNonce": 1915917552,
			"isDeleted": false,
			"id": "MpPLEC5V",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4575.375156027243,
			"y": -2565.753993510121,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.59996032714844,
			"height": 25,
			"seed": 715763216,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(t)",
			"rawText": "x(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3419,
			"versionNonce": 1872851472,
			"isDeleted": false,
			"id": "KpSF47WlBlPyNNlDxVDSA",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4273.9681752618835,
			"y": -2579.074555694232,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 791606800,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097093,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3448,
			"versionNonce": 1794275056,
			"isDeleted": false,
			"id": "rVI2s7jNM8rhojBjItEQn",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4272.50256872174,
			"y": -2518.985112854968,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 1208333328,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 4804,
			"versionNonce": 1288220688,
			"isDeleted": false,
			"id": "6g1Hwam1CuvBXAYZOd5__",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4295.89109202291,
			"y": -2573.7266427745226,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 1398059536,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 268,
			"versionNonce": 1164318960,
			"isDeleted": false,
			"id": "6mm5ovV2Fn-ZUeO1kdb70",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4304.586918425606,
			"y": -2520.594456367179,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.724738906051243,
			"height": 0,
			"seed": 1477701648,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					11.724738906051243,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3426,
			"versionNonce": 1045966352,
			"isDeleted": false,
			"id": "yBf0yF7G1nMKpWAC55vjW",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4227.353034742757,
			"y": -2558.535240552511,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1044082192,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 256,
			"versionNonce": 353729264,
			"isDeleted": false,
			"id": "r9xn1SVB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4218.160534566104,
			"y": -2560.6973244309206,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 190.65975952148438,
			"height": 25,
			"seed": 784542736,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t - to) dt = x(to)",
			"rawText": "(t - to) dt = x(to)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t - to) dt = x(to)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 32,
			"versionNonce": 222817296,
			"isDeleted": false,
			"id": "sB1XeCW4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4275.2992556168,
			"y": -2561.8028309621354,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.59996032714844,
			"height": 25,
			"seed": 964502256,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(t)",
			"rawText": "x(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 27,
			"versionNonce": 1015586032,
			"isDeleted": false,
			"id": "TczP3JWl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4656.372664044376,
			"y": -2485.8656419848244,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.0999755859375,
			"height": 25,
			"seed": 72034544,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "3.",
			"rawText": "3.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3.",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3417,
			"versionNonce": 596634128,
			"isDeleted": false,
			"id": "HNd5_2En1ofCFrGYtIu-y",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4612.462743251404,
			"y": -2482.914950327117,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 2062800112,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 45,
			"versionNonce": 222789360,
			"isDeleted": false,
			"id": "465LRtCB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4595.62793715115,
			"y": -2481.7174282483957,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87.45988464355469,
			"height": 25,
			"seed": 1570264592,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(at) =  1",
			"rawText": "(at) =  1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(at) =  1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 39,
			"versionNonce": 1814571024,
			"isDeleted": false,
			"id": "RPSUBNWqvW73zq1AnK7Nk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4522.169888693165,
			"y": -2459.1720955582146,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 23.44950616587539,
			"height": 0,
			"seed": 509218032,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					23.44950616587539,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 31,
			"versionNonce": 1742348528,
			"isDeleted": false,
			"id": "M0wa47m9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4518.683423671002,
			"y": -2452.3789851439437,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.059982299804688,
			"height": 25,
			"seed": 1411026160,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "|a|",
			"rawText": "|a|",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "|a|",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3424,
			"versionNonce": 856204816,
			"isDeleted": false,
			"id": "wi1txSBv84GTzFnC50wp6",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4486.105627085661,
			"y": -2469.41027495049,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1220197616,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 24,
			"versionNonce": 1539867376,
			"isDeleted": false,
			"id": "KfJUoMAE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4470.945990263763,
			"y": -2468.854115223057,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 26.359970092773438,
			"height": 25,
			"seed": 1308643568,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t)",
			"rawText": "(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 178,
			"versionNonce": 86598672,
			"isDeleted": false,
			"id": "1IBqd2hO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4686.377505881909,
			"y": -2177.9436076035795,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 924.2991333007812,
			"height": 25,
			"seed": 1953288944,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The discrete-time unit impulse function   [n], also called unit sample sequence, is defined as:",
			"rawText": "The discrete-time unit impulse function   [n], also called unit sample sequence, is defined as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The discrete-time unit impulse function   [n], also called unit sample sequence, is defined as:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3498,
			"versionNonce": 1201317104,
			"isDeleted": false,
			"id": "n5wfL4hk67NUhKGN8BF4v",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4288.378604447912,
			"y": -2178.391909577507,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1509894896,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3452,
			"versionNonce": 276980240,
			"isDeleted": false,
			"id": "ajEQKzrPzS0o2lAE2slnb",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4299.868715880186,
			"y": -2098.7399226419193,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1199920656,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3454,
			"versionNonce": 2027456240,
			"isDeleted": false,
			"id": "o1f9d6yXHdSiY-buZXe5j",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4344.438777629601,
			"y": -2010.7494312339443,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 308991728,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3456,
			"versionNonce": 67870736,
			"isDeleted": false,
			"id": "rASUPBbYH8FUm6bPE1uWg",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4290.211732597134,
			"y": -1931.8935615441314,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1696435216,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 41,
			"versionNonce": 1275734256,
			"isDeleted": false,
			"id": "L6sO5gQI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4283.531291670571,
			"y": -2096.286328407494,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 61.49992370605469,
			"height": 25,
			"seed": 1966015504,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097094,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "[n] = ",
			"rawText": "[n] = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[n] = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 88,
			"versionNonce": 1874664976,
			"isDeleted": false,
			"id": "ISCTgalB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4185.91046952642,
			"y": -2122.693671846753,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 134.5198516845703,
			"height": 75,
			"seed": 778499824,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "sZMbm80rvV8b-pspaUBxn",
					"type": "arrow"
				},
				{
					"id": "ZIu1Hhos2OYZp2cVosDhD",
					"type": "arrow"
				}
			],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1   for n = 0\n\n0  for n != 0",
			"rawText": "1   for n = 0\n\n0  for n != 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1   for n = 0\n\n0  for n != 0",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "arrow",
			"version": 30,
			"versionNonce": 1287097072,
			"isDeleted": false,
			"id": "sZMbm80rvV8b-pspaUBxn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4189.46265859501,
			"y": -2111.8292431291525,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.17427342569954,
			"height": 19.052771606765873,
			"seed": 197999120,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ISCTgalB",
				"focus": 0.8790745907648151,
				"gap": 3.552189068590451
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-35.17427342569954,
					19.052771606765873
				]
			]
		},
		{
			"type": "arrow",
			"version": 27,
			"versionNonce": 613342224,
			"isDeleted": false,
			"id": "ZIu1Hhos2OYZp2cVosDhD",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4193.859421507893,
			"y": -2060.5334111769725,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 30.77751051281666,
			"height": 24.91508435224523,
			"seed": 1287156976,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ISCTgalB",
				"focus": -0.93034263329476,
				"gap": 7.9489519814733285
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-30.77751051281666,
					-24.91508435224523
				]
			]
		},
		{
			"type": "text",
			"version": 101,
			"versionNonce": 1432923376,
			"isDeleted": false,
			"id": "NGSyDtT5",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4676.498370785314,
			"y": -2012.2360474552668,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 553.0994262695312,
			"height": 25,
			"seed": 1376616176,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The shifted unit impulse function  [n - k] is defined as:",
			"rawText": "The shifted unit impulse function  [n - k] is defined as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The shifted unit impulse function  [n - k] is defined as:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 31,
			"versionNonce": 343464464,
			"isDeleted": false,
			"id": "VFNtIkV5",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4267.683460471201,
			"y": -1926.4056599098249,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 99.45986938476562,
			"height": 25,
			"seed": 1372533776,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "[n - k] = ",
			"rawText": "[n - k] = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[n - k] = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 799379184,
			"isDeleted": false,
			"id": "QQTnyRzm",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4144.650143730391,
			"y": -1949.4500757170422,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 130.49984741210938,
			"height": 75,
			"seed": 1470470672,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "1Kzrz2KQnRbB4mn6iKMyE",
					"type": "arrow"
				},
				{
					"id": "ZYpgH_lXr7BAP0MTziZkg",
					"type": "arrow"
				}
			],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1   for n = k\n\n0  for n != k",
			"rawText": "1   for n = k\n\n0  for n != k",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1   for n = k\n\n0  for n != k",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "arrow",
			"version": 26,
			"versionNonce": 846403600,
			"isDeleted": false,
			"id": "1Kzrz2KQnRbB4mn6iKMyE",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4152.631957735084,
			"y": -1937.4234825407966,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 23.449534519649205,
			"height": 16.121558526480385,
			"seed": 911224336,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "QQTnyRzm",
				"focus": 0.9206028673340986,
				"gap": 7.981814004692751
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-23.449534519649205,
					16.121558526480385
				]
			]
		},
		{
			"type": "arrow",
			"version": 22,
			"versionNonce": 871772400,
			"isDeleted": false,
			"id": "ZYpgH_lXr7BAP0MTziZkg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4148.235194822202,
			"y": -1889.0588636689026,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.5183214393619,
			"height": 19.05271489921961,
			"seed": 1176910064,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "QQTnyRzm",
				"focus": -0.8850044979974064,
				"gap": 3.585051091810783
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-20.5183214393619,
					-19.05271489921961
				]
			]
		},
		{
			"type": "text",
			"version": 104,
			"versionNonce": 1383437840,
			"isDeleted": false,
			"id": "kmeA2PeF",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4673.776862212107,
			"y": -1838.4950127273646,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 688.1393432617188,
			"height": 25,
			"seed": 1215214320,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The graphical representation of   [n] and   [n - 3] are shown below:",
			"rawText": "The graphical representation of   [n] and   [n - 3] are shown below:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The graphical representation of   [n] and   [n - 3] are shown below:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3458,
			"versionNonce": 1776456432,
			"isDeleted": false,
			"id": "EE2iIZ2BrkfdDud6_Iu8R",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4341.127482218676,
			"y": -1839.6268107596534,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 938998800,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3488,
			"versionNonce": 158880784,
			"isDeleted": false,
			"id": "UBm9DyaPYh2yDrebdg332",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4241.6093673363985,
			"y": -1839.888005718984,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 779555056,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 137,
			"versionNonce": 670217456,
			"isDeleted": false,
			"id": "txxMPsdJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4406.562015409058,
			"y": -1472.1557559927926,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 622.4793701171875,
			"height": 25,
			"seed": 146267664,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "PROPERTIES OF DISCRETE-TIME UNIT SAMPLE SEQUENCE",
			"rawText": "PROPERTIES OF DISCRETE-TIME UNIT SAMPLE SEQUENCE",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "PROPERTIES OF DISCRETE-TIME UNIT SAMPLE SEQUENCE",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "arrow",
			"version": 90,
			"versionNonce": 225661456,
			"isDeleted": false,
			"id": "7uvMPaWV7tALpZzR4WVhr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4661.911318468011,
			"y": -1596.703220933578,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 507.1740363603494,
			"height": 0,
			"seed": 134973968,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					507.1740363603494,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 119,
			"versionNonce": 867079920,
			"isDeleted": false,
			"id": "vLDbaLQ_4sHym3vn0aRnQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3986.8179008143798,
			"y": -1600.6923474990235,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 524.2667683287536,
			"height": 0,
			"seed": 121847824,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Zs3hUHQhWO36QjayaDC93",
				"focus": 0.23366267752385203,
				"gap": 2.1757023867841987
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					524.2667683287536,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 59,
			"versionNonce": 358518800,
			"isDeleted": false,
			"id": "SW-v3Wm1kqxES6tE4BmFF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4449.704385588239,
			"y": -1433.4104363137694,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 694.9307432170935,
			"height": 0,
			"seed": 742786288,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					694.9307432170935,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 89,
			"versionNonce": 1637759216,
			"isDeleted": false,
			"id": "w2AKJz5ByXIbaBESKzCIJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2129.015536127344,
			"y": -1055.1959545766636,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 617.9856962316176,
			"height": 83.51160386029392,
			"seed": 1227249168,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "DOfM1hI5A0MC6AWsUQ4Zb",
				"focus": -0.05673451220243234,
				"gap": 8.755576103470503
			},
			"endBinding": {
				"elementId": "GR0ouguJ0H8RzGgqmxOCR",
				"focus": -0.928511348411676,
				"gap": 29.601295894708755
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-409.021168428309,
					41.198974609375
				],
				[
					-617.9856962316176,
					83.51160386029392
				]
			]
		},
		{
			"type": "arrow",
			"version": 239,
			"versionNonce": 959581712,
			"isDeleted": false,
			"id": "_L-zlhOGSIF-EKKSaDcVE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2132.727191688006,
			"y": -1060.7634020146231,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1308.4530819163601,
			"height": 168.23760627297725,
			"seed": 314282512,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "DOfM1hI5A0MC6AWsUQ4Zb",
				"focus": -0.5059844453603178,
				"gap": 12.467231664132214
			},
			"endBinding": {
				"elementId": "tFJXLMdXeIN0EypMMFij_",
				"focus": -0.6540208370310413,
				"gap": 6.196637010136101
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-575.3019875919122,
					-71.63428452435664
				],
				[
					-1098.6412497127753,
					15.588946174172634
				],
				[
					-1308.4530819163601,
					96.6033217486206
				]
			]
		},
		{
			"type": "arrow",
			"version": 381,
			"versionNonce": 894016240,
			"isDeleted": false,
			"id": "dknBSVLuqmd_00LEBU8yf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2133.584864352407,
			"y": -1067.9877208291734,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1272.1052086871614,
			"height": 654.7979603643021,
			"seed": 2070256656,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "DOfM1hI5A0MC6AWsUQ4Zb",
				"focus": -0.6320066543022459,
				"gap": 13.324904328533194
			},
			"endBinding": {
				"elementId": "HGurlKY2fWES5yDTmKYwa",
				"focus": -0.4658107156388931,
				"gap": 19.759617054090995
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-509.99351435122344,
					-159.11580226732303
				],
				[
					-1176.2925962365198,
					-205.16723168414705
				],
				[
					-1272.1052086871614,
					-654.7979603643021
				]
			]
		},
		{
			"type": "ellipse",
			"version": 84,
			"versionNonce": 1374014480,
			"isDeleted": false,
			"id": "TlWHhxjekBP6qw-zSaeNa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4470.669679237327,
			"y": -1685.5849483555724,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 23.13578287760356,
			"height": 25.239054361979015,
			"seed": 1460978192,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 70,
			"versionNonce": 20495600,
			"isDeleted": false,
			"id": "IykKq6Zps7S4pZg3w50QX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4636.87949775946,
			"y": -1610.9653397943741,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 23.13578287760356,
			"height": 25.239054361979015,
			"seed": 1545411088,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 71,
			"versionNonce": 1500629520,
			"isDeleted": false,
			"id": "k3REtlrQql5WEp0mwBe0K",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4554.720155311546,
			"y": -1610.7207922683322,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 23.13578287760356,
			"height": 25.239054361979015,
			"seed": 1890734832,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 54,
			"versionNonce": 116629232,
			"isDeleted": false,
			"id": "zS_WTTzw9Z7vmlHamNi9J",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4402.982769243836,
			"y": -1608.0539628412496,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 23.13578287760356,
			"height": 25.239054361979015,
			"seed": 1314574352,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 75,
			"versionNonce": 1255016464,
			"isDeleted": false,
			"id": "BFvZWm77xCvHKOF6DExk1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4315.301494829774,
			"y": -1608.8239009922906,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 23.13578287760356,
			"height": 25.239054361979015,
			"seed": 238058736,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 45,
			"versionNonce": 386023664,
			"isDeleted": false,
			"id": "Zs3hUHQhWO36QjayaDC93",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3984.9176650771687,
			"y": -1616.260587190208,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 23.13578287760356,
			"height": 25.239054361979015,
			"seed": 1430701584,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "vLDbaLQ_4sHym3vn0aRnQ",
					"type": "arrow"
				}
			],
			"updated": 1703931097095,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 47,
			"versionNonce": 32671248,
			"isDeleted": false,
			"id": "2OBYTmXN4A2u2yOSOrF1E",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3904.203838579774,
			"y": -1616.2605058099998,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 23.13578287760356,
			"height": 25.239054361979015,
			"seed": 1704224496,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 43,
			"versionNonce": 820814576,
			"isDeleted": false,
			"id": "XjTnhy9m_oyOd-2s0ZFxj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3815.6404433974812,
			"y": -1614.3638586745828,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 23.13578287760356,
			"height": 25.239054361979015,
			"seed": 2079915024,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 45,
			"versionNonce": 467092496,
			"isDeleted": false,
			"id": "vGG_O2yWM3D5nFwND9JUK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3725.8941055068576,
			"y": -1616.4670487787496,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 23.13578287760356,
			"height": 25.239054361979015,
			"seed": 1329991920,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 49,
			"versionNonce": 591054064,
			"isDeleted": false,
			"id": "px3b1yO3rAw4NSdfHUU0d",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3652.5226048558147,
			"y": -1694.3256099766663,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 23.13578287760356,
			"height": 25.239054361979015,
			"seed": 1586065936,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 83,
			"versionNonce": 1450459664,
			"isDeleted": false,
			"id": "8glT1rrQtCpB8GHwp2pmw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3563.977194699565,
			"y": -1610.9092281407286,
			"strokeColor": "#f08c00",
			"backgroundColor": "#ffec99",
			"width": 23.13578287760356,
			"height": 25.239054361979015,
			"seed": 1655536368,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 60,
			"versionNonce": 729065200,
			"isDeleted": false,
			"id": "9BUrQ7vfi5KAlp1650njt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4460.153362505555,
			"y": -1658.242622509218,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 0,
			"height": 65.20084635416674,
			"seed": 332434960,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					65.20084635416674
				]
			]
		},
		{
			"type": "line",
			"version": 69,
			"versionNonce": 1891729424,
			"isDeleted": false,
			"id": "TA3xQk1FYkMwvdlf1Vtp_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3642.276408200466,
			"y": -1664.9009696251321,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 0,
			"height": 65.20084635416674,
			"seed": 2121357552,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097095,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					65.20084635416674
				]
			]
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 371345648,
			"isDeleted": false,
			"id": "QuouKirz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4496.842490109724,
			"y": -1683.8093542800511,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 699652112,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 179764752,
			"isDeleted": false,
			"id": "3m4ajBwB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3680.842490109724,
			"y": -1690.4760209467179,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 2083092720,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3475,
			"versionNonce": 1590405872,
			"isDeleted": false,
			"id": "8xL4TwKnjet37qbWobdPy",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4420.911762720438,
			"y": -1690.601069189459,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 208659184,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 32,
			"versionNonce": 88914960,
			"isDeleted": false,
			"id": "PmaCaMsE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4402.795330278994,
			"y": -1692.166247183697,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 29.15997314453125,
			"height": 25,
			"seed": 781077008,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "[n]",
			"rawText": "[n]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[n]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3466,
			"versionNonce": 1341705456,
			"isDeleted": false,
			"id": "nJaaX7jtxx_1rs2xUhYZ2",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -3614.8466585537744,
			"y": -1699.8221792155005,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 624317168,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 29,
			"versionNonce": 1652210192,
			"isDeleted": false,
			"id": "v7XfHOAx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3592.128622922227,
			"y": -1704.4289018060927,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 70.99990844726562,
			"height": 25,
			"seed": 411989008,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "[n - 3]",
			"rawText": "[n - 3]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[n - 3]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 32,
			"versionNonce": 590458608,
			"isDeleted": false,
			"id": "0C9goRS4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4469.255515012071,
			"y": -1570.6825639154679,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 1903298576,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 25,
			"versionNonce": 624490512,
			"isDeleted": false,
			"id": "cW52dHVj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4394.025432818061,
			"y": -1563.8655066238014,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 627408912,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 553537776,
			"isDeleted": false,
			"id": "iZBDS1zb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4303.208375526394,
			"y": -1559.8093542800511,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 14.239990234375,
			"height": 25,
			"seed": 1742534672,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 18,
			"versionNonce": 830436880,
			"isDeleted": false,
			"id": "TlA7zd4e",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4549.255515012071,
			"y": -1566.4760209467179,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 13.639984130859375,
			"height": 25,
			"seed": 1457025040,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-1",
			"rawText": "-1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 14,
			"versionNonce": 1088860912,
			"isDeleted": false,
			"id": "UI73ASBg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4635.509156776394,
			"y": -1567.8093542800511,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 22.459976196289062,
			"height": 25,
			"seed": 994076176,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-2",
			"rawText": "-2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 742798352,
			"isDeleted": false,
			"id": "wdvN2zVp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4170.175823443064,
			"y": -1574.4760209467179,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 9.339996337890625,
			"height": 25,
			"seed": 876045552,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "n",
			"rawText": "n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "n",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 24,
			"versionNonce": 1232262384,
			"isDeleted": false,
			"id": "CCshRla6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3468.84249010973,
			"y": -1584.2784298008846,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 9.339996337890625,
			"height": 25,
			"seed": 2070419984,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "n",
			"rawText": "n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "n",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 21,
			"versionNonce": 1535455760,
			"isDeleted": false,
			"id": "Tbg12d4T",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3986.025392127959,
			"y": -1569.9126257644261,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 13.639984130859375,
			"height": 25,
			"seed": 530947312,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-1",
			"rawText": "-1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 25,
			"versionNonce": 1881847536,
			"isDeleted": false,
			"id": "LZM8Yle1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3899.6595474013966,
			"y": -1571.8654252435929,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 1238730480,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 25,
			"versionNonce": 104099856,
			"isDeleted": false,
			"id": "dqC801Lu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3804.84249010973,
			"y": -1568.0720495925514,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 1188245744,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 31,
			"versionNonce": 2039896304,
			"isDeleted": false,
			"id": "bb6O7wdA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3720.0725519586886,
			"y": -1565.5557735508846,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 14.239990234375,
			"height": 25,
			"seed": 503003376,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 16,
			"versionNonce": 1414262288,
			"isDeleted": false,
			"id": "AaMVBPYv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3644.84249010973,
			"y": -1569.9126257644261,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 13.619979858398438,
			"height": 25,
			"seed": 903333104,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "3",
			"rawText": "3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 19,
			"versionNonce": 1497217776,
			"isDeleted": false,
			"id": "8ZJwIjOr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3556.4294855524386,
			"y": -1568.0158158685927,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 1507545328,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "4",
			"rawText": "4",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3477,
			"versionNonce": 784575504,
			"isDeleted": false,
			"id": "F8yrAWaLkL0HQg2wZ4vXx",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4594.681094467551,
			"y": -1381.4108429524724,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 852530416,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 52,
			"versionNonce": 1370021104,
			"isDeleted": false,
			"id": "OYyKMZ7U",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4576.564662026107,
			"y": -1382.9760209467106,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 204.39974975585938,
			"height": 25,
			"seed": 1741715184,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "[n] = u[n] - u[n - 1]",
			"rawText": "[n] = u[n] - u[n - 1]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[n] = u[n] - u[n - 1]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3477,
			"versionNonce": 529771024,
			"isDeleted": false,
			"id": "Pad9DJIMHSC6KNpbouunG",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -3940.0144278008847,
			"y": -1400.077509619139,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 723877616,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 41,
			"versionNonce": 341819120,
			"isDeleted": false,
			"id": "k4RBylN8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3921.8979953594408,
			"y": -1401.6426876133767,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 99.45986938476562,
			"height": 25,
			"seed": 435691760,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "[n - k] = ",
			"rawText": "[n - k] = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[n - k] = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3548,
			"versionNonce": 833873936,
			"isDeleted": false,
			"id": "cJe0BpNQ4SfMrKxQ7KWHC",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -3829.368024806093,
			"y": -1276.1718292805974,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 705536016,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 1642750192,
			"isDeleted": false,
			"id": "f70y0saV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3897.4849908021492,
			"y": -1279.840197379002,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 242.01971435546875,
			"height": 25,
			"seed": 92216848,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x[n]    [n - no] = x[no]",
			"rawText": "x[n]    [n - no] = x[no]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x[n]    [n - no] = x[no]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3537,
			"versionNonce": 1360815632,
			"isDeleted": false,
			"id": "gvpl5rHOgs9JvfgkPIbN6",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4401.462263087342,
			"y": -1309.428827978514,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1746153712,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 93,
			"versionNonce": 701547248,
			"isDeleted": false,
			"id": "qiJ7XiUs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4381.242559161525,
			"y": -1310.9940873529604,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 67.11991882324219,
			"height": 25,
			"seed": 1782616816,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "[n - k]",
			"rawText": "[n - k]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[n - k]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 28,
			"versionNonce": 717562896,
			"isDeleted": false,
			"id": "f7PgNdo9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4632.222962928742,
			"y": -1387.4524206862934,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 10.899993896484375,
			"height": 25,
			"seed": 1966662896,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1.",
			"rawText": "1.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1.",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 51,
			"versionNonce": 714794224,
			"isDeleted": false,
			"id": "670EGwcb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3795.001913937856,
			"y": -1423.0955684727521,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 120.49986267089844,
			"height": 75,
			"seed": 2145575952,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097096,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1  for n = k\n\n0 for n != k",
			"rawText": "1  for n = k\n\n0 for n != k",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1  for n = k\n\n0 for n != k",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 212214288,
			"isDeleted": false,
			"id": "eHrl2IE6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4606.945720904003,
			"y": -1310.9070105300436,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 72.73991394042969,
			"height": 25,
			"seed": 599584784,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x[n] = ",
			"rawText": "x[n] = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x[n] = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 64,
			"versionNonce": 298895088,
			"isDeleted": false,
			"id": "SgAD8UNj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4461.500164263378,
			"y": -1311.733019644627,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 40.799957275390625,
			"height": 25,
			"seed": 26451696,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x[k]",
			"rawText": "x[k]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x[k]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 14,
			"versionNonce": 1169645584,
			"isDeleted": false,
			"id": "r1AjENTd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3982.1758234430645,
			"y": -1402.4760209467104,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 19.719985961914062,
			"height": 25,
			"seed": 2087765744,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2.",
			"rawText": "2.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2.",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 59,
			"versionNonce": 469395696,
			"isDeleted": false,
			"id": "O7neNGxr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3990.3822850316064,
			"y": -1281.8564734206684,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 18.279983520507812,
			"height": 25,
			"seed": 1850397424,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "4.",
			"rawText": "4.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4.",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 59,
			"versionNonce": 99671568,
			"isDeleted": false,
			"id": "z26NGnhv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4644.429444862336,
			"y": -1313.0663529779602,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 19.0999755859375,
			"height": 25,
			"seed": 777196784,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "3.",
			"rawText": "3.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3.",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 1871,
			"versionNonce": 882887408,
			"isDeleted": false,
			"id": "9RwAPVpHD2Y1YcX4N5FQs",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4493.151113761904,
			"y": -1318.9953168673492,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 20.3192084036864,
			"height": 32.618601391763576,
			"seed": 29220368,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.843215143654266,
					0.18480793989663538
				],
				[
					9.8366007463286,
					2.1562530948622793
				],
				[
					-5.484077008607414,
					2.757119593628204
				],
				[
					-6.257472484180191,
					5.636642166848667
				],
				[
					2.0389517083284083,
					15.431462981372556
				],
				[
					2.3201864267185357,
					19.035217809357736
				],
				[
					-4.99191625142479,
					26.797151285018206
				],
				[
					-6.538707202570457,
					30.40090611300341
				],
				[
					9.913523823251808,
					30.46234829690127
				],
				[
					9.91352382325178,
					32.618601391763576
				],
				[
					-10.405684580434592,
					32.156581542021826
				],
				[
					-6.819941920960652,
					25.873111585534826
				],
				[
					-0.0703086795975878,
					18.850409869461078
				],
				[
					-0.4921607571828126,
					15.708674891217575
				],
				[
					-9.843215143654337,
					4.43539055752022
				],
				[
					-8.858893629288854,
					1.1088476393800382
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1855,
			"versionNonce": 1045077008,
			"isDeleted": false,
			"id": "HtBAIEStBlZMY41pcTCMZ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -3925.3177956873615,
			"y": -1285.7712669812815,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 20.3192084036864,
			"height": 32.618601391763576,
			"seed": 999242256,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.843215143654266,
					0.18480793989663538
				],
				[
					9.8366007463286,
					2.1562530948622793
				],
				[
					-5.484077008607414,
					2.757119593628204
				],
				[
					-6.257472484180191,
					5.636642166848667
				],
				[
					2.0389517083284083,
					15.431462981372556
				],
				[
					2.3201864267185357,
					19.035217809357736
				],
				[
					-4.99191625142479,
					26.797151285018206
				],
				[
					-6.538707202570457,
					30.40090611300341
				],
				[
					9.913523823251808,
					30.46234829690127
				],
				[
					9.91352382325178,
					32.618601391763576
				],
				[
					-10.405684580434592,
					32.156581542021826
				],
				[
					-6.819941920960652,
					25.873111585534826
				],
				[
					-0.0703086795975878,
					18.850409869461078
				],
				[
					-0.4921607571828126,
					15.708674891217575
				],
				[
					-9.843215143654337,
					4.43539055752022
				],
				[
					-8.858893629288854,
					1.1088476393800382
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 17,
			"versionNonce": 373878000,
			"isDeleted": false,
			"id": "IJvEcpHO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4508.842490109732,
			"y": -1267.809354280044,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 50.2999267578125,
			"height": 25,
			"seed": 564749040,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "k = -",
			"rawText": "k = -",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "k = -",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 23,
			"versionNonce": 12360208,
			"isDeleted": false,
			"id": "MssiayQj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3943.5091567763993,
			"y": -1243.809354280044,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 49.899932861328125,
			"height": 25,
			"seed": 64460016,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "n = -",
			"rawText": "n = -",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "n = -",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3260,
			"versionNonce": 1786629872,
			"isDeleted": false,
			"id": "ErBv626_A8gTBL1OtWv2r",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4440.0824219482365,
			"y": -1254.5919443234327,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 1646760688,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3254,
			"versionNonce": 1614731280,
			"isDeleted": false,
			"id": "zYM5Wbowamb4tWYSoK0jO",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -3924.2289419270787,
			"y": -1301.0850168331983,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 932442640,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3258,
			"versionNonce": 1774612720,
			"isDeleted": false,
			"id": "f9gGpBsE6shoLG8vXDbqI",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4498.659809440098,
			"y": -1337.2533924842398,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 1546320624,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3247,
			"versionNonce": 1355372048,
			"isDeleted": false,
			"id": "KCcFeYRfN0JozYl8c0SC7",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -3869.2031037109314,
			"y": -1232.090632067573,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 754777840,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 124,
			"versionNonce": 2074792688,
			"isDeleted": false,
			"id": "T1kRy3Lf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4644.842490109731,
			"y": -2386.476020946716,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 786.63916015625,
			"height": 25,
			"seed": 2007684624,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "4  x(t)   (t - to) = x(to)   (t - to)  = x(to);   x(t)   (t) = x(0)   (t) = x(0)",
			"rawText": "4  x(t)   (t - to) = x(to)   (t - to)  = x(to);   x(t)   (t) = x(0)   (t) = x(0)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4  x(t)   (t - to) = x(to)   (t - to)  = x(to);   x(t)   (t) = x(0)   (t) = x(0)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 54,
			"versionNonce": 122950672,
			"isDeleted": false,
			"id": "jjv4MEb4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dotted",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4636.842490109731,
			"y": -2297.142687613383,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 348.279541015625,
			"height": 25,
			"seed": 1826478320,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "5.  x(t) =       x(T)   (t - T) dT",
			"rawText": "5.  x(t) =       x(T)   (t - T) dT",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "5.  x(t) =       x(T)   (t - T) dT",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3442,
			"versionNonce": 1454568688,
			"isDeleted": false,
			"id": "BhVRw8finhJBTeuOQMbcR",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4508.042022137346,
			"y": -2321.1971210653364,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 2115041296,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3486,
			"versionNonce": 1507267088,
			"isDeleted": false,
			"id": "1_PzpjsqxlJKbbjoD_io8",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4485.543822823765,
			"y": -2254.7979451531546,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 794261008,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 4873,
			"versionNonce": 543610608,
			"isDeleted": false,
			"id": "LmsQaRjV2EI9MpikD0jFI",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4504.725884536391,
			"y": -2307.436122208127,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 11.509261779512075,
			"height": 41.589456947420416,
			"seed": 790508560,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					4.398532809084827,
					40.066834098759045
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3356,
			"versionNonce": 524963856,
			"isDeleted": false,
			"id": "MRp4EMqtyDAeUeP_1Lisx",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4414.734435246486,
			"y": -2291.052241064457,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1171489520,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 34,
			"versionNonce": 223246576,
			"isDeleted": false,
			"id": "bHd_HVA-MG0o7U0ULzW8n",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4526.5372329482725,
			"y": -2255.5557735508833,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 21.03257242838572,
			"height": 0,
			"seed": 558512368,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					21.03257242838572,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3359,
			"versionNonce": 262524432,
			"isDeleted": false,
			"id": "NqDeER_Ko1_7bDWckxmNJ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4563.861266301174,
			"y": -2383.822179215499,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1376356880,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3362,
			"versionNonce": 15850224,
			"isDeleted": false,
			"id": "80eb3PCVV3UCer4Biryn4",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4372.9880566657575,
			"y": -2385.718907731124,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 178316016,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3356,
			"versionNonce": 601984016,
			"isDeleted": false,
			"id": "wQ8HkgtShr1pSikLk0wZC",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -4105.401101913154,
			"y": -2383.052241064458,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1384202256,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3356,
			"versionNonce": 769195248,
			"isDeleted": false,
			"id": "XUQfh_6EErQBPvQZsa8WL",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -3973.401101913154,
			"y": -2381.718907731124,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.854407807242281,
			"height": 15.530247465744933,
			"seed": 1359285488,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.47861379166329243,
					0.6148976118180371
				],
				[
					2.7459702869508646,
					0.21920164769727535
				],
				[
					5.9336578619901275,
					3.602587401808762
				],
				[
					6.4741861962107645,
					9.399942173055843
				],
				[
					4.825584137230446,
					13.36096134384025
				],
				[
					0.9352144567093226,
					13.640128174232249
				],
				[
					0.03863248027629207,
					10.456580617725495
				],
				[
					1.5437866853996516,
					8.645904905327507
				],
				[
					4.410591563693601,
					9.469686494182403
				],
				[
					5.516580151810234,
					9.702543349996933
				],
				[
					5.50652846593968,
					8.658538743086362
				],
				[
					1.564219194464783,
					7.770413087499971
				],
				[
					-0.4687444119447881,
					8.925174601782338
				],
				[
					-0.8784731582983338,
					11.78433041788163
				],
				[
					0.3963304825998596,
					14.628666080858068
				],
				[
					3.642891355787948,
					14.994789432989306
				],
				[
					6.975934648943947,
					12.077232336834529
				],
				[
					6.94009547374867,
					4.742637616202103
				],
				[
					3.473850276912003,
					-0.21475297636300184
				],
				[
					1.2058274425126,
					-0.5354580327556278
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 156,
			"versionNonce": 1979025936,
			"isDeleted": false,
			"id": "LP9PvMR9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2981.1450433323275,
			"y": -4276.231552952135,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 772.6520385742188,
			"height": 56.54885031960201,
			"seed": 1978090736,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"fontSize": 45.23908025568161,
			"fontFamily": 1,
			"text": "RECTANGULAR PLUSE FUNCTION",
			"rawText": "RECTANGULAR PLUSE FUNCTION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "RECTANGULAR PLUSE FUNCTION",
			"lineHeight": 1.25,
			"baseline": 38
		},
		{
			"type": "line",
			"version": 86,
			"versionNonce": 898359024,
			"isDeleted": false,
			"id": "bnmrfitZdLqSzikeeLD-6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3042.912486284492,
			"y": -4218.452417946745,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 883.3669281005859,
			"height": 0,
			"seed": 141277424,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					883.3669281005859,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 84,
			"versionNonce": 551143440,
			"isDeleted": false,
			"id": "eg7HQCnM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3149.5899166002077,
			"y": -4153.793204392177,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 708.0193481445312,
			"height": 25,
			"seed": 580131056,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The unit rectangular pulse function    (t/T) shown below is defined as:",
			"rawText": "The unit rectangular pulse function    (t/T) shown below is defined as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The unit rectangular pulse function    (t/T) shown below is defined as:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3596,
			"versionNonce": 1217560816,
			"isDeleted": false,
			"id": "9pRNOeFxfALVXercdCblp",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -2775.229406843593,
			"y": -4151.652358095187,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.41606000375753,
			"height": 11.837194272125984,
			"seed": 977538800,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.634374296734201,
					-0.023342752406411843
				],
				[
					6.655868577744826,
					1.3144826613906686
				],
				[
					6.956172824871558,
					9.959181665359083
				],
				[
					5.016450278046757,
					11.718617614711139
				],
				[
					-2.062653262238049,
					11.813851519719572
				],
				[
					-2.0556694425373543,
					11.252458095374038
				],
				[
					4.649711000192106,
					11.059081590894097
				],
				[
					6.183508408902888,
					10.290226531125723
				],
				[
					6.197476048304158,
					6.781543701576625
				],
				[
					4.630287238916851,
					6.4187463441963555
				],
				[
					-1.93053086856556,
					6.512117353822111
				],
				[
					-1.929937758582982,
					5.94807786389816
				],
				[
					5.0801066789222675,
					5.613785965959741
				],
				[
					6.205862537923513,
					4.815797782629793
				],
				[
					5.787525424280815,
					1.361909553681761
				],
				[
					4.343885919130615,
					0.7193827482476424
				],
				[
					-2.459887178885971,
					0.7228273769987609
				],
				[
					-2.4501737281720697,
					0.2315457753074848
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3658,
			"versionNonce": 545670672,
			"isDeleted": false,
			"id": "E-0RCy6WPtoK26fMWM4Ia",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -2749.1493710894133,
			"y": -4073.163093897846,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 29.04758431220404,
			"height": 40.23631750862496,
			"seed": 1058300656,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					14.296571821438928,
					-0.07934535631989076
				],
				[
					20.53267540838103,
					4.4681146990923
				],
				[
					21.45908336821197,
					33.852683870963794
				],
				[
					15.475237237378895,
					39.83325847899578
				],
				[
					-6.36307484423347,
					40.156972152305066
				],
				[
					-6.341530473074385,
					38.248715554505374
				],
				[
					14.343883986674385,
					37.59140113910502
				],
				[
					19.075492486364,
					34.9779527499204
				],
				[
					19.118581228681798,
					23.05143763820697
				],
				[
					14.283963665109109,
					21.818237495735975
				],
				[
					-5.955490741307157,
					22.135618921015904
				],
				[
					-5.953661057530878,
					20.21836796760168
				],
				[
					15.671610738684638,
					19.08206196156742
				],
				[
					19.1444526934138,
					16.369585915769793
				],
				[
					17.85392538426208,
					4.6293254938805
				],
				[
					13.4004448174916,
					2.4452849216878416
				],
				[
					-7.58850094399207,
					2.4569937078193416
				],
				[
					-7.558535939684335,
					0.7870572298531195
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 14,
			"versionNonce": 1182065392,
			"isDeleted": false,
			"id": "Nowo0RUB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2705.4148160658874,
			"y": -4082.72730453464,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 77241360,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097097,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 838009872,
			"isDeleted": false,
			"id": "2ygf6jxk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2705.088389629626,
			"y": -4046.004386280067,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 16.079986572265625,
			"height": 25,
			"seed": 631510032,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "T",
			"rawText": "T",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 24,
			"versionNonce": 1572537584,
			"isDeleted": false,
			"id": "CGHeul2HXOSv0nPbnD5yz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2712.4136876598277,
			"y": -4051.387538195082,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 32.703046100895335,
			"height": 0,
			"seed": 1839323888,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					32.703046100895335,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 16,
			"versionNonce": 857211408,
			"isDeleted": false,
			"id": "L8Z3w9jd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2668.829450212229,
			"y": -4071.2363943069345,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 32.33995056152344,
			"height": 25,
			"seed": 1067015408,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "4hsmnQtRyCiAy-UxqMJAH",
					"type": "arrow"
				}
			],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": " = ",
			"rawText": " = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": " = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 53,
			"versionNonce": 736945904,
			"isDeleted": false,
			"id": "eFzlanvU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2605.6036528846757,
			"y": -4090.5597153935387,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 187.5997772216797,
			"height": 75,
			"seed": 1310739184,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "KsGCgQdLOI1wv_9inlYih",
					"type": "arrow"
				},
				{
					"id": "4hsmnQtRyCiAy-UxqMJAH",
					"type": "arrow"
				}
			],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1  for |t| <= T / 2\n\n0 otherwise",
			"rawText": "1  for |t| <= T / 2\n\n0 otherwise",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1  for |t| <= T / 2\n\n0 otherwise",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "arrow",
			"version": 24,
			"versionNonce": 49102864,
			"isDeleted": false,
			"id": "KsGCgQdLOI1wv_9inlYih",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2614.3045865737,
			"y": -4078.3194497566296,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 23.084463724275793,
			"height": 11.54226907869679,
			"seed": 569590000,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "eFzlanvU",
				"focus": 0.9065192436642897,
				"gap": 8.700933689024168
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-23.084463724275793,
					11.54226907869679
				]
			]
		},
		{
			"type": "arrow",
			"version": 21,
			"versionNonce": 1569884400,
			"isDeleted": false,
			"id": "4hsmnQtRyCiAy-UxqMJAH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2608.5334148177926,
			"y": -4035.997858495673,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 19.237090320122206,
			"height": 11.54226907869679,
			"seed": 352496656,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "eFzlanvU",
				"focus": -0.8008073946576832,
				"gap": 2.929761933116879
			},
			"endBinding": {
				"elementId": "L8Z3w9jd",
				"focus": -0.16832424079549138,
				"gap": 8.718994512790687
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-19.237090320122206,
					-11.54226907869679
				]
			]
		},
		{
			"type": "text",
			"version": 43,
			"versionNonce": 1634385424,
			"isDeleted": false,
			"id": "wKiIsok4",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3115.1709136268664,
			"y": -3972.4559065020558,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 270.4596862792969,
			"height": 25,
			"seed": 1773539856,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "It is an even function of t",
			"rawText": "It is an even function of t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "It is an even function of t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "arrow",
			"version": 59,
			"versionNonce": 1312025328,
			"isDeleted": false,
			"id": "JxdkBQGh_RgzFvDomIV2t",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2870.41643870785,
			"y": -3687.5848842078485,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 604.044472298971,
			"height": 0,
			"seed": 1802483952,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					604.044472298971,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 51,
			"versionNonce": 1334344720,
			"isDeleted": false,
			"id": "IGctH9vm5vSEeYzhKNKtu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2578.0127849349838,
			"y": -3664.5004204835727,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 0,
			"height": 321.2592892530488,
			"seed": 1855150832,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "EGbQHl0d",
				"focus": -3.091257688934533,
				"gap": 14.387847156058797
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-321.2592892530488
				]
			]
		},
		{
			"type": "text",
			"version": 29,
			"versionNonce": 676924656,
			"isDeleted": false,
			"id": "EGbQHl0d",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2563.624937778925,
			"y": -3683.8605487467203,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 1987615760,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "IGctH9vm5vSEeYzhKNKtu",
					"type": "arrow"
				}
			],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 23,
			"versionNonce": 1866365456,
			"isDeleted": false,
			"id": "4alS2hNg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2436.091532195846,
			"y": -3674.4308404054473,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 40.31996154785156,
			"height": 25,
			"seed": 657305104,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "T/2",
			"rawText": "T/2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T/2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 22,
			"versionNonce": 92925680,
			"isDeleted": false,
			"id": "sBrxbXge",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2759.6399747572973,
			"y": -3670.9100050872316,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 48.539947509765625,
			"height": 25,
			"seed": 993518096,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-T/2",
			"rawText": "-T/2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-T/2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 81,
			"versionNonce": 1669642256,
			"isDeleted": false,
			"id": "iC-UQ6ArLaQ7uc2Qb4xV0",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2733.8331941980364,
			"y": -3820.3207180969493,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 315.48822914681796,
			"height": 0,
			"seed": 1485712112,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					315.48822914681796,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 32,
			"versionNonce": 240029936,
			"isDeleted": false,
			"id": "SczYyDm10WmOMR0o7zLDt",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2733.833194198037,
			"y": -3683.7375108036945,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 0,
			"height": 140.4306551305258,
			"seed": 1619613936,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-140.4306551305258
				]
			]
		},
		{
			"type": "line",
			"version": 26,
			"versionNonce": 810759696,
			"isDeleted": false,
			"id": "1uKzxDm33e4gJRn9HAw7I",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2420.2686889698543,
			"y": -3687.5848842078485,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 0,
			"height": 134.65963224085363,
			"seed": 1871176432,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-134.65963224085363
				]
			]
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 439284464,
			"isDeleted": false,
			"id": "bXn9u0mL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2601.5673682286197,
			"y": -3856.1382319117356,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 1512905456,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3671,
			"versionNonce": 446821392,
			"isDeleted": false,
			"id": "1LBvcAMq4mwdddm9jSBTn",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -2545.009845259518,
			"y": -3965.8227614124194,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 20.12417044962328,
			"height": 25.0901477513763,
			"seed": 1598665232,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.904666945369401,
					-0.049477358682859546
				],
				[
					14.22504037733166,
					2.7861808662358674
				],
				[
					14.866855940689636,
					21.10950734795863
				],
				[
					10.721246509387964,
					24.838812360065834
				],
				[
					-4.408339136664969,
					25.040670392693443
				],
				[
					-4.393413193330906,
					23.850739431042445
				],
				[
					9.937444820021755,
					23.440858089441804
				],
				[
					13.215503846384042,
					21.81119090602765
				],
				[
					13.24535573305191,
					14.37417765928189
				],
				[
					9.895932012911345,
					13.60519143744429
				],
				[
					-4.125964813496215,
					13.803100872175957
				],
				[
					-4.124697208321651,
					12.607561303046191
				],
				[
					10.857294098391975,
					11.89899532714483
				],
				[
					13.263279487414835,
					10.20757749929458
				],
				[
					12.369201988228387,
					2.8867070304278486
				],
				[
					9.283830032457178,
					1.524805543305726
				],
				[
					-5.257314508933643,
					1.5321067873613141
				],
				[
					-5.236554749783578,
					0.49078502727220763
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 28,
			"versionNonce": 1337136368,
			"isDeleted": false,
			"id": "Irtk3633",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2519.585020786737,
			"y": -3961.858044816652,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 72.43991088867188,
			"height": 25,
			"seed": 1525052656,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t / T)",
			"rawText": "(t / T)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t / T)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 141095440,
			"isDeleted": false,
			"id": "1qOnQQv7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2277.039571925266,
			"y": -3669.364029239289,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 662404848,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 54,
			"versionNonce": 1147336432,
			"isDeleted": false,
			"id": "FOasrDAp",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2715.3947340108225,
			"y": -3606.8424436352493,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec99",
			"width": 267.0596923828125,
			"height": 25,
			"seed": 659699952,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Rectangular Pulse Function",
			"rawText": "Rectangular Pulse Function",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Rectangular Pulse Function",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "rectangle",
			"version": 178,
			"versionNonce": 1621110800,
			"isDeleted": false,
			"id": "rGfwhTgpljkYVZfAJbVCH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3215.097883707674,
			"y": -4354.616221201553,
			"strokeColor": "#820bf9",
			"backgroundColor": "transparent",
			"width": 1215.9440570407442,
			"height": 817.2020382351338,
			"seed": 2053575920,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "0z4j4BTpfLEGj5M3euFAl",
					"type": "arrow"
				}
			],
			"updated": 1703931097098,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 79,
			"versionNonce": 482777328,
			"isDeleted": false,
			"id": "0rBlc7E7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2905.853512298226,
			"y": -3363.9812846471327,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 700.482666015625,
			"height": 53.68073698762183,
			"seed": 1389774576,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 42.944589590097465,
			"fontFamily": 1,
			"text": "TRIANGULAR PULSE FUNCTION",
			"rawText": "TRIANGULAR PULSE FUNCTION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "TRIANGULAR PULSE FUNCTION",
			"lineHeight": 1.25,
			"baseline": 38
		},
		{
			"type": "line",
			"version": 70,
			"versionNonce": 1799335440,
			"isDeleted": false,
			"id": "Mgs3jInROWb9ZyyMzWvMm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2939.737813421907,
			"y": -3303.6901231718884,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 760.039767971286,
			"height": 0,
			"seed": 679599856,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					760.039767971286,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 83,
			"versionNonce": 744880880,
			"isDeleted": false,
			"id": "P2OIgc42",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3149.919706114176,
			"y": -3243.0008856515965,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 691.4193725585938,
			"height": 25,
			"seed": 1894054128,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The unit triangular pulse function    (t/T) shown below is defined as:",
			"rawText": "The unit triangular pulse function    (t/T) shown below is defined as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The unit triangular pulse function    (t/T) shown below is defined as:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 496,
			"versionNonce": 826240016,
			"isDeleted": false,
			"id": "nywL6SuqMIAF1j0yK2kCB",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.71238898038469,
			"x": -2812.1341538548536,
			"y": -3251.127829660958,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.33426388103564,
			"height": 31.909147980925358,
			"seed": 1000469008,
			"groupIds": [
				"C25kAGRIv7omZhs7guTsm"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					31.909147980925358
				],
				[
					38.33426388103564,
					16.47345900130687
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 542,
			"versionNonce": 365501680,
			"isDeleted": false,
			"id": "Dv6qNK7OkllieilnQOnOU",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.71238898038469,
			"x": -2838.871750333561,
			"y": -3144.394259923131,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 54.58170929805007,
			"height": 52.39536037692734,
			"seed": 1539136528,
			"groupIds": [
				"FcQ05WWdxYQLSNUXU-PPt"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					52.39536037692734
				],
				[
					54.58170929805007,
					27.049698147502227
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 22,
			"versionNonce": 1553426960,
			"isDeleted": false,
			"id": "6UQOHEdR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2758.5165078719883,
			"y": -3145.0496059742427,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 876780784,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 25,
			"versionNonce": 1786248944,
			"isDeleted": false,
			"id": "BQ8rQfRm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2754.272741384569,
			"y": -3107.7894662116614,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 16.079986572265625,
			"height": 25,
			"seed": 1718116880,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "T",
			"rawText": "T",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 40,
			"versionNonce": 406824976,
			"isDeleted": false,
			"id": "o5SX9yn6VLhbJotKAB6p8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2771.7505943421584,
			"y": -3117.2652138526923,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 49.16698901684231,
			"height": 0,
			"seed": 1931652336,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					49.16698901684231,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 24,
			"versionNonce": 1257939184,
			"isDeleted": false,
			"id": "mzjKYW2S",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2710.409826345507,
			"y": -3124.270226662148,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 22.3399658203125,
			"height": 25,
			"seed": 562634768,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "-oKule2damegBVP8S-QmQ",
					"type": "arrow"
				},
				{
					"id": "mQRZe_w3AQ8S5jrZbNjIR",
					"type": "arrow"
				}
			],
			"updated": 1703931097098,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "= ",
			"rawText": "= ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "= ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 91,
			"versionNonce": 1882203664,
			"isDeleted": false,
			"id": "7sp2VWxT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2624.4944416813432,
			"y": -3148.1956908464017,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 316.25958251953125,
			"height": 75,
			"seed": 1950140656,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "-oKule2damegBVP8S-QmQ",
					"type": "arrow"
				},
				{
					"id": "mQRZe_w3AQ8S5jrZbNjIR",
					"type": "arrow"
				}
			],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1 - 2( |t| / T)   for |t| < (T/2)\n\n0                for |t| > (T/2)",
			"rawText": "1 - 2( |t| / T)   for |t| < (T/2)\n\n0                for |t| > (T/2)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1 - 2( |t| / T)   for |t| < (T/2)\n\n0                for |t| > (T/2)",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "arrow",
			"version": 40,
			"versionNonce": 114885360,
			"isDeleted": false,
			"id": "-oKule2damegBVP8S-QmQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2636.541354729233,
			"y": -3135.7029040921407,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 45.069786170860425,
			"height": 16.389049183238967,
			"seed": 234186992,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "7sp2VWxT",
				"focus": 0.9146113483698104,
				"gap": 12.046913047889575
			},
			"endBinding": {
				"elementId": "mzjKYW2S",
				"focus": -0.06842103143840059,
				"gap": 6.4587196251013665
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-45.069786170860425,
					16.389049183238967
				]
			]
		},
		{
			"type": "arrow",
			"version": 26,
			"versionNonce": 828433424,
			"isDeleted": false,
			"id": "mQRZe_w3AQ8S5jrZbNjIR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2632.4441518832505,
			"y": -3092.681758977489,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 49.16698901684276,
			"height": 20.48625202922085,
			"seed": 239002128,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "7sp2VWxT",
				"focus": -0.8435623446259464,
				"gap": 7.949710201907237
			},
			"endBinding": {
				"elementId": "mzjKYW2S",
				"focus": -0.5096768890210724,
				"gap": 6.4587196251013665
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-49.16698901684276,
					-20.48625202922085
				]
			]
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 1016800496,
			"isDeleted": false,
			"id": "1lJQuxBv",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3128.3905455774475,
			"y": -3019.624262274967,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 269.419677734375,
			"height": 25,
			"seed": 441679376,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "it is an even function of t.",
			"rawText": "it is an even function of t.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "it is an even function of t.",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "arrow",
			"version": 79,
			"versionNonce": 1237967376,
			"isDeleted": false,
			"id": "nFzUIjP-vsxXAqN9M4T7k",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2866.975584196055,
			"y": -2692.8479806952164,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 581.8094228769278,
			"height": 0,
			"seed": 1624929008,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					581.8094228769278,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 76,
			"versionNonce": 2043217648,
			"isDeleted": false,
			"id": "kodKI1EEMBcdr7HKl5rr1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2590.4112214347933,
			"y": -2637.535068509745,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 391.28735034496776,
			"seed": 2001469456,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "vo0pbYQo",
				"focus": -3.2111657852280615,
				"gap": 15.21281452922085
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-391.28735034496776
				]
			]
		},
		{
			"type": "line",
			"version": 62,
			"versionNonce": 677584912,
			"isDeleted": false,
			"id": "0sqn0YZti7anrx1q02gFl",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2797.3223431499923,
			"y": -2688.750619316361,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 203.8381799474937,
			"height": 203.8381799474937,
			"seed": 1984539376,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					203.8381799474937,
					-203.8381799474937
				]
			]
		},
		{
			"type": "line",
			"version": 60,
			"versionNonce": 1525328112,
			"isDeleted": false,
			"id": "kSqpcWoMhBZ60X3tfKp-d",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2592.459862491003,
			"y": -2893.613139608569,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 201.78947944145693,
			"height": 201.78947944145693,
			"seed": 1543210000,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					201.78947944145693,
					201.78947944145693
				]
			]
		},
		{
			"type": "text",
			"version": 19,
			"versionNonce": 488939024,
			"isDeleted": false,
			"id": "81Z5TDqG",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2575.5461487633243,
			"y": -2912.581994240267,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 1290128912,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 730335984,
			"isDeleted": false,
			"id": "BRL0ArZe",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2290.72820791511,
			"y": -2672.8710155217195,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 1568647184,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 24,
			"versionNonce": 956718096,
			"isDeleted": false,
			"id": "rHHph2Wk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2411.855091285646,
			"y": -2678.468097882718,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40.31996154785156,
			"height": 25,
			"seed": 699050224,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "T/2",
			"rawText": "T/2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T/2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 24,
			"versionNonce": 103361776,
			"isDeleted": false,
			"id": "Uclg5rDA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2812.165538284935,
			"y": -2674.5719939866144,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.539947509765625,
			"height": 25,
			"seed": 609848848,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-T/2",
			"rawText": "-T/2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-T/2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 31,
			"versionNonce": 771774992,
			"isDeleted": false,
			"id": "vo0pbYQo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2575.1984069055725,
			"y": -2677.169396584017,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 1137274096,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "kodKI1EEMBcdr7HKl5rr1",
					"type": "arrow"
				}
			],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 63,
			"versionNonce": 1951796976,
			"isDeleted": false,
			"id": "vwtfV6Sq",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2713.337452918153,
			"y": -2597.1615809133596,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 250.27972412109375,
			"height": 25,
			"seed": 174620400,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Triangular Pulse Function",
			"rawText": "Triangular Pulse Function",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Triangular Pulse Function",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 580,
			"versionNonce": 789223440,
			"isDeleted": false,
			"id": "mNzw4GyifX-VRwJrrYqdd",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.71238898038469,
			"x": -2562.149845303728,
			"y": -3030.5533599664996,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.01253854394619,
			"height": 27.811905501724155,
			"seed": 1806364400,
			"groupIds": [
				"Bhe5t4bWAFAHn2KhVf7UU"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					27.811905501724155
				],
				[
					26.01253854394619,
					14.358211172067382
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 32,
			"versionNonce": 244756720,
			"isDeleted": false,
			"id": "mULYKlQN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2527.548815286254,
			"y": -3023.3738817960707,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 72.43991088867188,
			"height": 25,
			"seed": 936568336,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t / T)",
			"rawText": "(t / T)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t / T)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "rectangle",
			"version": 86,
			"versionNonce": 1344083472,
			"isDeleted": false,
			"id": "k3pcBEP3oHiRM6NE-jdQ_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3182.574089389591,
			"y": -3396.203963091726,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 1206.6399710518972,
			"height": 864.5196295403812,
			"seed": 462009872,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "LyBrbQDYJDeeONRPjzse2",
					"type": "arrow"
				}
			],
			"updated": 1703931097099,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 121,
			"versionNonce": 477303536,
			"isDeleted": false,
			"id": "4rGL31gI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2860.8989134717417,
			"y": -2431.200612602107,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 475.7928466796875,
			"height": 60.315852378731606,
			"seed": 1072377072,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 48.25268190298529,
			"fontFamily": 1,
			"text": "SIGNUM FUNCTION",
			"rawText": "SIGNUM FUNCTION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "SIGNUM FUNCTION",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "line",
			"version": 104,
			"versionNonce": 1714410512,
			"isDeleted": false,
			"id": "s-_trjeoRZCNxh-NttZak",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2883.2010001453073,
			"y": -2351.7782682235356,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 562.6990474871736,
			"height": 0,
			"seed": 953726480,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					562.6990474871736,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 93,
			"versionNonce": 879965424,
			"isDeleted": false,
			"id": "7lxnPlfM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2948.856378230771,
			"y": -2319.775745171377,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 580.3594360351562,
			"height": 25,
			"seed": 254384656,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The unit signum function sgn (t) shown below is defined as:",
			"rawText": "The unit signum function sgn (t) shown below is defined as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The unit signum function sgn (t) shown below is defined as:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 57,
			"versionNonce": 1731908112,
			"isDeleted": false,
			"id": "3f8WVgBW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2705.0476205057244,
			"y": -2233.208580992273,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 88.91989135742188,
			"height": 25,
			"seed": 587554320,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "sgn(t) = ",
			"rawText": "sgn(t) = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "sgn(t) = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 64,
			"versionNonce": 1545541360,
			"isDeleted": false,
			"id": "YF5Nglqi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2592.139960320323,
			"y": -2263.0593272609294,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 130.19984436035156,
			"height": 75,
			"seed": 2016606736,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "12WqodUujW7J0t5gygPtJ",
					"type": "arrow"
				},
				{
					"id": "06GmxlBHipOZhghdF3tLo",
					"type": "arrow"
				}
			],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1   for t > 0\n\n-1 for  t < 0",
			"rawText": "1   for t > 0\n\n-1 for  t < 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1   for t > 0\n\n-1 for  t < 0",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "arrow",
			"version": 85,
			"versionNonce": 1245057040,
			"isDeleted": false,
			"id": "12WqodUujW7J0t5gygPtJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2603.224629442699,
			"y": -2248.4449105485537,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 16.262266807949345,
			"height": 16.262266807949345,
			"seed": 764047600,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YF5Nglqi",
				"focus": 0.9655969759528558,
				"gap": 11.084669122375999
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-16.262266807949345,
					16.262266807949345
				]
			]
		},
		{
			"type": "arrow",
			"version": 101,
			"versionNonce": 671004912,
			"isDeleted": false,
			"id": "06GmxlBHipOZhghdF3tLo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2603.2246294426996,
			"y": -2201.2843037710086,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.701628065600744,
			"height": 18.701628065600744,
			"seed": 1374076432,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YF5Nglqi",
				"focus": -0.9791392883910369,
				"gap": 11.084669122376454
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-18.701628065600744,
					-18.701628065600744
				]
			]
		},
		{
			"type": "arrow",
			"version": 148,
			"versionNonce": 1729728016,
			"isDeleted": false,
			"id": "HnF7aQ-JUXH8kFcMfK1c-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2830.896584983936,
			"y": -1954.097678398505,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 578.9370821923321,
			"height": 0,
			"seed": 568339184,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "S1vcSOq2",
				"focus": 2.0184338756441322,
				"gap": 12.73042344555165
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					578.9370821923321,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 110,
			"versionNonce": 1536826096,
			"isDeleted": false,
			"id": "R8OYUZ4tsgAhRhkP4-d6h",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2543.054190341942,
			"y": -1760.5765916958635,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 395.1733775974553,
			"seed": 1240144112,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-395.1733775974553
				]
			]
		},
		{
			"type": "line",
			"version": 78,
			"versionNonce": 1457343504,
			"isDeleted": false,
			"id": "gN5fwkzXXKCai5sFbiZXz",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2543.054190341942,
			"y": -2045.1525672516,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 200.02601859495826,
			"height": 0,
			"seed": 49809648,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					200.02601859495826,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 108,
			"versionNonce": 158940400,
			"isDeleted": false,
			"id": "3ywkZ3SAsqgVeN1Wiui8Y",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2740.9637744825895,
			"y": -1853.5409446087074,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 200.02601859495826,
			"height": 0,
			"seed": 1700184816,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					200.02601859495826,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 47,
			"versionNonce": 1400457744,
			"isDeleted": false,
			"id": "VGCoE2AO",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2558.4087165077767,
			"y": -2058.1814337343644,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 823347728,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 45,
			"versionNonce": 858005232,
			"isDeleted": false,
			"id": "7ccrwVzX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2534.1888968194708,
			"y": -1860.7517688865873,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.639984130859375,
			"height": 25,
			"seed": 290832912,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097099,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-1",
			"rawText": "-1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 43,
			"versionNonce": 400918544,
			"isDeleted": false,
			"id": "tmZ9g261",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2538.90792116306,
			"y": -1946.0862792965422,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 1663727632,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 1763885296,
			"isDeleted": false,
			"id": "S1vcSOq2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2247.1118641599996,
			"y": -1941.3672549529533,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 6399216,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "HnF7aQ-JUXH8kFcMfK1c-",
					"type": "arrow"
				}
			],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 51,
			"versionNonce": 1075447312,
			"isDeleted": false,
			"id": "WEMqcPJf",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2607.341356347499,
			"y": -1683.1562645977665,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 148.23985290527344,
			"height": 25,
			"seed": 394871024,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Signum Function",
			"rawText": "Signum Function",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Signum Function",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 146,
			"versionNonce": 1794974448,
			"isDeleted": false,
			"id": "FQYzfP1c",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2855.4159803205985,
			"y": -1590.1476628093735,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 715.3392944335938,
			"height": 75,
			"seed": 114941456,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The signum function can be expressed in terms of unit step function as:\n                \n                sgn(t) = -1 + 2u(t)",
			"rawText": "The signum function can be expressed in terms of unit step function as:\n                \n                sgn(t) = -1 + 2u(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The signum function can be expressed in terms of unit step function as:\n                \n                sgn(t) = -1 + 2u(t)",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "rectangle",
			"version": 110,
			"versionNonce": 688833552,
			"isDeleted": false,
			"id": "GB1okOYpbb8RBkdtTjwPN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3139.9276024004675,
			"y": -2462.404373166646,
			"strokeColor": "#d2bab0",
			"backgroundColor": "transparent",
			"width": 1109.1381072998051,
			"height": 951.3939857482915,
			"seed": 2073590000,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "gXcmVqd8vDGnjJ7uiei3B",
					"type": "arrow"
				}
			],
			"updated": 1703931097100,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 158,
			"versionNonce": 1195066608,
			"isDeleted": false,
			"id": "gXcmVqd8vDGnjJ7uiei3B",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1920.3641492029906,
			"y": -1354.741846400188,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 78.8720703125,
			"height": 410.13468424479174,
			"seed": 1498431728,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "DOfM1hI5A0MC6AWsUQ4Zb",
				"focus": -0.5887612770691462,
				"gap": 2.7819891001877295
			},
			"endBinding": {
				"elementId": "GB1okOYpbb8RBkdtTjwPN",
				"focus": -0.7761045317895056,
				"gap": 31.55327558517206
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-32.600341796875455,
					-234.51306152343795
				],
				[
					-78.8720703125,
					-410.13468424479174
				]
			]
		},
		{
			"type": "arrow",
			"version": 168,
			"versionNonce": 1354482192,
			"isDeleted": false,
			"id": "LyBrbQDYJDeeONRPjzse2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1657.457248161324,
			"y": -1365.2582038220626,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 289.19759114583326,
			"height": 1177.8225708007817,
			"seed": 1885971696,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "DOfM1hI5A0MC6AWsUQ4Zb",
				"focus": 0.027652607882879512,
				"gap": 13.298346522062275
			},
			"endBinding": {
				"elementId": "k3pcBEP3oHiRM6NE-jdQ_",
				"focus": -1.0465451033936568,
				"gap": 29.279279030536372
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-288.14611816406295,
					-411.1861572265625
				],
				[
					-289.19759114583326,
					-1177.8225708007817
				]
			]
		},
		{
			"type": "arrow",
			"version": 172,
			"versionNonce": 2070226672,
			"isDeleted": false,
			"id": "0z4j4BTpfLEGj5M3euFAl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1565.152242769885,
			"y": -1380.7450354871016,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 420.6510416666665,
			"height": 2460.8079020182286,
			"seed": 1267638800,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "DOfM1hI5A0MC6AWsUQ4Zb",
				"focus": 0.1425906775977975,
				"gap": 28.785178187101337
			},
			"endBinding": {
				"elementId": "rGfwhTgpljkYVZfAJbVCH",
				"focus": -0.959587326202119,
				"gap": 13.350542230378323
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-265.010009765625,
					-422.7539876302071
				],
				[
					-420.6510416666665,
					-2460.8079020182286
				]
			]
		},
		{
			"type": "text",
			"version": 255,
			"versionNonce": 907608080,
			"isDeleted": false,
			"id": "j5mQkC5w",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1134.3281410039317,
			"y": 1667.1912260078498,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 914.5971069335938,
			"height": 66.40781402587886,
			"seed": 460006640,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"fontSize": 53.12625122070309,
			"fontFamily": 1,
			"text": "BASIC OPERATIONS ON SIGNALS",
			"rawText": "BASIC OPERATIONS ON SIGNALS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "BASIC OPERATIONS ON SIGNALS",
			"lineHeight": 1.25,
			"baseline": 46
		},
		{
			"type": "line",
			"version": 172,
			"versionNonce": 335726832,
			"isDeleted": false,
			"id": "e-R2rbVHQmkjElygG1gWo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1171.7032939097135,
			"y": 1743.197404333927,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 991.8159866333006,
			"height": 0,
			"seed": 1102596624,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					991.8159866333006,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 799,
			"versionNonce": 958299664,
			"isDeleted": false,
			"id": "oT5HNN7F",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1229.1464549204557,
			"y": 1776.566544958927,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1145.098876953125,
			"height": 225,
			"seed": 849140752,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "When we process a signal, this signal may undergo several manipulations involving the independent variable or the \namplitude of the signal. The basic operations on signals are:\n\n1. Time shifting                           2. Time reversal\n3. Time scaling                           4. Amplitude scaling\n5. Signal addition                         6 Signal multiplication\n\nThe first three operations correspond to transformation in independent variable t or n of a signal. The last there\noperations correspond to transformation on amplitude of a signal.",
			"rawText": "When we process a signal, this signal may undergo several manipulations involving the independent variable or the \namplitude of the signal. The basic operations on signals are:\n\n1. Time shifting                           2. Time reversal\n3. Time scaling                           4. Amplitude scaling\n5. Signal addition                         6 Signal multiplication\n\nThe first three operations correspond to transformation in independent variable t or n of a signal. The last there\noperations correspond to transformation on amplitude of a signal.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "When we process a signal, this signal may undergo several manipulations involving the independent variable or the \namplitude of the signal. The basic operations on signals are:\n\n1. Time shifting                           2. Time reversal\n3. Time scaling                           4. Amplitude scaling\n5. Signal addition                         6 Signal multiplication\n\nThe first three operations correspond to transformation in independent variable t or n of a signal. The last there\noperations correspond to transformation on amplitude of a signal.",
			"lineHeight": 1.25,
			"baseline": 216
		},
		{
			"type": "rectangle",
			"version": 200,
			"versionNonce": 1285303024,
			"isDeleted": false,
			"id": "Nk9cQkG4lbeEz0woUdakw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1336.589107449392,
			"y": 1632.297375931772,
			"strokeColor": "#ff8787",
			"backgroundColor": "transparent",
			"width": 1347.9950506036935,
			"height": 435.947265625,
			"seed": 1837232656,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "ckQXNxQsunZp-vW9nhS3e",
					"type": "arrow"
				},
				{
					"id": "IJZU1HLzygiPVJId9tYit",
					"type": "arrow"
				},
				{
					"id": "YMv4c_rrumq_OvyAbaLIr",
					"type": "arrow"
				},
				{
					"id": "B6nNheSaMhPzhQHMlz_3m",
					"type": "arrow"
				},
				{
					"id": "572tTRBJyvH3PkPsJKVCY",
					"type": "arrow"
				}
			],
			"updated": 1703931097100,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 123,
			"versionNonce": 2059680784,
			"isDeleted": false,
			"id": "ckQXNxQsunZp-vW9nhS3e",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 74.87363995106534,
			"y": 31.469680258609515,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 281.6194781135109,
			"height": 1750.95947265625,
			"seed": 1878638608,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "M3e1lYQJ",
				"focus": -0.9920504516240455,
				"gap": 14.130533435797929
			},
			"endBinding": {
				"elementId": "Nk9cQkG4lbeEz0woUdakw",
				"focus": 0.8848645145184614,
				"gap": 31.918929706920153
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					250.07071102366717,
					1080.5470275878906
				],
				[
					-31.54876708984375,
					1750.95947265625
				]
			]
		},
		{
			"type": "text",
			"version": 209,
			"versionNonce": 800673008,
			"isDeleted": false,
			"id": "q5i6hbh0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2137.2397099175187,
			"y": 1496.6936055094063,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 166.9798583984375,
			"height": 25,
			"seed": 75157744,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "TIME SHIFTING",
			"rawText": "TIME SHIFTING",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "TIME SHIFTING",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 262,
			"versionNonce": 1023556112,
			"isDeleted": false,
			"id": "rTSS4Uasx3hb6t2frN2HW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2147.6598058448417,
			"y": 1523.7899965801628,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 205.8184523809523,
			"height": 0,
			"seed": 1161451536,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					205.8184523809523,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 843,
			"versionNonce": 920792816,
			"isDeleted": false,
			"id": "fTNlmq7E",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2498.9222557227376,
			"y": 1542.4364968640757,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 940.259033203125,
			"height": 275,
			"seed": 1174804496,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Mathematically, the time shifting of a continuous-time signal x(t) or discrete time signal\nx[n] can be represented by\n                            y(t) = x(t - T)\nOR\n                            y[n] = x[n - T]\n\nThe time shifting of a signal may result in time delay or time advance. In the above equation\nif T POSITIVE the shift is to the right and the shifting DELAYS the signal, and if T is\nNEGATIVE the shift is to the left and then the shifting ADVANCES the signal. An arbitrary\nsignal x(t), its delayed version and advanced version are shown. Shifting a signal in time means\nthat a signal may be either advanced in the time axis or delayed in the time axis.",
			"rawText": "Mathematically, the time shifting of a continuous-time signal x(t) or discrete time signal\nx[n] can be represented by\n                            y(t) = x(t - T)\nOR\n                            y[n] = x[n - T]\n\nThe time shifting of a signal may result in time delay or time advance. In the above equation\nif T POSITIVE the shift is to the right and the shifting DELAYS the signal, and if T is\nNEGATIVE the shift is to the left and then the shifting ADVANCES the signal. An arbitrary\nsignal x(t), its delayed version and advanced version are shown. Shifting a signal in time means\nthat a signal may be either advanced in the time axis or delayed in the time axis.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Mathematically, the time shifting of a continuous-time signal x(t) or discrete time signal\nx[n] can be represented by\n                            y(t) = x(t - T)\nOR\n                            y[n] = x[n - T]\n\nThe time shifting of a signal may result in time delay or time advance. In the above equation\nif T POSITIVE the shift is to the right and the shifting DELAYS the signal, and if T is\nNEGATIVE the shift is to the left and then the shifting ADVANCES the signal. An arbitrary\nsignal x(t), its delayed version and advanced version are shown. Shifting a signal in time means\nthat a signal may be either advanced in the time axis or delayed in the time axis.",
			"lineHeight": 1.25,
			"baseline": 265
		},
		{
			"type": "rectangle",
			"version": 258,
			"versionNonce": 1120958480,
			"isDeleted": false,
			"id": "HzUUR-e6rZ6UIG44xYRff",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2562.403636883308,
			"y": 1476.6676265605697,
			"strokeColor": "#a5d8ff",
			"backgroundColor": "transparent",
			"width": 1072.6598103841147,
			"height": 750.8619791666671,
			"seed": 161422064,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "IJZU1HLzygiPVJId9tYit",
					"type": "arrow"
				}
			],
			"updated": 1703931097100,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 150,
			"versionNonce": 1788793072,
			"isDeleted": false,
			"id": "IJZU1HLzygiPVJId9tYit",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1322.5814775594768,
			"y": 1631.096839656882,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 164.744223736702,
			"height": 86.635872978095,
			"seed": 80359152,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Nk9cQkG4lbeEz0woUdakw",
				"focus": -0.2806973382502537,
				"gap": 1.2005362748900552
			},
			"endBinding": {
				"elementId": "HzUUR-e6rZ6UIG44xYRff",
				"gap": 2.418125203014597,
				"focus": -0.8927061438270072
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-80.83776595744666,
					-48.138381355076945
				],
				[
					-164.744223736702,
					-86.635872978095
				]
			]
		},
		{
			"type": "arrow",
			"version": 85,
			"versionNonce": 807859728,
			"isDeleted": false,
			"id": "fCBxnQGtZJ2SEEoiMZ2yx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2499.5175354853222,
			"y": 2122.040937651085,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 247.4091861122531,
			"seed": 1742450416,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-247.4091861122531
				]
			]
		},
		{
			"type": "arrow",
			"version": 151,
			"versionNonce": 41366256,
			"isDeleted": false,
			"id": "Jh1zQG2demgdvwkb4gk8m",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2546.0105517784964,
			"y": 2108.7571819973027,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 238.33598889802624,
			"height": 0,
			"seed": 1887790320,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "gmbL9Vd1",
				"focus": 1.3932694284539322,
				"gap": 4.915867855674151
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					238.33598889802624,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 167,
			"versionNonce": 1778234384,
			"isDeleted": false,
			"id": "fkCXOqJNn2w1cPCXflvde",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2234.2565246636586,
			"y": 2125.1035698381884,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 247.4091861122531,
			"seed": 1659730960,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-247.4091861122531
				]
			]
		},
		{
			"type": "arrow",
			"version": 150,
			"versionNonce": 83055856,
			"isDeleted": false,
			"id": "KDlPJRmL6rMSAXwsOQ0r6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2257.503016748363,
			"y": 2110.1594009442742,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 306.8282547005406,
			"height": 0,
			"seed": 1308850704,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "y1yOBH5p",
				"focus": 1.6094636232225457,
				"gap": 7.6182952902818215
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					306.8282547005406,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 154,
			"versionNonce": 1984737808,
			"isDeleted": false,
			"id": "pzOBwGzPgj0psW9m94qv9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1716.7800392606991,
			"y": 2128.4245569372843,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 247.4091861122531,
			"seed": 1401353232,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-247.4091861122531
				]
			]
		},
		{
			"type": "arrow",
			"version": 130,
			"versionNonce": 1738225392,
			"isDeleted": false,
			"id": "3wC6EtMnaJkxlkGEDdFMY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1875.5054697986436,
			"y": 2110.159433068041,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 336.39510827231993,
			"height": 0,
			"seed": 1554903568,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					336.39510827231993,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 52,
			"versionNonce": 1544286224,
			"isDeleted": false,
			"id": "gg5aKAffpxWIYLNfolHnA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2495.959153752179,
			"y": 2106.1468689833223,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.836721679920174,
			"height": 55.14281949605174,
			"seed": 720814096,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					31.836721679920174,
					-55.14281949605174
				]
			]
		},
		{
			"type": "line",
			"version": 32,
			"versionNonce": 787929328,
			"isDeleted": false,
			"id": "AMOmDtje0jx5FqjJFoWBc",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2464.4103384766854,
			"y": 2049.6910841354606,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 83.02323190789457,
			"height": 0,
			"seed": 365254896,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					83.02323190789457,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 30,
			"versionNonce": 53702160,
			"isDeleted": false,
			"id": "r7PbM3aSC69QcV4rBomRc",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2381.387106568791,
			"y": 2048.0306708953294,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 58.11626233552579,
			"seed": 407324176,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					58.11626233552579
				]
			]
		},
		{
			"type": "line",
			"version": 67,
			"versionNonce": 244202224,
			"isDeleted": false,
			"id": "bv4Xo7-ew5JGSXNq0vGg_",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2162.721350694502,
			"y": 2112.3619465095544,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.836721679920174,
			"height": 55.14281949605174,
			"seed": 1877282544,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					31.836721679920174,
					-55.14281949605174
				]
			]
		},
		{
			"type": "line",
			"version": 132,
			"versionNonce": 347810832,
			"isDeleted": false,
			"id": "wfELmtO_vFPVrWeGddIBI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1779.547522569501,
			"y": 2109.499975909226,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.836721679920174,
			"height": 55.14281949605174,
			"seed": 1211941392,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					31.836721679920174,
					-55.14281949605174
				]
			]
		},
		{
			"type": "line",
			"version": 53,
			"versionNonce": 149511408,
			"isDeleted": false,
			"id": "Rd4I34XDwFi7UKPYMLYjD",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2129.7443326520242,
			"y": 2056.4038617650535,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 83.02323190789457,
			"height": 0,
			"seed": 1932020976,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					83.02323190789457,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 59,
			"versionNonce": 1520118288,
			"isDeleted": false,
			"id": "IWHT44BhdtBatJ7IsNzBh",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1747.3715427671564,
			"y": 2054.4314625051857,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 83.02323190789457,
			"height": 0,
			"seed": 1390933520,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					83.02323190789457,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 68,
			"versionNonce": 261111536,
			"isDeleted": false,
			"id": "wJx3OgLT-bfuGymnPfybH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2045.4812760346404,
			"y": 2056.108119278292,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 58.11626233552579,
			"seed": 174911504,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097100,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					58.11626233552579
				]
			]
		},
		{
			"type": "line",
			"version": 62,
			"versionNonce": 533424144,
			"isDeleted": false,
			"id": "Vez5esqV0p7QKFXEExa1q",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1667.3792124038832,
			"y": 2052.342378632733,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 58.11626233552579,
			"seed": 760765680,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					58.11626233552579
				]
			]
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 587915504,
			"isDeleted": false,
			"id": "ad1Nv3cY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2483.841458696667,
			"y": 2125.578085574605,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 481035504,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 272885264,
			"isDeleted": false,
			"id": "IzXpoJev",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2217.5256692229827,
			"y": 2124.5254539956577,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 1724517616,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 1927365360,
			"isDeleted": false,
			"id": "2ymECnB7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1734.3677744861407,
			"y": 2127.6833487325002,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 1302598896,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 33,
			"versionNonce": 419210256,
			"isDeleted": false,
			"id": "0Jbed7dH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1796.3099774055486,
			"y": 2113.628751179046,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 24.299972534179688,
			"height": 25,
			"seed": 1790339600,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-T",
			"rawText": "-T",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-T",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 25,
			"versionNonce": 2107335920,
			"isDeleted": false,
			"id": "TURDSxWZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1688.2593760486411,
			"y": 2119.21799742699,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 69.59991455078125,
			"height": 25,
			"seed": 811873520,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-T + 6",
			"rawText": "-T + 6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-T + 6",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 26,
			"versionNonce": 1206755856,
			"isDeleted": false,
			"id": "a357eMck",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2071.5802667764365,
			"y": 2122.2571627230427,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 61.37992858886719,
			"height": 25,
			"seed": 559937776,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "T + 6",
			"rawText": "T + 6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T + 6",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 22,
			"versionNonce": 817972976,
			"isDeleted": false,
			"id": "MNJPDXbL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2171.5359359787394,
			"y": 2112.294362044589,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 16.079986572265625,
			"height": 25,
			"seed": 800975376,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "T",
			"rawText": "T",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 739172368,
			"isDeleted": false,
			"id": "TxuoOrsa",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2381.7361955387723,
			"y": 2122.420190837763,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 12.79998779296875,
			"height": 25,
			"seed": 802409488,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "6",
			"rawText": "6",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 17,
			"versionNonce": 148564208,
			"isDeleted": false,
			"id": "aCbwoLFU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2483.3966569645536,
			"y": 1870.0703694459046,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.59996032714844,
			"height": 25,
			"seed": 1512883440,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(t)",
			"rawText": "x(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 894983696,
			"isDeleted": false,
			"id": "apzTP7Ys",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2209.4463126780865,
			"y": 1865.6210671741119,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 81.89990234375,
			"height": 25,
			"seed": 651998960,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(t - T)",
			"rawText": "x(t - T)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t - T)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 28,
			"versionNonce": 829442800,
			"isDeleted": false,
			"id": "LSHnORAY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1696.4887096250438,
			"y": 1870.6910487993175,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 86.17990112304688,
			"height": 25,
			"seed": 1838865648,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(t + T)",
			"rawText": "x(t + T)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t + T)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 22,
			"versionNonce": 348265488,
			"isDeleted": false,
			"id": "gmbL9Vd1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2306.88062399272,
			"y": 2113.673049852977,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 963329264,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "Jh1zQG2demgdvwkb4gk8m",
					"type": "arrow"
				}
			],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 40,
			"versionNonce": 621374704,
			"isDeleted": false,
			"id": "y1yOBH5p",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1949.6101820339413,
			"y": 2117.777696234556,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 817904368,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "KDlPJRmL6rMSAXwsOQ0r6",
					"type": "arrow"
				}
			],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 24,
			"versionNonce": 474225168,
			"isDeleted": false,
			"id": "YCoFf75I",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1537.9125052247305,
			"y": 2113.078085574605,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 1518133488,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 78,
			"versionNonce": 1294880496,
			"isDeleted": false,
			"id": "78pIJFru",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2280.930847359973,
			"y": 2185.774205451934,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 420.3795166015625,
			"height": 25,
			"seed": 99875344,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The same applies for discrete time signals",
			"rawText": "The same applies for discrete time signals",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The same applies for discrete time signals",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 91,
			"versionNonce": 517363728,
			"isDeleted": false,
			"id": "QwHaLUPk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2133.2809635117096,
			"y": 2284.954817727028,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 167.4598388671875,
			"height": 25,
			"seed": 423908368,
			"groupIds": [
				"Zrfrlmbk6RpVYLpgVPOWH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "TIME REVERSAL",
			"rawText": "TIME REVERSAL",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "TIME REVERSAL",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 100,
			"versionNonce": 577171696,
			"isDeleted": false,
			"id": "BHutwhNVtog_FfGQw1p5X",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2172.594114553376,
			"y": 2319.21059572182,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 229.25480143229152,
			"height": 0,
			"seed": 1247458032,
			"groupIds": [
				"Zrfrlmbk6RpVYLpgVPOWH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					229.25480143229152,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 453,
			"versionNonce": 1349572112,
			"isDeleted": false,
			"id": "Sdo69CuJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2547.497957267477,
			"y": 2334.842587214198,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1078.138916015625,
			"height": 100,
			"seed": 1692436496,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Time reversal, also called time folding of a signal x(t) can be obtained by folding the signal about t = 0.\nThis operation is very useful in CONVOLUTION. It is denoted by x(-t). It is obtained by replacing the \nindependent variable t by (-t). Folding is also called REFLECTION of the signal about the time origin t = 0.\nThe figure below shows an arbitrary signal x(t) and its reflection:",
			"rawText": "Time reversal, also called time folding of a signal x(t) can be obtained by folding the signal about t = 0.\nThis operation is very useful in CONVOLUTION. It is denoted by x(-t). It is obtained by replacing the \nindependent variable t by (-t). Folding is also called REFLECTION of the signal about the time origin t = 0.\nThe figure below shows an arbitrary signal x(t) and its reflection:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Time reversal, also called time folding of a signal x(t) can be obtained by folding the signal about t = 0.\nThis operation is very useful in CONVOLUTION. It is denoted by x(-t). It is obtained by replacing the \nindependent variable t by (-t). Folding is also called REFLECTION of the signal about the time origin t = 0.\nThe figure below shows an arbitrary signal x(t) and its reflection:",
			"lineHeight": 1.25,
			"baseline": 91
		},
		{
			"type": "arrow",
			"version": 113,
			"versionNonce": 1278956272,
			"isDeleted": false,
			"id": "8gwmRdizJeVLH-tOZefHN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2453.1911375636323,
			"y": 2684.7623111487956,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.547473508864641e-13,
			"height": 220.84177652994777,
			"seed": 142936080,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "VgqpIsHr",
				"focus": -0.1707985547020494,
				"gap": 5.8759823269319895
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					4.547473508864641e-13,
					-220.84177652994777
				]
			]
		},
		{
			"type": "arrow",
			"version": 77,
			"versionNonce": 638293008,
			"isDeleted": false,
			"id": "oloOndgrIDsC7yr8qF-vM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2500.5143560152383,
			"y": 2668.9878428328234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 377.6785956488725,
			"height": 0,
			"seed": 121773296,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					377.6785956488725,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 136,
			"versionNonce": 1093891312,
			"isDeleted": false,
			"id": "mmproRAcyvVdq7Z6NV47T",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1642.3775553348553,
			"y": 2699.5709949239126,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.547473508864641e-13,
			"height": 220.84177652994777,
			"seed": 1177290992,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					4.547473508864641e-13,
					-220.84177652994777
				]
			]
		},
		{
			"type": "arrow",
			"version": 92,
			"versionNonce": 899584528,
			"isDeleted": false,
			"id": "irUjB8ykwqeTCvZbVHi8Z",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1905.2843376970511,
			"y": 2673.2802370029053,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 326.0044691297744,
			"height": 0,
			"seed": 1738369776,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					326.0044691297744,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 37,
			"versionNonce": 1725388528,
			"isDeleted": false,
			"id": "Y9SdMgBzLGbYN9FAstYQw",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2452.3456311074683,
			"y": 2668.9878428328234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 76.24296400282083,
			"height": 76.24296400282083,
			"seed": 1154904592,
			"groupIds": [
				"NbYdlUMGp3Z8_xAMBwlBP"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					76.24296400282083,
					-76.24296400282083
				]
			]
		},
		{
			"type": "line",
			"version": 48,
			"versionNonce": 371314704,
			"isDeleted": false,
			"id": "fNFtD4AZQOYxLdAq9jBPU",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2375.2263039861573,
			"y": 2593.621224994282,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 108.66814507378467,
			"height": 0,
			"seed": 793223920,
			"groupIds": [
				"NbYdlUMGp3Z8_xAMBwlBP"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					108.66814507378467,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 85,
			"versionNonce": 833550576,
			"isDeleted": false,
			"id": "WKg7o7HJQFpEJR4qNZ_Wg",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2268.3108512409317,
			"y": 2593.621258902702,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.98483615451414,
			"height": 70.98483615451369,
			"seed": 1789561360,
			"groupIds": [
				"NbYdlUMGp3Z8_xAMBwlBP"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					70.98483615451414,
					70.98483615451369
				]
			]
		},
		{
			"type": "line",
			"version": 60,
			"versionNonce": 1066225168,
			"isDeleted": false,
			"id": "jTl-TCabpNCEIAcxbQ5C8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1896.557731368754,
			"y": 2671.63629485581,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 76.24296400282083,
			"height": 76.24296400282083,
			"seed": 620998160,
			"groupIds": [
				"le030NdnDlFegdR6IS-wG"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					76.24296400282083,
					-76.24296400282083
				]
			]
		},
		{
			"type": "line",
			"version": 71,
			"versionNonce": 1161976560,
			"isDeleted": false,
			"id": "P4bDRiSxAkgf07kLy4xbI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1819.4384042474426,
			"y": 2596.269677017269,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 108.66814507378467,
			"height": 0,
			"seed": 310602768,
			"groupIds": [
				"le030NdnDlFegdR6IS-wG"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					108.66814507378467,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 108,
			"versionNonce": 1792609296,
			"isDeleted": false,
			"id": "CcWlqcMq4wS4WR7Lj6MB1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1712.522951502217,
			"y": 2596.2697109256887,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.98483615451414,
			"height": 70.98483615451369,
			"seed": 1968925200,
			"groupIds": [
				"le030NdnDlFegdR6IS-wG"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					70.98483615451414,
					70.98483615451369
				]
			]
		},
		{
			"type": "line",
			"version": 62,
			"versionNonce": 337214704,
			"isDeleted": false,
			"id": "jGwDjyBE3N-NbA60HaDlu",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2390.6182195406277,
			"y": 2683.009555072407,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 2111136272,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 64,
			"versionNonce": 1912408592,
			"isDeleted": false,
			"id": "yUgCxyZnTyUUa1Qc4Kyog",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2261.7302149288716,
			"y": 2679.305712277263,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 1267437808,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 64,
			"versionNonce": 2143051504,
			"isDeleted": false,
			"id": "iUgKGb8axPxttsnk-zvKA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2325.7302149288716,
			"y": 2681.7057122772644,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 549188112,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 68,
			"versionNonce": 804341776,
			"isDeleted": false,
			"id": "LAXtG2S9l45IhGprGL9N6",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2198.530214928871,
			"y": 2680.657885128827,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 58915568,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 64,
			"versionNonce": 2024997104,
			"isDeleted": false,
			"id": "XA_7snHEZ6lLvC3OpUEYu",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1892.9302149288715,
			"y": 2687.305712277263,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 481470480,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 64,
			"versionNonce": 1622001168,
			"isDeleted": false,
			"id": "lQzFk1esRwTuo5eBo1WpZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1831.330214928871,
			"y": 2683.305712277263,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 26748144,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 69,
			"versionNonce": 512058096,
			"isDeleted": false,
			"id": "3VzNrRWR-SQyEeXhX4t34",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1763.4541407101215,
			"y": 2685.491576535077,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 2042076688,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 68,
			"versionNonce": 19563536,
			"isDeleted": false,
			"id": "vCzE_LIF54DlnEuYbMR98",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1705.0540918819963,
			"y": 2685.8296136444505,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 2066943728,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 1606124784,
			"isDeleted": false,
			"id": "a64uKK7w",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2128.0004235540305,
			"y": 2683.9338989444773,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 627976720,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 794788368,
			"isDeleted": false,
			"id": "5vJlJeKj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1578.400423554031,
			"y": 2692.7338989444775,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 438191856,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 17,
			"versionNonce": 433940208,
			"isDeleted": false,
			"id": "9o3ILhTq",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1617.6004235540308,
			"y": 2474.3338989444774,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 45.8199462890625,
			"height": 25,
			"seed": 877221904,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(-t)",
			"rawText": "x(-t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(-t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 172277776,
			"isDeleted": false,
			"id": "pY4JBO6g",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1766.4004235540308,
			"y": 2571.9338989444773,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.1199951171875,
			"height": 25,
			"seed": 451936496,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A",
			"rawText": "A",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 963840240,
			"isDeleted": false,
			"id": "ixkhO7N1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2318.400423554031,
			"y": 2572.7338989444775,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.1199951171875,
			"height": 25,
			"seed": 1550138896,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A",
			"rawText": "A",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 16,
			"versionNonce": 298991120,
			"isDeleted": false,
			"id": "qdaTxjgj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2429.600423554031,
			"y": 2463.1338989444776,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.59996032714844,
			"height": 25,
			"seed": 526152432,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(t)",
			"rawText": "x(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 126,
			"versionNonce": 1510238960,
			"isDeleted": false,
			"id": "VgqpIsHr",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2458.8960412298125,
			"y": 2690.6382934757276,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 392865296,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "8gwmRdizJeVLH-tOZefHN",
					"type": "arrow"
				}
			],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 30,
			"versionNonce": 117439504,
			"isDeleted": false,
			"id": "9Crr21YV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2396.000423554031,
			"y": 2687.009973163227,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 206.0797119140625,
			"height": 25,
			"seed": 1864230416,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1      2     3     4",
			"rawText": "1      2     3     4",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1      2     3     4",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 45,
			"versionNonce": 1712950512,
			"isDeleted": false,
			"id": "SEAkas03",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1900.00042355403,
			"y": 2699.1338989444776,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 262.7196350097656,
			"height": 25,
			"seed": 663384592,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-4    -3     -2    -1    0",
			"rawText": "-4    -3     -2    -1    0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-4    -3     -2    -1    0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 316,
			"versionNonce": 1271265808,
			"isDeleted": false,
			"id": "NtgY17Tn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2526.0127219472815,
			"y": 2769.8447086521187,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1082.078857421875,
			"height": 75,
			"seed": 128050416,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The signal x(-t + 3) obtained by shifting the reversed signal x(-t) to the right by 3 units (delay by 3 units)\nis whown below. the signal x(-t - 3) obtained by shifting the reversed signal x(-t) to the left by 3 units\n(advance by 3 units) is also shown below:",
			"rawText": "The signal x(-t + 3) obtained by shifting the reversed signal x(-t) to the right by 3 units (delay by 3 units)\nis whown below. the signal x(-t - 3) obtained by shifting the reversed signal x(-t) to the left by 3 units\n(advance by 3 units) is also shown below:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The signal x(-t + 3) obtained by shifting the reversed signal x(-t) to the right by 3 units (delay by 3 units)\nis whown below. the signal x(-t - 3) obtained by shifting the reversed signal x(-t) to the left by 3 units\n(advance by 3 units) is also shown below:",
			"lineHeight": 1.25,
			"baseline": 66
		},
		{
			"type": "arrow",
			"version": 121,
			"versionNonce": 926576368,
			"isDeleted": false,
			"id": "DjQYbQBhtuFBqYZRP0kBr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2466.7454349497525,
			"y": 3077.720923590812,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.547473508864641e-13,
			"height": 220.84177652994777,
			"seed": 711392272,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "KHChKOlG",
				"focus": -0.1707985547020494,
				"gap": 5.8759823269319895
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-4.547473508864641e-13,
					-220.84177652994777
				]
			]
		},
		{
			"type": "arrow",
			"version": 129,
			"versionNonce": 1125922832,
			"isDeleted": false,
			"id": "lpEBbWO3gklcsTQ2lw0KR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2605.584079587633,
			"y": 3061.9464552748395,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 469.1940218351465,
			"height": 0,
			"seed": 1783429648,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "TzcUfqjx",
				"focus": 2.195684488932311,
				"gap": 14.946056111653888
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					469.1940218351465,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 89,
			"versionNonce": 904859888,
			"isDeleted": false,
			"id": "5Vi0hseNLBZHW-E09kiFZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2543.5910011717724,
			"y": 3062.7900133568082,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 76.24296400282083,
			"height": 76.24296400282083,
			"seed": 2026059792,
			"groupIds": [
				"92JWVzDVzkIwXeIKL7zKb"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					76.24296400282083,
					-76.24296400282083
				]
			]
		},
		{
			"type": "line",
			"version": 100,
			"versionNonce": 821736976,
			"isDeleted": false,
			"id": "EGKyonLYWzfY1Hjxw0NQd",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2466.471674050461,
			"y": 2987.423395518267,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 108.66814507378467,
			"height": 0,
			"seed": 432125456,
			"groupIds": [
				"92JWVzDVzkIwXeIKL7zKb"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					108.66814507378467,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 137,
			"versionNonce": 2042589936,
			"isDeleted": false,
			"id": "71mwOhmDuPpAvPNlySBoI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2359.5562213052353,
			"y": 2987.423429426687,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.98483615451414,
			"height": 70.98483615451369,
			"seed": 1379955728,
			"groupIds": [
				"92JWVzDVzkIwXeIKL7zKb"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					70.98483615451414,
					70.98483615451369
				]
			]
		},
		{
			"type": "line",
			"version": 64,
			"versionNonce": 442070032,
			"isDeleted": false,
			"id": "RuCzx7Z_CT08iH3yu3AVA",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2404.172516926749,
			"y": 3075.968167514423,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 1211593232,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 66,
			"versionNonce": 1764988144,
			"isDeleted": false,
			"id": "lph-CgopAiKZDmJl8cTVT",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2275.2845123149923,
			"y": 3072.264324719279,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 580825104,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 66,
			"versionNonce": 623931920,
			"isDeleted": false,
			"id": "yNlindQEBuZFH40VXbcqQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2339.2845123149923,
			"y": 3074.6643247192806,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 1768828432,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 70,
			"versionNonce": 1507030768,
			"isDeleted": false,
			"id": "9EzFpdgYWWipOvFU26ji2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2212.0845123149916,
			"y": 3073.6164975708434,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 1704848400,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "text",
			"version": 16,
			"versionNonce": 2021109776,
			"isDeleted": false,
			"id": "TzcUfqjx",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2141.5547209401507,
			"y": 3076.8925113864934,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 19261968,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "lpEBbWO3gklcsTQ2lw0KR",
					"type": "arrow"
				}
			],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 41,
			"versionNonce": 807868656,
			"isDeleted": false,
			"id": "K3UZb0D2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2405.0906517817716,
			"y": 2955.654225697573,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.1199951171875,
			"height": 25,
			"seed": 654190608,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A",
			"rawText": "A",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 23,
			"versionNonce": 472329744,
			"isDeleted": false,
			"id": "Pdztu4vS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2443.154720940151,
			"y": 2856.092511386494,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 91.93988037109375,
			"height": 25,
			"seed": 589211152,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097102,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(-t + 3)",
			"rawText": "x(-t + 3)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(-t + 3)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 134,
			"versionNonce": 2142665456,
			"isDeleted": false,
			"id": "KHChKOlG",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2472.4503386159327,
			"y": 3083.596905917744,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 41903120,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "DjQYbQBhtuFBqYZRP0kBr",
					"type": "arrow"
				}
			],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 34,
			"versionNonce": 1496771600,
			"isDeleted": false,
			"id": "XzwAB7z2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2405.84306537949,
			"y": 3079.968585605244,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 206.0797119140625,
			"height": 25,
			"seed": 1930977808,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1      2     3     4",
			"rawText": "1      2     3     4",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1      2     3     4",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 722050288,
			"isDeleted": false,
			"id": "RXYZJO7l",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2551.609074463291,
			"y": 3077.2991063432432,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.639984130859375,
			"height": 25,
			"seed": 1671844592,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-1",
			"rawText": "-1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 68,
			"versionNonce": 429845008,
			"isDeleted": false,
			"id": "cDNres747CdXnbOR3GCo1",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2540.649339493941,
			"y": 3074.314411201545,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 2141325840,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "arrow",
			"version": 210,
			"versionNonce": 61374192,
			"isDeleted": false,
			"id": "VPEX9DO1z7rxQ8jPbuULq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1528.7945153438895,
			"y": 3090.3362279117473,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 4.547473508864641e-13,
			"height": 220.84177652994777,
			"seed": 308069104,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					4.547473508864641e-13,
					-220.84177652994777
				]
			]
		},
		{
			"type": "arrow",
			"version": 253,
			"versionNonce": 1213671440,
			"isDeleted": false,
			"id": "dOXdwKsK4DftP2Z20-SdV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2009.322982286498,
			"y": 3064.0454699907405,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 543.6261537101866,
			"height": 0,
			"seed": 564585712,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					543.6261537101866,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 211,
			"versionNonce": 1780162800,
			"isDeleted": false,
			"id": "53QDuIaOR-h3qhSp4FvnH",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1975.1356688280725,
			"y": 3062.401472357139,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 76.24296400282083,
			"height": 76.24296400282083,
			"seed": 1197262576,
			"groupIds": [
				"f58w6AwPEkhFtyj6teEcX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					76.24296400282083,
					-76.24296400282083
				]
			]
		},
		{
			"type": "line",
			"version": 222,
			"versionNonce": 827827728,
			"isDeleted": false,
			"id": "FpSvJFKyxgh9N5wS_W2nY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1898.016341706761,
			"y": 2987.034854518598,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 108.66814507378467,
			"height": 0,
			"seed": 1074161904,
			"groupIds": [
				"f58w6AwPEkhFtyj6teEcX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					108.66814507378467,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 259,
			"versionNonce": 1844019952,
			"isDeleted": false,
			"id": "AK25C0dpoGwcBui3R7lhR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1791.1008889615355,
			"y": 2987.034888427018,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.98483615451414,
			"height": 70.98483615451369,
			"seed": 1999358704,
			"groupIds": [
				"f58w6AwPEkhFtyj6teEcX"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					70.98483615451414,
					70.98483615451369
				]
			]
		},
		{
			"type": "line",
			"version": 138,
			"versionNonce": 1637377040,
			"isDeleted": false,
			"id": "9fvmii6h8HqSfQnnqa6FK",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1779.347174937906,
			"y": 3078.070945265097,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 659877104,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 138,
			"versionNonce": 1838916848,
			"isDeleted": false,
			"id": "xR6bSiOurA6ePfHxjtyxG",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1717.7471749379056,
			"y": 3074.070945265097,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 2047463152,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 143,
			"versionNonce": 118579728,
			"isDeleted": false,
			"id": "cR-8y297xcwsMBzknnh-k",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1649.871100719156,
			"y": 3076.2568095229117,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 668102896,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 142,
			"versionNonce": 918128368,
			"isDeleted": false,
			"id": "YubTHg2LSGqj4ux8ga5ao",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1591.4710518910306,
			"y": 3076.594846632285,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 406246128,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "text",
			"version": 87,
			"versionNonce": 1354407952,
			"isDeleted": false,
			"id": "Cp6H1tnj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1464.8173835630655,
			"y": 3083.4991319323126,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 29291760,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 97,
			"versionNonce": 634071280,
			"isDeleted": false,
			"id": "dIt2fVlR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1504.0173835630653,
			"y": 2865.099131932312,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87.65988159179688,
			"height": 25,
			"seed": 166909680,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(-t - 3)",
			"rawText": "x(-t - 3)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(-t - 3)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 117,
			"versionNonce": 1317805584,
			"isDeleted": false,
			"id": "aajgyalN",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1859.3187374338036,
			"y": 2942.6226160409765,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.1199951171875,
			"height": 25,
			"seed": 1700428016,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A",
			"rawText": "A",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 119,
			"versionNonce": 1180207856,
			"isDeleted": false,
			"id": "xzWCUtqx",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1786.4173835630645,
			"y": 3089.8991319323122,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 262.7196350097656,
			"height": 25,
			"seed": 2004736752,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-4    -3     -2    -1    0",
			"rawText": "-4    -3     -2    -1    0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-4    -3     -2    -1    0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 145,
			"versionNonce": 1367202832,
			"isDeleted": false,
			"id": "jfgoBvd9byeOAcgoHAtfs",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1906.8872364396166,
			"y": 3072.608413934865,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 1407902736,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 140,
			"versionNonce": 1927916784,
			"isDeleted": false,
			"id": "amRGmtPuOPjIFW5HHjgdY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1969.6145091668895,
			"y": 3075.438225724638,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 813738224,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "line",
			"version": 140,
			"versionNonce": 1267194384,
			"isDeleted": false,
			"id": "XOoX7E7GKUjonq6yD-7Ko",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1845.069054621435,
			"y": 3069.983680270093,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 21.03251139322947,
			"seed": 2051693072,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-21.03251139322947
				]
			]
		},
		{
			"type": "text",
			"version": 33,
			"versionNonce": 1963364080,
			"isDeleted": false,
			"id": "OB9WmbDQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1976.4257960072011,
			"y": 3084.8904893541876,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 140.57980346679688,
			"height": 25,
			"seed": 1780678672,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-7    -6    -5",
			"rawText": "-7    -6    -5",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-7    -6    -5",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 75,
			"versionNonce": 799152144,
			"isDeleted": false,
			"id": "AWGCZUo7",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2237.841346932717,
			"y": 3161.838329264521,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 420.3795166015625,
			"height": 25,
			"seed": 735658224,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The same applies for discrete time signals",
			"rawText": "The same applies for discrete time signals",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The same applies for discrete time signals",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "rectangle",
			"version": 261,
			"versionNonce": 624374000,
			"isDeleted": false,
			"id": "CVZnsrrZHoLztl0FrTV3S",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2606.1274797452174,
			"y": 2264.6430777996766,
			"strokeColor": "#a8ff05",
			"backgroundColor": "transparent",
			"width": 1233.5588378906255,
			"height": 946.4646606445317,
			"seed": 1062227184,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 190,
			"versionNonce": 1371837968,
			"isDeleted": false,
			"id": "YMv4c_rrumq_OvyAbaLIr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1332.393593026467,
			"y": 1629.0941886395206,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 131.07098943536926,
			"height": 644.4563598632815,
			"seed": 165541392,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Nk9cQkG4lbeEz0woUdakw",
				"focus": 0.7241093325382365,
				"gap": 3.203187292251414
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-131.07098943536926,
					-7.17022705078125
				],
				[
					-117.30434348366475,
					343.02166193181824
				],
				[
					-124.18761097301126,
					510.8040771484377
				],
				[
					-50.47802734375,
					637.2861328125002
				]
			]
		},
		{
			"type": "text",
			"version": 137,
			"versionNonce": 184783600,
			"isDeleted": false,
			"id": "ohK8RKAR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -610.9391188961972,
			"y": 2319.629082675523,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 552.6458129882812,
			"height": 44.45506361874323,
			"seed": 635329264,
			"groupIds": [
				"fvcKK9IbYRGbr5BEs3Pj0",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"fontSize": 35.56405089499459,
			"fontFamily": 1,
			"text": "CLASSIFICATION OF SIGNALS",
			"rawText": "CLASSIFICATION OF SIGNALS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CLASSIFICATION OF SIGNALS",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "line",
			"version": 132,
			"versionNonce": 1189565456,
			"isDeleted": false,
			"id": "ptgSB4J7qhpkS9DHe2PG9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -750.057094535414,
			"y": 2373.1247534907225,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 804.1026697780508,
			"height": 0,
			"seed": 20282608,
			"groupIds": [
				"fvcKK9IbYRGbr5BEs3Pj0",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					804.1026697780508,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 131,
			"versionNonce": 2096346352,
			"isDeleted": false,
			"id": "IIoiFsFt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -830.5157062775021,
			"y": 2421.288660391189,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 611.1141357421875,
			"height": 36.47233442826715,
			"seed": 1208412176,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"fontSize": 29.177867542613722,
			"fontFamily": 1,
			"text": "PERIODIC AND NON-PERIODIC SIGNALS",
			"rawText": "PERIODIC AND NON-PERIODIC SIGNALS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "PERIODIC AND NON-PERIODIC SIGNALS",
			"lineHeight": 1.25,
			"baseline": 25
		},
		{
			"type": "text",
			"version": 627,
			"versionNonce": 1157779984,
			"isDeleted": false,
			"id": "IlNcL5zs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -838.7842343590504,
			"y": 2472.0928500979667,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 765.5391845703125,
			"height": 500,
			"seed": 1416379120,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A periodic continuous-time signal satisfies\n                x(t) = x(t + nT\n\nWhere\n n is an integer\n T is the period of the signal\n\nA periodic signal is on that repeats itself every T seconds.\n\n\nA popular example of a periodic signal is the sinusoid:\n                x(t) = Asin(wt +  )\nWhere\nA is the amplitude of the signal\nw  is the angular frequency in radians per second\n   is the phase in radians\n\n\nA non periodic signal is one which does not repeat itself after T seconds. An\nis the ramp function",
			"rawText": "A periodic continuous-time signal satisfies\n                x(t) = x(t + nT\n\nWhere\n n is an integer\n T is the period of the signal\n\nA periodic signal is on that repeats itself every T seconds.\n\n\nA popular example of a periodic signal is the sinusoid:\n                x(t) = Asin(wt +  )\nWhere\nA is the amplitude of the signal\nw  is the angular frequency in radians per second\n   is the phase in radians\n\n\nA non periodic signal is one which does not repeat itself after T seconds. An\nis the ramp function",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A periodic continuous-time signal satisfies\n                x(t) = x(t + nT\n\nWhere\n n is an integer\n T is the period of the signal\n\nA periodic signal is on that repeats itself every T seconds.\n\n\nA popular example of a periodic signal is the sinusoid:\n                x(t) = Asin(wt +  )\nWhere\nA is the amplitude of the signal\nw  is the angular frequency in radians per second\n   is the phase in radians\n\n\nA non periodic signal is one which does not repeat itself after T seconds. An\nis the ramp function",
			"lineHeight": 1.25,
			"baseline": 490
		},
		{
			"type": "line",
			"version": 702,
			"versionNonce": 1083152112,
			"isDeleted": false,
			"id": "IrhipiIhdec0GI1gbjp2I",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.71238898038469,
			"x": -511.1424010737105,
			"y": 2745.87400732534,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.046487292187056,
			"height": 14.09502370824567,
			"seed": 227716112,
			"groupIds": [
				"7T0sRmROz09fBkc4c7xhx",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					14.09502370824567
				],
				[
					15.046487292187056,
					7.2767156089229985
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 730,
			"versionNonce": 51220496,
			"isDeleted": false,
			"id": "b1Dq_x4awUy5Ptx-G5OjG",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.71238898038469,
			"x": -833.496650749152,
			"y": 2844.4653161800975,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.44141736977378,
			"height": 15.466695965379149,
			"seed": 1191845392,
			"groupIds": [
				"gbSMkTu3F-hWeWtnniSlt",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097103,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					15.466695965379149
				],
				[
					16.44141736977378,
					7.984856945213957
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 114,
			"versionNonce": 710883568,
			"isDeleted": false,
			"id": "myRnOhgY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -834.3487068255035,
			"y": 3039.315455241221,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 543.6622314453125,
			"height": 40.423848828734066,
			"seed": 866406640,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 32.33907906298725,
			"fontFamily": 1,
			"text": "ANALOG AND DIGITAL SIGNALS",
			"rawText": "ANALOG AND DIGITAL SIGNALS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "ANALOG AND DIGITAL SIGNALS",
			"lineHeight": 1.25,
			"baseline": 27
		},
		{
			"type": "text",
			"version": 583,
			"versionNonce": 419499536,
			"isDeleted": false,
			"id": "6M2ZQosr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -833.2641120989409,
			"y": 3101.7900820548366,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 978.2590942382812,
			"height": 225,
			"seed": 1711618288,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "If a continuous time signal x(t) can assume any value in the range of -   < t  <   , then it is \ncalled an analog signal. Although all analog signals are continuous-time signals, not all continuous\ntime signals are analog signals.\n\nIf a discrete-time signal assumes only finite values, then it is called a digital signal.\n\n\n    An ANALOG SIGNAL is a continuous-time signal in which the variations withe time is analogous\n     (or proportional) to some physical phenomena.",
			"rawText": "If a continuous time signal x(t) can assume any value in the range of -   < t  <   , then it is \ncalled an analog signal. Although all analog signals are continuous-time signals, not all continuous\ntime signals are analog signals.\n\nIf a discrete-time signal assumes only finite values, then it is called a digital signal.\n\n\n    An ANALOG SIGNAL is a continuous-time signal in which the variations withe time is analogous\n     (or proportional) to some physical phenomena.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "If a continuous time signal x(t) can assume any value in the range of -   < t  <   , then it is \ncalled an analog signal. Although all analog signals are continuous-time signals, not all continuous\ntime signals are analog signals.\n\nIf a discrete-time signal assumes only finite values, then it is called a digital signal.\n\n\n    An ANALOG SIGNAL is a continuous-time signal in which the variations withe time is analogous\n     (or proportional) to some physical phenomena.",
			"lineHeight": 1.25,
			"baseline": 216
		},
		{
			"type": "text",
			"version": 149,
			"versionNonce": 1038785264,
			"isDeleted": false,
			"id": "YieOTteI",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -821.5132314488294,
			"y": 3362.8156736672768,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1027.218994140625,
			"height": 25,
			"seed": 589214960,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A DIGITAL SIGNAL is a discrete-time signal that can have a finite number of values (usually binary).",
			"rawText": "A DIGITAL SIGNAL is a discrete-time signal that can have a finite number of values (usually binary).",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A DIGITAL SIGNAL is a discrete-time signal that can have a finite number of values (usually binary).",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 296,
			"versionNonce": 1607781392,
			"isDeleted": false,
			"id": "0YBzISwn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -815.2962776262855,
			"y": 3472.39371975015,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 980.9990234375,
			"height": 50,
			"seed": 914456080,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A digital signal can assume only finite number of values. The difference between analog and digital\nsignals is that analog is a continuous electric signal, whereas digital is a discrete electric signal.",
			"rawText": "A digital signal can assume only finite number of values. The difference between analog and digital\nsignals is that analog is a continuous electric signal, whereas digital is a discrete electric signal.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A digital signal can assume only finite number of values. The difference between analog and digital\nsignals is that analog is a continuous electric signal, whereas digital is a discrete electric signal.",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "text",
			"version": 61,
			"versionNonce": 1304018160,
			"isDeleted": false,
			"id": "f0nBBq5p",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -823.8654943626204,
			"y": 3572.3375530197372,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 592.6975708007812,
			"height": 47.861469655796796,
			"seed": 1627524624,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 38.28917572463744,
			"fontFamily": 1,
			"text": "ENERGY AND POWER SIGNALS",
			"rawText": "ENERGY AND POWER SIGNALS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "ENERGY AND POWER SIGNALS",
			"lineHeight": 1.25,
			"baseline": 33
		},
		{
			"type": "line",
			"version": 107,
			"versionNonce": 1367394832,
			"isDeleted": false,
			"id": "pkzKoSolj69UOZfO9ZH2R",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -835.1156889674663,
			"y": 3006.188092959729,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1101.922563193501,
			"height": 0,
			"seed": 920017936,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1101.922563193501,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 109,
			"versionNonce": 458530544,
			"isDeleted": false,
			"id": "ai_bULRQmYG98p5n6XGwn",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -827.2856959909049,
			"y": 3545.5465808660656,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1101.922563193501,
			"height": 0,
			"seed": 602428944,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1101.922563193501,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 434,
			"versionNonce": 1761413136,
			"isDeleted": false,
			"id": "GQJVhMYL6VZcBvbNP7Nh9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -894.3959496801201,
			"y": 2267.0616406281615,
			"strokeColor": "#ced4da",
			"backgroundColor": "transparent",
			"width": 1194.3480199697071,
			"height": 3418.9170811400854,
			"seed": 852054032,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "ULLmPUoIxmP0p7KOr_UXW",
					"type": "arrow"
				}
			],
			"updated": 1703931097104,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 122,
			"versionNonce": 2000896240,
			"isDeleted": false,
			"id": "zTtCcZQl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -794.5432794434913,
			"y": 3662.702689253453,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 896.1790771484375,
			"height": 25,
			"seed": 445934096,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "For continuous-time signals x(t), the normalized energy E of x(t) (assuming x(t) is real) is:",
			"rawText": "For continuous-time signals x(t), the normalized energy E of x(t) (assuming x(t) is real) is:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "For continuous-time signals x(t), the normalized energy E of x(t) (assuming x(t) is real) is:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 73,
			"versionNonce": 37848592,
			"isDeleted": false,
			"id": "qXl8f47u",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -338.8292503231505,
			"y": 3720.666504963429,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80.2799072265625,
			"height": 25,
			"seed": 1239935728,
			"groupIds": [
				"zkZWLYQjwxzv6dZSAQZRg",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(t)  dt",
			"rawText": "x(t)  dt",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t)  dt",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 101,
			"versionNonce": 1628283632,
			"isDeleted": false,
			"id": "lFcr209R",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -302.9295741506364,
			"y": 3709.9426761890995,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 1228678672,
			"groupIds": [
				"zkZWLYQjwxzv6dZSAQZRg",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 98,
			"versionNonce": 977683472,
			"isDeleted": false,
			"id": "oFcBDWzZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -408.9484752219802,
			"y": 3721.4244598643245,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 45.81993103027344,
			"height": 25,
			"seed": 2074544368,
			"groupIds": [
				"zkZWLYQjwxzv6dZSAQZRg",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "E = ",
			"rawText": "E = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3212,
			"versionNonce": 658228464,
			"isDeleted": false,
			"id": "YtkK2bLLEn7PfgM1WkcOg",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -339.39995204446774,
			"y": 3700.92438844822,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 2119899376,
			"groupIds": [
				"zkZWLYQjwxzv6dZSAQZRg",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 4591,
			"versionNonce": 1325613584,
			"isDeleted": false,
			"id": "66DPl_9cAgzv4zaRltGGp",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -348.2010279057267,
			"y": 3706.7844805527616,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 1927489552,
			"groupIds": [
				"zkZWLYQjwxzv6dZSAQZRg",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3190,
			"versionNonce": 123053808,
			"isDeleted": false,
			"id": "Z_NAYSty1tKoRLjeqyXzj",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -328.7073084609773,
			"y": 3762.5259458048063,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 575891184,
			"groupIds": [
				"zkZWLYQjwxzv6dZSAQZRg",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 58,
			"versionNonce": 2138079248,
			"isDeleted": false,
			"id": "l9NJkgiKW56WxJH4dZuBm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -367.4253392300965,
			"y": 3762.9965692771743,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 15.951709533005669,
			"height": 0,
			"seed": 641328144,
			"groupIds": [
				"zkZWLYQjwxzv6dZSAQZRg",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.951709533005669,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 91,
			"versionNonce": 1306740976,
			"isDeleted": false,
			"id": "rmXKKUPX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -793.3209787139447,
			"y": 3788.356916724944,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 653.1992797851562,
			"height": 25,
			"seed": 1114817776,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "If x(t) is complex valued, The above equation can be generalized:",
			"rawText": "If x(t) is complex valued, The above equation can be generalized:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "If x(t) is complex valued, The above equation can be generalized:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 129,
			"versionNonce": 1803943440,
			"isDeleted": false,
			"id": "ySw2k17w",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -330.2271077113784,
			"y": 3842.5579681681456,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 106.9998779296875,
			"height": 25,
			"seed": 1111794704,
			"groupIds": [
				"eNmdvk3I2JjvfP5G10GHL",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "| x(t) |  dt",
			"rawText": "| x(t) |  dt",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "| x(t) |  dt",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 184,
			"versionNonce": 1986833136,
			"isDeleted": false,
			"id": "shvHdiQA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -265.96898921091486,
			"y": 3828.2892998134093,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 137732624,
			"groupIds": [
				"eNmdvk3I2JjvfP5G10GHL",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 144,
			"versionNonce": 1950071824,
			"isDeleted": false,
			"id": "CaJ1Xtev",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -400.34633261020815,
			"y": 3843.3159230690408,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 45.81993103027344,
			"height": 25,
			"seed": 592896016,
			"groupIds": [
				"eNmdvk3I2JjvfP5G10GHL",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "E = ",
			"rawText": "E = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3258,
			"versionNonce": 1266273520,
			"isDeleted": false,
			"id": "Eq_WSL3TeT4sQo7WH7_C8",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -330.79780943269566,
			"y": 3822.8158516529365,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 60841488,
			"groupIds": [
				"eNmdvk3I2JjvfP5G10GHL",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 4637,
			"versionNonce": 462010896,
			"isDeleted": false,
			"id": "IU2y7ujoAIAGqJlahoMvv",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -339.5988852939546,
			"y": 3828.6759437574783,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 1510611984,
			"groupIds": [
				"eNmdvk3I2JjvfP5G10GHL",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3236,
			"versionNonce": 110276336,
			"isDeleted": false,
			"id": "yEScB0qX1UjL3AwEpFvjl",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -320.10516584920526,
			"y": 3884.417409009523,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 18.103371308638394,
			"height": 7.371235523356667,
			"seed": 2022447632,
			"groupIds": [
				"eNmdvk3I2JjvfP5G10GHL",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.723515117468466,
					1.2693130715717729
				],
				[
					5.757153658937881,
					0.1584407104143679
				],
				[
					5.7283129925924925,
					-3.323864263730762
				],
				[
					1.8737579923465546,
					-3.818380599554409
				],
				[
					-5.642652705846473,
					1.5844174034657996
				],
				[
					-10.37585740063659,
					0.7566303771615281
				],
				[
					-11.022134662038823,
					-4.048092503367329
				],
				[
					-6.702342819435515,
					-5.399847052321768
				],
				[
					-2.73161136209535,
					-2.6386109638197226
				],
				[
					-3.411205543837127,
					-1.9016727488717535
				],
				[
					-6.699727873671321,
					-4.416263059451445
				],
				[
					-9.906204458463634,
					-3.8833707396822987
				],
				[
					-10.284032657324445,
					-1.2855896499681094
				],
				[
					-8.345697690100593,
					0.9802582205000405
				],
				[
					-4.775693241404568,
					0.07248360697317935
				],
				[
					1.8620677622442514,
					-4.833352206265836
				],
				[
					6.069452277623235,
					-4.299906621635387
				],
				[
					7.081236646599571,
					-1.287045371459051
				],
				[
					5.824745339266876,
					1.39186688531899
				],
				[
					1.84362529405945,
					1.9713884710348992
				],
				[
					-1.697560475237168,
					-0.2684438869301857
				],
				[
					-1.1760757628919691,
					-0.9349252260650047
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 104,
			"versionNonce": 1684535312,
			"isDeleted": false,
			"id": "6cF16-QL4tWafV8gpN-ZM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -358.82319661832446,
			"y": 3884.888032481891,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 15.951709533005669,
			"height": 0,
			"seed": 840849424,
			"groupIds": [
				"eNmdvk3I2JjvfP5G10GHL",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.951709533005669,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 107,
			"versionNonce": 1883197680,
			"isDeleted": false,
			"id": "FEkJOveu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -791.1532362740746,
			"y": 3913.819446625313,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 771.979248046875,
			"height": 25,
			"seed": 1901753072,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Where |x(t)| is the magnitude of x(t). The normalized power P for real x(t) is:",
			"rawText": "Where |x(t)| is the magnitude of x(t). The normalized power P for real x(t) is:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Where |x(t)| is the magnitude of x(t). The normalized power P for real x(t) is:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 129,
			"versionNonce": 852391440,
			"isDeleted": false,
			"id": "m64ZnkJB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -311.86522958418425,
			"y": 3975.057959264929,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80.2799072265625,
			"height": 25,
			"seed": 1712513040,
			"groupIds": [
				"fKkGPcx-YlfAwcDDBieNl",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(t)  dt",
			"rawText": "x(t)  dt",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t)  dt",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 152,
			"versionNonce": 504560,
			"isDeleted": false,
			"id": "2WUxSGaj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -273.1980909322294,
			"y": 3962.9503992508794,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 249323024,
			"groupIds": [
				"fKkGPcx-YlfAwcDDBieNl",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 169,
			"versionNonce": 733295632,
			"isDeleted": false,
			"id": "Bymc7IAW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -456.7053257223915,
			"y": 3977.1995918659345,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 77.85989379882812,
			"height": 25,
			"seed": 499522576,
			"groupIds": [
				"fKkGPcx-YlfAwcDDBieNl",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "P = lim ",
			"rawText": "P = lim ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "P = lim ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 4632,
			"versionNonce": 2087965936,
			"isDeleted": false,
			"id": "rzPA1E2mI0fqWdC2gMtEf",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -324.0044161065904,
			"y": 3965.327075033812,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 920279056,
			"groupIds": [
				"fKkGPcx-YlfAwcDDBieNl",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 98,
			"versionNonce": 353645072,
			"isDeleted": false,
			"id": "6-6rE772kyoexFPB2TWch",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -337.6938560116893,
			"y": 4021.5391637582247,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 15.951709533005669,
			"height": 0,
			"seed": 219124752,
			"groupIds": [
				"fKkGPcx-YlfAwcDDBieNl",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097104,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.951709533005669,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 29,
			"versionNonce": 453752560,
			"isDeleted": false,
			"id": "2f8bArm8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -311.4921800668318,
			"y": 4015.8070221841417,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 24.698290590588826,
			"height": 15.313934861567885,
			"seed": 1051943440,
			"groupIds": [
				"fKkGPcx-YlfAwcDDBieNl",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 12.251147889254307,
			"fontFamily": 1,
			"text": "T/2",
			"rawText": "T/2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T/2",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 904097808,
			"isDeleted": false,
			"id": "5BmJTXhE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -332.5817539771936,
			"y": 3946.6077177707643,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 24.698290590589565,
			"height": 15.313934861568343,
			"seed": 591753232,
			"groupIds": [
				"fKkGPcx-YlfAwcDDBieNl",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 12.251147889254675,
			"fontFamily": 1,
			"text": "T/2",
			"rawText": "T/2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T/2",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "text",
			"version": 75,
			"versionNonce": 542595312,
			"isDeleted": false,
			"id": "5CrbbMMe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -368.66040356250807,
			"y": 3965.564821843987,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 1266088464,
			"groupIds": [
				"fKkGPcx-YlfAwcDDBieNl",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 93,
			"versionNonce": 907734544,
			"isDeleted": false,
			"id": "rPZKHwOV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -373.49088109300425,
			"y": 3997.984073403061,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 16.079986572265625,
			"height": 25,
			"seed": 1147236880,
			"groupIds": [
				"fKkGPcx-YlfAwcDDBieNl",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "T",
			"rawText": "T",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 165,
			"versionNonce": 2145303280,
			"isDeleted": false,
			"id": "v-cLTzureglWBxY68Fc74",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -374.8763096026771,
			"y": 3991.091769925222,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 15.951709533005669,
			"height": 0,
			"seed": 1149730544,
			"groupIds": [
				"fKkGPcx-YlfAwcDDBieNl",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.951709533005669,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 71,
			"versionNonce": 2125638672,
			"isDeleted": false,
			"id": "94xUPpPJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -418.4403883770846,
			"y": 4002.310049636374,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 7.777679443359367,
			"height": 12.092173411348057,
			"seed": 137485040,
			"groupIds": [
				"fKkGPcx-YlfAwcDDBieNl",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 9.673738729078446,
			"fontFamily": 1,
			"text": "T",
			"rawText": "T",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "line",
			"version": 2468,
			"versionNonce": 2083118320,
			"isDeleted": false,
			"id": "Sb7cpkggF3dWSHmuDJMJq",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -405.6772436034232,
			"y": 4008.0450573956086,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.497780189546306,
			"height": 3.0724039323585393,
			"seed": 1004217584,
			"groupIds": [
				"fKkGPcx-YlfAwcDDBieNl",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.1426339408329302,
					-0.03376268057536724
				],
				[
					3.7612626693433566,
					-0.23633876402758025
				],
				[
					1.6826701415483325,
					-1.3505072230147483
				],
				[
					2.1033376769354195,
					-1.4517952647408507
				],
				[
					4.4293816961346195,
					-0.2194574237398903
				],
				[
					4.132439906449593,
					0.6246095906443212
				],
				[
					2.5487503614629348,
					1.6206086676176887
				],
				[
					2.0291022295141636,
					1.586845987042321
				],
				[
					3.687027221922099,
					0.5064402086305362
				],
				[
					3.1426339408329302,
					0.28698278489063034
				],
				[
					-2.647730958024623,
					0.35450814604136915
				],
				[
					-3.0683984934116864,
					0.06752536115074337
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3373,
			"versionNonce": 430090768,
			"isDeleted": false,
			"id": "XYR5DKJLY_MeQ9FFFnP2d",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -391.44740388995405,
			"y": 4008.624481136566,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 10.65337745130407,
			"height": 4.672878604967847,
			"seed": 96885776,
			"groupIds": [
				"fKkGPcx-YlfAwcDDBieNl",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.6027199600595596,
					0.8046610200365407
				],
				[
					3.3879397338856534,
					0.10044099167707232
				],
				[
					3.370967729097908,
					-2.107111372929215
				],
				[
					1.1026593226500505,
					-2.4206022114942445
				],
				[
					-3.320558810685191,
					1.0044164458636833
				],
				[
					-6.105930402982059,
					0.4796539047088828
				],
				[
					-6.486248272318793,
					-2.5662244531432292
				],
				[
					-3.944159717334685,
					-3.4231479486633893
				],
				[
					-1.6074843958366207,
					-1.6727058415916756
				],
				[
					-2.007408432546324,
					-1.2055354728112966
				],
				[
					-3.9426208877009277,
					-2.799620375584349
				],
				[
					-5.829551491077596,
					-2.4618016867213206
				],
				[
					-6.051893857346684,
					-0.8149793004264851
				],
				[
					-4.911232613601253,
					0.6214192520920299
				],
				[
					-2.810375030425826,
					0.04594984045247674
				],
				[
					1.0957799170603846,
					-3.064027467765517
				],
				[
					3.5717195948659337,
					-2.725858045361949
				],
				[
					4.1671291789852765,
					-0.8159021321265798
				],
				[
					3.427715733109017,
					0.8823520790729771
				],
				[
					1.0849269896494222,
					1.249730656304458
				],
				[
					-0.998971527501463,
					-0.17017577201213063
				],
				[
					-0.6920909260387309,
					-0.5926811146219415
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 69,
			"versionNonce": 1187036912,
			"isDeleted": false,
			"id": "pCpwyQAR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -794.7238529214106,
			"y": 4050.171568712045,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 510.939453125,
			"height": 25,
			"seed": 798460144,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "This can be generalized for complex values x(t) as:",
			"rawText": "This can be generalized for complex values x(t) as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "This can be generalized for complex values x(t) as:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 159,
			"versionNonce": 300083216,
			"isDeleted": false,
			"id": "8ZUw0C9y",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -302.4362739524886,
			"y": 4111.308660355442,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 106.9998779296875,
			"height": 25,
			"seed": 1398311152,
			"groupIds": [
				"g02Dgfu7x0QIV537IfgmI",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "| x(t) |  dt",
			"rawText": "| x(t) |  dt",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "| x(t) |  dt",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 207,
			"versionNonce": 539713776,
			"isDeleted": false,
			"id": "oicN13Cb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -233.49501963213083,
			"y": 4099.201100341392,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 456780528,
			"groupIds": [
				"g02Dgfu7x0QIV537IfgmI",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 194,
			"versionNonce": 1399547408,
			"isDeleted": false,
			"id": "SJ2cWVna",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -447.2763700906957,
			"y": 4113.450292956446,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 77.85989379882812,
			"height": 25,
			"seed": 1688145136,
			"groupIds": [
				"g02Dgfu7x0QIV537IfgmI",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "P = lim ",
			"rawText": "P = lim ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "P = lim ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 4657,
			"versionNonce": 2012332784,
			"isDeleted": false,
			"id": "_cEftl-WUmt0zlf6Wma87",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -314.5754604748947,
			"y": 4101.577776124324,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 1225780976,
			"groupIds": [
				"g02Dgfu7x0QIV537IfgmI",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 123,
			"versionNonce": 187966480,
			"isDeleted": false,
			"id": "30a4Vlq_AlZTpsHS4LobK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -328.2649003799936,
			"y": 4157.789864848737,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 15.951709533005669,
			"height": 0,
			"seed": 1897173232,
			"groupIds": [
				"g02Dgfu7x0QIV537IfgmI",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.951709533005669,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 54,
			"versionNonce": 211543280,
			"isDeleted": false,
			"id": "nocNyVjO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -302.06322443513614,
			"y": 4152.057723274655,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 24.698290590588826,
			"height": 15.313934861567885,
			"seed": 875885296,
			"groupIds": [
				"g02Dgfu7x0QIV537IfgmI",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 12.251147889254307,
			"fontFamily": 1,
			"text": "T/2",
			"rawText": "T/2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T/2",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "text",
			"version": 71,
			"versionNonce": 120922640,
			"isDeleted": false,
			"id": "5OtleyKn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -323.152798345498,
			"y": 4082.8584188612767,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 24.698290590589565,
			"height": 15.313934861568343,
			"seed": 955847920,
			"groupIds": [
				"g02Dgfu7x0QIV537IfgmI",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 12.251147889254675,
			"fontFamily": 1,
			"text": "T/2",
			"rawText": "T/2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T/2",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "text",
			"version": 100,
			"versionNonce": 196200176,
			"isDeleted": false,
			"id": "w0CsDPgu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -359.23144793081246,
			"y": 4101.815522934499,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 350811888,
			"groupIds": [
				"g02Dgfu7x0QIV537IfgmI",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 118,
			"versionNonce": 375808016,
			"isDeleted": false,
			"id": "60L5kf41",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -364.06192546130865,
			"y": 4134.234774493572,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 16.079986572265625,
			"height": 25,
			"seed": 1821153520,
			"groupIds": [
				"g02Dgfu7x0QIV537IfgmI",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "T",
			"rawText": "T",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 190,
			"versionNonce": 834365680,
			"isDeleted": false,
			"id": "G9nKNfc2UlKXGKHsDPjxV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -365.44735397098145,
			"y": 4127.342471015734,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 15.951709533005669,
			"height": 0,
			"seed": 325843696,
			"groupIds": [
				"g02Dgfu7x0QIV537IfgmI",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.951709533005669,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 96,
			"versionNonce": 1757404688,
			"isDeleted": false,
			"id": "HcVbjWmZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -409.0114327453889,
			"y": 4138.560750726887,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 7.777679443359367,
			"height": 12.092173411348057,
			"seed": 739187952,
			"groupIds": [
				"g02Dgfu7x0QIV537IfgmI",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 9.673738729078446,
			"fontFamily": 1,
			"text": "T",
			"rawText": "T",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T",
			"lineHeight": 1.25,
			"baseline": 8
		},
		{
			"type": "line",
			"version": 2493,
			"versionNonce": 1782631152,
			"isDeleted": false,
			"id": "0AG3LGh6qNydHYrcdXAoe",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -396.24828797172756,
			"y": 4144.2957584861215,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.497780189546306,
			"height": 3.0724039323585393,
			"seed": 1207828208,
			"groupIds": [
				"g02Dgfu7x0QIV537IfgmI",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.1426339408329302,
					-0.03376268057536724
				],
				[
					3.7612626693433566,
					-0.23633876402758025
				],
				[
					1.6826701415483325,
					-1.3505072230147483
				],
				[
					2.1033376769354195,
					-1.4517952647408507
				],
				[
					4.4293816961346195,
					-0.2194574237398903
				],
				[
					4.132439906449593,
					0.6246095906443212
				],
				[
					2.5487503614629348,
					1.6206086676176887
				],
				[
					2.0291022295141636,
					1.586845987042321
				],
				[
					3.687027221922099,
					0.5064402086305362
				],
				[
					3.1426339408329302,
					0.28698278489063034
				],
				[
					-2.647730958024623,
					0.35450814604136915
				],
				[
					-3.0683984934116864,
					0.06752536115074337
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3398,
			"versionNonce": 1866046480,
			"isDeleted": false,
			"id": "_snLjTn-UboRMawpZknuZ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -382.01844825825833,
			"y": 4144.875182227079,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 10.65337745130407,
			"height": 4.672878604967847,
			"seed": 130064624,
			"groupIds": [
				"g02Dgfu7x0QIV537IfgmI",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.6027199600595596,
					0.8046610200365407
				],
				[
					3.3879397338856534,
					0.10044099167707232
				],
				[
					3.370967729097908,
					-2.107111372929215
				],
				[
					1.1026593226500505,
					-2.4206022114942445
				],
				[
					-3.320558810685191,
					1.0044164458636833
				],
				[
					-6.105930402982059,
					0.4796539047088828
				],
				[
					-6.486248272318793,
					-2.5662244531432292
				],
				[
					-3.944159717334685,
					-3.4231479486633893
				],
				[
					-1.6074843958366207,
					-1.6727058415916756
				],
				[
					-2.007408432546324,
					-1.2055354728112966
				],
				[
					-3.9426208877009277,
					-2.799620375584349
				],
				[
					-5.829551491077596,
					-2.4618016867213206
				],
				[
					-6.051893857346684,
					-0.8149793004264851
				],
				[
					-4.911232613601253,
					0.6214192520920299
				],
				[
					-2.810375030425826,
					0.04594984045247674
				],
				[
					1.0957799170603846,
					-3.064027467765517
				],
				[
					3.5717195948659337,
					-2.725858045361949
				],
				[
					4.1671291789852765,
					-0.8159021321265798
				],
				[
					3.427715733109017,
					0.8823520790729771
				],
				[
					1.0849269896494222,
					1.249730656304458
				],
				[
					-0.998971527501463,
					-0.17017577201213063
				],
				[
					-0.6920909260387309,
					-0.5926811146219415
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 91,
			"versionNonce": 1875504368,
			"isDeleted": false,
			"id": "MBvcLUZb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -790.6834488810066,
			"y": 4202.696821237296,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 747.6593017578125,
			"height": 25,
			"seed": 2083938544,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Similarly, for a discrete-time signal x[n], the normalized energy E of x[n] is",
			"rawText": "Similarly, for a discrete-time signal x[n], the normalized energy E of x[n] is",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Similarly, for a discrete-time signal x[n], the normalized energy E of x[n] is",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 111,
			"versionNonce": 1003198992,
			"isDeleted": false,
			"id": "jGEynDIW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -384.6289767017749,
			"y": 4252.6912817884695,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 142.9398193359375,
			"height": 25,
			"seed": 921959440,
			"groupIds": [
				"9pkQu_HukLW8N78NvvZqG",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "E =    | x[n] |",
			"rawText": "E =    | x[n] |",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "E =    | x[n] |",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 131,
			"versionNonce": 1809764080,
			"isDeleted": false,
			"id": "wSiJVrUT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -234.57367032019727,
			"y": 4241.42376038301,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 1287035632,
			"groupIds": [
				"9pkQu_HukLW8N78NvvZqG",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 1867,
			"versionNonce": 1634588688,
			"isDeleted": false,
			"id": "Xa8SwYAaq35oyYruBZ9j-",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -328.6838692223031,
			"y": 4245.422085485893,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 20.3192084036864,
			"height": 32.618601391763576,
			"seed": 1935704304,
			"groupIds": [
				"9pkQu_HukLW8N78NvvZqG",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097105,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.843215143654266,
					0.18480793989663538
				],
				[
					9.8366007463286,
					2.1562530948622793
				],
				[
					-5.484077008607414,
					2.757119593628204
				],
				[
					-6.257472484180191,
					5.636642166848667
				],
				[
					2.0389517083284083,
					15.431462981372556
				],
				[
					2.3201864267185357,
					19.035217809357736
				],
				[
					-4.99191625142479,
					26.797151285018206
				],
				[
					-6.538707202570457,
					30.40090611300341
				],
				[
					9.913523823251808,
					30.46234829690127
				],
				[
					9.91352382325178,
					32.618601391763576
				],
				[
					-10.405684580434592,
					32.156581542021826
				],
				[
					-6.819941920960652,
					25.873111585534826
				],
				[
					-0.0703086795975878,
					18.850409869461078
				],
				[
					-0.4921607571828126,
					15.708674891217575
				],
				[
					-9.843215143654337,
					4.43539055752022
				],
				[
					-8.858893629288854,
					1.1088476393800382
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 76,
			"versionNonce": 386363632,
			"isDeleted": false,
			"id": "0GqIUjYs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -343.79702017337246,
			"y": 4284.860889472282,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 28.752847092642046,
			"height": 14.405253396104852,
			"seed": 388650512,
			"groupIds": [
				"9pkQu_HukLW8N78NvvZqG",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 11.524202716883883,
			"fontFamily": 1,
			"text": "n = -",
			"rawText": "n = -",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "n = -",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "line",
			"version": 3472,
			"versionNonce": 1410881040,
			"isDeleted": false,
			"id": "Rj_IWz_tdk7gLEvxSVFIn",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -309.2408351548207,
			"y": 4291.528555886668,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 6.138584068415392,
			"height": 2.6925600157519516,
			"seed": 912101616,
			"groupIds": [
				"xEgmvNTdNeMmhg2ACFanE",
				"9pkQu_HukLW8N78NvvZqG",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.9235034859061202,
					0.46365383566378293
				],
				[
					1.9521652142941952,
					0.057875117458571414
				],
				[
					1.9423857731099001,
					-1.2141389304343893
				],
				[
					0.6353634780940527,
					-1.3947755291098554
				],
				[
					-1.9133396433835497,
					0.5787549367152556
				],
				[
					-3.518298986957487,
					0.2763814415905035
				],
				[
					-3.737441998111981,
					-1.4786845407523528
				],
				[
					-2.2726648065166173,
					-1.972452544514106
				],
				[
					-0.9262488020924415,
					-0.9638300602109164
				],
				[
					-1.156689085612298,
					-0.694641758553592
				],
				[
					-2.271778117284309,
					-1.6131696369276314
				],
				[
					-3.359046656584546,
					-1.4185150843271583
				],
				[
					-3.487162581656377,
					-0.46959933340895127
				],
				[
					-2.829902011445615,
					0.35806807166414606
				],
				[
					-1.6193665780547963,
					0.026476763809140668
				],
				[
					0.6313994948647039,
					-1.7655236834315104
				],
				[
					2.0580610329550697,
					-1.570667034609998
				],
				[
					2.401142070303411,
					-0.47013107838822416
				],
				[
					1.975084548210028,
					0.5084202113450472
				],
				[
					0.6251459280869262,
					0.7201074712378456
				],
				[
					-0.5756175195661001,
					-0.0980570047085004
				],
				[
					-0.39878980650931123,
					-0.3415088655685973
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3432,
			"versionNonce": 1489752816,
			"isDeleted": false,
			"id": "GER5tZbw749oLe2q0f9pT",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -326.04750246583876,
			"y": 4235.563801653194,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 10.65337745130407,
			"height": 4.672878604967847,
			"seed": 143258128,
			"groupIds": [
				"b7WMigv_XgfCXOEzV-ROp",
				"9pkQu_HukLW8N78NvvZqG",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.6027199600595596,
					0.8046610200365407
				],
				[
					3.3879397338856534,
					0.10044099167707232
				],
				[
					3.370967729097908,
					-2.107111372929215
				],
				[
					1.1026593226500505,
					-2.4206022114942445
				],
				[
					-3.320558810685191,
					1.0044164458636833
				],
				[
					-6.105930402982059,
					0.4796539047088828
				],
				[
					-6.486248272318793,
					-2.5662244531432292
				],
				[
					-3.944159717334685,
					-3.4231479486633893
				],
				[
					-1.6074843958366207,
					-1.6727058415916756
				],
				[
					-2.007408432546324,
					-1.2055354728112966
				],
				[
					-3.9426208877009277,
					-2.799620375584349
				],
				[
					-5.829551491077596,
					-2.4618016867213206
				],
				[
					-6.051893857346684,
					-0.8149793004264851
				],
				[
					-4.911232613601253,
					0.6214192520920299
				],
				[
					-2.810375030425826,
					0.04594984045247674
				],
				[
					1.0957799170603846,
					-3.064027467765517
				],
				[
					3.5717195948659337,
					-2.725858045361949
				],
				[
					4.1671291789852765,
					-0.8159021321265798
				],
				[
					3.427715733109017,
					0.8823520790729771
				],
				[
					1.0849269896494222,
					1.249730656304458
				],
				[
					-0.998971527501463,
					-0.17017577201213063
				],
				[
					-0.6920909260387309,
					-0.5926811146219415
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 43,
			"versionNonce": 1220744208,
			"isDeleted": false,
			"id": "ekYSSSl8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -783.128120409496,
			"y": 4314.637482580957,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 311.879638671875,
			"height": 25,
			"seed": 428111088,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "While the normalized power P is:",
			"rawText": "While the normalized power P is:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "While the normalized power P is:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 222,
			"versionNonce": 1739846896,
			"isDeleted": false,
			"id": "W8te6slb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -366.7067698397905,
			"y": 4366.945637123451,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 147.11981201171875,
			"height": 25,
			"seed": 679913200,
			"groupIds": [
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "        | x[n] |",
			"rawText": "        | x[n] |",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "        | x[n] |",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 225,
			"versionNonce": 359010832,
			"isDeleted": false,
			"id": "8aQvqLAg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -220.18307602526045,
			"y": 4349.792185870158,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 552880368,
			"groupIds": [
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 1961,
			"versionNonce": 1766315760,
			"isDeleted": false,
			"id": "NBTcS6jRqQgh0mesQjnIF",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -314.29327492736627,
			"y": 4353.790510973043,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 20.3192084036864,
			"height": 32.618601391763576,
			"seed": 1063103216,
			"groupIds": [
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.843215143654266,
					0.18480793989663538
				],
				[
					9.8366007463286,
					2.1562530948622793
				],
				[
					-5.484077008607414,
					2.757119593628204
				],
				[
					-6.257472484180191,
					5.636642166848667
				],
				[
					2.0389517083284083,
					15.431462981372556
				],
				[
					2.3201864267185357,
					19.035217809357736
				],
				[
					-4.99191625142479,
					26.797151285018206
				],
				[
					-6.538707202570457,
					30.40090611300341
				],
				[
					9.913523823251808,
					30.46234829690127
				],
				[
					9.91352382325178,
					32.618601391763576
				],
				[
					-10.405684580434592,
					32.156581542021826
				],
				[
					-6.819941920960652,
					25.873111585534826
				],
				[
					-0.0703086795975878,
					18.850409869461078
				],
				[
					-0.4921607571828126,
					15.708674891217575
				],
				[
					-9.843215143654337,
					4.43539055752022
				],
				[
					-8.858893629288854,
					1.1088476393800382
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 170,
			"versionNonce": 284774416,
			"isDeleted": false,
			"id": "uhC4Y6Id",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -329.4064258784356,
			"y": 4393.2293149594325,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 28.752847092642046,
			"height": 14.405253396104852,
			"seed": 1313524976,
			"groupIds": [
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 11.524202716883883,
			"fontFamily": 1,
			"text": "n = -",
			"rawText": "n = -",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "n = -",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "text",
			"version": 92,
			"versionNonce": 303003888,
			"isDeleted": false,
			"id": "IheiWA3h",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -321.3147203686846,
			"y": 4337.487815268109,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.160736083984375,
			"height": 15.860296970548992,
			"seed": 2108493040,
			"groupIds": [
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 12.688237576439194,
			"fontFamily": 1,
			"text": "N",
			"rawText": "N",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "N",
			"lineHeight": 1.25,
			"baseline": 11
		},
		{
			"type": "text",
			"version": 128,
			"versionNonce": 1937034768,
			"isDeleted": false,
			"id": "sMLYC0gH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -300.5737331888003,
			"y": 4391.393704489808,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.160736083984375,
			"height": 15.860296970548992,
			"seed": 1300094192,
			"groupIds": [
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 12.688237576439194,
			"fontFamily": 1,
			"text": "N",
			"rawText": "N",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "N",
			"lineHeight": 1.25,
			"baseline": 11
		},
		{
			"type": "text",
			"version": 257,
			"versionNonce": 1167252208,
			"isDeleted": false,
			"id": "OjU9aqxc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -430.93683008074447,
			"y": 4375.196978160517,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.160736083984375,
			"height": 15.860296970548992,
			"seed": 637602832,
			"groupIds": [
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 12.688237576439194,
			"fontFamily": 1,
			"text": "N",
			"rawText": "N",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "N",
			"lineHeight": 1.25,
			"baseline": 11
		},
		{
			"type": "text",
			"version": 100,
			"versionNonce": 902859792,
			"isDeleted": false,
			"id": "YKEJKgq8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -377.32886959326487,
			"y": 4373.862208195131,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.25956726074219,
			"height": 15.880932430342853,
			"seed": 2074978032,
			"groupIds": [
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 12.704745944274283,
			"fontFamily": 1,
			"text": "2N + 1",
			"rawText": "2N + 1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2N + 1",
			"lineHeight": 1.25,
			"baseline": 11
		},
		{
			"type": "text",
			"version": 140,
			"versionNonce": 911867120,
			"isDeleted": false,
			"id": "8lcpFKhh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -357.9850794536723,
			"y": 4353.992495844717,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.4429849877441,
			"height": 15.880932430342853,
			"seed": 1178791440,
			"groupIds": [
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 12.704745944274283,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 10
		},
		{
			"type": "line",
			"version": 239,
			"versionNonce": 1912900112,
			"isDeleted": false,
			"id": "6KzwArFxm8MiVkmmgIbp6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -375.0814935880439,
			"y": 4370.511861063648,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40.38109811811783,
			"height": 0,
			"seed": 92496112,
			"groupIds": [
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					20.93833859926557,
					0
				],
				[
					40.38109811811783,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3530,
			"versionNonce": 99409648,
			"isDeleted": false,
			"id": "R_n6lJFPblnLMoML-cRy8",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -393.26697759993334,
			"y": 4385.091371324371,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 10.65337745130407,
			"height": 4.672878604967847,
			"seed": 216504048,
			"groupIds": [
				"bDxmnNRub3ec76313TS6h",
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.6027199600595596,
					0.8046610200365407
				],
				[
					3.3879397338856534,
					0.10044099167707232
				],
				[
					3.370967729097908,
					-2.107111372929215
				],
				[
					1.1026593226500505,
					-2.4206022114942445
				],
				[
					-3.320558810685191,
					1.0044164458636833
				],
				[
					-6.105930402982059,
					0.4796539047088828
				],
				[
					-6.486248272318793,
					-2.5662244531432292
				],
				[
					-3.944159717334685,
					-3.4231479486633893
				],
				[
					-1.6074843958366207,
					-1.6727058415916756
				],
				[
					-2.007408432546324,
					-1.2055354728112966
				],
				[
					-3.9426208877009277,
					-2.799620375584349
				],
				[
					-5.829551491077596,
					-2.4618016867213206
				],
				[
					-6.051893857346684,
					-0.8149793004264851
				],
				[
					-4.911232613601253,
					0.6214192520920299
				],
				[
					-2.810375030425826,
					0.04594984045247674
				],
				[
					1.0957799170603846,
					-3.064027467765517
				],
				[
					3.5717195948659337,
					-2.725858045361949
				],
				[
					4.1671291789852765,
					-0.8159021321265798
				],
				[
					3.427715733109017,
					0.8823520790729771
				],
				[
					1.0849269896494222,
					1.249730656304458
				],
				[
					-0.998971527501463,
					-0.17017577201213063
				],
				[
					-0.6920909260387309,
					-0.5926811146219415
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 2623,
			"versionNonce": 1124648976,
			"isDeleted": false,
			"id": "X_0GuI6LD-FWZwOls422x",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -411.1645262563077,
			"y": 4381.997881275993,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 7.497780189546306,
			"height": 3.0724039323585393,
			"seed": 2074910448,
			"groupIds": [
				"cgnc8IJ17GntaIZYqNfng",
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.1426339408329302,
					-0.03376268057536724
				],
				[
					3.7612626693433566,
					-0.23633876402758025
				],
				[
					1.6826701415483325,
					-1.3505072230147483
				],
				[
					2.1033376769354195,
					-1.4517952647408507
				],
				[
					4.4293816961346195,
					-0.2194574237398903
				],
				[
					4.132439906449593,
					0.6246095906443212
				],
				[
					2.5487503614629348,
					1.6206086676176887
				],
				[
					2.0291022295141636,
					1.586845987042321
				],
				[
					3.687027221922099,
					0.5064402086305362
				],
				[
					3.1426339408329302,
					0.28698278489063034
				],
				[
					-2.647730958024623,
					0.35450814604136915
				],
				[
					-3.0683984934116864,
					0.06752536115074337
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 135,
			"versionNonce": 1691582704,
			"isDeleted": false,
			"id": "jxQsg3T1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -425.5938314052985,
			"y": 4356.084316405002,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 22.299972534179688,
			"height": 25,
			"seed": 547468016,
			"groupIds": [
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "lim",
			"rawText": "lim",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "lim",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 81,
			"versionNonce": 617956880,
			"isDeleted": false,
			"id": "o5QI9qIv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -470.57977054504903,
			"y": 4360.696296786298,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 45.5599365234375,
			"height": 25,
			"seed": 1308239088,
			"groupIds": [
				"9QPWqGoYlLoSRY6mqerZw",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "P = ",
			"rawText": "P = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "P = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 113,
			"versionNonce": 848683760,
			"isDeleted": false,
			"id": "VFAC5hWq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -783.3145185255867,
			"y": 4437.973730868437,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 826.9791259765625,
			"height": 25,
			"seed": 70960656,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Based on the definitions of E and P in the equation above, we define the following:",
			"rawText": "Based on the definitions of E and P in the equation above, we define the following:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Based on the definitions of E and P in the equation above, we define the following:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 163,
			"versionNonce": 1415709712,
			"isDeleted": false,
			"id": "2X0aFDYW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -757.4245710843996,
			"y": 4486.1464823058495,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 907.0791015625,
			"height": 25,
			"seed": 74595056,
			"groupIds": [
				"XT44UQ5Ec2Fr2HpecfdUk",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A signal x(t) or x[n] is an ENERGY SIGNAL if and only if  0 < E <    consequently P = 0",
			"rawText": "A signal x(t) or x[n] is an ENERGY SIGNAL if and only if  0 < E <    consequently P = 0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A signal x(t) or x[n] is an ENERGY SIGNAL if and only if  0 < E <    consequently P = 0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3611,
			"versionNonce": 498861296,
			"isDeleted": false,
			"id": "YMj-vTCnYa41Q1UpLonGC",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -56.002449268951224,
			"y": 4497.116632650859,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 26.33715001093348,
			"height": 11.615808331854543,
			"seed": 1996893200,
			"groupIds": [
				"iCOq5qowbtA1NZCtQJraA",
				"bzX08dQqITCdwxk7Cwcsh",
				"XT44UQ5Ec2Fr2HpecfdUk",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097106,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.9622247692386914,
					2.000220628655372
				],
				[
					8.375623355804983,
					0.24967550125139581
				],
				[
					8.33366537223364,
					-5.237842433098056
				],
				[
					2.725980950579558,
					-6.017115725302229
				],
				[
					-8.209045057953672,
					2.4967712424867017
				],
				[
					-15.095006791482179,
					1.1923202577530567
				],
				[
					-16.03522399699704,
					-6.379102455719604
				],
				[
					-9.750703625901194,
					-8.509236773448897
				],
				[
					-3.9740033493511007,
					-4.158000259378885
				],
				[
					-4.9626906831047926,
					-2.9967114862646893
				],
				[
					-9.746899350018658,
					-6.959276376272605
				],
				[
					-14.411746210886172,
					-6.119529087186257
				],
				[
					-14.961418301355293,
					-2.0258697365086142
				],
				[
					-12.141489464186007,
					1.5447195478931315
				],
				[
					-6.9477749288087365,
					0.11422178590469478
				],
				[
					2.7089737678500168,
					-7.61653764154371
				],
				[
					8.82996169026751,
					-6.775918501522025
				],
				[
					10.301926013936441,
					-2.028163704971536
				],
				[
					8.473957096740097,
					2.1933445094911868
				],
				[
					2.682143292858699,
					3.106571558405646
				],
				[
					-2.4696452460000664,
					-0.4230217211970322
				],
				[
					-1.7109787598914643,
					-1.4732824905914192
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 169,
			"versionNonce": 799474192,
			"isDeleted": false,
			"id": "PHnbCuq6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -767.2040147180891,
			"y": 4529.887258453586,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 908.2391357421875,
			"height": 25,
			"seed": 495243504,
			"groupIds": [
				"jnUKXVnyFqBEn6y5blpRE",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A signal x(t) or x[n] is a POWER SIGNAL if and only if 0 < P <    and consequently E = ",
			"rawText": "A signal x(t) or x[n] is a POWER SIGNAL if and only if 0 < P <    and consequently E = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A signal x(t) or x[n] is a POWER SIGNAL if and only if 0 < P <    and consequently E = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 3648,
			"versionNonce": 1137567472,
			"isDeleted": false,
			"id": "LFekQUWbAk9mj4X1tKiwh",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -96.70439471312173,
			"y": 4543.310816343361,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 26.33715001093348,
			"height": 11.615808331854543,
			"seed": 920179728,
			"groupIds": [
				"LwDGR-AdQb_Qhu5ZgdrII",
				"_CzkxKvPFuohYxniO85_u",
				"P2f0x_T1uDj-oy3m5dRrh",
				"jnUKXVnyFqBEn6y5blpRE",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.9622247692386914,
					2.000220628655372
				],
				[
					8.375623355804983,
					0.24967550125139581
				],
				[
					8.33366537223364,
					-5.237842433098056
				],
				[
					2.725980950579558,
					-6.017115725302229
				],
				[
					-8.209045057953672,
					2.4967712424867017
				],
				[
					-15.095006791482179,
					1.1923202577530567
				],
				[
					-16.03522399699704,
					-6.379102455719604
				],
				[
					-9.750703625901194,
					-8.509236773448897
				],
				[
					-3.9740033493511007,
					-4.158000259378885
				],
				[
					-4.9626906831047926,
					-2.9967114862646893
				],
				[
					-9.746899350018658,
					-6.959276376272605
				],
				[
					-14.411746210886172,
					-6.119529087186257
				],
				[
					-14.961418301355293,
					-2.0258697365086142
				],
				[
					-12.141489464186007,
					1.5447195478931315
				],
				[
					-6.9477749288087365,
					0.11422178590469478
				],
				[
					2.7089737678500168,
					-7.61653764154371
				],
				[
					8.82996169026751,
					-6.775918501522025
				],
				[
					10.301926013936441,
					-2.028163704971536
				],
				[
					8.473957096740097,
					2.1933445094911868
				],
				[
					2.682143292858699,
					3.106571558405646
				],
				[
					-2.4696452460000664,
					-0.4230217211970322
				],
				[
					-1.7109787598914643,
					-1.4732824905914192
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3654,
			"versionNonce": 362561552,
			"isDeleted": false,
			"id": "cSyIsnvxx3lgnc-oBC0EF",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 153.08184508234882,
			"y": 4539.76604534178,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 26.33715001093348,
			"height": 11.615808331854543,
			"seed": 614840560,
			"groupIds": [
				"weQLonq2Tx4kVRhrPf3SR",
				"8sehhEG19I8hygM7nbjrR",
				"XavXtyvLiJUvRe3U5zRao",
				"jnUKXVnyFqBEn6y5blpRE",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.9622247692386914,
					2.000220628655372
				],
				[
					8.375623355804983,
					0.24967550125139581
				],
				[
					8.33366537223364,
					-5.237842433098056
				],
				[
					2.725980950579558,
					-6.017115725302229
				],
				[
					-8.209045057953672,
					2.4967712424867017
				],
				[
					-15.095006791482179,
					1.1923202577530567
				],
				[
					-16.03522399699704,
					-6.379102455719604
				],
				[
					-9.750703625901194,
					-8.509236773448897
				],
				[
					-3.9740033493511007,
					-4.158000259378885
				],
				[
					-4.9626906831047926,
					-2.9967114862646893
				],
				[
					-9.746899350018658,
					-6.959276376272605
				],
				[
					-14.411746210886172,
					-6.119529087186257
				],
				[
					-14.961418301355293,
					-2.0258697365086142
				],
				[
					-12.141489464186007,
					1.5447195478931315
				],
				[
					-6.9477749288087365,
					0.11422178590469478
				],
				[
					2.7089737678500168,
					-7.61653764154371
				],
				[
					8.82996169026751,
					-6.775918501522025
				],
				[
					10.301926013936441,
					-2.028163704971536
				],
				[
					8.473957096740097,
					2.1933445094911868
				],
				[
					2.682143292858699,
					3.106571558405646
				],
				[
					-2.4696452460000664,
					-0.4230217211970322
				],
				[
					-1.7109787598914643,
					-1.4732824905914192
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 176,
			"versionNonce": 1364429040,
			"isDeleted": false,
			"id": "ivPeyMjy",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -874.9682059162931,
			"y": 4618.503691891876,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1163.1190185546875,
			"height": 25,
			"seed": 1845814512,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Or in otherwords, A POWER SIGNAL HAS INFINITE ENERGY AND AN ENERGY SIGNAL HAS ZERO AVERAGE POWER",
			"rawText": "Or in otherwords, A POWER SIGNAL HAS INFINITE ENERGY AND AN ENERGY SIGNAL HAS ZERO AVERAGE POWER",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Or in otherwords, A POWER SIGNAL HAS INFINITE ENERGY AND AN ENERGY SIGNAL HAS ZERO AVERAGE POWER",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "rectangle",
			"version": 65,
			"versionNonce": 1178189328,
			"isDeleted": false,
			"id": "cKACRzJbeDKE8BOX9NxCx",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -844.8016012559679,
			"y": 3259.79011776526,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 1072.1251406912081,
			"height": 139.02872376522782,
			"seed": 1572367888,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 175,
			"versionNonce": 567601904,
			"isDeleted": false,
			"id": "O--wz2Y0DcfURaXDLAmju",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -820.7317149675673,
			"y": 4472.136624692234,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 1037.3679985434328,
			"height": 93.57708429886074,
			"seed": 538588176,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 108,
			"versionNonce": 1115126800,
			"isDeleted": false,
			"id": "0v2LcOl2",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -842.7415095584043,
			"y": 4709.975602570612,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 548.3350830078125,
			"height": 50.02906291105579,
			"seed": 947837680,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 40.02325032884463,
			"fontFamily": 1,
			"text": "EVEN AND ODD SYMMETRY",
			"rawText": "EVEN AND ODD SYMMETRY",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "EVEN AND ODD SYMMETRY",
			"lineHeight": 1.25,
			"baseline": 35
		},
		{
			"type": "line",
			"version": 169,
			"versionNonce": 1608125680,
			"isDeleted": false,
			"id": "1FyvXo4synh1qTLiAsCwO",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -837.3852837586439,
			"y": 4672.639511058502,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1101.922563193501,
			"height": 0,
			"seed": 828175088,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1101.922563193501,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 105,
			"versionNonce": 743275024,
			"isDeleted": false,
			"id": "Tle7gDTc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -840.8307234335138,
			"y": 4783.23463361671,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 322.859619140625,
			"height": 25,
			"seed": 757944560,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "By definition, a signal is even if ",
			"rawText": "By definition, a signal is even if ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "By definition, a signal is even if ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 65,
			"versionNonce": 619376368,
			"isDeleted": false,
			"id": "iBSjoApS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -424.26764466703924,
			"y": 4831.111913201659,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 185.66761779785156,
			"height": 40.1031494140625,
			"seed": 2012136976,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 32.08251953125,
			"fontFamily": 1,
			"text": "x(t) = x(-t)",
			"rawText": "x(t) = x(-t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t) = x(-t)",
			"lineHeight": 1.25,
			"baseline": 27
		},
		{
			"type": "text",
			"version": 218,
			"versionNonce": 649312272,
			"isDeleted": false,
			"id": "XAuk5Gav",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -841.5362211532022,
			"y": 4888.067197900836,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1083.678955078125,
			"height": 50,
			"seed": 1407713008,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A function is even if its plot is symmetric about the vertical axis; that is the signal for t < 0 is the mirror\nimage of the signal for t > 0. Examples are cos, t, t^2, and t^4.",
			"rawText": "A function is even if its plot is symmetric about the vertical axis; that is the signal for t < 0 is the mirror\nimage of the signal for t > 0. Examples are cos, t, t^2, and t^4.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A function is even if its plot is symmetric about the vertical axis; that is the signal for t < 0 is the mirror\nimage of the signal for t > 0. Examples are cos, t, t^2, and t^4.",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 428839152,
			"isDeleted": false,
			"id": "sODkHIyR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -837.0713046804624,
			"y": 4979.556559602964,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 299.879638671875,
			"height": 25,
			"seed": 1047186672,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "By definition a signal is odd if",
			"rawText": "By definition a signal is odd if",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "By definition a signal is odd if",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 90,
			"versionNonce": 899823120,
			"isDeleted": false,
			"id": "W2uCA9QH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -441.83294145505306,
			"y": 4986.7007571075355,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 198.8516845703125,
			"height": 40.1031494140625,
			"seed": 372090896,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 32.08251953125,
			"fontFamily": 1,
			"text": "x(t) = -x(-t)",
			"rawText": "x(t) = -x(-t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t) = -x(-t)",
			"lineHeight": 1.25,
			"baseline": 27
		},
		{
			"type": "text",
			"version": 203,
			"versionNonce": 357561072,
			"isDeleted": false,
			"id": "wtb09GSU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -843.3343071166743,
			"y": 5040.644374907983,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1087.5789794921875,
			"height": 50,
			"seed": 184344592,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "The plot of an odd function is antisymmetrical about the vertical axis. Exaples of odd functions are t, t^3,\nand sin t",
			"rawText": "The plot of an odd function is antisymmetrical about the vertical axis. Exaples of odd functions are t, t^3,\nand sin t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "The plot of an odd function is antisymmetrical about the vertical axis. Exaples of odd functions are t, t^3,\nand sin t",
			"lineHeight": 1.25,
			"baseline": 41
		},
		{
			"type": "text",
			"version": 83,
			"versionNonce": 504427536,
			"isDeleted": false,
			"id": "Ro58bEX2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -832.8159855315254,
			"y": 5154.024644709347,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 744.8391723632812,
			"height": 25,
			"seed": 1327876112,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Any signal x(t) can be represented as the sum of even and odd signals as:",
			"rawText": "Any signal x(t) can be represented as the sum of even and odd signals as:",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Any signal x(t) can be represented as the sum of even and odd signals as:",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 58,
			"versionNonce": 1051989232,
			"isDeleted": false,
			"id": "aXDwpugQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -491.7313388601489,
			"y": 5189.985325082518,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 277.2318115234375,
			"height": 33.39064577792441,
			"seed": 477994224,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 26.712516622339532,
			"fontFamily": 1,
			"text": "x(t) = x (t)  + x (t)",
			"rawText": "x(t) = x (t)  + x (t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t) = x (t)  + x (t)",
			"lineHeight": 1.25,
			"baseline": 24
		},
		{
			"type": "text",
			"version": 60,
			"versionNonce": 1173877264,
			"isDeleted": false,
			"id": "mJCvbNXo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -380.59514994725,
			"y": 5200.054048071215,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 10.939987182617188,
			"height": 25,
			"seed": 1002697232,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "e",
			"rawText": "e",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "e",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 57,
			"versionNonce": 725874416,
			"isDeleted": false,
			"id": "GWkCogvm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -258.48042463142554,
			"y": 5201.117942789466,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.079986572265625,
			"height": 25,
			"seed": 175270416,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "o",
			"rawText": "o",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "o",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 49,
			"versionNonce": 340733968,
			"isDeleted": false,
			"id": "g7weE1Om",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -794.4041535598042,
			"y": 5274.551322146651,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 155.2198028564453,
			"height": 100,
			"seed": 1519463952,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Where x (t)  = \n\n\nand  x (t) = ",
			"rawText": "Where x (t)  = \n\n\nand  x (t) = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Where x (t)  = \n\n\nand  x (t) = ",
			"lineHeight": 1.25,
			"baseline": 91
		},
		{
			"type": "text",
			"version": 68,
			"versionNonce": 2139592944,
			"isDeleted": false,
			"id": "WOxVQg8N",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -719.5395600539449,
			"y": 5283.970496340986,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 10.939987182617188,
			"height": 25,
			"seed": 1426182896,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097107,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "e",
			"rawText": "e",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "e",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 65,
			"versionNonce": 1359916560,
			"isDeleted": false,
			"id": "JJoKnIse",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -727.6377427321675,
			"y": 5357.720496340988,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.079986572265625,
			"height": 25,
			"seed": 305625616,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "o",
			"rawText": "o",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "o",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 78,
			"versionNonce": 252115696,
			"isDeleted": false,
			"id": "g1Jh6m50",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -634.9889502836695,
			"y": 5258.093039675948,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 135.73983764648438,
			"height": 25,
			"seed": 207555312,
			"groupIds": [
				"kNQu_YPq5-ILOUo9Prcf5",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "[x(t) + x(-t)]",
			"rawText": "[x(t) + x(-t)]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[x(t) + x(-t)]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 80,
			"versionNonce": 86928400,
			"isDeleted": false,
			"id": "eN0lV6fB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -572.065976650857,
			"y": 5292.177664920088,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 263212272,
			"groupIds": [
				"kNQu_YPq5-ILOUo9Prcf5",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 81,
			"versionNonce": 2085231856,
			"isDeleted": false,
			"id": "DmdZQlo7fRWjpymPSl6_d",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -637.9393515898219,
			"y": 5284.662863894698,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 152.5,
			"height": 0,
			"seed": 1596004592,
			"groupIds": [
				"kNQu_YPq5-ILOUo9Prcf5",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					152.5,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 82,
			"versionNonce": 1520855568,
			"isDeleted": false,
			"id": "Erni9UgD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -637.638108943105,
			"y": 5332.686850711104,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 131.4598388671875,
			"height": 25,
			"seed": 246218992,
			"groupIds": [
				"szKeV3zP11zAGDrphkQxE",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "[x(t) - x(-t)]",
			"rawText": "[x(t) - x(-t)]",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[x(t) - x(-t)]",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 86,
			"versionNonce": 1490616048,
			"isDeleted": false,
			"id": "pnfbXc5B",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -577.186952326894,
			"y": 5370.327841922041,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 1719235312,
			"groupIds": [
				"szKeV3zP11zAGDrphkQxE",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 94,
			"versionNonce": 2087626768,
			"isDeleted": false,
			"id": "OigPm-WDhqrgA65DwMUe5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -641.4601030749084,
			"y": 5362.102285566327,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 152.5,
			"height": 0,
			"seed": 786254064,
			"groupIds": [
				"szKeV3zP11zAGDrphkQxE",
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					152.5,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 84,
			"versionNonce": 1161535728,
			"isDeleted": false,
			"id": "wWtMHVcR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -841.2699779413153,
			"y": 5433.690654509236,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 685.8729248046875,
			"height": 36.83082580566431,
			"seed": 557666544,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"fontSize": 29.46466064453145,
			"fontFamily": 1,
			"text": "PROPERTIES OF EVEN AND ODD FUNCTIONS",
			"rawText": "PROPERTIES OF EVEN AND ODD FUNCTIONS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "PROPERTIES OF EVEN AND ODD FUNCTIONS",
			"lineHeight": 1.25,
			"baseline": 25
		},
		{
			"type": "text",
			"version": 550,
			"versionNonce": 1988044304,
			"isDeleted": false,
			"id": "f9o1s29V",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -850.780630801321,
			"y": 5479.074779900878,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1134.2249755859375,
			"height": 189.96183268229203,
			"seed": 1089008144,
			"groupIds": [
				"Vjz-x0_q82rEQvBO3VUUZ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"fontSize": 25.328244357638937,
			"fontFamily": 1,
			"text": "1. The product of two even functions is also an even function.\n2. The product of two odd functions is an even function.\n3. The product of an even function and an odd function is an odd function.\n4. The sum (or difference) of two even functions is also an even function.\n5. The sum (or difference) of two odd functions is an odd function.\n6. the sum (or difference) of an even function and an odd function is neither even or odd.",
			"rawText": "1. The product of two even functions is also an even function.\n2. The product of two odd functions is an even function.\n3. The product of an even function and an odd function is an odd function.\n4. The sum (or difference) of two even functions is also an even function.\n5. The sum (or difference) of two odd functions is an odd function.\n6. the sum (or difference) of an even function and an odd function is neither even or odd.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1. The product of two even functions is also an even function.\n2. The product of two odd functions is an even function.\n3. The product of an even function and an odd function is an odd function.\n4. The sum (or difference) of two even functions is also an even function.\n5. The sum (or difference) of two odd functions is an odd function.\n6. the sum (or difference) of an even function and an odd function is neither even or odd.",
			"lineHeight": 1.25,
			"baseline": 180
		},
		{
			"type": "arrow",
			"version": 91,
			"versionNonce": 284820208,
			"isDeleted": false,
			"id": "ULLmPUoIxmP0p7KOr_UXW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 80.2255227677565,
			"y": 2.3186645943694657,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 315.48828125,
			"height": 2247.853546142579,
			"seed": 351810800,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "M3e1lYQJ",
				"focus": -1.0035898880988523,
				"gap": 19.482416252489088
			},
			"endBinding": {
				"elementId": "GQJVhMYL6VZcBvbNP7Nh9",
				"focus": 0.07851219702261868,
				"gap": 16.889429891212785
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					315.48828125,
					859.7053527832036
				],
				[
					39.43603515625,
					2247.853546142579
				]
			]
		},
		{
			"type": "text",
			"version": 155,
			"versionNonce": 365945872,
			"isDeleted": false,
			"id": "avlbZdEg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4311.45097176136,
			"y": -4700.533947058977,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 603.5526123046875,
			"height": 61.75837703358496,
			"seed": 1112629264,
			"groupIds": [
				"JCHhx9XpPwGWZ6n6HRfau"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"fontSize": 49.406701626867964,
			"fontFamily": 1,
			"text": "SINUSOIDAL FUNCTION",
			"rawText": "SINUSOIDAL FUNCTION",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "SINUSOIDAL FUNCTION",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "text",
			"version": 163,
			"versionNonce": 1520182512,
			"isDeleted": false,
			"id": "MEIb6i7u",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4380.2690248752515,
			"y": -4610.239846869332,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 698.3593139648438,
			"height": 25,
			"seed": 554162192,
			"groupIds": [
				"JCHhx9XpPwGWZ6n6HRfau"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "A continuous-time sinusoidal signal in the most general form is given by",
			"rawText": "A continuous-time sinusoidal signal in the most general form is given by",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "A continuous-time sinusoidal signal in the most general form is given by",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 84,
			"versionNonce": 1213784592,
			"isDeleted": false,
			"id": "iPe6y59F",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4150.5710610845745,
			"y": -4558.503996592222,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 208.67974853515625,
			"height": 25,
			"seed": 1031430672,
			"groupIds": [
				"JCHhx9XpPwGWZ6n6HRfau"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(t) = A sin (wt +  )",
			"rawText": "x(t) = A sin (wt +  )",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t) = A sin (wt +  )",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 722,
			"versionNonce": 799672048,
			"isDeleted": false,
			"id": "S4xMf13TRlyNdDtxin83H",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.71238898038469,
			"x": -3967.3535733892363,
			"y": -4558.654955565155,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.262810922438458,
			"height": 17.58778214741325,
			"seed": 680241680,
			"groupIds": [
				"D3Q1DjB5dkJKJnqwGj7rI",
				"JCHhx9XpPwGWZ6n6HRfau"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					17.58778214741325
				],
				[
					17.262810922438458,
					9.079891706996523
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 176,
			"versionNonce": 2098339856,
			"isDeleted": false,
			"id": "fPFgAIT0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4383.154879503636,
			"y": -4537.6907510803085,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 361.75958251953125,
			"height": 100,
			"seed": 29519600,
			"groupIds": [
				"JCHhx9XpPwGWZ6n6HRfau"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Where\n    A = Amplitude\n    w = Angular frequency in radians\n      = Phase angle in radians",
			"rawText": "Where\n    A = Amplitude\n    w = Angular frequency in radians\n      = Phase angle in radians",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Where\n    A = Amplitude\n    w = Angular frequency in radians\n      = Phase angle in radians",
			"lineHeight": 1.25,
			"baseline": 91
		},
		{
			"type": "line",
			"version": 808,
			"versionNonce": 749447408,
			"isDeleted": false,
			"id": "q2OTtKaCfJNgp15tPsJXL",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 4.71238898038469,
			"x": -4347.483719001674,
			"y": -4460.533245622974,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.262810922438458,
			"height": 17.58778214741325,
			"seed": 209734160,
			"groupIds": [
				"GHl42hRCiSaSKcqwYJ6aJ",
				"JCHhx9XpPwGWZ6n6HRfau"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					17.58778214741325
				],
				[
					17.262810922438458,
					9.079891706996523
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 81,
			"versionNonce": 66297360,
			"isDeleted": false,
			"id": "GP1U_FWW1888-WlffY6NN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4370.494351391292,
			"y": -4638.571465779383,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 687.9395378960498,
			"height": 0,
			"seed": 272840720,
			"groupIds": [
				"JCHhx9XpPwGWZ6n6HRfau"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					687.9395378960498,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 102,
			"versionNonce": 489229040,
			"isDeleted": false,
			"id": "LXpB0Kf0-TtCxZSH_ogDF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4478.578267101741,
			"y": -4744.1238989345875,
			"strokeColor": "#6741d9",
			"backgroundColor": "transparent",
			"width": 893.8832106413656,
			"height": 318.4093757911969,
			"seed": 435232272,
			"groupIds": [
				"JCHhx9XpPwGWZ6n6HRfau"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "FQgCyMJAoHF76q2raEMVh",
					"type": "arrow"
				}
			],
			"updated": 1703931097108,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 368,
			"versionNonce": 1844796432,
			"isDeleted": false,
			"id": "FQgCyMJAoHF76q2raEMVh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2162.4873873082192,
			"y": -976.3410367689062,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1407.0773925781273,
			"height": 3357.697342381216,
			"seed": 102935568,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "LXpB0Kf0-TtCxZSH_ogDF",
				"focus": -0.5350152248885734,
				"gap": 15.130276574029267
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					-100.0532679703515
				],
				[
					-239.77099609375045,
					-326.7590306118637
				],
				[
					-498.4714355468759,
					-430.92129795808955
				],
				[
					-1142.0673828125014,
					-522.8293343128803
				],
				[
					-1231.9814249674491,
					-3272.403262554952
				],
				[
					-1407.0773925781273,
					-3457.7506103515675
				]
			]
		},
		{
			"type": "arrow",
			"version": 196,
			"versionNonce": 464137456,
			"isDeleted": false,
			"id": "B6nNheSaMhPzhQHMlz_3m",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1321.5527381586426,
			"y": 1630.2107298288458,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 728.5736083984398,
			"height": 1799.044910777699,
			"seed": 1413693168,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Nk9cQkG4lbeEz0woUdakw",
				"focus": -0.6265429596779885,
				"gap": 2.0866461029261245
			},
			"endBinding": {
				"elementId": "U0JdJMAM-3DqmTHmT2dq-",
				"focus": 0.7419487663470797,
				"gap": 15.794491199502886
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-209.36945134943176,
					-315.4881702769885
				],
				[
					-263.86285955255676,
					-760.0397283380684
				],
				[
					-728.5736083984398,
					-1173.8047096946025
				],
				[
					-539.2806729403433,
					-1799.044910777699
				]
			]
		},
		{
			"type": "text",
			"version": 56,
			"versionNonce": 1829722640,
			"isDeleted": false,
			"id": "0wtb5j5S",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2134.934973598985,
			"y": 3354.324721306122,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 301.60711669921875,
			"height": 48.51940274802071,
			"seed": 776751120,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"fontSize": 38.815522198416566,
			"fontFamily": 1,
			"text": "TIME SCALING",
			"rawText": "TIME SCALING",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "TIME SCALING",
			"lineHeight": 1.25,
			"baseline": 33
		},
		{
			"type": "line",
			"version": 66,
			"versionNonce": 834080496,
			"isDeleted": false,
			"id": "V87ffQFRTbZF31k_8cXtz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2194.5891262090704,
			"y": 3407.2110183586788,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 433.0792236328125,
			"height": 0,
			"seed": 1530806800,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					433.0792236328125,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 641,
			"versionNonce": 876189712,
			"isDeleted": false,
			"id": "D7TtYJdm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2564.3736425147044,
			"y": 3426.746034042864,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1216.0787353515625,
			"height": 150,
			"seed": 1842266128,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097108,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Time scaling involves the compression or expansion of a signal in time. Given a continuous-time signal x(t), the time-scalled\nform x(t) is x(at), where a is a constant. The scaled signal x(at) will be compressed is |a| > 1 or expanded if |a| < 1;\na negative value of a yields time reversal as well as compression or expansion.\n\nAgain, we can obtain x(at) from a signal by replacing every t with at and simplifying. Notice that the time reversal can be\nconsidered a special case of time scaling with the scaling factor a = -1",
			"rawText": "Time scaling involves the compression or expansion of a signal in time. Given a continuous-time signal x(t), the time-scalled\nform x(t) is x(at), where a is a constant. The scaled signal x(at) will be compressed is |a| > 1 or expanded if |a| < 1;\na negative value of a yields time reversal as well as compression or expansion.\n\nAgain, we can obtain x(at) from a signal by replacing every t with at and simplifying. Notice that the time reversal can be\nconsidered a special case of time scaling with the scaling factor a = -1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Time scaling involves the compression or expansion of a signal in time. Given a continuous-time signal x(t), the time-scalled\nform x(t) is x(at), where a is a constant. The scaled signal x(at) will be compressed is |a| > 1 or expanded if |a| < 1;\na negative value of a yields time reversal as well as compression or expansion.\n\nAgain, we can obtain x(at) from a signal by replacing every t with at and simplifying. Notice that the time reversal can be\nconsidered a special case of time scaling with the scaling factor a = -1",
			"lineHeight": 1.25,
			"baseline": 141
		},
		{
			"type": "text",
			"version": 68,
			"versionNonce": 2010624240,
			"isDeleted": false,
			"id": "PQgDxRDh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2096.708064673639,
			"y": 3603.3891106972233,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 318.40228271484375,
			"height": 30.915451049804688,
			"seed": 2094725648,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"fontSize": 24.73236083984375,
			"fontFamily": 1,
			"text": "y(t) = x(at)  Time Scaling",
			"rawText": "y(t) = x(at)  Time Scaling",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y(t) = x(at)  Time Scaling",
			"lineHeight": 1.25,
			"baseline": 21
		},
		{
			"type": "arrow",
			"version": 325,
			"versionNonce": 1466701328,
			"isDeleted": false,
			"id": "xrfRKnfLiur4owVSriADk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2550.429201353655,
			"y": 4023.790008970398,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 490.978479385376,
			"height": 0,
			"seed": 92404464,
			"groupIds": [
				"jNmXyQ_TMtw0NksO_msJ7"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "Ko38g0lS",
				"focus": 1.4570709228515626,
				"gap": 9.551849365234375
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					490.978479385376,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 338,
			"versionNonce": 898896624,
			"isDeleted": false,
			"id": "tRl26mtls4wRvLHEIZkei",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2319.728508223162,
			"y": 4053.3670353375855,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 349.00882720947266,
			"seed": 1867448560,
			"groupIds": [
				"cdvbap4K4j71Cy0KirD2x",
				"jNmXyQ_TMtw0NksO_msJ7"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "LxVv1e6V",
				"focus": 0.0450848994237772,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-349.00882720947266
				]
			]
		},
		{
			"type": "line",
			"version": 147,
			"versionNonce": 731829264,
			"isDeleted": false,
			"id": "iYgdMKcHqrHW4nTeUtPxR",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2493.246994246111,
			"y": 4022.6262974225465,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 171.5467071533203,
			"height": 171.5467071533203,
			"seed": 1213680880,
			"groupIds": [
				"cdvbap4K4j71Cy0KirD2x",
				"jNmXyQ_TMtw0NksO_msJ7"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					171.5467071533203,
					-171.5467071533203
				]
			]
		},
		{
			"type": "line",
			"version": 150,
			"versionNonce": 24392944,
			"isDeleted": false,
			"id": "4rw8FQIgVLZRIsTImnZJs",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2319.7284700761893,
			"y": 3851.0795521222535,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 171.54672622680664,
			"height": 171.54672622680664,
			"seed": 2100895984,
			"groupIds": [
				"cdvbap4K4j71Cy0KirD2x",
				"jNmXyQ_TMtw0NksO_msJ7"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					171.54672622680664,
					171.54672622680664
				]
			]
		},
		{
			"type": "text",
			"version": 123,
			"versionNonce": 650760720,
			"isDeleted": false,
			"id": "Ko38g0lS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2049.8988726030448,
			"y": 4029.5033955060426,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 818601712,
			"groupIds": [
				"cdvbap4K4j71Cy0KirD2x",
				"jNmXyQ_TMtw0NksO_msJ7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "xrfRKnfLiur4owVSriADk",
					"type": "arrow"
				}
			],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 119,
			"versionNonce": 1627395824,
			"isDeleted": false,
			"id": "LxVv1e6V",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2337.6808931718924,
			"y": 3678.358643003601,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.59996032714844,
			"height": 25,
			"seed": 226953968,
			"groupIds": [
				"cdvbap4K4j71Cy0KirD2x",
				"jNmXyQ_TMtw0NksO_msJ7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "tRl26mtls4wRvLHEIZkei",
					"type": "arrow"
				}
			],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "x(t)",
			"rawText": "x(t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x(t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 114,
			"versionNonce": 1071976464,
			"isDeleted": false,
			"id": "36SRqa2L",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2302.064285505877,
			"y": 3831.0522388898316,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 119615216,
			"groupIds": [
				"cdvbap4K4j71Cy0KirD2x",
				"jNmXyQ_TMtw0NksO_msJ7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 119,
			"versionNonce": 1757395184,
			"isDeleted": false,
			"id": "tS1Lys66",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2153.2617189775565,
			"y": 4032.2496723615113,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 1133845008,
			"groupIds": [
				"cdvbap4K4j71Cy0KirD2x",
				"jNmXyQ_TMtw0NksO_msJ7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 129,
			"versionNonce": 1323863568,
			"isDeleted": false,
			"id": "OEs8xQZS",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2298.350105513201,
			"y": 4033.588020750183,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 181587984,
			"groupIds": [
				"cdvbap4K4j71Cy0KirD2x",
				"jNmXyQ_TMtw0NksO_msJ7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 123,
			"versionNonce": 1547377392,
			"isDeleted": false,
			"id": "fJXcVHxk",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2493.9308931718924,
			"y": 4026.3342213117066,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.639984130859375,
			"height": 25,
			"seed": 1859705360,
			"groupIds": [
				"cdvbap4K4j71Cy0KirD2x",
				"jNmXyQ_TMtw0NksO_msJ7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-1",
			"rawText": "-1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "arrow",
			"version": 648,
			"versionNonce": 1825328144,
			"isDeleted": false,
			"id": "gi50HUIu09MUkLlertjDC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1842.3026830613264,
			"y": 4024.464114548987,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 492.8755890038624,
			"height": 0,
			"seed": 1027302640,
			"groupIds": [
				"iwweBeb5ahyXD9_GeXj0_"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "01bhP3pj",
				"focus": 1.4570709228515626,
				"gap": 7.654739746747964
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					492.8755890038624,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 802,
			"versionNonce": 1308245232,
			"isDeleted": false,
			"id": "8R-6cJZsqCiRwj3FlESeh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1611.6019899308333,
			"y": 4054.0411409161743,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.0427322140283195,
			"height": 347.3479148463198,
			"seed": 2086749936,
			"groupIds": [
				"dDJmRff9soW4v8rKueNes",
				"iwweBeb5ahyXD9_GeXj0_"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "dF0RJV9L",
				"focus": 0.04508489942377582,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					1.0427322140283195,
					-347.3479148463198
				]
			]
		},
		{
			"type": "line",
			"version": 350,
			"versionNonce": 1401440784,
			"isDeleted": false,
			"id": "h2UlnqZ6fLG9brX-WShr8",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1695.455398342763,
			"y": 4023.3004030011352,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 81.88162954230074,
			"height": 171.5467071533203,
			"seed": 1618667760,
			"groupIds": [
				"dDJmRff9soW4v8rKueNes",
				"iwweBeb5ahyXD9_GeXj0_"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					81.88162954230074,
					-171.5467071533203
				]
			]
		},
		{
			"type": "line",
			"version": 357,
			"versionNonce": 1065688816,
			"isDeleted": false,
			"id": "5yyDMFsZSPTICSQE2Xi9A",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1611.6019517838606,
			"y": 3851.7536577008423,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 96.82588175723436,
			"height": 169.88624873914205,
			"seed": 353389296,
			"groupIds": [
				"dDJmRff9soW4v8rKueNes",
				"iwweBeb5ahyXD9_GeXj0_"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					96.82588175723436,
					169.88624873914205
				]
			]
		},
		{
			"type": "text",
			"version": 286,
			"versionNonce": 1041532944,
			"isDeleted": false,
			"id": "01bhP3pj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1341.772354310716,
			"y": 4030.1775010846313,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 346647792,
			"groupIds": [
				"dDJmRff9soW4v8rKueNes",
				"iwweBeb5ahyXD9_GeXj0_"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "gi50HUIu09MUkLlertjDC",
					"type": "arrow"
				}
			],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 322,
			"versionNonce": 1097056496,
			"isDeleted": false,
			"id": "dF0RJV9L",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1667.7450358581823,
			"y": 3680.6932260698545,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 119.85986328125,
			"height": 25,
			"seed": 1221480176,
			"groupIds": [
				"dDJmRff9soW4v8rKueNes",
				"iwweBeb5ahyXD9_GeXj0_"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "8R-6cJZsqCiRwj3FlESeh",
					"type": "arrow"
				}
			],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "y(x) = x(2t)",
			"rawText": "y(x) = x(2t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y(x) = x(2t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 277,
			"versionNonce": 1214842384,
			"isDeleted": false,
			"id": "mkMeK9Vi",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1593.937767213548,
			"y": 3831.7263444684204,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 705097968,
			"groupIds": [
				"dDJmRff9soW4v8rKueNes",
				"iwweBeb5ahyXD9_GeXj0_"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 323,
			"versionNonce": 320742128,
			"isDeleted": false,
			"id": "Fv6L3DzZ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1526.497955105458,
			"y": 4027.9423454771063,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.65997314453125,
			"height": 25,
			"seed": 1608209136,
			"groupIds": [
				"dDJmRff9soW4v8rKueNes",
				"iwweBeb5ahyXD9_GeXj0_"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1/2",
			"rawText": "1/2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1/2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 292,
			"versionNonce": 1333642256,
			"isDeleted": false,
			"id": "Lo0VUx7h",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1590.2235872208723,
			"y": 4034.262126328772,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 1624470768,
			"groupIds": [
				"dDJmRff9soW4v8rKueNes",
				"iwweBeb5ahyXD9_GeXj0_"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 330,
			"versionNonce": 1128023280,
			"isDeleted": false,
			"id": "s6CDBvhj",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1711.083498286225,
			"y": 4030.329217618091,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.87995910644531,
			"height": 25,
			"seed": 309810928,
			"groupIds": [
				"dDJmRff9soW4v8rKueNes",
				"iwweBeb5ahyXD9_GeXj0_"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-1/2",
			"rawText": "-1/2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-1/2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "arrow",
			"version": 477,
			"versionNonce": 1363853840,
			"isDeleted": false,
			"id": "6cDCbj6mfjjwYgThqCHmO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2422.8244335500362,
			"y": 4484.790222716089,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 879.8630230506465,
			"height": 2.4268517127402447,
			"seed": 1776290032,
			"groupIds": [
				"GeERzRocWo14kCM9LrbrJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097109,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "1OaspUVV",
				"focus": 1.4570709228515628,
				"gap": 5.713386535644531
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					879.8630230506465,
					-2.4268517127402447
				]
			]
		},
		{
			"type": "arrow",
			"version": 571,
			"versionNonce": 1329997552,
			"isDeleted": false,
			"id": "TVZz0HX7wbk-zep5urn8C",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1944.7062467354313,
			"y": 4510.2799198828725,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.170558488257484,
			"height": 344.154688908503,
			"seed": 1959881456,
			"groupIds": [
				"GeERzRocWo14kCM9LrbrJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "H8HEUoFY",
				"focus": -0.09449061588457833,
				"gap": 13.639549956258634
			},
			"endBinding": {
				"elementId": "Jmd8DxtL",
				"focus": 0.04508489942377947,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					5.170558488257484,
					-344.154688908503
				]
			]
		},
		{
			"type": "line",
			"version": 267,
			"versionNonce": 1288175632,
			"isDeleted": false,
			"id": "UGTatD8PxQDTMf47czlga",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2269.6199643064883,
			"y": 4484.911315016158,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 324.797766481759,
			"height": 175.06301242131485,
			"seed": 524717296,
			"groupIds": [
				"GeERzRocWo14kCM9LrbrJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					324.797766481759,
					-175.06301242131485
				]
			]
		},
		{
			"type": "line",
			"version": 275,
			"versionNonce": 1136904432,
			"isDeleted": false,
			"id": "cIu0fy5PiMnIrY7c1xWSY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1944.7062085884586,
			"y": 4307.9924366675405,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 320.86072072326397,
			"height": 177.166709977123,
			"seed": 1120366320,
			"groupIds": [
				"GeERzRocWo14kCM9LrbrJ"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					320.86072072326397,
					177.166709977123
				]
			]
		},
		{
			"type": "text",
			"version": 255,
			"versionNonce": 569212432,
			"isDeleted": false,
			"id": "1OaspUVV",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1540.378962575018,
			"y": 4488.076757538994,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 1205604592,
			"groupIds": [
				"GeERzRocWo14kCM9LrbrJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "6cDCbj6mfjjwYgThqCHmO",
					"type": "arrow"
				}
			],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 223,
			"versionNonce": 1547512560,
			"isDeleted": false,
			"id": "Jmd8DxtL",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2003.9147821499068,
			"y": 4140.1252309743695,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 135.27984619140625,
			"height": 25,
			"seed": 1175220976,
			"groupIds": [
				"GeERzRocWo14kCM9LrbrJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "TVZz0HX7wbk-zep5urn8C",
					"type": "arrow"
				}
			],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "y(x) = x(1/2t)",
			"rawText": "y(x) = x(1/2t)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y(x) = x(1/2t)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 190,
			"versionNonce": 1907571728,
			"isDeleted": false,
			"id": "FdKBTS7M",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1927.042024018146,
			"y": 4287.965123435119,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 5.4199981689453125,
			"height": 25,
			"seed": 601920752,
			"groupIds": [
				"GeERzRocWo14kCM9LrbrJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 239,
			"versionNonce": 591023344,
			"isDeleted": false,
			"id": "WBej0l0M",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1625.476749327819,
			"y": 4489.162556906798,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 920680176,
			"groupIds": [
				"GeERzRocWo14kCM9LrbrJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 205,
			"versionNonce": 2115058192,
			"isDeleted": false,
			"id": "T5yBxp2E",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1923.3278440254703,
			"y": 4490.50090529547,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.759994506835938,
			"height": 25,
			"seed": 1670650096,
			"groupIds": [
				"GeERzRocWo14kCM9LrbrJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 247,
			"versionNonce": 306392816,
			"isDeleted": false,
			"id": "adW6fpGe",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2293.257370505091,
			"y": 4491.549429047783,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 22.459976196289062,
			"height": 25,
			"seed": 1032026864,
			"groupIds": [
				"GeERzRocWo14kCM9LrbrJ"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "-2",
			"rawText": "-2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "-2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 36,
			"versionNonce": 167737360,
			"isDeleted": false,
			"id": "H8HEUoFY",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2048.1009025796866,
			"y": 4523.919469839131,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 227.53973388671875,
			"height": 25,
			"seed": 596154384,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "TVZz0HX7wbk-zep5urn8C",
					"type": "arrow"
				}
			],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "a < 1 (signal expanded)",
			"rawText": "a < 1 (signal expanded)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "a < 1 (signal expanded)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 48,
			"versionNonce": 836751600,
			"isDeleted": false,
			"id": "fl2G5gyB",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1684.5790519937489,
			"y": 4086.8487911281936,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 237.17971801757812,
			"height": 25,
			"seed": 1635607792,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "a > 1 (signal compressed",
			"rawText": "a > 1 (signal compressed",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "a > 1 (signal compressed",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "rectangle",
			"version": 197,
			"versionNonce": 964032016,
			"isDeleted": false,
			"id": "SEGp2-vXyTOw7g4I3-EFH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2674.245723746679,
			"y": 3336.336889272725,
			"strokeColor": "#006eff",
			"backgroundColor": "transparent",
			"width": 1422.85173034668,
			"height": 1224.0941467285156,
			"seed": 1353755664,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "572tTRBJyvH3PkPsJKVCY",
					"type": "arrow"
				}
			],
			"updated": 1703931097110,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 196,
			"versionNonce": 966275824,
			"isDeleted": false,
			"id": "572tTRBJyvH3PkPsJKVCY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1329.756269452499,
			"y": 2068.8130691140004,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.75732421875,
			"height": 1264.8208895596595,
			"seed": 215524368,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Nk9cQkG4lbeEz0woUdakw",
				"focus": 0.9900818500580921,
				"gap": 1
			},
			"endBinding": {
				"elementId": "SEGp2-vXyTOw7g4I3-EFH",
				"focus": 0.7447388912327847,
				"gap": 2.7029305990649846
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					25.81265536221599,
					476.10029740767095
				],
				[
					20.076460404829504,
					691.205943714489
				],
				[
					-22.94466885653401,
					1264.8208895596595
				]
			]
		},
		{
			"type": "text",
			"version": 108,
			"versionNonce": 1902949392,
			"isDeleted": false,
			"id": "4U3xo1Wj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2091.8724980580087,
			"y": 4714.294780761732,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 334.8210754394531,
			"height": 37.44016737275953,
			"seed": 748221680,
			"groupIds": [
				"g9B0OGj1bNh6uKEQ8pQxG"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"fontSize": 29.952133898207627,
			"fontFamily": 1,
			"text": "AMPLITUDE SCALING",
			"rawText": "AMPLITUDE SCALING",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "AMPLITUDE SCALING",
			"lineHeight": 1.25,
			"baseline": 25
		},
		{
			"type": "line",
			"version": 153,
			"versionNonce": 804541680,
			"isDeleted": false,
			"id": "3pLB-taAb0_p5vkYOmqEt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2147.0735608803234,
			"y": 4771.677554331498,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 455.2962342227833,
			"height": 0,
			"seed": 656377872,
			"groupIds": [
				"g9B0OGj1bNh6uKEQ8pQxG"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					455.2962342227833,
					0
				]
			]
		},
		{
			"id": "h8iGeDiC",
			"type": "text",
			"x": -2539.534042883217,
			"y": 4811.660140647437,
			"width": 488.8394775390625,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1661649136,
			"version": 230,
			"versionNonce": 937144848,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"text": "Amplitude transformations take the general form:",
			"rawText": "Amplitude transformations take the general form:",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "Amplitude transformations take the general form:",
			"lineHeight": 1.25
		},
		{
			"id": "ZDFxISKV",
			"type": "text",
			"x": -2095.168982894377,
			"y": 4870.111329961053,
			"width": 285.29608154296875,
			"height": 43.02795410156284,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1314777840,
			"version": 69,
			"versionNonce": 175912688,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"text": "y(t) = Ax(t) + B",
			"rawText": "y(t) = Ax(t) + B",
			"fontSize": 34.42236328125027,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 30,
			"containerId": null,
			"originalText": "y(t) = Ax(t) + B",
			"lineHeight": 1.25
		},
		{
			"id": "aUbf9I0L",
			"type": "text",
			"x": -2526.676900026074,
			"y": 4971.660140647437,
			"width": 470.8594665527344,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1118628880,
			"version": 53,
			"versionNonce": 331018256,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"text": "Where A and B are constants. For example, let",
			"rawText": "Where A and B are constants. For example, let",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "Where A and B are constants. For example, let",
			"lineHeight": 1.25
		},
		{
			"id": "GP3GP2X3",
			"type": "text",
			"x": -2090.9626143117885,
			"y": 5017.374426361723,
			"width": 173.43978881835938,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 765854960,
			"version": 23,
			"versionNonce": 1303894256,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"text": "y(t) = -2x(t) + 4",
			"rawText": "y(t) = -2x(t) + 4",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "y(t) = -2x(t) + 4",
			"lineHeight": 1.25
		},
		{
			"id": "MT8NiQCx",
			"type": "text",
			"x": -2541.2632124563193,
			"y": 5088.581788945428,
			"width": 1206.778564453125,
			"height": 50,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 648156688,
			"version": 230,
			"versionNonce": 1828875792,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703931097110,
			"link": null,
			"locked": false,
			"text": "We notice that A = -2 means amplitude reversal (-x(t) implies reflection about the horizontal axis) and amplitude scaling\n(|A| = 2). Also B = 4 shifts vertically the amplitude of the signal.",
			"rawText": "We notice that A = -2 means amplitude reversal (-x(t) implies reflection about the horizontal axis) and amplitude scaling\n(|A| = 2). Also B = 4 shifts vertically the amplitude of the signal.",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 41,
			"containerId": null,
			"originalText": "We notice that A = -2 means amplitude reversal (-x(t) implies reflection about the horizontal axis) and amplitude scaling\n(|A| = 2). Also B = 4 shifts vertically the amplitude of the signal.",
			"lineHeight": 1.25
		},
		{
			"id": "c7ZXzLTlLKtgYMHwAkZ02",
			"type": "rectangle",
			"x": -2642.573920638518,
			"y": 4690.885691707705,
			"width": 1408.4293692452566,
			"height": 493.5136631556916,
			"angle": 0,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"seed": 551062032,
			"version": 102,
			"versionNonce": 758070000,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "aIwziKMFqGqJY-f4nfXnU",
					"type": "arrow"
				}
			],
			"updated": 1703931097110,
			"link": null,
			"locked": false
		},
		{
			"id": "aIwziKMFqGqJY-f4nfXnU",
			"type": "arrow",
			"x": -1282.1777476154766,
			"y": 2061.9056320385744,
			"width": 296.558837890625,
			"height": 2687.95947265625,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 2056276208,
			"version": 100,
			"versionNonce": 1823091728,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703931097111,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					94.646484375,
					1186.235595703125
				],
				[
					296.558837890625,
					2561.76416015625
				],
				[
					50.47802734375,
					2687.95947265625
				]
			],
			"lastCommittedPoint": [
				50.47802734375,
				2687.95947265625
			],
			"startBinding": null,
			"endBinding": {
				"elementId": "c7ZXzLTlLKtgYMHwAkZ02",
				"focus": 0.28724175517865386,
				"gap": 2.444831121534662
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "rvqrmFw6",
			"type": "text",
			"x": -3008.7342101234544,
			"y": -6014.569216847252,
			"width": 568.1546630859375,
			"height": 40.77440534319158,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 229246192,
			"version": 175,
			"versionNonce": 1421584912,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "THE UNIT PARABOLIC FUNCTION",
			"rawText": "THE UNIT PARABOLIC FUNCTION",
			"fontSize": 32.619524274553264,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 27,
			"containerId": null,
			"originalText": "THE UNIT PARABOLIC FUNCTION",
			"lineHeight": 1.25
		},
		{
			"id": "hhfNiy8GUmixDKhJ8Dy4f",
			"type": "line",
			"x": -2971.208168456788,
			"y": -5970.98337598625,
			"width": 486.37766520182277,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 359739120,
			"version": 128,
			"versionNonce": 31189008,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					486.37766520182277,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "cJchVIt7",
			"type": "text",
			"x": -3185.3109623319824,
			"y": -5936.401335562812,
			"width": 1057.3389892578125,
			"height": 75,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1737139440,
			"version": 293,
			"versionNonce": 1547986448,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "The continuous-time unit parabolic function p(t), also called unit acceleration signal starts at t = 0, and\nis defined as:\n",
			"rawText": "The continuous-time unit parabolic function p(t), also called unit acceleration signal starts at t = 0, and\nis defined as:\n",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 66,
			"containerId": null,
			"originalText": "The continuous-time unit parabolic function p(t), also called unit acceleration signal starts at t = 0, and\nis defined as:\n",
			"lineHeight": 1.25
		},
		{
			"id": "YYIGU6FW",
			"type": "text",
			"x": -2934.589221609326,
			"y": -5812.211500968086,
			"width": 68.55990600585938,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1276269072,
			"version": 128,
			"versionNonce": 283976720,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "vZYG5WRhuW4HKmkVSJ3Jw",
					"type": "arrow"
				}
			],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "p(t) = ",
			"rawText": "p(t) = ",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "p(t) = ",
			"lineHeight": 1.25
		},
		{
			"id": "SCSSanET",
			"type": "text",
			"x": -2750.29211772749,
			"y": -5829.482085074531,
			"width": 106.4998779296875,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"k286v5rEBGmXeQV-kucoF",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 422243856,
			"version": 184,
			"versionNonce": 1105158160,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "for t >= 0",
			"rawText": "for t >= 0",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "for t >= 0",
			"lineHeight": 1.25
		},
		{
			"id": "RBr8cAc2",
			"type": "text",
			"x": -2826.929309499951,
			"y": -5845.4858845130075,
			"width": 11.29998779296875,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"O5BjthEuaNfLov6THEGww",
				"k286v5rEBGmXeQV-kucoF",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1586888208,
			"version": 152,
			"versionNonce": 1025039888,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "t",
			"rawText": "t",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25
		},
		{
			"id": "eBAW4pxk",
			"type": "text",
			"x": -2822.263934744092,
			"y": -5812.3167103186715,
			"width": 14.239990234375,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"O5BjthEuaNfLov6THEGww",
				"k286v5rEBGmXeQV-kucoF",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 501118480,
			"version": 159,
			"versionNonce": 1349688336,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "2",
			"rawText": "2",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25
		},
		{
			"id": "xMBFe1tC",
			"type": "text",
			"x": -2812.3522831327637,
			"y": -5853.741347159492,
			"width": 8.324539184570225,
			"height": 14.614720669672554,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"O5BjthEuaNfLov6THEGww",
				"k286v5rEBGmXeQV-kucoF",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1740958448,
			"version": 187,
			"versionNonce": 233085456,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "2",
			"rawText": "2",
			"fontSize": 11.691776535738043,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 9,
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25
		},
		{
			"id": "2wWIxLmihcQJBJs-6xFRU",
			"type": "line",
			"x": -2835.830905569287,
			"y": -5821.0962360755075,
			"width": 39.43603515625,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"O5BjthEuaNfLov6THEGww",
				"k286v5rEBGmXeQV-kucoF",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 1966858480,
			"version": 165,
			"versionNonce": 140957712,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					39.43603515625,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "nAdhbswR",
			"type": "text",
			"x": -2820.679309499951,
			"y": -5770.256544913398,
			"width": 170.31979370117188,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"k286v5rEBGmXeQV-kucoF",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1868601072,
			"version": 201,
			"versionNonce": 871454224,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "vZYG5WRhuW4HKmkVSJ3Jw",
					"type": "arrow"
				}
			],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "0      for t < 0",
			"rawText": "0      for t < 0",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "0      for t < 0",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 134,
			"versionNonce": 318706192,
			"isDeleted": false,
			"id": "FV71CyYV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2769.90030034736,
			"y": -5683.3300083533395,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.29998779296875,
			"height": 25,
			"seed": 534116368,
			"groupIds": [
				"8jErV-tpF8Ns5jkR2T7_S",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "t",
			"rawText": "t",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 141,
			"versionNonce": 1936871440,
			"isDeleted": false,
			"id": "7wf9PFsV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2765.2349255915005,
			"y": -5650.160834159004,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 1350333968,
			"groupIds": [
				"8jErV-tpF8Ns5jkR2T7_S",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 169,
			"versionNonce": 516804112,
			"isDeleted": false,
			"id": "tzOTN5HT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2755.3232739801724,
			"y": -5691.585470999824,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.324539184570225,
			"height": 14.614720669672554,
			"seed": 1671640080,
			"groupIds": [
				"8jErV-tpF8Ns5jkR2T7_S",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 11.691776535738043,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "line",
			"version": 147,
			"versionNonce": 235506704,
			"isDeleted": false,
			"id": "AVkKIGeYrlGvHGfMPLdAb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2778.801896416696,
			"y": -5658.9403599158395,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 39.43603515625,
			"height": 0,
			"seed": 524431888,
			"groupIds": [
				"8jErV-tpF8Ns5jkR2T7_S",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					39.43603515625,
					0
				]
			]
		},
		{
			"id": "iq1trtgD",
			"type": "text",
			"x": -3064.589221609326,
			"y": -5693.461500968086,
			"width": 28.079971313476562,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1434922000,
			"version": 124,
			"versionNonce": 1528662544,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "OR",
			"rawText": "OR",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "OR",
			"lineHeight": 1.25
		},
		{
			"id": "d4krxJJ6ArSCO4_LMjj3b",
			"type": "arrow",
			"x": -2843.7180591947754,
			"y": -5821.0962360755075,
			"width": 27.605209350585938,
			"height": 19.718017578125,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 329539088,
			"version": 131,
			"versionNonce": 553764880,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-27.605209350585938,
					19.718017578125
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "vZYG5WRhuW4HKmkVSJ3Jw",
			"type": "arrow",
			"x": -2831.8872333891113,
			"y": -5761.9421833411325,
			"width": 27.605209350585938,
			"height": 27.605209350585938,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 631701744,
			"version": 459,
			"versionNonce": 1302020336,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049475,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-27.605209350585938,
					-27.605209350585938
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "nAdhbswR",
				"focus": -0.9439102977248194,
				"gap": 11.207923889160156
			},
			"endBinding": {
				"elementId": "YYIGU6FW",
				"focus": -0.6552532788652513,
				"gap": 6.536872863769531
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "QHUy5vCk",
			"type": "text",
			"x": -2852.388064993115,
			"y": -5670.010344351875,
			"width": 68.55990600585938,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 808290032,
			"version": 146,
			"versionNonce": 1209730064,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "p(t) = ",
			"rawText": "p(t) = ",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "p(t) = ",
			"lineHeight": 1.25
		},
		{
			"id": "57mVA6m5",
			"type": "text",
			"x": -2725.4162479765137,
			"y": -5669.482161368476,
			"width": 37.71995544433594,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 912169712,
			"version": 139,
			"versionNonce": 1145045520,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "u(t)",
			"rawText": "u(t)",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "u(t)",
			"lineHeight": 1.25
		},
		{
			"id": "ET7FP59O",
			"type": "text",
			"x": -3179.589221609326,
			"y": -5583.461500968086,
			"width": 699.4192504882812,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 2045247728,
			"version": 191,
			"versionNonce": 789921808,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "The shifted version of the unit parabolic sequence p(t - a) is given by",
			"rawText": "The shifted version of the unit parabolic sequence p(t - a) is given by",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "The shifted version of the unit parabolic sequence p(t - a) is given by",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 205,
			"versionNonce": 1217576464,
			"isDeleted": false,
			"id": "XPUDYBI6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2867.666642624285,
			"y": -5468.755189308706,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 110.11984252929688,
			"height": 25,
			"seed": 262648848,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "b2PShKTlypBriCo5tarqo",
					"type": "arrow"
				},
				{
					"id": "4JTmiAxmqOnTkiN3jxdpX",
					"type": "arrow"
				}
			],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "p(t - a) = ",
			"rawText": "p(t - a) = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "p(t - a) = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 244,
			"versionNonce": 1001175056,
			"isDeleted": false,
			"id": "KOAF4bgB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2628.876130539325,
			"y": -5486.0258289016565,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 106.07986450195312,
			"height": 25,
			"seed": 1454813712,
			"groupIds": [
				"AdQNtE-Ihgy2Wq1206R0x",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "for t >= a",
			"rawText": "for t >= a",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "for t >= a",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 251,
			"versionNonce": 1132148240,
			"isDeleted": false,
			"id": "NR9ndnOr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2727.0238869424675,
			"y": -5502.029628340133,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 67.91990661621094,
			"height": 25,
			"seed": 523628560,
			"groupIds": [
				"JNHzvIh2Wva2vBWZyf-Yp",
				"AdQNtE-Ihgy2Wq1206R0x",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "4JTmiAxmqOnTkiN3jxdpX",
					"type": "arrow"
				}
			],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t - a)",
			"rawText": "(t - a)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t - a)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 234,
			"versionNonce": 1905324560,
			"isDeleted": false,
			"id": "R0GfB58S",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2696.5458568243926,
			"y": -5468.860454145797,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 1360883216,
			"groupIds": [
				"JNHzvIh2Wva2vBWZyf-Yp",
				"AdQNtE-Ihgy2Wq1206R0x",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 285,
			"versionNonce": 1690841104,
			"isDeleted": false,
			"id": "lVu18gtY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2655.0853548934624,
			"y": -5510.285090986617,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.324539184570225,
			"height": 14.614720669672554,
			"seed": 358951952,
			"groupIds": [
				"JNHzvIh2Wva2vBWZyf-Yp",
				"AdQNtE-Ihgy2Wq1206R0x",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 11.691776535738043,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "line",
			"version": 254,
			"versionNonce": 711437840,
			"isDeleted": false,
			"id": "LkoflJZdpKZOxAF7E5-en",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2710.112827649588,
			"y": -5477.639979902633,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 39.43603515625,
			"height": 0,
			"seed": 906308112,
			"groupIds": [
				"JNHzvIh2Wva2vBWZyf-Yp",
				"AdQNtE-Ihgy2Wq1206R0x",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					39.43603515625,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 261,
			"versionNonce": 1265069072,
			"isDeleted": false,
			"id": "GBMG4EUQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2699.263322311786,
			"y": -5426.800288740524,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 169.8997802734375,
			"height": 25,
			"seed": 2113234960,
			"groupIds": [
				"AdQNtE-Ihgy2Wq1206R0x",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "b2PShKTlypBriCo5tarqo",
					"type": "arrow"
				}
			],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "0      for t < a",
			"rawText": "0      for t < a",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0      for t < a",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 203,
			"versionNonce": 1214752784,
			"isDeleted": false,
			"id": "LpMiOcfZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2680.033080249037,
			"y": -5348.477933643534,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 67.91990661621094,
			"height": 25,
			"seed": 422438416,
			"groupIds": [
				"Sd2CWVfL9jRrPJv1Jmjil",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "(t - a)",
			"rawText": "(t - a)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(t - a)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 172,
			"versionNonce": 1532503568,
			"isDeleted": false,
			"id": "NDGgzcbh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2652.4231476096556,
			"y": -5315.308759449198,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 14.239990234375,
			"height": 25,
			"seed": 1957078032,
			"groupIds": [
				"Sd2CWVfL9jRrPJv1Jmjil",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 215,
			"versionNonce": 2005459984,
			"isDeleted": false,
			"id": "ucOkFdZg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2612.396694418072,
			"y": -5359.601493768711,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.324539184570225,
			"height": 14.614720669672554,
			"seed": 509059600,
			"groupIds": [
				"Sd2CWVfL9jRrPJv1Jmjil",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 11.691776535738043,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"type": "line",
			"version": 180,
			"versionNonce": 183624208,
			"isDeleted": false,
			"id": "8lRt3q0Xx04hO2zzJf1HL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2665.990118434851,
			"y": -5324.088285206034,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 39.43603515625,
			"height": 0,
			"seed": 624484368,
			"groupIds": [
				"Sd2CWVfL9jRrPJv1Jmjil",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					39.43603515625,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 154,
			"versionNonce": 76226576,
			"isDeleted": false,
			"id": "yVd1ekta",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2950.3433948881348,
			"y": -5360.043474997627,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 28.079971313476562,
			"height": 25,
			"seed": 2034392592,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "OR",
			"rawText": "OR",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "OR",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "arrow",
			"version": 610,
			"versionNonce": 1200866544,
			"isDeleted": false,
			"id": "4JTmiAxmqOnTkiN3jxdpX",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2733.7045781353236,
			"y": -5485.701617792896,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 22.842221959664585,
			"height": 19.018565157205558,
			"seed": 1265376272,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703932049480,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "NR9ndnOr",
				"focus": 0.7359764037352207,
				"gap": 6.680691192856102
			},
			"endBinding": {
				"elementId": "XPUDYBI6",
				"focus": 0.6212882548089426,
				"gap": 1
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-22.842221959664585,
					19.018565157205558
				]
			]
		},
		{
			"type": "arrow",
			"version": 876,
			"versionNonce": 943409392,
			"isDeleted": false,
			"id": "b2PShKTlypBriCo5tarqo",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2710.471246200946,
			"y": -5414.543495069817,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 40.53868103027253,
			"height": 30.624570472301457,
			"seed": 1840126480,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703932049480,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "GBMG4EUQ",
				"focus": -0.9442281556275827,
				"gap": 11.207923889160156
			},
			"endBinding": {
				"elementId": "XPUDYBI6",
				"focus": -0.6552532788652428,
				"gap": 6.536872863769531
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-40.53868103027253,
					-30.624570472301457
				]
			]
		},
		{
			"type": "text",
			"version": 213,
			"versionNonce": 455629328,
			"isDeleted": false,
			"id": "sE4FxUEJ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2791.201625478955,
			"y": -5336.592318381416,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 110.11984252929688,
			"height": 25,
			"seed": 855660560,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "p(t - a) = ",
			"rawText": "p(t - a) = ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "p(t - a) = ",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 173,
			"versionNonce": 926062608,
			"isDeleted": false,
			"id": "olrpKV8a",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2611.1704212553223,
			"y": -5336.064135398017,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 79.27989196777344,
			"height": 25,
			"seed": 1331353104,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "u(t - a)",
			"rawText": "u(t - a)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "u(t - a)",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"id": "wTxyvsl6",
			"type": "text",
			"x": -3144.2789057556192,
			"y": -5244.439639965088,
			"width": 672.8392944335938,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 2119664656,
			"version": 133,
			"versionNonce": 323294736,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "The graphical representations of p(t) and p(t - a) are shown below:",
			"rawText": "The graphical representations of p(t) and p(t - a) are shown below:",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "The graphical representations of p(t) and p(t - a) are shown below:",
			"lineHeight": 1.25
		},
		{
			"id": "9SGIhgwR2MKoLt6I6ltfo",
			"type": "arrow",
			"x": -3171.6724532625126,
			"y": -4913.9346997077355,
			"width": 398.99977740119493,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 181596912,
			"version": 237,
			"versionNonce": 1438952176,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049482,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					398.99977740119493,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": {
				"elementId": "oDsoocav",
				"focus": 1.1481330343524314,
				"gap": 1.8516629294053928
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "upxNgd4aWOI-LkZ782iO1",
			"type": "arrow",
			"x": -3065.891131456446,
			"y": -4865.683536449463,
			"width": 0,
			"height": 302.49755859375,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 281550576,
			"version": 259,
			"versionNonce": 2144455920,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049483,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-302.49755859375
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": {
				"elementId": "ZbGINOX0",
				"focus": 1.2526199515923067,
				"gap": 4.574941695511825
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"type": "arrow",
			"version": 215,
			"versionNonce": 1877651184,
			"isDeleted": false,
			"id": "wSsdzDL4rGCBYvXGw8f4N",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2553.4531285085372,
			"y": -4906.179386164112,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 398.99977740119493,
			"height": 0,
			"seed": 1402784272,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703932049484,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "145U9vB2",
				"focus": 1.8234761800291743,
				"gap": 10.29345225036468
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					398.99977740119493,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 215,
			"versionNonce": 1855410416,
			"isDeleted": false,
			"id": "pt94Cx1xVJaac-FLDozzY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2447.67180670247,
			"y": -4857.928222905838,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 302.49755859375,
			"seed": 1201211408,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703932049485,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "bljhlHfo",
				"focus": -3.161124302853116,
				"gap": 14.86852926792426
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					-302.49755859375
				]
			]
		},
		{
			"id": "FRrq9nzKwYEmQJX3mWUcF",
			"type": "line",
			"x": -3064.4363069484307,
			"y": -4914.703750754025,
			"width": 147.22785101996533,
			"height": 236.61614312065922,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 2050644496,
			"version": 175,
			"versionNonce": 553995280,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					64.85036214192723,
					-26.29069010416697
				],
				[
					105.16272650824658,
					-63.09763590494822
				],
				[
					140.21697998046875,
					-133.20610894097172
				],
				[
					147.22785101996533,
					-236.61614312065922
				]
			],
			"lastCommittedPoint": [
				147.22785101996533,
				-236.61614312065922
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"type": "line",
			"version": 212,
			"versionNonce": 413223440,
			"isDeleted": false,
			"id": "6p4YeE384El_EuIhb2L35",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2331.175853609867,
			"y": -4907.655626988371,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 147.22785101996533,
			"height": 236.61614312065922,
			"seed": 548009712,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					64.85036214192723,
					-26.29069010416697
				],
				[
					105.16272650824658,
					-63.09763590494822
				],
				[
					140.21697998046875,
					-133.20610894097172
				],
				[
					147.22785101996533,
					-236.61614312065922
				]
			]
		},
		{
			"id": "bljhlHfo",
			"type": "text",
			"x": -2432.8032774345456,
			"y": -4889.000388395084,
			"width": 13.759994506835938,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 2075566608,
			"version": 66,
			"versionNonce": 2014152720,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "pt94Cx1xVJaac-FLDozzY",
					"type": "arrow"
				}
			],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "0",
			"rawText": "0",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25
		},
		{
			"id": "gn4z02NS",
			"type": "text",
			"x": -2334.9001741359343,
			"y": -4897.2944218694765,
			"width": 13.339981079101562,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1426020368,
			"version": 70,
			"versionNonce": 523682832,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "a",
			"rawText": "a",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "a",
			"lineHeight": 1.25
		},
		{
			"id": "145U9vB2",
			"type": "text",
			"x": -2144.258559010066,
			"y": -4895.885933913747,
			"width": 11.29998779296875,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1662384368,
			"version": 76,
			"versionNonce": 1105445392,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "wSsdzDL4rGCBYvXGw8f4N",
					"type": "arrow"
				}
			],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "t",
			"rawText": "t",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25
		},
		{
			"id": "oDsoocav",
			"type": "text",
			"x": -2771.3947216619763,
			"y": -4912.08303677833,
			"width": 11.29998779296875,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1859181072,
			"version": 75,
			"versionNonce": 4619792,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "9SGIhgwR2MKoLt6I6ltfo",
					"type": "arrow"
				}
			],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "t",
			"rawText": "t",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25
		},
		{
			"id": "1wWqXFif",
			"type": "text",
			"x": -3049.469944101212,
			"y": -4899.000388395084,
			"width": 13.759994506835938,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1150351376,
			"version": 65,
			"versionNonce": 1512716816,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "0",
			"rawText": "0",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "0",
			"lineHeight": 1.25
		},
		{
			"id": "ZbGINOX0",
			"type": "text",
			"x": -3061.3161897609343,
			"y": -5189.093924772037,
			"width": 36.21995544433594,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1203656944,
			"version": 87,
			"versionNonce": 2063104016,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "upxNgd4aWOI-LkZ782iO1",
					"type": "arrow"
				}
			],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "p(t)",
			"rawText": "p(t)",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "p(t)",
			"lineHeight": 1.25
		},
		{
			"id": "M1BCkwdc",
			"type": "text",
			"x": -2426.136610767879,
			"y": -5181.222610617307,
			"width": 77.77989196777344,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 391574256,
			"version": 74,
			"versionNonce": 941995024,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "p(t - a)",
			"rawText": "p(t - a)",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "p(t - a)",
			"lineHeight": 1.25
		},
		{
			"id": "ab4cVO59",
			"type": "text",
			"x": -3061.9766897575428,
			"y": -4775.333798870078,
			"width": 903.5191650390625,
			"height": 50,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 283255824,
			"version": 183,
			"versionNonce": 1064612368,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "The unit parabolic function can be obtained by integrating the unit ramp function or double\nintegrating the unit step function",
			"rawText": "The unit parabolic function can be obtained by integrating the unit ramp function or double\nintegrating the unit step function",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 41,
			"containerId": null,
			"originalText": "The unit parabolic function can be obtained by integrating the unit ramp function or double\nintegrating the unit step function",
			"lineHeight": 1.25
		},
		{
			"id": "Py0kh4Jh",
			"type": "text",
			"x": -2904.1015702303616,
			"y": -4682.853192790976,
			"width": 614.0994873046875,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1243018992,
			"version": 122,
			"versionNonce": 1077145616,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "p(t) =     u(t) dt =   r(t) dt =   tdt =          for t >= 0",
			"rawText": "p(t) =     u(t) dt =   r(t) dt =   tdt =          for t >= 0",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "p(t) =     u(t) dt =   r(t) dt =   tdt =          for t >= 0",
			"lineHeight": 1.25
		},
		{
			"id": "HYPzD8XW",
			"type": "text",
			"x": -2460.3120194491116,
			"y": -4700.302655681601,
			"width": 11.29998779296875,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"EEDaUZ2qfGf5fjQJD3mJi",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 851161840,
			"version": 88,
			"versionNonce": 576417296,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "t",
			"rawText": "t",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "t",
			"lineHeight": 1.25
		},
		{
			"id": "2lfW7OCe",
			"type": "text",
			"x": -2456.931526285049,
			"y": -4664.7673163261325,
			"width": 14.239990234375,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"EEDaUZ2qfGf5fjQJD3mJi",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1530833936,
			"version": 96,
			"versionNonce": 249768976,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "2",
			"rawText": "2",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25
		},
		{
			"id": "sNh8bB0p",
			"type": "text",
			"x": -2444.6066361483304,
			"y": -4704.93565128707,
			"width": 7.930236816406253,
			"height": 13.922475868808618,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"EEDaUZ2qfGf5fjQJD3mJi",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1103111184,
			"version": 137,
			"versionNonce": 1338190352,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "2",
			"rawText": "2",
			"fontSize": 11.137980695046894,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 9,
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25
		},
		{
			"id": "EpMSvWTbp18bFcUoMMgAV",
			"type": "line",
			"x": -2469.293525796768,
			"y": -4673.2858710136325,
			"width": 34.70367431640625,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"EEDaUZ2qfGf5fjQJD3mJi",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 509549072,
			"version": 108,
			"versionNonce": 804481040,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					34.70367431640625,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"type": "line",
			"version": 4632,
			"versionNonce": 1533797904,
			"isDeleted": false,
			"id": "M19GGfazmqlqDY5xI_P4n",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -2802.405312318269,
			"y": -4691.026152922544,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 1490396176,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 4647,
			"versionNonce": 1059365904,
			"isDeleted": false,
			"id": "pSNDpmYH_pouZXiy4OxM3",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -2816.185154694978,
			"y": -4692.801780058776,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 1155962608,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 4641,
			"versionNonce": 1763025424,
			"isDeleted": false,
			"id": "hO6TTUbbSw4LF_la3apwO",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -2682.1582076734935,
			"y": -4693.224326445495,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 506317840,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 4641,
			"versionNonce": 1748426768,
			"isDeleted": false,
			"id": "4O4yJlKf_6bEs_jjV5X4I",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -2559.1447189039623,
			"y": -4695.688987090026,
			"strokeColor": "#000000",
			"backgroundColor": "#000000",
			"width": 9.845901348774076,
			"height": 41.589456947420416,
			"seed": 1698316528,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.3004523516478184,
					1.209246316033144
				],
				[
					-4.647215587003986,
					7.474741786573146
				],
				[
					-2.7824431328169865,
					23.031382720284135
				],
				[
					-1.929247599468808,
					36.6778015252594
				],
				[
					-4.76203365582413,
					40.257893632991994
				],
				[
					-5.815664686982577,
					38.159200625341974
				],
				[
					-7.110728970427248,
					39.06231660896368
				],
				[
					-5.698924137345239,
					41.589456947420416
				],
				[
					-1.9112206088837684,
					40.06683409875895
				],
				[
					-0.3264495593557388,
					34.95376775974244
				],
				[
					-0.8542846482743336,
					22.90701973556727
				],
				[
					-3.097498378143099,
					6.542350217190476
				],
				[
					-0.3185877841610525,
					1.5678752667868323
				],
				[
					1.3234560187953854,
					3.660584469366615
				],
				[
					2.735172378346828,
					3.145557380114573
				],
				[
					1.9308144075824294,
					0.7935268837256421
				],
				[
					0,
					0
				]
			]
		},
		{
			"id": "fjlPvrf1",
			"type": "text",
			"x": -3073.5089798983304,
			"y": -4625.585492595664,
			"width": 992.1790161132812,
			"height": 50,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 817108496,
			"version": 231,
			"versionNonce": 746610192,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "The ramp function is the derivative of the parabolic function and step function is double derivative\nof the parabolic function",
			"rawText": "The ramp function is the derivative of the parabolic function and step function is double derivative\nof the parabolic function",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 41,
			"containerId": null,
			"originalText": "The ramp function is the derivative of the parabolic function and step function is double derivative\nof the parabolic function",
			"lineHeight": 1.25
		},
		{
			"id": "JuW0iiuc",
			"type": "text",
			"x": -2781.8473588045804,
			"y": -4564.782514080039,
			"width": 364.9595947265625,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 107068432,
			"version": 96,
			"versionNonce": 1726618640,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "r(t) =     p(t);      u(t) =      p(t)",
			"rawText": "r(t) =     p(t);      u(t) =      p(t)",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "r(t) =     p(t);      u(t) =      p(t)",
			"lineHeight": 1.25
		},
		{
			"id": "Ad0zILn3",
			"type": "text",
			"x": -2710.6166764315335,
			"y": -4575.162885173789,
			"width": 11.379989624023438,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"Bi6hwJsWzIsJOt9JZ96Zm",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1406745616,
			"version": 89,
			"versionNonce": 1768692240,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "d",
			"rawText": "d",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "d",
			"lineHeight": 1.25
		},
		{
			"id": "QuXxbG4b",
			"type": "text",
			"x": -2712.4601212557523,
			"y": -4545.2336249198825,
			"width": 22.679977416992188,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"Bi6hwJsWzIsJOt9JZ96Zm",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 278049808,
			"version": 105,
			"versionNonce": 117331984,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "dt",
			"rawText": "dt",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "dt",
			"lineHeight": 1.25
		},
		{
			"id": "9sdwPIpx5TVRSOrLYKC3o",
			"type": "line",
			"x": -2719.9382706698148,
			"y": -4549.7370428886325,
			"width": 37.85858154296875,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"Bi6hwJsWzIsJOt9JZ96Zm",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 265725168,
			"version": 91,
			"versionNonce": 1939396112,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					37.85858154296875,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "9jyl4b2x",
			"type": "text",
			"x": -2482.1386185702054,
			"y": -4584.824567302695,
			"width": 7.9210662841796875,
			"height": 13.922475868808615,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"ibQ2DX2Fn5ufBAz9xITLX",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1676361456,
			"version": 114,
			"versionNonce": 607360016,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "2",
			"rawText": "2",
			"fontSize": 11.137980695046892,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 8,
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 82,
			"versionNonce": 784765456,
			"isDeleted": false,
			"id": "K8wlFZmL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2497.5626239556937,
			"y": -4576.430615886679,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.379989624023438,
			"height": 25,
			"seed": 1694658800,
			"groupIds": [
				"JBccaUin5gKPVRhJSUkRW",
				"ibQ2DX2Fn5ufBAz9xITLX",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "d",
			"rawText": "d",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "d",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "text",
			"version": 98,
			"versionNonce": 709480464,
			"isDeleted": false,
			"id": "WYysiwdj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2499.4060687799124,
			"y": -4546.501355632773,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 22.679977416992188,
			"height": 25,
			"seed": 795267824,
			"groupIds": [
				"JBccaUin5gKPVRhJSUkRW",
				"ibQ2DX2Fn5ufBAz9xITLX",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dt",
			"rawText": "dt",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dt",
			"lineHeight": 1.25,
			"baseline": 16
		},
		{
			"type": "line",
			"version": 84,
			"versionNonce": 246763024,
			"isDeleted": false,
			"id": "WKs8Fx0-XZZGZlXcDZgde",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2506.884218193975,
			"y": -4551.004773601523,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.85858154296875,
			"height": 0,
			"seed": 854521072,
			"groupIds": [
				"JBccaUin5gKPVRhJSUkRW",
				"ibQ2DX2Fn5ufBAz9xITLX",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					37.85858154296875,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 107,
			"versionNonce": 352390160,
			"isDeleted": false,
			"id": "ZC938EFW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2473.4707413729398,
			"y": -4547.34977008085,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 7.930236816406251,
			"height": 13.922475868808615,
			"seed": 286820368,
			"groupIds": [
				"ibQ2DX2Fn5ufBAz9xITLX",
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"fontSize": 11.137980695046892,
			"fontFamily": 1,
			"text": "2",
			"rawText": "2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2",
			"lineHeight": 1.25,
			"baseline": 9
		},
		{
			"id": "FzDSaYBI",
			"type": "text",
			"x": -2925.38237136765,
			"y": -4490.73162856165,
			"width": 516.4393920898438,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1392514288,
			"version": 100,
			"versionNonce": 388303376,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1703932049154,
			"link": null,
			"locked": false,
			"text": "The same applies for discrete time parabolic signals",
			"rawText": "The same applies for discrete time parabolic signals",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "The same applies for discrete time parabolic signals",
			"lineHeight": 1.25
		},
		{
			"id": "aXY-O4G4IHm5NEvVO66Rp",
			"type": "rectangle",
			"x": -3256.0970320121824,
			"y": -6055.387688674499,
			"width": 1230.4039306640634,
			"height": 1640.5384521484386,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"7YqY8ICnsj5opCX1Y-KNS"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"seed": 969473552,
			"version": 208,
			"versionNonce": 1735164144,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "4lXWzC-yfpfZeQr_QwGYN",
					"type": "arrow"
				}
			],
			"updated": 1703932062023,
			"link": null,
			"locked": false
		},
		{
			"id": "4lXWzC-yfpfZeQr_QwGYN",
			"type": "arrow",
			"x": -1539.8881697074944,
			"y": -1374.19591621356,
			"width": 473.23242187500045,
			"height": 3400.962890625002,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"seed": 970798096,
			"version": 154,
			"versionNonce": 858296560,
			"isDeleted": false,
			"boundElements": [],
			"updated": 1703932066179,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-277.62963867187545,
					-612.0471191406255
				],
				[
					-347.03710937500045,
					-3066.545410156251
				],
				[
					-473.23242187500045,
					-3400.962890625002
				]
			],
			"lastCommittedPoint": [
				-473.23242187500045,
				-3400.962890625002
			],
			"startBinding": {
				"elementId": "DOfM1hI5A0MC6AWsUQ4Zb",
				"focus": 0.12094475853072544,
				"gap": 22.236058913559646
			},
			"endBinding": {
				"elementId": "aXY-O4G4IHm5NEvVO66Rp",
				"focus": -0.4911714812279569,
				"gap": 12.57250976562409
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "7bJETWEI",
			"type": "text",
			"x": -2441.0966228858997,
			"y": -4390.276135694284,
			"width": 9.999984741210938,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 770836720,
			"version": 2,
			"versionNonce": 1473313808,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1703931988598,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 16,
			"containerId": null,
			"originalText": "",
			"lineHeight": 1.25
		},
		{
			"id": "fwEQSv5o",
			"type": "text",
			"x": -1867.6378009020536,
			"y": -3262.0849737870494,
			"width": 9.999984741210938,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1298006544,
			"version": 2,
			"versionNonce": 1538460912,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1703932063861,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 16,
			"containerId": "4lXWzC-yfpfZeQr_QwGYN",
			"originalText": "",
			"lineHeight": 1.25
		}
	],
	"appState": {
		"theme": "dark",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "dashed",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 20,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 1698.5015141080444,
		"scrollY": 952.3548737141673,
		"zoom": {
			"value": 1.0800000000000003
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"gridColor": {
			"Bold": "#C9C9C9FF",
			"Regular": "#EDEDEDFF"
		},
		"currentStrokeOptions": null,
		"previousGridSize": null,
		"frameRendering": {
			"enabled": true,
			"clip": true,
			"name": true,
			"outline": true
		}
	},
	"files": {}
}
```
%%