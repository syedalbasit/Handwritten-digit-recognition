# Handwritten Digit Recognition System 🔢

A machine learning project that recognizes handwritten digits from **0–9** using a neural network trained on the **MNIST dataset**.

The system preprocesses handwritten digit images, passes them through the trained model, and predicts the digit with its output probabilities.

## Features

* MNIST dataset for training and testing
* Neural network with feedforward and backpropagation
* Sigmoid/Tanh activation and Softmax output
* Custom handwritten image testing
* Flask-based web interface for digit prediction

## Technologies

* Python
* NumPy
* TensorFlow / Keras
* OpenCV
* Flask
* Matplotlib

## How It Works

```text
Handwritten Image
       ↓
Image Preprocessing
       ↓
Neural Network
       ↓
Softmax Prediction
       ↓
Predicted Digit (0–9)
```

## Dataset

The project uses the **MNIST handwritten digit dataset**, containing images of digits from 0 to 9.

## Usage

Train the model:

```bash
python train.py
```

Run the Flask application:

```bash
python app.py
```

Then upload a handwritten digit image through the web interface to get the predicted digit.

## Project

**Course:** Artificial Intelligence
**Department:** Computer & Information Systems Engineering
**NED University of Engineering & Technology**
