#  Plant Disease Prediction

This project is a **Plant Disease Prediction Application** that uses a deep learning model to classify plant leaf images into different disease categories.  
It is trained on a dataset from **Kaggle**, which contains labeled images of healthy and diseased plant leaves.

##  Dataset

The dataset used in this project must be **downloaded manually** from Kaggle:  
🔗 [PlantVillage Dataset on Kaggle](https://www.kaggle.com/emmarex/plantdisease)

Once downloaded, extract the dataset and arrange it in the following directory structure inside your project:
Plant_disease_project/
│
│ ├── train/
│ ├── test/
│ └── valid/
│
├── model_training.ipynb
├── requirement.txt
├── app.py
└── README.md


- **train/** → Contains training images.
- **test/** → Contains testing images.
- **valid/** → Contains validation images.

## ⚙️ Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/plant-disease-prediction.git
   cd plant-disease-prediction
Install dependencies
Make sure you have Python 3.8+ installed, then run:

pip install -r requirement.txt

Usage

Train the Model
Open and run model_training.ipynb in Jupyter Notebook to train the model.

Run the Application

streamlit run app.py


Upload Leaf Images
Upload an image of a leaf in the application interface to get disease predictions.

🛠 Requirements

The main libraries required for this project are:

TensorFlow 2.10.0

scikit-learn 1.3.0

NumPy 1.24.3

Matplotlib 3.7.2

Seaborn 0.13.0

Pandas 2.1.0

Streamlit

Librosa 0.10.1

You can find the complete list in requirement.txt.

Model

Model Type: CNN (Convolutional Neural Network)

Dataset Split:

Training: 70%

Validation: 15%

Testing: 15%
