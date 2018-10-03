### Section 12.3 Dot Products

#### Homework
p808: 5, 9, 13, 17, 21, 24, 25-28, 29-37odd, 40, **45**, 49, **55**, 59, 63, **69, 72**, 85

5\. Explain how to find the angle between two nonzero vectors.
>Solution
Given non-zero vectors u and v, the angle between them is $\cos^{-1} \frac{u \cdot v}{|u||v|}$.

9–12\. **Dot product from the definition** Consider the following vectors u and v. Sketch the vectors, find the angle between the vectors, and compute the dot product using the definition $u\cdot v = |u| |v| \cos \th$.
9\. $u=4i, v=6j$
>Solution
The vector u(x+) is perpendicular to the vector v (y+). Therefore $\th = \frac{\pi}{2}$, u and v are orthogonal, and $u\cdot v = 0$.

13\. **Dot product from the definition** Compute $u \cdot v$ if u and v are unit vectors and the angle between them is $\frac{\pi}{3}$.
>Solution
$$
\begin{aligned}
u \cdot v &= |u| |v| \cos \th \\
&= 1 \times 1 \times \cos \frac{\pi}{3} = \frac{1}{2}
\end{aligned}
$$

15–24\. **Dot products and angles** Compute the dot product of the vectors u and v, and find the angle between the vectors.
17\. $u = i, v= i + \sqrt 3 j$
>Solution
$$
\begin{aligned}
u \cdot v &= 1 \times 1 + 0 \times \sqrt 3 = 1\\
\cos \th &= \frac{u \cdot v}{|u| |v|} = \frac{1}{1 \times  2} = \frac{1}{2}\\
\To \th &= \frac{\pi}{3}
\end{aligned}
$$

21\. $u=\la -10, 0, 4 \ra, v = \la 1, 2, 3 \ra$
>Solution
$$
\begin{aligned}
u \cdot v &= -10 \times 1 + 0 \times 2 + 4 \times 3 = 2\\
\cos \th &= \frac{u \cdot v}{|u| |v|} = \frac{2}{\sqrt{116} \times  \sqrt{14}} = \frac{1}{\sqrt{406}}\\
\To \th &= \cos^{-1} \frac{1}{\sqrt{406}}
\end{aligned}
$$

24\. $u=i-4j-6k, v=2i-4j+2k$
>Solution
$$
\begin{aligned}
u \cdot v &= 1 \times 2 + (-4) \times (-4) + (-6) \times 2 = 6\\
\cos \th &= \frac{u \cdot v}{|u| |v|} = \frac{6}{\sqrt{53} \times  \sqrt{24}} = \frac{6}{\sqrt{1272}}\\
\To \th &= \cos^{-1} \frac{6}{\sqrt{1272}}
\end{aligned}
$$

25-28\. **Sketching orthogonal projections** Find $\text{proj}_v u$ and $\text{scal}_v u$ by inspection without using formulas.
>Solution
25\. $\text{proj}_v u = 3i, \text{scal}_v u = 3$
26\. $\text{proj}_v u = -3i, \text{scal}_v u = -3$
27\. $\text{proj}_v u = 3j, \text{scal}_v u = 3$
28\. Todo

29–36\. **Calculating orthogonal projections** For the given vectors u and v, calculate $\text{proj}_v u$ and $\text{scal}_v u$.
29\. $u= \la -1, 4 \ra, v=\la -4, 2 \ra$
>Solution
$$
\begin{aligned}
\text{scal}_v u &= \frac{u \cdot v}{|v|} = \frac{(-1) \times (-4) + 4 \times 2 }{\sqrt{(-4)^2 + 2^2}} = \frac{6}{\sqrt 5}\\
\text{proj}_v u &= \text{scal}_v u (\frac{v}{|v|} )= \frac{6}{\sqrt 5} \times \frac{\la -4, 2 \ra}{\sqrt{20}}\\
&=\la -\frac{12}{5}, \frac{6}{5} \ra
\end{aligned}
$$

31\. $u= \la 3, 3, -3 \ra, v=\la 1, -1, 2 \ra$
>Solution
$$
\begin{aligned}
\text{scal}_v u &= \frac{u \cdot v}{|v|} = \frac{3 \times 1 + 3 \times (-3) + (-3) \times 2}{\sqrt 6} = -\sqrt 6\\
\text{proj}_v u &= \text{scal}_v u (\frac{v}{|v|}) = -\sqrt 6 \times \frac{\la 1, -1, 2 \ra}{\sqrt 6}\\
&= \la -1, 1, -2 \ra
\end{aligned}
$$

