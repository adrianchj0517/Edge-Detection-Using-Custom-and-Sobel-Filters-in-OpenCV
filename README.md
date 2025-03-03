# Edge Detection Using Custom and Sobel Filters in OpenCV

## 📌 Overview
This project implements **edge detection algorithms** using both **custom convolution kernels** and the **Sobel filter** in OpenCV. The goal is to process an image and detect its edges efficiently using gradient-based methods.

## 🔥 Features
- **Custom Edge Detection**: Implements a manual convolution method for detecting edges in x and y directions.
- **Sobel Edge Detection**: Uses OpenCV's built-in Sobel filter for gradient computation.
- **Grayscale Conversion**: Converts input images to grayscale for processing.
- **Image Processing & Visualization**: Reads an input image, applies edge detection, and visualizes results using Matplotlib.

## 📊 How It Works
1. **Custom Edge Detection (`edge_detection`)**:
   - Converts an image to grayscale.
   - Uses manually defined convolution kernels to compute gradients in x and y directions.
   - Computes the gradient magnitude and normalizes it for visualization.

2. **Sobel Edge Detection (`sobel_edge_detection`)**:
   - Converts an image to grayscale.
   - Applies OpenCV's Sobel filters to detect edges along x and y axes.
   - Computes the gradient magnitude and normalizes it for visualization.

## 🚀 Installation & Usage
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- OpenCV
- NumPy
- Matplotlib

### Installation
```bash
pip install opencv-python numpy matplotlib
