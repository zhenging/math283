### Section 12.2 Vectors in three Dimensions

#### Homework
p797: 3, 7, 8, 11, 13, 21-33odd, 41, 47, 48, 53, 56, 59, 63, 67, 75

3\. Describe the plane $x = 4$.
>Solution
The plane $x = 4$ is parallel to the yz-plane and contains all the points with x-coordinate 4.

7\. Which point is farther from the origin, $(3, -1, 2)$ or $(0, 0, - 4)$?
>Solution
Because $\sqrt{3^2 + (-1)^2 + 2^2} = \sqrt {14} < \sqrt{0^2 + 0^2 + (-4)^2} = \sqrt {16}$, the point $(0, 0, - 4)$ is further from the origin.

8\. Express the vector from $P(-1, -4, 6)$ to $Q(1, 3, -6)$ as a position vector in terms of i, j, and k.
>Solution
$$
\begin{aligned}
\vec{PQ} &= \langle 1 - (-1), 3-(-4), -6-6) \rangle\\
&= \langle 2, 7, -12 \rangle\\
&= 2i + 7j -12k
\end{aligned}
$$

11\. **Points in $\mathbb{R}^3$** Find the coordinates of the vertices A, B, C of the following rectangle. (Graph 11).
>Solution
$A(3, -4, 5), B(0, -4, 0), C(0, -4, 5)$

13\. **Plotting points in $\mathbb{R}^3$** For each points P(x, y, z) given below, let A(x, y, 0), B(x, 0, z) and C(0, y, z) be points in the xy-, xz-, and yz-planes, respectively. Plot and label the points A, B, C, and P in $\mathbb{R}^3$.
a. $P(2, 2, 4)$ &emsp; b. $P(1, 2, 5)$ &emsp; c. $P(-2, 0, 5)$\
>Solution
Graph (13).

21\. **Planes** Sketch the plane parallel to the xy-plane through (2, 4, 2) and find its equation.
>Solution
$z=2$. Graph (21).

23–26\. **Spheres and balls** Find an equation or inequality that describes the following objects.
23\. A sphere with center (1, 2, 3) and radius 4.
>Solution
$(x-1)^2 + (y-2)^2 + (z-3)^2 = 16$

25\. A ball with center (-2, 0, 4) and radius 1.
>Solution
$(x+2)^2 + y^2 + (z-4)^2 \les 1$

27\. **Midpoints and spheres** Find an equation of the sphere passing through $P(1, 0, 5)$ and $Q(2, 3, 9)$ with its center at the midpoint of PQ.
>Solution
1\. The midpoint of PQ is $O(\frac{1 + 2}{2}, \frac{0 + 3}{2}, \frac{5 + 9}{2})$, or $O(\frac{3}{2}, \frac{3}{2}, 7)$.
2\. The radius of the sphere is $R=|OP|$.
$$
\begin{aligned}
|OP| &= \sqrt{(1 - \frac{3}{2})^2 + (0 - \frac{3}{2})^2 + (5-7)^2}\\
&= \frac{\sqrt{27}}{2}
\end{aligned}
$$
3\. The equation for the sphere is $(x-\frac{3}{2})^2 + (y-\frac{3}{2})^2 + (z-7)^2 = \frac{26}{4}$.

29–38\. **Identifying sets** Give a geometric description of the following sets of points.
29\. $(x-1)^2 + y^2 + z^2 - 9 = 0$
>Solution
This is a sphere centered at $(1, 0, 0)$ with radius of 3.

31\. $x^2 + y^2 + z^2 -2y - 4z - 4 = 0$
>Solution
$$
\begin{aligned}
x^2 + y^2 + z^2 -2y - 4z - 4 &= 0\\
x^2 + (y-1)^2 + (z-2)^2 &= 9
\end{aligned}
$$
This is a sphere centered at $(0, 1, 2)$ with radius of 3.