33\. $u= \la -8, 0, 2 \ra, v=\la 1, 3, -3 \ra$
>Solution
$$
\begin{aligned}
\text{scal}_v u &= \frac{u \cdot v}{|v|} = \frac{-8 \times 1 + 0 + 2 \times (-3)}{\sqrt{19}} = -\frac{14}{\sqrt{19}}\\
\text{proj}_v u &= \text{scal}_v u (\frac{v}{|v|}) = -\frac{14}{\sqrt{19}} \times \frac{\la 1, 3, -3 \ra}{\sqrt{19}}\\
&= \la -\frac{14}{19}, -\frac{42}{19}, \frac{42}{19} \ra
\end{aligned}
$$

35\. $u=5 i + j - 5 k, v =-i + j - 2 k$
>Solution
$$
\begin{aligned}
\text{scal}_v u &= \frac{u \cdot v}{|v|} = \frac{5 \times (-1) + 1 \times 1 + (-5) \times (-2)}{\sqrt{6}} = \sqrt{6}\\
\text{proj}_v u &= \text{scal}_v u (\frac{v}{|v|}) = \sqrt 6 \times \frac{\la -1, 1, -2 \ra}{\sqrt 6}\\
&= \la -1, 1, -2 \ra
\end{aligned}
$$

37–42\. **Computing work** Calculate the work done in the following situations.
37\. A suitcase is pulled 50 ft along a flat sidewalk with a constant force of 30 lb at an angle of $30\degree$ above the horizontal.
>Solution
$$
\begin{aligned}
w &= F \cdot d = |F| |d| \cos(30\degree)\\
&= 30 \times 50 \times \frac{\sqrt 3}{2} = 750\sqrt 3 \text{ foot-pounds}
\end{aligned}
$$

40\. A constant force $F = \la 4, 3, 2 \ra$ (in newtons) moves an object from $\la 0, 0, 0 \ra$ to $\la 8, 6, 0 \ra$. (Distance is measured in meters.)
>Solution
$$
\begin{aligned}
w &= F\cdot d = \la 4, 3, 2 \ra \cdot \la 8, 6, 0 \ra\\
&= 4 \times 8 + 3 \times 6 + 0 = 50J
\end{aligned}
$$

43–46\. **Parallel and normal forces** Find the components of the vertical force $F = \la 0, -10 \ra$ in the directions parallel to and normal to the following planes. Show that the total force is the sum of the two component forces.
45\. A plane that makes an angle of $\pi/3$ with the positive x-axis.
>Solution
$v = \la \frac{1}{2}, -\frac{\sqrt 3}{2} \ra$. Let the component parallel to $F$ be $P$, and normal to $F$ be $N$.
$$
\begin{aligned}
P = \text{proj}_v F &= \frac{F\cdot v}{v\cdot v} v \\
&=5\sqrt 3\la \frac{1}{2}, -\frac{\sqrt 3}{2} \ra = \la \frac{5\sqrt 3}{2}, -\frac{15}{2} \ra\\
N = F - P &= \la -\frac{5\sqrt 3}{2}, -\frac{5}{2} \ra
\end{aligned}
$$

48–52\. **Orthogonal vectors** Let a and b be real numbers.
49\. Find all vectors $\la 1, a, b \ra$ orthogonal to $\la 4, -8, 2 \ra$.
>Solution
When two vectors are orthogonal, their dot product is 0.
$$
\begin{aligned}
&\la 1, a, b \ra \cdot \la 4, -8, 2 \ra = 0\\
\To &4-8a + 2b = 0\\
\To &b = 4a-2
\end{aligned}
$$
These vectors have the form of $\la 1, a, 4a-2 \ra$.

54–57\. **Vectors with equal projections** Given a fixed vector v, there is an infinite set of vectors u with the same value of $\text{proj}_v u$.
55\. Let $v = \la 1, 1 \ra$. Give a description of the position vectors u such that $\text{proj}_v u = \text{proj}_v \la 1, 2 \ra$.
>Solution
Todo
<br>
<br>

58–61\. **Decomposing vectors** For the following vectors $u$ and $v$, express $u$ as the sum $u = p + n$, where $p$ is parallel to $v$ and $n$ is orthogonal to $v$.
59\. $u = \la -2, 2 \ra, v= \la 2, 1 \ra$
>Solution
$$
\begin{aligned}
p = \text{proj}_v u &= \frac{u \cdot v}{v\cdot v} v\\
&=-\frac{2}{5}\la 2, 1 \ra = \la -\frac{4}{5}, -\frac{2}{5} \ra\\
n = u-p &= \la -\frac{6}{5}, \frac{12}{5} \ra
\end{aligned}
$$

