---
layout: page
title: Research
---

**Development of Ab-initio methods towards the description of Excited States for Periodic Systems**

Quantum chemistry methods capable of describing the electronic structure of solids have long been desired in the fields of condensed matter physics and materials science. Knowledge of the excited state spectrum of technologically important materials, like those with light-harvesting or superconducting characteristics, is particularly crucial to the solution of difficult scientific and societal problems. 

Several methods are currently used to calculate properties of solids, such as Time-Dependent Density Functional Theory and the GW approximation. These techniques have seen a degree of success in computing electronic properties, but also possess a number of drawbacks. For example, both techniques tend to give inaccurate band gaps and possess non-straightforward avenues towards obtaining higher accuracy. 

Part of my research involves developing methods derived from Coupled-Cluster theory to circumvent such issues and accurately predict excited-state properties of solids:

<br/>
*Equation-of-motion Coupled Cluster Theory for Solids*

![eom](/assets/img/eom.png "eom")

The Equation-of-motion Coupled Cluster technique has been used to obtain high-accuracy excited state properties for molecules in the past. The extension of this formalism to solids is a logical next step. This was first implemented by McClain et al. in the quantum chemistry software PySCF. My work on this project involves leading a subgroup to extend this foundational code to Unrestricted systems using spatial orbitals, as well as General systems with spin orbitals. We expect to publish the results of this work, including applications to various solids , in the near future.

<br/>
*Coupled-Cluster Green's Functions for Solids*

![dmd](/assets/img/dmd.png "luc")

While the Equation-of-motion technique for solids has given promising results for description of quasiparticle energies, it has difficulty converging satellite states with larger many-body character. Because these states are important to understand the electronic properties of  materials, a method to acquire these satellite states is desired. 

The frequency-dependent Single-particle Green's function, which can be evaluated directly in the Coupled Cluster Approximation, offers a potential solution to this issue. Its poles contain the quasiparticle energies of the many-body system, and can be found explicitly through its dependence on the energy. In my work on this project, I implemented the Coupled Cluster Green's Function method for Periodic systems in PySCF, and am active in its improvement.

<br/><br/>
**Genetic Algorithms for Fluorophore Determination**

![luc](/assets/img/luc.png "luc")

One of my past projects involved the development of a genetic algorithm to determine chemilluminescent probes for disease detection. Applying the algorithm to explore the chemical space of molecules derived from Luciferin, a chemical species responsible for the light given off by fireflies, I identified several candidates with strong fluorescent properties for further computational and experimental study. We hope to generalize this initial implementation to a variety of molecular base structures and apply it to additional chemical search projects in the future.
