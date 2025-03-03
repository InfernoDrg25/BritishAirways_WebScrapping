# BritishAirways_WebScrapping

## Project Overview
This repository contains a data analysis project focused on British Airways customer reviews. The analysis uses web-scraped review data to extract insights about customer sentiment, common topics of discussion, and areas of concern.

## Objectives
* Extract and analyze customer sentiment from British Airways reviews
* Identify common phrases and topics in customer feedback
* Categorize and quantify major complaint areas
* Present actionable insights for service improvement

## Methods
1. Text Preprocessing: Cleaning review text by removing HTML tags, special characters, and applying NLP techniques
2. Sentiment Analysis: Classifying reviews as positive, negative, or neutral using TextBlob
3. Visualization: Creating word clouds, n-gram charts, and complaint distribution graphs
4. Topic Analysis: Identifying common phrases and complaint categories

## Technologies Used
* Python 3.10.8
* Libraries:
*   Pandas for data manipulationNLTK for natural language processing
*   TextBlob for sentiment analysis
*   Matplotlib/Seaborn for data visualization
*   WordCloud for text visualization

## Key Findings
* Distribution of customer sentiment across British Airways reviews
* Most frequently mentioned words in positive vs. negative reviews
* Common bigrams and trigrams revealing specific discussion topics
* Breakdown of major complaint categories
* Proportion of negative reviews mentioning each complaint type

# Repository Structure
* Code.ipynb: Jupyter notebook containing all analysis code
* BA_reviews.xlsx: Raw scraped review data
* cleaned_BA_reviews.xlsx: Preprocessed review data with sentiment scores

# Acknowledgement
Forage for providing the project framework

