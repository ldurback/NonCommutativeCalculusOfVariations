# Non-Commutative Calculus of Variations

# Non-Commutative Lagrangian Mechanics

A generalization of Lagrangian Mechanics to a probabilistic mechanics via not assuming that x and dx commute and using

<a href="https://www.codecogs.com/eqnedit.php?latex=\delta&space;ExpectationValue(S)&space;=&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\delta&space;ExpectationValue(S)&space;=&space;0" title="\delta ExpectationValue(S) = 0" /></a>

Perhaps the equations of quantum mechanics follow?

There is currently one place where *MAGIC* happens (i.e. one spot in the argument that is very poorly justified).

# Motivation: Stablizing Strategies of Non-Commutative (Cooperative, Galilean) Relativistic Game Theory

Note:  I will be concentrating on Cooperative Game Theory, in which each agent in the game has the same Utility Function (Accumulated Score) so that the whole system is scored together because it is the easiest path I found to quantum mechanics.  In general, this theory can be generalized to Non-cooperative Game Theory, where each agent has its own Utility Function as well as its own Immediate Score.  I did not concentrate on non-cooperative game theory because I could not find any argument from it that p = m(dx/dt).

The total system in a cooperative game theory has an initial state (initial cause), an endgoal state (final cause), a current state, and a Utility Function (Accumulated Score), which scores the dynamics between the initial state and the current state.

The Stabilizing Strategies of a game theory have a final expected Utility Function (the expected value of the Utility Function evaluated at the endgoal) which does not at all change when the strategy is infinitesimally perturbed.  This ensures that approximations to the strategies exists.

A Relativistic Game is one whose scores respect a form of relativity.  In the case of Galilean relativity, we have a universal time parameter and we can say that the Utility Function (Accumulated Score), which scores the dynamics between the initial and current state, must be in the form of an integral over time of an Immediate Score.  Additionally, we can say that a game theory respects relativity when the Immediate Score is a constant when no available change in state is preferable.

A Non-Commutative Game is one in which the variables that appear in the Utility Function do not necessarily commute.  Since I am considering Galilean relativity, I will assume that time, t, is real, that change in time, dt, is a positive real infinitesimal, and that the curvature of time, d^2t = 0.  I will also assume that position, x, is hermitian and that dx and d^2 x exist. Furthermore, commutation relations between all variables exist.  I also assume that S(x,t), the Utility Function, and L(x,(dx/dt),t), the Immediate Score, both commute and have derivatives. 

## Assumptions

x is hermitian.  t, dt are real  d^2 t = 0.

Commutation relations exist between x, dx, and d^2x.

x, and all its differentials, commute with t, and all its differentials.

Let z = (x,t) be the state of the system

The system progresses from an fixed initial state (the initial cause) to a fixed final state (the final cause, or goal state).

Let S(z) be the system's Utility Function

Let <a href="https://www.codecogs.com/eqnedit.php?latex=|\psi\rangle" target="_blank"><img src="https://latex.codecogs.com/gif.latex?|\psi\rangle" title="|\psi\rangle" /></a> be a normalized Heisenberg picture (not varried or dynamic) wavefunction for the system

Assume

<a href="https://www.codecogs.com/eqnedit.php?latex=ExpectationValue(S(z))&space;=&space;\langle&space;\psi|S|\psi\rangle" target="_blank"><img src="https://latex.codecogs.com/gif.latex?ExpectationValue(S(z))&space;=&space;\langle&space;\psi|S|\psi\rangle" title="ExpectationValue(S(z)) = \langle \psi|S|\psi\rangle" /></a>

The stategies of all agents stabilizes the expectation value of S(z_final).

