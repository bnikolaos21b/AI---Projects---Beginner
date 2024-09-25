# MNIST Handwritten Digit Generation using GANs

## Project Overview

This project implements a **Generative Adversarial Network (GAN)** to generate realistic handwritten digits from the MNIST dataset. It showcases the potential of generative models in deep learning and marks a key step in my AI journey. By using adversarial training, this project highlights how a model can learn to create entirely new data based on patterns learned from real images.

## Key Features

- **Data Preprocessing**: Efficiently loads and scales the MNIST dataset to a format suitable for GAN training.
- **Generator and Discriminator**: Constructs two neural networks—one to generate images and the other to classify them as real or fake.
- **Adversarial Training**: Trains both models together, allowing the generator to improve at fooling the discriminator over time.
- **Visualization**: Produces and saves generated digit images after each epoch to track the progress of the GAN.

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
   git clone https://github.com/bnikolaos21b/mnist-gan
   cd mnist-gan

2. Run the training script or Jupyter notebook. The model will train for a set number of epochs, saving generated images along the way.

3. Generated images will be saved and can be visualized to assess how well the GAN has learned to create digits.

## Conclusion

This project is a simple yet powerful demonstration of how GANs can be applied to image generation tasks. While trained on a basic dataset like MNIST, the same principles can be extended to more complex data generation challenges.

## License

This project is licensed under the MIT License—feel free to explore, modify, and expand upon it.

