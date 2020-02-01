# Non-Commutative Calculus of Variations

# Non-Commutative Lagrangian Mechanics

A generalization of Lagrangian Mechanics in which each particle has its own Action and where we do not assume that x and dx commute.

# Motivation: Stablizing Strategies of Non-Commutative (Galilean) Relativistic Game Theory

Each agent in a game theory has an initial state (initial cause), an endgoal state (final cause), a current state, and a Utility Function (life-review score), which scores the dynamics between the initial state and the current state.

The Stabilizing Strategies of a game theory have a final Utility Function (the Utility Function evaluated at the endgoal) which does not at all change when the strategy is infinitesimally perturbed.  This ensures that approximations to the strategies exists.

A Relativistic Game is one whose scores respect a form of relativity.  In the case of Galilean relativity, we have a universal time parameter and we can say that the Utility Function (life-review score), which scores the dynamics between the initial and current state, must be in the form of an integral over time of an Immediate Score.  Additionally, we can say that a game theory respects relativity when the Immediate Score is a constant when available no change in state is preferable.

A Non-Commutative Game is one in which the variables that appear in the Utility Function do not necessarily commute.  Since I am considering Galilean relativity, I will assume that time, t, is a real number, that change in time, dt, is a positive infinitesimal, and that the curvature of time, d^2t = 0.  I will also assume that x and dx are elements of an algebra and have a commutation relation.  I also assume that x is hermitian.

## Assumptions

t, time, is a real number.  dt, the change in time, is a positive real number.  d^2 t = 0.

For each object/agent i:  x_i and dx_i are elements of a non-commutative algebra.  x_i and x_j commute.  dx_i and dx_j commute.  x_i and dx_j commute only if x != j.

Let x = (x_1, ..., x_n) where n is the number of objects/agents in the system.

Let z = (x,t) be the state of the system

Let z_i = (x_i, t) be the state of agent_i.

The system progresses from an fixed initial state (the initial cause) to a fixed final state (the final cause, or goal state).

Let S_i(z) be agent_i's Utility Function

The agent_i's stategy stabilizes S_i(z_final).

<a href="https://www.codecogs.com/eqnedit.php?latex=\delta_i&space;S_i(z_{final})&space;=&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\delta_i&space;S_i(z_{final})&space;=&space;0" title="\delta_i S_i(z_{final}) = 0" /></a>

S_i(z) is the integral from the initial state to the final state of L_i(x, t, dx/dt), agent_i's Immediate Score, or agent_i's Lagrangian, over time.

<a href="https://www.codecogs.com/eqnedit.php?latex=S_i(z)&space;=&space;\int_{z_{init}}^{z}&space;L_i(x,t,\frac{dx}{dt})&space;dt" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S_i(z)&space;=&space;\int_{z_{init}}^{z}&space;L_i(x,t,\frac{dx}{dt})&space;dt" title="S_i(z) = \int_{z_{init}}^{z} L_i(x,t,\frac{dx}{dt}) dt" /></a>

Defining

<a href="https://www.codecogs.com/eqnedit.php?latex=F_i&space;=&space;\frac{\partial&space;L_i}{\partial&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F_i&space;=&space;\frac{\partial&space;L_i}{\partial&space;z}" title="F_i = \frac{\partial L_i}{\partial z}" /></a>

Then

<a href="https://www.codecogs.com/eqnedit.php?latex=F_i&space;\to&space;0&space;\implies&space;\frac{dL_i}{dt}&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F_i&space;\to&space;0&space;\implies&space;\frac{dL_i}{dt}&space;\to&space;0" title="F_i \to 0 \implies \frac{dL_i}{dt} \to 0" /></a>

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

## The Form of the Kinetic Energy and x-Momentum

According to our assumptions, in the event that F -> 0, we have that dL/dt = d^2S/dt^2 -> 0.

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{dL}{dt}&space;=&space;\frac{d}{dt}&space;(p&space;\cdot&space;\frac{dz}{dt})&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{dL}{dt}&space;=&space;\frac{d}{dt}&space;(p&space;\cdot&space;\frac{dz}{dt})&space;\to&space;0" title="\frac{dL}{dt} = \frac{d}{dt} (p \cdot \frac{dz}{dt}) \to 0" /></a>

Since as F = dp/dt, we have that dp/dt -> 0, so

<a href="https://www.codecogs.com/eqnedit.php?latex=p&space;\cdot&space;\frac{d^2&space;z}{dt^2}&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p&space;\cdot&space;\frac{d^2&space;z}{dt^2}&space;\to&space;0" title="p \cdot \frac{d^2 z}{dt^2} \to 0" /></a>

Note that z = (x,t), and name p = (p_x, p_t).  Also note that d^2 t = 0.

