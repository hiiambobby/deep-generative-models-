# 🧠 Deep Generative Models

This repository contains my hands-on implementations and experiments with various deep generative models like Variational Autoencoders (VAEs) and Generative Adversarial Networks (GANs). The goal is to understand how these models work and apply them to datasets like CelebA and MNIST.

---

## 📌 Implemented Models

| Model | Dataset | Description |
|-------|---------|-------------|
| ✅ VAE | CelebA | Variational Autoencoder trained to generate human faces |
| ✅ GAN | MNIST  | A simple GAN generating handwritten digits |

---
## 📁 Project Structure

deep-generative-models/
│
├── vae-celeba/
│ ├── train.py
│ ├── model.py
│ └── README.md
│
├── gan-mnist/
│ ├── train.py
│ ├── generator.py
│ ├── discriminator.py
│ └── README.md
│
└── README.md
---
### 🔧 Requirements

- Python 3.8+
- PyTorch
- torchvision
- matplotlib
- tqdm
- numpy
