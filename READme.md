# Potato Disease Identification using CNN, Deep Learning

This project identifies potato leaf diseases using a Convolutional Neural Network (CNN) model. It classifies potato leaves into three categories: 
- **Healthy**
- **Early Blight**
- **Late Blight**

The project utilizes a custom-trained CNN model, achieving high accuracy and efficient predictions. 

---

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Dataset](#dataset)
5. [Model Architecture](#model-architecture)
6. [Usage](#usage)
7. [Results](#results)
8. [Gradio Interface](#gradio-interface)
9. [License](#license)

---

## Introduction
Potato diseases significantly impact agricultural productivity. This project leverages Deep Learning techniques to automate and enhance disease detection, helping farmers take timely action.

---

## Features
- Classifies potato leaf images into three classes: **Healthy**, **Early Blight**, and **Late Blight**.
- Provides confidence scores for each class.
- Includes a Gradio interface for easy image upload and predictions.

---

## Technologies Used
- **Programming Language**: Python
- **Deep Learning Framework**: TensorFlow and Keras
- **Model Architecture**: Sequential CNN
- **Interface**: Gradio
- **Dataset**: Kaggle's [PlantVillage Dataset](https://www.kaggle.com/emmarex/plantdisease)

---

## Dataset
The dataset was sourced from Kaggle's PlantVillage repository. It includes annotated images of potato leaves for the classes mentioned. Image preprocessing techniques such as resizing, rescaling, flipping, and rotation were applied.

---

## Model Architecture
The CNN model consists of:
- Convolutional Layers
- MaxPooling Layers
- Flatten Layer
- Dense Layers

The model was trained using:
- **Optimizer**: Adam
- **Loss Function**: Sparse Categorical Crossentropy
- **Metrics**: Accuracy

---

## Usage
### Requirements
Install the required Python libraries:
```bash
pip install tensorflow gradio

Steps

1. Clone this repository:

git clone https://github.com/your-username/Potato-Disease-Identification.git
cd Potato-Disease-Identification


2. Run the Gradio interface:

python app.py


3. Upload an image of a potato leaf and get predictions.




---

Results

Test Accuracy: 97.67%

Confusion Matrix, Precision, Recall, and F1-Score metrics validate the model's performance.


Sample predictions using Gradio:


---

Gradio Interface

A user-friendly Gradio interface is included to upload images and view predictions with confidence scores.




---

License

This project is licensed under the MIT License.


---

Acknowledgments

Kaggle for the PlantVillage Dataset.

TensorFlow/Keras for Deep Learning tools.

Contributions and guidance from Mr. Ismail (Lecturer in GC Skardu(MS in AI))  ismskd@gmail.com





