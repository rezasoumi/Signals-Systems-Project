# Signals & Systems Project: JPEG Compression and Noise Neutralization
The project of the course Signals and Systems under the sharif university of technology.

## Overview

This repository contains the implementation of two phases of the Signals & Systems course project at Sharif University of Technology. The project focuses on **JPEG Compression** and **Noise Neutralization** techniques.

### Phase 1: JPEG Compression and Decompression

In this phase, we have implemented a JPEG compression and decompression system. The JPEG (Joint Photographic Experts Group) algorithm is a widely used method for compressing digital images while preserving their quality. Our implementation covers the following main steps:

- Applying the Discrete Cosine Transform (DCT) on 8x8 blocks.
- Quantization of DCT coefficients using quantization tables.
- Zigzag coding.
- Decoding the compressed image back to its original form.

### Phase 2: Noise Neutralization for Noisy Channels

In this phase, we focused on developing a noise neutralization system to counteract the effect of noise when transmitting signals through a noisy channel. The implementation involves the following key steps:

- Modeling the noisy channel to understand the noise characteristics.
- Implementing suitable actions to reduce the impact of noise. (we didn't use Median Filter, Wiener Filter, ... here)
- Evaluating the system's performance through quantitative metrics like Mean Squared Error (MSE).

## How to run

The codes are in Project_SignalsSystems.ipynb
you can download this repo and run sections respectively.
