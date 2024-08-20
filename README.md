# Text Sentiment and Emotion Analysis

This project performs sentiment and emotion analysis on a given text file (`read.txt`). The code processes the text by cleaning, tokenizing, removing stopwords, and lemmatizing. It then analyzes the emotions associated with the words in the text and plots the results. Additionally, the code performs a sentiment analysis to determine whether the text has a positive, negative, or neutral sentiment.

## Features

- Text Cleaning: Converts text to lowercase and removes punctuation.
- Tokenization: Breaks down text into individual words for processing.
- Stopword Removal: Filters out common English stopwords.
- Lemmatization: Converts words to their base forms.
- Emotion Detection: Identifies emotions associated with words using an `emotions.txt` file.
- Sentiment Analysis: Determines the sentiment polarity of the entire text (Positive, Negative, Neutral).
- Visualization: Generates a bar chart (`graph.png`) displaying the frequency of detected emotions.

## Requirements

- Python 3.x
- nltk
- matplotlib

## Usage

1. Place your text data in a file named `read.txt`.
2. Run the Python script to perform sentiment and emotion analysis.
3. The script will output the detected emotions, sentiment analysis result, and save a bar chart of emotions in `graph.png`.

## Files

- `read.txt`: The input text file containing the text to be analyzed.
- `emotions.txt`: A file containing words and their corresponding emotions.

## Output

- A list of detected emotions and their counts.
- The sentiment of the text (Positive, Negative, or Neutral).
- A bar chart saved as `graph.png` showing the frequency of emotions.
