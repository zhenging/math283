### Section 12.6 Calculus for Vector-valued Functions

#### Homework
p835: 2, 9-23odd, 26, 27, 31, 33, 37, 38, 43, 49, 51, 53, 56, 59, 63, 66, 69, **73**, 77, 78, 82, **87**, 89a,b

2\. Explain the geometric meaning of $r'(t)$?
>Solution
The vector $r'(t)$ points in the direction of the curve at $P$. $r'(t)$ is the tangent vector at $P$.

7–14. **Derivatives of vector-valued functions** Differentiate the following functions.
9\. $r(t) = \la 2t^3, 6\sqrt t, 3/t \ra$
>Solution
$r'(t) = \la 6t^2, \frac{3}{\sqrt t}, -\frac{3}{t^2} \ra$

11\. $r(t)=\la e^t, 2e^{-t}, -4e^{2t} \ra$
>Solution
$r'(t) = \la e^t, -2e^{-t}, -8e^{2t} \ra$

13\. $r(t) = \la te^{-t}, t\ln t, t\cos t \ra$
>Solution
$r'(t) = \la e^{-t} - te^{-t}, \ln t + 1, \cos t - t\sin t \ra$

15–20. **Tangent vectors** Find a tangent vector at the given value of $t$ for the following curves.
15\. $r(t) = \la t, 3t^2, t^3 \ra, t=1$
>Solution
$r'(t) = \la 1, 6t, 3t^2 \ra, r'(1) = \la 1, 6, 3 \ra$

17\. $r(t) = \la t, \cos{2t}, 2\sin t \ra, t=\pi/2$
>Solution
$r'(t) = \la 1, -2\sin{2t}, 2\cos t \ra, r'(\pi/2) = \la 1, 0, 0 \ra$

19\. $r(t) = \la 2t^4, 6t^{3/2}, 10/t \ra, t=1$
>Solution
$r'(t) = \la 8t^3, 9\sqrt t, -\frac{10}{t^2} \ra, r'(1) = \la 8, 9, -10 \ra$

21–26. **Unit tangent vectors** Find the unit tangent vector for the following parameterized curves.
21\. $r(t) = \la 2t, 2t, t \ra, \text{ for } 0 \les t \les 1$
>Solution
$$
\begin{aligned}
r'(t) &=\la 2, 2, 1 \ra, |r'(t)| = \sqrt{2^2 + 2^2 + 1^2} = 3\\
T(t) &= \frac{r'(t)}{|r'(t)|} = \la \frac{2}{3}, \frac{2}{3}, \frac{1}{3} \ra
\end{aligned}
$$

26\. $r(t) = \la e^{2t}, 2e^{2t}, 2e^{-3t} \ra, \text{ for }  t \ges 0$
>Solution
$$
\begin{aligned}
r'(t) &=\la 2e^{2t}, 4e^{2t}, -6e^{-3t} \ra, |r'(t)| = \sqrt{(2e^{2t})^2 + (4e^{2t})^2 + (-6e^{-3t})^2} = \sqrt{20e^{4t} + 36e^{-}}\\
T(t) &= \frac{r'(t)}{|r'(t)|} =\frac{1}{\sqrt{20e^{4t} + 36e^{-}}} \la 2e^{2t}, 4e^{2t}, -6e^{-3t} \ra
\end{aligned}
$$

27–30. **Unit tangent vectors at a point** Find the unit tangent vector at the given value of $t$ for the following parameterized curves.
27\. $r(t) = \la \cos{2t}, 4, 3\sin{2t} \ra$, for $0 \les t \les \pi; t=\pi/2$
>Solution
$$
\begin{aligned}
r'(t) &= \la -\sin{2t}, 0, 6\cos{2t} \ra\\
r'(\frac{\pi}{2}) &= \la 0, 0, -6 \ra\\
|r'(\frac{\pi}{2})| &= \sqrt{(0 + 0 + (-6)^2} = 6\\
T(\frac{\pi}{2}) &= \frac{r'(\pi/2)}{|r'(\pi/2)|} =\la 0, 0, -1 \ra
\end{aligned}
$$

