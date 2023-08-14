# Week 7

Topic: The Canonical Correlation Analysis Family in Self-Supervised Learning

Keynote Speaker: Xunyi Jiang, Langtian Ma

Time: Aug 3, 19:30 - 21:00 pm

Venue: Lecture Hall 3, 302 (SUSTech)

Online Link: [TencentMeeting](https://meeting.tencent.com/dm/ciI4lpALLhxz)

## Compendium

I. Traditional CCA

- Generalized CCA framework
- Traditional Nonlinear CCA
- A compressed representatoin approach for CCA
- Kernel CCA



II. Deep CCA and its variates

- Deep canonical correlation analysis
- Deep canonically correlated autoencoders



III. CCA in Self-supervised Learning

There are 4 major categories of self-supervise methods, including information maximization, clustering, distillation techniques, and contrastive method. In this week, I will introduce 3 methods(W-MSE/Barlow Twins/VICReg) lying in information maximization, and 2 methods(SeLa/SwAV) in clustering.

The story line is as following:

- Overview of SSL methods
- Information maximization methods: W-MSE/Barlow Twins/VICReg
- Clustering methods: SeLa/SwAV
- Summary of these methods

## Material

Slides [1](https://nbviewer.org/github/niusj03/23summer/blob/master/content/docs/pdfs/Week7_Jiang.pdf) and [2](https://nbviewer.org/github/niusj03/23summer/blob/master/content/docs/pdfs/Week7_Ma.pdf) for Canonical Correlation Analysis Family from Xunyi Jiang and Langtian Ma.

## References

1. Breiman, L et al, [Estimating Optimal Transformations for Multiple Regression and Correlation](https://users.soe.ucsc.edu/~draper/eBay-Google-2013-breiman-friedman-1985.pdf)
2. Painsky A et al, [Nonlinear Canonical Correlation Analysis:A Compressed Representation Approach](https://www.mdpi.com/1099-4300/22/2/208)
3. D. R. Hardoon et al, [Canonical correlation analysis: An overview with application to learning methods](https://ieeexplore.ieee.org/abstract/document/6788402/)
4. Andrew, G et al[Deep canonical correlation analysis](https://proceedings.mlr.press/v28/andrew13.html)
5. Wang, W et al[On deep multi-view representation learning](http://proceedings.mlr.press/v37/wangb15.html)

6. A. Ermolov, A. Siarohin, E. Sangineto, and N. Sebe, [Whitening for Self-Supervised Representation Learning](https://arxiv.org/pdf/2007.06346.pdf)

7. J. Zbontar, L. Jing, I. Misra, Y. Lecun, and S. Deny, [Barlow Twins: Self-Supervised Learning via Redundancy Reduction](https://arxiv.org/pdf/2103.03230.pdf)

8. A. Bardes, J. Ponce, and Y. Lecun,  [VICREG: VARIANCE-INVARIANCE-COVARIANCE RE- GULARIZATION FOR SELF-SUPERVISED LEARNING](https://arxiv.org/pdf/2105.04906.pdf)

9. Y. Asano, C. Rupprecht, and A. Vedaldi, [SELF-LABELLING VIA SIMULTANEOUS CLUSTERING AND REPRESENTATION LEARNING](https://arxiv.org/pdf/1911.05371.pdf)

10. M. Caron, I. Misra, J. Mairal, P. Goyal, P. Bojanowski, and A. Joulin, [Unsupervised Learning of Visual Features by Contrasting Cluster Assignments](https://arxiv.org/pdf/2006.09882.pdf)
