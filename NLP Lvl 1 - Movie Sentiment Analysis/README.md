# Movie Sentiment Analysis

## Project Overview

This project applies **Natural Language Processing (NLP)** techniques to analyze the sentiment of movie reviews. The goal is to classify whether a given movie review expresses a positive or negative sentiment. Using a dataset of labeled movie reviews, a machine learning model is trained to understand and predict the sentiment based on the review text.

## Key Features

- **Data Preprocessing**: Cleans and tokenizes the text data, including removing stopwords and punctuation.
- **Model Architecture**: Builds a deep learning model using techniques like word embeddings and recurrent neural networks (RNNs) to classify sentiments.
- **Training and Evaluation**: Trains the model on the movie review dataset and evaluates its performance using metrics such as accuracy and F1-score.
- **Prediction**: Uses the trained model to predict the sentiment of new, unseen movie reviews.

## Requirements

To run the project, you’ll need the following packages:
- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Pandas
- Scikit-learn

Install the dependencies with:

pip install tensorflow keras numpy pandas scikit-learn

## Running the Project

1. Clone this repository:
   git clone https://github.com/bnikolaos21b/movie-sentiment-analysis
   cd movie-sentiment-analysis

2. Load the dataset and the Jupyter notebook (`Movie_Sentiment_Analysis.ipynb`).

3. Run the notebook to preprocess the data, build the sentiment analysis model, and classify the movie reviews.

4. Evaluate the model's performance on the test set, and visualize the predictions.

## Conclusion

This project showcases how NLP techniques and deep learning models can be applied to sentiment analysis tasks. While trained on movie reviews, the same approach can be extended to other types of textual data to analyze sentiment. Future improvements could include using more advanced architectures or fine-tuning pre-trained language models like BERT for better results.


