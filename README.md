# 🔊 UrbanSound8K Audio Classification

A lightweight **Audio Classification** project built with **TensorFlow** that classifies urban sounds into **10 environmental sound classes** using **39 MFCC features** extracted with **Librosa**.

## 🚀 Highlights

- 🎯 Test Accuracy: **~90%**
- 🧠 Artificial Neural Network (ANN)
- ⚙️ ~50K+ Trainable Parameters
- 🎵 Feature Extraction using **39 MFCCs**
- 🔍 Supports prediction on custom `.wav` audio files

## 📂 Dataset

**UrbanSound8K**

| Class | Samples |
|------|---------:|
| air_conditioner | 1000 |
| car_horn | 429 |
| children_playing | 1000 |
| dog_bark | 1000 |
| drilling | 1000 |
| engine_idling | 1000 |
| gun_shot | 374 |
| jackhammer | 1000 |
| siren | 929 |
| street_music | 1000 |

## 🛠 Tech Stack

- TensorFlow
- Librosa
- NumPy
- Pandas

## 🧠 Model

- Input: **39 MFCC Features**
- Network: **Fully Connected Artificial Neural Network (ANN)**
- Parameters: **50K+**
- Loss: **Categorical Crossentropy**
- Optimizer: **RMSProp**

## 📸 Sample Prediction

![Sample Prediction](images/sample_prediction.png)

## 📁 Project Structure

```
├── UrbanSound8K/
├── model/
├── notebooks/
├── predict.py
├── train.py
├── requirements.txt
└── README.md
```

## 📈 Results

- **Test Accuracy:** ~90%
- Predicts one of the following 10 classes:
  - Air Conditioner
  - Car Horn
  - Children Playing
  - Dog Bark
  - Drilling
  - Engine Idling
  - Gun Shot
  - Jackhammer
  - Siren
  - Street Music

## 📜 License

This project is intended for educational and learning purposes.
