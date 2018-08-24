### Section 12.4 Cross Products

#### Homework
p817: 4, 7, 9, 10, 13, 15-25odd, 29, 32, **35**, 39, 42, 45, 55, **63**, 65

4\. If u and v are orthogonal, what is the magnitude of $u \times v$?
>Solution
$u \times v = |u||v|$

7–8\. **Cross products from the definition** Find the cross product $u \times v$ in each figure.
>Solution
7\. $u \times v = \langle 3, 0, 0 \rangle \times \langle 0, 5, 0 \rangle = \langle 0, 0, 15 \rangle$.
8\. $u \times v = \langle -4, 0, 0 \rangle \times \langle 0, 0, 2 \rangle = \langle 0, 8, 0 \rangle$.

9–12\. **Cross products from the definition** Sketch the following vectors u and v. Then compute $|u \times v|$ and show the cross product on your sketch.
9\. $u=\langle 0, -2, 0 \rangle, v=\langle 0, 1, 0 \rangle$
>Solution
u and v are parallel. $u \times v = 0$.

10\. $u=\langle 0, 4, 0 \rangle, v=\langle 0, 0, 8 \rangle$
>Solution
u and v are orthogonal. $u \times v = |u||v| = 4 \times 8 = 32$.

13\. **Magnitude of a cross product** Compute $|u \times v|$ if u and v are unit vectors and the angle between u and v is $\pi/4$.
>Solution
$|u \times v| = |u| |v| \sin\frac{\pi}{4} = 1\times 1 \times \frac{\sqrt 2}{2} = \frac{\sqrt 2}{2}$

15–20\. **Coordinate unit vectors** Compute the following cross products. Then make a sketch showing the two vectors and their cross product.
15\. $j \times k$
>Solution
$j \times k= i$

17\.  $-j \times k$
>Solution
$-j \times k= -i$

19\. $-2i \times 3k$
>Solution
$-2i \times 3k = 6j$

21–24\. **Area of a parallelogram** Find the area of the parallelogram that has two adjacent sides u and v.
21\. $u = 3i-j, v=3j + 2k$
>Solution
Let the area be $A$, $A = |u \times v|$.
$$
\begin{aligned}
u \times v &= \begin{vmatrix}
   i & j & k\\
   3 & -1 & 0\\
   0 & 3 & 2
\end{vmatrix}
= \begin{vmatrix}
   -1 & 0\\
   3 & 2
\end{vmatrix} i - \begin{vmatrix}
   3 & 0\\
   0 & 2
\end{vmatrix} j + \begin{vmatrix}
   3 & -1\\
   0 & 3
\end{vmatrix} k\\
&= -2i-6j+9k\\
A &= |u \times v| = |-2i-6j+9k| = 11
\end{aligned}
$$

23\. $u = 2i-j-2k, v=3i + 2j-k$
>Solution
Let the area be $A$, $A = |u \times v|$.
$$
\begin{aligned}
u \times v &= \begin{vmatrix}
   i & j & k\\
   2 & -1 & -2\\
   3 & 2 & -1
\end{vmatrix}
= \begin{vmatrix}
   -1 & -2\\
   2 & -1
\end{vmatrix} i - \begin{vmatrix}
   2 & -2\\
   3 & -1
\end{vmatrix} j + \begin{vmatrix}
   2 & -1\\
   3 & 2
\end{vmatrix} k\\
&= 5i-4j+7k\\
A &= |u \times v| = |5i-4j+7k| = \sqrt{90}
\end{aligned}
$$

25–28\. **Area of a triangl**e For the given points $A, B$, and $C$, find the area of the triangle with vertices $A, B$, and $C$.
25\. $A(0, 0, 0), B(3, 0, 1), C(1, 1, 0)$
>Solution
$$
\begin{aligned}
Area &= \frac{1}{2} |\vec{AB} \times \vec{AC}|\\
\vec{AB} &= \langle 3, 0, 1 \rangle \quad \vec{AC} = \langle 1, 1, 0 \rangle\\
\vec{AB} \times \vec{AC} &= \begin{vmatrix}
   i & j & k\\
   3 & 0 & 1\\
   1 & 1 & 0
\end{vmatrix} =  -i + j + 3k\\
Area &= \frac{1}{2} |-i + j + 3k| = \frac{\sqrt{11}}{2}
\end{aligned}
$$

29–34\. **Computing cross products** Find the cross products $u \times v$ and $v \times u$ for the following vectors $u$ and $v$.
29\. $u=\langle 3, 5, 0 \rangle, v = \langle 0, 3, -6 \rangle$
>Solution
$u \times v = \begin{vmatrix}
   i & j & k\\
   3 & 5 & 0\\
   0 & 3 & -6
