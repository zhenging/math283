### Section 12.9 Curvature and Normal Vectors

#### Curvature
If a small increment in arc length $\Delta s$ along the curve results in a large change in the direction of $T$, the curve is turning quickly over that interval and we say it has a large curvature ( Figure 12.102a). If a small increment $\Delta s$ in arc length results in a small change in the direction of $T$, the curve is turning slowly over that interval and it has a small curvature (Figure 12.102b). The magnitude of the rate at which the direction of $T$ changes with respect to arc length is the **curvature** of the curve.
![Graph](../assets/fig12_102.png)

Let $r$ describe a smooth parameterized curve. If $s$ denotes arc length and $T = \dfrac{r'}{|r'|}$ is the unit tangent vector, the **curvature** is $\kappa(s) = |\dfrac{dT}{ds}|$.

##### Curvature Formula
$$
\begin{aligned}
\kappa(s) &= |\dfrac{dT}{ds}|\\
\kappa(t) & = \frac{|dT/dt|}{|ds/dt|} \\
&= \frac{1}{|v|}\lvert\frac{dT}{dt}\rvert = \frac{|T'(t)|}{|r'(t)|}
\end{aligned}
$$

##### Alternative Curvature Formula
$$
\begin{aligned}
\kappa = \frac{|v \times a|}{|v|^3}
\end{aligned}
$$
where $v = r'$ is the velocity and $a=v'$ is the acceleration.

#### Principal Unit Normal Vector
Let $r$ describe a smooth parameterized curve. The principal unit normal vector at a point $P$ on the curve at which $\kappa \ne 0$ is
$$
\begin{aligned}
N(s) = \frac{dT/ds}{|dT/ds|} = \frac{1}{\kappa} \frac{dT}{ds}
\end{aligned}
$$
In practice, we use the equivalent formula
$$
\begin{aligned}
N(t) = \frac{dT/dt}{|dT/dt|}
\end{aligned}
$$
evaluated at value of $t$ corresponding to $P$.

##### Proerties of the Principal Unit NOrmal Vector
Let $r$ describe a smooth parameterized curve with unit tangent vector $T$ and principal unit normal vector $N$.
1\. $T$ and $N$ are orthogonal at all points of the curve; that is, $T(t) \cdot N(t) = 0$ at all points where $N$ is defined.
2\. The principal unit normal vector points to the inside of the curve - in the direction that the curve is turning.

#### Components of the Acceleration
The acceleration vector of an object moving in space along a smooth curve has the following representation in terms of its **tangential component** $a_T$ (in the direction of $T$) and its **normal component** $a_N$ (in the direction of $N$):
$$
\begin{aligned}
a &= a_N N + a_T T\\
a_N &= \kappa |v|^2 = \frac{|v \times a|}{|v|}\\
a_T &= \frac{d^2s}{dt^2}
\end{aligned}
$$

#### The Binormal Vector and Torsion
Let $C$ be a smooth parameterized curve with unit tangent and principal unit normal vectors $T$ and $N$, respectively. Then, at each point of the curve at which the curvature is nonzero, the unit binormal vector is
$$
\begin{aligned}
B = T \times N
\end{aligned}
$$
and the torsion is
$$
\begin{aligned}
\tau = -\frac{dB}{ds} \cdot N
\end{aligned}
$$

#### Homework
p874: 4, 11, 12, 15, 19, 21, 25, 26, 27, 31, 34, 41, 45, 47, 50, 51, 63, 69
