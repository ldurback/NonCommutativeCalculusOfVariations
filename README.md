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
