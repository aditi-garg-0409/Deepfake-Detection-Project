 Deepfake Detection using Deep Learning (ResNeXt + LSTM)

## 📖 Overview
This project focuses on detecting **deepfake videos** using deep learning.  
It combines **Convolutional Neural Networks (CNNs)** and **Recurrent Neural Networks (RNNs)** for accurate detection.  

- **ResNeXt (CNN)** is used to extract spatial features from video frames.  
- **LSTM (RNN)** is used to learn temporal patterns across frames.  
- Together, they classify whether a video is **real or fake**.  

---

## 🚀 Features
- Deepfake detection using a hybrid **ResNeXt + LSTM** model.  
- Django-based web application for video upload and prediction.  
- Dockerized setup for easy deployment.  
- Works on both CUDA-enabled and non-CUDA systems.  

---
## 📂 Directory Structure
For ease of understanding the project is structured in below format
```
Deepfake_detection_using_deep_learning
    |
    |--- Django Application
    |--- Model Creation
    |--- Documentaion
```

## 🏗️ System Architecture
The system works as follows:  
1. Input video is uploaded by the user.  
2. Frames are extracted from the video.  
3. ResNeXt extracts features from each frame.  
4. LSTM analyzes these features across time.  
5. The final output predicts whether the video is **Real** or **Fake**.  

---

## 📊 Results
The model was trained on multiple videos with different frame counts.  
Below are the results achieved:  

| Frames Used | Accuracy |
|-------------|----------|
| 10          | 84.21%   |
| 20          | 87.79%   |
| 40          | 89.34%   |
| 60          | 90.59%   |
| 80          | 91.49%   |
| 100         | 93.58%   |
