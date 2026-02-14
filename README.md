# Barcode Detector

## Description
This project implements a barcode detection system using computer vision and deep learning techniques. It classifies images as containing a barcode or not.

## Features
- Detects the presence of barcodes in images.
- Uses Convolutional Neural Networks (CNNs) for classification.
- Visualizes results with sample images throughout the process.

## Dataset
The dataset consists of images divided into two categories:
- **0**: Images without barcodes.
- **1**: Images with barcodes.

The data is organized in the `0/` and `1/` directories.

## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- Matplotlib
- Scikit-image

## Getting Started

### Prerequisites
Install the required packages:
```bash
pip install opencv-python-headless tensorflow matplotlib scikit-image
```

### Running the Project
The main code is located in `Barcode Detector.ipynb`. You can run this notebook using Jupyter Notebook or VS Code.

**Note:** The notebook was originally designed to run on Google Colab and contains code to mount Google Drive. If running locally with the provided folders `0/` and `1/`, you will need to adjust the `DATASET_PATH` variable in the notebook to point to the local directory (e.g., the current folder) instead of the Google Drive path.

## Structure
- `Barcode Detector.ipynb`: Main Jupyter Notebook containing the code for training and evaluation.
- `0/`: Directory containing images without barcodes.
- `1/`: Directory containing images with barcodes.
