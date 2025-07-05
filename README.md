# 🧠 ASL Translator – Real-Time Sign Language to Text

A machine learning-powered interface that translates **Mexican Sign Language (LSM)** gestures into real-time text, developed to support online education for the Deaf community.

Built in partnership with **AProSEL**, a Mexican online school for the Deaf.

---

## 📌 Overview

This project enables accurate and real-time translation of over **500 LSM gestures** using a **vector-based keypoint ML pipeline**. It aims to bridge communication gaps and expand accessibility in educational contexts.

- 🧠 96% average recognition accuracy  
- 🎯 Real-time inference using webcam input  
- 🌍 Supports educational use cases in Spanish-speaking communities  

---

## 🛠 Technologies Used

- **Python**  
- **OpenCV** – For hand/gesture capture  
- **TensorFlow / PyTorch** – For training and inference  
- **MediaPipe / Custom keypoint detection**  
- **Flask (optional)** – For web demo integration  

---

## 🚀 How It Works

1. Capture video feed through webcam  
2. Detect and extract hand keypoints  
3. Feed keypoints into a trained classification model  
4. Output recognized LSM gesture as text in real time

---

## 📷 Demo (Coming Soon)

We'll include a GIF or video demo here showcasing live translation.

> Want to contribute? Check the [issues](https://github.com/GestureGraphix/asl-translator/issues) tab!

---

## 🧑‍🤝‍🧑 Real-World Impact

This project was created in collaboration with **AProSEL**, a nonprofit Mexican school for the Deaf. It supports their mission to teach **Mexican Sign Language (LSM)** to students online — expanding access to language, education, and opportunity.

---

## 📂 Folder Structure

```bash
asl-translator/
├── data/                # Keypoint data and labels
├── model/               # Trained model and training scripts
├── webcam_demo.py       # Real-time translation script
├── preprocess.py        # Feature extraction pipeline
├── utils/               # Helper functions
└── README.md            # Project documentation

