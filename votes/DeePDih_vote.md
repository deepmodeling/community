
# A Vote for New Projects: DeePDih

## Proposal

DeePDih is a Python package that perform on-the-fly dihedral parametrization of classical force-field, with any energy calculator (ForceField, NNP or QM).
With the accuracy and efficiency of NNPs, **DeePDih** can efficiently optimize the dihedral parameters of any biomolecule, greatly enhancing the accuracy of MM simulations, such as FEP calculations. **DeePDih** now reaches its best performance with the fine-tuned **DPA-2-TB model**, which is obtained from OpenLAM Q1 version's pretraining and fine-tuned with a drug molecule dataset constructed by active learning.

This on-the-fly force field optimization approach addresses the key challenges of high computational expense and labor-intensive parameter library construction, paving the way for more efficient and broadly applicable force field optimization.

In summary, **DeePDih** offers the following key features:

* Molecule Fragmentation: Decompose complex organic molecules into fragments containing at least one rotamer using a fragmentation method.
* Flexible Scan: Perform flexible scans on the high-accuracy potential surface (QM or NNP) around each rotamer for every fragment. This involves fixing the dihedral angle of the rotatable bond and optimizing bond lengths and angles to obtain relaxed conformations.
* Fragment Cataloging: Catalog each fragment's fingerprint in the fragment library to identify the dihedral parameters that need optimization.
* Parameter Optimization: Catalog each fragment's fingerprint in a fragment library to identify the dihedral parameters that need optimization. Optimize MM dihedral parameters to minimize the relative error between high-accuracy (QM or NNP) and MM potential surfacesc. The fragments' fingerprints are based on molecular topologies using a node-embedding-based approach, ensuring that similar local environments share identical fingerprints.
* Parameter Matching: Match the optimized parameters to complex organic molecules using fingerprints.

The code is the implementation of the DeePDih manuscript: [Efficient and Precise Force Field Optimization for Biomolecules Using DPA-2](https://dp-filetrans-bj.oss-cn-beijing.aliyuncs.com/changjunhan/pdfs/DPA2_FEP_Manuscript_v1.pdf). It is currently available on GitHub at: [https://github.com/WangXinyan940/DeePDih](https://github.com/WangXinyan940/DeePDih). The manuscript will be released on arXiv when the repo moves to DeepModeling.

## Deadline

The vote will be open for at least 6 days unless there is an objection.

## Scope

TOC MEMBERS.

## Result

Approved by:

wanghan-iapcm
