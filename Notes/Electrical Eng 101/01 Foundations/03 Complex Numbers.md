24-12-2023 <=> 11:10
=> Type : Note
=> Tags : #complexnumbers 

---
### Imaginary Numbers
In the space of real numbers, the negative numbers do not have a defined square root, because any real number (positive or negative) multiplied by itself will have a positive product.

However, we can arbitrarily define a value called $j$ to represent the square root of $-1$. 

### Complex Numbers and 2D Vectors
By adding real any imaginary numbers we can have complex numbers. Instead of imagining the number line as a single line from $- \infty$ to $+ \infty$, we can imagine the space of complex numbers as being a two dimensional plane: on the x-axis are the real numbers, and on the y-axis are the imaginary. Any point on the 2D plane is now a complex number: $$z = a + bj$$
We can define basic operations on complex numbers $z = a + bj$ by thinking about them as two-dimensional vectors: $$Re(z) = \Re(z) = \Re(a + bj) = a$$
$$Im(z) = \Im(z) = \Im(a + bj) = b$$
##### Addition and Subtraction
$$z_1 + z_2 = (a + bj) + (c + dj) = (a + c) + (b + d)j$$
$$z_1 - z_2 = (a + bj) - (c + dj) = (a - c) + (b + d)j$$
##### Multiplication and Rotations
Multiplication is a more complicated case, but we can expand the product and work term by term to get the correct result: 
$$z_1z_2 = (a + bj)(c+ dj)$$
$$z_1z_2 = ac + adj + bcj + bdj^2$$
$$z_1z_2 = ac + adj + bcj + bd(-1)$$
$$z_1z_2 = (ac - bd) + (ad + bc)j$$
If we consider the special case of multiplying by $j$:
$$z_1j = (a + bj)j$$
$$z_1j = aj + bj^2$$
$$z_1j = aj + b(-1)$$
$$z_1j = (-b) + aj$$
Interestingly, we find when multiplying by $j$, the real and imaginary parts of $z_1$ have swapped, and the real part gets a negative sign too.

This maps geometrically by rotation by 90 degrees counterclockwise around the origin.

Multiplication by $j$ a second time (i.e multiplying $z_1$ by $j$ twice) maps geometrically to two 90 degree rotations, for a total of 180 degrees around the origin:
$$(z_1j)j = (-b + aj)j = -bj + aj^2 = -a -bj$$

Similarly, multiplication by $-j$ corresponds to 90 degree clockwise rotation. In either direction, the series of rotation is periodic, because $j^4 = (-1)^2 = 1$.

##### Complex Conjugate
The complex conjugate $\bar{z}$ of a complex number $z$ is defined as the value the negative imaginary part:
$$z = a + bj$$
$$\bar{z} = a - bj$$
$$\Im(\bar{z}) = -\Im(z)$$
The complex conjugate is important because it multiplies with the original complex number to a purely real number:
$$z\bar{z} = (a + bj)(a - bj)$$
$$=a^2 + abj - abj - b^2j^2$$
$$= a^2 + (abj - abj) - b^2(-1)$$
$$= a^2 + b^2$$
##### Division
Using the complex conjugate and multiplication definitions, we can define the division of complex numbers as well:
$$\frac{z_1}{z_2} = \frac{a + bj}{c + dj}$$
$$\frac{z_1}{z_2} = \frac{z_1}{z_2} \left( \frac{\bar{z_2}}{\bar{z_2}} \right)$$
$$\frac{z_1}{z_2} = \frac{(a+bj)(c-dj)}{(c+dj)(c-dj)}$$
$$\frac{z_1}{z_2} = \frac{(a+bj)(c-dj)}{c^2 + d^2}$$
$$\frac{z_1}{z_2} = \frac{(ac + bd)(bc -ad)j}{c^2 + d^2}$$
$$\frac{z_1}{z_2} = \left( \frac{ac + bd}{c^2 + d^2} \right) + \left(  \frac{bc - ad}{ c^2 + d^2} \right) $$
Notice that for two purely real numbers (i.e b = 0 and d = 0), this simplifies to ordinary division: $\frac{z_1}{z_2} = \frac{a}{c}$. The real numbers are a subset of the complex numbers.

##### Phase Angle and Magnitude
The complex numbers can be though of as part of a two-dimensional vector space, or imagined visually on the x-y (Re-Im) plane. These graphical interpretations give rise to two other geometric properties of a complex number: **magnitude** and **phase angle**.