<a href="https://www.codecogs.com/eqnedit.php?latex=0&space;=&space;\delta&space;\langle&space;\psi|&space;S(z_{final})&space;|&space;\psi&space;\rangle&space;=&space;\langle&space;\psi&space;|&space;\delta&space;S(z_{final})&space;|&space;\psi&space;\rangle" target="_blank"><img src="https://latex.codecogs.com/gif.latex?0&space;=&space;\delta&space;\langle&space;\psi|&space;S(z_{final})&space;|&space;\psi&space;\rangle&space;=&space;\langle&space;\psi&space;|&space;\delta&space;S(z_{final})&space;|&space;\psi&space;\rangle" title="0 = \delta \langle \psi| S(z_{final}) | \psi \rangle = \langle \psi | \delta S(z_{final}) | \psi \rangle" /></a>

Abstracting away the wavefunction

<a href="https://www.codecogs.com/eqnedit.php?latex=\delta&space;S(z_{final})&space;=&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\delta&space;S(z_{final})&space;=&space;0" title="\delta S(z_{final}) = 0" /></a>

S(z) is the integral from the initial state to the final state of L(x, t, dx/dt), the Immediate Score, or Lagrangian, over time.

<a href="https://www.codecogs.com/eqnedit.php?latex=S(z)&space;=&space;\int_{z_{init}}^{z}&space;L(x,t,\frac{dx}{dt})&space;dt" target="_blank"><img src="https://latex.codecogs.com/gif.latex?S(z)&space;=&space;\int_{z_{init}}^{z}&space;L(x,t,\frac{dx}{dt})&space;dt" title="S(z) = \int_{z_{init}}^{z} L(x,t,\frac{dx}{dt}) dt" /></a>

Assume that L and S commute and have derivatives.

Defining

<a href="https://www.codecogs.com/eqnedit.php?latex=F&space;=&space;\frac{\partial&space;L}{\partial&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F&space;=&space;\frac{\partial&space;L}{\partial&space;z}" title="F = \frac{\partial L}{\partial z}" /></a>

Then F, being the gradient of the Immediate Score with respect to state, is 0 when no change in state is preferable.  Our assumption is that as F->0, L approaches a constant.

<a href="https://www.codecogs.com/eqnedit.php?latex=F&space;\to&space;0&space;\implies&space;\frac{dL}{dt}&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F&space;\to&space;0&space;\implies&space;\frac{dL}{dt}&space;\to&space;0" title="F \to 0 \implies \frac{dL}{dt} \to 0" /></a>

## Euler-Lagrange Equations

Since we assumed that L and S have derivatives.

