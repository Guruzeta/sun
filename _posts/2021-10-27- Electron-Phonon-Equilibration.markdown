---
layout: post
title:  "Electron Phonon equilibration"
date:   2021-10-27 16:41:33 +0530
categories: Notes
author: Guru Kalyan
feature: https://i.imgur.com/LmN4maY.jpg
---

Project on e-ph equilibration using keldysh formalism.


# Abstract

We are investigating the dynamics of a coupled electron- phonon system within Keldysh formalism, where both electrons and phonons evolve in time self-consistently, as opposed to the standard paradigm of one set of constituents forming a static bath for the other.

Experimentally, this is relevant for various physical models. For example, in devices such as bolometers (measures power of incident radiation by noting the concomitant temperature rise in the incident material), the general idea is that charged particles impinge and excite electrons in lattice, which subsequently thermalise by redistributing received energy. This would involve a chain-reaction b/w electrons and phonons, each exchanging energy with the other while evolving towards steady state. Various results in such systems depend crucially on the specificities of this non-equilibrium dynamics. More interestingly, at low temperatures, this dynamics might be interesting as other subsidiary phenomena such as superconductivity (e.g. s-wave) involve electron-phonon interaction to enable an entirely new phase of matter.

We hope to study this phenomena in detail by doing an honest calculation sans popular approximations.


**<a href="https://github.com/Guruzeta/Julia" target="_blank">
Link to github repo containing codes</a>**

**<a href="https://guruzeta.github.io/sun/pdfs/kft1.pdf" target="_blank">
Working draft</a>**

## References

1. Lin, Zhibin and Zhigilei, Leonid V and Celli, Vittorio. "Electron-phonon coupling and electron heat capacity of
metals under conditions of strong electron-phonon nonequilibrium". In: Physical Review B, volume 77, number 7,
pages 075133, year 2008, publisher : APS.

2.  Saavedra, JRM and Asenjo-Garcia et al. "Hot-electron dynamics and thermalization in small metallic nanoparticles".
In: ACS Photonics, volume 3, number 9, year 2016, publisher: ACS Publications.

3. Chakraborty, Ahana and Sensarma, Rajdeep. "Power-law tails and non-Markovian dynamics in open quantum systems: An exact solution from Keldysh field theory". In: Physical Review B, volume 97,number 10, 2018, publisher: APS.

4. Kamenev, Alex. "Field theory of non-equilibrium systems", 2011, publisher: Cambridge University Press.
