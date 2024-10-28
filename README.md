# Denoising Bioluminescence Microscopy with Deep Learning

Welcome to the **Denoising Bioluminescence Microscopy** workshop repository! This repository provides the materials and scripts necessary to denoise microscopy images using deep learning, specifically aimed at enhancing noisy bioluminescence images. This repository includes pre-trained models, scripts, and a Google Colab notebook to make it easier for participants to follow along during the workshop.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Usage](#usage)
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
│   └── /prediction           # Inference of the image
│   └── /source				  # Raw microscopy images
│
├── /models                   # Pre-trained models or saved checkpoints
│   └── denoising_model       # Example deep learning model (e.g., a UNet model)
│
├── /media                    # media files
│
├── /Instructions             # instructions for the workshop
│
├── /denoising_workshop.ipynb # step-by-step guide for denoising bioluminescence images
│
└── README.md                 # This file
```

## Usage

### Google Colab

The easiest way to follow along with the workshop is by using the provided Google Colab notebook.

1. Open the [denoising_workshop.ipynb](./notebooks/denoising_workshop.ipynb) notebook in Google Colab by clicking [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LuisFMCuriel/MINDLAB-Denoising-bioluminescence-images/blob/main/denoising_workshop.ipynb).
2. Follow the step-by-step instructions to run the model on sample data or your own images.
3. No local setup or GPU is required as Colab provides these resources.

### Example Results

Below is an example showing a noisy bioluminescence microscopy image and the result after denoising with the provided model:

![Denoising](https://github.com/LuisFMCuriel/MINDLAB-Denoising-bioluminescence-images/blob/main/media/fig.png)

### License

This project is licensed under the MIT License - see the LICENSE file for details.

### Contributing

Contributions are welcome! Please feel free to submit issues or pull requests to help improve the repository.


## References

[1] Morales-Curiel, L. F., Castro-Olvera, G., Gonzalez, A., Lin, L., El-Quessny, M., Porta-de-la-Riva, M., Severino, J., Battle, L., Ramallo, D., Ruprech, V., Loza-Alvarez, P., & Krieg, M. (2022). Volumetric imaging of fast cellular dynamics with deep learning enhanced bioluminescence microscopy. Communications Biology, 5(1), 1330. doi:10.1038/s42003-022-04292-x
