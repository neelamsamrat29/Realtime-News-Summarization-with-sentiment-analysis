**Real-Time News Summarization and Sentiment Analysis**
This project fetches top headlines from the NewsAPI, summarizes the content of the articles, performs sentiment analysis, and stores the results in an SQLite database. The user can interact with the program to fetch new data, display summarized news, or filter news based on sentiment.

**Features**

Fetches top news from NewsAPI.

Summarizes news articles using a pre-trained BART model.

Analyzes the sentiment of the summarized content (Positive/Negative).

Stores the news, summaries, and sentiment in an SQLite database.

Allows users to filter and display news based on sentiment.


**Requirements**


Python 3.x

requests library

transformers library (for NLP models)

sqlite3 library (for database management)


**Usage**

Once the script is running, you'll see a menu with options:

Fetch and process news: Fetches the latest news articles, summarizes the content, performs sentiment analysis, and stores it in the SQLite database.

Display all news: Displays all news articles with their summaries and sentiment.

Display positive news: Filters and displays news articles with a positive sentiment.

Display negative news: Filters and displays news articles with a negative sentiment.

Exit: Exits the program.
