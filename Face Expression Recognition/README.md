# Facial Expression Recognition

## Project Overview

This project uses **Convolutional Neural Networks (CNNs)** to classify facial expressions from images. The model is trained to recognize a variety of emotions based on facial expressions, which can have real-world applications in areas like human-computer interaction, emotion analysis, and behavioral studies.

## Key Features

- **Data Preprocessing**: Loads and preprocesses the facial expression dataset, including resizing images and normalizing pixel values.
- **Model Architecture**: Builds a CNN to classify images into various facial expression categories (e.g., happy, sad, angry).
- **Training and Evaluation**: Trains the CNN model on the facial expression dataset and evaluates its accuracy on a validation set.
- **Prediction**: Uses the trained model to predict the facial expressions in new images.

## Requirements

To run the project, you’ll need the following packages:
- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Pandas
- OpenCV (optional, for image processing)

Install the dependencies with:

pip install tensorflow keras numpy matplotlib pandas opencv-python

## Running the Project

1. Clone this repository:
   git clone https://github.com/bnikolaos21b/facial-expression-recognition
   cd facial-expression-recognition

2. Load the dataset and the Jupyter notebook (`Facial_Expression_Recognition.ipynb`).

3. Download the dataset from here : https://www.kaggle.com/datasets/ashishpatel26/facial-expression-recognitionferchallenge

4. Run the notebook to preprocess the data, build the model, and classify facial expressions.

5. Visualize the model's predictions on both the training and test sets to evaluate performance.

## Conclusion

This project demonstrates how CNNs can be applied to the task of recognizing facial expressions from images. The model can be expanded and fine-tuned with more data and deeper architectures to improve accuracy. This is a practical example of how deep learning can be used in emotion detection and analysis.

## License

This project is licensed under the MIT License—feel free to use, modify, and expand upon it.
