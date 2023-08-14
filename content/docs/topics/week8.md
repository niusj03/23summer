# Week 8

Topic: The simple summary of Self-Supervised Learning & Masked Image Model in Self-Supervised Learning Family in Self-Supervised Learning

Keynote Speaker: Shengjie Niu, Zebin Yun

Time: Aug 10, 19:30 - 21:30 pm

Venue: Lecture Hall 3, 302 (SUSTech)

Online Link: [TencentMeeting](https://meeting.tencent.com/dm/ciI4lpALLhxz)

## Compendium

I. Stage-1: Verstile developments among the field of SSL

- InstDisc proposed new pretext task of instance-level discrimination.
- CPC employed the predictive pretxt task on SSL, so as to realize wide applicability.
- InvaSpread utilize the negative pairs among the batch samples.
- CMC first proposed the utilization from the perspective of mutiview.
- Stage conclusion in terms of objective functions, pretext tasks and construction of negative pairs.

II. Stage-2: Two distinguished methodologies lead the trend

- MoCo proposed momentum encoder and query dictionary for contrastive Self-Supervised Learning.
- SimCLR proposed a simple but effective framework to claim the function of augmentation strategies and project head.
- MoCo v2 and SimCLR v2
- SeLa first compared the instance with clustering prototypes instead of negative pairs, and propose a new component of predict head.
- SwAV achieve the promising performance with sway mode of SeLa, leading to the following trend of learning without negative pairs.

III. Stage-3: Learning without negative pairs

- BYOL: first Self-Supervised Learning literature finished its training totally without negative pairs.
- SimSiam summarized and analysed the function of all kinds of components, resulting in a structure-easy but effective model.

**Significant Timepoint: (2020.10) Vision Transfermer(ViT) brought large impacts on computer vision field and promoted the progress of generative vision model based on ViT.**

IV. Masked Image Model (MIM) family in Self-Supervised Learning

- BEiT trained transformer-based model to reconstruct the input in the form of token-level label (In need of pre-trained tokenizer)
- MAE trained transformer-based model to reconstercut the input in pixel level
- SimMIM summarized some MIM models and found a series of simple but effective components.

## Material

[Slides & Source Code](https://www.overleaf.com/read/dshmrcjjvyfk) for Week-8 seminar from Shengjie Niu.

[Big Picture](https://nbviewer.org/github/niusj03/23summer/blob/master/content/docs/pdfs/BigP.pdf) from Shengjie Niu.


## Reference

1. Z. Wu et al, [Unsupervised Feature Learning via Non-Parametric Instance Discrimination](https://arxiv.org/pdf/1805.01978.pdf).

2. A. Oord et al, [Representation Learning with Contrastive Predictive Coding](https://arxiv.org/abs/1807.03748).

3. M. Ye et al, [Unsupervised Embedding Learning via Invariant and Spreading Instance Feature](https://arxiv.org/abs/1904.03436).

4. Y. Tian et al, [Contrastive Multiview Coding](https://arxiv.org/abs/1906.05849).

5. K. He et al, [Momentum Contrast for Unsupervised Visual Representation Learning](https://arxiv.org/abs/1911.05722).

6. T. Chen et al, [A Simple Framework for Contrastive Learning of Visual Representations](https://arxiv.org/abs/2002.05709).

7. X. Chen et al, [Improved Baselines with Momentum Contrastive Learning](https://arxiv.org/abs/2003.04297).

8. T. Chen et al, [Big Self-Supervised Models are Strong Semi-Supervised Learners](https://arxiv.org/abs/2006.10029).

9. Y. Asano et al, [Self-labelling via simultaneous clustering and representation learning](https://arxiv.org/abs/1911.05371).

10. M. Caron et al, [Unsupervised Learning of Visual Features by Contrasting Cluster Assignments](https://arxiv.org/abs/2006.09882).

11. J. Grill et al, [Bootstrap your own latent: A new approach to self-supervised Learning](https://arxiv.org/abs/2006.07733).

12. X. Chen et al, [Exploring Simple Siamese Representation Learning](https://arxiv.org/abs/2011.10566).

13. M. Caron et al, [Emerging Properties in Self-Supervised Vision Transformers](https://arxiv.org/abs/2104.14294).

14. B. Hao et al, [BEiT: BERT Pre-Training of Image Transformers](https://arxiv.org/abs/2106.08254).

15. K He et al, [Masked Autoencoders Are Scalable Vision Learners](https://arxiv.org/abs/2111.06377).

16. Z Xie et al, [SimMIM: A Simple Framework for Masked Image Modeling](https://arxiv.org/abs/2111.09886).