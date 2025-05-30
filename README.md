
# 😄 Emotion Detection Using Spiking Neural Networks (CSNN)

This project explores real-time facial emotion recognition using a **Convolutional Spiking Neural Network (CSNN)**. Inspired by the biological workings of the human brain, this energy-efficient model is designed for performance on neuromorphic hardware while maintaining high accuracy on emotion classification tasks.

---

## 🎯 Objective

To build a power-efficient, real-time facial emotion recognition system using biologically inspired Spiking Neural Networks (SNNs) trained on the **FER2013** dataset.

---

## ✨ Features

- 📸 **Facial Emotion Recognition**: Classifies faces into seven emotion categories (e.g., happy, sad, angry).
- 🧠 **Neuromorphic Design**: Uses Spiking Neural Networks for energy-efficient and real-time processing.
- ⚡ **Convolutional Architecture**: Incorporates convolutional and fully connected layers with spiking neurons (LIF & IFNode).
- 🔁 **Temporal Encoding**: Utilizes spike-based information propagation, mimicking real brain-like activity.
- 📊 **Performance Optimization**: Batch normalization, early stopping, and adaptive learning via Adam optimizer.

---

## 🧪 Technologies Used

- **Frameworks**: PyTorch, SpikingJelly
- **Language**: Python
- **Libraries**: NumPy, Matplotlib, Scikit-learn, TorchInfo, TorchVision
- **Environment**: Google Colab / Jupyter Notebook / VS Code

---

## 🧠 Model Architecture

- Input → Convolution + Pooling (2 Layers) → Spiking Layers (IF + LIF) → Fully Connected Layers (3 Layers) → Output
- Neuron Types: **Leaky Integrate-and-Fire (LIF)**, **Integrate-and-Fire (IFNode)**
- Loss: Custom MSE-based loss with spike rate tuning
- Optimizer: Adam (learning rate = 1e-3)

---
## 📂 Dataset

**FER2013** (Facial Expression Recognition 2013 Dataset):  
- Grayscale facial images (48x48)  
- 7 Emotion classes: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral

---


