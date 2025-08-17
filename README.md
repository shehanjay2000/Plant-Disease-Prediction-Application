# Plant Disease Prediction Application

![Streamlit App](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)



This app utilizes a Kaggle dataset to train a machine learning model for predicting plant diseases from images. Users can preprocess data, train the model, and perform predictions on new plant images. The project is designed for educational and practical use in plant health monitoring.



## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Model Training](#model-training)
- [Project Structure](#project-structure)


## Overview

This repository contains the source code for a Plant Disease Prediction Application. The project utilizes a machine learning model to identify common plant diseases from images. The application is built with a Python backend and provides a user-friendly interface to upload images and receive instant predictions.ting.

## Features

- **Data Preprocessing**: Prepare and split the dataset into training, testing, and validation sets.
- **Model Training**:  Train a machine learning model using the processed dataset.
- **Prediction**: Perform real-time disease prediction on new plant images.
- **Model Performance**: Accuracy, classification report, and confusion matrix visualization.
- **Error Handling**: User-friendly messages for invalid inputs or loading issues.



## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/shehanjay2000/Plant-Disease-Prediction-Application.git
   cd Disease-Prediction-Application
   ```

2. **Set Up Virtual Environment** (Recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirement.txt
   ```

4. **Download Dataset**:
   - Get the dataset from Kaggle Plant Disease Dataset
   - Extract and place it in the data/ folder with train/, test/, and valid/ subdirectories.

5. **Train the Model** (If not already done):
   - Run the Jupyter notebook: `/model_training.ipynb`.
   - This generates `trained_model.keras`.



## Model Training

The model is trained in `model_training.ipynb` using TensorFlow:

- **Preprocessing**: Image resizing, normalization, and dataset splitting
- **Training**: Train the model with the dataset in train/.
- **Saving**: Save the trained model to trained_model.keras

Run the notebook to retrain if needed.



## Project Structure

```
plant-disease-prediction/
├── test/                # Test dataset images
├── train/               # Training dataset images
├── valid/               # Validation dataset images
├── model_training.ipynb    # Model training script
├── README.md            # Project documentation
├── requirements.txt     # Python dependencies
├── trained_model.keras  # Trained model file
├── training_history.json # Training history
├── home_page.jpg        # Homepage image
├── main.py              # Main script
├── Test_Plant_Disease.ipynb # Test scripts
```

