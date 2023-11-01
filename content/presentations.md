---
title: "Presentations"
date: 2020-12-02 09:06
draft: false
---

# SUBMITTED ABSTRACTS

### Arjan Berger (LCPQ, Toulouse)

**The one-point model: solving equations in pointland**

In the one-point model we consider a zero-dimensional space. The advantage of this model is that the many-body equations simplify enormously and can be solved analytically. In particular, the one-body Greenʼs function is a solution of a set of functional integro-differential equations, which relate the one-particle Greenʼs function to its functional derivative with respect to an external potential [1]. In the one-point model, these equations become ordinary differential equations that are solvable with standard techniques.  This allows us to analyze several aspects of these equations as well as of standard methods for determining the one-body Greenʼs function, such as GW, that are important for real systems. For example, it allows us to investigate the problem of unphysical solutions of the many-body equations [2].

[1] J.A. Berger et al., New J. Phys. 16 113025 (2014)
[2] A. Stan et al., New J. Phys. 17 093045 (2015)

### Michel Caffarel (LCPQ, Toulouse)

**Path integral for the quartic oscillator: An approximate analytic expression for the partition function**

Using a path integral formalism we derive an approximate analytic expression for the partition function of the quartic anharmonic oscillator $V(x) = \frac{1}{2} \omega^2 x^2 + g x^4$. From the partition function we also derive explicit expressions for the ground- and first-excited state energies $E_0(g)$ and $E_1(g)$, respectively. Quite remarkably, these energies are found to be accurate for the whole range of the coupling constant $g$. In addition, both the weak- and strong-coupling expansions are qualitatively reproduced. We believe that our approximate explicit partition function reproducing the key features of the exact partition function defines an interesting model to investigate the properties of the quartic oscillator.

### Antoine Levitt (LMO, Orsay)

**Resonances: the example of the 1D chain**

I will discuss the concept of quantum mechanical resonances and
numerical methods to compute them, starting from the example of the 1D
chain.

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

It is important to take into account the effects of special relativity in the quantum description of chemical systems with heavy elements. The relativistic effects account for gold’s color, mercury’s liquid state at room temperature and are responsible for the efficiency of lead-acid batteries in cars [1]. Relativistic electronic-structure computational methods have been developed in the no-pair approximation, and are now routinely applied on molecular systems. Hence, the next challenge is to go beyond the no-pair approximation by including the quantum-electrodynamics (QED) effects of virtual electron-positron pairs. Such description is needed to recover some properties, even in very simple systems, e.g. the Lamb shift in the Hydrogen atom. In this work we are interested in a one-dimensional model of relativistic hydrogen-like atom using delta-potential interactions. It is motivated by the non-relativistic version of this model which leads to the same ground-state energy and radial wave function as the three-dimensional one [2]. In this model we are able to make accurate QED calculations [3]. After calculating the spectrum of the 1D Dirac operator [4]
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

**Application of DMFT to realistic materials : the example of Ba2IrO4**

Describing the behavior of strongly correlated materials from first principles remains nowadays a challenge in computational condensed matter physics. Indeed, when Coulomb interaction is of the same order of magnitude as the kinetic energy of the electrons, like in materials with open d-shells, the Kohn-Sham band structure obtained within Density Functional Theory (DFT) is often quantitatively -- and even sometimes qualitatively -- wrong. To take strong correlations into account, Dynamical Mean Field Theory (DMFT) has been successfully coupled with DFT, in a scheme dubbed DFT+DMFT, to treat such systems for the past 25 years [1,2].

In this talk, I will introduce how the state-of-the-art DFT+DMFT calculations can be performed, using the example of Ba2IrO4, a compound isostructural to the well-known La2CuO4 [3]: starting from a DFT calculation, a Hubbard-Kanamori-like model Hamiltonian is parametrized [4,5] using Wannier functions [6] and constrained Random Phase Approximation (cRPA) [7]. The model is then solved within DMFT using a continuous time Monte-Carlo solver in the Hybridization expansion (CT-HYB) scheme [8]. The calculated spectral function compares very well with available experimental angle-resolved photo-emission spectroscopy (ARPES) data [3] and sheds light on the complex physics in this material, where strong electron-electron interaction interplays with a large spin-orbit coupling.

This research work not only enhances our comprehension of the low-energy physics of Ba2IrO4 but paves also the way to study other spin-orbit materials with intriguing physics, especially the iridium-based compound Sr2IrO4.

[1] V. I. Anisimov et al 1997 J. Phys.: Condens. Matter 9 7359
[2] A. I. Lichtenstein and M. I. Katsnelson 1998 Phys. Rev. B 57 6884.
[3] S. Moser et al 2014 New J. Phys. 16 013008
[4] J. Hubbard. 1963 Proc. R. Soc. London A 276 238
[5] J. Kanamori 1963 Prog. Theor. Phys. 30 275–289
[6] N. Marzari et al Rev. Mod. 2012 Phys. 84, 1419
[7] F. Aryasetiawan et al 2004 Phys.Rev. B 70, 195104.
[8] P. Seth 2016 Comp. Phys. Com. 200 274-284

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

