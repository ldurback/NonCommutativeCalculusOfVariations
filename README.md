# NonCommutativeLagrangianMechanics

A Lagrangian Mechanics where we do not assume that x and dx commute.

## Assumptions

t, time, is a real number.  dt, the change in time, is a positive real number.  d^2 t = 0.

The system is progresses from a fixed initial state (the initial cause) to a fixed final state (the final cause, or goal state).

The system's dynamics stabilize the Action, S.

<a href="https://www.codecogs.com/eqnedit.php?latex=\delta&space;S&space;=&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\delta&space;S&space;=&space;0" title="\delta S = 0" /></a>

S is the integral from the initial state to the final state of L, the Lagrangian, over time.

<a href="https://www.codecogs.com/eqnedit.php?latex=S&space;=&space;\int_{init}^{final}&space;L&space;dt" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S&space;=&space;\int_{init}^{final}&space;L&space;dt" title="S = \int_{init}^{final} L dt" /></a>

L is a function of (x, dx, t, dt)

x and dx are elements of a (non-commutative) algebra and have a commutation relation.

Defining

<a href="https://www.codecogs.com/eqnedit.php?latex=z&space;=&space;(x,t)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?z&space;=&space;(x,t)" title="z = (x,t)" /></a>

and

<a href="https://www.codecogs.com/eqnedit.php?latex=F&space;=&space;\frac{\partial&space;L}{\partial&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F&space;=&space;\frac{\partial&space;L}{\partial&space;z}" title="F = \frac{\partial L}{\partial z}" /></a>

Then

<a href="https://www.codecogs.com/eqnedit.php?latex=F&space;\to&space;0&space;\implies&space;\frac{dL}{dt}&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F&space;\to&space;0&space;\implies&space;\frac{dL}{dt}&space;\to&space;0" title="F \to 0 \implies \frac{dL}{dt} \to 0" /></a>

## Euler-Lagrange Equations

<a href="https://www.codecogs.com/eqnedit.php?latex=0&space;=&space;\delta&space;S&space;=&space;\delta&space;\int_i^f&space;L&space;dt&space;=&space;\int_i^f&space;\delta(Ldt)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?0&space;=&space;\delta&space;S&space;=&space;\delta&space;\int_i^f&space;L&space;dt&space;=&space;\int_i^f&space;\delta(Ldt)" title="0 = \delta S = \delta \int_i^f L dt = \int_i^f \delta(Ldt)" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=\int_i^f&space;\delta(Ldt)&space;=&space;\int_i^f&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;\delta&space;z&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;\delta&space;d&space;z" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\int_i^f&space;\delta(Ldt)&space;=&space;\int_i^f&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;\delta&space;z&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;\delta&space;d&space;z" title="\int_i^f \delta(Ldt) = \int_i^f \frac{\partial L dt}{\partial z} \cdot \delta z + \frac{\partial L dt}{\partial d z} \cdot \delta d z" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\int_i^f&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;\delta&space;z&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;d&space;\delta&space;z" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\int_i^f&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;\delta&space;z&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;d&space;\delta&space;z" title="= \int_i^f \frac{\partial L dt}{\partial z} \cdot \delta z + \frac{\partial L dt}{\partial d z} \cdot d \delta z" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\int_i^f&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;\delta&space;z&space;&plus;&space;[d(\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;\delta&space;z)&space;-&space;d(\frac{\partial&space;L&space;dt}{\partial&space;d&space;z})&space;\cdot&space;\delta&space;z]" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\int_i^f&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;\delta&space;z&space;&plus;&space;[d(\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;\delta&space;z)&space;-&space;d(\frac{\partial&space;L&space;dt}{\partial&space;d&space;z})&space;\cdot&space;\delta&space;z]" title="= \int_i^f \frac{\partial L dt}{\partial z} \cdot \delta z + [d(\frac{\partial L dt}{\partial d z} \cdot \delta z) - d(\frac{\partial L dt}{\partial d z}) \cdot \delta z]" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\int_i^f&space;[\frac{\partial&space;L&space;dt}{\partial&space;z}&space;-&space;\frac{d&space;\partial&space;L&space;dt}{\partial&space;d&space;z}]&space;\cdot&space;\delta&space;z&space;&plus;&space;[\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;\delta&space;z]_i^f" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\int_i^f&space;[\frac{\partial&space;L&space;dt}{\partial&space;z}&space;-&space;\frac{d&space;\partial&space;L&space;dt}{\partial&space;d&space;z}]&space;\cdot&space;\delta&space;z&space;&plus;&space;[\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;\delta&space;z]_i^f" title="= \int_i^f [\frac{\partial L dt}{\partial z} - \frac{d \partial L dt}{\partial d z}] \cdot \delta z + [\frac{\partial L dt}{\partial d z} \cdot \delta z]_i^f" /></a>

