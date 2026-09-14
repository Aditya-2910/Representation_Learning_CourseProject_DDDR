# Diffusion-Driven Data Replay (DDDR) - Reproduction & Extension

This repository reproduces and extends the ECCV 2024 paper **"Diffusion-Driven Data Replay: A Novel Approach to Combat Forgetting in Federated Class Continual Learning"** for a Representation Learning course project.

🙏 *Special thanks to the original authors for their well-organized public code.*

---

## 🚀 Our Modifications & Novelty
- **[Feature]**: Added another Autoencoder, before training, so as to increase the privacy of the data. The VAE added, blurs the images and reduces the clarity of the image while keeping the semantic meaning intact.
- **Results**: The results show that due to this change, the privacy is increased a lot, with a slight reduction in performance (2-3%)

---

## 📄 Original Paper Overview

- Links: [Paper](https://arxiv.org/abs/2409.01128) | [Poster](https://eccv.ecva.net/media/PosterPDFs/ECCV%202024/1969.png?t=1725949844.2686071) | [Video](https://eccv.ecva.net/virtual/2024/poster/1969)

### Abstract Summary
Federated Class Continual Learning (FCCL) faces catastrophic forgetting while maintaining client privacy. While GANs and knowledge distillation face instability or low data quality, this paper proposes using a pre-trained conditional diffusion model to reverse-engineer categories and search input conditions, enhanced via contrastive learning. *Readers can view the complete abstract and author details in the linked paper above.*
