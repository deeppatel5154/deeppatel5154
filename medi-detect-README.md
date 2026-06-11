# 🏥 Medi-Detect — AI Medical Detection System

> ML-powered object detection system for medical image analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Overview

**Medi-Detect** is a machine learning-powered detection system built with TensorFlow and Python that identifies and classifies objects in medical images with high accuracy.

- ✅ Achieved **90%+ object identification accuracy**

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core development |
| TensorFlow / Keras | Deep learning model |
| OpenCV | Image preprocessing |
| NumPy | Array operations |
| Matplotlib | Visualization |
| Jupyter Notebook | Training & evaluation |

---

## 📂 Project Structure

```
medi-detect/
│
├── data/
│   ├── train/                # Training images
│   ├── val/                  # Validation images
│   └── test/                 # Test images
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_model_training.ipynb
│   └── 03_evaluation.ipynb
│
├── src/
│   ├── preprocess.py
│   ├── model.py
│   └── predict.py
│
├── models/
│   └── medi_detect_model.h5
│
├── results/
│   └── detection_samples.png
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/deeppatel5154/medi-detect.git
cd medi-detect

# Install dependencies
pip install -r requirements.txt

# Run prediction on a sample image
python src/predict.py --image data/test/sample.jpg
```

---

## 📊 Model Performance

| Metric | Score |
|---|---|
| Accuracy | 90%+ |
| Precision | 0.91 |
| Recall | 0.89 |
| F1 Score | 0.90 |

---

## 📬 Contact

**Deep Patel** — [deeppatel5154@gmail.com](mailto:deeppatel5154@gmail.com) | [LinkedIn](https://www.linkedin.com/in/deeppatel5154)