### Umberto Morellini (CEREMADE, Paris)

**Relativistic electrons coupled with Newtonian nuclear dynamics**

In this talk, we consider a model consisting of differential equations coupling the time evolution of a finite number of relativistic electrons with the Newtonian dynamics of finitely many nuclei, where the former is described by the Bogoliubov-Dirac-Fock (BDF) equation of quantum electrodynamics (QED). The Cauchy problem for this model is addressed, proving a global well-posedness result. We believe that this system can be seen as a first step in the study of molecular dynamics phenomena, when both relativistic and quantum effects have to be taken into account [1].

[1] https://arxiv.org/abs/2310.13501

### Bruno Senjean (ICGM, Montpellier)

**Site-occupation embedding theory and ensemble density functional theory on the Hubbard dimer**

Describing the electronic correlation effects is a key challenge in quantum chemistry and condensed matter physics. Indeed, there is always a trade-off between the accuracy and the computational cost: while wavefunction-based methods are expensive but accurate, reduced-quantity-based methods (such as density functional theory (DFT)) are cheaper but more proned to errors due to approximations of their energy functionals. The holy grail method remains to be found, thus motivating new methodological developments on laboratory-models, due to both their simplicity as well as their physical richness.
In this talk, I will discuss two different in-principle-exact methods, one falling in the scope of embedding approaches that combine a many-body wavefunction with density functionals [1-4], and another that is an extension of density functional theory for the ensembles [5]. I will particularly focus on their implementation on the Hubbard dimer.
The former, called site-occupation embedding theory, aims to make the best compromise between computation cost and accuracy, by treating the correlation explicitly on a small part of the system while the correlation of the rest of the system is described implicitly with a density functionals, for which approximations have been developed on model Hamiltonians.
The second approach, called ensemble-DFT, allows the direct extraction of quantities such as excitations energies, ionisation potentials, electronic affinities and ergo the optical and fundamental gap. In contrast to regular ground-state DFT, the ensemble DFT exactifies the latter quantities that are inherently different from the KS gap (energy difference between the HOMO and LUMO) by a quantity referred to as the derivative discontinuity. In ensemble-DFT, the notion of derivative discontinuity is reformulated as a weight-derivative of the exchange-correlation energy functional of the density, from which functionals are currently developed on simple models [6-10].

[1] B. Senjean, M. Tsuchiizu, V. Robert, E. Fromager. Mol. Phys., 115, 48. (2017)
[2] B. Senjean, N. Nakatani, M. Tsuchiizu, E. Fromager. Phys. Rev. B, 97, 235105 (2018) [3] B. Senjean. Phys. Rev. B, 100, 035136 (2019)
[4] B. Senjean, N. Nakatani, M. Tsuchiizu, E. Fromager. Theor. Chem. Acc. 137, 169 (2018) [5] E. K. U. Gross, L. N. Oliveira, and W. Kohn, Phys. Rev. A 37, 2809 (1988)
[6] B. Senjean, E. Fromager. Phys. Rev. A, 98, 022513 (2018)
[7] B. Senjean, E. Fromager. Int. J. Quantum Chem. 120, e26190 (2020)
[8] C. Marut, B. Senjean et al. Faraday Discussions, 224, 402 (2020)
[9] F. Cernatic, B. Senjean, et al. Top. Curr. Chem. (Z) 380, 4 (2022)
[10] F. Cernatic, P-F. Loos, B. Senjean, and E. Fromager, in preparation.

### Quentin Marecat (ICGM, Montpellier)

**Recursive relations and quantum eigensolver algorithms within modified Schrieffer-Wolff transformations for the Hubbard dimer**

The emergence of quantum computers has rekindled interest in solving the Hubbard model accurately for any dimension, size, regime, and filling. Several quantum algorithms have been proposed for this purpose, targeting both Noisy Intermediate Scale Quantum (NISQ) devices and long-term fault-tolerant quantum devices. These algorithms often employ hybrid classical/quantum strategies, such as the Variational Quantum Eigensolver (VQE), to optimize variational parameters on classical computers while applying parameterized unitary transformations on quantum devices.
One promising approach is the unitary Van-Vleck (VV) similarity transformation[1]. It involves designing a unitary transformation that rotates the Hubbard Hamiltonian into an effective Hamiltonian in the low-energy subspace. This transformation can be used to obtain the ground state (or excited states) of the Hubbard model on a quantum computer. However, finding an explicit expression for the VV generator is often challenging, necessitating truncation or approximations such as the Schrieffer and Wolff (SW) transformation[2].
In this talk, I introduce modifications of the SW generator for the Hubbard dimer, providing both variational and iterative approaches. These modified SW transformations approximate, or even per- form the desired block-diagonalization of the Hubbard dimer at infinite perturbation order, similar to the VV generator. Two quantum algorithms associated with these modified SW transformations for the Hubbard dimer are presented, demonstrating their effectiveness, especially in the strongly interacting regime[3].

