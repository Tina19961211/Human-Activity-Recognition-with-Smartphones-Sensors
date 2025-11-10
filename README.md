# Human Activity Recognition with Smartphone Sensors

This project implements a full data-analysis workflow for **Human Activity Recognition (HAR)** using accelerometer and gyroscope sensor data collected from smartphones. The goal is to evaluate both deep-learning and classical machine-learning methods to distinguish between various physical activities — showcasing how everyday devices can be used for **wearable technology, rehabilitation, prosthetic feedback, and biomechanics applications**.

---

## 📋 Project Overview
- **Data Source:** Tri-axial accelerometer and gyroscope signals captured by smartphone sensors during daily activities.  
- **Preprocessing:** Noise filtering, segmentation into fixed-length windows, normalization, and feature extraction (time- and frequency-domain).  
- **Modeling:**  
  - Classical ML methods (SVM, Random Forest) using extracted features.  
  - Deep-learning (1D CNN) trained directly on raw segmented signals.  
- **Goal:** Develop robust models for accurate classification of human activities and explore the potential of smartphone-based wearable sensors for real-time motion monitoring and rehabilitation feedback.

---

## 🧰 Technologies & Libraries
- **Language:** Python 3.x  
- **Environment:** Jupyter Notebook (`human-activity-recognition-with-smartphones-sensor.ipynb`)  
- **Libraries:** Pandas, NumPy, SciPy, Scikit-learn, TensorFlow/Keras, Matplotlib, Seaborn

---

## 🚀 Usage Instructions

**1. Clone the repository**

```bash
git clone https://github.com/Tina19961211/Human-Activity-Recognition-with-Smartphones-Sensors.git
