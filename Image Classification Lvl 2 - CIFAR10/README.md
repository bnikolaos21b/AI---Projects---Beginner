# CIFAR-10 Image Captioning

## Project Overview

This project applies a **Convolutional Neural Network (CNN)** with attention mechanisms to generate captions for images from the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images across 10 classes. Image captioning is a complex task that combines computer vision and natural language processing to describe the content of images. 

## Key Features

- **Data Preprocessing**: Loads and preprocesses CIFAR-10 images to make them compatible with the CNN model.
- **Model Architecture**: Builds a CNN for image feature extraction.
- **Training and Evaluation**: Trains the model on the CIFAR-10 dataset and evaluates its ability to generate accurate captions.
- **Image Captioning**: Uses the trained model to generate captions for new images and compares them to the ground truth.

## Requirements

To run the project, you’ll need the following packages:
- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Pandas

Install the dependencies with:

pip install tensorflow keras numpy matplotlib pandas

## Running the Project

1. Clone this repository:
   git clone https://github.com/bnikolaos21b/cifar10-image-captioning
   cd cifar10-image-captioning

2. Load the dataset and the Jupyter notebook (`CIFAR10_Image_Captioning.ipynb`).

3. Run the notebook to preprocess the data, build the model, and generate image captions.

4. Visualize the generated captions and compare them to the actual labels of the CIFAR-10 dataset.

## Conclusion

This project showcases the integration of CNNs and RNNs for solving the image captioning task using the CIFAR-10 dataset. While CIFAR-10 images are relatively small, this project demonstrates the potential of combining visual features and language models to describe visual content. With more advanced techniques and larger datasets, the model's performance can be enhanced further.