33\. $x^2 + y^2 - 14y + z^2 \ges -13$
>Solution
$$
\begin{aligned}
x^2 + y^2 - 14y + z^2 &\ges -13\\
x^2 + (y-7)^2 + z^2 &\ges 36
\end{aligned}
$$
This is the outside of the ball centered at $(0, 7, 0)$ with radius of 6 (including the sphere).

39–44\. **Vector operations** For the given vectors u and v, evaluate the following expressions.
a. $3u + 2v$ &emsp; b. $4u-v$ &emsp; c. $|u + 3v|$
41\. $u = \langle -2, -1, -2 \rangle, v = \langle 1, 1, 1 \rangle$
>Solution
$$
\begin{aligned}
3u + 2v &= \langle -2 \times 3 + 1 \times 2, -1 \times 3 + 1 \times 2, -2 \times 3 + 1 \times 2 \rangle\\
&= \langle -4, -1, -4 \rangle\\
4u - v &= \langle -2 \times 4 - 1, -1 \times 4 - 1, -2 \times 4 - 1\rangle\\
&= \langle -9, -5, -9 \rangle\\
u + 3v &= \langle -2 + 1 \times 3, -1 + 1 \times 3, -2+ 1 \times 3\rangle\\
&= \langle 1, 2, 1 \rangle\\
|u + 3v| &= \sqrt{1^2 + 2^2 + 1^2} = \sqrt 6
\end{aligned}
$$

45–50\. **Unit vectors and magnitude** Consider the following points P and Q.
a. Find $\vec{PQ}$ and state your answer in two forms: $\langle a, b, c \rangle$ and $ai + bj + ck$.
b. Find the magnitude of $\vec{PQ}$.
c. Find two unit vectors parallel to $\vec{PQ}$.
47\. $P(-3, 1, 0), Q(-3, -4, 1)$
>Solution
a. $\vec{PQ} = \langle -3-(-3), -4-1, 1-0 \rangle = \langle 0, -5, 1 \rangle = -5j + k$
b. $|\vec{PQ}| = \sqrt{0^2 + (-5)^2 + 1^2} = \sqrt{26}$
c. two unit vector parallel to $\vec{PQ}$ are
$$
\begin{aligned}
\frac{\vec{PQ}}{|PQ|} &= \frac{\langle 0, -5, 1 \rangle}{\sqrt{26}}\\
-\frac{\vec{PQ}}{|PQ|} &= \frac{\langle 0, 5, -1 \rangle}{\sqrt{26}}
\end{aligned}
$$

48\. $P(3, 8, 12), Q(3, 9, 11)$
>Solution
a. $\vec{PQ} = \langle 3-3, 9-8, 11-12 \rangle = \langle 0, 1, -1 \rangle = j - k$
b. $|\vec{PQ}| = \sqrt{0^2 + 1^2 + (-1)^2} = \sqrt{2}$
c. two unit vector parallel to $\vec{PQ}$ are
$$
\begin{aligned}
\frac{\vec{PQ}}{|PQ|} &= \frac{\langle 0, 1, -1 \rangle}{\sqrt{2}}\\
-\frac{\vec{PQ}}{|PQ|} &= \frac{\langle 0, -1, 1 \rangle}{\sqrt{2}}
\end{aligned}
$$

53\. **Crosswinds** A small plane is flying horizontally due east in calm air at 250 mi/hr when it is hit by a horizontal crosswind blowing southwest at 50 mi/hr and a 30 mi/hr updraft. Find the resulting speed of the plane and describe with a sketch the approximate direction of the velocity relative to the ground.
>Solution
Graph (53). Let the initial velocity of the plane be $v_i$, the velocity of the crosswind be $v_{wind}$, the velocity of the updraft be $v_{up}$, and the final velocity of the plane be $v_f$.
$$
\begin{aligned}
v_i &= \langle 250, 0, 0 \rangle\\
v_{wind} &= \langle -50\sin\frac{\pi}{4}, -50\sin\frac{\pi}{4}, 0 \rangle\\
v_{up} &= \langle 0, 0, 30 \rangle\\
v_f &= v_i + v_{wind} + v_{up} \\
&= \langle 250-25\sqrt 2, -25 \sqrt 2, 30 \rangle
\end{aligned}
$$
The final speed of the plane is $|v_f| \approx 219.6$ mi/hr.

