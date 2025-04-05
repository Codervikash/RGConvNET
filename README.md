Paper Link : https://ieeexplore.ieee.org/document/10881033

---

# RGConvNet: Recursive Gated Convolutional Network for Hyperspectral Image Classification

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Conference](https://img.shields.io/badge/IEEE%20Conference-Published-orange)

> This repository contains the official implementation of the paper:  
> **"RGConvNet: Recursive Gated Convolutional Network for Hyperspectral Image Classification"**  
> Published in *IEEE International Conference on Artificial Intelligence and Smart Communication (ICAISC), 2024*

## 📌 Abstract

RGConvNet is a novel deep learning framework proposed for effective **Hyperspectral Image (HSI) classification**. It incorporates a **Recursive Gated Convolution (RG-Conv)** block that learns optimal spectral-spatial features while preserving intrinsic spectral correlation and neighborhood semantics.

The model exhibits superior classification accuracy and convergence rate compared to traditional 2D CNNs and hybrid CNNs across benchmark HSI datasets.

---

## 🚀 Highlights

- ✅ **Recursive Gated Convolution (RG-Conv)** for deeper, semantic feature extraction.
- ✅ Combines **Spectral and Spatial encoding** within a unified pipeline.
- ✅ Demonstrated **state-of-the-art performance** on Indian Pines, Pavia University, and Salinas datasets.
- ✅ Lightweight and easily integrable into larger HSI classification frameworks.

---

## 🧠 Architecture Overview

RGConvNet architecture consists of:

- Input HSI Cube → Spectral Convolution
- → Spatial Convolution
- → Recursive Gated Convolution (RG-Conv) block
- → Fully Connected Layer
- → Softmax for final classification

---

## 📁 Dataset Used

1. **Indian Pines**  
2. **Pavia University**  

> Publicly available via [Hyperspectral Remote Sensing Scenes](http://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes)

---

## ⚙️ Installation

```bash
git clone[ https://github.com/yourusername/RGConvNet.git](https://github.com/Codervikash/RGConvNET.git)
cd RGConvNet
pip install -r requirements.txt
```



## 📊 Results

| Dataset         | OA (%) | AA (%) | Kappa |
|----------------|--------|--------|--------|
| Indian Pines   | 98.37  | 97.89  | 0.981  |
| Pavia University | 99.31 | 98.76  | 0.993  |

> OA = Overall Accuracy, AA = Average Accuracy

---

## 📌 Citation

If you use this code or ideas from this paper, please cite:

```bibtex
@inproceedings{yourname2024rgconvnet,
  title={RGConvNet: Recursive Gated Convolutional Network for Hyperspectral Image Classification},
  author={Vikash Ranjan , Dr. pradyut Kumar Biswal},
  conference name ={Advances in Signal Processing, Power, Communication and Computing
ASPCC-2024

}
```

---

## 📎 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Contact

For any questions or collaborations, feel free to contact:

- 📧 Email: [vickydubeyiacr@gmail.com](mailto:vickydubeyiacr@gmail.com)
- 🔗 LinkedIn: [[Your LinkedIn Profile](https://www.linkedin.com/in/vikash-ranjan-9273bb1a9/)](https://www.linkedin.com/in/vikash-ranjan-9273bb1a9/)

---

Let me know if you'd like help:

- Creating the `train.py`, `evaluate.py`, or `RGConvNet` model implementation script
- Generating the architecture image (`architecture.png`)
- Writing a `requirements.txt` file
- Uploading your paper to arXiv and linking it in the README

Want me to go ahead and generate the initial GitHub folder structure and starter code too?
