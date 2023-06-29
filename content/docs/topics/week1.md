# Week 1

Topic: An Introduction of Model-Agnostic Meta-Learning: Principles, Mechanisms, and Variants

Keynote Speaker: Wang Ma

Time: Jun 21, 11:00 - 12:30 am

Venue: Business Hall, 314 (SUSTech)

Online Link: [TencentMeeting](https://sustech.meeting.tencent.com/dm/8FKe79A6nA1k)

## Compendium

I. Introduction: The Concept and Mechanism of Meta-Learning (Credits: Prof. Hung-yi Lee's Slides)

- Discussing the concept and mechanisms of Meta-Learning.
- Exploring its distinctive role and divergence from traditional Machine Learning approaches.

II. The Emergence of MAML

- Providing an overview of the Model-Agnostic Meta-Learning (MAML) Algorithm.
- Offering an intricate explanation of MAML's workings, augmented by sketch illustrations.
- Demonstrating the versatility of MAML through application examples such as classification, regression, and reinforcement learning problems.

III. First-Order MAML (FO-MAML)

- Illuminating the presence of the second derivative in the MAML Algorithm through mathematical derivation.
- Introducing the First-Order Model-Agnostic Meta-Learning (FO-MAML), with a focus on its divergence from the MAML algorithm (which part of the originial algorithm is ignored).
- Rewriting the FO-MAML algorithm to better illustrate its structure and functionality.

IV. The Advent of Reptile

- Re-examining the MAML optimization problem and diving deeper into FO-MAML.
- Introducing Reptile, with a clear delineation of its distinction from FO-MAML.
- Rewriting the Reptile algorithm for a better understanding.

V. Feature Reuse in MAML & Introduction to ANIL (Almost No Inner Loop)

- Discussing why MAML's efficiency is amplified by Feature Reuse rather than Rapid Learning, supplemented with the explanation and analysis of three experimental case studies.
- Explaining how the concept of feature reuse spearheaded the idea of ANIL.
- Providing a comprehensive explanation of ANIL, its unique algorithm, and how it differentiates from MAML.

VI. Conclusion

- Recapping the key concepts, techniques, and distinctions between MAML and its variants, emphasizing their potential impact on the future of machine learning.


## Material

The first week [slide](https://nbviewer.org/github/niusj03/23summer/blob/master/content/docs/pdfs/Week-1.pdf) from Wang Ma.

[Slide-ref](https://nbviewer.org/github/niusj03/23summer/blob/master/content/docs/pdfs/Week1-ref.pdf) is reference slide from hungyi-lee.

## References

1. Chelsea Finn's blog on [Learning to Learn](https://bair.berkeley.edu/blog/2017/07/18/learning-to-learn/)

2. Chelsea Finn et al. [Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks (MAML)](https://arxiv.org/abs/1703.03400)

3. Alex Nichol et al. [On First-Order Meta-Learning Algorithms (Reptile)](https://arxiv.org/abs/1803.02999)

4. Aniruddh Raghu et al. [Rapid Learning or Feature Reuse? Towards Understanding the Effectiveness of MAML](https://arxiv.org/abs/1909.09157)

5. Chelsea Finn. [Learning to Learn with Gradients](https://ai.stanford.edu/~cbfinn/_files/dissertation.pdf)