62–65\. **Distance between a point and a line** Carry out the following steps to determine the (smallest) distance between the point $P$ and the line $\ell$ through the origin.
a. Find any vector v in the direction of $\ell$.
b. Find the position vecter u corresponding to P.
c. Find $\text{proj}_v u$.
d. Show that $w = u-\text{proj}_v u$ is a vector orthogonal to $v$ whose length is the distance betwee $P$ and the line $\ell$.
e. Find $w$ and $|w|$. Explain why $|w|$ is the distance between P and $\ell$.
63\. $P(-12, 4); \ell: y = 2x$
>Solution
a. $v = \la 1, 2 \ra$
b. $u = \la -12, 4 \ra$
c. $\text{proj}_v u = \frac{u \cdot v}{v \cdot v} v = \la -\frac{4}{5}, -\frac{8}{5} \ra$.
d. $w = u-\text{proj}_v u = \la -\frac{56}{5}, \frac{28}{5} \ra$ and $w \cdot v = 0$. Therefore, $w$ and $v$ are orthogonal.
e. $|w| = \frac{28\sqrt 5}{5}$. $|w|$ is the component of $u$ orthogonal to $v$, so it is the distance from $P$ to $\ell$.

69\. **Orthogonal unit vectors in $\R^3$** Consider the vectors $I = \la \frac{1}{2}, \frac{1}{2}, \frac{1}{\sqrt 2} \ra$, $J = \la -\frac{1}{\sqrt 2}, \frac{1}{\sqrt 2}, 0 \ra$, $K = \la \frac{1}{2}, \frac{1}{2}, -\frac{1}{\sqrt 2} \ra$
a. Sketch **I, J, and K** and show that they are unit vectors.
b. Show that **I, J, and K** are pairwise orthogonal.
c. Express the vector $\la 1, 0, 0 \ra$ in terms of **I, J, and K.**
>Solution
a. $|I| = \sqrt{(\frac{1}{2})^2 + (\frac{1}{2})^2 + (\frac{1}{\sqrt 2})^2} = 1$, $|J| = \sqrt{(-\frac{1}{\sqrt 2})^2 + (\frac{1}{\sqrt 2})^2 + 0^2} = 1$, and $|K| = \sqrt{(\frac{1}{2})^2 + (\frac{1}{2})^2 + (-\frac{1}{\sqrt 2})^2} = 1$
b. $I \cdot J = -\frac{1}{2\sqrt 2} + \frac{1}{2\sqrt 2} = 0$, $I \cdot K = \frac{1}{4} + \frac{1}{4} - \frac{1}{2} = 0$, and $J \cdot K = -\frac{1}{2\sqrt 2} + \frac{1}{2\sqrt 2} = 0$
c. Let $\la 1, 0, 0 \ra = aI + bJ + cK$,
$$
\begin{aligned}
\begin{gathered}
\frac{1}{2}a - \frac{1}{\sqrt 2}b + \frac{1}{2}c = 1\\
\frac{1}{2}a + \frac{1}{\sqrt 2}b + \frac{1}{2}c = 0\\
\frac{1}{\sqrt 2}a - \frac{1}{\sqrt 2}c = 0
\end{gathered} \To
a = \frac{1}{2}, b = -\frac{1}{\sqrt 2}, c = \frac{1}{2}
\end{aligned}
$$
Therefore, $\la 1, 0, 0 \ra = \frac{1}{2}I - \frac{1}{\sqrt 2}J + \frac{1}{2}K$

72\. **Flow through a circle** Suppose water flows in a thin sheet over the xy-plane with a uniform velocity given by the vector $v = \la 1, 2 \ra$; this means that at all points of the plane, the velocity of the water has components 1 m/s in the x-direction and 2 m/s in the y-direction (see figure). Let C be an imaginary unit circle (that does not interfere with the flow). Graph (72).
>Solution
Todo
<br>
<br>
<br>
<br>
<br>

84–88\. **Cauchy-Schwarz Inequality** The definition $u \cdot v = |u| |v| \cos \th$ implies that$|u \cdot v| \les |u| |v|$ because $|\cos \th| \les 1$. This inequality, known as the Cauchy–Schwarz Inequality, holds in any number of dimensions and has many consequence.
85\. Verify that the Cauchy–Schwarz Inequality holds for $u=\la 3, -5, 6 \ra$ and $v = \la -8, 3, 1 \ra$.
>Solution
$|u \cdot v| = |3\times (-8) + (-5)\times 3 + 6\times 1| = 33$
$|u| |v| = \sqrt{3^2 + (-5)^2 + 6^2} \cdot \sqrt{(-8)^2 + 3^2 + 1^2} = \sqrt{70 \times 74}$
$33 \le \sqrt{70 \times 74}$. Therefore $|u \cdot v| \les |u| |v|$.