<a href="https://www.codecogs.com/eqnedit.php?latex=0&space;=&space;\delta&space;S(z_{final})&space;=&space;\delta&space;\int_{z_{init}}^{z_{final}}&space;L&space;dt&space;=&space;\int_{z_{init}}^{z_{final}}&space;\delta(Ldt)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?0&space;=&space;\delta&space;S(z_{final})&space;=&space;\delta&space;\int_{z_{init}}^{z_{final}}&space;L&space;dt&space;=&space;\int_{z_{init}}^{z_{final}}&space;\delta(Ldt)" title="0 = \delta S(z_{final}) = \delta \int_{z_{init}}^{z_{final}} L dt = \int_{z_{init}}^{z_{final}} \delta(Ldt)" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=\int_{z_{init}}^{z_{final}}&space;\delta(L&space;dt)&space;=&space;\int_{z_{init}}^{z_{final}}&space;\frac{\partial&space;L&space;\cdot&space;dt}{\partial&space;z}&space;\cdot&space;\delta&space;z&space;&plus;&space;\frac{\partial&space;L&space;\cdot&space;dt}{\partial&space;dz}&space;\cdot&space;\delta&space;dz" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\int_{z_{init}}^{z_{final}}&space;\delta(L&space;dt)&space;=&space;\int_{z_{init}}^{z_{final}}&space;\frac{\partial&space;L&space;\cdot&space;dt}{\partial&space;z}&space;\cdot&space;\delta&space;z&space;&plus;&space;\frac{\partial&space;L&space;\cdot&space;dt}{\partial&space;dz}&space;\cdot&space;\delta&space;dz" title="\int_{z_{init}}^{z_{final}} \delta(L dt) = \int_{z_{init}}^{z_{final}} \frac{\partial L \cdot dt}{\partial z} \cdot \delta z + \frac{\partial L \cdot dt}{\partial dz} \cdot \delta dz" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\int_{z_{init}}^{z_{final}}&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;\delta&space;z&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;dz}&space;\cdot&space;d&space;\delta&space;z" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\int_{z_{init}}^{z_{final}}&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;\delta&space;z&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;dz}&space;\cdot&space;d&space;\delta&space;z" title="= \int_{z_{init}}^{z_{final}} \frac{\partial L dt}{\partial z} \cdot \delta z + \frac{\partial L dt}{\partial dz} \cdot d \delta z" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\int_{z_{init}}^{z_{final}}&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;\delta&space;z&space;&plus;&space;d(\frac{\partial&space;L&space;dt}{\partial&space;dz}&space;\cdot&space;\delta&space;z)&space;-&space;d(\frac{\partial&space;L&space;dt}{\partial&space;d&space;z})&space;\cdot&space;\delta&space;z" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\int_{z_{init}}^{z_{final}}&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;\delta&space;z&space;&plus;&space;d(\frac{\partial&space;L&space;dt}{\partial&space;dz}&space;\cdot&space;\delta&space;z)&space;-&space;d(\frac{\partial&space;L&space;dt}{\partial&space;d&space;z})&space;\cdot&space;\delta&space;z" title="= \int_{z_{init}}^{z_{final}} \frac{\partial L dt}{\partial z} \cdot \delta z + d(\frac{\partial L dt}{\partial dz} \cdot \delta z) - d(\frac{\partial L dt}{\partial d z}) \cdot \delta z" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\int_{z_{init}}^{z_{final}}&space;[\frac{\partial&space;L&space;dt}{\partial&space;z}&space;-&space;d\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}]&space;\cdot&space;\delta&space;z&space;&plus;&space;[\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;\delta&space;z]_{z_{init}}^{z_{final}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\int_{z_{init}}^{z_{final}}&space;[\frac{\partial&space;L&space;dt}{\partial&space;z}&space;-&space;d\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}]&space;\cdot&space;\delta&space;z&space;&plus;&space;[\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;\delta&space;z]_{z_{init}}^{z_{final}}" title="= \int_{z_{init}}^{z_{final}} [\frac{\partial L dt}{\partial z} - d\frac{\partial L dt}{\partial d z}] \cdot \delta z + [\frac{\partial L dt}{\partial d z} \cdot \delta z]_{z_{init}}^{z_{final}}" /></a>

Since the end points are not varied, the last term here is 0

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;\int_{z_{init}}^{z_{final}}&space;[\frac{\partial&space;L&space;dt}{\partial&space;z}&space;-&space;d&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}]&space;\cdot&space;\delta&space;z" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;\int_{z_{init}}^{z_{final}}&space;[\frac{\partial&space;L&space;dt}{\partial&space;z}&space;-&space;d&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}]&space;\cdot&space;\delta&space;z" title="= \int_{z_{init}}^{z_{final}} [\frac{\partial L dt}{\partial z} - d \frac{\partial L dt}{\partial d z}] \cdot \delta z" /></a>

Noting that the variation is arbitrary gives us the Euler-Lagrange equation

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\partial&space;L&space;dt}{\partial&space;z}&space;=&space;d\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\partial&space;L&space;dt}{\partial&space;z}&space;=&space;d\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}" title="\frac{\partial L dt}{\partial z} = d\frac{\partial L dt}{\partial d z}" /></a>

which we can rewrite as

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\partial&space;L}{\partial&space;z}&space;=&space;\frac{d}{dt}\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\partial&space;L}{\partial&space;z}&space;=&space;\frac{d}{dt}\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}" title="\frac{\partial L}{\partial z} = \frac{d}{dt}\frac{\partial L dt}{\partial d z}" /></a>

