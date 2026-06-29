# CIFAR-10 Image Classification using Deep Learning

## Project Overview

This project implements an image classification system using the CIFAR-10 dataset using a Convolutional Neural Network (CNN) built with TensorFlow/Keras. The model is trained with data augmentation and optimized using callbacks. A Gradio web application is provided for real-world image prediction.

---

## Dataset

- Dataset: CIFAR-10
- Total Images: 60,000
- Training Images: 50,000
- Testing Images: 10,000
- Image Size: 32×32 RGB
- Classes: 10

Classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

---

## Technologies

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Pandas
- Seaborn
- Scikit-learn
- Pillow
- Gradio

---

## Project Features

✔ CNN Model

✔ Data Preprocessing

✔ Data Augmentation

✔ Batch Normalization

✔ Dropout

✔ EarlyStopping

✔ ReduceLROnPlateau

✔ ModelCheckpoint

✔ Accuracy & Loss Graph

✔ Confusion Matrix

✔ Classification Report

✔ Gradio Web Application

---

## Project Structure

```

CIFAR10-Image-Classification/

├── README.md

├── requirements.txt

├── app.py

├── best_model.keras

├── performance_results.csv

├── CIFAR_10_Image_Classifier.ipynb

├── images/

├── examples/

├── screenshots/

└── LICENSE

```

---

## Installation

Clone Repository

```bash
git clone https://github.com/Ferdaus71/CIFAR-10-Image-Classifier.git

cd CIFAR10-Image-Classification
```

Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Training Instructions

1. Open Google Colab

2. Upload

```
CIFAR_10_Image_Classifier.ipynb
```

3. Run all cells.

4. The notebook will

- Load CIFAR-10
- Preprocess data
- Apply augmentation
- Train CNN
- Save best_model.keras
- Evaluate model
- Generate graphs
- Save performance_results.csv

---

## Running the Gradio App

```bash
python app.py
```

or in Google Colab

```python
demo.launch(share=True)
```

---

## Performance Results

| Metric | Value |
|----------|---------|
| Training Accuracy | 98% |
| Validation Accuracy | 90% |
| Test Accuracy | 90% |

---

## Screenshots

Add screenshots here:

- Accuracy Graph
  <img width="855" height="470" alt="image" src="https://github.com/user-attachments/assets/57e22364-d1ad-4ad8-af14-1c75184379bd" />

- Loss Graph
- 
  <img width="855" height="470" alt="image" src="https://github.com/user-attachments/assets/b2284d13-f05e-412b-a5f5-d378dd559ecf" />

- Confusion Matrix
- 
  <img width="854" height="766" alt="image" src="https://github.com/user-attachments/assets/d6b38999-f73a-48c2-8032-db9c9d5ea4d3" />

- Prediction Result
- 
  <img width="515" height="369" alt="image" src="https://github.com/user-attachments/assets/010aad9e-33eb-4ec7-afd5-2be7b6767216" />

- Gradio Interface
- 
  <img width="1895" height="1076" alt="image" src="https://github.com/user-attachments/assets/11733739-4423-45a8-8570-3bea2339322e" />


---

## Author

Ferdaus Hossen
