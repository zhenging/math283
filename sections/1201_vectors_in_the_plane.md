### Section 12.1 Vectors in the Plane

#### Homework
p787: 1, 6, 11, 17, 21a-d, 23c, 25, 31, 32, 36, 39, 43, 45, **51**, **52**, 57, 58, 61, 71, 80, 87

1\. Interpret the following statement: Points have a location, but no size or direction; nonzero vectors have a size and direction, but no location.
>Solution
The coordinate of a point determines its location, but a given point has no width or breadth, so it has no size or direction. A nonzero vector has size (magnitude) and direction, but it has no location it the sense that it can be translated to a different initial point and be considered the same vector.

6\. Explain how to add two vectors geometrically.
>Solution
Place the tail of $v$ at the head of $u$. The sum of $u$ and $v$ is the vector that extends from the tail of $u$ to the head of $v$.

11\. How do you compute the magnitude of $v = \langle v_1, v_2 \rangle$?
>Solution
$|v| = \sqrt{v_1^2 + v_2^2}$

17–22\. **Vector operations** Refer to the figure and carry out the following vector operations
17\. **Scalar multiples** Which of the following vectors equals $\vec{CE}$? (There may be more than one correct answer.)
a. $v$ &emsp; b. $\frac{1}{2}\vec{HI}$ &emsp; c. $\frac{1}{3}\vec{OA}$ &emsp; d. $u$ &emsp; e. $\frac{1}{2}\vec{IH}$
>Solution
a, c, e

21\. **Vector addition** Write the following vectors as sums of scalar multiples of $u$ and $v$.
a\. $\vec{OE}$ &emsp; b\. $\vec{OB}$ &emsp; c\. $\vec{OF}$ &emsp; d\. $\vec{OG}$
>Solution
a. $\vec{OE} = 3u + 3v$
b. $\vec{OB} = u + 2v$
c. $\vec{OF} = 2u + 5v$
d. $\vec{OG} = -2u + 3v$

23\. **Components and magnitudes** Define the points $O(0, 0), P(2, 3), Q(4, 2)$, and $R(-6, -1)$. For each vector, do the following.
(i) Sketch the vector in an xy-coordinate system.
(ii) Compute the magnitude of the vector.
c. $\vec{RQ}$
>Solution
Graph 23.
$\vec{RQ} = \langle 4-(-6), 2-(-1) \rangle = \langle 10, 3 \rangle$
$|\vec{RQ}| = \sqrt{10^2 + 3^2} = \sqrt{109}$

24-27\. **Components and equality** Define the points $P(-3, -1), Q(-1, 2), R(1, 2), S(3, 5), T(4, 2)$ and $U(6, 4)$
25\. Sketch $\vec{QU}, \vec{PT}$ and $\vec{RS}$ and the corresponding position vectors.
>Solution
Graph 25.

28-33\. **Vector operations** Let $u = \langle 4, -2\rangle, v = \langle -4, 6\rangle$ and $w = \langle 0, 8\rangle$. Express the following vectors in the form $\langle a, b\rangle$.
31\. $w-3v$
>Solution
$w-3v = \langle 0-3\times(-4), 8-3\times 6)\rangle = \langle 12, -10 \rangle$

32\. $10u - 3v + w$
>Solution
$10u - 3v + w = \langle 10 \times 4 - 3\times(-4) + 0, 10 \times (-2) - 3\times 6 + 8\rangle = \langle 28, -30 \rangle$

34-41\. **Vector operations** Let $u = \langle 3, -4\rangle, v = \langle 1, 1\rangle$ and $w = \langle -1, 0\rangle$. Carry out the following computations.
36\. Find $|u+v+w|$.
>Solution
$u+v+w = \langle 3 + 1 -1, -4 + 1 + 0 \rangle = \langle 3, -3 \rangle$
$|u+v+w| = \sqrt{3^2 + (-3)^2} = 3\sqrt 2$

39\. Find two vectors parallel to $v$ with three times the magnitude of $v$.
>Solution
$3v = \langle 3, 3 \rangle$, $-3v = \langle -3, -3 \rangle$

