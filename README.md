# Crop Disease Classification

## Project Overview
**Crop Disease Classification** is a deep learning-based system designed to detect and classify diseases in crop leaves using **Convolutional Neural Networks (CNNs)**.  
This project helps farmers, agricultural experts, and researchers identify leaf diseases quickly, enabling timely preventive measures to improve crop yield and reduce losses.

The system leverages a dataset of healthy and diseased crop leaves. Images are preprocessed, normalized, and augmented to improve model performance. The trained CNN model can classify multiple disease types and provides visualizations for easy interpretation.

---

## Features
- Uses **CNN** for high-accuracy image classification  
- Python scripts for **training** and **prediction**  
- Generates visualizations of predictions for model interpretability  
- Easily extendable for **real-time detection** and **multi-crop support**  

---

## Dataset
- Original dataset: PlantVillage dataset containing images of healthy and diseased leaves.  
- Images are categorized into different disease classes.  
- Preprocessing includes:
  - Resizing images to uniform dimensions
  - Normalization of pixel values
  - Data augmentation (flipping, rotation, zoom) to improve model generalization  

> **Note:** Only a small sample of the dataset is included in this repo for demonstration. Full dataset can be downloaded from [PlantVillage Dataset](https://www.kaggle.com/emmarex/plantdisease).  
