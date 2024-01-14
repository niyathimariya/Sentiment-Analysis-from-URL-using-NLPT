# Sentiment-Analysis-from-URL-using-NLPT
Created a Python script employing NLTK and TextBlob for sentiment analysis, summarizing online articles. Integrated web scraping with Newspaper library for URL-based data extraction, applying natural language processing to evaluate sentiment polarity and discern emotional tones in text.

## Requirements
- Python 3.x
- Required Python packages can be installed using the following:
  ```bash
  pip install nltk textblob newspaper3k

How to Use<br>
Clone the repository or download the Python script.<br>
Install the required dependencies by running the command mentioned in the "Requirements" section.<br>
Run the script in a Python environment.<br><br>

Code Explanation<br>
1.Importing Libraries:<br>
Necessary libraries for natural language processing and article extraction are imported.<br>

2.Setting the URL:<br>
Specify the URL of the Wikipedia page on Social Anxiety Disorder.<br>

3.Downloading and Parsing the Article:<br>
Create an Article object, download the content from the specified URL, and parse the article.<br>

4.NLP Processing:<br>
Apply Natural Language Processing (NLP) techniques to the article.<br>

5.Extracting the Summary:<br>
Extract the summary of the article using the summary attribute of the Article object.<br>

6.Sentiment Analysis:<br>
Use TextBlob to perform sentiment analysis on the extracted summary. Calculate the sentiment polarity and print the result.<br><br>

Notes<br>
Ensure an internet connection as the script fetches data from the specified Wikipedia URL.<br>
The accuracy of sentiment analysis may vary based on the complexity and structure of the text.<br>
