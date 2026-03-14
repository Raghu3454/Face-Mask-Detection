# 😷 Face Mask Detection using Deep Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-TensorFlow-orange)
![Computer Vision](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)

---

## 📌 Project Overview

The **Face Mask Detection System** uses **Deep Learning and Computer Vision** to detect whether a person is wearing a **face mask** or **not wearing a mask** in real time.

The model is trained using a **Convolutional Neural Network (CNN)** and uses **OpenCV** to detect faces through a webcam.

This project demonstrates how **Artificial Intelligence can be used for public safety and health monitoring**.

---

## 🚀 Features

✔ Real-time face mask detection
✔ Detects **Mask** and **No Mask**
✔ Uses **CNN Deep Learning model**
✔ Webcam-based detection using OpenCV
✔ Beginner-friendly AI project

---

## 🛠️ Technologies Used

* 🐍 Python
* 🤖 TensorFlow / Keras
* 👁️ OpenCV
* 🔢 NumPy
* 📊 Matplotlib

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

## 📊 Dataset

The dataset contains two categories:

| Folder       | Description                    |
| ------------ | ------------------------------ |
| with_mask    | Images of people wearing masks |
| without_mask | Images of people without masks |

Dataset can be downloaded from Kaggle.

---

## ⚙️ Installation

Clone the repository

```
git clone https://github.com/yourusername/face-mask-detection.git
```

Move into the project folder

```
cd face-mask-detection
```

Install required libraries

```
pip install tensorflow opencv-python numpy matplotlib
```

---

## ▶️ How to Run the Project

### Step 1: Train the Model

```
python train_model.py
```

This will generate the trained model:

```
face_mask_model.h5
```

---

### Step 2: Run Real-Time Detection

```
python detect_mask.py
```

Your webcam will open and detect:

* **Mask 😷**
* **No Mask ❌**

---

## 🧠 Deep Learning Model

The project uses a **Convolutional Neural Network (CNN)** for image classification.

Workflow:

1. Load dataset images
2. Preprocess and resize images
3. Train CNN model
4. Save trained model
5. Detect mask in real-time using webcam

---

## 🔮 Future Improvements

* Improve model accuracy
* Add mobile camera detection
* Deploy using **Streamlit or Flask**
* Integrate with **CCTV cameras**

---

## 👨‍💻 Author

**Raghavendra**
BTech – Artificial Intelligence & Data Science

---

⭐ If you like this project, consider giving it a **star on GitHub**.
# Face-Mask-Detection
