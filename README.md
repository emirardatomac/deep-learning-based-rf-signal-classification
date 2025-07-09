# Deep Learning Based RF Signal Classification

This project presents a deep learning approach to classify wireless RF signals by their modulation types. Using the **RadioML 2018.01A** dataset, we train a hybrid **CNN + LSTM** model to distinguish between 8 different modulation schemes from raw I/Q data.

> ✅ Final test accuracy: **90.66%**

---

## 📡 Selected Modulation Classes

- BPSK
- QPSK
- 16PSK
- 4ASK
- 32APSK
- 16QAM
- FM
- AM-DSB-WC

---

## 🧠 Model Architecture

- Separate CNN branches for I and Q inputs
- Feature merging followed by LSTM layer
- Fully connected layers with LeakyReLU + Dropout
- Softmax output for classification

---
## Dataset
Link : https://www.kaggle.com/datasets/pinxau1000/radioml2018/data

---

