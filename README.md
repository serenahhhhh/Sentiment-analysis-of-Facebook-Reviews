# Sentiment Analysis for Facebook Reviews

## Overview
This project focuses on performing sentiment analysis on Facebook reviews. The objective is to understand how users feel about the products and services offered by Facebook by categorizing their sentiments into Positive, Neutral, and Negative.

## Features

- **Preprocessing and Stemming**: Cleaned the dataset by applying stemming and various preprocessing steps to make the text data more uniform and manageable.
  
- **Defining a Cleaning Function**: Created a function to remove punctuations, URLs, special characters, whitespace, and other unnecessary elements from the text data.

- **Applying the Cleaning Function**: The cleaning function was applied to the entire dataset, ensuring that all text entries were free from stopwords and other irrelevant components.

- **Visualizing Ratings**: Generated a pie chart to visualize the distribution of ratings from Facebook reviews.

- **Exploring Reviews**: Analyzed the text of the reviews to understand the general sentiment expressed by users.

- **Sentiment Analysis**: Added three new columns to the dataset—Positive, Neutral, and Negative—representing the sentiment categories of the reviews.

- **Determining Sentiment Majority**: Developed a function to calculate the majority sentiment (Positive, Neutral, Negative) by summing the respective scores. The function used three variables: `x`, `y`, `z` to represent Positive, Negative, and Neutral scores.

- **Majority Sentiment**: Based on the analysis, the majority of the reviews were found to be Neutral. This was determined by summing the respective sentiment scores and comparing them.

- **Conclusion**: The analysis concluded that most Facebook users tend to leave neutral reviews about the products and services.

## Getting Started

### Prerequisites
- Python 3.x
- Libraries: Pandas, NumPy, Matplotlib, NLTK, and other required dependencies.

### Installation
Clone the repository and install the required libraries using `pip`.

```bash
git clone <repository-url>
cd sentiment-analysis-facebook-reviews
pip install -r requirements.txt
