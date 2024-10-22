# Denoising Bioluminescence Microscopy with Deep Learning

Welcome to the **Denoising Bioluminescence Microscopy** workshop repository! This repository provides the materials and scripts necessary to denoise microscopy images using deep learning, specifically aimed at enhancing noisy bioluminescence images. This repository includes pre-trained models, scripts, and a Google Colab notebook to make it easier for participants to follow along during the workshop.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Usage](#usage)
  - [Google Colab](#google-colab)
  - [Local Setup](#local-setup)
- [Example Results](#example-results)
- [License](#license)
- [Contributing](#contributing)

## Introduction

Bioluminescence microscopy is a powerful imaging technique, but it often suffers from high levels of noise, especially in low-light conditions. Deep learning-based methods, particularly convolutional neural networks (CNNs), have shown great promise in addressing these issues. In this workshop, we will explore how to apply deep learning models to denoise bioluminescence microscopy images, and participants will be guided through the process using Google Colab.

## Features

- **Deep learning-based denoising models**: Pre-trained deep learning models, such as UNet, are provided for denoising tasks.
- **Google Colab notebook**: Easy-to-use notebook for running the models directly on the cloud, without the need for local setup.
- **Training scripts**: Python scripts for preprocessing data and training custom models if desired.
- **Sample data**: One sample bioluminescence microscopy image is included to demonstrate the process.

## Getting Started

To get started, you can run the notebook in [Google Colab](#google-colab) or set up the repository locally. Detailed instructions for both are provided below.

## Repository Structure

```plaintext
/denoising-biolum-microscopy
│
├── /data                     # Sample or synthetic data for training/testing
│   └── /raw                  # Raw microscopy images
│   └── /processed            # Preprocessed or noisy/clean image pairs
│
├── /models                   # Pre-trained models or saved checkpoints
│   └── denoising_model.h5    # Example deep learning model (e.g., a UNet model)
│
├── /notebooks                # Google Colab notebooks for participants
│   └── denoising_workshop.ipynb
│
├── /scripts                  # Python scripts for preprocessing, training, etc.
│   └── train.py              # Script to train a model from scratch
│   └── preprocess.py         # Data preprocessing script
│
└── README.md                 # This file
```

## Usage

### Google Colab

The easiest way to follow along with the workshop is by using the provided Google Colab notebook.

1. Open the [denoising_workshop.ipynb](./notebooks/denoising_workshop.ipynb) notebook in Google Colab.
2. Follow the step-by-step instructions to run the model on sample data or your own images.
3. No local setup or GPU is required as Colab provides these resources.

### Local Setup

If you prefer to run everything locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/denoising-biolum-microscopy.git
   cd denoising-biolum-microscopy ```

2. **Install dependencies:**

Make sure you have Python 3.6 or higher. Install the required libraries:


