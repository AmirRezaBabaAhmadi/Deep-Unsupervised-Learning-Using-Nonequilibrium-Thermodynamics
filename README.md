# Deep Unsupervised Learning using Nonequilibrium Thermodynamics

This repository provides a tutorial and implementation of a diffusion model using a Multi-Layer Perceptron (MLP) to denoise and generate data samples from the Swiss Roll dataset. This guide covers how to set up, train, and evaluate the diffusion model, demonstrating its application in generative modeling through reverse diffusion.

## Overview

The diffusion model presented in this project leverages an MLP to approximate the reverse diffusion process, gradually transforming noise into coherent data samples. The project includes code for defining the model, training it on a 2D projection of the Swiss Roll dataset, and visualizing the results.

## Features

- **Diffusion Model Implementation**: A neural network-based model that performs reverse diffusion to generate data samples.
- **Swiss Roll Dataset**: Uses a 2D projection of the Swiss Roll dataset for training and testing.
- **Customizable MLP Architecture**: The MLP model is flexible and can be easily modified for different tasks.
- **Visualization of Results**: Generates plots that show the diffusion process and the generated samples at different steps.

## Requirements

To run the code, you will need Python and the following libraries:

- `torch` (PyTorch)
- `numpy`
- `matplotlib`
- `tqdm`
- `scikit-learn`

## Acknowledgements

- The original authors and contributors of *Deep Unsupervised Learning using Nonequilibrium Thermodynamics* for their foundational work in diffusion models. [Read more](https://arxiv.org/abs/1503.03585)
