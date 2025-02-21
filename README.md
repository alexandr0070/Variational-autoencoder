# Variational Autoencoder (VAE) for Image Generation  

## Overview  

This notebook implements a **Variational Autoencoder (VAE)** using TensorFlow and Keras to generate anime-style face images.

### **Dataset**  
The model is trained on the **"soumikrakshit/anime-faces"** dataset from Kaggle. This dataset contains images of anime-style faces that are used to train the VAE. The images are preprocessed and normalized before training.  

### The **loss function** consists of:  
- **Reconstruction Loss (MSE)**: Ensures the output image is similar to the input.  
- **KL Divergence Loss**: Regularizes the latent space to ensure smooth interpolation between generated images.  

## Installation  

To run this notebook, install the necessary dependencies:  

```bash
pip install tensorflow numpy matplotlib kagglehub opencv-python seaborn
