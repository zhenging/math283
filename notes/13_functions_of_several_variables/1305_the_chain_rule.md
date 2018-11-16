### Section 13.5 The Chain Rule

#### Chain Rule With One Independent Variable
Let $z$ be a differentiable function of $x$ and $y$ on its domain, where x and y are differentiable functions of t on an interval $I$. Then
$$
\begin{aligned}
\frac{dz}{dt} = \frac{\partial z}{dx} \frac{dx}{dt} + \frac{\partial z}{dy} \frac{dy}{dt}
\end{aligned}
$$

#### Chain Rule With Several Independent Variables
Let $z$ be a differentiable function of $x$ and $y$ on its domain, where x and y are differentiable functions of $s$ and $t$. Then
$$
\begin{aligned}
\frac{dz}{ds} &= \frac{\partial z}{dx} \frac{dx}{ds} + \frac{\partial z}{dy} \frac{dy}{ds}\\
\frac{dz}{dt} &= \frac{\partial z}{dx} \frac{dx}{dt} + \frac{\partial z}{dy} \frac{dy}{dt}
\end{aligned}
$$

##### EXAMPLE 2 Chain Rule with two independent variables
Let $z = \sin 2x \cos 3y$, where $x = s + t$, and $y=s - t$. Evaluate $\partial z/\partial s$ and $\partial z/\partial t$.
>Solution
$$
\begin{aligned}
\frac{\partial z}{\partial s} &= 2\cos[2(s+t)] \cos[3(s-t)] - 3\sin[2(s + t)]\sin [3(s-t)]\\
\frac{\partial z}{\partial t} &= 2\cos[2(s+t)] \cos[3(s-t)] + 3\sin[2(s + t)]\sin [3(s-t)]\\
\end{aligned}
$$

#### Implicit Differentiation
Let $F$ be differentiable on its domain and suppose that $F(x, y) = 0$ defined $y$ as a differentiable function of $x$. Provided $F_y \ne 0$,
$$
\begin{aligned}
\frac{dy}{dx} = -\frac{F_x}{F_y}
\end{aligned}
$$
To find $dy/dx$, we treate $x$ as the independent variable and differentiate both side of $F(x, y(x)) = 0$ with respect to $x$. The derivative of the right side is $0$. On the left side, we use the Chain Rule
$$
\begin{aligned}
\frac{\partial F}{dx} \blue{\underbrace{\frac{dx}{dx}}_{1}} + \frac{\partial F}{dy} \frac{dy}{dx} = 0\\
\To \frac{dy}{dx} &= -\frac{F_x}{F_y}
\end{aligned}
$$

##### EXAMPLE 5 Implicit differentiation
Find $dy/dx$ when $F(x, y) =\sin xy + \pi y^2 - x = 0$.
>Solution
$$
\frac{dy}{dx} = -\frac{F_x}{F_y} = -\frac{y\cos xy - 1}{x\cos xy + 2\pi y}
$$