## Force and Momentum

Note: dz is the Change of State, or the Motion.  dS = Ldt is the Change in Accumulated Score, or the Additional Score.  d^2 S = dL dt is the change in the Additional Score, or the Profit.  d^2S/dt = dL, the change in immediate score, is the rate of profit.

Definition of Force

<a href="https://www.codecogs.com/eqnedit.php?latex=F&space;:=&space;\frac{\partial&space;L}{\partial&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F&space;:=&space;\frac{\partial&space;L}{\partial&space;z}" title="F := \frac{\partial L}{\partial z}" /></a>

The Force measures the Gradient of the Immediate Score with respect to State.  The force gives you the direction that state can be changed to most improve the Immediate Score and the rate of this improvement.  Though it is simply called the "force", it is "rate of profit of channging state"

Definition of Momentum

<a href="https://www.codecogs.com/eqnedit.php?latex=p&space;:=&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p&space;:=&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}" title="p := \frac{\partial L dt}{\partial d z}" /></a>

Since <a href="https://www.codecogs.com/eqnedit.php?latex=p&space;=&space;\frac{\partial&space;dS}{\partial&space;dz}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p&space;=&space;\frac{\partial&space;dS}{\partial&space;dz}" title="p = \frac{\partial dS}{\partial dz}" /></a>, the momentum measures the Gradient of the Additional Score with respect to the Motion.  The momentum tells you the direction that the motion can be changed to most improve the additional score and the rate of this improvement.  Though it is called the "momentum", it is the "profit of changing motion".

The Euler-Lagrange Equation then reads

<a href="https://www.codecogs.com/eqnedit.php?latex=F&space;=&space;\frac{d}{dt}&space;p" target="_blank"><img src="https://latex.codecogs.com/gif.latex?F&space;=&space;\frac{d}{dt}&space;p" title="F = \frac{d}{dt} p" /></a>

The equation says that, for a strategy that stabilizes the final accumulated score, the rate of profit of changing state is equal to the rate of profit of changing motion.

## Alternate form of the Lagrangian

<a href="https://www.codecogs.com/eqnedit.php?latex=d^2&space;S&space;=&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;d&space;z&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;d^2&space;z&space;=&space;dp&space;\cdot&space;dz&space;&plus;&space;p&space;\cdot&space;d^2&space;z&space;=&space;d(p&space;\cdot&space;d&space;z)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?d^2&space;S&space;=&space;\frac{\partial&space;L&space;dt}{\partial&space;z}&space;\cdot&space;d&space;z&space;&plus;&space;\frac{\partial&space;L&space;dt}{\partial&space;d&space;z}&space;\cdot&space;d^2&space;z&space;=&space;dp&space;\cdot&space;dz&space;&plus;&space;p&space;\cdot&space;d^2&space;z&space;=&space;d(p&space;\cdot&space;d&space;z)" title="d^2 S = \frac{\partial L dt}{\partial z} \cdot d z + \frac{\partial L dt}{\partial d z} \cdot d^2 z = dp \cdot dz + p \cdot d^2 z = d(p \cdot d z)" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=dS&space;=&space;L&space;dt&space;=&space;p&space;\cdot&space;dz" target="_blank"><img src="https://latex.codecogs.com/gif.latex?dS&space;=&space;L&space;dt&space;=&space;p&space;\cdot&space;dz" title="dS = L dt = p \cdot dz" /></a>

Note:  this implies

<a href="https://www.codecogs.com/eqnedit.php?latex=p&space;=&space;\frac{\partial&space;S}{\partial&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p&space;=&space;\frac{\partial&space;S}{\partial&space;z}" title="p = \frac{\partial S}{\partial z}" /></a>

## The Form of the Kinetic Energy and x-Momentum

