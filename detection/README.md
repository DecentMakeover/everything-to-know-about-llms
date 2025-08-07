## CNNs for Object Detection — Essential Papers

Key milestones for two-stage and one-stage detectors, plus modern anchor-free and transformer baselines.

### Two-stage detectors
- **R-CNN (2014)**: Rich feature hierarchies — Girshick et al. [Paper](https://arxiv.org/abs/1311.2524)
- **SPP-Net (2014)**: Spatial pyramid pooling — He et al. [Paper](https://arxiv.org/abs/1406.4729)
- **Fast R-CNN (2015)**: Multitask training with RoI pooling — Girshick [Paper](https://arxiv.org/abs/1504.08083)
- **Faster R-CNN (2015)**: Region Proposal Networks — Ren et al. [Paper](https://arxiv.org/abs/1506.01497)
- **FPN (2017)**: Feature Pyramid Networks — Lin et al. [Paper](https://arxiv.org/abs/1612.03144)
- **Mask R-CNN (2017)**: Extends Faster R-CNN with masks — He et al. [Paper](https://arxiv.org/abs/1703.06870)
- **Cascade R-CNN (2018)**: Cascade of detectors — Cai & Vasconcelos [Paper](https://arxiv.org/abs/1712.00726)

### One-stage detectors
- **OverFeat (2014)**: Integrated recognition, localization, detection — Sermanet et al. [Paper](https://arxiv.org/abs/1312.6229)
- **YOLO v1 (2016)**: Unified real-time detection — Redmon et al. [Paper](https://arxiv.org/abs/1506.02640)
- **YOLOv2/YOLO9000 (2016)**: Joint detection and classification — Redmon & Farhadi [Paper](https://arxiv.org/abs/1612.08242)
- **YOLOv3 (2018)**: Multi-scale predictions — Redmon & Farhadi [Paper](https://arxiv.org/abs/1804.02767)
- **SSD (2016)**: Single Shot MultiBox Detector — Liu et al. [Paper](https://arxiv.org/abs/1512.02325)
- **RetinaNet (2017)**: Focal Loss — Lin et al. [Paper](https://arxiv.org/abs/1708.02002)

### Anchor-free and modern baselines
- **FCOS (2019)**: Fully convolutional one-stage detector — Tian et al. [Paper](https://arxiv.org/abs/1904.01355)
- **CenterNet (2019)**: Keypoint triplets for objects — Zhou et al. [Paper](https://arxiv.org/abs/1904.07850)
- **EfficientDet (2020)**: Compound scaling for detectors — Tan et al. [Paper](https://arxiv.org/abs/1911.09070)
- **DETR (2020)**: End-to-end detection with transformers — Carion et al. [Paper](https://arxiv.org/abs/2005.12872)
- **Deformable DETR (2020)**: Multi-scale deformable attention — Zhu et al. [Paper](https://arxiv.org/abs/2010.04159)

### Training objectives and tricks
- **Focal Loss (2017)**: Class imbalance solution — Lin et al. [Paper](https://arxiv.org/abs/1708.02002)
- **GIoU/DIoU/CIoU Loss (2019–2020)**: Better bounding box regression — Rezatofighi et al. [GIoU](https://arxiv.org/abs/1902.09630), Zheng et al. [DIoU/CIoU](https://arxiv.org/abs/1911.08287)

### Suggested reading path
- R-CNN → Fast/Faster R-CNN → FPN → YOLOv3 → SSD → RetinaNet → FCOS → EfficientDet → DETR.


