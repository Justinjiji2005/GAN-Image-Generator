# GAN Image Generator

## Overview
A Deep Convolutional Generative Adversarial Network (DCGAN) built with 
TensorFlow that generates realistic handwritten digit images from random noise.

## How it Works
- Generator network learns to create fake digit images from random noise
- Discriminator network learns to tell real from fake images
- Both networks compete and improve each other over 30 epochs
- Result: Generator can produce realistic handwritten digits

## Model Architecture
### Generator
- Input: 100-dimensional random noise vector
- 4 layer Conv2DTranspose network
- Output: 28x28 grayscale image

### Discriminator
- Input: 28x28 grayscale image
- 3 layer Conv2D network
- Output: Real or Fake classification

## Training Details
- Dataset: MNIST (60,000 handwritten digit images)
- Epochs: 30
- Batch size: 32
- Optimizer: Adam (learning rate 0.0001)
- Framework: TensorFlow / Keras
- Hardware: GPU (Google Colab T4)

## Results
The GAN successfully learned to generate handwritten digit images
from random noise after 30 epochs of training.

## Tools Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab (T4 GPU)

## Author
Justin Thomas — B.Tech Data Science, Manipal University Dubai
