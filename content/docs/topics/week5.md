# Week 5

Topic: The Deep Metric Learning Family in Self-Supervised Learning

Keynote Speaker: Xinyao Li, Yiming Zhang, Shengqi Fang

Time: Jul 20, 19:30 - 21:30 pm

Venue: Lecture Hall 3, 302 (SUSTech)


Online Link: [TencentMeeting](https://sustech.meeting.tencent.com/dm/rzsV1UdvWHtp)

## Compendium

I. Contrastive Predictive Coding：

- Introduce Contrastive Predictive Coding, which learns self-supervised representations by predicting the future in latent space by using powerful autoregressive models.
- Introduce the concept of InfoNCE loss, which is a widely used loss function.


II. The Contrastive Loss Function

- Introduce the core ideas of Deep Metric Learning and discuss the shortcomings of traditional Metric Learning methods.
- Discuss DrLIM (Dimensionality Reduction by Learning an Invariant Mapping).
- Introduce Contrastive Loss and its spring model analogy: Attract-only spring and m-Repulse-only spring.
- Show the experiments of DrLIM along with traditional Metric Learning methods.

III. The Triplet Loss Function

- Introduce Triplet Loss: anchor, positive and negative; easy, hard and semi-hard triplets.
- Discuss the importance of triplet selection and two methods: choosing semi-hard triplets (applied in FaceNet) and Batch Hard.

VI. A brief review of SimCLR:
- Introduce structure of contrastive learning.
- emphasize the importance of data augmentation(random cropping and color distortion).

## Material

Slides [1](https://nbviewer.org/github/niusj03/23summer/blob/master/content/docs/pdfs/Week5_Li.pdf), [2](https://nbviewer.org/github/niusj03/23summer/blob/master/content/docs/pdfs/Week5_Fang.pdf) and [3](https://nbviewer.org/github/niusj03/23summer/blob/master/content/docs/pdfs/Week5_Zhang.pdf) for Deep Metric Learning Family from Xinyao Li, Shengqi Fang and Yiming Zhang.

## Reference

1. Balestriero, R et al. [A Cookbook of Self-supervised Learning](https://arxiv.org/abs/2304.12210)

2. R Hadsell et al, [Dimensionality Reduction by Learning an Invariant Mapping](https://ieeexplore.ieee.org/document/1640964)

3. F Schroff et al, [FaceNet: A unified embedding for face recognition and clustering](https://ieeexplore.ieee.org/document/7298682)

4. A Hermans et al, [In Defense of the Triplet Loss for Person Re-Identification](https://arxiv.org/abs/1703.07737)

5. J Goldberger et al，[Neighbourhood Components Analysis](https://proceedings.neurips.cc/paper/2004/file/42fe880812925e520249e808937738d2-Paper.pdf)

6. K Sohn et al,[Improved Deep Metric Learning with Multi-class N-pair Loss Objective](https://papers.nips.cc/paper/2016/file/6b180037abbebea991d8b1232f8a8ca9-Paper.pdf)

7. A Oord et al，[Representation Learning with Contrastive Predictive Coding](https://arxiv.org/abs/1807.03748)

8. T Chen et al, [A Simple Framework for Contrastive Learning of Visual Representations](https://arxiv.org/abs/2002.05709)

8. A Dosovitskiy et al, [Discriminative Unsupervised Feature Learning with Convolutional Neural](http://arxiv.org/abs/1406.6909 )

9. Z Wu et al, [Unsupervised Feature Learning via Non-Parametric Instance-level Discrimination](http://arxiv.org/abs/1805.01978)
