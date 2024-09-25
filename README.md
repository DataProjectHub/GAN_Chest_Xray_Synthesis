# GAN-based Chest X-ray Image Synthesis

## Project Overview
This project implements a **Generative Adversarial Network (GAN)** to generate synthetic chest X-ray images for data augmentation and research purposes. The goal is to tackle data scarcity in medical imaging by creating realistic X-ray images of both **normal** and **pneumonia** cases.

## Features
- Generates synthetic chest X-ray images to improve dataset balance.
- GAN architecture with a generator and discriminator model.
- Ability to augment training data for medical AI models.
- Useful in addressing challenges such as data imbalance and data limitations in healthcare.

## Dataset
The **Chest X-ray dataset** used for this project can be found on [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).

## Getting Started

### Prerequisites
- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib

Install the required packages using the following command:
```bash
pip install -r requirements.txt
