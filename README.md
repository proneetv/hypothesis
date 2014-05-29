Hypothesis
==========

Numerical methods in quantum mechanics
--------------------------------------

This repository holds the files which were used to do a computational analysis for the following:

- Schrodinger Equations - Harmonic Oscillator, N degree potentials, Morse Potential
- Schrodinger Equation for central potentials
- Scattering from a potential
- The Variational Method

How to use:
-----------

To compile: 
`gcc harmonic1.c -lm`

Fill in whatever parameters you want with the file name and the data sheet would be generated with columns being:
- x
- parity * x
- probability distribution
- classical probability
- V Potential

Algorithms used:
----------------

Numerov Method
Bisection Method
Newton-Raphson Method
Secant Method

TODO:
-----

I'd be trying to improve the computational approach with the use of parallel algorithms.

References:
-----------
(I'd be adding more as and when I use)

> www.fisica.uniud.it/~giannozz/Corsi/MQ/mq.html
