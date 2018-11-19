### Section 15.2 Line Integrals

#### Scalar Line Integrals in the Plane
Suppose the scalar-valued function $f$ is defined on the smooth curve $C:r(s) = \la x(s), y(s) \ra$, parameterized by the arc length $s$. The line integral of $f$ over $C$ is
$$
\begin{aligned}
\int_C f(x(s), y(s)) ds = \lim_{\Delta \to 0} \sum_{k=1}^b f(x(s_k^*), y(s_k^*))
\end{aligned}
$$
provided this limit exists over all partitions of $C$. When the limit exists, $f$ is said to be integrable on $C$.

![Graph](../assets/1517.png)

##### EXAMPLE 1 Average temperature on a circle
The temperature of the circular plate $R = \{ (x, y): x^2 + y^2 \les 1\}$ is $T(x, y) = 100(x^2 + 2y^2)$. Find the average temperature along the edge of the plate.
>Solution
Calculating the average value required integrating the temperature function over the boundary circle $C = \{ (x, y): x^2 + y^2 = 1\}$ and dividing by the length (circumference) of $C$.
$$
\begin{aligned}
\int_C T(x, y)ds = 300 \pi
\end{aligned}
$$

##### Evaluating Scalar Line Integrals in $\R^2$
Left f be continuous on a region containing a smooth curve $C:r(t) = \la x(t), y(t) \ra$, for $a \les x \les b$. Then
$$
\begin{aligned}
\int_C fs &= \int_a^v f(x(t), y(t)) |r'(t)| dt\\
&= \int_a^v f(x(t), y(t)) \sqrt{x'(t)^2 + y'(t)^2} dt
\end{aligned}
$$

#### Line Integrals in $\R^3$

##### EXAMPLE 3 Line integrals in $\R^3$
Evaluate $\dint_C (xy + 2z) ds$ on the following segments.
a. The line sements from $P(1, 0, 0)$ to $Q(0, 1, 1)$.
b. The line sements from $Q(0, 1, 1)$ to $P(1, 0, 0)$.
>Solution
Both a and b yield the same result $\frac{7\sqrt 3}{6}$. A scalar line integral is independent of the orientation and parameterization of the curve.

##### EXAMPLE 4 Flight of an eagle
An eagle soars on the ascending spiral path $C: r(t) = \la x(t), y(t), z(t) \ra = \la 2400\cos \frac{t}{2}, 2400\sin \frac{t}{2}, 500t \ra$, where $x, y$ and $z$ are measured in feet and $t$ is measured in miniutes. How far does the eagle fly over the time interval $0 \les t \les 10$?
>Solution
$13000$ ft.

#### Line Integrals of Vector Fields
Let $F$ be a vector field that is continuous on a region containing a smooth oreiented curvce $C$ parameterized by arc length. Let $T$ be the unit tangent vector at each point of $C$ consistent with the orientation. The line integral of $F$ over $C$ is $\dint_C F \cdot T ds$.

Suppose that $C$ has a parameterization $r(t) = \la x(t), y(t), z(t) \ra$, for $a \les x \les b$. The unit vector at a point on the curve is
$$
T = \frac{r'(t)}{|r'(t)}
$$
The arc length differential $ds = |r'(t)|dt$, then the line integral becomes
$$
\begin{aligned}
\int_C F \cdot T ds &= \int_a^b F\cdot \frac{r'(t)}{|r'(t)} |r'(t)|dt\\
&= \int_a^b F\cdot r'(t) dt\\
&= \int_a^b (fx'(t) + gy'(t) + hz'(t)) dt\\
&= \int_C fdx + gdy + hdz\\
&= \int_C F\cdot dr
\end{aligned}
$$

##### EXAMPLE 5 Different Path
Evaluate $\int_C F \cdot T ds$ with $F = \la y-x, x \ra$ on the following oriented plath in $\R^2$.
a. The quarter circle $C_1$ from $P(0, 1)$ to $Q(1, 0)$.
b. The quarter circle $-C_1$ from $Q(0, 1)$ to $P(1, 0)$.
c. THe path $C_2$ form P to Q via two line segments through $O(0, 0)$.
>Solution
a. $\frac{1}{2}$
b. $-\frac{1}{2}$
c. $-\frac{1}{2}$

##### Work Integrals

#### Circulation
Let $F$ be a continuous vector field on a region $D$ of $\R^3$ and let $C$ be a closed smooth oriented curve in $D$. The **circulation** of $F$ on $C$ is $\dint_C F \cdot T ds$, where $T$ is the unit vector tangent to $C$ consistent with the orientation.

##### EXAMPLE 7 Circulation of two-dimensional flows
Let $C$ be the unit circle with counterclockwise orientation. Find the circulation on $C$ for the following vector fields.
a. The radial flow field $F = \la x, y \ra$
b. The radial flow field $F = \la -y, x \ra$
>Solution
a. $0$.
b. $2\pi$

#### Flux
Let $F$ be a continuous vector field on a region $R$ of $\R^2$. let $C:r(t) = \la x(t), y(t) \ra$, for $a \les t \les b$, be a closed smooth oriented curve in $R$ that does not intersect itself. The **flux** of $F$ across $C$ is
$$
\int_C F\cdot n ds = \int_a^b (fy'(t) - gx'(t))dt
$$
where $n = T\times \khat$ is the unit normal vector and $T$ is the unit tangent vector consistent with the orientation. If $C$ is a closed curve with counterclockwise orientation, $n$ is the outward normal vector and the flux integral gives the outward flux across $C$.

##### EXAMPLE 9 Flux of two-dimensional flows
Find the outward flux across the unit circle with counterclockwise orientation for the following vector fields.
a. The radial flow field $F = \la x, y \ra$
b. The radial flow field $F = \la -y, x \ra$
>Solution
a. $2\pi$.
b. $0$
