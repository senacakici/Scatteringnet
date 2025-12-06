# ScatteringNet

A prototype neural network model for predicting particle radius from simulated small-angle X-ray scattering (SAXS) profiles.

## Overview

This project demonstrates how a simple feedforward neural network (MLP) can be used to learn the relationship between 1D scattering profiles and physical particle radii. The data is synthetically generated using a Gaussian approximation to scattering intensity and includes random noise to emulate experimental conditions.

## Features

- Synthetic scattering data simulation using NumPy
- Regression model using PyTorch
- MinMax scaling for normalization
- Evaluation with MSE loss
- Visualization of training loss and prediction accuracy

## Requirements

Install the required Python packages using:

```bash
pip install -r requirements.txt