<a href="https://www.codecogs.com/eqnedit.php?latex=p_x&space;\cdot&space;\frac{d^2&space;x}{dt^2}&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p_x&space;\cdot&space;\frac{d^2&space;x}{dt^2}&space;\to&space;0" title="p_x \cdot \frac{d^2 x}{dt^2} \to 0" /></a>

Since p_x is arbitrary, we have

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{d^2&space;x}{dt^2}&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{d^2&space;x}{dt^2}&space;\to&space;0" title="\frac{d^2 x}{dt^2} \to 0" /></a>

The only Lagrangian consistent with d^2x/dt^2 = 0 is L = k (dx/dt)^2 for some proportionality constant k.  Defining m as 2k, we get that as F -> 0

<a href="https://www.codecogs.com/eqnedit.php?latex=L&space;\to&space;\frac{1}{2}&space;m&space;\frac{dx^2}{dt^2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L&space;\to&space;\frac{1}{2}&space;m&space;\frac{dx^2}{dt^2}" title="L \to \frac{1}{2} m \frac{dx^2}{dt^2}" /></a>

Note

<a href="https://www.codecogs.com/eqnedit.php?latex=p_x&space;=&space;\frac{\partial&space;L&space;dt}{\partial&space;dx}&space;=&space;\frac{\partial&space;L}{\partial&space;\frac{dx}{dt}}&space;\to&space;m&space;\frac{dx}{dt}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p_x&space;=&space;\frac{\partial&space;L&space;dt}{\partial&space;dx}&space;=&space;\frac{\partial&space;L}{\partial&space;\frac{dx}{dt}}&space;\to&space;m&space;\frac{dx}{dt}" title="p_x = \frac{\partial L dt}{\partial dx} = \frac{\partial L}{\partial \frac{dx}{dt}} \to m \frac{dx}{dt}" /></a>

Since p_x is independent of F, we get that regardless of F

<a href="https://www.codecogs.com/eqnedit.php?latex=p_x&space;=&space;\frac{\partial&space;L}{\partial&space;\frac{dx}{dt}}=&space;m&space;\frac{dx}{dt}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p_x&space;=&space;\frac{\partial&space;L}{\partial&space;\frac{dx}{dt}}=&space;m&space;\frac{dx}{dt}" title="p_x = \frac{\partial L}{\partial \frac{dx}{dt}}= m \frac{dx}{dt}" /></a>

Thus, we get

<a href="https://www.codecogs.com/eqnedit.php?latex=L&space;=&space;\frac{1}{2}m\frac{dx^2}{dt^2}&space;-&space;V(x,t)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L&space;=&space;\frac{1}{2}m\frac{dx^2}{dt^2}&space;-&space;V(x,t)" title="L = \frac{1}{2}m\frac{dx^2}{dt^2} - V(x,t)" /></a>

Where V(x,t) is arbitrary.


## The relationship between x and dx as well as z and p

Define

<a href="https://www.codecogs.com/eqnedit.php?latex=\phi=e^{\frac{S}{-i&space;\hbar}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\phi=e^{\frac{S}{-i&space;\hbar}}" title="\phi=e^{\frac{S}{-i \hbar}}" /></a>

Then, taking the differential, we get

<a href="https://www.codecogs.com/eqnedit.php?latex=-i&space;\hbar&space;d&space;\phi=dS&space;\phi=(p&space;\cdot&space;dz)\phi" target="_blank"><img src="https://latex.codecogs.com/gif.latex?-i&space;\hbar&space;d&space;\phi=dS&space;\phi=(p&space;\cdot&space;dz)\phi" title="-i \hbar d \phi=dS \phi=(p \cdot dz)\phi" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=-i&space;\hbar&space;\frac{\partial}{\partial&space;z}&space;\phi=&space;p\phi" target="_blank"><img src="https://latex.codecogs.com/gif.latex?-i&space;\hbar&space;\frac{\partial}{\partial&space;z}&space;\phi=&space;p\phi" title="-i \hbar \frac{\partial}{\partial z} \phi= p\phi" /></a>

Since p is a function of z and dz and the commutation relationship between z and dz is formulaic, we get

<a href="https://www.codecogs.com/eqnedit.php?latex=p&space;=&space;-i\hbar&space;\frac{\partial}{\partial&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p&space;=&space;-i\hbar&space;\frac{\partial}{\partial&space;z}" title="p = -i\hbar \frac{\partial}{\partial z}" /></a>

Noting that p_x = m (dx/dt)

<a href="https://www.codecogs.com/eqnedit.php?latex=d&space;x&space;=&space;-i\frac{\hbar}{m}dt&space;\frac{\partial}{\partial&space;x}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?d&space;x&space;=&space;-i\frac{\hbar}{m}dt&space;\frac{\partial}{\partial&space;x}" title="d x = -i\frac{\hbar}{m}dt \frac{\partial}{\partial x}" /></a>

Since we assumed as the beginning that x and dx are hermitian, we get that hbar and m are real.

Since dx is also a generator of translations, we also get that hbar and m are positive.
