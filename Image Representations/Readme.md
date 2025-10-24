# Quantum Image Encoding Methods

## Overview
This folder contains implementations of three major **quantum image representation models** — **FRQI**, **NEQR**, and **MCQI** — using **Cirq** for quantum simulation.  
Each model demonstrates how classical images can be encoded, simulated, and reconstructed in quantum systems.

---

## Encodings Included

| Encoding | Description | Image Type | Key Feature |
|-----------|--------------|-------------|--------------|
| **FRQI** (Flexible Representation of Quantum Images) | Encodes grayscale images as rotation angles on a single qubit. | Grayscale | Simple and compact representation |
| **NEQR** (Novel Enhanced Quantum Representation) | Uses binary intensity encoding for grayscale pixel values. | Grayscale | Precise pixel-value encoding |
| **MCQI** (Multi-Channel Quantum Image Representation) | Extends quantum encoding to RGB color images. | Color | Multi-channel quantum image support |

---

## Project Structure

```plaintext
quantum_image_encodings/
│
├──FRQI
  ├── FRQI_for_variable_sizes.ipynb   # FRQI grayscale encoding
├──NEQR
  ├── NEQR_for_variable_sizes.ipynb   # NEQR grayscale encoding
├──MCQI
  ├── MCQI_for_variable_sizes.ipynb   # MCQI RGB encoding

```

---

## Requirements
All scripts use Python 3.10+ and require the following packages:
```bash
pip install cirq numpy matplotlib pillow opencv-python scikit-image

