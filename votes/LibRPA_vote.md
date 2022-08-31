# A Vote for New Project: LibRPA

## Proposal

LibRPA is an implementation of many-body perturbation methods at the level of random phase approximation (RPA) using space-time algorithm. For more information, see the [original repository](https://github.com/Srlive1201/LibRPA).

Many-body perturbation methods based on Green’s function have demonstrated great competence in accurate first-principle simulation of electronic structure for materials. Among them, adiabatic-connection fluctuation-dissipation theorem (ACFDT) within RPA offers an exchange-correlation energy which is almost self-interaction free and seamlessly incorporates the long-range dispersion interaction. It has proved successful in describing cohesive energy of bulk solids, surface adsorption, etc. For band structure calculation, the GW method is able to give band energies in close agreement with photoelectron measurements without any tuning parameters, and hence allows for a more rigorous prediction of optoelectronic properties.

However, the application of these advanced methods to large systems is hampered by the $\mathcal{O}(N^4)$ complexity and large prefactor of the conventional algorithm to compute response function and self-energy. To overcome the obstacle, LibRPA implemented the efficient space-time algorithm and exploits the two-center localized resolution-of-identity (LRI) technique in the numerical atomic orbital (NAO) basis set. These treatments lead to an $\mathcal{O}(N^2)$ scaling in computing correlation (self) energy. As a post-SCF package, LibRPA can be interfaced with existing ab initio software based on NAO framework.

LibRPA is written in C++ and authored by Rong Shi and Min-Ye Zhang. 

At the current stage, LibRPA can readily compute the RPA correlation energy in $\mathcal{O}(N^2)$ for system with hundreds of atoms. The exact energy needs to be computed from the SCF code. Interfaces with ABACUS and FHI-aims have been implemented. The combined exchange-correlation energy can be used as training data for machine learning methods such as DeePKS.

## Deadline

The vote will be open for at least 6 days unless there is an objection.

## Scope

TOC MEMBERS

## Result