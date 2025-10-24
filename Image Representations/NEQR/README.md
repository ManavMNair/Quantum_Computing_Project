# NEQR Image Encoding with Cirq

## Overview
This project demonstrates **NEQR (Novel Enhanced Quantum Representation)** encoding of grayscale images using **Cirq**, a quantum simulation library.  
It encodes classical images into quantum circuits, simulates them, and reconstructs the encoded images to evaluate fidelity through **PSNR** and **SSIM** metrics.

## Features
- Implements NEQR quantum image encoding and decoding.
- Simulates quantum circuits using **Cirq**.
- Supports multiple image resolutions (32×32, 16×16, 8×8, 4×4).
- Evaluates reconstruction quality using **PSNR** and **SSIM**.
- Visualizes original and reconstructed images side by side.

## Requirements
Ensure you have the following dependencies installed:
```bash
pip install cirq numpy matplotlib pillow opencv-python scikit-image

