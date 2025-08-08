# 😃 Image Recognition with Emotions

This project uses **OpenCV**, **MTCNN**, and a pre-trained **Keras** model to detect faces in an image and recognize their emotions.  
It draws colored rectangles around the detected faces and labels them with the predicted emotion.

---

## 📌 Features
- Detects faces in an image using **MTCNN**
- Predicts emotions using a pre-trained deep learning model
- Supports **7 emotions**:
  - Angry 😠
  - Sad 😢
  - Neutral 😐
  - Disgust 🤢
  - Surprise 😮
  - Fear 😨
  - Happy 😄
- Displays results on the original image

---

## 📂 Project Structure
Image_Recognition_with_Emotions/
│
├── image4.jpg # Sample input image
├── model_v6_23.hdf5 # Pre-trained emotion recognition model
├── image_recognition_with_emotions.py # Main project script
└── README.md # Project documentation

---

## ⚙️ Requirements

Install the following dependencies before running the project:

```bash
pip install opencv-python mtcnn keras numpy
