# Encoder-only Mask Transformer (EoMT) - Zero-Shot Segmentation

This repository contains experiments with the **Encoder-only Mask Transformer (EoMT)** for zero-shot image segmentation.

## Overview

EoMT demonstrates that a standard Vision Transformer (ViT) encoder can be leveraged as a segmentation model without explicit mask supervision. This repository provides examples of zero-shot segmentation using pretrained models.

![EomT Pipeline Comparison](pipeline.png)

![Example EoMT Segmentation using ViT and DinoV2](zero_shot.png)
If you use this code, please cite the original paper:
Kerssies et al., "Your ViT is Secretly an Image Segmentation Model," CVPR 2025
- https://github.com/tue-mps/eomt.git
- https://arxiv.org/abs/2503.19108