According to our assumptions, in the event that F -> 0, we have that dL/dt = d^2S/dt^2 -> 0.

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{dL}{dt}&space;=&space;\frac{d}{dt}&space;(p&space;\cdot&space;\frac{dz}{dt})&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{dL}{dt}&space;=&space;\frac{d}{dt}&space;(p&space;\cdot&space;\frac{dz}{dt})&space;\to&space;0" title="\frac{dL}{dt} = \frac{d}{dt} (p \cdot \frac{dz}{dt}) \to 0" /></a>

Since as F = dp/dt, we have that dp/dt -> 0, so

<a href="https://www.codecogs.com/eqnedit.php?latex=p&space;\cdot&space;\frac{d^2&space;z}{dt^2}&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p&space;\cdot&space;\frac{d^2&space;z}{dt^2}&space;\to&space;0" title="p \cdot \frac{d^2 z}{dt^2} \to 0" /></a>

Note that z = (x,t), and name p = (p_x, p_t).  Also note that d^2 t = 0.

<a href="https://www.codecogs.com/eqnedit.php?latex=p_x&space;\cdot&space;\frac{d^2&space;x}{dt^2}&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p_x&space;\cdot&space;\frac{d^2&space;x}{dt^2}&space;\to&space;0" title="p_x \cdot \frac{d^2 x}{dt^2} \to 0" /></a>

Since p_x is arbitrary, we have

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{d^2&space;x}{dt^2}&space;\to&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{d^2&space;x}{dt^2}&space;\to&space;0" title="\frac{d^2 x}{dt^2} \to 0" /></a>

The only Lagrangian consistent with d^2x/dt^2 = 0 

<a href="https://www.codecogs.com/eqnedit.php?latex=L&space;=&space;\frac{dx}{dt}&space;\cdot&space;k&space;\cdot&space;\frac{dx}{dt}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L&space;=&space;\frac{dx}{dt}&space;\cdot&space;k&space;\cdot&space;\frac{dx}{dt}" title="L = \frac{dx}{dt} \cdot k \cdot \frac{dx}{dt}" /></a>

for some proportionality constant k.  Defining m = 2k, we get that as F -> 0

<a href="https://www.codecogs.com/eqnedit.php?latex=L&space;\to&space;\frac{1}{2}&space;\frac{dx}{dt}&space;\cdot&space;m&space;\cdot&space;\frac{dx}{dt}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L&space;\to&space;\frac{1}{2}&space;\frac{dx}{dt}&space;\cdot&space;m&space;\cdot&space;\frac{dx}{dt}" title="L \to \frac{1}{2} \frac{dx}{dt} \cdot m \cdot \frac{dx}{dt}" /></a>

Note

<a href="https://www.codecogs.com/eqnedit.php?latex=p_x&space;=&space;\frac{\partial&space;L&space;dt}{\partial&space;dx}&space;=&space;\frac{\partial&space;L}{\partial&space;\frac{dx}{dt}}&space;\to&space;m&space;\cdot&space;\frac{dx}{dt}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p_x&space;=&space;\frac{\partial&space;L&space;dt}{\partial&space;dx}&space;=&space;\frac{\partial&space;L}{\partial&space;\frac{dx}{dt}}&space;\to&space;m&space;\cdot&space;\frac{dx}{dt}" title="p_x = \frac{\partial L dt}{\partial dx} = \frac{\partial L}{\partial \frac{dx}{dt}} \to m \cdot \frac{dx}{dt}" /></a>

Since p_x is independent of F, we get that regardless of F

<a href="https://www.codecogs.com/eqnedit.php?latex=p_x&space;=&space;\frac{\partial&space;L}{\partial&space;\frac{dx}{dt}}=&space;m&space;\cdot&space;\frac{dx}{dt}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p_x&space;=&space;\frac{\partial&space;L}{\partial&space;\frac{dx}{dt}}=&space;m&space;\cdot&space;\frac{dx}{dt}" title="p_x = \frac{\partial L}{\partial \frac{dx}{dt}}= m \cdot \frac{dx}{dt}" /></a>

Thus, we get

