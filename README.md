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

Python 3.9+

Required libraries:

pip install annoy Pillow matplotlib opencv-python scikit-image numpy

## 📝 License

## Copyright © 2025 Francesca Chiaradia

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
