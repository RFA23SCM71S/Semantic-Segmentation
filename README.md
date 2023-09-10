# Semantic-Segmentation

## Problem Statement
The project aims to perform semantic segmentation on a dataset of pet images, distinguishing between cats and dogs by classifying each pixel in the images. This involves dataset preparation, labeling, and the development of a model to accurately segment and differentiate cats and dogs in images.

## Solution
Our approach involves data preparation, model development, and optimization for semantic segmentation of pet images (cats and dogs). Leveraging libraries like OpenCV, Matplotlib, NumPy, TensorFlow, and Keras, we performed the following steps:

1. **Data Handling:** We downloaded and labeled the dataset, created segmentation masks, and performed an 80-20 train-test split with 10% for validation.

2. **Model Building:** We designed two models, "My_Model" and "your_Model," with convolutional layers and skip connections. Both models were trained, with "My_Model" achieving around 70% accuracy. Additionally, we implemented SegFormer, a transformer-based model, achieving promising segmentation results.

![image](https://github.com/Raghukarn/Semantic-Segmentation/assets/119719960/971c93b3-1933-484c-a280-361f6c3e31db)
