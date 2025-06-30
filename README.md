# Machine Learning Models for EOS SAT-1 Satellite Image Enhancing

This repository contains the author’s accepted version of the paper:

**"Machine Learning Models for EOS SAT-1 Satellite Image Enhancing"**  
**Viacheslav Popika, Lidia Lelechenko**  
Accepted to **IGARSS 2024 (IEEE International Geoscience and Remote Sensing Symposium)**

## 📄 Abstract

This study presents a novel multi-stage method for enhancing the quality and resolution of satellite images from the EOS SAT-1 optical satellite. The proposed approach addresses the absence of clean ground truth data by training a *Distortion Network* to emulate realistic degradation, followed by the use of a *Super-Resolution GAN (SRGAN)* trained on synthetically generated image pairs.

Special focus is given to maintaining the stability of agro-indices such as NDVI during enhancement, which is critical for agricultural monitoring applications.

### Key Contributions:
- A synthetic training data generation pipeline tailored to EOS SAT-1 imagery.
- A GAN-based super-resolution approach capable of enhancing real satellite images.
- A lightweight post-processing stage that preserves statistical properties and NDVI values.
- Quantitative and qualitative validation of the approach on real and synthetic data.


## 📁 Files

- [`20240523112109_984052_4347.pdf`](./20240523112109_984052_4347.pdf): Author’s accepted manuscript (AAM) submitted to IGARSS 2024.
- Example figures and supplemental data (coming soon).

## 📌 Citation

If you use or refer to this work, please cite it as:

```bibtex
@inproceedings{popika2024eossat,
  author    = {Viacheslav Popika and Lidia Lelechenko},
  title     = {Machine Learning Models for EOS SAT-1 Satellite Image Enhancing},
  booktitle = {IGARSS 2024 - IEEE International Geoscience and Remote Sensing Symposium},
  year      = {2024}
}