Since the end points are not varied, the last term here is 0

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\int_i^f&space;[\frac{\partial&space;L&space;dt}{\partial&space;z}&space;-&space;\frac{d&space;\partial&space;L&space;dt}{\partial&space;d&space;z}]&space;\cdot&space;\delta&space;z" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\int_i^f&space;[\frac{\partial&space;L&space;dt}{\partial&space;z}&space;-&space;\frac{d&space;\partial&space;L&space;dt}{\partial&space;d&space;z}]&space;\cdot&space;\delta&space;z" title="= \int_i^f [\frac{\partial L dt}{\partial z} - \frac{d \partial L dt}{\partial d z}] \cdot \delta z" /></a>

Noting that the variation is arbitrary gives us the Euler-Lagrange equation

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\partial&space;L&space;dt}{\partial&space;z}&space;=&space;\frac{d&space;\partial&space;L&space;dt}{\partial&space;d&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\partial&space;L&space;dt}{\partial&space;z}&space;=&space;\frac{d&space;\partial&space;L&space;dt}{\partial&space;d&space;z}" title="\frac{\partial L dt}{\partial z} = \frac{d \partial L dt}{\partial d z}" /></a>

which we can rewrite as

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\partial&space;L}{\partial&space;z}&space;=&space;\frac{d}{dt}\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\partial&space;L}{\partial&space;z}&space;=&space;\frac{d}{dt}\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}" title="\frac{\partial L}{\partial z} = \frac{d}{dt}\frac{\partial L dt}{\partial d z}" /></a>

## Force and Momentum

Definition of Force

<a href="https://www.codecogs.com/eqnedit.php?latex=F&space;:=&space;\frac{\partial&space;L}{\partial&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F&space;:=&space;\frac{\partial&space;L}{\partial&space;z}" title="F := \frac{\partial L}{\partial z}" /></a>

Definition of Momentum

<a href="https://www.codecogs.com/eqnedit.php?latex=p&space;:=&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p&space;:=&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}" title="p := \frac{\partial L dt}{\partial d z}" /></a>

The Euler-Lagrange Equation then reads

<a href="https://www.codecogs.com/eqnedit.php?latex=F&space;=&space;\frac{d}{dt}&space;p" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F&space;=&space;\frac{d}{dt}&space;p" title="F = \frac{d}{dt} p" /></a>

## Alternate form of the Lagrangian

<a href="https://www.codecogs.com/eqnedit.php?latex=d^2&space;S&space;=&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;d&space;z&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;d^2&space;z&space;=&space;dp&space;\cdot&space;dz&space;&plus;&space;p&space;\cdot&space;d^2&space;z&space;=&space;d(p&space;\cdot&space;d&space;z)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?d^2&space;S&space;=&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;d&space;z&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;d^2&space;z&space;=&space;dp&space;\cdot&space;dz&space;&plus;&space;p&space;\cdot&space;d^2&space;z&space;=&space;d(p&space;\cdot&space;d&space;z)" title="d^2 S = \frac{\partial L dt}{\partial z} \cdot d z + \frac{\partial L dt}{\partial d z} \cdot d^2 z = dp \cdot dz + p \cdot d^2 z = d(p \cdot d z)" /></a>


