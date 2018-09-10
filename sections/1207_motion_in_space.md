### Section 12.7 Motion In Space

#### Position, Velocity, Speed, Acceleration
let the _position_ of an object moving in the three-dimensional space be given by $r(t) = \langle x(t), y(t), z(t) \rangle$, for $t \ges 0$. The _velocity_ of the object is
$$
v(t) = r'(t) = \langle x'(t), y'(t), z'(t)\rangle
$$
The _speed_ of the object is the scalar function
$$
|v(t)| = \sqrt{x'(t)^2 + y'(t)^2 + z'(t)^2}
$$
The _acceleration_ of the object is
$$
a(t) = v'(t) = r''(t)
$$

#### Straight-Line and Circular Motion

##### Motion with Constant $|r|$
Let $r$ describe a path on which $|r|$ is constant (motion on a circle or spherecentered at the origin). Then, $r \cdot v = 0$, which means the position vector and the velocity vector are orthogonal at all times for which the functions are defined.
**Proof** If $r$ has constant magnitude, then $|r(t)|^2 = r(t) \cdot r(t) = c$ for some consant $c$. Differentiating the equation $r(t) \cdot r(t)$, we have
$$
\begin{aligned}
0 &= \frac{d}{dt}\Big( r(t) \cdot r(t)\Big)\\
&= r'(t)\cdot r(t) + r(t)\cdot r'(t)\\
&= 2r'(t) \cdot r(t)\\
&= 2v(t) \cdot r(t)
\end{aligned}
$$
Because $r(t)\cdot v(t) = 0$ for all $t$, it follows that $r$ and $v$ are orthogonal for all $t$.

#### Homework
p847: 2, 3, 7, 11, 14, 17, 21, 27, 28, 33, 35, 39, 42, 45, 47, 55, 58, 61, 63, 67, 69, 71, 74a, 74b,c, 76
