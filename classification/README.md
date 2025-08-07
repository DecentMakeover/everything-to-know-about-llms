## CNNs for Image Classification — Essential Papers

A curated, opinionated reading list to build strong intuition for convolutional neural networks (CNNs) in image classification. Start near the top and go chronologically to understand how ideas evolved.

### Core architectures
- **LeNet-5 (1998)**: Gradient-based learning for document recognition — LeCun et al. [Paper](https://ieeexplore.ieee.org/document/726791)
- **AlexNet (2012)**: ImageNet classification with deep CNNs — Krizhevsky et al. [Paper](https://proceedings.neurips.cc/paper_files/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html)
- **ZFNet (2013)**: Visualizing and understanding CNNs — Zeiler & Fergus [Paper](https://arxiv.org/abs/1311.2901)
- **VGG (2014)**: Very deep convolutional networks — Simonyan & Zisserman [Paper](https://arxiv.org/abs/1409.1556)
- **Inception v1/GoogLeNet (2014)**: Going deeper with convolutions — Szegedy et al. [Paper](https://arxiv.org/abs/1409.4842)
- **Batch Normalization (2015)**: Accelerating deep network training — Ioffe & Szegedy [Paper](https://arxiv.org/abs/1502.03167)
- **ResNet (2015)**: Deep residual learning — He et al. [Paper](https://arxiv.org/abs/1512.03385)
- **Inception v3/v4 (2015/2016)**: Rethinking the Inception architecture — Szegedy et al. [Paper](https://arxiv.org/abs/1512.00567)
- **WideResNet (2016)**: Wide residual networks — Zagoruyko & Komodakis [Paper](https://arxiv.org/abs/1605.07146)
- **DenseNet (2016)**: Densely connected CNNs — Huang et al. [Paper](https://arxiv.org/abs/1608.06993)
- **ResNeXt (2017)**: Aggregated residual transformations (cardinality) — Xie et al. [Paper](https://arxiv.org/abs/1611.05431)
- **SENet (2017)**: Squeeze-and-excitation blocks — Hu et al. [Paper](https://arxiv.org/abs/1709.01507)
- **MobileNet v1 (2017)**: Depthwise separable convolutions — Howard et al. [Paper](https://arxiv.org/abs/1704.04861)
- **ShuffleNet v1 (2017)**: Pointwise group conv and channel shuffle — Zhang et al. [Paper](https://arxiv.org/abs/1707.01083)
- **MobileNet v2 (2018)**: Inverted residuals, linear bottlenecks — Sandler et al. [Paper](https://arxiv.org/abs/1801.04381)
- **ShuffleNet v2 (2018)**: Practical guidelines for efficient CNNs — Ma et al. [Paper](https://arxiv.org/abs/1807.11164)
- **EfficientNet (2019)**: Compound scaling — Tan & Le [Paper](https://arxiv.org/abs/1905.11946)
- **RegNet (2020)**: Designing network design spaces — Radosavovic et al. [Paper](https://arxiv.org/abs/2003.13678)
- **NFNet (2021)**: High-performance convnets without batch norm — Brock et al. [Paper](https://arxiv.org/abs/2102.06171)
- **ConvNeXt (2022)**: Modernized ResNet matching ViT performance — Liu et al. [Paper](https://arxiv.org/abs/2201.03545)

### Training and regularization techniques (high impact for CNNs)
- **Label Smoothing (2015/2016)**: Introduced with Inception — Szegedy et al. [Paper](https://arxiv.org/abs/1512.00567)
- **Residual connections (2015)**: Optimization made easier — He et al. [Paper](https://arxiv.org/abs/1512.03385)
- **Mixup (2018)**: Beyond empirical risk minimization — Zhang et al. [Paper](https://arxiv.org/abs/1710.09412)
- **AutoAugment (2018)**: Learned data augmentation policies — Cubuk et al. [Paper](https://arxiv.org/abs/1805.09501)
- **CutMix (2019)**: Mixed sample data augmentation — Yun et al. [Paper](https://arxiv.org/abs/1905.04899)

### How to use this list
- Start with AlexNet → VGG → Inception → ResNet to build historical intuition.
- Then read DenseNet, ResNeXt, SENet to understand feature reuse, cardinality, and attention.
- Finish with EfficientNet, RegNet, NFNet, ConvNeXt for modern performant convnets.

If you want a compact minimum-viable path: AlexNet → VGG → ResNet → DenseNet → MobileNet v2 → EfficientNet → ConvNeXt.


