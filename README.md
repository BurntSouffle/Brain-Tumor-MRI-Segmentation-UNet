# Brain Tumor MRI Segmentation (2D UNet)

This repository contains a simple implementation of semantic segmentation for brain tumors using a 2D UNet architecture on multi-modal MRI scans.

This project was developed as part of my BSc (Hons) Artificial Intelligence coursework at the University of East London (**First Class Honours**). It demonstrates my understanding of pixel-wise prediction workflows and medical image preprocessing — essential skills for AI in medical imaging.

---

## 🧩 Project Overview

Accurate brain tumor segmentation is a key step in medical diagnosis and treatment planning. In this assignment, I implemented:

- Preprocessing of multi-channel brain MRI images.
- A 2D UNet model architecture for semantic segmentation.
- Training and evaluation using Dice score and pixel-wise accuracy.
- Visual comparison of ground truth masks and predicted segmentation.

---

## 📊 Example Results

Below is an example of the input channels, ground truth, and model predictions:

<img width="1590" height="1470" alt="brain scans and segmentation" src="https://github.com/user-attachments/assets/31c22b97-195b-4ff0-bd63-8114f4c8531e" />

---

## ⚙️ How to Run

- Runs fully in **Google Colab** — no local setup needed.
- Required libraries: TensorFlow/Keras, NumPy, Matplotlib.
- Dataset loading steps are included in the notebook.

---

## 📁 Files

| Filename | Description |
|----------|-------------|
| `Brain-Tumor-Segmentation-UNet` | Notebook with the full preprocessing, UNet implementation, training, and prediction steps. |
| `brain scans and segmentation.png` | Example visualization of model predictions vs ground truth. |

---

## 📍 Author

**Abu Sufian Basith**  
BSc (Hons) Artificial Intelligence — University of East London (**First Class Honours**)  
Applying for MSc Artificial Intelligence and Medical Imaging


