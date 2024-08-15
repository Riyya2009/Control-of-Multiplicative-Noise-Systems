# Control-of-Multiplicative-Noise-Systems

Modeling processes using controlled dynamical systems are ubiquitous in the sciences; a stereotypical example is the trajectory of a car or plane, but the trajectory of weights in gradient descent is another good example. One of the key goals of a controller in a control system is to keep the system stable in the presence of noise (i.e., to make sure that the system state (or errors) does not grow unboundedly). A common model for such systems is a linear time-invariant control system. The problem of designing optimal control strategies was solved for such systems, first in the idealistic and “noise-free” case, then in the case of “additive noise.”

However, this problem is still unsolved for the case of “multiplicative noise” (i.e., when the system model might be changing, say, because it is being repeatedly estimated from data). Over the course of the project, we gradually build up from designing optimal controls for easier types of multiplicative-noise systems into attempting to design controls for harder types of such systems where there is no known optimal control. We used techniques from stochastic optimization and policy gradient algorithm to work on active research problems.
