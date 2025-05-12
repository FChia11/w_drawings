# Image Cleaning and SSIM Evaluation

## 📌 Overview

This project performs **image cleaning** and then evaluates the similarity between the original and processed images using the **Structural Similarity Index (SSIM)**. SSIM is a perceptual metric that measures image quality degradation, commonly used for comparing image processing outputs.

## ✨ Features

- 🧼 **Image Cleaning**: Removes noise, normalizes images, or applies custom preprocessing.
- 🖤 **Grayscale Conversion**: Converts images to grayscale for consistent SSIM computation.
- 📊 **SSIM Calculation**: Computes SSIM scores to assess similarity between original and cleaned images.

## 🚀 Usage

- Run the script:

   ```bash
   python image_cleaning_ssim.py

## 📦 Requirements

Python 3.x

Required libraries:

pip install opencv-python scikit-image numpy
