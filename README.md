# Flood-Damage-Detection--CNN
Utilised Python libraries like TensorFlow/Keras, NumPy, and Matplotlib for model development and visualisation.  – Gained hands-on experience in Computer Vision, Geospatial Data Analysis, and Deep Learning mode
# Flood Damage Detection from Post-Hurricane Satellite Imagery using Convolutional Neural Networks

## Project Overview

This project develops an intelligent flood damage detection system using Convolutional Neural Networks (CNNs) to classify satellite images into **Damage** and **No Damage** categories after Hurricane Harvey (2017).

The study compares three deep learning architectures:

- VGG16
- ResNet50
- Custom CNN

Among the evaluated models, **VGG16 achieved the highest classification accuracy of approximately 93%**, demonstrating strong performance for satellite image classification. This project explores transfer learning, data augmentation, and CNN-based image analysis for disaster management. :contentReference[oaicite:2]{index=2}


# Objectives

- Detect flooded areas using satellite imagery
- Compare multiple CNN architectures
- Improve disaster response using AI
- Evaluate model performance using standard metrics


# Dataset

The project uses publicly available satellite images collected after Hurricane Harvey.

Images are classified into:

- Damage
- No Damage

Image Size:

128 × 128 RGB


# Technologies Used

- Python
- TensorFlow
- PyTorch
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Jupyter Notebook


# Deep Learning Models

- VGG16
- ResNet50
- Custom CNN



# Data Preprocessing

- Image resizing
- Data augmentation
- Normalization
- Train-validation-test split


# Results

| Model | Accuracy |
|--------|----------|
| VGG16 | 93% |
| ResNet50 | 89% |
| Custom CNN | 63% |


# Project Structure

Flood-Damage-Detection-CNN
│
├── dataset
├── notebooks
├── paper
├── images
├── results
├── requirements.txt
└── README.md

# Installation

bash
git clone https://github.com/YourUsername/Flood-Damage-Detection-CNN.git

cd Flood-Damage-Detection-CNN

pip install -r requirements.txt

# Running the Project

Open the Jupyter Notebook:
Flood_Damage_Detection.ipynb

Run all cells sequentially.

# Research Paper

The conference paper is included in the `paper` folder.

# Future Improvements

- Vision Transformers (ViT)
- EfficientNet
- U-Net segmentation
- Real-time flood monitoring
- Explainable AI (Grad-CAM)

# Author

**Sonu M.B**

M.Sc Data Analytics

Department of Computer Science

St. Joseph's College (Autonomous), Irinjalakuda

Email: sonuamith105@gmail.com

# License

This project is for educational and research purposes.
