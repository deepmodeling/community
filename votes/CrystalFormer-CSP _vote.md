
# A Vote for New Projects: CrystalFormer-CSP

## Proposal

Crystal structure prediction (CSP) is a fundamental problem in materials science with broad applications spanning from superconductors to battery materials. The goal of CSP is to predict the spatial arrangement of atoms given the chemical formula, which is notoriously difficult due to the complex interplay between chemical bonding, geometric constraints, and thermodynamic stability.

**CrystalFormer-CSP** employs a three-stage approach for CSP, a pretrained autoregressive transformer samples initial crystal structure candidates based on the given chemical formula; then, MLFF is used to bring these structures to lower energy states via structure relaxation; finally, the relaxed candidates are ranked according to their energy above hull, providing an assessment of their thermodynamic stability.

The core of this workflow is a generative model that models the conditional probability of crystal structure given a chemical formula in the same fashion as sampling answers given language prompts. CrystalFormer-CSP is an autoregressive transformer designed for generating inorganic crystal structures with space group symmetries. The model takes as input a chemical formula and outputs the crystal structure.

For more information, see the [original repository](https://github.com/zdcao121/CrystalFormer-CSP)

## Deadline

The vote will be open for at least 6 days unless there is an objection.

## Scope

TOC MEMBERS.
