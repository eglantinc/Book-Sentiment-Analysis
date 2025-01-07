# Book-Sentiment-Analysis

This project analyzes Amazon book reviews using exploratory data analysis (EDA) and sentiment analysis to uncover 
patterns in customer ratings and sentiments.

## Dataset
The project uses the [Amazon Books Reviews Dataset](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews/data) from Kaggle. 
The dataset contains customer reviews and ratings for books sold on Amazon. However, the CSV file was reduced to **1,000 entries** for simplicity and faster processing.

This project is inspired by [this Kaggle notebook](https://www.kaggle.com/code/robikscube/sentiment-analysis-python-youtube-tutorial), 
which links to the [Rob Mulla YouTube channel](https://www.youtube.com/channel/UCxladMszXan-jfgzyeIMyvw).


## Key Features
- **Exploratory Data Analysis**:
  - Count plot summarizing the distribution of ratings (1 to 5 stars).
  - Box plot illustrating the spread of review scores.
- **Sentiment Analysis**:
  - Sentiment analysis of sampled reviews using their first sentence.
  - Visualization of positive, neutral, and negative sentiment distributions.
  - Analysis of compound sentiment scores across different star ratings.

## Visualizations
The project produces several visualizations, including:
1. **Count Plot of Ratings**: Shows the number of reviews per rating (1–5 stars).
2. **Box Plot of Review Scores**: Displays the spread and outliers in ratings.
3. **Sentiment Distribution by Ratings**: Visualizes positive, neutral, and negative sentiment scores.
4. **Compound Sentiment Scores by Ratings**: Highlights overall sentiment polarity.

## Prerequisites
- Python 3.8+
- Libraries: `pandas`, `numpy`, `nltk`, `matplotlib`, `seaborn`, `vaderSentiment`

## Notes
- For sentiment analysis, the first sentence of a randomly selected review was used.
- This project demonstrates basic sentiment analysis techniques and visualization.
- This is also a basic beginner project and **will improve as I learn in a more pronounced way**.
---
