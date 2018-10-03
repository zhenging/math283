### Section 12.5 Lines and Curves in Space

#### Homework
p826: 1-3, 5-27odd, 31, 33, 35, 38, 41, 44, 45, 49, 51, 57, 61, 67, 75

1\. How many independent variables does the function $r(t) = \la f(t), g(t), h(t) \ra$ have?
>Solution
One. Just $t$.

3\. Why is $r(t) = \la f(t), g(t), h(t) \ra$ called a vector-valued function?
>Solution
For every input $t$, the output $r(t)$ is a vector.

5\. How do you find an equation for the line through the points $P_0(x_0, y_0, z_0)$ to  $P_1(x_1, y_1, z_1)$?
>Solution
$\vec{P_0P_1} = \la x_1-x_0, y_1-y_0, z_1-z_0 \ra$
$r(t) = \la x_0 + (x_1-x_0)t, y_0 + (y_1-y_0)t, z_0 + (z_1-z_0)t \ra$

7\. How do you evaluate $\dlim_{t\to a} r(t)$, where $r(t) = \la f(t), g(t), h(t) \ra$?
>Solution
$\dlim_{t \to a} f(t) = L_1, \dlim_{t \to a} g(t) = L_2, \dlim_{t \to a} h(t) = L_3$, then $\dlim_{t\to a} r(t) = \la L_1, L_2, L_3 \ra$.

9–24\. **Equations of lines** Find equations of the following lines.
9\. The line through $\la 0, 0, 1 \ra$ in the direction of the vector $v=\la 4, 7, 0 \ra$
>Solution
$r(t) = \la 4t, 7t, 1 \ra$

11\. The line through $\la 0, 0, 1 \ra$ parallel to the y-axis.
>Solution
Direction vector,  $v =\la 0, 1, 0 \ra$. Equation, $r(t) = \la 0, t, 1 \ra$

13\. The line through $\la 0, 0, 0 \ra$ and $\la 1, 2, 3 \ra$
>Solution
Direction vection, $v =\la 1, 2, 3 \ra$. Equation, $r(t) = \la t, 2t, 3t \ra$

15\. The line through $\la -3, 4, 6 \ra$ and $\la 5, -1, 0 \ra$
>Solution
Direction vection, $v =\la 8, -5, -6 \ra$. Euqation, $r(t) = \la -3+8t, 4-5t, 6-6t \ra$

17\. The line through $\la 0, 0, 0 \ra$ and is parallel to the line $r(t) = \la 3-2t, 5+8t, 7-4t \ra$.
>Solution
Direction vection, $v =\la -2, 8, -4 \ra$. Euqation, $r(t) = \la -2t, 8t, -4t \ra$

19\. The line through $\la 0, 0, 0 \ra$ and is perpendicular to both $u=\la 1, 0, 2 \ra$ and $v = \la 0, 1, 1 \ra$.
>Solution
Direction vector, $w = u \cdot v = \begin{vmatrix}
  i & j & k\\
  1 & 0 & 2\\
  0 & 1 & 1
 \end{vmatrix} = \la -2, -1, 1 \ra$
Equation, $r(t) = \la -2t, -t, t \ra$

21\. The line through $\la -2, 5, 3 \ra$ and is perpendicular to both $u=\la 1, 1, 2 \ra$ and the x-axis.
>Solution
Direction vector, $w = u \cdot v = \begin{vmatrix}
  i & j & k\\
  1 & 1 & 2\\
  1 & 0 & 0
 \end{vmatrix} = \la 0, 2, -1 \ra$
Equation, $r(t) = \la -2, 5+2t, 3-t \ra$.

23\. The line through $\la 1, 2, 3 \ra$ that is perpendicular to the lines $r_1(t) = \la 3-2t, 5+8t, 7-4t \ra$, and $r_2(t) = \la -2t, 5+t, 7-t \ra$.
>Solution
Direction vector, $w = u \cdot v = \begin{vmatrix}
  i & j & k\\
  -2 & 8 & -4\\
  -2 & 1 & -1
 \end{vmatrix} = \la -4, 6, 14 \ra$
Equation, $r(t) = \la 1-4t, 2+6t, 3+14t \ra$.

25–28\. **Line segments** Find an equation of the line segment joining the first point to the second point.
25\. $(0, 0, 0)$, and $(1, 2, 3)$.
>Solution
Direction vection, $v = \la 1, 2, 3 \ra$. Equation, $r(t) = \la t, 2t, 3t \ra$, for $0 \les t \les 1$.

27\. $(2, 4, 8)$, and $(7, 5, 3)$.
>Solution
Direction vection, $v = \la 5, 1, -5 \ra$. Equation, $r(t) = \la 2 + 5t, 4 + t, 8-5t \ra$, for $0 \les t \les 1$.

29–36\. **Curves in space** Graph the curves described by the following functions, indicating the direction of positive orientation. Try to antici pate the shape of the curve before using a graphing utility.
31\. $r(t) = \cos t \text{i} + \text{j} + \sin t \text{k}$, for $0 \les t \les 2\pi$.
>Solution
Graph 31.

33\. $r(t) = t\cos t \text{i} + \sin t \text{j} + tk$, for $0 \les t \les 6\pi$.
>Solution
Graph 33.

35\. $r(t) = e^{-t/20}\sin t \text{i} + e^{-t/20}\cos t \text{j} + tk$, for $0 \les t \lt \infty$.
>Solution
Graph 35.

