---
title: "Presentations"
date: 2020-12-02 09:06
draft: false
---

# ORAL PRESENTATIONS

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

**Finite Uniform Electron Gases**

The Uniform Electron Gas (UEG), which was introduced almost a century ago by Thomas and Fermi, has become one of the most widely used fundamental models in quantum physics, and its properties have been studied by many of the leading figures in the field.  In its simplest form, it is characterised by a single parameter ρ — the mean number of electrons per unit volume — and its energy per unit volume and other properties are then computable functions of ρ.  One of its key weaknesses of the UEG is that it is an infinite system and this limits its accuracy when it is applied, for example, to finite molecular systems.

In recent years, there has been interest in the Finite Uniform Electron Gases (FUEGs) that are created when a finite number of electrons are confined to a finite space in which all points are equivalent.  The simplest examples of this arise when n electrons are confined to a sphere and we have called this system n-ringium, n-spherium and n-glomium, respectively, when the sphere is 1-, 2- or 3-dimensional.  The Schrödinger equations for 2-ringium, 2-spherium and 2-glomium are quasi-exactly solvable and admit simple polynomial solutions for certain values of the spherical radius R.

I will present a pedagogical introduction to FUEGs, highlight some of the key features of their exact solutions, and note some of the important questions that remain unanswered.

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

**An introduction to Dynamical Mean-Field Theory**

The "famous" Hubbard model was conceived in the 1960s [1,2,3] to get
insight into how the Coulomb interactions between conduction electrons
(for instance, in 3d transition metals) may affect "their motion" on a
lattice, and thus induce insulating or magnetic properties in a solid.
In its simplest form, the one-orbital (or single-band) Hubbard model
contains only a hopping term t between neighboring sites and an on-site
repulsive interaction term U. And yet, key insights into the Mott
metal-insulator transition (MIT) --  when the Coulomb repulsion can turn
a system insulating [4] -- can already be obtained, especially since the
advent of Dynamical Mean-Field Theory (DMFT) around 1990 [5,6].

DMFT can be seen as a quantum many-body extension of classical
mean-field approaches. Its power is the non-perturbative description of
correlations, which allows treating arbitrary interaction strengths:
DMFT can then capture both the Fermi liquid and the Mott insulator, and
provides a spatial mean-field description of the transition between them
[7].

In this talk, we will provide an introduction to the DMFT formalism,
explain how the method can be implemented in practice and discuss the
MIT and the phase diagramm of the Hubbard model on an infinite Bethe
lattice (where DMFT equations are exact).

[1] J. Hubbard, Proc. R. Soc. London, Ser. A 276, 238 (1963); J.
Hubbard, Proc. R. Soc. London, Ser. A 277, 237 (1964).
[2] M.C. Gutzwiller, Phys. Rev. Lett. 10, 159 (1963)
[3] J. Kanamori, Progress of Theoretical Physics 30, 275 (1963)
[4] N. F. Mott and R. Peierls, Proceedings of the Physical Society 49,
72 (1937); N. F. Mott, Proceedings of the Physical Society. Section A
62, 416 (1949).
[5] W. Metzner and D. Vollhardt, Phys. Rev. Lett. 62, 324 (1989).
[6] A. Georges and G. Kotliar, Phys. Rev. B 45, 6479 (1992)
[7] A. Georges, G. Kotliar, W. Krauth, and M. J. Rozenberg, Rev. Mod.
Phys. 68, 13 (1996).

### Nicolas Laflorencie (LPT, Toulouse)

**Topological and quantum critical properties of the interacting Majorana chain model**

Despite our very good understanding of several models in one dimension involving interacting (Dirac) fermions, the case of Majorana fermions has remained relatively unexplored. This is probably due to the fact that Majorana particles are not found as elementary objects in nature. Nevertheless, 20 years ago, in the context of modeling p-wave superconducting wires, Alexei Kitaev proposed a very influential yet simple toy model in which unpaired Majorana fermions can appear as edge states. In this talk I will present the basics of this problem and explore the non-trivial effects of interactions in such a system, building on DMRG and self-consistent mean-field approaches. If time permits, I may also touch on disorder effects...

### Pieter Van Isacker (GANIL, Caen)

**Symmetries of nuclear models**

Symmetry considerations have played an important role in the development of the interacting
shell model as well as the geometric collective model of the atomic nucleus. On the one hand,
the nuclear many-body problem, formulated in terms of interacting nucleons in a spherical
harmonic oscillator, has two analytic solutions, namely if the interaction is of the pairing or of
the quadrupole type, giving rise to an underlying SU(2) or SU(3) symmetry, respectively. On
the other hand, the collective description of the nucleus by way of phonon-like excitations
(bosons) of a liquid drop leads to the U(5) symmetry of a harmonic oscillator in five
dimensions. A connection between both views of the nucleus can be obtained through the
interacting boson model, whose spectrum-generating algebra is U(6).
In this talk I will review historical developments of several symmetry models of the atomic
nucleus and discuss applications of relevance to current studies in nuclear structure.

