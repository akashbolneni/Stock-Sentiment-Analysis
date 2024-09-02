# Stock-Sentiment-Analysis

This app combines news sentiment analysis and stock trading to make news more actionable for algorithmic trading. It analyzes news sentiment and performs stock price performance analysis using NLP with Python.

### Implementation
1. Get stock news via the Mboum Finance API.
2. Utilize Python's NLP and Pandas packages to examine the news's sentiment.
3. With Plotly, create a bar graph of the sentiment ratings.
4. To restrict stock price data to the relevant time frame, take the earliest date out of the news.
5. Access past stock prices by utilizing the Mboum Finance API.
6. Using Plotly, plot the stock prices on a line graph.
7. Create hyperlinks out of the text in the Headline column.
8. Show the combined data in the analysis.html template.

### Libraries/Tech Used
* Flask
* Pandas
* Matplotlib
* NLTK
* BeautifulSoup
* Plotly
* NumPy
