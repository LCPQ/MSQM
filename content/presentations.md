---
title: "Presentations"
date: 2020-12-02 09:06
draft: false
---

# SUBMITTED ABSTRACTS

### Arjan Berger (LCPQ, Toulouse)

**The one-point model: solving equations in pointland**

In the one-point model we consider a zero-dimensional space.
The advantage of this model is that the many-body equations simplify enormously and can be solved analytically.
In particular, the one-body Greenʼs function is a solution of a set of functional integro-differential equations, which relate the one-particle Greenʼs
function to its functional derivative with respect to an external potential [1].
In the one-point model, these equations become ordinary differential equations that are solvable with standard techniques. 
This allows us to analyze several aspects of these equations as well as of standard methods for determining the one-body Greenʼs function, such as GW, that are important for real systems.
For example, it allows us to investigate the problem of unphysical solutions of the many-body equations [2].

[1] J.A. Berger et al., New J. Phys. 16 113025 (2014)
[2] A. Stan et al., New J. Phys. 17 093045 (2015)

### Michel Caffarel (LCPQ, Toulouse)

**Path integral for the quartic oscillator: An approximate analytic expression for the partition function**

Using a path integral formalism 
we derive an approximate analytic expression for the partition function of the quartic anharmonic oscillator $V(x) = \frac{1}{2} 
\omega^2 x^2 + g x^4$. From the partition function we also derive explicit expressions for the ground-
and first-excited state energies $E_0(g)$ and $E_1(g)$, respectively. 
Quite remarkably, these energies are found to be accurate for the whole range
of the coupling constant $g$. In addition, both the weak- and strong-coupling expansions are qualitatively 
reproduced.
We believe that 
our approximate explicit partition function reproducing the key features of the exact partition function 
defines an interesting model to investigate 
the properties of the quartic oscillator.

### Antoine Levitt (LMO, Orsay)

**TBA**

### Peter Gill (USyd, Sydney)

**How delocalised are the polyacenes?**

The polyacenes or $n$-acenes consist of $n$ linearly fused benzene rings, and include benzene itself, naphthalene, anthracene, tetracene, etc.  Their $\sigma$ electrons are well localised into C-C and C-H bonds and their $\pi$ electrons are delocalised over the entire molecule.  At least, that is what many of us teach our undergraduate students.  But is it true?  In this lecture, I will report calculations in which the $\pi$ electrons are artificially confined into localised orbitals and I will use the resulting energy increase — the localisation energy — as a measure of the degree to which the $\pi$ electrons want to be delocalised.  The results suggest that we may need to update our undergraduate lectures…

### Eric Cancès (CERMICS, Paris)

**Model systems for discretization error analysis**

In the first part of my talk, I will present a detailed analysis of the famous error cancellation phenomenon in electronic structure calculation on the example of a 1D Hamiltonian with Dirac-delta potentials and periodic boundary conditions [1]. In the second part of my talk, I will illustrate the importance of continuous spectrum (scattering states) in quantum chemistry by numerical calculations based on the explicit knowledge of the bound states of the hydrogen atom [2].

[1] E. Cancès and G. Dusson, Discretization error cancellation in electronic structure calculation: toward a quantitative study, M2AN 51 (2017) 1617–1636
[2] E. Cancès, R. Coyaud and L.R. Scott, Van der Waals interactions between two hydrogen atoms: the next orders, Comm. Math. Sci. 21 (2023) 915–948.

### Timothee Audinet (LCT, Paris)

**One-dimensional model with delta-type interactions: Dirac's equation with QED interactions**

It is important to take into account the effects of special relativity in the quantum description of chemical systems with heavy elements. The relativistic effects account for gold’s color, mercury’s liquid state at room temperature and are responsible for the efficiency of lead-acid batteries in cars [1]. Relativistic electronic-structure computational methods have been developed in the no-pair approximation, and are now routinely applied on molecular systems. Hence, the next challenge is to go beyond the no-pair approximation by including the quantum-electrodynamics (QED) effects of virtual electron-positron pairs. Such description is needed to recover some properties, even in very simple systems, e.g. the Lamb shift in the Hydrogen atom.
In this work we are interested in a one-dimensional model of relativistic hydrogen-like atom using delta-potential interactions. It is motivated by the non-relativistic version of this model which leads to the same ground-state energy and radial wave function as the three-dimensional one [2]. In this model we are able to make accurate QED calculations [3]. After calculating the spectrum of the 1D Dirac operator [4]
$$
\boldsymbol{\mathrm{D}}(x) = -\mathrm{i} c \boldsymbol{\sigma}_1 \frac{\mathrm{d}}{\mathrm{d} x} + \boldsymbol{\sigma}_3 m c^2  -Z \delta(x)
$$
in first quantization, we develop an effective QED Hamiltonian in a fermionic Fock-space. This effective QED theory includes the effects of the vacuum polarization but does not include the photon degrees of freedom [5,6,7]. Within this framework we are able to calculate the vacuum-polarization density and the QED Lamb-type shift of the bound-state energy.