56\. **Maintaining equilibrium** An object is acted upon by the forces $F_1 = \langle 10, 6, 3 \rangle$ and $F_2 = \langle 0, 4, 9\rangle$. Find the force $F_3$ that must act on the object so that the sum of the forces is zero.
>Solution
$$
\begin{aligned}
F_1 + F_2 + F_3 &= 0\\
F_3 &= -F_1 - F_2 = \langle -10-0, -6-4, -3-9 \rangle\\
&= \langle -10, -10, -12 \rangle
\end{aligned}
$$

58–60\. **Sets of points** Describe with a sketch the sets of points (x, y, z) satisfying the following equations.
59\. $x^2y^2z^2 > 0$
>Solution
This represents all the points that are not on the three axes.

63\. **Sets of points** Give a geometric description of the set of points (x, y, z) that lie on the intersection of the sphere $x^2 + y^2 + z^2 = 5$ and the plane $z = 1$.
>Solution
$z = 1 \To x^2 + y^2  = 4$. This represents a circle centered at $(0, 0, 1)$ with radius of 2 in the $z=1$ plane.

67–70\. **Parallel vectors of varying lengths** Find vectors parallel to v of the given length.
67\. $v = \langle 6, -8, 0 \rangle$; length = 20
>Solution
$$
\begin{aligned}
20 \times \frac{v}{|v|} &= \frac{\langle 6 \times 20, -8 \times 20, 0 \times 20\rangle}{\sqrt{6^2 + (-8)^2 + 0^2}}\\
& = \langle 12, -16, 0 \rangle
\end{aligned}
$$

75\. **Three-cable load** A 500-kg load hangs from three cables of equal length that are anchored at the points $(-2, 0, 0), (1, \sqrt 3, 0)$, and $(1, -\sqrt 3, 0)$. The load is located at $(0, 0, -2\sqrt 3)$. Find the vectors describing the forces on the cables due to the load. Graph 75.
>Solution
Let the force vector on the three cable be $F_1, F_2, F_3$, and the weight of the load be $W = \langle 0, 0, -500 \times 9.8 \rangle$. The direction vector of $F_1, F_2, F_3$ are $\langle 1, \sqrt 3, 2\sqrt 3 \rangle, \langle -2, 0, 2\sqrt 3 \rangle$ and $\langle 1, -\sqrt 3, 2\sqrt 3 \rangle$.
$$
\begin{aligned}
&\begin{gathered}
F_1 + F_2 + F_3 + W = \langle 0, 0, 0 \rangle\\
F_1 = f_1\langle 1, \sqrt 3, 2\sqrt 3 \rangle\\
F_2 = f_2\langle -2, 0, 2\sqrt 3 \rangle\\
F_3 = f_3\langle 1, -\sqrt 3, 2\sqrt 3 \rangle\\
\end{gathered} \To \begin{cases}
f_1-2f_2 + f_3 + 0 = 0\\
\sqrt 3 f_1 +0 -\sqrt 3 f_3 + 0 = 0\\
2\sqrt 3(f_1+f_2 + f_3) - 500 \times 9.8 = 0\\
\end{cases}\\
\To & f_1 = f_2 = f_3 = \frac{2450}{3\sqrt 3}\\
F_1 &= \frac{2450}{3\sqrt 3}\langle 1, \sqrt 3, 2\sqrt 3 \rangle\\
F_2 &= \frac{2450}{3\sqrt 3}\langle -2, 0, 2\sqrt 3 \rangle\\
F_3 &= \frac{2450}{3\sqrt 3}\langle 1, -\sqrt 3, 2\sqrt 3 \rangle
\end{aligned}
$$
