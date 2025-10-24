# MCQI Image Encoding with Cirq

## Overview
This project implements **MCQI (Multi-Channel Quantum Image Representation)** — a quantum encoding technique that represents **color images (RGB)** on a quantum system using **Cirq**.  
It simulates how classical color images can be mapped into quantum states through controlled rotation gates and then reconstructed to evaluate fidelity using **PSNR** and **SSIM** metrics.

The implementation dynamically handles different image sizes (8×8, 16×16, and 32×32) to demonstrate how resolution impacts encoding accuracy.

---

## Features
- Implements **MCQI encoding** for **RGB color images**.
- Uses **Cirq** for quantum circuit creation and simulation.
- Supports **multiple resolutions**: 8×8, 16×16, and 32×32.
- Performs **quantum image reconstruction** from measurement data.
- Evaluates results with **PSNR** and **SSIM** metrics.
- Provides **visual comparisons** of classical vs quantum-encoded images.

---

## Requirements
Install dependencies before running the notebook or script:

```bash
pip install cirq numpy matplotlib opencv-python scikit-image
