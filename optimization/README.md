## Optimization for Deep Learning — Essential Papers

A focused list of optimizers and large-scale training techniques that matter in practice.

### Core optimizers
- **SGD with Momentum (1964/2013)**: Polyak momentum; deep learning adoption — Sutskever et al. [Paper](https://proceedings.neurips.cc/paper_files/paper/2013/file/51c5c3af6…)
- **Nesterov Momentum (1983/2013)**: Nesterov accelerated gradient; DL usage — Sutskever et al. [Paper](https://proceedings.neurips.cc/paper_files/paper/2013/file/51c5c3af6…)
- **Adagrad (2011)**: Adaptive subgradient — Duchi et al. [Paper](https://jmlr.org/papers/v12/duchi11a.html)
- **RMSProp (2012)**: Adaptive method (Hinton lecture notes) — Tieleman & Hinton [Note](https://www.cs.toronto.edu/~hinton/coursera/lecture6/lec6.pdf)
- **Adam (2014)**: Adaptive moments — Kingma & Ba [Paper](https://arxiv.org/abs/1412.6980)
- **AMSGrad (2018)**: Convergence fix for Adam — Reddi et al. [Paper](https://arxiv.org/abs/1904.09237)
- **AdamW (2017/2019)**: Decoupled weight decay — Loshchilov & Hutter [Paper](https://arxiv.org/abs/1711.05101)
- **Nadam (2016)**: Adam with Nesterov momentum — Dozat [Paper](https://openreview.net/pdf?id=OM0jvwB8jIp57ZJjtNEZ)
- **AdaBelief (2020)**: Better generalization than Adam — Zhuang et al. [Paper](https://arxiv.org/abs/2010.07468)
- **RAdam (2019)**: Rectified Adam — Liu et al. [Paper](https://arxiv.org/abs/1908.03265)
- **Lion (2023)**: Evolved sign momentum — Chen et al. [Paper](https://arxiv.org/abs/2302.06675)

### Large-batch and large-model training
- **LARS/LAMB (2017/2019)**: Layer-wise adaptive rate scaling; LAMB for BERT — You et al. [LARS](https://arxiv.org/abs/1708.03888), [LAMB](https://arxiv.org/abs/1904.00962)
- **Adafactor (2018)**: Memory-efficient adaptive optimizer — Shazeer & Stern [Paper](https://arxiv.org/abs/1804.04235)
- **Shampoo (2018/2021)**: Second-order preconditioning — Gupta et al. [Paper](https://arxiv.org/abs/1802.09568)

### Practical reads
- **On the Convergence of Adam and Beyond (2018)** — Reddi et al. [Paper](https://arxiv.org/abs/1904.09237)
- **Decoupled Weight Decay Regularization (AdamW) (2019)** — Loshchilov & Hutter [Paper](https://arxiv.org/abs/1711.05101)

Suggested path: SGD+Momentum → Adam → AdamW → LAMB/Adafactor → Lion.


