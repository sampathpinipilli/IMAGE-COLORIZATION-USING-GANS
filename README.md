# 🎨 Image Colorization using GANs

This project uses **Generative Adversarial Networks (GANs)** to automatically colorize grayscale images using a deep learning approach implemented in TensorFlow.

## 🧠 Abstract
Image colorization has traditionally required human intervention. With deep learning, especially GANs, we can teach a model to generate realistic color images from grayscale inputs. This project builds and trains a GAN model on images to perform automatic colorization.

## 📂 Dataset
- Source: Custom dataset (COCO/ImageNet)
- Preprocessing: Resizing (120x120), grayscale conversion, normalization

## 🏗️ Model Architecture
- **Generator:** Multi-layer CNN with transposed convolutions and skip connections
- **Discriminator:** Deep CNN that classifies images as real or generated
- **Losses:** Binary cross-entropy (GAN), MSE (perceptual)

## 🏃 Training
- Optimizer: Adam (learning rate: 0.0005)
- Epochs: 150
- Batch size: 64

## 📈 Results
Below is an example of the output:
- **Left:** Grayscale input
- **Center:** GAN colorized output
- **Right:** Ground truth image

(Add your output image samples here)

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy, PIL, Matplotlib
- Google Colab

## 🚀 Getting Started
To run this project:
```bash
pip install -r requirements.txt
