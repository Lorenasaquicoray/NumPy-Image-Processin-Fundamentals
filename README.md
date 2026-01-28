# NumPy Image Processing Fundamentals
# Computer Vision Foundations & Image Processing Pipeline

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![NumPy](https://img.shields.io/badge/Library-NumPy-013243?style=flat-square&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-orange?style=flat-square)

## 📖 Project Overview
This repository explores the mathematical underpinnings of Computer Vision by implementing core image processing algorithms from scratch. Rather than relying solely on high-level library abstractions, this project treats images as high-dimensional NumPy tensors to perform low-level matrix manipulation, statistical analysis, and procedural synthesis.

These techniques establish the preprocessing workflow required for modern Machine Learning and Deep Learning (CNN) pipelines.

## 🚀 Key Competencies Demonstrated

### 1. Tensor Manipulation & Data Filtering
* Utilization of **NumPy** for high-performance matrix operations.
* Implementation of Boolean masking and logical operators to filter high-dimensional datasets.
* Data dimensionality reduction and reshaping.

### 2. Feature Extraction & Segmentation
* **Channel Decomposition:** Isolating RGB spectral channels for independent feature analysis.
* **Binary Thresholding:** Implementing segmentation logic to separate foreground subjects from backgrounds (a prerequisite for object detection).
* **Grayscale Conversion:** Reducing computational complexity by transforming 3-channel tensors into single-channel intensity matrices.

### 3. Statistical Analysis (Algorithmic Implementation)
* **Manual Histogram Computation:** Engineered a custom traversal algorithm (nested loops) to calculate pixel intensity frequency without relying on built-in library functions.
* **Data Binning:** Aggregating continuous pixel data into discrete intervals to analyze contrast distributions and noise levels.
