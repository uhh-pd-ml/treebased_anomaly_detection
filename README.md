# Tree-Based Algorithms for Weakly Supervised Anomaly Detection

This repository contains the code for the following paper:

*"Back to the Roots: Tree-Based Algorithms for Weakly Supervised Anomaly Detection"*,  
By Thorben Finke, Marie Hein, Gregor Kasieczka, Michael Krämer, Alexander Mück, Parada Prangchaikul, Tobias Quadfasel, David Shih, and Manuel Sommerhalder. <br>
[arXiv:2309.13111](https://arxiv.org/abs/2309.13111). 

## Reproduction of paper results

The code for the results of this paper can be found in the two submodules of this repository: 

- *BackToTheRoots* contains the code for the main part of the paper, as well as appendix C ("Ensembling")
- *treebased_ad* contains the code for appendices A ("Comparisons of different BDT architectures") and B ("Uninformative features, rotational
invariance, and tabular data")

More detailed instructions on how to reproduce the results can be found in the README of the respective submodule.

Note that cloning this repository including the dataset will require `git-lfs` to be installed on the system.
## Dataset

In the "dataset" folder, you can also find the dataset used in this paper. It is a version of the LHC Olympics RnD dataset containing high-level features of two jets similar to the high-level feature sets included in https://zenodo.org/record/6466204. However, the subjettiness features used there are expanded to include $\tau_N^\beta$ with $1 \le N \le 9$ as well as $\beta \in [0.5, 1, 2]$.

For the reproduction of results for appendices A and B, pre-processed samples as well as pre-trained model files also exist inside the `treebased_ad` submodule.