37–40\. **Exotic curves** Graph the curves described by the following functions. Use analysis to anticipate the shape of the curve before using a graphing utility.
38\. $r(t) = 2\cos t \text{i} + 4\sin t \text{j} + \cos{10t} \text{k}$, for $0 \les t \les 2\pi$.
>Solution
Graph 38.

41–46\. **Limits** Evaluate the following limits.
41\. $\dlim_{t\to \pi/2}(\cos{2t}\text{i} - 4\sin t \text{j} + \frac{2t}{\pi} \text{k})$
>Solution
$\dlim_{t\to \pi/2}r(t) = -\text{i} - 4\text{j} + \text{k}$

44\. $\dlim_{t\to 2}(\frac{t}{t^2 + 1} \text{i} - 4e^{-t}\sin{\pi t} \text{j} + \frac{1}{\sqrt{4t + 1}}\text{k})$
>Solution
$\dlim_{t \to 2} r(t) = \frac{2}{5} \text{i} + \frac{1}{3}\text{k}$

45\. $\dlim_{t\to 0}(\frac{\sin t}{t} \text{i} - \frac{e^t - t- 1}{t}\text{j} + \frac{\cos t + t^2/2 -1}{t^2}\text{k})$
>Solution
$$
\begin{aligned}
\lim_{t \to 0} r(t) &= \lim_{t \to 0}(\frac{\cos t}{1} \text{i} - \frac{e^t - 1}{1}\text{j} + \frac{-\sin t + t}{2t}\text{k})\\
&= \lim_{t \to 0}(\frac{\cos t}{1} \text{i} - \frac{e^t - 1}{1}\text{j} + \frac{-\cos t + 1}{2}\text{k})\\
&= i
\end{aligned}
$$

49\. **Point of intersection** Determine the equation of the line that is perpendicular to the lines $r(t) = \la 4t, 1 + 2t, 3t \ra$ and $R(s) = \la -1 + s, -7+2s, -12 + 3s \ra$ and pass through the point of intersection of the line $r$ and $R$.
>Solution
Direction vector, $v = \begin{vmatrix}
 i & j & k\\
 4 & 2 & 3\\
 1 & 2 & 3
 \end{vmatrix} = \la 0, -9, 6 \ra$.
 Intersection
 $$
 \begin{aligned}
 \begin{cases}
4t = -1 + s\\
1 + 2t = -7 + 2s
 \end{cases} \To  \begin{cases}
t = 1\\
s = 5
\end{cases}
\end{aligned}
$$
The point of intersection is $(4, 3, 3)$.
Equation of the line, $l(t) = \la 4, 3-9t, 3 + 6t \ra$

50–55\. **Skew lines** A pair of lines in $\R^3$ are said to be skew if they are neither parallel nor intersecting. Determine whether the following pairs of lines are parallel, intersecting, or skew. If the lines intersect, determine the point(s) of intersection.
51\. $r(t) = \la 1 + 6t, 3-7t, 2 + t \ra$, $R(s) = \la 10 + 3s, 6+s, 14 + 4s \ra$
>Solution
$\begin{cases}
1 + 6t = 10 + 3s\\
3 - 7t = 6 + s\\
2 + t = 14 + 4s
\end{cases} \To \begin{cases}
t = 0\\
s = -3
\end{cases}
$
These two lines intersect at point $(1, 3, 2)$.

56–59\. **Domains** Find the domains of the following vector-valued functions.
57\. $r(t) = \sqrt{t+2} \text{i} + \sqrt{2-t}\text{j}$
>Solution
$\begin{cases}
t + 2 \ges 0\\
2-t \ges 0
\end{cases} \To -2 \les t \les 2$

60–63\. **Line-plane intersections** Find the point (if it exists) at which
the following planes and lines intersect.
61\. $z=4; r(t) = \la 2t+1, -t+4, t-6 \ra$
>Solution
$t-6 = 4 \To t = 10$. The intersection point is $(21, -6, 4)$.

67\. Matching functions with graphs Match functions a–f with the appropriate graphs A–F.
>Solution
a -> E. (A line)
b -> D. (Parabolic like)
c -> F. (A circle in xy-plane and z=2)
d -> C. (Circular helix, elongated along the x-axis)
e -> A. (Closed curve)
f -> B. (Circular helix, elongated along the y-axis)

75\. Graph the curve $r(t) = \la \frac{1}{2}\sin{2t}, \frac{1}{2}(1-\cos{2t}), \cos t \ra$ and and prove that it lies on the surface of a sphere centered at the origin.
>Solution
Graph 75. To prove the curve lies on the surface of a sphere centered at the origin, we need to show that the magnitude of every point on the curve should be constant.
$$
\begin{aligned}
|r(t)|^2 &= (\frac{1}{2}\sin{2t})^2 + (\frac{1}{2}(1-\cos{2t}))^2 + {\cos t}^2\\
&= \frac{1}{4}(\sin^2 {2t} + \cos^2 2t - 2\cos{2t} + 1) + \cos^2 t\\
&= \frac{1}{4}(2 - 2\cos{2t}) + \frac{1 + \cos{2t}}{2}\\
&= \frac{1-\cos{2t}}{2} + \frac{1 + \cos{2t}}{2}\\
&= 1\\
|r(t)| &= 1
\end{aligned}
$$
Therefore, every point has a distance of 1 to the origin. The curve lies on the curve of a sphere centered at the origin.