<a href="https://www.codecogs.com/eqnedit.php?latex=L&space;=&space;\frac{1}{2}\frac{dx}{dt}\cdot&space;m&space;\cdot&space;\frac{dx}{dt}&space;-&space;V(x,t)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L&space;=&space;\frac{1}{2}\frac{dx}{dt}\cdot&space;m&space;\cdot&space;\frac{dx}{dt}&space;-&space;V(x,t)" title="L = \frac{1}{2}\frac{dx}{dt}\cdot m \cdot \frac{dx}{dt} - V(x,t)" /></a>

Where V(x,t) is arbitrary.

If we define

<a href="https://www.codecogs.com/eqnedit.php?latex=T(\frac{dx}{dt})&space;=&space;\frac{1}{2}&space;\frac{dx}{dt}&space;\cdot&space;m&space;\cdot&space;\frac{dx}{dt}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?T(\frac{dx}{dt})&space;=&space;\frac{1}{2}&space;\frac{dx}{dt}&space;\cdot&space;m&space;\cdot&space;\frac{dx}{dt}" title="T(\frac{dx}{dt}) = \frac{1}{2} \frac{dx}{dt} \cdot m \cdot \frac{dx}{dt}" /></a>

Then <a href="https://www.codecogs.com/eqnedit.php?latex=L&space;=&space;T&space;-&space;V" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L&space;=&space;T&space;-&space;V" title="L = T - V" /></a>

Since L = T(dx/dt) - V(x,t) is the Immediate Score, we see that T(dx/dt) is the Kinetic part of the Immediate Score (the Immediate Score associated with the immediate motion), or the Kinetic Score (aka Kinetic Energy), and that [-V(x,t)] is the Situational part of the Immediate Score (the Immediate Score associated with the immediate state), or the Situational Score (aka the negative of the Potential Energy).

## The relationship between x and dx as well as z and p  (Where the *MAGIC* happens.  VERY poorly justified)

Define

<a href="https://www.codecogs.com/eqnedit.php?latex=\phi=e^{\frac{S}{-i&space;\hbar}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\phi=e^{\frac{S}{-i&space;\hbar}}" title="\phi=e^{\frac{S}{-i \hbar}}" /></a>

Then, taking the differential and noting that S(z) and L(z) commute, we get

<a href="https://www.codecogs.com/eqnedit.php?latex=-i&space;\hbar&space;d&space;\phi=dS&space;\phi=(p&space;\cdot&space;dz)\phi" target="_blank"><img src="https://latex.codecogs.com/gif.latex?-i&space;\hbar&space;d&space;\phi=dS&space;\phi=(p&space;\cdot&space;dz)\phi" title="-i \hbar d \phi=dS \phi=(p \cdot dz)\phi" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=-i&space;\hbar&space;\frac{\partial}{\partial&space;z}&space;\phi=&space;p\phi" target="_blank"><img src="https://latex.codecogs.com/gif.latex?-i&space;\hbar&space;\frac{\partial}{\partial&space;z}&space;\phi=&space;p\phi" title="-i \hbar \frac{\partial}{\partial z} \phi= p\phi" /></a>

Since p is a function of z and dz and the commutation relationship between z and dz is formulaic, we get

<a href="https://www.codecogs.com/eqnedit.php?latex=p&space;=&space;-i\hbar&space;\frac{\partial}{\partial&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p&space;=&space;-i\hbar&space;\frac{\partial}{\partial&space;z}" title="p = -i\hbar \frac{\partial}{\partial z}" /></a>

Noting that

<a href="https://www.codecogs.com/eqnedit.php?latex=p=m&space;\cdot&space;\frac{dx}{dt}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p=m&space;\cdot&space;\frac{dx}{dt}" title="p=m \cdot \frac{dx}{dt}" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=d&space;x&space;=&space;-i\frac{\hbar}{m}&space;\cdot&space;dt&space;\cdot&space;\frac{\partial}{\partial&space;x}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?d&space;x&space;=&space;-i\frac{\hbar}{m}&space;\cdot&space;dt&space;\cdot&space;\frac{\partial}{\partial&space;x}" title="d x = -i\frac{\hbar}{m} \cdot dt \cdot \frac{\partial}{\partial x}" /></a>

