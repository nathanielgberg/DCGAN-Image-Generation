# DCGAN Project

This repository contains the implementation of a Deep Convolutional Generative Adversarial Network (DCGAN) as part of the ECE-176 project. The goal is to generate realistic images by training a GAN on a specific dataset, exploring various architectures and hyperparameters.

## Overview

DCGANs combine convolutional neural networks with the GAN architecture to produce high-quality generated images. This project implements a DCGAN using [PyTorch/TensorFlow] (adjust depending on your framework) and provides:
- A comprehensive training pipeline.
- Evaluation metrics to assess the performance of both the generator and discriminator.
- A collection of generated images during the training process for qualitative analysis.

## Features

- **End-to-End Training:** Integrated pipeline from data preprocessing to model evaluation.
- **Modular Codebase:** Organized components including the generator, discriminator, and training loop for easy experimentation.
- **Customizable Hyperparameters:** Easily configurable learning rate, batch size, network architecture, and more.
- **Visualization:** Continuous generation and saving of output images during training.
- **YouTube Demonstration:** Detailed demonstration video available to show the training process and results.

## Repository Structure

```plaintext
├── notebook.pdf            # Project documentation or results overview in PDF format
└── project.ipynb           # Jupyter Notebook containing the code for the DCGAN

**## YouTube Demonstration**

For a detailed demonstration of the project and the training process, watch the YouTube video below: [DCGAN Project Demo](https://youtu.be/OXE5zRu8pFE)
