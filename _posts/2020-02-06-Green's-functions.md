---
layout: post
title:  "Green's Functions"
date:   2020-06-02 16:41:33 +0530
categories: Notes
author: Guru Kalyan
feature: https://i.imgur.com/LmN4maY.jpg

---


As the title reads here I wish to digress a little bit into why does one care about Green's functions, other than as a tool for solving PDE's(read E&M).
Though a digression, I'll try to mention the broad areas where Green's function
can give a clue to the physics of a system. In fact, recently I came across a
video that iterated the line "The language of Many body physics is Green's functions".
Hopefully this short exposition of mine can help to decrypt some of these "shower"
thoughts that I've been having.

So to my current knowledge, Green's functions are used in the following areas:

1. As a first object calculated to yield scattering cross sections in relativistic field theories (e.g. $$ \phi^4 $$ theory) and to calculate S-matrix elements.

2. As a tool to calculate the linear response of a quantum system, mostly
compacted by Kubo's formula.( Why is it important?)

3. In many body physics, Green's function typically are thought of as "propagating" some excitations.
In a QM sense, a green's function will look like

$$ \mathcal{G}\;=\;<\Vec{r},t|\Vec{r'},t> $$

What this describes is the amplitude for propagation from one space time point to another. The many body analogue of this is defined as

$$ \mathcal{G}^{R}\;=\;-i\theta(t-t') <\{c_i(t), \dagger{c}_j(t') \}> $$

Turns out, the latter captures the "single particle" dynamics of the interacting $$ \mathcal{H}$$.

The two important observations are:-

1. The poles of $$\mathcal{G}^{R}$$ are the effective one-particle energies.
This is important in the following sense - Suppose you are handed a many body problem with a generic hamiltonian. Now **solving** the problem necessitates to diagonalizing $$\mathcal{H}$$. This is clear to see when one uses second quantization approach. Typical strategies involve performing a canonical transformation and diagonalizing in new basis.

 However, when one writes a path integral for the problem, it's not entirely evident about how to recover **single** particle levels. The way forward is to generate an effective quadratic action (through various approximations like saddle point expansion, doing a hubbard stratonovich transformation, mean field decoupling etc.). Once done, it's easy to read off the $$\mathcal{G}^{-1}$$ (which in certain cases might be a matrix too ;) ) and compute it's poles. In examples like BCS superconductivity or Bogoliubov theory of bosons, the latter is very easy to do and one extracts single particle spectrum with lesser misery :smile:

2. Imaginary part of  $$\mathcal{G}^{R}$$ on the other hand represents the **local** density of states for one-particle spectrum.

As clearly evident, this post requires some concrete explanation and hopefully
I'll cover points 2 and 3 by the end of this week.
