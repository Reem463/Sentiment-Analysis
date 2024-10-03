# Sentiment Analysis of IMDB Movie Reviews

## Project Overview
This project focuses on sentiment analysis of movie reviews from the IMDB dataset. The model classifies movie reviews as either positive or negative, providing insights into audience feedback for movies. The task was implemented using an LSTM-based deep learning architecture to analyze the text data and predict sentiment.

## Dataset
The dataset used for this project contains 50,000 movie reviews from the IMDB website, available on Kaggle:(https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
![image](https://github.com/user-attachments/assets/35785a1d-877f-46d2-a2fc-6029558e9495)

## Data Preprocessing
To prepare the dataset, the following preprocessing steps were applied:

* Converted all text to lowercase.
* Removed HTML tags from reviews.
* Filtered out non-alphabetic text.
* Removed common stop words to focus on key terms.
* Applied lemmatization to reduce words to their root forms.
* Tokenized the reviews and applied padding sequences to ensure uniform input length
  
