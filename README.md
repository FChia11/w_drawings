# Image Cleaning and SSIM Evaluation

## 📌 Overview

This project performs **image cleaning** and then evaluates the similarity between the original and processed images using the **Structural Similarity Index (SSIM)**. SSIM is a perceptual metric that measures image quality degradation, commonly used for comparing image processing outputs.

## ✨ Features

- 🧼 **Image Cleaning**: Removes noise, normalizes images, or applies custom preprocessing.
- 🖤 **Grayscale Conversion**: Converts images to grayscale for SSIM computation.
- 📊 **SSIM Calculation**: Computes SSIM scores to assess similarity between image pairs.

## 🚀 Usage

1. Place the original images in your input directory (e.g., `./input/`).
2. Open the notebook:

   image_cleaning_ssim.ipynb

3. Run the cells sequentially in a Jupyter environment like:
   - Jupyter Notebook / JupyterLab
   - Google Colab
   - VS Code with Jupyter support

4. The notebook will:
   - Load images from an input folder
   - Clean and process the images
   - Display before/after visuals
   - Print SSIM scores

## 📦 Requirements

Python 3.x

Required libraries:

pip install annoy Pillow matplotlib opencv-python scikit-image numpy
