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
├── image4.jpg # Sample input image   
├── model_v6_23.hdf5 # Pre-trained emotion recognition model   
├── image_recognition_with_emotions.py # Main project script   
└── README.md # Project documentation    

---

## ⚙️ Requirements

Install the following dependencies before running the project:

```bash
pip install opencv-python mtcnn keras numpy
```

---

## 🚀 How to Run
1. Clone the repository:

```
git clone https://github.com/bardiw/Image_Recognition_with_Emotions.git
cd Image_Recognition_with_Emotions
```
2. Run the script:

```
python image_recognition_with_emotions.py
```
3. The processed image will be saved as final_image.jpg and displayed in a pop-up window.

---

## 🧠 Model Information
The model_v6_23.hdf5 file is a CNN model trained on a facial expression dataset for emotion classification.

---

