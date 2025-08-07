## Everything to Know About LLMs and Deep Learning: Curated Paper Lists and Roadmaps

A practical, opinionated index of the most important research papers for modern deep learning. Covers Large Language Models (LLMs), transformers, NLP, and core computer vision topics with CNNs (classification, semantic segmentation, object detection), plus optimization, regularization, and learning-rate schedules. Each section includes a concise reading path from foundational works to state-of-the-art.

### Table of Contents
- [CNNs for Classification](#cnns-for-classification)
- [CNNs for Segmentation](#cnns-for-segmentation)
- [CNNs for Detection](#cnns-for-detection)
- [Embeddings and Tokenization](#embeddings-and-tokenization)
- [Sequence Models](#sequence-models)
- [Optimization](#optimization)
- [Regularization](#regularization)
- [Learning Rates and Schedules](#learning-rates-and-schedules)
- [NLP Foundations](#nlp-foundations)
- [LSTMs and RNNs](#lSTMs-and-rnns)
- [Transformers and LLMs](#transformers-and-llms)
- [How to Use This Repository](#how-to-use-this-repository)
- [Contribute](#contribute)

### What you’ll find
- **Curated paper lists**: High-signal, low-noise selections that matter in practice.
- **Suggested reading paths**: Learn in the right order; build intuition step by step.
- **Practical training tips**: Optimizers, schedules, regularizers, augmentations, scaling.

## CNNs for Classification
- Keyword highlights: CNN architectures, ImageNet, AlexNet, VGG, Inception, ResNet, DenseNet, MobileNet, EfficientNet, ConvNeXt.
- Start here: `classification/README.md` — essential papers and training techniques.

## CNNs for Segmentation
- Keyword highlights: semantic segmentation, instance segmentation, FCN, U-Net, DeepLab, PSPNet, HRNet, OCRNet, Dice loss, Lovasz-Softmax.
- Read: `segmentation/README.md` — core architectures, objectives, and suggested path.

## CNNs for Detection
- Keyword highlights: object detection, R-CNN family, Faster R-CNN, FPN, Mask R-CNN, SSD, YOLO, RetinaNet, FCOS, EfficientDet, DETR.
- Read: `detection/README.md` — two-stage vs one-stage, anchor-free, transformer-based.

## Embeddings and Tokenization
- Keyword highlights: word embeddings, word2vec, GloVe, fastText, BPE, SentencePiece, WordPiece, contextual embeddings (ELMo).
- Read: `embeddings/README.md` — representations and subword tokenization.

## Sequence Models
- Keyword highlights: sequence modeling, RNNs, LSTM, GRU, Seq2Seq, Bahdanau attention, CTC, scheduled sampling.
- Read: `sequence-models/README.md` — overview and links; see also `lstms/README.md`.

## Optimization
- Keyword highlights: SGD with momentum, Adam/AdamW, AMSGrad, LAMB, Adafactor, Shampoo, Lion; large-batch training.
- Read: `optimization/README.md` — optimizers and large-scale training methods.

## Regularization
- Keyword highlights: weight decay, dropout, batch normalization, label smoothing, stochastic depth; Mixup, CutMix, AutoAugment, RandAugment.
- Read: `regularization/README.md` — regularizers and augmentation-as-regularization.

## Learning Rates and Schedules
- Keyword highlights: warmup, cosine annealing (SGDR), cyclical learning rates (CLR), One-Cycle policy, linear scaling rule.
- Read: `learning-rates/README.md` — schedules and scaling rules that work.

## NLP Foundations
- Keyword highlights: word2vec, GloVe, BPE, SentencePiece, Seq2Seq, attention, ELMo, ULMFiT.
- Read: `nlp/README.md` — representations, tokenization, and pre-transformer NLP.

## LSTMs and RNNs
- Keyword highlights: LSTM, GRU, bidirectional RNNs, CTC loss, Seq2Seq, Bahdanau attention.
- Read: `lstms/README.md` — classic sequence modeling and where it still shines.

## Transformers and LLMs
- Keyword highlights: transformers, BERT, GPT, T5, Transformer-XL, XLNet, RoBERTa, ELECTRA; ViT, Swin; DETR; LoRA; scaling laws (Chinchilla).
- Read: `transformers/README.md` — foundational and efficient variants, finetuning, scaling.

## How to Use This Repository
- Pick a topic, open the linked `README.md`, and follow the suggested reading path.
- Skim abstracts first, then deep-dive into 2–3 pivotal papers per section.
- Apply ideas in small experiments (augmentations, schedules, optimizers) to build intuition.

## Contribute
Have a must-read paper or a better reading path? PRs are welcome. Please keep additions high-signal and include a brief rationale.