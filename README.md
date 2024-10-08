# Amazon Echo Studio Reviews - Web Scraping and Data Analysis

## Overview

This project focuses on extracting, cleaning, and analyzing Amazon Echo Studio product reviews to uncover customer sentiment and feedback patterns. By using web scraping tools and natural language processing techniques, the project aims to provide actionable insights for product development and marketing strategies.

## Tools and Technologies
- **Python**
- **BeautifulSoup**: Used for web scraping to extract review data.
- **NLTK (Natural Language Toolkit)**: Employed for tokenization, part-of-speech (POS) tagging, and sentiment analysis.
- **TextBlob**: Used for sentiment polarity analysis.
- **Pandas**: For data cleaning, manipulation, and processing.
- **Matplotlib/Seaborn**: To visualize insights from the analysis, such as sentiment distribution and common words.
- **WordCloud**: For visualizing frequently used words in customer reviews.

## Features
- **Web Scraping**: Extracted over 500 customer reviews for Amazon Echo Studio using BeautifulSoup, including the review title, description, rating, and date.
- **Data Cleaning**: Preprocessed the text data by removing punctuation, converting to lowercase, tokenizing, and eliminating stopwords to improve data quality.
- **Sentiment Analysis**: Applied sentiment analysis using TextBlob to classify customer reviews into positive, neutral, and negative sentiment categories.
- **POS Tagging**: Analyzed the structure of the reviews using NLTK’s POS tagging to extract frequently mentioned nouns, adjectives, and verbs.
- **Visualization**: Generated visualizations like word clouds, bar charts, and sentiment distributions to highlight key feedback patterns.
- **Feedback Categorization**: Converted review sentiment into binary feedback (positive/negative) for further analysis and visualization.

## Key Findings
- **Sentiment Breakdown**: A majority of the reviews were classified as positive, reflecting overall customer satisfaction with Amazon Echo Studio.
- **Common Themes**: Nouns such as "sound," "speaker," and "Alexa" were most frequently mentioned in positive feedback, while negative feedback focused on "connectivity" and "issues" with WiFi and pairing.
- **Descriptive Language**: Adjectives like "great," "amazing," and "awesome" were frequently used in positive reviews, while negative reviews commonly used adjectives like "poor" and "disappointing."