The magnitude of a complex number is defined just like it is in three-dimensional vector spaces, as the overall length of the vector from the origin:
$$|z| = \sqrt{z\bar{z}} = \sqrt{a^2 + b^2}$$
The phase angle is defined graphically from the x-y plane interpretation: it is the counterclockwise angle from the positive x-axis to the vector represented by the complex number. The phase of a positive real number is 0 degrees and that of a negative number is 180 degrees or $\pi$ radians. In general, the phase is defined as:
$$\phi(z) = \tan^{-1}\frac{Im(z)}{Re(z)}$$
However, the naive $\tan^{-1}$ definition does obscure the fact that a complex number with negative real part and negative imaginary part lies in the 3rd quadrant: the range of $\tan^{-1}$ is $\left[ -\frac{\pi}{2}, +\frac{\pi}{2} \right]$ which is only $\pi$ radians or 180 degrees wide - it covers only half of the phase space. (In computer programming, the "atan2" function accounts for these multiple quadrant issues and gives a full $2\pi$ range of output by checking the sign of the numerator and denominator before proceeding. You should do the same when working by hand.)

Complex numbers also have an alternative representation is the polar interpretation. It is easy, useful, and suggested by the phase and magnitude. As long as we're careful to have specified the phase angle with full $2\pi$ range, we can directly map any complex number with cartesian representation $z = (a, b$) to a polar representation $(r,\theta)$, where $r = |z|$ and $\theta = \phi(z)$. To map back and forth between the two representations, note that:
$$z = a + bj = (r, \theta)$$
$$a = r \cos \theta$$
$$b = r \sin \theta$$
##### Operations on Polar Complex Numbers
While some operations like addition and subtraction are easiest in the cartesian representation $a + bj$, other operations are actually simpler in the polar representation $(r, \theta)$. In particular, multiplication and division become quite simple:
$$z_1z_2 = (r_1, \theta_1) \cdot (r_2, \theta_2)$$
$$z_1z_2 = (r_1r_2,\theta_1 + \theta_2)$$
In multiplication, the two radius (or magnitude) values multiply, and the two phase angles add.

This is useful because many electronic systems like amplifiers and filters can be thought of as working multiplicatively: a filter may reduce the input magnitude by a factor of $\frac{1}{10}$ and apply a phase delay of -90 degrees. By tracking both the magnitude and phase, we can consider this filter as effectively being like multiplying the input signal by a complex number $$z_{\text{filter}} = \left( r = \frac{1}{10}, \theta = -\frac{\pi}{2} \right) = -\frac{1}{10}j$$
In division, it's quite similar:
$$\frac{z_1}{z_2} = \frac{(r_1, \theta_1)}{(r_2, \theta_2)}$$
$$\frac{z_1}{z_2} = \left(\frac{r_1}{r_2}, \theta_1 - \theta_2 \right)$$
In division, the magnitude are divided, and the phase angles are subtracted.

##### Euler's Formula and Polar Complex Numbers
The polar representation of complex numbers is closely connected to one of the most beautiful expressions in mathematics. First, we start by observing that
$$z = a + bj$$
$$z = (r \cos \theta) + (r \sin \theta)j$$
$$z = r(\cos \theta + j \sin \theta)$$
The $r$ is just a scaling factor, but the other term is actually very interesting: the angle $\theta$ traces out a unit circle on the complex number plane.

It turns out there is a more compact representation of the complex plane unit circle, and it's and incredible piece of mathematics called Euler's Formula:
$$e^{j\theta} = \cos \theta + j \sin \theta$$
The Formula is incredibly powerful. The natural base constant $e$ raised to any imaginary number produces a complex number with unit magnitude and angle varying by the parameter.

Taking this as a given for the moment, this lets us write the complex number $z$ very simply:
$$z = re^{j\theta}$$
Any complex number can be written in this form, where $r$ and $\theta$ are real numbers specifying the magnitude and phase of the complex number.

Importantly, from this definition, the rules about multiplication and division of complex numbers are very easy to work with. Since for any exponents $e^Ae^B = e^{(A+B)}$ and $\frac{e^A}{e^B} = e^{(A-B)}$:
$$z_1z_2 = (r_1e^{j\theta_1})(r_2e^{j\theta_2})= (r_1r_2)e^{j(\theta_1 + \theta_2)}$$
$$\frac{z_1}{z_2} = \frac{r_1e^{j\theta_1}}{r_2e^{j\theta_2}} = \frac{r_1}{r_2}e^{j(\theta|1 - \theta_2)}$$

---
## Summary

---
### References
[Ultimate Electronics Book](https://ultimateelectronicsbook.com/complex-numbers/)

---
24-12-2023 <-> 11:10