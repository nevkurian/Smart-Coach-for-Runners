# 🏃‍♂️ Smart Coach for Runners

An IoT + Machine Learning project that helps runners monitor their physical activity and predict fatigue levels using sensor data and physiological indicators.

---

## 📌 Project Overview

**Smart Coach for Runners** is a wearable fitness monitoring solution that collects motion and biometric data through sensors, processes the data via a microcontroller (ESP32), and uses a machine learning model to predict whether a runner is experiencing fatigue.

The system provides real-time feedback using a vibration motor, helping runners take breaks before reaching dangerous fatigue levels.

---

## 🧠 Machine Learning Component

The dataset used for fatigue prediction (`running_with_binary_fatigue.csv`) contains features such as:

- Age, Gender, Height, Weight
- Activity Type and Duration
- Heart Rate, Stress Level
- Sleep Hours, Hydration Level
- BMI, Fitness Level
- **Fatigue** (Binary: 0 = Not Fatigued, 1 = Fatigued)

### 📊 ML Workflow
1. Data preprocessing (encoding, scaling, cleaning)
2. Train-test split
3. Random Forest Classifier for fatigue prediction
4. Model evaluation using classification metrics

---

## 📁 Project Structure

```bash
.
├── iot_proj.ipynb                    # ML implementation in Jupyter Notebook
├── running_with_binary_fatigue.csv  # Dataset used for training/testing
├── README.md                         # Project description and documentation
