# Twitter Sentiment Analysis

This project performs sentiment analysis on Twitter data using natural language processing (NLP) techniques. It cleans and preprocesses tweet text, visualizes word frequencies and hashtags, and trains a logistic regression model to classify tweets as positive or negative.

## Dataset

The dataset used is `Twitter Sentiments.csv`, which contains tweets labeled with sentiment (0 for positive, 1 for negative).

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - nltk
  - wordcloud

## Installation

1. Clone or download the repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud
   ```

3. Download NLTK data (if not already done):

   ```python
   import nltk
   nltk.download('punkt')
   ```

## Usage

1. Open the Jupyter Notebook `twitter_sentiment_analysis .ipynb`.
2. Run the cells in order to:
   - Load and explore the dataset
   - Clean and preprocess the tweet text (remove handles, special characters, short words, stemming)
   - Visualize word clouds for overall, positive, and negative sentiments
   - Analyze hashtags
   - Extract features using Bag of Words
   - Train and evaluate a logistic regression model
   - Adjust prediction threshold for better F1 score

## Features

- Text preprocessing: Removing Twitter handles, special characters, short words, and stemming
- Data visualization: Word clouds and hashtag frequency plots
- Sentiment classification: Logistic regression with Bag of Words features
- Model evaluation: Accuracy and F1 score metrics

## Results

The model achieves an F1 score of approximately [insert value from notebook] on the test set. Adjust the probability threshold to optimize for precision/recall trade-off.

## License

[Add license if applicable]