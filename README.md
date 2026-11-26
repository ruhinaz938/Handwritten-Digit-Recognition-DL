# ✍️ Handwritten Digit Recognition (Deep Learning)

A Deep Learning image classification project built using **TensorFlow & Keras** that recognizes handwritten digits (0–9) from the MNIST dataset with **~97.5% accuracy**.

## 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning Framework:** TensorFlow / Keras
* **Numerical & Visualization:** NumPy, Matplotlib

## 🧠 Neural Network Architecture
* **Input Layer:** `Flatten` (converts 28x28 grayscale images into a 784-dimensional vector)
* **Hidden Layer:** `Dense(128)` with **ReLU** activation + `Dropout(0.2)` regularization
* **Output Layer:** `Dense(10)` with **Softmax** activation for multi-class probability distribution
* **Optimizer & Loss:** `Adam` optimizer with `Sparse Categorical Crossentropy`

## 🚀 How to Run
Open `Handwritten_Digit_Recognition.ipynb` in Google Colab using the badge inside the notebook to train and visualize predictions.
