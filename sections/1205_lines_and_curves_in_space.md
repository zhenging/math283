### Section 12.5 Lines and Curves in Space

#### Homework
p826: 1-3, 5-27odd, 31, 33, 35, 38, 41, 44, 45, 49, 51, 57, 61, 67, 75

1\. How many independent variables does the function $r(t) = \langle f(t), g(t), h(t) \rangle$ have?
>Solution
One. Just $t$.

3\. Why is $r(t) = \langle f(t), g(t), h(t) \rangle$ called a vector-valued function?
>Solution
For every input $t$, the output $r(t)$ is a vector.

5\. How do you find an equation for the line through the points $P_0(x_0, y_0, z_0)$ to  $P_1(x_1, y_1, z_1)$?
>Solution
$\vec{P_0P_1} = \langle x_1-x_0, y_1-y_0, z_1-z_0 \rangle$
$r(t) = \langle x_0 + (x_1-x_0)t, y_0 + (y_1-y_0)t, z_0 + (z_1-z_0)t \rangle$

7\. How do you evaluate $\dlim_{t\to a} r(t)$, where $r(t) = \langle f(t), g(t), h(t) \rangle$?
>Solution
$\dlim_{t \to a} f(t) = L_1, \dlim_{t \to a} g(t) = L_2, \dlim_{t \to a} h(t) = L_3$, then $\dlim_{t\to a} r(t) = \langle L_1, L_2, L_3 \rangle$.

9–24\. **Equations of lines** Find equations of the following lines.
9\. The line through $\langle 0, 0, 1 \rangle$ in the direction of the vector $v=\langle 4, 7, 0 \rangle$
>Solution
$r(t) = \langle 4t, 7t, 1 \rangle$

11\. The line through $\langle 0, 0, 1 \rangle$ parallel to the y-axis.
>Solution
Direction vector,  $v =\langle 0, 1, 0 \rangle$. Equation, $r(t) = \langle 0, t, 1 \rangle$

13\. The line through $\langle 0, 0, 0 \rangle$ and $\langle 1, 2, 3 \rangle$
>Solution
Direction vection, $v =\langle 1, 2, 3 \rangle$. Equation, $r(t) = \langle t, 2t, 3t \rangle$

15\. The line through $\langle -3, 4, 6 \rangle$ and $\langle 5, -1, 0 \rangle$
>Solution
Direction vection, $v =\langle 8, -5, -6 \rangle$. Euqation, $r(t) = \langle -3+8t, 4-5t, 6-6t \rangle$

17\. The line through $\langle 0, 0, 0 \rangle$ and is parallel to the line $r(t) = \langle 3-2t, 5+8t, 7-4t \rangle$.
>Solution
Direction vection, $v =\langle -2, 8, -4 \rangle$. Euqation, $r(t) = \langle -2t, 8t, -4t \rangle$

19\. The line through $\langle 0, 0, 0 \rangle$ and is perpendicular to both $u=\langle 1, 0, 2 \rangle$ and $v = \langle 0, 1, 1 \rangle$.
>Solution
Direction vector, $w = u \cdot v = \begin{vmatrix}
  i & j & k\\
  1 & 0 & 2\\
  0 & 1 & 1
 \end{vmatrix} = \langle -2, -1, 1 \rangle$
Equation, $r(t) = \langle -2t, -t, t \rangle$

21\. The line through $\langle -2, 5, 3 \rangle$ and is perpendicular to both $u=\langle 1, 1, 2 \rangle$ and the x-axis.
>Solution
Direction vector, $w = u \cdot v = \begin{vmatrix}
  i & j & k\\
  1 & 1 & 2\\
  1 & 0 & 0
 \end{vmatrix} = \langle 0, 2, -1 \rangle$
Equation, $r(t) = \langle -2, 5+2t, 3-t \rangle$.

23\. The line through $\langle 1, 2, 3 \rangle$ that is perpendicular to the lines $r_1(t) = \langle 3-2t, 5+8t, 7-4t \rangle$, and $r_2(t) = \langle -2t, 5+t, 7-t \rangle$.
>Solution
Direction vector, $w = u \cdot v = \begin{vmatrix}
  i & j & k\\
  -2 & 8 & -4\\
  -2 & 1 & -1
 \end{vmatrix} = \langle -12, -10, -14 \rangle$
Equation, $r(t) = \langle 1-12t, 2-10t, 3-14t \rangle$.

25–28\. **Line segments** Find an equation of the line segment joining the first point to the second point.
25\. $(0, 0, 0)$, and $(1, 2, 3)$.
>Solution
Direction vection, $v = \langle 1, 2, 3 \rangle$. Equation, $r(t) = \langle t, 2t, 3t \rangle$, for $0 \les t \les 1$.

