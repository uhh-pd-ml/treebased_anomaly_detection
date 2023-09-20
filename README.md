# Tree-Based Algorithms for Weakly Supervised Anomaly Detection

Weakly supervised methods are producing promising results for model agnostic anomaly detection for LHC data. Current benchmarks largely use small, tabular feature sets as deep neural networks are sensitive to noise features in this extreme weakly supervised regime. As tree-based models are the state of the art for tabular data in machine learning, we propose their use for weakly supervised anomaly detection. 

## Citation

*"Back to the Roots: Tree-Based Algorithms for Weakly Supervised Anomaly Detection"*,  
By Thorben Finke, Marie Hein, Gregor Kasieczka, Michael Krämer, Alexander Mück, Parada Prangchaikul, Tobias Quadfasel, David Shih, and Manuel Sommerhalder. <br>
[Add_arxiv_number_later]( 	
https://doi.org/10.1103/PhysRevD.106.055006). 


## Reproduction of paper results

The code for the results of this paper can be found in the two submodules of this repository: 

- *BackToTheRoots* contains the code for the main part of the paper, as well as appendix C ("Ensembling")
- *treebased_ad* contains the code for appendices A ("Comparisons of different BDT architectures") and B ("Uninformative features, rotational
invariance, and tabular data")

More detailed instructions on how to reproduce the results is contained within the respective submodules. 