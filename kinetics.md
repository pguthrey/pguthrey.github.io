---
layout: default
---

## Kinetic Equations

The original motivation behind the Regionally-Implicit DG method was to develop an efficient solver for the relativistic Vlasov-Maxwell (RVM) system in order to model laser-plasma interactions.  The unique difficulty inherent to the relativistic regime of plasmas is that operator splitting of the relativistic Lorentz Force term leads to unphysical instabilities [Huot et. al 2003].  Our approach implements Cheng-Knorr splitting, using a Semi-Lagrangian DG method for the advection term and the electromagnetic field update, and RIDG for the Lorentz force term. 

Our current work centers around two popular relativistic phenomena:

* Weibel instability, where momentum anisotropies cause electromagnetic wave growth [Weibel 1959]
* Wakefield acceleration, where a laser causes plasma waves to accelerate to nearly the speed of light.  

Particle-in-cell (PIC) simulations are commonly used to generate models of such plasma applications, as seen in this video:

<iframe width="560" height="315" src="https://www.youtube.com/embed/lgxVYl_pslI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

More details can be found in this paper:

[(coming soon) P.T. Guthrey and J.A. Rossmanith. The regionally-implicit discontinuous Galerkin method: Application to the Relativistic Vlasov-Maxwell System.](./)


[back](./)