27\. $(2, 4, 8)$, and $(7, 5, 3)$.
>Solution
Direction vection, $v = \langle 5, 1, -5 \rangle$. Equation, $r(t) = \langle 2 + 5t, 4 + t, 8-5t \rangle$, for $0 \les t \les 1$.

29–36\. **Curves in space** Graph the curves described by the following functions, indicating the direction of positive orientation. Try to antici pate the shape of the curve before using a graphing utility.
31\. $r(t) = \cos t \text{i} + \text{j} + \sin t \text{k}$, for $0 \les t \les 2\pi$.
>Solution
Graph (31).
<br>
<br>
<br>
<br>
<br>
<br>

33\. $r(t) = t\cos t \text{i} + \sin t \text{j} + tk$, for $0 \les t \les 6\pi$.
>Solution
Graph (33).

35\. $r(t) = e^{-t/20}\sin t \text{i} + e^{-t/20}\cos t \text{j} + tk$, for $0 \les t \lt \infty$.
>Solution
Graph (35).

37–40\. **Exotic curves** Graph the curves described by the following functions. Use analysis to anticipate the shape of the curve before using a graphing utility.
38\. $r(t) = 2\cos t \text{i} + 4\sin t \text{j} + \cos{10t} \text{k}$, for $0 \les t \les 2\pi$.

41–46\. **Limits** Evaluate the following limits.
41\. $\dlim_{t\to \pi/2}(\cos{2t}\text{i} - 4\sin t \text{j} + \frac{2t}{\pi} \text{k})$
>Solution
$\dlim_{t\to \pi/2}r(t) = -\text{i} - 4\text{j} + \text{k}$

44\. $\dlim_{t\to 2}(\frac{t}{t^2 + 1} \text{i} - 4e^{-t}\sin{\pi t} \text{j} + \frac{1}{\sqrt{4t + 1}}\text{k})$
>Solution
$\dlim_{t \to 2} r(t) = \frac{2}{5} \text{i} + \frac{1}{3}\text{k})$

45\. $\dlim_{t\to 0}(\frac{\sin t}{t} \text{i} - \frac{e^t - t- 1}{t}\text{j} + \frac{\cos t + t^2/2 -1}{t^2}\text{k})$
>Solution
$$
\begin{aligned}
\lim_{t \to 0} r(t) &= \lim_{t \to 0}(\frac{\cos t}{1} \text{i} - \frac{e^t - 1}{1}\text{j} + \frac{-\sin t + t}{2t}\text{k})\\
&= \lim_{t \to 0}(\frac{\cos t}{1} \text{i} - \frac{e^t - 1}{1}\text{j} + \frac{-\cos t + 1}{2}\text{k})\\
&= i
\end{aligned}
$$

49\. **Point of intersection** Determine the equation of the line that is perpendicular to the lines $r(t) = \langle 4t, 1 + 2t, 3t \rangle$ and $R(s) = \langle -1 + s, -7+2s, -12 + 3s \rangle$ and pass through the point of intersection of the line $r$ and $R$.
>Solution
Direction vector, $v = \begin{vmatrix}
 i & j & k\\
 4 & 2 & 3\\
 1 & 2 & 3
 \end{vmatrix} = \langle 0, -9, 6 \rangle$.
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
Equation of the line, $l(t) = \langle 4, 3-9t, 3 + 6t \rangle$

50–55\. **Skew lines** A pair of lines in $\mathbb{R}^3$ are said to be skew if they are neither parallel nor intersecting. Determine whether the following pairs of lines are parallel, intersecting, or skew. If the lines intersect, determine the point(s) of intersection.
51\. $r(t) = \langle 1 + 6t, 3-7t, 2 + t \rangle$
$R(s) = \langle 10 + 3s, 6+s, 14 + 4t \rangle$
>Solution
Direction vector of $r(t)$, $v_r = \langle 6, -7, 1 \rangle$
Direction vector of $R(t)$, $v_R = \langle 3, 1, 4 \rangle$
$v_r \cdot v_R = $
todo

56–59\. **Domains** Find the domains of the following vector-valued functions.
57\. $r(t) = \sqrt{t+2} \text{i} + \sqrt{2-t}\text{j}$
>Solution
$\begin{cases}
t + 2 \ges 0\\
2-t \ges 0
\end{cases} \To -2 \les t \les 2$

60–63\. **Line-plane intersections** Find the point (if it exists) at which
the following planes and lines intersect.
61\. $z=4; r(t) = \langle 2t+1, -t+4, t-6 \rangle$
>Solution
todo

67\. Matching functions with graphs Match functions a–f with the appropriate graphs A–F.
>Solution
todo

75\. Graph the curve $r(t) = \langle \frac{1}{2}\sin{2t}, \frac{1}{2}(1-\cos{2t}), \cos t \rangle$ and and prove that it lies on the surface of a sphere centered at the origin.
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