[1] P. Pyykkö, Annu. Rev. Phys. Chem. 63, 45 (2012).
[2] D. Traore, E. Giner and J. Toulouse, J. Chem. Phys. 156, 044113 (2022).
[3] T. Audinet and J. Toulouse, J. Chem. Phys. 158, 244108 (2023).
[4] I. R. Lapidus, Am. J. Phys. 51, 1036 (1983).
[5] P. Chaix and D. Iracane, J. Phys. B 22, 3791 (1989).
[6] C. Hainzl, M. Lewin, E. Séré and J. P. Solovej, Phys. Rev. A 76, 052104 (2007).
[7] J. Toulouse, SciPost Chem. 1, 2 (2021).

### Cyril Martins (LCPQ, Toulouse)

**TBA**

### Leo Gaspard (LCPQ, Toulouse)

**TBA**

### Cesar Feniou (QUBITS-P, Paris)

**Greedy Gradient-free Adaptive Variational Quantum Algorithms on a Noisy Intermediate Scale Quantum Computer**

Hybrid quantum-classical adaptive Variational Quantum Eigensolvers (VQE) already hold the potential to outperform classical computing for simulating quantum many-body systems. However, their practical implementation on current quantum processing units (QPUs) is very challenging due to the noisy evaluation of a polynomially scaling number of observables, undertaken for operator selection and optimisation of a high-dimensional cost function. To overcome this, we propose new techniques to execute adaptive algorithms on a 25-qubit error-mitigated QPU coupled to a GPU-accelerated HPC simulator. Targeting physics applications, we compute the ground state of a 25-body Ising model using the newly introduced Greedy Gradient-free Adaptive VQE (CGA-VQE) requiring only five circuit measurements per iteration, regardless of the number of qubits and size of the operator pool. We show that the QPU successfully executes the algorithms and yields the correct choice of parametrised unitary operators. While the QPU evaluation of the resulting ansatz wave-function is polluted by hardware noise, a single final evaluation of the sought-after observables on a classical GPU-accelerated/noiseless simulator allows the recovery of the correct approximation of the ground state, thus highlighting the need for hybrid quantum-classical observable measurement.

### Nicolas Laflorencie (LPT, Toulouse)

**Topological and quantum critical properties of the interacting Majorana chain model**

Despite our very good understanding of several models in one dimension involving interacting (Dirac) fermions, the case of Majorana fermions has remained relatively unexplored. This is probably due to the fact that Majorana particles are not found as elementary objects in nature. Nevertheless, 20 years ago, in the context of modeling p-wave superconducting wires, Alexei Kitaev proposed a very influential yet simple toy model in which unpaired Majorana fermions can appear as edge states. In this talk I will present the basics of this problem and explore the non-trivial effects of interactions in such a system, building on DMRG and self-consistent mean-field approaches. If time permits, I may also touch on disorder effects...

### Jack Thomas (LMO, Orsay) 

**TBA**

### Pieter Van Isacker (GANIL, Caen)

**TBA**

### Alexander Tichai (TU, Darmstadt)

**TBA**

### Denis Lacroix (IN2P3, Orsay)

**TBA**

### Alfred Kirsch (CERMICS, Paris)

**Some mathematical insights on DMFT on a Hubbard model**

In this talk, I will discuss recent work on the mathematical properties of the Dynamical Mean-Field Theory applied to the Hubbard model [2, 4, 1]. In spite of its general use in condensed matter physics, the mathematical framework of DMFT has not been explored thoroughly: to our knowledge, this issue has only been addressed in [3], where it is shown that the self-consistent map is well defined for a particular set of functions representing a finite bath. In this talk, after a brief reminder on the Hubbard model and the DMFT formalism, I will present joint work with S. Perrin-Roussel and E. Cances in which we start by extending this result to a larger class of functions that can model infinite bath. I will also detail results on a specific impurity solver, the Iterated Perturbation Theory (IPT). If time allows, I will then discuss numerical developments arising from these results (using TRIQS [5]) and the well-posedness of the DMFT equations in this frame.

[1] Antoine Georges, Gabriel Kotliar, Werner Krauth, and Marcelo J. Rozen- berg. Dynamical mean-field theory of strongly correlated fermion systems and the limit of infinite dimensions. Reviews of Modern Physics, 68(1):13– 125, January 1996.
[2] J. Hubbard. Electron Correlations in Narrow Energy Bands. Proceedings of the Royal Society of London. Series A, Mathematical and Physical Sciences, 276(1365):238–257, 1963. Publisher: The Royal Society.
[3] Michael Lindsey. The Quantum Many-Body Problem: Methods and Analysis. PhD thesis, UC Berkeley, Berkeley, 2019.
[4] Walter Metzner and Dieter Vollhardt. Correlated Lattice Fermions in $d = \infty$ Dimensions. Physical Review Letters, 62(3):324–327, January 1989.
[5] Olivier Parcollet, Michel Ferrero, Thomas Ayral, Hartmut Hafermann, Igor Krivenko, Laura Messio, and Priyanka Seth. TRIQS: A toolbox for research on interacting quantum systems. Computer Physics Communications, 196:398–415, November 2015.

# POSTERS

### Vitaly Gorelov (LSI, Palaiseau)

**TBA**

### Antoine Roux (CEA, Saclay)

**Emulation for (very) large scale PGCM computations of nuclei**

### Pepijn Demol (KU, Leuven)

**TBA**



 
