### Section 15.3 Conservative Vector Fields

#### Types of Curves and Regions
+ Simple and Closed curves
+ Connected and Simply Connected Regions

#### Test for conservative Vector Field
A vector field is said to be conservative on a region (in $\R^2$ or $\R^3$) if there exists a scalar function $\varphi$ such that $F = \nabla\varphi$.

#### Finding Potential Functions

#### Fundamental Theorem for Line Integrals and Path Independence
Let $F$ be a continuous vector field on an open connnected region \in $\R^2$ (or $D$ in $\R^3$). There exists a potential function $\varphi$ with $F = \nabla\varphi$ (which means) that $F$ is conservative if and only if
$$
\begin{aligned}
\int_C F\cdot T s = \int_C F\cdot dr = \varphi (B) - \varphi (A),
\end{aligned}
$$
for all points $A$ and $B$ in $R$ and all smooth oriented curves $C$ from $A$ and $B$.

#### Line Integrals on Closed Curves
Let $R$ in $\R^2$ (or $D$ in $\R^3$) be an open region. Then $F$ is a conservative vector field on $R$ if and only if $\oint_C F \cdot dr = 0$ on all simple closed smooth oriented curves $C$ in $R$.

##### EXAMPLE 5 A closed curve line integral in $\R^3$
Evaluate $\dint_C \nabla(-xy + xz + yz) \cdot dr$ on the curve $C:r(t) = \la \sin t, \cos t, \sin t \ra$, for $0 \les t \les 2\pi$, without using Theorems 15.4 or 15.5.
>Solution
$0$.