<a href="https://www.codecogs.com/eqnedit.php?latex=dS&space;=&space;L&space;dt&space;=&space;p&space;\cdot&space;dz" target="_blank"><img src="https://latex.codecogs.com/gif.latex?dS&space;=&space;L&space;dt&space;=&space;p&space;\cdot&space;dz" title="dS = L dt = p \cdot dz" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=L&space;=&space;p&space;\cdot&space;\frac{dz}{dt}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L&space;=&space;p&space;\cdot&space;\frac{dz}{dt}" title="L = p \cdot \frac{dz}{dt}" /></a>

## The Form of the Kinetic Energy and x-Momentum (to do)

According to our assumptions, in the event that F -> 0, we have that dL/dt = d^2S/dt^2 -> 0.

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{dL}{dt}&space;=&space;\frac{d}{dt}&space;(p&space;\cdot&space;\frac{dz}{dt})&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{dL}{dt}&space;=&space;\frac{d}{dt}&space;(p&space;\cdot&space;\frac{dz}{dt})&space;\to&space;0" title="\frac{dL}{dt} = \frac{d}{dt} (p \cdot \frac{dz}{dt}) \to 0" /></a>

Since as F = dp/dt, we have that dp/dt -> 0, so

<a href="https://www.codecogs.com/eqnedit.php?latex=p&space;\cdot&space;\frac{d^2&space;z}{dt^2}&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p&space;\cdot&space;\frac{d^2&space;z}{dt^2}&space;\to&space;0" title="p \cdot \frac{d^2 z}{dt^2} \to 0" /></a>

Note that z = (x,t), and name p = (p_x, p_t).  Also note that d^2 t = 0.

<a href="https://www.codecogs.com/eqnedit.php?latex=p_x&space;\cdot&space;\frac{d^2&space;x}{dt^2}&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p_x&space;\cdot&space;\frac{d^2&space;x}{dt^2}&space;\to&space;0" title="p_x \cdot \frac{d^2 x}{dt^2} \to 0" /></a>

Since p_x is arbitrary, we have

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{d^2&space;x}{dt^2}&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{d^2&space;x}{dt^2}&space;\to&space;0" title="\frac{d^2 x}{dt^2} \to 0" /></a>


## The relationship between z and dz

Define

<a href="https://www.codecogs.com/eqnedit.php?latex=\phi=e^{\frac{S}{-i&space;\hbar}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\phi=e^{\frac{S}{-i&space;\hbar}}" title="\phi=e^{\frac{S}{-i \hbar}}" /></a>

Then, taking the differential, we get

<a href="https://www.codecogs.com/eqnedit.php?latex=-i&space;\hbar&space;d&space;\phi=dS&space;\phi=(p&space;\cdot&space;dz)\phi" target="_blank"><img src="https://latex.codecogs.com/gif.latex?-i&space;\hbar&space;d&space;\phi=dS&space;\phi=(p&space;\cdot&space;dz)\phi" title="-i \hbar d \phi=dS \phi=(p \cdot dz)\phi" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=-i&space;\hbar&space;\frac{\partial}{\partial&space;z}&space;\phi=&space;p\phi" target="_blank"><img src="https://latex.codecogs.com/gif.latex?-i&space;\hbar&space;\frac{\partial}{\partial&space;z}&space;\phi=&space;p\phi" title="-i \hbar \frac{\partial}{\partial z} \phi= p\phi" /></a>

Since p is a function of z and dz and the commutation relationship between z and dz is formulaic, we get

<a href="https://www.codecogs.com/eqnedit.php?latex=p&space;=&space;-i\hbar&space;\frac{\partial}{\partial&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p&space;=&space;-i\hbar&space;\frac{\partial}{\partial&space;z}" title="p = -i\hbar \frac{\partial}{\partial z}" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=d&space;z&space;=&space;-i\frac{\hbar}{m}dt&space;\frac{\partial}{\partial&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?d&space;z&space;=&space;-i\frac{\hbar}{m}dt&space;\frac{\partial}{\partial&space;z}" title="d z = -i\frac{\hbar}{m}dt \frac{\partial}{\partial z}" /></a>

Since we assumed as the beginning that z and dz are hermitian, we get that hbar and m are real.

Since dz is also a generator of translations, we also get that hbar and m are positive.