31–36. **Derivative rules** Let
$$
\begin{aligned}
u(t) = 2t^3\bold{i} + (t^2-1)\bold{j} - 8\bold{k}\\
v(t) = e^t\bold{i} + 2e^{-t}\bold{j} - e^{2t}\bold{k}
\end{aligned}
$$
Compute the derivative of the following functions.
31\. $(t^{12} + 3t)u(t)$
>Solution
$$
\begin{aligned}
u'(t) &= 6t^2\bold{i} + 2t\bold{j} - 0\bold{k}\\
\frac{d}{dt}(t^{12} + 3t)u(t) &= (12t^{11} + 3)\la 2t^3, t^2-1, -8 \ra +  (t^{12} + 3t)\la 6t^2, 2t, 0 \ra\\
&= \la 24t^{14} + 6t^3,  12t^{13}-12t^{11}+3t^2 - 3, -96t^{11}-24\ra + \la 6t^{14}+18t^3, 2t^{13}+6t^2, 0 \ra\\
&= \la 30t^{14} + 24t^3, 14t^{13}-12t^{11}+9t^2 - 3,  -96t^{11}-24\ra
\end{aligned}
$$

33\. $u(t^4-2t)$
>Solution
$$
\begin{aligned}
\frac{d}{dt} u(t^4-2t)&= u'(t^2 - 2t) \cdot \frac{d}{dt}(t^2 - 2t)\\
&= \la 6(t^2-3t)^2, 2(t^2 - 2t), 0 \ra \cdot (2t - 2)\\
&= \la 6(t^2-3t)^2 (2t - 2), 2(t^2 - 2t)(2t - 2), 0 \ra
\end{aligned}
$$

37–40. **Derivative rules** Compute the following derivatives.
37\. $\dfrac{d}{dt}\lb t^2(\bold{i} + 2\bold{j} - 2t\bold{k}) \cdot (e^2\bold{i} + 2e^t\bold{j} - 3e^{-t}\bold{k})\rb$
>Solution
$$
\begin{aligned}
t^2(\bold{i} + 2\bold{j} - 2t\bold{k}) \cdot (e^t\bold{i} + 2e^t\bold{j} - 3e^{-t}\bold{k}) &= t^2e^t \bold{i} + 4t^2e^t\bold{j} + 6t^3e^{-t}\bold{k}\\
\frac{d}{dt}(t^2e^t \bold{i} + 4t^2e^t\bold{j} + 6t^3e^{-t}\bold{k}) &= (t^2e^t + 2te^t)\bold{i} + 4(t^2e^t + 2te^t)\bold{j} + 6(-t^3e^{-t} + 3t^2e^{-t})\bold{k}
\end{aligned}
$$

