# Natural Language Processing with Disaster Tweets

This repository contains my work for the [Kaggle Twitter Disaster Competition](https://www.kaggle.com/competitions/nlp-getting-started/overview), where the goal is to predict whether a given tweet is about a real disaster or not using natural language processing techniques.

![Competition Header](https://www.kaggle.com/competitions/17777/images/header)

## Project Overview

In this project, I implemented a basic preprocessing pipeline followed by fine-tuning a BERT model. The preprocessing steps include:

- **Removing URLs**: Stripping out any links in the tweets.
- **Removing Hashtags**: Eliminating hashtags, as they are not typically useful for sentiment analysis.
- **Cleaning Text**: Removing basic useless characters like punctuation, special symbols, etc.

### Model Selection and Training

Initially, I experimented with the base BERT model, but later transitioned to the larger BERT model for improved performance. The choice of BERT is motivated by its strong performance in NLP tasks, particularly in text classification problems.

### Results

The model achieved its best accuracy on the test set on 04/09/2024:

| Date       | Accuracy  |
|------------|-----------|
| 04/09/2024 | **82.960%** |

### Installation

Clone this repository:

```bash
git clone https://github.com/Geronimo-Basso/sentiment-analysis-nlp.git
```