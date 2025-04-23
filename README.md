# Sentimental-Analysis-on-Web-Scraped-Dynamic-Stock-News-Data
Python project that performs sentiment analysis on dynamically scraped stock news headlines using VADER. It fetches data from Finviz for stocks like AAPL, TSLA, and GOOGL, analyzes sentiment, visualizes trends with matplotlib, and exports results for further use.

------

## Sentiment Analysis on Web Scraped Dynamic Stock News Data

This project performs sentiment analysis on real-time stock market news headlines scraped from Finviz for selected tickers like Apple (AAPL), Tesla (TSLA), and Google (GOOGL). The VADER sentiment analyzer from NLTK is used to classify headlines into positive, neutral, or negative sentiment. The results are visualized using matplotlib and saved for further analysis.

------

Features:
- Scrapes live news headlines from the Finviz website
- Applies VADER sentiment analysis to each headline
- Visualizes sentiment trends per stock over time
- Exports results to a CSV file

------

Technologies Used:
- Python
- BeautifulSoup
- Requests
- Pandas
- NLTK (VADER)
- Matplotlib

------

How to Use:
1. Install required libraries: requests, beautifulsoup4, pandas, nltk, matplotlib
2. Run the script or Jupyter Notebook
3. Make sure NLTK’s vader_lexicon is downloaded
4. Edit the stock tickers list as needed
5. Analyze and export the sentiment results

------

Expected Output:
- CSV file with headlines and their sentiment scores
- Stacked bar chart showing sentiment distribution per stock


------

Important Notes:
- Scraping is done responsibly using headers to mimic a real browser
- Tickers can be changed easily in the code
- The script is suitable for customization or integration into larger data pipelines

