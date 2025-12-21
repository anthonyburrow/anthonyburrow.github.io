---
layout: project
title: SNIaSpectrumNN
description: (WIP) Neural network models for predicting observational
 properties of SNe Ia using their optical spectra.
repo: SNIaSpectrumNN
pinned: True
categories: [Python, data science]
tags: [python]
---

## About

This project provides a collection of models that predict various properties of
SNe Ia (e.g., Si II velocity, pseudo-equivalent widths, line strengths) given
only their optical spectrum. Each model shares a common transformer-based
autoencoder backbone that learns a compact representation of the spectrum,
which is then used by task-specific output heads.

### Architecture

- **Base Encoder**: A transformer autoencoder with gated residual network
layers that learns spectral features.
- **Pre-training**: The autoencoder is pre-trained on spectrum reconstruction
to learn meaningful representations.
- **Task-Specific Heads**: After pre-training, the encoder backbone is
fine-tuned with different output heads for specific prediction tasks.

## Example

Coming soon!
