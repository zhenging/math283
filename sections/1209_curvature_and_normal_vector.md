### Section 12.9 Curvature and Normal Vectors

#### Curvature
If a small increment in arc length $\Delta s$ along the curve results in a large change in the direction of $T$, the curve is turning quickly over that interval and we say it has a large curvature ( Figure 12.102a). If a small increment $\Delta s$ in arc length results in a small change in the direction of $T$, the curve is turning slowly over that interval and it has a small curvature (Figure 12.102b). The magnitude of the rate at which the direction of $T$ changes with respect to arc length is the **curvature** of the curve.
![Graph](../assets/12102.png)

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
We assume that $v(t) \ne 0$ and $a(t) \ne 0$. Because $T = v/|v|$, we begin by writing $v = v|T|$ and differentiating both sides with respect to $t$:
$$
\begin{aligned}
a  &= \frac{dv}{dt} = \frac{d}{dt} (|v(t)|T(t)) \\
&= \frac{d}{dt}(|v(t)|)T(t) + |v(t)|\frac{dT}{dt}
\end{aligned}
$$
We now form $v\times  a$:
$$
\begin{aligned}
v \times a &= |v|T \times \Big\lb \frac{d}{dt}(|v(t)|)T + |v(t)|\frac{dT}{dt} \Big\rb \\
&= \underbrace{|v|T \times \Big(\frac{d}{dt}(|v(t)|)T\Big)}_{\text{(1)}} + \underbrace{|v|T \times |v|\frac{dT}{dt}}_{\text{(2)}}\\
&= |v|T \times |v|\frac{dT}{dt}
\end{aligned}
$$
(1) - $|v|T$ and $\dfrac{d}{dt}(|v(t)|)T$ form $aT \times bT$, where $a$ and $b$ are scalars. Therefore $aT$ and $bT$ are parallel vectors and $aT \times bT = 0$.
(2) - $T$ and $\frac{dT}{dt}$ are orthogonal. Therefore, the magnitude of the second term simplifies as follows:
$$
\begin{aligned}
|v\times a| = \Big||v|T \times |v|\frac{dT}{dt}\Big| &= |v||T|\Big||v|\frac{dT}{dt}\Big| \underbrace{\sin\th}_{\text{1}}\\
&= |v|^2 \Big|\frac{dT}{dt}\Big| \underbrace{|T|}_{\text{1}}\\
&= |v|^2 \Big|\frac{dT}{dt}\Big|\\
&= |v|^2 \kappa |v|\\
&= \kappa |v|^3
\end{aligned}
$$
Solving for the curvature gives $\kappa = \dfrac{|v \times a|}{|v|^3}$, where $v = r'$ is the velocity and $a=v'$ is the acceleration.

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

##### Proerties of the Principal Unit Normal Vector
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
Define the _unit binormal vector_ $B = T \times N$. $B$ is orthogonal to both $T$ and $N$. Becase $T$ and $N$ are unit vector, $B$ is also a unit vector. $T, N$ and $B$ form a right handed coordinate system that changes its orientation as we move along the curve. This coordinate system is ofen called the **TNB frame**.
![Graph](../assets/12110.png)
The rate at which the curve $C$ twists out of the plane determined by $T$ and $N$ is the rate at which $B$ changes as we move along $C$, which is $\dfrac{dB}{ds}$.
$$
\begin{aligned}
\frac{dB}{ds} &= \frac{d}{ds}(T\times N)\\
&= \underbrace{\frac{dT}{ds} \times N}_{\text{parallel vectors}} + T \times \frac{dN}{ds}\\
&= 0 + T \times \frac{dN}{ds}
\end{aligned}
$$
(1) - $\dfrac{dB}{ds}$ is orthogonal to both $T$ and $\dfrac{dN}{ds}$, because it is the cross product of $T$ and $\dfrac{dN}{ds}$.
(2) - $\dfrac{dB}{ds}$ is orthogonal to $B$. (Theorem 12.8)
(3) - From (1) and (2), $\dfrac{dB}{ds}$ is orthogonal to both $T$ and $B$, so it must be parallel to $N$. We write
$$
\begin{aligned}
\frac{dB}{ds}  = -\tau N
\end{aligned}
$$
where the scalar $\tau$ is the _torsion_. Notice that $|\dfrac{dB}{ds}| = |-\tau N| = |-\tau|$, so the magnitude of the torsion equals the magnitude of $\dfrac{dB}{ds}$, which is the rate at which the curve twists out of the **TN**-plane.
We take the dot product of both sides of the equation defining the torsion with $N$.
$$
\begin{aligned}
\frac{dB}{ds} \cdot N &= -\tau N \cdot N\\
\frac{dB}{ds} \cdot N &= -\tau\\
\To \tau &= -\frac{dB}{ds} \cdot N
\end{aligned}
$$

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

##### EXAMPLE 8 Unit binormal vectors
Consider the circle $C$ defined by
$$
\begin{aligned}
r(t) = \la R\sin t, R\cos t \ra
\end{aligned}
$$

##### EXAMPLE 9 Torsion of a helix
Compute the torsion of the helix $r(t) = \la a\cos t, a\sin t, bt \ra$ for $t \ges 0$, with $a > 0$ and $b  > 0$.
>Solution
$$
\begin{aligned}
T &= \frac{\la -a\sin t, a\cos t, b \ra}{\sqrt{a^2 + b^2}}\\
N &= \la -\cos t, -\sin t, 0 \ra\\
B &= T\times N = \frac{1}{\sqrt{a^2 + b^2}} \begin{vmatrix}
 i & j & k\\
-a\sin t & a\cos t & b\\
 -\cos t & -\sin t & 0
 \end{vmatrix}\\
 &= \frac{\la b\sin t, -b\cos t, a \ra}{\sqrt{a^2 + b^2}}
\end{aligned}
$$
The next step is to determine $\dfrac{dB}{ds}$, whichy we do in the same way we computed $\dfrac{dT}{ds}$, by writing
$$
\begin{aligned}
\frac{dB}{ds} &= \frac{dB/dt}{ds/dt}  \\
&=  \frac{\la b\cos t, b\sin t, 0 \ra}{\sqrt{a^2 + b^2}} \cdot \frac{1}{\sqrt{a^2\sin^2 t + a^2 \cos^2 t + b^2}}\\
&= \frac{\la b\cos t, b\sin t, 0\ra}{a^2 + b^2}
\end{aligned}
$$
The final step is to compute the torsion
$$
\begin{aligned}
\tau = -\frac{dB}{ds} \cdot N &= -\frac{\la b\cos t, b\sin t, 0\ra}{a^2 + b^2} \cdot \la -\cos t, -\sin t, 0 \ra\\
&= \frac{b}{a^2 + b^2}
\end{aligned}
$$
