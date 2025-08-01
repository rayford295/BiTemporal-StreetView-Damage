# 🛰️ BiTemporal-StreetView-Damage

Hyperlocal disaster damage assessment using bi-temporal street-view imagery and pre-trained vision models.

<p align="center">
  <img src="images/study_area_disaster_damage_made.png" alt="Study Area" width="600"/>
</p>

---

## 📌 Introduction

This project aims to enhance disaster damage perception and localization through **bi-temporal street-view imagery** (before and after disaster events). We leverage **pre-trained vision and vision-language models** (e.g., Swin Transformer and ConvNeXt, GPT-4o) to analyze fine-grained street-level damage in a hyperlocal context.

Key contributions include:
（1）Dual-channel model for damage assessment using bi-temporal street-view images.
（2）The dataset includes 2,249 labeled pre/post-disaster street-view image pairs.
（3）Outperforms baseline: Our model improves accuracy from 66.14% to 77.11%.
（4）Grad-CAM confirms the benefits of adding pre-disaster context for model focus.
（5）Enables rapid hyperlocal damage assessment for resilient city planning.


---

## 🧠 Paper Reference

> Yang, Y., Zou, L., Zhou, B., Li, D., Lin, B., Abedin, J., & Yang, M. (2025).  
> *Hyperlocal disaster damage assessment using bi-temporal street-view imagery and pre-trained vision models*.  
> arXiv preprint [arXiv:2504.09066](https://arxiv.org/abs/2504.09066)

---

## 📁 Repository Structure

```bash
BiTemporal-StreetView-Damage/
│
├── codes/                          # Source code for model implementation and experiments
├── images/                         # Figures and illustrations
│   ├── study_area_disaster_damage_made.png
│   ├── architect1.drawio_1.png
│   ├── design_experiment.drawio_1.png
│   ├── dual_channel.drawio_2.png
│   ├── 0204-06.png
│   └── ...
├── LICENSE
├── README.md
└── .gitignore

