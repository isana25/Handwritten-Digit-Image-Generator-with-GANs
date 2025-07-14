# Handwritten Digit Image Generator with GANs

A PyTorch implementation of Generative Adversarial Networks (GANs) to generate realistic handwritten digit images similar to the MNIST dataset.

## 🎯 Overview

This project demonstrates the power of GANs in generating synthetic handwritten digits through adversarial training. The generator network learns to create realistic digit images while the discriminator network learns to distinguish between real and generated images.

## ✨ Features

- **PyTorch-based GAN implementation**
- **MNIST dataset training**
- **Real-time visualization** of generated images
- **Loss tracking** and plotting
- **Model persistence** for reuse


## 🚀 Quick Start

### Prerequisites

- Python 3.x
- PyTorch
- torchvision  
- matplotlib
- numpy

### Run the Notebook

**📖 Check the working notebook here:**  
[Open in Google Colab](https://colab.research.google.com/drive/1n5Cl67bODp2iMdpvfqbxmoFpC1CcXIAb?usp=sharing)

### Training Steps

1. **Setup** - Import libraries and configure device
2. **Data Loading** - Download and preprocess MNIST dataset
3. **Model Definition** - Define Generator and Discriminator architectures
4. **Training Loop** - Adversarial training with loss visualization
5. **Results** - Generate and display synthetic digits

## 🏗️ Architecture

| Component | Description |
|-----------|-------------|
| **Generator** | Transforms random noise (100D) → digit images (784D) |
| **Discriminator** | Classifies images as real/fake (784D → 1D) |
| **Loss Function** | Binary Cross Entropy |
| **Optimizer** | Adam (lr=0.0002, β₁=0.5, β₂=0.999) |

## 📊 Results

- **Progressive improvement** in generated digit quality
- **Stable training** with balanced generator/discriminator losses
- **Diverse digit generation** across all classes (0-9)

## 🔧 Hyperparameters

- **Batch Size**: 128
- **Noise Dimension**: 100
- **Learning Rate**: 0.0002
- **Epochs**: 50
- **Image Size**: 28×28

## 🚀 Next Steps

- [ ] Implement Deep Convolutional GAN (DCGAN)
- [ ] Add conditional generation for specific digits
- [ ] Try different datasets (CIFAR-10, CelebA)
- [ ] Explore advanced GAN variants (WGAN, StyleGAN)

⭐ **Star this repository if you found it helpful!**


