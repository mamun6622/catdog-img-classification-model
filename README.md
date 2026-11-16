# 🐱🐶 Cat and Dog Image Classification

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-green?logo=opencv)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 About The Project

This project is a Cat and Dog Image Classification system developed using Python and Machine Learning techniques.

The main objective of this project is to classify images into two categories:

- 🐱 Cat
- 🐶 Dog

The system uses image processing techniques to preprocess images and prepare them for classification.

## 🚀 Features

- Cat and Dog image classification
- Image preprocessing using OpenCV
- Image resizing (128 × 128 pixels)
- Image normalization
- Dataset splitting into training, validation, and testing sets
- Machine Learning and Deep Learning support

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

## 📂 Project Structure

```text
catdog-img-classification-model/
│
├── aug/
│   ├── 0/                  # Cat images
│   └── 1/                  # Dog images
│
├── train.py                # Training script
├── requirements.txt        # Dependencies
├── README.md               # Project documentation
└── .gitignore
```

## 📊 Dataset Information

The dataset contains two classes:

| Class | Label |
|:---|:---:|
| Cat 🐱 | 0 |
| Dog 🐶 | 1 |

### Image Preprocessing

1. Load images using OpenCV.
2. Resize images to 128 × 128 pixels.
3. Convert images into NumPy arrays.
4. Normalize pixel values between 0 and 1.
5. Split the dataset into training, validation, and testing sets.

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/mamun6622/catdog-img-classification-model.git
```

### 2. Navigate to the Project Directory

```bash
cd catdog-img-classification-model
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

## ▶️ Run the Project

Execute the Python script:

```bash
python train.py
```

## 📈 Model Evaluation

The model can be evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
