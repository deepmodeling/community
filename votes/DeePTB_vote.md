# A Vote for New Projects: DeePTB

## Proposal
**DeePTB** is a Python package that adopts the deep learning method to construct electronic tight-binding (TB) Hamiltonians using a minimal basis.
With a neural network environmental correction scheme, **DeePTB** can efficiently predict TB Hamiltonians for large-size unseen structures with *ab initio* accuracy after training with *ab initio* eigenvalues from smaller sizes. 
This feature enables efficient simulations of large-size systems under structural perturbations such as strain, which is crucial for semiconductor band gap engineering. Furthermore, DeePTB offers the ability to perform efficient and accurate finite temperature simulations, incorporating both atomic and electronic behaviour through the integration of molecular dynamics (MD). Another significant advantage is that using eigenvalues as the training labels makes DeePTB much more flexible and independent of the choice of various bases (PW or LCAO) and the exchange-correlation (XC) functionals (LDA, GGA and even HSE) used in preparing the training labels. In addition, **DeePTB** can handle systems with strong spin-orbit coupling (SOC) effects.
These capabilities make **DeePTB** adaptable to various research scenarios, extending its applicability to a wide range of materials and phenomena and offering a powerful and versatile tool for accurate and efficient simulations.


In summary, **DeePTB** offers the following key features:
- Slater-Koster-like parameterization with customizable radial dependence.
- Orthogonal basis tight-binding Hamiltonian with a customizable number of basis and bond neighbours.
- Incorporation of local atomic and bond environmental corrections using symmetry-preserving neural networks.
- Utilization of an efficient gradient-based fitting algorithm based on autograd implementation.
- Flexibility and independence from the choice of bases and XC functionals used in preparing the training labels.
- Ability to handle systems with strong spin-orbit coupling effects.
- Efficient and accurate finite temperature simulations through integration with molecular dynamics.

The code is the official implementation of the DeePTB paper: [*DeePTB: A deep learning-based tight-binding approach with ab initio accuracy*](https://arxiv.org/abs/2307.04638), which is currently available on GitHub at: https://github.com/QG-phy/deeptb.

## Deadline
The vote will be open for at least 5 days unless there is an objection.

## Scope
TOC MEMBERS.

## Result
