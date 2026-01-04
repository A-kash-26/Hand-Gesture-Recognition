# ✋ Hand Gesture Recognition System

This project implements a **Hand Gesture Recognition System** using computer vision and machine learning techniques. It is designed as part of **PRODIGY ML Internship – Task 03** and focuses on enabling natural human–computer interaction through hand gestures.

---

## 📌 Project Overview

Hand gesture recognition allows users to interact with computers without physical input devices. This project captures hand gestures through a camera, processes the visual data, extracts meaningful features, and classifies gestures into predefined categories.

---

## 🎯 Objectives

* Detect and track hand movements
* Extract relevant gesture features
* Classify hand gestures accurately
* Enable intuitive human–computer interaction

---

## 🧠 Approach

1. **Image Acquisition** – Capture hand images/video using a camera
2. **Preprocessing** – Resize, grayscale conversion, noise removal
3. **Hand Detection** – Detect hand landmarks using MediaPipe
4. **Feature Extraction** – Extract landmark-based features
5. **Classification** – Predict gesture using a ML model

---

## 🛠️ Technologies Used

* Python
* OpenCV
* NumPy
* MediaPipe
* scikit-learn

---

## 📂 Repository Structure

```
PRODIGY_ML_03/
│
├── README.md
├── hand_gesture_recognition.ipynb
├── hand_gesture_recognition.py
└── sample_gestures/
```

---

## 🚀 How to Run

```bash
pip install opencv-python mediapipe numpy scikit-learn
python hand_gesture_recognition.py
```

---

## 📈 Results

* Accurate detection of hand landmarks
* Reliable gesture classification in controlled environments
* Real-time performance with webcam input

---

## 🚧 Limitations

* Sensitive to lighting conditions
* Background noise can affect detection
* Limited gesture vocabulary

---

## 🔮 Future Improvements

* Use CNNs / Deep Learning for higher accuracy
* Improve robustness in complex backgrounds
* Expand gesture set for real-world applications

---

## 👨‍💻 Author

**Akash S**
Machine Learning Intern – Prodigy InfoTech

⭐ If you find this project useful, please star the repository!
