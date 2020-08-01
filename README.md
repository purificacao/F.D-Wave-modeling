# F.D-Wave-modeling
This is just a tiny project presenting a wave modeling animation.

\begin{equation}
\frac{\partial^2 u}{\partial t^2} = c^{2}\left ( \frac{\partial^2 u}{\partial x^2} +\frac{\partial^2 u}{\partial y^2} \right )
\end{equation}

where $t$ is the time, $u$ is the displacement, $c$ is the wave propagation velocity through the medium, x and y are Cartesian coordinates. The program below shows the waves propagation in a two-dimensional domain, through the numerical solution of the wave equation. The __Finite Difference Method__ in two dimensions with transient term will be used. The domain will be a square with dimensions of 1 m x 1 m, so that: its discretization will be given with:
  

• $dt << 0,01s$ 
 \
 \
e a variável $u$ será definida no contorno como: \
• $u(x=0) = sen(10*t)*sen(y*π)$; \
• $u(x=1) = 0$; \
• $u(y=0) = 0$; \
• $u(y=1) = 0$; 
