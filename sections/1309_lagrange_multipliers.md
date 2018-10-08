### Section 13.9 Lagrange Multipliers

#### Lagrange Multipliers with Two Independent Variables

##### Parallel Gradients (Ball Park Theorem)
Let $f$ be a differentiable function in a region of $\R^2$ that contains the smooth curve $C$ given by $g(x, y) = 0$. Assume that $f$ that a local extreme value (relative to values of $f$ on $C$) at a point $P(a, b)$ on $C$. Then $\nabla f(a, b)$ is orthogonal to the line tangent to $C$ at $P$. Assuming $\nabla g(a, b) \ne 0$, it follows that there is a real number $\lm$ (called a **Lagrange Multiplier**) such that $\nabla f(a, b) = \lm \nabla g(a, b)$.

**Proof**: Because $C$ is smooth it can be expressed parametrically in the form $C:r(t) = \la x(t), y(t) \ra$, where $x$ and $y$ are differentiable functions on an interval in $t$ that contains $t_0$ with $P(a, b) = (x(t_0), y(t_0))$. As we vary $t$ and follow $C$, the rate of change of $f$ is given by the Chain Rule:
$$
\begin{aligned}
\frac{df}{dt} = \frac{\partial f}{\partial x} \frac{dx}{dt} + \frac{\partial f}{\partial y} \frac{dy}{dt} = \nabla f \cdot r'(t)
\end{aligned}
$$
At the point $(x(t_0), y(t_0)) = (a, b)$ at which $f$ has a local maximum or minimum value, we have $\dfrac{df}{dt}\big \vert_{t = t_0} = 0$, which implies that $\nabla f \cdot r'(t) = 0$. Because $r'(t)$ is tangent to $C$, the gradient $\nabla f(a, b)$ is orthogonal to the line tange to $C$ at $P$.
To prove the second assertion, note that the constraint curve $C$ given by $g(x, y) = 0$ is also a level curve of the surface $z= g(x, y)$. Recall that the gradients are orthogonal to level curves. Therefore, at the point $P(a, b)$, $\nabla g(a, b)$ is orthogonal to $C$ at $(a, b)$. Because both $\nabla f(a, b)$ and $\nabla g(a, b)$ are orthogonal to $C$, the gradients are parallel, so there is a real number $\lm$ such that $\nabla f(a, b) = \lm \nabla g(a, b)$.

##### Method of Lagrange Multiplier in Two Variables
Let the objective function $f$ and the constraint function $g$ be differentiable on a region of $\R^2$ with $$\nabla g(a, b) \ne 0$ on the curve $g(x, y) = 0$. To locate the maximum and minimum values of $f$ subject to the constraint $g(x, y) = 0$, carry out the following steps.

1\. Find the values of $x, y$ and $\lm$ (if they exist) that satisfy the equations
$$
\begin{aligned}
\nabla f(a, b) = \lm \nabla g(a, b) \text{ and } g(x, y) = 0
\end{aligned}
$$
2\. Among the values $(x, y)$ found in step 1, select the largest and smallest corresonding function values, which are the maximum and minimum values of $f$ subject to the constraint.

##### EXAMPLE 1 Lagrange multipliers with two variables
Find the maximum and minimum values of the objective function $f(x, y) = 2x^2 + y^2 + 2$, where $x$ and $y$ lie on the ellipse $C$ given by $g(x, y) = x^2 + 4y^2 -4 = 0$.
>Solution
$f_{max} (\pm 2, 0) = 10$, $f_{min}(0, \pm 1) = 3$

#### Lagrange Multipliers with THree Independent Variables

##### EXAMPLE 2  A geometry problem
Find the least distance between the point $P(3, 4, 0)$ and the surface of the cone $z^2 = x^2 + y^2$.
>Solution
$$
\begin{aligned}
d (x, y, z) = \sqrt{(x-3)^2 + (y-4)^2 + z^2}
\end{aligned}
$$
The minimum distance is $\sqrt{\frac{25}{2}}$. The points are $(\frac{3}{2}, 2, \pm \frac{5}{2})$.
