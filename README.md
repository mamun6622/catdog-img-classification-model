Cat and Dog Image Classification
Project Overview

This project is an image classification system that uses Machine Learning and Computer Vision to distinguish between images of cats and dogs.

The project uses Python, OpenCV, NumPy, and Deep Learning techniques to process images and classify them into two categories:

Class 0: Cats 
Class 1: Dogs 

The main goal is to build an image classification model that can automatically identify whether an input image contains a cat or a dog.

Features
Cat and dog image classification
Image preprocessing using OpenCV
Image resizing to 128 × 128 pixels
Pixel normalization
Training, validation, and testing dataset splitting
Model evaluation and performance analysis
Technologies Used

Python
OpenCV (cv2)
NumPy
Scikit-learn
TensorFlow / Keras
Matplotlib Project Structure
text
catdog-img-classification-model/
│
├── aug/
│   ├── 0/              # Cat images
│   └── 1/              # Dog images
│
├── train.py            # Model training code
├── requirements.txt    # Required libraries
├── README.md           # Project documentation
└── .gitignore

📊 Dataset

The dataset contains two categories of images:

Category	Label
Cat	0
Dog	1

Images are preprocessed before being passed to the classification model.

Image Preprocessing
Load images using OpenCV.
Resize each image to 128 × 128 pixels.
Convert images into NumPy arrays.
Normalize pixel values between 0 and 1.
Split the dataset into training, validation, and testing sets.
⚙️ Installation

Step 1: Clone the repository

bash
git clone https://github.com/mamun6622/catdog-img-classification-model.git


Step 2: Navigate to the project directory

bash
cd catdog-img-classification-model


Step 3: Install dependencies

bash
pip install -r requirements.txt

▶️ How to Run

Run the Python training script:

bash
python train.py


The program will load the images, preprocess the dataset, and prepare the data for model training.

📈 Model Performance

Model performance can be evaluated using:

Accuracy
Precision
Recall
F1-score
Confusion Matrix

