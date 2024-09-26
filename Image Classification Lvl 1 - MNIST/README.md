# Simple MNIST Image Classification

## Project Overview

This project uses a **Convolutional Neural Network (CNN)** to classify handwritten digits from the MNIST dataset. The MNIST dataset contains 70,000 28x28 grayscale images of the digits 0-9, which is widely used for training image processing systems. The goal of this project is to build a simple image classifier that can accurately predict the digit displayed in an image.

## Key Features

- **Data Preprocessing**: Loads and normalizes the MNIST dataset to prepare it for training.
- **Model Architecture**: Constructs a CNN model consisting of convolutional layers, pooling layers, and dense layers to classify digits.
- **Training and Evaluation**: Trains the CNN on the MNIST dataset and evaluates its performance on the test set using metrics like accuracy.
- **Prediction**: Uses the trained model to predict digits for new input images.

## Requirements

To run the project, you’ll need the following packages:
- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib

Install the dependencies with:

pip install tensorflow numpy matplotlib

## Running the Project

1. Clone this repository:
   git clone https://github.com/bnikolaos21b/simple-mnist-classification
   cd simple-mnist-classification

2. Load the dataset and the Jupyter notebook (`Simple_MNIST_Image_Classification.ipynb`).

3. Run the notebook to preprocess the data, build the CNN model, and classify the images.

4. Visualize the classification results to evaluate the model's performance.

## Conclusion

This project demonstrates how CNNs can be applied to classify handwritten digits from the MNIST dataset. It serves as a great introduction to image classification and deep learning techniques. With further experimentation, the model's accuracy can be improved by tweaking the architecture or tuning hyperparameters.