### Alexander Tichai (TU, Darmstadt)

**Nuclear superfluidity: the Pairing Hamiltonian as a many-body testbed**

Atomic nuclei away from shell closures are characterized by strong static correlations that are (partly) linked to the emergence of superfluidity responsible for characteristic patterns in the nuclear phenomenology, e.g. odd-even mass staggering along isotopic chains. While the onset of superfluidity is accompanied by a breakdown of symmetry-conserving Hartree-Fock theory, the corresponding pairing correlations can be efficiently grasped by spontaneously breaking (and restoring) particle-number symmetry.

In this talk I will discuss the Pairing Hamiltonian as a schematic model for superfluidity. Its exact solution for arbitrary system size is available from the seminal work of Richardson from the 1960s [1]. Since then it has been frequently used as a testbed in (nuclear) many-body theory.
I will review a collection of frameworks including mean-field theory, many-body perturbation theory [2] and coupled cluster theory [3,4], and highlight the role of the symmetry restoration.
Furthermore, I will present recent emulator developments that enable robust interpolation/extrapolation in the coupling value [5]. I will conclude with an overview of particle-number-broken many-body frameworks applied in realistic first-principles simulations of atomic nuclei as motivated by their success for the Pairing Hamiltonian [6,7].

[1] R. Richardson, Phys. Lett. 3, 277 (1963)
[2] D. Lacroix, D. Gambacurta,  Phys. Rev. C 86, 014306 (2012)
[3] T. Henderson, G. E. Scuseria, J. Dukelsky, A. Signoracci, T. Duguet, Phys. Rev. C 89, 054305 (2014)
[4] Y. Qiu, T. M. Henderson, J. Zhao, G. E. Scuseria, J. Chem. Phys. 147, 064111 (2017)
[5] M. Companys Franzke, A. Tichai, K. Hebeler, A. Schwenk, arXiv:2302:08373 (2023)
[6] A. Tichai, P. Arthuis, T. Duguet, H. Hergert, V. Somà, R. Roth, Phys. Lett. B 786, 195 (2018)
[7] A. Tichai, P. Demol, T. Duguet, arXiv:2307:15619 (2023)

### Denis Lacroix (IN2P3, Orsay)

**Exploring the richness of the Lipkin Model and its extensions: from nuclear to neutrino physics and quantum computing**

I will discuss the basic ingredient of the Lipkin model consisting of a set of permutation invariant 2-level systems occupied by fermions.
Due to its symmetry property, this model can be easily solved even for many particles. Still, it contains interesting physical
properties, like a quantum phase transition. Naturally, this model serves as a benchmark for testing
many-body approaches to treat static and dynamical properties of complex many-body systems. Illustrations of the application
of this model or its extensions will be shown during the talk in various fields. Due to its intrinsic 2-level system nature, it also appears useful
to test quantum algorithms using qubits. A few examples of recent progress in quantum computers will be presented.

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

### Diata Traore (QUBIT-P, Paris)

**One-dimensional model systems for understanding and development of the density-based basis-set correction method**

In our recent works [1,2], we proposed a two-electron one-dimensional model to help the development of correlated methods for computation of accurate energies and molecular properties. For that, we represent the electron-electron interaction by simple formulations regarding the quantity of interest.
On one side, a δ-dirac interaction combined with a Hermite-Gaussian basis-set helped development of methods for correlation energies and properties related to the ground-state solution. On the other side, we access bounded excited-states using a one-dimensional two-electron Hooke’s atom.
We illustrate the applications of this model with our work on the density-based basis-set correction.

[1] D. Traore, E. Giner, J. Toulouse, Journal of Chemical Physics 156, 044113 1- 13 (2022).
[2] D. Traore, E. Giner, J. Toulouse, Journal of Chemical Physics 158, 234107 1-9 (2023).

### Lucia Reining (LSI, Palaiseau)

**Zero, one, many: the Hubbard dimer with two electrons in many-body perturbation theory**

Many-body perturbation theory is today part of the standard toolbox of first principles calculations. Most often, first-or at most second-order approximations are used. Still, calculations for real materials can be very involved. Moreover, numerous open questions remain, not least because for both total energies and spectra we do not have enough thorough benchmarks. This explains why, for example, after decades of GW calculations the best choice for the Green's function G and for the screened Coulomb interaction W to build the GW self-energy is still a matter of debate.

One way to contribute to filling this gap is the use of simple solvable models. Here, we will examine results for the symmetric half-filled Hubbard dimer, which allows us to cover the full range from vanishing to strong correlation. Our aim is to design an optimal way to use MBPT, remaining at low order, with a particular focus on the design of effective interactions. This will include combinations of MBPT with time-dependent density functional theory.

We will illustrate how the simple model allows us to benchmark, and also to understand and to improve results. Finally, we will also discuss limitations of the extrapolation of results from the Hubbard dimer to real systems.
 
### David Gontier (CEREMADE, Paris) 

**Phase transition in the Peierls / SSH model**

