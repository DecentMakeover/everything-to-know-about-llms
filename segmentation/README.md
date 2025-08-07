## CNNs for Image Segmentation — Essential Papers

A concise, high-signal reading list for semantic and instance segmentation with CNNs. Read roughly in order.

### Semantic segmentation (core CNN architectures)
- **FCN (2015)**: Fully Convolutional Networks for Semantic Segmentation — Long et al. [Paper](https://arxiv.org/abs/1411.4038)
- **U-Net (2015)**: Convolutional networks for biomedical image segmentation — Ronneberger et al. [Paper](https://arxiv.org/abs/1505.04597)
- **SegNet (2015)**: A deep encoder-decoder architecture — Badrinarayanan et al. [Paper](https://arxiv.org/abs/1511.00561)
- **DeepLab series (v1–v3+) (2014–2018)**: Atrous conv, ASPP, encoder–decoder — Chen et al. [DeepLab v3+ Paper](https://arxiv.org/abs/1802.02611)
- **PSPNet (2017)**: Pyramid Scene Parsing Network — Zhao et al. [Paper](https://arxiv.org/abs/1612.01105)
- **HRNet (2019)**: High-Resolution Representations — Sun et al. [Paper](https://arxiv.org/abs/1908.07919)
- **OCRNet (2019)**: Object-Contextual Representations — Yuan et al. [Paper](https://arxiv.org/abs/1909.11065)
- **BiSeNet v2 (2020)**: Bilateral segmentation network — Yu et al. [Paper](https://arxiv.org/abs/2004.02147)
- **Fast-SCNN (2019)**: Efficient real-time segmentation — Poudel et al. [Paper](https://arxiv.org/abs/1902.04502)

### Instance and panoptic segmentation cross-over
- **Mask R-CNN (2017)**: Strong baseline for instance segmentation — He et al. [Paper](https://arxiv.org/abs/1703.06870)

### Training objectives and tricks
- **Dice loss (2016)**: V-Net for volumetric segmentation — Milletari et al. [Paper](https://arxiv.org/abs/1606.04797)
- **Lovasz-Softmax (2017)**: Directly optimizes IoU — Berman et al. [Paper](https://arxiv.org/abs/1705.08790)
- **CRF as RNN (2015)**: Structured prediction with CRF layers — Zheng et al. [Paper](https://arxiv.org/abs/1502.03240)

### Suggested reading path
- FCN → U-Net → DeepLab v3+ → PSPNet → HRNet → Mask R-CNN → OCRNet/BiSeNet v2.


