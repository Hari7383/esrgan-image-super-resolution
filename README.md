# ESRGAN — Image Super Resolution

A PyTorch implementation of **ESRGAN (Enhanced Super-Resolution Generative Adversarial Network)** for transforming low-resolution images into high-resolution, photo-realistic outputs.

This project demonstrates how modern GAN architectures significantly outperform traditional interpolation methods in image upscaling tasks.

---

## 🚀 Project Overview

Image super-resolution is widely used in:
✔ Medical imaging  
✔ Satellite imagery  
✔ Old photo restoration  
✔ Video upscaling  
✔ Surveillance enhancement  

This repository provides a **complete ESRGAN pipeline**, including:
- Data preprocessing
- Generator & Discriminator architecture
- Training loop
- Inference & result visualization

---

## 🧠 What is ESRGAN?

ESRGAN improves upon SRGAN by:
- Removing batch normalization
- Using Residual-in-Residual Dense Blocks (RRDB)
- Employing a relativistic discriminator
- Producing sharper textures and realistic details

---

## 🛠️ Tech Stack

- Python 3.8+
- PyTorch
- NumPy
- OpenCV / Pillow
- Matplotlib

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/Hari7383/esrgan-image-super-resolution.git
cd esrgan-image-super-resolution
```

Create and activate a virtual environment:
```
python -m venv venv
source venv/bin/activate     # Linux / macOS
venv\Scripts\activate        # Windows
```
