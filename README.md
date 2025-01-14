# Kernel PCA Analysis - Kernel Principal Component Analysis

![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)

This repository contains the Python code used to explore and compare different methods of Kernel Principal Component Analysis (Kernel PCA). This project is part of the thesis I am preparing for my Master 1 in Applied Mathematics at Université Paris-Dauphine.

## 📜 Context

Kernel PCA is an extension of traditional Principal Component Analysis (PCA) that allows for handling data with nonlinear relationships. By using specific kernels, such as RBF or polynomial kernels, this method projects the data into a higher-dimensional space to capture complex structures.

In this project, we demonstrate the advantages of Kernel PCA through an example using a synthetic dataset (S-curve). We compare the results obtained with various kernels to highlight their differences and applications.

## 📂 Repository Content

- **`kernel_pca_analysis.py`**: Main script containing the code to generate data, apply Kernel PCA, and visualize the results.
- **Figures**: Visualizations of the projections obtained with different kernels (generated by running the code).
- **`README.md`**: This file explaining the repository content.

## 🚀 Key Features

1. **Data Generation**:
   - Synthetic 3D \textit{S-curve} dataset with added noise.

2. **Kernel PCA Application**:
   - Comparison of several kernels:
     - Linear
     - Polynomial
     - RBF (Radial Basis Function)
     - Sigmoid
     - Cosine

3. **Distance Analysis**:
   - Calculation of relative differences between pairwise distances in the original and transformed spaces.

4. **Visualizations**:
   - Projections of the data in the transformed space for each kernel.

## 🖼️ Example Results

### Original Data
The synthetic 3D S-curve dataset used for this project:


### Projections with Different Kernels
Below are the projections obtained for various kernels after applying Kernel PCA:

- Linear Kernel

- RBF Kernel

- Polynomial Kernel

## 📊 Observed Results
The following table summarizes the relative differences in pairwise distances between the original and transformed spaces for each kernel:

Kernel	 : Relative Difference

Linear	 : $3.29 \times 10^{-16}$

Polynomial	: 0.60

RBF	: 0.93

Sigmoid	: 0.79

Cosine	: 0.44

## Key Insights:
Linear Kernel: Perfectly preserves distances but fails to capture nonlinear relationships. 

Polynomial Kernel: Captures nonlinear interactions while moderately preserving distances.

RBF Kernel: Unrolls the S-curve effectively but significantly alters distances.

Sigmoid Kernel: Produces transformations similar to RBF but slightly less intense.

Cosine Kernel: Useful for angular relationships, providing a balance between preservation and transformation.

## 📧 Contact
For any inquiries about this project or my thesis, feel free to reach out to me via GitHub or email.