By convention, we make hbar real and positive so that positive m implies dx is hermitian and a generator of forward translation.

## Equation of Motion: Commutator Bracket **(In progress)**

<a href="https://www.codecogs.com/eqnedit.php?latex=p&space;=&space;-i\hbar&space;\frac{\partial}{\partial&space;z}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p&space;=&space;-i\hbar&space;\frac{\partial}{\partial&space;z}" title="p = -i\hbar \frac{\partial}{\partial z}" /></a>

Implies

<a href="https://www.codecogs.com/eqnedit.php?latex=p_t&space;=&space;-i&space;\hbar&space;\frac{\partial}{\partial&space;t}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p_t&space;=&space;-i&space;\hbar&space;\frac{\partial}{\partial&space;t}" title="p_t = -i \hbar \frac{\partial}{\partial t}" /></a>

Thus, for any dynamical variable f(x,p_x) which does not depend on time, we have

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{d}{dt}&space;f&space;=&space;-\frac{1}{i&space;\hbar}[p_t,f]" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{d}{dt}&space;f&space;=&space;-\frac{1}{i&space;\hbar}[p_t,f]" title="\frac{d}{dt} f = -\frac{1}{i \hbar}[p_t,f]" /></a>

And for a general f(x,p_x,t)

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{d}{dt}&space;f&space;=&space;-\frac{1}{i&space;\hbar}[p_t,f]&space;&plus;&space;\frac{\partial&space;f}{\partial&space;t}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{d}{dt}&space;f&space;=&space;-\frac{1}{i&space;\hbar}[p_t,f]&space;&plus;&space;\frac{\partial&space;f}{\partial&space;t}" title="\frac{d}{dt} f = -\frac{1}{i \hbar}[p_t,f] + \frac{\partial f}{\partial t}" /></a>

## The Hamiltonian (Negative Time-Momentum)

Defining

<a href="https://www.codecogs.com/eqnedit.php?latex=H&space;=&space;p_x&space;\cdot&space;\frac{dx}{dt}&space;-&space;L" target="_blank"><img src="https://latex.codecogs.com/gif.latex?H&space;=&space;p_x&space;\cdot&space;\frac{dx}{dt}&space;-&space;L" title="H = p_x \cdot \frac{dx}{dt} - L" /></a>

as the Legendre transform of L, we see that H is a function of (x,p_x,t) and H = -p_t.

We also get the Hamiltonian Equations

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{dx}{dt}&space;=&space;\frac{\partial&space;H}{\partial&space;p_x}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{dx}{dt}&space;=&space;\frac{\partial&space;H}{\partial&space;p_x}" title="\frac{dx}{dt} = \frac{\partial H}{\partial p_x}" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{dp_x}{dt}&space;=&space;-\frac{\partial&space;H}{\partial&space;x}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{dp_x}{dt}&space;=&space;-\frac{\partial&space;H}{\partial&space;x}" title="\frac{dp_x}{dt} = -\frac{\partial H}{\partial x}" /></a>

And we get

<a href="https://www.codecogs.com/eqnedit.php?latex=H=i\hbar\frac{\partial}{\partial&space;t}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?H=i\hbar\frac{\partial}{\partial&space;t}" title="H=i\hbar\frac{\partial}{\partial t}" /></a>

Note:  In the future, we'll simply use -p_t instead of H.

## Equation of Motion: Poisson Bracket

