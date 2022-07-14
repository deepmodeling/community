# A Vote for New Projects: DeepH-pack

## Proposal

DeepH-pack is the official implementation of the Deep Hamiltonian (DeepH) method described in the paper [*Deep-learning density functional theory Hamiltonian for efficient ab initio electronic-structure calculation*](https://www.nature.com/articles/s43588-022-00265-6) and in the [Research Briefing](https://www.nature.com/articles/s43588-022-00270-9). For more information, see the [documentation](https://deeph-pack.readthedocs.io) and the [original repository](https://github.com/mzjb/DeepH-pack).

DeepH method employs a graph neural network to represent the mapping from the atomic structure of a material to the density functional theory (DFT) Hamiltonian, from which all the electronic-related physical quantities in the single-particle picture can be predicted, including the band structure, Berry phase and physical responses to external fields. Importantly, DeepH takes full advantage of the 'nearsightedness' principle of electronic matter and can properly deal with covariance (i.e. equivariance) of the Hamiltonian matrix by basis transformation, which ensures good generalizability. By learning from DFT and then making independent predictions, DeepH can bypass the computationally most demanding part of a DFT simulation (namely the self-consistent field iterations) and, thus, substantially improve the efficiency of ab initio electronic-structure calculations and greatly extend the scope of first-principles materials research.

## Deadline

The vote will be open for at least 6 days unless there is an objection.

## Scope

TOC MEMBERS.

## Result

See also https://github.com/deepmodeling/community/pull/12 
