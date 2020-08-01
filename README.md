# F.D-Wave-modeling
This is just a tiny project presenting a wave modeling animation.

![image](https://user-images.githubusercontent.com/32949538/89110093-965c6880-d41d-11ea-827c-cb7279c30380.png)

where _t_ is the time, _u_ is the displacement, _c_ is the wave propagation velocity through the medium, _x_ and _y_ are Cartesian coordinates. The program below shows the waves propagation in a two-dimensional domain, through the numerical solution of the wave equation. The __Finite Difference Method__ in two dimensions with transient term will be used. The domain will be a square with dimensions of 1 m x 1 m, so that, its discretization will be given with:
  

• _dt << 0,01s
 \
 \
e a variável _u_ será definida no contorno como: \
• _u(x=0) = sen(10*t)*sen(y*π)$; \
• _u(x=1) = 0; \
• _u(y=0) = 0; \
• _u(y=1) = 0; 
