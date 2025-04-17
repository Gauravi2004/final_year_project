# final_year_project
This project enables two-way communication for Divyang individuals by converting hand gestures into text and audio using machine learning. It supports alphabetic and word-level gestures with 99.6% accuracy, and also converts responses from the other person into both text and audio formats.
# Empowering Communication: Gesture-Based Language to Text and Audio System for Divyang Individuals

This project is designed to bridge the communication gap for **Divyang (differently-abled) individuals** by recognizing hand gestures and translating them into **text and audio outputs** using machine learning.

It promotes **two-way communication**, enabling Divyang users to express themselves through gestures, while also receiving text and audio responses from others.

---

## 🔍 Features

- ✋ Real-time gesture recognition using webcam
- 🔤 Supports **alphabetic and word-level gestures**
- 🎯 Achieved **99.6% accuracy** with Random Forest classifier
- 🔁 **Two-way communication** system:
  - Gesture ➜ Text + Audio
  - Text Response ➜ Audio Output
- 🧠 Machine Learning Models: SVM, KNN, Decision Tree, Random Forest
- 🎛️ Custom keyboard interface for sentence formation
- 🗣️ Text-to-Speech (TTS) integration for audio feedback
- 📚 Educational and user-friendly interface

---

## 🚀 How It Works

1. **Gesture Input**: Hand gestures are captured using a webcam.
2. **Preprocessing**: Input images are resized, flattened, and binarized.
3. **Prediction**: ML model predicts the gesture label.
4. **Output**: Recognized gesture is converted to text and audio.
5. **Reply**: Other person types response ➜ System reads it aloud.

---

## 🛠️ Tech Stack

- Python  
- OpenCV  
- Scikit-learn  
- Tkinter (for GUI)  
- Pyttsx3 (for Text-to-Speech)

---

## 📊 Model Performance

| Model            | Accuracy |
|------------------|----------|
| SVM              | 97.4%    |
| KNN              | 95.2%    |
| Decision Tree    | 96.1%    |
| **Random Forest**| **99.6%**|

---

## 📦 Installation

```bash
git clone https://github.com/your-username/gesture-language-to-text-audio.git
cd gesture-language-to-text-audio
pip install -r requirements.txt
python app.py
