# Handwritten Character Recognition using CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN) to recognize handwritten digits (0–9) from the MNIST dataset.

The model is trained using TensorFlow and Keras and can predict handwritten digits from grayscale images.

## Dataset
- Dataset: MNIST
- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Classes: 10 (Digits 0–9)
- Image Type: Grayscale

## Technologies Used
- Python
- TensorFlow & Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## CNN Architecture
1. Convolutional Layer (32 filters)
2. Max Pooling Layer
3. Convolutional Layer (64 filters)
4. Max Pooling Layer
5. Flatten Layer
6. Dense Layer (128 neurons)
7. Dropout Layer (0.5)
8. Output Layer (10 neurons, Softmax)

## Model Performance

| Metric | Result |
|---|---:|
| Training Accuracy | 99.25% |
| Validation Accuracy | 99.30% |
| Test Accuracy | 99.25% |
| Test Loss | 0.0230 |
| Macro Precision | 99.24% |
| Macro Recall | 99.25% |
| Macro F1-score | 99.24% |

## Project Files
- `Handwritten_Character_Recognition.ipynb` – Complete project notebook
- `handwritten_digit_cnn.keras` – Trained CNN model
- `requirements.txt` – Required Python libraries

## How to Run
1. Clone or download this repository.
2. Install the required libraries.
3. Open the Jupyter Notebook.
4. Run the notebook cells step by step.

## Installation

```bash
pip install -r requirements.txt
```

## Acknowledgement
This project was completed as part of the CodeAlpha Machine Learning Internship.

## Author
Sadiya Hossain