WhatsApp Sentiment Analysis Project
Overview

This project involves analyzing sentiment from WhatsApp chat data using Python. We aim to clean the data, perform sentiment analysis, and categorize the overall sentiment of the chat.
Project Structure

The project is structured as follows:

    Data Cleaning: We cleaned the WhatsApp chat data to prepare it for sentiment analysis. This included removing unnecessary characters, handling missing values, and normalizing text.
    Sentiment Analysis: Using the cleaned data, we applied sentiment analysis techniques to assign sentiment scores to each message.
    Overall Sentiment Categorization: Based on sentiment scores, we categorized the overall sentiment of the chat into categories like 'happy', 'angry', 'bad', and 'neutral'.

Tools and Libraries Used

    Python
    Pandas for data manipulation
    TextBlob for sentiment analysis
    Microsoft Edge for web scraping 

Files Included

    Cleaned_whatsapp.csv: The cleaned WhatsApp chat data file.
    sentiment_analysis.py: Python script for sentiment analysis and categorization.
    README.md: This file, providing an overview of the project.

Steps to Replicate

    Data Cleaning:
        Ensure WhatsApp chat data (Cleaned_whatsapp.csv) is formatted correctly.
        Use pandas to clean the data by removing unnecessary characters and normalizing text.

    Sentiment Analysis:
        Use TextBlob or another sentiment analysis tool to calculate sentiment scores for each message.
        Implement a function to categorize sentiment scores into predefined categories ('happy', 'angry', 'bad', 'neutral').

    Save Results:
        Save the cleaned data (Cleaned_whatsapp.csv) after processing.
        Save the results of sentiment analysis to a new CSV file (Reviewdf_with_sentiment.csv).

Usage

    Clone the repository and ensure all dependencies (Python, pandas, TextBlob) are installed.
    Run sentiment_analysis.py to replicate the sentiment analysis process.
    Review the saved CSV files (Cleaned_whatsapp.csv and Reviewdf_with_sentiment.csv) for cleaned data and sentiment analysis results.

Contributors

    [Muzammil Haider]

License

This project is licensed under the MIT License.
