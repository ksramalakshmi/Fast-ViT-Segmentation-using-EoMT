# Encoder-only Mask Transformer (EoMT) - A Preliminary Implementation

Link to the complete Medium article - https://ksramalakshmi.medium.com/eomt-a-simpler-faster-way-to-do-image-segmentation-360c17421298

This repository contains experiments with the **Encoder-only Mask Transformer (EoMT)** for zero-shot image segmentation.

<img width="539" height="605" alt="EomT Pipeline Comparison" src="https://github.com/user-attachments/assets/a7a2f403-764e-4a94-80f3-186ee4253460" />

## Overview

EoMT demonstrates that a standard Vision Transformer (ViT) encoder can be leveraged as a segmentation model without explicit mask supervision. This repository provides examples of zero-shot segmentation using pretrained models.

<img width="512" height="663" alt="Example EoMT Segmentation using ViT and DinoV2" src="https://github.com/user-attachments/assets/d7f6a5bd-a442-433d-87d5-97c8f9fffe27" />

Even in a zero-shot setting, EoMT produces meaningful masks — showing strong potential if properly fine-tuned on segmentation data. If I were to extend this work, I’d love to test hybrid approaches — EoMT as the core, with tiny adapters only where performance gaps appear. I’d also be curious to see it on non-standard datasets like 3D scans or remote sensing, where inductive biases sometimes help.


If you use this code, please cite the original paper <br>
**Kerssies et al., "Your ViT is Secretly an Image Segmentation Model," CVPR 2025**
- https://github.com/tue-mps/eomt.git
- https://arxiv.org/abs/2503.19108