[1] I. Shavitt, and L. T. Redmon, "Quasidegenerate perturbation theories. A canonical van Vleck formalism and its relationship to other approaches.", The Journal of Chemical Physics 73, 5711- 5717. (1980).
[2] J.R. Schrieffer, and P.A. Wolff, "Relation between the Anderson and kondo hamiltonians", Physical Review 149, 491 (1966).
[3] Q. Marécat, B. Senjean and M. Saubanère, "Recursive relations and quantum eigensolver algorithms within modified Schrieffer- Wolff transformations for the Hubbard dimer.", Physical Review
B 107, 155110 (2023).

### Long Meng (CERMICS, Paris) 

**A Rigorous Justification Of Mittleman’s Approach To The Dirac–Fock Model**

In this talk, we study the relationship between the Dirac–Fock model and the electron-positron Hartree–Fock model. We justify the Dirac–Fock model as a variational approximation of QED when the vacuum polarization is neglected and when the fine structure constant $\alpha$ is small and the velocity of light $c$ is large. As a byproduct, we also prove, when $\alpha$ is small or $c$ is large, the no-unfilled shells theory in the Dirac–Fock theory for atoms and molecules. The proof is based on some new properties of the Dirac-Fock model.

### David Gontier (CEREMADE, Paris) 

**Phase transition in the Peierls / SSH model**

The Peierls/SSH model is a simple one-dimensional model used to describe molecular chains such as polyacetylene. In this model, we consider a distortion energy between the atoms, and an electronic quantum energy given by a tight-binding model. Peierls showed that it was energetically favorable for the chain to dimerize (hence the structure …=C-C=C-… of polyacetylene). In this talk, we will study the phase diagram of this model, when we add temperature. We show the existence of a critical temperature above which the chain no longer dimerizes. Work in collaboration with Adéchola Kouandé and Éric Séré.

# POSTERS

### Vitaly Gorelov (LSI, Palaiseau)

**TBA**

### Antoine Roux (CEA, Saclay)

**Emulation for (very) large scale PGCM computations of nuclei**

### Pepijn Demol (KU, Leuven)

**TBA**

### Diata Traore (QUBIT-P, Paris)

**TBA**

### Jeremy Morere (LPCT, Nancy) 

**TBA**

### Mauricio Rodríguez-Mayorga (Neel Institute, Grenoble)

**Relativistic effects on the two-electron Harmonium atom**

The non-relativistic Harmonium atom is a model system where parabolic confinement ($1⁄2\omega^2 r^2$) replaces the Coulombic ($-Z/r$) electron-nucleus interaction [1-4]. Varying the confinement strength (ω) enhances the different types of electronic correlation effects. Large (small) ω values make the weak (strong) electronic correlation dominant [1,3]. Consequently, this model system has served as a tool in the development and benchmarking of methods [5,6]. Moreover, analytic solutions for the two-electron Harmonium atom can also be obtained for certain ω values [4], which provides us with wavefunctions for two electrons that are explored to better understand the repercussions of electronic correlation effects.
In this work, we explore numerically the role of relativistic effects on the two-electron Harmonium. Our results indicate that only for the large $\omega$ values scalar relativistic effects are important and lead to a reduction of the total energy accompanied by changes in the electronic structure (e.g. a shrinking of the radial electronic density P(r)).

[1] Cioslowski, J., & Pernal, K. (2000). The ground state of harmonium. J. Chem. Phys., 113, 8434-8443. 
[2] Cioslowski, J. (2018). One-Electron Densities of Harmonium Atoms. In Theoretical and Quantum Chemistry at the Dawn of the 21st Century (pp. 349-380). Apple Academic Press.
[3] Cioslowski, J. (2018). Natural orbitals of the ground state of the two-electron harmonium atom. Theo. Chem. Acc, 137, 173.
[4] Taut, M. (1993). Two electrons in an external oscillator potential: Particular analytic solutions of a Coulomb correlation problem. Phys. Rev. A, 48, 3561.
[5] Rodríguez-Mayorga, M., Ramos-Cordoba, E., Via-Nadal, M., Piris, M., & Matito, E. (2017). Comprehensive benchmarking of density matrix functional approximations. Phys. Chem. Chem. Phys., 19, 24029.
[6] Jana, S., Behera, S. K., Śmiga, S., Constantin, L. A., & Samal, P. (2021). Improving the applicability of the Pauli kinetic energy density based semilocal functional for solids. New J. Phys., 23, 063007.


 
