# VOICE BRIDGE – Sign Language to Text Conversion

VOICE BRIDGE is an AI-powered assistive tool designed to enhance communication for individuals with hearing impairments by converting sign language gestures into readable text and speech in real time.

## 🔍 Overview

This project integrates computer vision and deep learning (LSTM) to recognize and interpret hand gestures from a live video feed. It accurately identifies 12 different signs and converts them into corresponding text output. It also provides **voice translation**, making communication more seamless and accessible.

## 🖐️ Hardware Integration

As part of this system, we have **designed a specialized remote device** to capture sign gestures more accurately and efficiently. This remote captures the hand movements and sends the data to the system, which then translates the gesture into text and optionally into voice.

> ⚙️ This design is **patented** under the jurisdiction of the **Patent Office, Government of India**.

📄 [Patent Certificate – View here](https://drive.google.com/file/d/1Mms0lpSUdlNUe8PcOf89ni99fdxtFIPP/view?usp=sharing)

## 🎯 Features

- Real-time hand gesture recognition
- Text output for 12 distinct sign gestures
- Voice translation for interpreted gestures
- Hardware remote for more accurate gesture capture
- Sequential LSTM model for improved gesture understanding
- Spatial-temporal feature extraction using computer vision

## 🧠 Technology Stack

- **Language**: Python  
- **Libraries**: OpenCV, NumPy, TensorFlow/Keras  
- **Model**: LSTM (Long Short-Term Memory)  
- **Approach**: Computer vision + Deep Learning  

## 🚀 How It Works

1. Captures real-time video frames or remote sensor input
2. Preprocesses data and extracts spatial-temporal features
3. Feeds sequential data into an LSTM model
4. Predicts and displays the corresponding text
5. Converts text to voice (optional)

## 📈 Performance

- Achieved over 92% accuracy across 12 distinct signs
- Supports real-time gesture recognition and speech output
- Designed to be lightweight and accessible

## 💡 Impact

VOICE BRIDGE bridges the gap in communication for the hearing-impaired community by providing a reliable and practical solution. Its intuitive interface and real-time feedback make it suitable for everyday use, schools, hospitals, and public spaces.

## 📂 Future Enhancements

- Expand gesture recognition to alphabets, words, and sentences
- Develop cross-platform mobile and web applications
- Enhance the hardware remote for broader gesture sets
- Add multilingual speech translation

## 📎 Repository Link

[VOICE BRIDGE GitHub Repository](https://github.com/mahima16yadav/Voice-Bridge)

---

Feel free to clone the repository, explore the code, and contribute!
