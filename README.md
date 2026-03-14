# 😷 Face Mask Detection using Deep Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Deep Learning](https://img.shields.io/badge/TensorFlow-CNN-orange)
![Computer Vision](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)

---

## 📌 Project Overview

The **Face Mask Detection System** is a deep learning project that detects whether a person is wearing a **face mask** or **not wearing a mask** using a webcam.

This project uses **Convolutional Neural Networks (CNN)** for image classification and **OpenCV** for real-time face detection.

The model is trained using a dataset from **Kaggle**.

---

## 🚀 Features

✔ Real-time mask detection

✔ Detects **Mask 😷** and **No Mask ❌**

✔ Uses **CNN Deep Learning model**

✔ Webcam-based detection

✔ Kaggle dataset training

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib

---

## 📊 Dataset

The dataset used for this project is from **Kaggle**.

Dataset link:

https://www.kaggle.com/datasets/omkargurav/face-mask-dataset

Dataset structure:

```text
dataset
│
├── with_mask
│   ├── image1.jpg
│   ├── image2.jpg
│
├── without_mask
│   ├── image1.jpg
│   ├── image2.jpg
```

The dataset contains images of people **with masks and without masks**.

---

## 📂 Project Structure

```text
face-mask-detection
│
├── dataset
│   ├── with_mask
│   └── without_mask
│
├── train_model.py
├── detect_mask.py
├── face_mask_model.h5
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```
git clone https://github.com/yourusername/face-mask-detection.git
```

Move to project directory:

```
cd face-mask-detection
```

Install required libraries:

```
pip install tensorflow opencv-python numpy matplotlib
```

---

## ▶️ Run the Project

### Train Model

```
python train_model.py
```

### Start Detection

```
python detect_mask.py
```

The webcam will open and detect:

* **Mask**
* **No Mask**

---

## 🧠 Model Workflow

1. Load Kaggle dataset
2. Preprocess and resize images
3. Train CNN model
4. Save trained model
5. Detect mask using webcam

---

## 🔮 Future Improvements

* Increase dataset size
* Improve CNN accuracy
* Deploy as web application
* Integrate with CCTV systems

---

## 👨‍💻 Author

**Raghavendra**
BTech – Artificial Intelligence & Data Science

---

⭐ If you like this project, consider giving it a star on GitHub.
