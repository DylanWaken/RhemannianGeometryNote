-----
Assume $F(t)$ is a matrix function of $t$, $x$ is a vector function of $t$, then the time varying homogeneous equation would be the form: $$\frac{dx}{dt}=F(t)x,\quad x(t_{0})=c$$
The solution to such equation would be of the form: $$x(t) = \Psi (t,t_{0})x(t_{0})$$
- where $\Psi$ is the transition matrix with following properties:
> $\partial \Psi (\tau ,t) / \partial \tau =F(\tau) \Psi (\tau, t)$
> $\partial \Psi (\tau, t) / \partial t = - \Psi (\tau, t)F(t)$
> $\Psi (\tau,t)=\Psi(\tau,s)\Psi(s,t)$
> $\Psi(t, \tau)=\Psi^{-1}(\tau,t)$

The transition matrix have no closed form solution. However, given a transition matrix, we can construct the solution to the following non-homogeneous equation: $$\frac{dx}{dt}=F(t)x + L(t)w(t),\quad x(t_{0})=c$$
as: $$x(t) = x(t) = \Psi (t,t_{0})x(t_{0}) + \int _{t_{0}} ^t  \Psi (t,\tau)L(\tau)w(\tau)\, d\tau $$