The Peierls/SSH model is a simple one-dimensional model used to describe molecular chains such as polyacetylene. In this model, we consider a distortion energy between the atoms, and an electronic quantum energy given by a tight-binding model. Peierls showed that it was energetically favorable for the chain to dimerize (hence the structure …=C-C=C-… of polyacetylene). In this talk, we will study the phase diagram of this model, when we add temperature. We show the existence of a critical temperature above which the chain no longer dimerizes. Work in collaboration with Adéchola Kouandé and Éric Séré.

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

### Aleksandra Petkovic (LPT, Toulouse)

**Dissipative impurity dynamics in one dimensional quantum liquids**

In the first part of the talk we will consider a system of bosons with contact interaction in one dimension, the Lieb-Liniger model. Then, we will study the motion of a slow impurity (a foreign particle) through this system. While at zero temperature the impurity motion is frictionless, at low temperatures finite friction appears due to scattering off thermally excited quasiparticles. We will derive analytical results for the friction force within a microscopic theory and uncover interesting regimes of the impurity dynamics.

### Marie Labeye (ENS, Paris)

**Time dependent models for strong field physics**

# POSTERS

### Vitaly Gorelov (LSI, Palaiseau)

**Exploring electronic interactions and charge transfer in photovoltaic systems via a model Hamiltonian**

### Antoine Roux (CEA, Saclay)

**Emulation for (very) large scale PGCM computations of nuclei**

### Jeremy Morere (LPCT, Nancy) 

**Arbitrariness of the degree of complexity of superoperators in the EOM formulation of TD-DFT objects**

When describing the reorganization of electronic structure induced by the interaction between light and matter, two objects are particularly crucial: the one-body difference density matrix and the one-body transition density matrix. The primary motivation that led us to focus on these two matrices is as follows: the first one allows us to calculate the difference in expectation value of one-body operators between two electronic states without needing these two states explicitly. The second one provides us expectation values associated with transition properties.
If we had access to the exact eigenstates of the stationary Hamiltonian, we could write an exact transition operator. In the equation-of-motion formalism (EOM), it is possible to prove that an arbitrary number of nested commutators, called superoperators, involving this exact operator and second quantization operators allows us to write the exact expression of our two density matrices of interest.
As time-dependent density-functional theory method (TD-DFT) cannot give access to the exact transition operator, writing an approximate expression for these matrices involves the use of a substitution operator. This operator is inspired by the operator that generates the central equation of the Random Phase Approximation method. The use of superoperators in TD-DFT is enabled by the structure of its fundamental equation and its physical interpretation. Interestingly, there exists a structural and interpretational identity between the fundamental equations of TD-DFT and Bethe-Salpeter equation (BSE) methods. The development carried out with the substitution operator in TD-DFT is also applicable to BSE.
We intend to demonstrate and justify that, in this specific context, the choice of the complexity degree of the superoperators might not be arbitrary — unlike with an exact transition operator — and require a minimum degree of complexity for superoperators, in order to express the two density matrices.


[1] Thibaud Etienne. A comprehensive, self-contained derivation of the one-body density matrices from single-reference excited-state calculation methods using the equation-of-motion formalism, arxiv repository 1811.08849v15. 2018.
[2] Andrei Ipatov, Felipe Cordova, Lo ̈ıc Joubert Doriol, and Mark E. Casida. Excited-state spin- contamination in time-dependent density-functional theory for molecules with open-shell ground states. Journal of Molecular Structure: THEOCHEM, 914(1-3):60–73, November 2009.
[3] Xavier Blase, Ivan Duchemin, and Denis Jacquemin. The Bethe–Salpeter equation in chemistry: relations with TD-DFT, applications and challenges. Chemical Society Reviews, 47(3):1022–1043, 2018.

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

### Jack Thomas (LMO, Orsay) 

**Friedel oscillations in the reduced Hartree-Fock model**

When a defect potential is placed in a material, the material rearranges and the total potential at long-range is screened by the electrons. In the finite temperature reduced Hartree-Fock model, small defects are completely screened [1]; the total change in potential decays exponentially. On the other hand, in metals at zero temperature, the presence of the Fermi-surface introduces non-analytic behaviour into the independent-particle susceptibility, leading to what are known as Friedel oscillations; the total potential oscillates and decays algebraically. In this talk, we will show how this rate of decay depends on the properties of the Fermi-surface. Joint work with Antoine Levitt. 

[1] Antoine Levitt, Archive for Rational Mechanics and Analysis 238 (2020) 901–927 

### Long Meng (CERMICS, Paris) 

**A Rigorous Justification Of Mittleman’s Approach To The Dirac–Fock Model**

In this talk, we study the relationship between the Dirac–Fock model and the electron-positron Hartree–Fock model. We justify the Dirac–Fock model as a variational approximation of QED when the vacuum polarization is neglected and when the fine structure constant $\alpha$ is small and the velocity of light $c$ is large. As a byproduct, we also prove, when $\alpha$ is small or $c$ is large, the no-unfilled shells theory in the Dirac–Fock theory for atoms and molecules. The proof is based on some new properties of the Dirac-Fock model.

