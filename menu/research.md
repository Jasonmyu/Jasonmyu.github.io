---
layout: page
title: Research
---

**Theoretical Characterization of Rare-Earth and Actinide Compounds**

![comp](/assets/img/comp.png "comp")

Coordination compounds of the rare-earth and actinide elements have garnered
significant interest for their novel catalytic and magnetic properties, which
are employed for applications in small-molecule activation, magnetism, and the
separation of nuclear waste products. Unfortunately, the oftentimes pyrophoric
and radioactive nature of these species complicate their experimental
handling, requiring specialized instrumentation and methodology. The
availability and regulation of starting material is also a sizable obstacle.

To address such difficulties, my Ph.D. research involves the development and
application of
quantum chemistry electronic structure methods to investigate the properties of novel rare-earth and
actinide compounds. With our current theoretical methodology based on Density
Functional Theory (DFT), robust computation of equilibrium strucures, excitation
energies, and force constants are possible for these complicated systems. A
precise treatment of their magnetic properties, including the calculation of
hyperfine coupling constants, magnetic moments, and anisotropy are currently
under development.
Some of my recent work in this area is briefly mentioned below:

<br/>
*Characterization of Bis(pentaisopropylcyclopentadienyl) Terbium(II) and Dysprosium(II)*

![ln](/assets/img/ln.png "ln")

In a collaboration with the group of Professor Long, I studied the electronic
properties of a series of novel low-valent, linear lanthanide
complexes Dy(CpiPr5)2 and Tb(CpiPr5)2. We discovered that, contrary to prior
predictions, the ground states associated with these species adopted 4fn 5d1
configurations, with significant 6s/5dz2 hybrid character in the HOMO. These
compounds are now being further investigated for their suitability as single
molecule magnets (SMMs). See the published article here:
https://doi.org/10.1021/jacs.9b05816

 
<br/>
*Prediction of Bis(pentaisopropylcyclopentadienyl) Actinide Species*

![toc](/assets/img/ln.png "toc")

Through our previous work on Dy(CpiPr5)2 and Tb(CpiPr5)2, we also suspected that
the analogous divalent actinide species would also be synthetically isolable. If
so, these compounds would represent the first linear cyclopentadienyl complexes 
for the actinides, which were previously thought to be impossible to exist due
to the known absence of covalent interactions within f-element species. 

In our study (see: https://doi.org/10.1021/acs.inorgchem.9b02505), we found
computational evidence for the accessibility of such compounds. Soon after our
results were made available online, bis(cyclopentadienyl) uranium(II) was
synthesized by Lafield et al., validating our own theoretical predictions.


**Development of Ab-initio methods towards the description of Excited States for Periodic Systems**

Quantum chemistry methods capable of describing the electronic structure of solids have long been desired in the fields of condensed matter physics and materials science. Knowledge of the excited state spectrum of technologically important materials, like those with light-harvesting or superconducting characteristics, is particularly crucial to the solution of difficult scientific and societal problems. 

Several methods are currently used to calculate properties of solids, such as Time-Dependent Density Functional Theory and the GW approximation. These techniques have seen a degree of success in computing electronic properties, but also possess a number of drawbacks. For example, both techniques tend to give inaccurate band gaps and possess non-straightforward avenues towards obtaining higher accuracy. 

Part of my research involves developing methods derived from Coupled-Cluster theory to circumvent such issues and accurately predict excited-state properties of solids:

<br/>
*Equation-of-motion Coupled Cluster Theory for Solids*

![eom](/assets/img/eom.png "eom")

The Equation-of-motion Coupled Cluster technique has been used to obtain
high-accuracy excited state properties for molecules in the past. The extension
of this formalism to solids is a logical next step. This was first implemented
by McClain et al. in the quantum chemistry software PySCF, and recently extended 
to unrestricted systems using spatial orbitals, as well as general systems with spin orbitals. 
A recent application to the bulk electronic properties of MnO and NiO can be found here:
https://doi.org/10.1103/PhysRevB.101.165138


<br/>
*Coupled-Cluster Green's Functions for Solids*

![dmd](/assets/img/dmd.png "luc")

While the Equation-of-motion technique for solids has given promising results for description of quasiparticle energies, it has difficulty converging satellite states with larger many-body character. Because these states are important to understand the electronic properties of  materials, a method to acquire these satellite states is desired. 

The frequency-dependent Single-particle Green's function, which can be evaluated
directly in the Coupled Cluster Approximation, offers a potential solution to
this issue. Its poles contain the quasiparticle energies of the many-body
system, and can be found explicitly through its dependence on the energy. In my
work on this project, I implemented an initial version of the Coupled Cluster Green's Function method
for Periodic systems in PySCF.

<br/><br/>
**Genetic Algorithms for Fluorophore Determination**

![luc](/assets/img/luc.png "luc")

One of my past projects involved the development of a genetic algorithm to determine chemilluminescent probes for disease detection. Applying the algorithm to explore the chemical space of molecules derived from Luciferin, a chemical species responsible for the light given off by fireflies, I identified several candidates with strong fluorescent properties for further computational and experimental study. We hope to generalize this initial implementation to a variety of molecular base structures and apply it to additional chemical search projects in the future.