38\. $\dfrac{d}{dt}\lb (t^3\bold{i} - 2t\bold{j} - 2\bold{k}) \times (t\bold{i}-t^2\bold{j} - t^3\bold{k})\rb$
>Solution
$$
\begin{aligned}
(t^3\bold{i} - 2t\bold{j} - 2\bold{k}) \times (t\bold{i}-t^2\bold{j} - t^3\bold{k} &= \begin{vmatrix}
 i & j & k\\
t^3 & -2t & -2\\
 t & -t^2 & -t^3
 \end{vmatrix}\\
&= \la 2t^4 - 2t^2, t^6 - 2t, -t^5 + 2t^2\ra\\
\frac{d}{dt} \la 2t^4 - 2t^2, t^6 - 2t, -t^5 + 2t^2\ra&=  \la 8t^3-4t, 6t^5-2, -5t^4+4t \ra
\end{aligned}
$$

41–46. **Higher derivatives** Compute $r''(t)$ and $r'''(t)$ for the following functions.
43\. $r(t) = \la t^2 + 1, t + 1, 1 \ra$
>Solution
$$
\begin{aligned}
r'(t) &= \la 2t, 1, 0 \ra\\
r''(t) &= \la 2, 0, 0 \ra\\
r'''(t) &= \la 0, 0, 0 \ra
\end{aligned}
$$

47–52. **Indefinite integrals** Compute the indefinite integral of the following functions.
49\. $r(t) = \la 2\cos t, 2\sin{3t}, 4\cos{8t} \ra$
>Solution
$R(t) = \la 2\sin t, -\dfrac{2}{3}\cos{3t}, \dfrac{1}{2}\sin{4t} \ra + C$

51\. $r(t) = e^{3t}\bold{i} + \dfrac{1}{1 + t^2}\bold{j} - \dfrac{1}{\sqrt{2t}}\bold{k}$
>Solution
$R(t) = \la \dfrac{1}{3}e^{3t}, \tan^{-1} t, -\sqrt{2t} \ra + C$

53–58. Finding $r$ from $r'$ Find the function r that satisfies the given condition.
53\. $r'(t) = \la e^t, \sin t, \sec^2 t \ra$, $r(0) = \la 2, 2, 2 \ra$
>Solution
$$
\begin{aligned}
r(t) &= \int r'(t) dt\\
&= \la e^t, -\cos t, \tan t \ra + C\\
r(0) &= \la 1, -1, 0  \ra + C = \la 2, 2, 2 \ra \\
\To C &= \la 1, 3, 2\ra\\
r(t) &= \la e^t + 1, -\cos t + 3, \tan t  + 2\ra
\end{aligned}
$$

56\. $r'(t) = \la \sqrt t, \cos{\pi t, 4/\pi} \ra$, $r(1) = \la 2, 3, 4 \ra$
>Solution
$$
\begin{aligned}
r(t) &= \int r'(t) dt\\
&= \la \frac{2}{3}t^{3/2}, \frac{\sin{\pi t}}{\pi}, \frac{4t}{\pi} \ra  + C\\
r(1) &= \la \frac{2}{3}, 0, \frac{4}{\pi} \ra + C = \la 2, 3, 4 \ra \\
\To C &=
\end{aligned}
$$

59–66. **Definite integral**s Evaluate the following definite integrals.
59\. $\dint^1_{-1}(\bold{i} + t\bold{j} + 3t^2\bold{k})dt$
>Solution
$$
\begin{aligned}
\int^1_{-1}(\bold{i} + t\bold{j} + 3t^3\bold{k})dt &= \la t, \frac{t^2}{2}, t^3 \ra |^1_{-1}\\
&=\la 2, 0, 2 \ra
\end{aligned}
$$

63\. $\dint^{\pi}_{-\pi}(\sin t\bold{i} + \cos t\bold{j} + 2t\bold{k})dt$
>Solution
$$
\begin{aligned}
\int^{\pi}_{-\pi}(\sin t\bold{i} + \cos t\bold{j} + 2t\bold{k})dt &= \la -\cos t, \sin t, t^2 \ra |^{\pi}_{-\pi}\\
&= \la 0,0,0 \ra
\end{aligned}
$$

66\. $\dint^{\pi/4}_0(\sec^2 t\bold{i} - 2\cos t\bold{j} - \bold{k})dt$
>Solution
$$
\begin{aligned}
\int^{\pi/4}_0(\sec^2 t\bold{i} - 2\cos t\bold{j} - \bold{k})dt &= \la \tan t, -2\sin t, -t \ra | ^{\pi/4}_0\\
&= \la 1, -\sqrt 2, -\frac{\pi}{4} \ra
\end{aligned}
$$

68–71. **Tangent lines** Suppose the vector-valued function $r(t) = \la f(t), g(t), h(t) \ra$ is smooth on an interval containing the point $\la f(t_0), h(t_0), g(t_0) \ra$. The line tangent to $r(t)$ at $t = t_0$ is the line parallel to the tangent vector $r'(t_0)$ that passes through $\la f(t_0), h(t_0), g(t_0) \ra$. For each of the following functions, find the line tangent to the curve at $t = t_0$.
69\. $r(t) = \la 2 + \cos t, 3 + \sin{2t}, t \ra$; $t_0 = \pi / 2$
>Solution
$$
\begin{aligned}
r'(t) &= \la -\sin t, 2\cos 2t, 1 \ra\\
r'(\pi/2) &= \la -1, -2, 1 \ra\\
r(t_0) &= \la 2, 3, \pi/2\ra
\end{aligned}
$$
The equation of tangent line is $\la 2 - t, 3-2t, \pi/2 + t\ra$.

72-77. **Derivative rules** Let $u(t) = \la 1, t, t^2 \ra$, $v(t) = \la t^2, -2t, 1 \ra$, and $g(t) = 2\sqrt t$. Compute the derivative of the following functions.
73\. $v(e^t)$
>Solution
$$
\begin{aligned}
\frac{d}{dt}v(e^t) &= v'(e^t) e^t\\
&= e^t\la 2e^t, -2, 0  \ra\\
&= \la 2e^{2t}, -2e^t, 0 \ra
\end{aligned}
$$

77\. $u(t) \times v(t)$
>Solution
$$
\begin{aligned}
u(t) \times v(t) &= \begin{vmatrix}
 i & j & k\\
1 & t & t^2\\
 t^2 & -2t & 1
 \end{vmatrix} = \la t + 2t^3, t^4-1, -2t-t^3 \ra\\
 \frac{d}{dt}\lb u(t) \times v(t) \rb &= \la 6t^2 + 1, 4t^3, -3t^3 - 2 \ra
\end{aligned}
$$

78–83. **Relationship between $r$ and $r'$**
78\. Consier the circle $r(t) = \la a\cos t, a\sin t \ra$, for $0 \les t \les 2\pi$, whera $a$ is a positive real number. Compute $r'$ and show that it is orthogonal to $r$ for all $t$.
>Solution
$$
\begin{aligned}
r'(t) &= \la -a\sin t, a\cos t \ra\\
r(t)\cdot r'(t) &= -a^2\sin t \cos t + a^2\sin t \cos t = 0
\end{aligned}
$$

82\. Consier the ellipse $r(t) = \la 2\cos t, 8\sin t, 0 \ra$, for $0 \les t \les 2\pi$. Find all points on the ellipse at which $r$ and $r'$ are orthogonal.
>Solution
$$
\begin{aligned}
r'(t) &= \la -2\sin t, 8\cos t, 0 \ra\\
r(t) \cdot r'(t) &= -2\sin t \cos t + 64\sin t \cos t + 0 \\
&=\sin{2t} = 0\\
\To &t = 0, \frac{\pi}{2}, \pi, \frac{3\pi}{2}
\end{aligned}
$$
At points (2, 0, 0), (0, 8, 0), (-2, 0, 0), (0, -8, 0), $r$ and $r'$ are orthogonal.

87\. **Proof of Product Rule** By expressing $u$ in terms of its components, prove that $\dfrac{d}{dt}(f(t)u(t)) = f'(t)u(t) + f(t)u'(t)$
>Solution
$$
\begin{aligned}
\frac{d}{dt}(f(t)u(t)) &= \frac{d}{dt}\la f(t)u_1(t), f(t)u_2(t), f(t)u_3(t) \ra\\
&= \la f'(t)u_1(t) + f(t)u'_1(t), f'(t)u_2(t) + f(t)u'_2(t), f'(t)u_3(t) + f(t)u'_3(t) \ra\\
&= \la f'(t)u_1(t), f'(t)u_2(t) , f'(t)u_3(t) \ra + \la f(t)u'_1(t), f(t)u'_2(t) , f(t)u'_3(t) \ra\\
&= f'(t)\la u_1(t), u_2(t), u_3(t) \ra + f(t) \la u'_1(t), u'_2(t), u'_3(t)  \ra\\
&= f'(t)u(t) + f(t)u'(t)
\end{aligned}
$$

89\. **Cusps and noncusps**
a\. Graph the curve $r(t) = \la t^3, t^3 \ra$. Show that $r'(0) = 0$ and the curve does not have a cusp at $t=0$.
>Solution
$$
\begin{aligned}
r'(t) &= \la 3t^2, 3t^2 \ra\\
r'(0) &= \la 0, 0 \ra\\
\lim_{t \to 0}\frac{dy}{dx} &= \frac{dy/dt}{dx/dt} = \frac{3t^2}{2t^2} = 1
\end{aligned}
$$
Therefore, there is no cusp at $t=0$.

b. Graph the curve $r(t) = \la t^3, t^2 \ra$. Show that $r'(0) = 0$ and the curve has a cusp at $t=0$. Explain.
>Solution
$$
\begin{aligned}
r'(t) &= \la 3t^2, 2t \ra\\
r'(0) &= \la 0, 0 \ra\\
\lim_{t \to 0}\frac{dy}{dx} &= \lim_{t \to 0}\frac{dy/dt}{dx/dt}\\
&= \lim_{t \to 0} \frac{2}{3t} &\bold{DNE}
\end{aligned}
$$
Therefore, the curve has a cusp at $t=0$.
