---
layout: page
title: Research
---

**Characterization of Rare-Earth and Actinide Compounds**

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
*Record Hyperfine Clock Transitions in Ln-based Molecular Qubits*

![hct](/assets/img/HCT.png "hct")

Due to their extensive magnetic tunability and potential for
self-assembly-based scale-up, lanthanide single molecule magnets 
represent a promising next-generation qubit platform for quantum
computing. In collaboration with the groups of Professor Evans at UCI and Professor Hill at FSU, 
we recently demonstrated the viability of this technology by
highlighting a novel series of Ln complexes: [La(OAr\*3)]-,
[Lu(OAr\*3)]-, and [Lu(NR2)3]- (OAr\* = 2,6-Ad2-4-t-Bu-C6H2O, Ad = adamantyl, t-Bu= tert-butyl, R = SiMe3 with Me =
methyl). We demonstrated through EPR and KS-DFT studies that variation of the
s-orbital mixing present in the 6s/d Singly Occupied Molecular Orbital
(SOMO) of these complexes could be used to tune their magnetic structure
and subsequently engineer clock transitions, a type of hyperfine transition that is particularly resilient against
quantum decoherence. We ultimately showed that [Lu(OAr\*)3]- exhibited a massive clock transition of approximately 9 GHz 
resulting in enhanced magnetic relaxation times. The above figure
depicts an illustration of a hyperfine clock transition (left) and 
the singly occupied molecular orbital density responsible for it
in [Lu(OAr\*)3]- (right). A publication is
currently under review, and a preprint is available here:
https://doi.org/10.26434/chemrxiv.14399333.v1 

<br/>
*Predictions of Hyperfine Clock Transitions from Local Exact
Two-Component Theory*

![hfc](/assets/img/HFC.png "hfc")

While KS-DFT successfully predicted the trends in
hyperfine coupling for [La(OAr\*3)]-,
[Lu(OAr\*3)]-, and [Lu(NR2)3]-, the values themselves possessed errors of roughly one order of magnitude
when compared with experimental results. This can mostly be attributed to the non-relativistic operator
used to calculate the HFC matrix, giving rise to a large picture-change
error. While such a method proved useful when paired with
experiment, improvements which can achieve quantitative accuracy are desired if
in silico discovery of optimal SMMs is to be realized.
 
In collaboration with Yannick Franzke from the University of Marburg, we
implemented the hyperfine coupling expression in the quasirelativistic
exact two-component framework (X2C), which circumvents the errors described
above. As illustrated in the above figure, our X2C, "SO"-based hyperfine
coupling constants greatly reduce the error over the previous method
(denoted "SR-NR" here), and brings them in line with experimental
results. As such, we have realized an accurate tool capable of in-silico
exploration of new single molecule magnet candidates. A publication is
currently under review, and a preprint is available here:
https://doi.org/10.33774/chemrxiv-2021-wnz1v

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

![toc](/assets/img/toc.png "toc")

Through our previous work on Dy(CpiPr5)2 and Tb(CpiPr5)2, we also suspected that
the analogous divalent actinide species would also be synthetically isolable. If
so, these compounds would represent the first linear cyclopentadienyl complexes 
for the actinides, which were previously thought to be impossible to exist due
to the known absence of covalent interactions within f-element species. 

In our study (see: https://doi.org/10.1021/acs.inorgchem.9b02505), we found
computational evidence for the accessibility of such compounds. Soon after our
results were made available online, bis(cyclopentadienyl) uranium(II) was
synthesized by Lafield et al., validating our own theoretical predictions.

<br/><br/>
**Development of Ab-initio methods towards the description of Excited States for Periodic Systems**

Quantum chemistry methods capable of describing the electronic structure of solids have long been desired in the fields of condensed matter physics and materials science. Knowledge of the excited state spectrum of technologically important materials, like those with light-harvesting or superconducting characteristics, is particularly crucial to the solution of difficult scientific and societal problems. 

Part of my research involves developing methods derived from Coupled-Cluster theory to accurately predict excited-state properties of solids:

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
