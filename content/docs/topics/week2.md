# Week 2

Topic: The Bridge: Transferable Feature towards Advanced Mechanism

Keynote Speaker: Zebin Yun

Time: Jun 29, 19:30 - 21:30 pm

Venue: Lecture Hall 3, 302 (SUSTech)

Online Link: [TencentMeeting](https://sustech.meeting.tencent.com/dm/rzsV1UdvWHtp)

# Compendium

Present transferability of features in deep neural networks, specifically the generality versus specificity of neurons in each layer of a deep convolutional neural network. Furthermore, detail the connection between transferable features and pretrain-finetune mechanism. 

- The first layer of a deep neural network learns simple features are generalizable across tasks. 
- As the layers get deeper, the neurons become more specialized to their original task, making them less transferable to new tasks. 
- Fine-tuning a pre-trained network on a new task can be difficult due to optimization difficulties related to splitting the network. 
- The transferability of features can be quantified by measuring the performance of a network when transferring between dis-similar tasks. 
- Networks trained on a natural target task perform better when transferring to a man-made target task than vice versa. 6. The performance of a network can be improved by initializing the first few layers with random, untrained weights.
- The pretrain weight can utilize the transferable feature for downstream tasks 

## Material

I. The second week [slide](https://nbviewer.org/github/niusj03/23summer/blob/master/content/docs/pdfs/Week-2.pdf) from Zebin Yun.

II. Some helpful videos:

- [BERT and its family - Introduction and Fine-tune](https://www.youtube.com/watch?v=1_gRK9EIQpc)
- [BERT and its family - ELMo, BERT, GPT, XLNet, MASS, BART, UniLM, ELECTRA, and more](https://www.youtube.com/watch?v=Bywo7m6ySlk)
- [Lecture 21: Auto-encoder (1/2)](https://www.youtube.com/watch?v=E7wlA85RxcI)
- [Lecture 22: Auto-encoder (2/2)](https://www.youtube.com/watch?v=PsBHWq9KKqk)


## References

1. Yosinski, J et al. [How transferable are features in deep neural networks?](https://arxiv.org/abs/1411.1792)

2. Devlin, Jacob, et al. [Bert: Pre-training of deep bidirectional transformers for language understanding.](https://arxiv.org/abs/1810.04805) - [Code](https://colab.research.google.com/drive/1m0fQjJfkK9vAovxPj9Nd3-hQuxezB2w1) of BERT

3. S. J. Pan et al. [Domain Adaptation via Transfer Component Analysis](https://cse.hkust.edu.hk/~jamesk/papers/tnn11.pdf)

4. Long M et al. [Transfer feature learning with joint distribution adaptation](https://ieeexplore.ieee.org/document/6751384)



