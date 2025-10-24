# FRQI Image Encoding with Cirq

## Overview
This project implements **FRQI (Flexible Representation of Quantum Images)** encoding of grayscale images using **Cirq**, a Python framework for quantum circuit simulation.  
It converts classical images into quantum representations, simulates quantum measurements, and reconstructs the images to evaluate fidelity through **PSNR** and **SSIM** metrics.

The notebook supports variable image sizes to demonstrate how image resolution affects encoding and reconstruction accuracy.

---

## Features
- Implements **FRQI encoding and decoding** for grayscale images.
- Uses **Cirq** to simulate quantum circuits.
- Works with multiple resolutions: 32×32, 16×16, 8×8, and 4×4.
- Reconstructs images from quantum measurements.
- Evaluates reconstruction using **PSNR** (Peak Signal-to-Noise Ratio) and **SSIM** (Structural Similarity Index).
- Visualizes both **original** and **reconstructed** images for comparison.

---

## Requirements
Install the required dependencies using:

```bash
pip install cirq numpy matplotlib pillow scikit-image

