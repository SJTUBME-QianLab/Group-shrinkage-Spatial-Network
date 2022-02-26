This repository holds the code for the paper

**Group-Shrinkage Feature Selection with a Spatial-Embedding Network for Mining DNA Methylation Data**

All the materials released in this library can ONLY be used for RESEARCH purposes and not for commercial use.

The authors' institution (Biomedical Image and Health Informatics Lab, School of Biomedical Engineering, Shanghai Jiao Tong University) preserve the copyright and all legal rights of these codes.

# Author List

Xinlu Tang, Zhanfeng Mo, Xiaohua Qian  *

# Abstract

Identifying disease-related biomarkers from high-dimensional DNA methylation data helps in reducing the early screening costs and inferring pathogenesis mechanisms. Good discovery results have been achieved through methods of spatial correlation of methylation sites, group-based regularization, and network constraints. However, these methods still have some key limitations as they cannot exclude isolated differential sites, and they only consider adjacent site ordering. Therefore, we propose a group-shrinkage feature selection algorithm guided by a spatial-embedding network, to encourage the selection of clustered methylation sites and discourage the selection of isolated differential sites through the exploitation of biased correlation based on sample deviation. To the best of our knowledge, this is the first published work to address the exclusion of isolated methylation sites in mining DNA methylation data. Specifically, our algorithm promotes the group shrinkage in virtue of a network structure constraint, penalizing weakly-correlated isolated methylation sites. The spatial-embedding network is constructed based on detailed spatial correlation information of DNA methylation sites, where this information accounts for the uneven site distribution. The experimental simulations and applications demonstrated that the proposed method outperforms the state-of-the-art regularization methods, especially in rejecting isolated methylation sites. Overall, we provide an efficient method for biomarker candidates discovery in DNA methylation data. This method exhibits an enhanced reliability due to biological prior integration, and thus has a promising potential for clinical applications.
