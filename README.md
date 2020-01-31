# NonCommutativeLagrangianMechanics

A Lagrangian Mechanics where we do not assume that x and dx commute.

## Assumptions

t, time, is a real number.  dt, the change in time, is a positive real number.

The system is progresses from a fixed initial state (the initial cause) to a fixed final state (the final cause, or goal state).

The system's dynamics stabilize the Action, S.

<a href="https://www.codecogs.com/eqnedit.php?latex=\delta&space;S&space;=&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\delta&space;S&space;=&space;0" title="\delta S = 0" /></a>

S is the integral from the initial state to the final state of L, the Lagrangian, over time.

<a href="https://www.codecogs.com/eqnedit.php?latex=S&space;=&space;\int_{init}^{final}&space;L&space;dt" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S&space;=&space;\int_{init}^{final}&space;L&space;dt" title="S = \int_{init}^{final} L dt" /></a>

L is a function of (x, dx, t, dt)

x and dx are elements of a (non-commutative) algebra.

Defining

<a href="https://www.codecogs.com/eqnedit.php?latex=\varepsilon&space;=&space;(x,t)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\varepsilon&space;=&space;(x,t)" title="\varepsilon = (x,t)" /></a>

and

<a href="https://www.codecogs.com/eqnedit.php?latex=F&space;=&space;\frac{\partial&space;L}{\partial&space;\varepsilon}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F&space;=&space;\frac{\partial&space;L}{\partial&space;\varepsilon}" title="F = \frac{\partial L}{\partial \varepsilon}" /></a>

Then

<a href="https://www.codecogs.com/eqnedit.php?latex=F&space;\to&space;0&space;\implies&space;\frac{dL}{dt}&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F&space;\to&space;0&space;\implies&space;\frac{dL}{dt}&space;\to&space;0" title="F \to 0 \implies \frac{dL}{dt} \to 0" /></a>

## Euler-Lagrange Equations

<a href="https://www.codecogs.com/eqnedit.php?latex=0&space;=&space;\delta&space;S&space;=&space;\delta&space;\int_i^f&space;L&space;dt&space;=&space;\int_i^f&space;\delta(Ldt)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?0&space;=&space;\delta&space;S&space;=&space;\delta&space;\int_i^f&space;L&space;dt&space;=&space;\int_i^f&space;\delta(Ldt)" title="0 = \delta S = \delta \int_i^f L dt = \int_i^f \delta(Ldt)" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=\int_i^f&space;\delta(Ldt)&space;=&space;\int_i^f&space;\frac{\partial&space;L&space;dt}{\partial&space;\varepsilon}&space;\cdot&space;\delta&space;\varepsilon&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}&space;\cdot&space;\delta&space;d&space;\varepsilon" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\int_i^f&space;\delta(Ldt)&space;=&space;\int_i^f&space;\frac{\partial&space;L&space;dt}{\partial&space;\varepsilon}&space;\cdot&space;\delta&space;\varepsilon&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}&space;\cdot&space;\delta&space;d&space;\varepsilon" title="\int_i^f \delta(Ldt) = \int_i^f \frac{\partial L dt}{\partial \varepsilon} \cdot \delta \varepsilon + \frac{\partial L dt}{\partial d \varepsilon} \cdot \delta d \varepsilon" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\int_i^f&space;\frac{\partial&space;L&space;dt}{\partial&space;\varepsilon}&space;\cdot&space;\delta&space;\varepsilon&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}&space;\cdot&space;d&space;\delta&space;\varepsilon" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\int_i^f&space;\frac{\partial&space;L&space;dt}{\partial&space;\varepsilon}&space;\cdot&space;\delta&space;\varepsilon&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}&space;\cdot&space;d&space;\delta&space;\varepsilon" title="= \int_i^f \frac{\partial L dt}{\partial \varepsilon} \cdot \delta \varepsilon + \frac{\partial L dt}{\partial d \varepsilon} \cdot d \delta \varepsilon" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\int_i^f&space;\frac{\partial&space;L&space;dt}{\partial&space;\varepsilon}&space;\cdot&space;\delta&space;\varepsilon&space;&plus;&space;[d(\frac{\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}&space;\cdot&space;\delta&space;\varepsilon)&space;-&space;d(\frac{\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon})&space;\cdot&space;\delta&space;\varepsilon]" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\int_i^f&space;\frac{\partial&space;L&space;dt}{\partial&space;\varepsilon}&space;\cdot&space;\delta&space;\varepsilon&space;&plus;&space;[d(\frac{\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}&space;\cdot&space;\delta&space;\varepsilon)&space;-&space;d(\frac{\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon})&space;\cdot&space;\delta&space;\varepsilon]" title="= \int_i^f \frac{\partial L dt}{\partial \varepsilon} \cdot \delta \varepsilon + [d(\frac{\partial L dt}{\partial d \varepsilon} \cdot \delta \varepsilon) - d(\frac{\partial L dt}{\partial d \varepsilon}) \cdot \delta \varepsilon]" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\int_i^f&space;[\frac{\partial&space;L&space;dt}{\partial&space;\varepsilon}&space;-&space;\frac{d&space;\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}]&space;\cdot&space;\delta&space;\varepsilon&space;&plus;&space;[\frac{\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}&space;\cdot&space;\delta&space;\varepsilon]_i^f" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\int_i^f&space;[\frac{\partial&space;L&space;dt}{\partial&space;\varepsilon}&space;-&space;\frac{d&space;\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}]&space;\cdot&space;\delta&space;\varepsilon&space;&plus;&space;[\frac{\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}&space;\cdot&space;\delta&space;\varepsilon]_i^f" title="= \int_i^f [\frac{\partial L dt}{\partial \varepsilon} - \frac{d \partial L dt}{\partial d \varepsilon}] \cdot \delta \varepsilon + [\frac{\partial L dt}{\partial d \varepsilon} \cdot \delta \varepsilon]_i^f" /></a>

Since the end points are not varied, the last term here is 0

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\int_i^f&space;[\frac{\partial&space;L&space;dt}{\partial&space;\varepsilon}&space;-&space;\frac{d&space;\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}]&space;\cdot&space;\delta&space;\varepsilon" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\int_i^f&space;[\frac{\partial&space;L&space;dt}{\partial&space;\varepsilon}&space;-&space;\frac{d&space;\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}]&space;\cdot&space;\delta&space;\varepsilon" title="= \int_i^f [\frac{\partial L dt}{\partial \varepsilon} - \frac{d \partial L dt}{\partial d \varepsilon}] \cdot \delta \varepsilon" /></a>

Noting that the variation is arbitrary gives us the Euler-Lagrange equation

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\partial&space;L&space;dt}{\partial&space;\varepsilon}&space;=&space;\frac{d&space;\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\partial&space;L&space;dt}{\partial&space;\varepsilon}&space;=&space;\frac{d&space;\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}" title="\frac{\partial L dt}{\partial \varepsilon} = \frac{d \partial L dt}{\partial d \varepsilon}" /></a>

which we can rewrite as

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\partial&space;L}{\partial&space;\varepsilon}&space;=&space;\frac{d}{dt}\frac{\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\partial&space;L}{\partial&space;\varepsilon}&space;=&space;\frac{d}{dt}\frac{\partial&space;L&space;dt}{\partial&space;d&space;\varepsilon}" title="\frac{\partial L}{\partial \varepsilon} = \frac{d}{dt}\frac{\partial L dt}{\partial d \varepsilon}" /></a>

## Force and Momentum

