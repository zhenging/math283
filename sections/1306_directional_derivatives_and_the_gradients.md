### Section 13.6 Directional Derivaties and the Gradients

#### Directional Derivatives

##### EXAMPLE 1 Computing directional derivatives
Consider the paraboloid $z=f(x, y) = \dfrac{1}{4}(x^2 + 2y^2) + 2$. Let $P_0$ be the point $(3, 2)$ and condier the unit vectors $\d u = \la \frac{1}{\sqrt 2}, \frac{1}{\sqrt 2} \ra$ and $\d v = \la \frac{1}{2}, -\frac{\sqrt 3}{2} \ra$
a. Find the directional derivatives of $f$ at $P_0$ in the directions of $u$ and $v$.
>Solution
$D_u f(3, 2) = \dfrac{7}{2\sqrt 2}$ , and $D_v f(3, 2) = \dfrac{3}{4} - \sqrt 3$

#### The Gradient Vector
Let $f$ be differentiable at the point $(x, y)$. The **gradient** of $f$ at $(x, y)$ is the vector-valued function
$$
\begin{aligned}
\nabla f(x, y) = \la f_x(x, y), f_y(x, y) \ra = f_x(x, y) \ihat + f_y(x, y) \jhat
\end{aligned}
$$

##### EXAMPLE 2 Computing gradients
Find $\nabla f$ and $\nabla f(3, 2)$ for $f(x, y) = x^2 + 2xy - y^3$
>Solution
$\nabla f(x, y) = \la 2x + 2y, 2x-3y^2 \ra$
$\nabla f(3, 2) = \la 10, -6 \ra$

#### Interpretations of the Gradient
Let $f$ be differentiable at $(a, b)$, with $\nabla f(a, b) \ne 0$.
1\. $f$ has its maximum rate of **increase** at $(a, b)$ in the direction of the gradient $\nabla f(a, b)$. The rate of increase in this direction is $|\nabla f(a, b)|$.
2\. $f$ has its minimum rate of **decrease** at $(a, b)$ in the direction of the gradient $-\nabla f(a, b)$. The rate of decrease in this direction is $-|\nabla f(a, b)|$.
3\. The directional derivative is **zero** in any direction _orthogonal_ to $\nabla f(a, b)$.

##### EXAMPLE 4 Steepest ascent and descent
Consider the bowl-shaped paraboloid $z=f(x, y) = 4 + x^2 + 3y^2$.
>Solution
Todo

#### The Gradient and Level Curves
Given a function $f$ differentiable at $(a, b)$, the line tangent to the level curve of $f$ at $(a, b)$ is orthogonal to the gradient $\nabla f(a, b)$, provided $\nabla f(a, b) \ne 0$.

#### The Gradient In Three Dimensions
$$
\begin{aligned}
\nabla f(x, y, z) &= \la f_x(x, y, z), f_y(x, y, z), f_z(x, y, z) \ra \\
&= f_x(x, y, z) \ihat + f_y(x, y) \jhat + f_z(x, y, z) \khat
\end{aligned}
$$
