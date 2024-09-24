# Movie Sentiment Analysis Project

## Project Overview

This project explores **sentiment analysis** using IMDb movie reviews to classify them as either **positive** or **negative**. It compares the performance of three different models: **Naive Bayes**, **Logistic Regression**, and **LSTM** (Long Short-Term Memory neural networks).

### Models Used:
1. **Naive Bayes**: A probabilistic model often used for text classification tasks.
2. **Logistic Regression**: A linear model that works well for binary classification problems.
3. **LSTM**: A recurrent neural network capable of handling sequential data and capturing long-term dependencies in text.

## Project Structure

- **Movie_Sentiment_Analysis.ipynb**: Jupyter notebook with the complete workflow, including data loading, preprocessing, model training, evaluation, and real-time sentiment prediction.
- **README.md**: This file, explaining the project in detail.
- **Files/**: (Optional) Contains any relevant data or additional resources.

## Data

We use the IMDb movie reviews dataset to train and evaluate our models. The dataset contains 50,000 reviews, split into **25,000 for training** and **25,000 for testing**.

## Workflow

1. **Data Preprocessing**:
   - Text cleaning, tokenization, and removal of stopwords.
   - For the Naive Bayes and Logistic Regression models, we used **TF-IDF** vectorization to convert text data into numerical features.
   - For the LSTM model, we used **word embeddings** and padded the sequences to ensure uniform input size.

2. **Model Training**:
   - **Naive Bayes**: This model quickly converges and provides a baseline accuracy.
   - **Logistic Regression**: This model performs better than Naive Bayes and captures the relationships between features more effectively.
   - **LSTM**: LSTM captures sequential dependencies in text, but requires more computational power and training time.

3. **Evaluation**:
   - **Naive Bayes Accuracy**: 0.84
   - **Logistic Regression Accuracy**: 0.89
   - **LSTM Model Accuracy**: 0.85

4. **Real-Time Testing**:
   - The notebook includes a section where you can input your own review to test the model's prediction in real-time.

## Results

- **Logistic Regression** outperformed the other models, with an accuracy of **89%**, making it the best model for this task.
- **Naive Bayes** performed well for a simpler model, achieving an accuracy of **84%**.
- **LSTM** did well but requires more tuning and computational resources.

## Running the Project:
1. Clone the repository.
2. Install the required dependencies.
3. Open the Jupyter notebook and run the cells to see how the model is built and trained.
