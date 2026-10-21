# 🧠 Automated Brain MRI Tumor Segmentation & Volume Calculator

A Python-based medical image processing pipeline built for biomedical engineering analysis. This project automates the workflow of loading 3D medical scans, cleaning background artifacts, isolating brain tissue, and calculating precise pathological volumes in cubic centimeters ($cm^3$).

## 🚀 Features
* **NIfTI Ingestion (`nibabel`):** Loads 3D volumetric medical imaging formats.
* **Physical Calibration:** Extracts voxel dimensions from file headers to compute real-world volumetric measurements instead of abstract pixel counts.
* **Automated Preprocessing & Masking:** Normalizes intensity values and utilizes Otsu's thresholding combined with **Connected Component Analysis** (`scipy`) to cleanly extract brain tissue.
* **Lesion Detection & Quantification:** Targets high-intensity pathological regions and calculates volume in standard clinical units ($cm^3$).

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** `nibabel`, `nilearn`, `scikit-image`, `scipy`, `matplotlib`, `numpy`

## 📂 How to Run
You can run this project instantly in Google Colab by clicking the badge below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/YOUR-REPO-NAME/blob/main/Brain_MRI_Segmentation.ipynb)
*(Make sure to replace `YOUR-USERNAME` and `YOUR-REPO-NAME` with your actual GitHub details).*
