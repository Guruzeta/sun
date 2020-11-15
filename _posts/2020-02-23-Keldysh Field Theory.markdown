---
layout: post
title:  "Path Integrals and Keldysh Field Theory"
date:   2020-07-03 16:41:33 +0530
categories: Notes
author: Guru Kalyan
feature: https://i.imgur.com/LmN4maY.jpg

---
Hey there! I am currently working my nights on learning Keldysh Field theory for
non-equilibrium statistical mechanics. The real time situation is
me learning about path integrals and gaining on a field theoretic approach to
tackle many body problems.
I'll share the notes soon updating my progress therein.

#Update 3

# Update: 2
So I finally went into Keldysh field theory. One of the main ideas of the theory is to allow the case for non-adiabatic interactions i.e. one can ramp up a time varying external field that will drive the system away from equilibrium.

From what I've read about this, for equilibrium situations, one is guided by the following recipe :

$$ \|GS> = U_{t,-\infty}\|0> $$                                           

The only time dependence exhibited by the above is in the _adiabatic_ switching on and off of interactions, which seem to evolve $$\|0>$$ to $$\|GS>$$.

Since the term _adiabatic_ is new, let me define it here:

Suppose we have a quantum system( for the time being consider discrete and non-degenerate spectrum, it'll allow one to label states) subjected to
a time dependent external perturbation.

Now there are two ways this plays out:
1. $$ H_{ext}$$ varies rapidly, leaving our system ineffective to adapt to it's change(i.e. the functional form of $$ \Psi(x,t)$$ remains same).
The system time-scale goes as $$\tau_{system}$$ = $$\frac{h}{E_0}$$(I'll have to clarify why this is
precisely so). Also the separation from other eigenvalues is also important - a large separation will render transition rate lesser to other states. In this case, the wave function satisfies
$$ (\Psi(x,t))^2 $$ = $$ (\Psi(x,t_0))^2 $$

2. $$ H_{ext}$$ varies slowly, giving the system time to adapt and change it's functional dependence.
This crucially depends on the time difference $$t_1-t_0$$, the final and initial time of the applied perturbation(a statement of _Adiabatic_ theorem).
For very large time scales, the system will evolve from $$|n_0>$$ to $$(\Psi_{\epsilon}$$ i.e. an eigenstate of the interacting hamiltonian.

The adiabatic switching on and off of the interactions essentially evolve \\(|0>\\) to exp(iL)\\(|0>\\)
i.e. same state upto a phase factor. This can then be leveraged to calculate various correlators and expectation values of operators.

But in case of non-equilibrium dynamics,(a) isn't simply true. Moving further requires us to evolve both forward and backward in time, which is what Keldysh does.   


# Update: 1


Till now i've mostly been going through Prof. Sensarma's lectures on doing path integrals via the
imaginary time formalism. For a complete overview, look at the following overview of his concise lectures on path integral:-
[Path Integrals In Quantum Mechanics](https://theory.tifr.res.in/~sensarma/courses/ADVQMLNOTE/pathint.html)

I'm currently at lecture 24th of this series. Apart from that, I've made some notes that make the idea
of propagator precise as advertised in his lecture \\(22^{nd}\\). Kleinert's sections on \\(x^4\\).
I'm currently wondering about how to calculate the real time propagator using the same( I might be confusing the calculation of partition function with the same).

Apart from that, some work on why green's functions are relevant quantities experimentally is due. The apocryphal message of the Green's function as being a relevant experimental quantity is something i'd like to see. Further updates to follow.
