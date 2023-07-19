# Week 4

Topic: The Self-Distillation Family in Self-Supervised Learning

Keynote Speaker: Lifan Lin, Yue Wu, Shengjie Niu

Time: Jul 13, 19:30 - 21:30 pm

Venue: Lecture Hall 3, 302 (SUSTech)


Online Link: [TencentMeeting](https://sustech.meeting.tencent.com/dm/rzsV1UdvWHtp)

## Compendium

I. Introduction: Concept and Mechanism of Self-Distillation

- Introduce the basic concept and structure of self-distillation. Discuss the mechanisms of self-distillation and its relation with Knowledge distillation.
- Discuss the basic idea of contrastive learning and its pretext task (SimCLR).
- The learning objective: A representation mapping invariant of transformation(augmentation). Alignment and uniformity are two key requirement.
- Collapse(trivial solution). Optimal but unwanted result. Basic concept in preventing collapse.

II. Contrastive Learning without Negative Samples

- Introduce BYOL, a self-distillation model learning without negative pairs.
- Connections between BYOL and other works
- Provide some illuminations about why BYOL performs well and avoids collapse

III. Examination of BYOL-like model: Road to prevent collapse

- Mythology: Studying the components of the model through ablation to understand whether they are necessary in preventing collapse.
- Hypothesis proposed: Procedures taken are actually solving an underlying optimization problem. The optimization is EM-like and thus do well in searching for a representation.
- Validating the hypothesis vis experience.

IV. Combining Transformer with Self-Distillation

- Discuss the difficulty faced by the ViT(Vision Transformer). Specifically, the tokenizer of images.
- Tokenizer learn better deep semantic information using self-distillation.
- Discussing the trade-off between alignment and uniformity in ViT.
- Improvement: Introduction MIM(Masked Image Modelling, much similar to masked language modelling) to self-distillation to create more effective pretext tasks.



## Material

I. [Slide](https://nbviewer.org/github/niusj03/23summer/blob/master/content/docs/pdfs/Week4_Niu.pdf) for Intro to Self-Supervised Learning from Shengjie Niu.

II. Slides [1](https://nbviewer.org/github/niusj03/23summer/blob/master/content/docs/pdfs/Week4_Wu.pdf) and [2](https://nbviewer.org/github/niusj03/23summer/blob/master/content/docs/pdfs/Week4_Lin.pdf) for Self-Distillation Family from Yue Wu and Lifan Lin.



## References

1. Balestriero, R et al. [A Cookbook of Self-supervised Learning](https://arxiv.org/abs/2304.12210)

2. [Bootstrap your own latent: A new approach to self-supervised Learning](https://arxiv.org/abs/2006.07733)

3. [Exploring Simple Siamese Representation Learning](https://arxiv.org/abs/2011.10566)

4. [Emerging Properties in Self-Supervised Vision Transformers](https://arxiv.org/abs/2104.14294)

5. [A blog about BYOL](https://generallyintelligent.com/research/2020-08-24-understanding-self-supervised-contrastive-learning/)

6. [A Simple Framework for Contrastive Learning of Visual Representations (arxiv.org)](https://arxiv.org/abs/2002.05709)

7. [Bootstrap your own latent: A new approach to self-supervised Learning (arxiv.org)](https://arxiv.org/abs/2006.07733)

8. [Exploring Simple Siamese Representation Learning (arxiv.org)](https://arxiv.org/abs/2011.10566)

9. [Emerging Properties in Self-Supervised Vision Transformers (arxiv.org)](https://arxiv.org/abs/2104.14294)

10. [iBOT: Image BERT Pre-Training with Online Tokenizer (arxiv.org)](https://arxiv.org/abs/2111.07832)

11. [blog_quarto - BYOL: Contrastive Representation-Learning without Contrastive Losses (drscotthawley.github.io)](https://drscotthawley.github.io/blog_quarto/posts/2022-11-17-byol.html)

12. [Understanding self-supervised and contrastive learning with "Bootstrap Your Own Latent" (BYOL) - generally intelligent](https://generallyintelligent.com/research/2020-08-24-understanding-self-supervised-contrastive-learning/)