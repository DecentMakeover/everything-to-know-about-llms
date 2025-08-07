## Regularization — Essential Papers

Regularizers that consistently improve generalization in CNNs and beyond.

### Core
- **Weight Decay (L2)**: Classic; see decoupling in AdamW — Loshchilov & Hutter [Paper](https://arxiv.org/abs/1711.05101)
- **Dropout (2014)**: Preventing co-adaptation — Srivastava et al. [Paper](https://jmlr.org/papers/v15/srivastava14a.html)
- **Batch Normalization (2015)**: Optimization and regularization benefits — Ioffe & Szegedy [Paper](https://arxiv.org/abs/1502.03167)
- **Label Smoothing (2016)**: Better-calibrated classifiers — Szegedy et al. [Paper](https://arxiv.org/abs/1512.00567)

### Architecture/training strategies
- **Stochastic Depth (2016)** — Huang et al. [Paper](https://arxiv.org/abs/1603.09382)
- **DropConnect (2013)** — Wan et al. [Paper](https://proceedings.mlr.press/v28/wan13.html)
- **Shake-Shake (2017)** — Gastaldi [Paper](https://arxiv.org/abs/1705.07485)

### Data augmentation as regularization
- **Cutout (2017)** — DeVries & Taylor [Paper](https://arxiv.org/abs/1708.04552)
- **Mixup (2018)** — Zhang et al. [Paper](https://arxiv.org/abs/1710.09412)
- **Manifold Mixup (2019)** — Verma et al. [Paper](https://arxiv.org/abs/1806.05236)
- **AutoAugment (2019)** — Cubuk et al. [Paper](https://arxiv.org/abs/1805.09501)
- **RandAugment (2020)** — Cubuk et al. [Paper](https://arxiv.org/abs/1909.13719)
- **CutMix (2019)** — Yun et al. [Paper](https://arxiv.org/abs/1905.04899)

Suggested path: Weight Decay → Dropout → BatchNorm → Mixup/CutMix → Stochastic Depth → RandAugment.