Consider a dynamical variable f(x,p_x,t).  We have

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{d}{dt}&space;f(x,p_x,t)&space;=&space;\frac{\partial&space;f}{\partial&space;x}&space;\cdot&space;\frac{dx}{dt}&space;&plus;&space;\frac{\partial&space;f}{\partial&space;p_x}&space;\cdot&space;\frac{dp_x}{dt}&space;&plus;&space;\frac{\partial&space;f}{\partial&space;t}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{d}{dt}&space;f(x,p_x,t)&space;=&space;\frac{\partial&space;f}{\partial&space;x}&space;\cdot&space;\frac{dx}{dt}&space;&plus;&space;\frac{\partial&space;f}{\partial&space;p_x}&space;\cdot&space;\frac{dp_x}{dt}&space;&plus;&space;\frac{\partial&space;f}{\partial&space;t}" title="\frac{d}{dt} f(x,p_x,t) = \frac{\partial f}{\partial x} \cdot \frac{dx}{dt} + \frac{\partial f}{\partial p_x} \cdot \frac{dp_x}{dt} + \frac{\partial f}{\partial t}" /></a>

<a href="https://www.codecogs.com/eqnedit.php?latex==&space;-\frac{\partial&space;f}{\partial&space;x}&space;\cdot&space;\frac{\partial&space;p_t}{\partial&space;p_x}&space;&plus;&space;\frac{\partial&space;f}{\partial&space;p_x}&space;\cdot&space;\frac{\partial&space;p_t}{\partial&space;x}&space;&plus;&space;\frac{\partial&space;f}{\partial&space;t}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?=&space;-\frac{\partial&space;f}{\partial&space;x}&space;\cdot&space;\frac{\partial&space;p_t}{\partial&space;p_x}&space;&plus;&space;\frac{\partial&space;f}{\partial&space;p_x}&space;\cdot&space;\frac{\partial&space;p_t}{\partial&space;x}&space;&plus;&space;\frac{\partial&space;f}{\partial&space;t}" title="= -\frac{\partial f}{\partial x} \cdot \frac{\partial p_t}{\partial p_x} + \frac{\partial f}{\partial p_x} \cdot \frac{\partial p_t}{\partial x} + \frac{\partial f}{\partial t}" /></a>

Define the Poisson bracket as

<a href="https://www.codecogs.com/eqnedit.php?latex=\{f,g\}=&space;\frac{\partial&space;f}{\partial&space;x}&space;\cdot&space;\frac{\partial&space;g}{\partial&space;p_x}&space;-&space;\frac{\partial&space;f}{\partial&space;p_x}&space;\cdot&space;\frac{\partial&space;g}{\partial&space;x}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\{f,g\}=&space;\frac{\partial&space;f}{\partial&space;x}&space;\cdot&space;\frac{\partial&space;g}{\partial&space;p_x}&space;-&space;\frac{\partial&space;f}{\partial&space;p_x}&space;\cdot&space;\frac{\partial&space;g}{\partial&space;x}" title="\{f,g\}= \frac{\partial f}{\partial x} \cdot \frac{\partial g}{\partial p_x} - \frac{\partial f}{\partial p_x} \cdot \frac{\partial g}{\partial x}" /></a>

To get

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{d}{dt}&space;f(x,p_x,t)&space;=&space;\{&space;p_t,&space;f&space;\}&space;&plus;&space;\frac{\partial&space;f}{\partial&space;t}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{d}{dt}&space;f(x,p_x,t)&space;=&space;\{&space;p_t,&space;f&space;\}&space;&plus;&space;\frac{\partial&space;f}{\partial&space;t}" title="\frac{d}{dt} f(x,p_x,t) = \{ p_t, f \} + \frac{\partial f}{\partial t}" /></a>


Note.  This implies

<a href="https://www.codecogs.com/eqnedit.php?latex=-\frac{1}{i&space;\hbar}[p_t,\cdot]&space;=&space;\{&space;p_t,&space;\cdot&space;\}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?-\frac{1}{i&space;\hbar}[p_t,\cdot]&space;=&space;\{&space;p_t,&space;\cdot&space;\}" title="-\frac{1}{i \hbar}[p_t,\cdot] = \{ p_t, \cdot \}" /></a>