42-47\. **Unit vectors** Define the points $P(-4, 1), Q(3, -4)$ and $R(2, 6)$. Carry out the following calculations.
43\. Express $\vec{QR}$ in the form of $ai + bj$,
>Solution
$\vec{QR} = (2-3)\text{i} + (6-(-4))\text{j} = -\text{i} + 10\text{j}$

45\. Find two unit vectors parallel to $\vec{PR}$.
>Solution
$v_1\frac{\vec{PR}}{|\vec{PR}|} = \frac{1}{\sqrt{61}}\langle 6, 5 \rangle$
$v_2 = -\frac{1}{\sqrt{61}}\langle 6, 5 \rangle$

51\. **Airplane in a wind** An airplane flies horizontally from east to west at 320 mi/hr relative to the air. If it flies in a steady 40 mi/hr wind that blows horizontally toward the southwest ($45\degree$ south of west), find the speed and direction of the airplane relative to the ground.
>Solution
Graph 51. Let the initial velocity of airplane be $v_i$, the velocity of the wind be $v_{w}$, and the final velocity of airplane be $v_f$.
$$
\begin{aligned}
v_i &= -320\text{i}\\
v_w &= -40 \cos{45\degree}\text{i} - 40\sin{45\degree}\text{j}\\
v_f &= v_i + v_w =  (-320-20\sqrt2)\text{i} - 20\sqrt 2\text{j}\\
|v_f|&= \sqrt{(-20\sqrt 2)^2 + (- 320-20\sqrt2))^2} \approx 349.43 mi/hr\\
\th &= \tan^{-1}(\frac{20\sqrt 2}{320 + 20\sqrt 2}) \approx 4.64 \degree
\end{aligned}
$$
The speed of the airplane to the ground is 349.43 mi/hr and the direction is 4.64 degree south of west.

52\. **Canoe in a current** A woman in a canoe paddles due west at 4 mi/hr relative to the water in a current that flows northwest at 2 mi/hr. Find the speed and direction of the canoe relative to the shore.
>Solution
Graph 52. Let the velocity of the canoe relative to water be $v_i$, the velocity of the current be $v_c$, and the velocity of the canoe relative to the shore be $v_f$.
$$
\begin{aligned}
v_i &= \langle  -4, 0\rangle\\
v_c &= 2\langle -\frac{\sqrt 2}{2}, \frac{\sqrt 2}{2}  \rangle\\
v_f &= v_i + v_c = \langle -4-\sqrt 2, \sqrt 2 \rangle\\
\th &= \tan^{-1}(\frac{\sqrt 2}{-4-\sqrt 2})
\end{aligned}
$$

57\. **Suspended load** If a 500-lb load is suspended by two chains (see figure), what is the magnitude of the force each chain must be able to withstand? Graph 57.
>Solution
Let the force vector on the two chains be $F_1$ and $F_2$, and the weight of the load be $W$
$$
\begin{aligned}
\begin{gathered}
W = \langle 0, -500 \rangle\\
F_1 + F_2 + W = \langle 0, 0 \rangle\\
F_1 = |F_1|\langle \frac{\sqrt 2}{2}, \frac{\sqrt 2}{2} \rangle\\
F_2 = |F_2|\langle -\frac{\sqrt 2}{2}, \frac{\sqrt 2}{2} \rangle
\end{gathered}
\To &\begin{cases}
\frac{\sqrt 2}{2}|F_1| - \frac{\sqrt 2}{2}|F_2| + 0 = 0\\
\frac{\sqrt 2}{2}|F_2| + \frac{\sqrt 2}{2}|F_2| -500 = 0
\end{cases}\\
\To &|F_1| = |F_2| = 250\sqrt 2 lb
\end{aligned}
$$

