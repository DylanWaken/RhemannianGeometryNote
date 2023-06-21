----
Fourier Transform can be used to solve inhomogeneous time-invariant differential equations. The transform is given as: $$G(\mathbf{i}\omega ) = \mathscr{F}[g(t)] = \int _{-\infty} ^\infty g(t)\exp(-\mathbf{i}\omega t) \, dt $$
- $g(t)$ is the time-variant function
- $\omega$ is the angular frequency variable. Since fourier transform can be considered as the function for the position of the center of mass for the original function wrapped around a circle. 

Fourier transform has the inverse transform, as: $$g(t) = \mathscr{F}[G(\mathbf{i}\omega)] = \frac{1}{2 \pi} \int _{-\infty} ^\infty G(\mathbf{i} \omega) \exp (i \omega t)\, d\omega $$
Note that fourier transform have a crucial property, in which given some non-negative integer $n$ we have the following relationship: $$\mathscr{F}[d^n g(t)/dt^n]=(\mathbf{i} \omega)^n \mathscr{F}[g(t)]$$
And at the same time, the convolution between two functions get transformed into multiplication, as: $$\mathscr{F}[g(t) \star h(t)]= \mathscr{F}[g(t)] \mathscr F[h(t)]$$
where convolution is the following operation: $$g(t) \star h(t) = \int _{-\infty} ^\infty g(t-\tau) h(\tau)\, d\tau $$
