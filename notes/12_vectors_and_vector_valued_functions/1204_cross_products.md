### Section 12.4 Cross Products

#### The Cross product
Given two nonzero vectors $u$ and $v$ in $\R^3$, the cross product $u\times v$ is a vector with magnitude
$$
\begin{aligned}
|u \times v| = |u| |v| \sin \th
\end{aligned}
$$
where $0 \les \th \les \pi$ is the angle between $u$ and $v$. The direction of $u \times v$ is given by the right-hand rule: When you put the vectors to tail and let the fingers of your right hand curl from $u$ to $v$, the direction of $u \times v$ is the direction of your thumb, orthogonal to both $u$ and $v$. When $u\times v = 0$, the direction of $u \times v$ is undefined.

##### Geometry of the Cross Product
Let $u$ and $v$ be two nonzero vectors in $\R^3$.
1\. The vectors $u$ and $v$ are parallel ($\th = 0$ or $\th = \pi$) if and only if $u\times v = 0$.
2\. If $u$ and $v$ are two sides of a parallelogram, then the area of the parallelogram is
$$
\begin{aligned}
|u \times v| = |u| |v| \sin \th
\end{aligned}
$$

##### EXAMPLE 1 A cross product
Find the magnitude and direction of $u\times v$, where $u = \la 1, 1, 0 \ra$, and $v=\la 1, 1, \sqrt{2} \ra$
>Solution
$|u \times v| = |u| |v| \sin \th = \sqrt{2} \cdot 2 \cdot \frac{1}{\sqrt{2}} = 2$. The direction is given by the right-hand rule.

####  Prpperties of the Cross Product
Let $u, v$, and $w$ be nonzero vectors in $\R^3$, and let $a$ and $b$ be scalars.
1\. $u \times v = -(v \times u)$
2\. $(au) \times (bv) = ab(u \times v)$
3\. $u \times (v + w) = (u \times v) + (u \times w)$
4\. $(u + v) \times w = (u \times w) + (v \times w)$

##### Cross Products of Coordinate Unit Vectors
$$
\begin{aligned}
i \times j &= - (j \times i) = k\\
j \times k &= - (k \times j) = i\\
k \times i &= - (i \times k) = j\\
i \times i &= j \times j = j = k \times k = 0
\end{aligned}
$$

##### Evaluating the Cross Product
Let $u = u_1 \ihat + u_2 \ihat + u_3 \khat$ and $v = v_1 \ihat + v_2 \ihat + v_3 \khat$. Then
$$
\begin{aligned}
u \times v = \begin{vmatrix}
 i & j & k\\
u_1& u_2 & u_3\\
v_1& v_2 & v_3
\end{vmatrix} = \begin{vmatrix}
u_2 & u_3\\
v_2 & v_3
\end{vmatrix} \ihat + \begin{vmatrix}
u_1 & u_3\\
v_1 & v_3
\end{vmatrix} \jhat + \begin{vmatrix}
u_1 & u_2\\
v_1 & v_2
\end{vmatrix} \khat
\end{aligned}
$$

##### EXAMPLE 3 Area of a Triangle
Find the area of the triangle with vertices $O(0,0,0), P(0,0,0)$, $Q(3, 2, 0)$
>Solution
The area of the parallelogram is $\vec{OP} \times \vec{OQ} = \la -8, 12, -5 \ra$. The area of the triangle is half of that of the parallelogram.

##### EXAMPLE 4 Vector normal to two vectors
Find a vector normal to the two vectors $u = \la -1, 0, 6 \ra$, and $v= \la 2, -5, -3 \ra$
>Solution
A vector normal to $u$ and $v$ is parallel to $u \times v$. One normal vector is
$$
\begin{aligned}
u \times v = \la 30, 9, 5 \ra
\end{aligned}
$$

#### Applications of the Cross Product
+ Torque $|\tau|= | r \times F = |r| |F| \sin \th$
+ Force on a proton $|F| = |q| |v\times B| = |q| |v| |B| \sin\th$

#### Homework
p817: 4, 7, 9, 10, 13, 15-25odd, 29, 32, **35**, 39, 42, 45, 55, **63**, 65

4\. If u and v are orthogonal, what is the magnitude of $u \times v$?
>Solution
$u \times v = |u||v|$

7–8\. **Cross products from the definition** Find the cross product $u \times v$ in each figure.
>Solution
7\. $u \times v = \la 3, 0, 0 \ra \times \la 0, 5, 0 \ra = \la 0, 0, 15 \ra$.
8\. $u \times v = \la -4, 0, 0 \ra \times \la 0, 0, 2 \ra = \la 0, 8, 0 \ra$.

9–12\. **Cross products from the definition** Sketch the following vectors u and v. Then compute $|u \times v|$ and show the cross product on your sketch.
9\. $u=\la 0, -2, 0 \ra, v=\la 0, 1, 0 \ra$
>Solution
u and v are parallel. $u \times v = 0$.

10\. $u=\la 0, 4, 0 \ra, v=\la 0, 0, 8 \ra$
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
\vec{AB} &= \la 3, 0, 1 \ra \quad \vec{AC} = \la 1, 1, 0 \ra\\
\vec{AB} \times \vec{AC} &= \begin{vmatrix}
   i & j & k\\
   3 & 0 & 1\\
   1 & 1 & 0
\end{vmatrix} =  -i + j + 3k\\
Area &= \frac{1}{2} |-i + j + 3k| = \frac{\sqrt{11}}{2}
\end{aligned}
$$

29–34\. **Computing cross products** Find the cross products $u \times v$ and $v \times u$ for the following vectors $u$ and $v$.
29\. $u=\la 3, 5, 0 \ra, v = \la 0, 3, -6 \ra$
>Solution
$u \times v = \begin{vmatrix}
   i & j & k\\
   3 & 5 & 0\\
   0 & 3 & -6
\end{vmatrix} = -30i+18j + 9k$
$v \times u = -(u \times v) = 30i -18j - 9k$

32\. $u=\la 3, -4, 6 \ra, v = \la 1, 2, -1 \ra$
>Solution
$u \times v = \begin{vmatrix}
   i & j & k\\
   3 & -4 & 6\\
   1 & 2 & -1
\end{vmatrix} = -8i+9j + 10k$
$v \times u = -(u \times v) = 8i -9j - 10k$

35–38\. **Normal vectors** Find a vector normal to the given vectors.
35\. $\la 0, 1, 2 \ra$ and $\la -2, 0, 3 \ra$.
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
42\. Let $r=\vec{OP} = i-j+2k$. A force $F=\la 10, 10, 0 \ra$ is applied at $P$. Find the torque about $O$ that is produced.
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
55\. The side of $T$ are $u=\la 3, 3, 3 \ra, v= \la 6, 0, 6 \ra$, and $u-v$
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

62–64\. **Scalar triple product** Another operation with vectors is the scalar triple product, defined to be $u \cdot (v \times w)$, for vectors u, v, and w in $\R^3$.
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
The magnitude of the torque is $26.4 N\cdot m$, and the direction is negative x-axis.
