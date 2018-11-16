### Section 15.1 Vector Fields

#### Vector Fields in Two Dimensions
Let $f$ and $g$ are defined on a region $R$ of $\R^2$. A vector field in $\R^2$ is a function $F$ that assigns to each point in $R$ a vector $\la f(x, y), g(x, y)\ra$. The vector field is written as
$$
\begin{aligned}
F(x, y) &= \la f(x, y), g(x, y)\ra \quad \text{Or}\\
F(x, y) &= f(x, y) \ihat+  g(x, y)\jhat
\end{aligned}
$$

##### Radial Vector Fields in $\R^2$
$$
\begin{aligned}
F(x, y) = \frac{r}{|r|^p} = \frac{\la x, y\ra}{|r|^p}
\end{aligned}
$$

#### Vector Fields in Three Dimensions
$$
\begin{aligned}
F(x, y, z) &= \la f(x, y, z), g(x, y, z)\ra \quad \text{Or}\\
F(x, y, z) &= f(x, y, z) \ihat +  g(x, y, z)\jhat +  h(x, y, z)\khat
\end{aligned}
$$
And the radial vector fields
$$
\begin{aligned}
F(x, y, z) = \frac{r}{|r|^p} = \frac{\la x, y, z\ra}{|r|^p}
\end{aligned}
$$

#### Gradient Fields and Potential Functions
A vector field defined as the gradient of a scalar-valued function $\varphi$ is called a **gradient field** and the function $\varphi$is called a **potential function**.

##### EXAMPLE 4 Gradient fields
a. Sketch and interpret the gradient field associated with the temperature function $T = 200 - x^2 - y^2$ on the circular plate $R = \{(x, y): x^2 + y^2 \les 25\}$
b. Sketch and interpret the gradient field associated with the velocity potential $\varphi = \tan^{-1} (y/x)$
>Solution
a. $F = \nabla T = \la -2x, -2y \ra$
b. $\d F = \la \varphi_x, \varphi_y \ra = \la -\frac{y}{x^2 + y^2},  \frac{x}{x^2 + y^2}\ra$

##### Equipotential Curves and Surfaces
The level curve of a potential function are called **equipotential curves** (curves on which the potential function is constant.) The idea also apply to vector field in $\R^3$ in which case the vector field is orthogonal to the **equipotential surfaces**.
