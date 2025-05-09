# 🐱🐶 Cat vs Dog Image Classifier using CNN

This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify images as either cats or dogs. It was completed as part of the freeCodeCamp Machine Learning with Python certification.

> 🏆 Final test accuracy: **72%**

---

## 📂 Dataset

The dataset is sourced from [freeCodeCamp's Cats and Dogs dataset](https://cdn.freecodecamp.org/project-data/cats-and-dogs/cats_and_dogs.zip), containing:

- Training images: 2,000 (cats and dogs)
- Validation images: 1,000
- Test images: 50 (unlabeled)

---

## 🧪 Model Architecture

The CNN model consists of:

- Multiple `Conv2D` + `MaxPooling2D` layers
- `Dropout` to reduce overfitting
- `Flatten` + `Dense` layers for classification
- Sigmoid output for binary classification

Loss function: `binary_crossentropy`  
Optimizer: `adam`  
Metric: `accuracy`

---

## 📈 Results

The model achieved:

- ✅ **72% accuracy** on test data
- Plotted training vs validation accuracy/loss

Sample predictions:

![sample-plot](images/sample_predictions.png) <!-- Optional: replace with your own image -->

---

## 🚀 How to Run

1. Clone the repo:

2. Open the notebook:

In Google Colab or Jupyter Notebook

3. Run all cells to:

Download and preprocess data

Build and train the model

Evaluate and visualize predictions

📜 License
MIT License

🙌 Acknowledgments
freeCodeCamp

TensorFlow & Keras