\end{vmatrix} = -30i+18j + 9k$
$v \times u = -(u \times v) = 30i -18j - 9k$

32\. $u=\langle 3, -4, 6 \rangle, v = \langle 1, 2, -1 \rangle$
>Solution
$u \times v = \begin{vmatrix}
   i & j & k\\
   3 & -4 & 6\\
   1 & 2 & -1
\end{vmatrix} = -8i+9j + 10k$
$v \times u = -(u \times v) = 8i -9j - 10k$

35–38\. **Normal vectors** Find a vector normal to the given vectors.
35\. $\langle 0, 1, 2 \rangle$ and $\langle -2, 0, 3 \rangle$.
>Solution
A vectoc normal to u and v is parallel to $u \times v$. One normal vector is
$\begin{vmatrix}
   i & j & k\\
   0 & 1 & 2\\
   -2 & 0 & 3
\end{vmatrix} = 3i - 4j + 2k$

39\. **Tightening a bolt** Suppose you apply a force of 20 N to a 0.25-meter-long wrench attached to a bolt in a direction perpendicular to the bolt. Determine the magnitude of the torque when the force is applied at an angle of $45\degree$ to the wrench.
>Solution
$|\tau| = |r| |F| \sin \th = (0.25m)(20N)\sin(45\degree) = \frac{5\sqrt 2}{2}N\cdot m$

41–44\. **Computing torque** Answer the following questions about torque.
42\. Let $r=\vec{OP} = i-j+2k$. A force $F=\langle 10, 10, 0 \rangle$ is applied at $P$. Find the torque about $O$ that is produced.
>Solution
$$
\begin{aligned}
\tau &= r \times F = \begin{vmatrix}
   i & j & k\\
   1 & -1 & 2\\
   10 & 10 & 0
\end{vmatrix}\\
&= (0-20)i-(0-20)j+(20)k\\
&= -20i+20j + 20k
\end{aligned}
$$

45–48\. **Force on a moving charge** Answer the following questions about force on a moving charge.
45\. A particle with a positive unit charge $(q = 1)$ enters a constant magnetic field $B = i + j$ with a velocity $v = 20k$. Find the magnitude and direction of the force on the particle. Make a sketch of the magnetic field, the velocity, and the force.
>Solution
$$
\begin{aligned}
F &= q(v\times B)\\
&= \begin{vmatrix}
   i & j & k\\
   0 & 0 & 20\\
   1 & 1 & 0
\end{vmatrix} = -20i + 20j\\
|F| &= |-20i + 20j| = 20\sqrt 2
\end{aligned}
$$
The magnitude of the force is $20\sqrt 2$N and the angle of the force is 135 degreee with the positive x-axis.

54–57\. **Areas of triangles** Find the area of the following triangles $T$. (The area of a triangle is half the area of the corresponding parallelogram.)
55\. The side of $T$ are $u=\langle 3, 3, 3 \rangle, v= \langle 6, 0, 6 \rangle$, and $u-v$
>Solution
$$
\begin{aligned}
Area &= \frac{1}{2} |u \times v|\\
&= \frac{1}{2}\begin{Vmatrix}
   i & j & k\\
   3 & 3 & 3\\
   6 & 0 & 6
\end{Vmatrix}\\
&=\frac{1}{2} |18i-18k| = 9\sqrt 2
\end{aligned}
$$

62–64\. **Scalar triple product** Another operation with vectors is the scalar triple product, defined to be $u \cdot (v \times w)$, for vectors u, v, and w in $\mathbb{R}^3$.
63\. Consider the parallelepiped (slanted box) determined by the position vectors u, v, and w (see figure). Show that the volume of the parallelepiped is $|u \cdot (v \times w)|$. Graph (63).
>Solution
$|u \cdot (v \times w)| = |u||v \times w| |\cos \th|$. Because $|v \times w|$ represents the area of the base, we just need to see that the height of the parallelepiped is $|u||\cos \th|$. Note that the height is given by the scalar project of $u$ on $v \times w$, which has value $|u||\cos \th|$. Thus the given expression represents the volume of the parallelepiped.

65\. **Bicycle brakes** A set of caliper brakes exerts a force on the rim of a bicycle wheel that creates a frictional force F of 40 N (see figure). Assuming the wheel has a radius of 66 cm, find the magnitude and direction of the torque about the axle of the wheel.
>Solution
$$
\begin{aligned}
r &= 0.66k \quad F = 40j\\
\tau &= r \times F = \begin{vmatrix}
   i & j & k\\
   0 & 0 & 0.66\\
   0 & 40 & 0
\end{vmatrix} = -26.4i\\
|\tau| &= |-26.4i| = 26.4 N\cdot m
\end{aligned}
$$
The magnitude of the torque is $24.4 N\cdot m$, and the direction is negative x-axis.
