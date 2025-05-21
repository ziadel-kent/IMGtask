# 🖼️ Python Image Processing Project

## 🎯 Project Overview

This project implements a complete modular image processing pipeline using Python and OpenCV. It demonstrates key techniques such as color adjustment, noise reduction, blurring, edge detection, and feature extraction.

The code is designed with clarity, reusability, and robustness in mind. It supports various image formats and includes built-in error handling.

---

## ⚙️ Features & Techniques

1. *Color Adjustment*
   - Brightness and contrast manipulation using cv2.convertScaleAbs.

2. *Noise Reduction*
   - Non-local Means Denoising using cv2.fastNlMeansDenoisingColored.

3. *Gaussian Blurring*
   - Smoothing the image using cv2.GaussianBlur.

4. *Edge Detection*
   - Extracting object boundaries using the Canny algorithm.

5. *Feature Extraction*
   - Color histogram features from each RGB channel for object characterization.

---

## 🗂️ Input/Output

- *Supported Formats*: .jpg, .png, .tif
- *Output Files*: Saved in the /output directory
  - {filename}_brightness_contrast.jpg
  - {filename}_blur.jpg
  - {filename}_denoised.jpg
  - {filename}_edges.jpg
  - {filename}_features.npy

---

## 🚀 How to Run

1. Upload an image via the Colab upload interface.
2. Run all cells. The pipeline will:
   - Load the image
   - Apply each processing step
   - Save outputs in a local folder
   - Display the results

---

## 📌 File Structure

```plaintext
untitled12.py            # Main processing script
output/
  ├── image_brightness_contrast.jpg
  ├── image_blur.jpg
  ├── image_denoised.jpg
  ├── image_edges.jpg
  └── image_features.npy
