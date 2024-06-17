# Low-Light-Enhancement

# Intro
This repository contains the implementation of a Zero-DCE (Zero-Reference Deep Curve Estimation) model for image enhancement using TensorFlow/Keras. The Zero-DCE model aims to enhance low-light images by improving color constancy, exposure, and illumination smoothness.

# Requirements
1. Python 3.x
2. TensorFlow 2.x
3. Keras
4. NumPy
5. Matplotlib
6. PIL (Python Imaging Library)

# Dataset
[Here](https://www.kaggle.com/datasets/soumikrakshit/lol-dataset)

# Model Architecture
Implemented as a class Build_DCE_NET() in ZERO_DCE.ipynb file.
![image](https://github.com/palswayam5/Low-Light-Enhancement/assets/97727708/6cb69ead-ffae-4627-8c3b-4d65d13fdc6c)

# Custom Loss Functions
Several custom loss functions are implemented to optimize the model:

1. Color Constancy Loss (color_constancy_loss): Measures the consistency of color across images.
2. Exposure Loss (exposure_loss): Evaluates the exposure of images based on a specified grey level (E).
3. Illumination Smoothness Loss (illumination_smoothness_loss): Ensures smoothness of illumination in enhanced images.

# Results
PSNR Value on the unseen dataset images - 27.8 (Approximately)

   