58\. **Net force** Three forces are applied to an object, as shown in the figure. Find the magnitude and direction of the sum of the forces. Graph 58.
>Solution
$$
\begin{aligned}
F_1 &= \langle -|F_1|\cos \frac{\pi}{4}, |F_1|\sin \frac{\pi}{4} \rangle = \langle -50\sqrt 2, 50\sqrt 2 \rangle\\
F_2 &= \langle |F_2|\cos \frac{\pi}{6}, |F_2|\sin \frac{\pi}{6} \rangle = \langle 30\sqrt 3, 30 \rangle\\
F_3 &= \langle -|F_3|\cos \frac{\pi}{3}, -|F_3|\sin \frac{\pi}{3} \rangle = \langle -75, -75\sqrt 3\rangle\\
F_{total} &= F_1 + F_2 + F_3 = \langle -50\sqrt 2 + 30\sqrt 3 -75, 50\sqrt 2 + 30 - 75\sqrt 3\rangle\\
|F_{total}| &= \sqrt{(-50\sqrt 2 + 30\sqrt 3 -75)^2 + (50\sqrt 2 + 30 - 75\sqrt 3)^2}\\
\th &= \tan^{-1}\frac{50\sqrt 2 + 30 - 75\sqrt 3}{-50\sqrt 2 + 30\sqrt 3 -75}
\end{aligned}
$$

61\. **Unit vectors**
a. Find two unit vectors parallel to $v=6i-8j$.
b. Find $b$ if $v=\langle \frac{1}{3}, b\rangle$ is a unit vector.
c. Find all values of a such that $w = ai - \frac{a}{3}\text{j} is a unit vector$
>Solution
a. $v_1 = \frac{v}{|v|} = \frac{1}{10}\langle 6, -8 \rangle$ and $v_2 = -v_1 = -\frac{1}{10}\langle 6, -8 \rangle$.
b. $|v| = \sqrt{(\frac{1}{3})^2 + b^2} = 1 \To b = \pm \frac{2}{3}\sqrt 2$
c. $|w| = \sqrt{a^2 + (-\frac{a}{3})^2} = 1 \To a = \pm \frac{3}{\sqrt{10}}$

70-71\. **Solving vector equations** Solve the following pairs of equations for the vectors $u$ and $v$. Assume $i=\langle 1, 0 \rangle$ and $j=\langle0, 1 \rangle$
71\. $2u+3v = i, u-v = j$
>Solution
$$
\begin{aligned}
\begin{gathered}
2u_1 + 3v_1 = 1\\
2u_2 + 3v_2 = 0\\
u_1 - v_1 = 0\\
u_2 - v_2 = 1
\end{gathered} \To \begin{cases}
u_1 = \frac{1}{5}\\
v_1 = \frac{1}{5}\\
u_2 = \frac{3}{5}\\
v_2 = -\frac{7}{10}
\end{cases}
\To\begin{cases}
u = \langle \frac{1}{5}, \frac{3}{5} \rangle\\
v = \langle \frac{1}{5}, -\frac{2}{5} \rangle\\
\end{cases}
\end{aligned}
$$

80\. **Mass on a plane** A 100-kg object rests on an inclined plane at an angle of $30\degree$ to the floor. Find the components of the force perpendicular to and parallel to the plane. (The vertical component of the force exerted by an object of mass m is its weight, which is mg, where $g = 9.8 m/s^2$ is the acceleration due to gravity.) Graph 80.
>Solution
Let the force vector parallel to the plane be $F_x$, and the force vector normal to the plane be $F_y$.
$F = 980 \langle \cos(\frac{\pi}{3}, -\sin \frac{\pi}{3}) \rangle = \langle 490, -490\sqrt 3 \rangle$.
$F_x = \langle 490, 0 \rangle$ and $F_y = \langle 0, -490\sqrt 3\rangle$

87\. **Magnitude of scalar multiple** Prove that $|cv| = |c| |v|$, where $c$ is a scalar and $v$ is a vector.
>Solution
$$
\begin{aligned}
|cv| &= |\langle cv_1, cv_2 \rangle|\\
&= \sqrt{(cv_1)^2 + (cv_2)^2}\\
&= \sqrt{c^2(v_1^2 + v_2^2)}\\
&= |c| \sqrt{v_1^2 + v_2^2}\\
&= |c| |v|
\end{aligned}
$$
