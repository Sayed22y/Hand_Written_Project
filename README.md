## Handwritten Digit Recognition with CNN

This project implements a Convolutional Neural Network (CNN) using Keras to classify handwritten digits from the MNIST dataset.

## Dataset

MNIST: A dataset of 60,000 training images and 10,000 test images of handwritten digits (0-9), each of size 28x28 pixels.

## Model Architecture

Conv2D: 2 convolutional layers with ReLU activation

MaxPooling2D: 1 max-pooling layer

Dropout: Applied to prevent overfitting

Flatten: Converts the 2D feature maps into a 1D vector

Dense: Fully connected layers with ReLU and softmax activation

## Installation

To run this project, install the required dependencies:

```bash
pip install keras
```

## Running the Project

Load the dataset and preprocess it.

Build and train the CNN model.

Evaluate the model on test data.

Save the trained model.

Run the following command to execute the script:
```bash
python your_script.py
```
## Training Results

Epochs: 10

Batch size: 10

Final Test Accuracy: ~98.9%

## Model Saving

The trained model is saved in HDF5 format:
```bash
model.save('HandWritten.h5')
```
## Evaluation

Run the following to evaluate the model:
```bash
python -c "import keras.models as km; model = km.load_model('HandWritten.h5'); print(model.evaluate(x_test, y_test))"
```
## Dependencies

Python 3.12

Keras

NumPy

