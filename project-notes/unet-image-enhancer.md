# Local U-Net Image Enhancer

A local web app for enhancing and upscaling images.

## Summary

This project provides a browser UI for uploading an image, previewing enhancement results, comparing before/after output, and downloading the processed image. The backend works locally and can use a built-in image enhancement path or an optional PyTorch U-Net checkpoint.

## Features

- Local browser interface.
- Upload, preview, compare, and download workflow.
- Pillow and NumPy enhancement fallback.
- Optional PyTorch U-Net super-resolution checkpoint.
- Training script for paired low-resolution and high-resolution images.

## Stack

- Python
- Flask
- Pillow
- NumPy
- PyTorch
- HTML, CSS, JavaScript

## What I Learned

- How to turn an ML/image-processing idea into a usable local app.
- How to keep an app functional even when optional model weights are missing.
- How paired image datasets are structured for super-resolution training.

