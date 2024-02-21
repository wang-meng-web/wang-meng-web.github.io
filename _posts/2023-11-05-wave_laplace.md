---
title: 'Solve Wave Equation by Laplace Transform'
date: 2023-11-05
permalink: /posts/2023-11-05-wave_laplace/

---

Reference: Wave Motion in Elastic Solid, Karl F. Graff.  

$$
T\frac{\partial^2y}{\partial x^2}-\rho\frac{\partial^2y}{\partial t^2}=-q(x,t)
$$  


Solution by Laplace transform  


Consider the case of a harmonically varying force acting at a single point $x=\xi$  


$$
q(x,t)=P\delta(x-\xi) e^{-i\omega t}
$$  


$$
\frac{\partial^2 y}{\partial x^2}-\frac{1}{c_0^2}\frac{\partial^2 y}{\partial t^2}=\delta(x-\xi) e^{-i\omega t}
$$  


where P=-T has again been selected. Let $y(x,t)=\phi(x) e^{-i\omega t}$ so that  


$$
\phi''(x)+\beta^2\phi(x)=\delta(x-\xi) e^{-i\omega t}
$$
