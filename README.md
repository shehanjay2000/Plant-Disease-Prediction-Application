Plant Disease Prediction Application

Overview

This project develops a machine learning model to predict plant diseases using images from a Kaggle dataset. The application processes plant images to classify diseases, aiding in agricultural disease management.

Dataset

The dataset used in this project must be downloaded from Kaggle. You can access it here. After downloading, place the dataset files in the data/ directory as described in the project structure below.

Installation



Clone the repository:

git clone <https://github.com/shehanjay2000/Plant-disease-prediction-application.git>
cd plant-disease-prediction



Install the required dependencies:

pip install -r requirements.txt



Download the Kaggle dataset and extract it into the data/ directory.

Project Structure

plant-disease-prediction/
├── data/
│   ├── train/              # Training dataset images
│   ├── test/               # Test dataset images
│   ├── valid/              # Validation dataset images
├── notebooks/              # Jupyter notebooks 
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── main.py                 # Main script to run the application



Dependencies

Python 3.8+
TensorFlow or 
NumPy, Pandas
See requirements.txt for the full list of dependencies.


Notes

Ensure the Kaggle dataset is properly structured in the data/ directory with train/, test/, and valid/ subdirectories.


