# Hyperspectral Satellite Image Classification

A project exploring different CNN architectures (1D, 2D, 3D, and Hybrid) for hyperspectral image classification using the Pavia University dataset.

## Project Overview

This repository contains implementations of various Convolutional Neural Network (CNN) architectures for classifying hyperspectral satellite imagery. The project uses the publicly available Pavia University dataset as a benchmark to compare the performance of different CNN approaches:

- 1D CNN: Processes spectral information along the channel dimension
- 2D CNN: Captures spatial patterns within hyperspectral image patches
- 3D CNN: Jointly models both spatial and spectral information
- Hybrid CNN: Combines different CNN approaches for enhanced feature extraction

## Dataset

The project utilizes the **Pavia University** dataset, which is freely available for research purposes. This hyperspectral dataset was acquired by the ROSIS (Reflective Optics System Imaging Spectrometer) sensor during a flight campaign over Pavia, northern Italy.

### Dataset Details:
- Spatial resolution: 1.3 meters per pixel
- Image dimensions: 610×340 pixels
- Spectral bands: 103 (after removing noisy bands)
- 9 different land cover classes: 
  1. Asphalt
  2. Meadows
  3. Gravel
  4. Trees
  5. Metal sheets
  6. Bare soil
  7. Bitumen
  8. Self-blocking bricks
  9. Shadows

### Dataset Source:
You can download the Pavia University dataset from the Hyperspectral Remote Sensing Scenes repository maintained by the Computational Intelligence Group at the University of the Basque Country:
[https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes#Pavia_Centre_and_University](https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes#Pavia_Centre_and_University)

## Features

- Data preprocessing and normalization for hyperspectral imagery
- Implementation of various CNN architectures (1D, 2D, 3D, and Hybrid)
- Training and evaluation pipeline for model comparison
- Visualization tools for hyperspectral data and classification results

## Learning Outcomes

This project was developed to learn about:

- Processing and analyzing hyperspectral satellite imagery
- Implementing and comparing different CNN architectures for spectral-spatial data
- Understanding the trade-offs between model complexity and performance in hyperspectral classification
- Techniques for handling high-dimensional data with limited training samples


## References

1. Pavia University dataset from the Hyperspectral Remote Sensing Scenes: [https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes#Pavia_Centre_and_University](https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes#Pavia_Centre_and_University)


## License

This project is licensed under the MIT License - see the LICENSE file for details.
