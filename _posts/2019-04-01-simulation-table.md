---
layout: post
title: "Just some testing page"
date: 2019-04-01
---
## Testing page
### Channel gradient
$$
\begin{align*}
\nabla_{x,y} p(x,y,v_0,\Delta v) = \int dz \int_{v_0 - \Delta v/2}^{v_0 + \Delta v/2} d^3 vW(v) \nabla_{x,y}\left[{\color{blue} \rho(x,y,z)}e^{-\frac{m(v-{\color{red} v_{turb}(x,y,z)})^2}{2k_B{\color{blue} T(x,y,z)}}}\right]
\end{align*}
$$
\begin{align*}
In Fourier space, writing $X=(x,y)$
\end{align*}
$$
\begin{align*}
\mathcal{F}_{X}\{\nabla_{X} p(X,v_0,\Delta v)\}  = \int dz \int_{v_0 - \Delta v/2}^{v_0 + \Delta v/2} d^3 vW(v) \int d^2 K e^{iK\cdot X} {\color{red}iK} \left[ \rho(x,y,z)e^{-\frac{m(v- v_{turb}(x,y,z))^2}{2k_BT(x,y,z)}}\right]
\end{align*}
$$
What is a spectrum?
$$
\begin{align*}
P[p] &= \oint d^2K|\mathcal{F}_{X}\{\nabla_{X} p(X,v_0,\Delta v)\} |^2 = 2\pi K |\mathcal{F}_{X}\{\nabla_{X} p(X,v_0,\Delta v)\} |^2\\
&\sim 2\pi K{\color{red} K^2} |\mathcal{F}_{X}\{p(X,v_0,\Delta v)\} |^2
\end{align*}
$$
- Q1: USM-ed channel channal map <-> any correlation with original spectrum?
  USM : What spectrum?
- Q2: Spectrum relation between Thermal broadening <-> No Thermal broadening ?