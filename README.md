# 🛰️ BiTemporal-StreetView-Damage

Hyperlocal disaster damage assessment using bi-temporal street-view imagery and pre-trained vision models.

<p align="center">
  <img src="https://github.com/rayford295/BiTemporal-StreetView-Damage/blob/main/images/dual_channel.drawio%20(2).png" alt="Study Area Map" width="600"/>
</p>


---

## 📌 Introduction

This repository presents a novel framework for **bi-temporal street-view image analysis**, aimed at advancing hyperlocal disaster damage assessment. We integrate **pre- and post-disaster imagery** using **pre-trained vision and vision-language models** to classify and localize disaster impact more accurately.

### 🔍 Key Contributions

- ✅ **Dual-channel model** for fusing pre- and post-disaster street-view images.
- 📸 **2,249 labeled street-view image pairs**, annotated with fine-grained disaster impact.
- 📈 **Performance**: Accuracy improved from 66.14% (post-only) to 77.11% (bi-temporal).
- 🔥 **Grad-CAM visualization** confirms the added value of pre-disaster imagery for model focus.
- 🏙️ Enables **rapid and fine-grained damage mapping**, supporting climate-resilient urban planning.

---

## 📂 Dataset

You can access the **bi-temporal street-view disaster dataset** from the following DOI:

> 📁 Yang, Yifan (2025).  
> *Perceiving Multidimensional Disaster Damages from Street–View Images Using Visual–Language Models*.  
> figshare. Dataset. https://doi.org/10.6084/m9.figshare.28801208.v2

The dataset includes:
- Pre- and post-disaster images
- Location and damage type annotations
- Severity scores (minor, moderate, severe)
- Sample image regions from Horseshoe Beach, Florida after Hurricane Idalia and Milton

---

## 🧠 Paper Reference

> Yang, Y., Zou, L., Zhou, B., Li, D., Lin, B., Abedin, J., & Yang, M. (2025).  
> *Hyperlocal disaster damage assessment using bi-temporal street-view imagery and pre-trained vision models*.  
> arXiv preprint [arXiv:2504.09066](https://arxiv.org/abs/2504.09066)

---

## 🗂 Repository Structure

```bash
BiTemporal-StreetView-Damage/
│
├── codes/                          # Model training and evaluation scripts
├── images/                         # Project figures
│   ├── study_area_disaster_damage_made.png
│   ├── architect1.drawio (1).png
│   ├── design experiment.drawio (1).png
│   ├── dual_channel.drawio (2).png
│   ├── 0204-06.png
│   ├── readme.txt
├── LICENSE
├── README.md
└── .gitignore


