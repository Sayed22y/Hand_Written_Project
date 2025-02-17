### MNIST Classification with CNN

# Overview

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset. The model achieves high accuracy on the test set and is trained using TensorFlow/Keras.

## Requirements

To run this project, install the following dependencies:

pip install tensorflow numpy matplotlib

## Usage

Clone this repository:

git clone <repository_url>
cd <repository_folder>

Run the training script:

python train.py

Evaluate the model:

python evaluate.py

Model Architecture
Q
Input Layer: 28x28 grayscale images

Convolutional Layers

Max-Pooling Layers

Fully Connected Layers

Output Layer with Softmax Activation

Training and Evaluation

Dataset: MNIST (60,000 training, 10,000 testing images)

Optimizer: Adam

Loss Function: Categorical Crossentropy

Accuracy: ~99%

Results

The trained CNN achieves high accuracy on the test dataset, effectively recognizing handwritten digits.

License

This project is open-source under the MIT License.

