# Final Project: Article Summarizer
This project involves extracting and analyzing the sentiment of an article through natural language processing (NLP) techniques. The process includes:

Web Scraping: The HTML content of an article is scraped and stored.

Sentiment Analysis: Sentiment scores for each sentence are calculated using TextBlob, based on both tokens and lemmas.

Summary Generation: Sentences with sentiment scores above a specified threshold are selected to generate a summary of the article.

Results: The project includes the calculation of polarity scores for both token-based and lemma-based summaries, along with the number of sentences in the generated summary.

This work demonstrates how to apply basic NLP techniques to analyze text and generate summaries based on sentiment analysis.

## Create virtual environment
'''bash
python3 -m venv .venv
source .venv/bin/activate
'''

## Git add and commit 
'''bash
git add .
git commit -m "comment"
git push -u origin master
'''

## Install Dependencies
'''bash
python3 -m pip install beautifulsoup4 html5lib ipykernel jupyterlab matplotlib requests spacy spacytextblob numpy pickle nltk
python3 -m pip freeze > requirements.txt
'''

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Polarity score printed with an appropriate label: 1 pt
* (Question 2) Number of sentences printed: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Histogram shown with appropriate labelling: 1 pt
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Cutoff score seems appropriate given histograms: 2 pts (1/score)
* (Question 8) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 8) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 9) Polarity score printed with an appropriate label: 1 pt
* (Question 9) Number of sentences printed: 1 pt
* (Question 10) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 10) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 11) Polarity score printed with an appropriate label: 1 pt
* (Question 11) Number of sentences printed: 1 pt
* (Question 12) Thoughtful answer based on reported polarity scores: 1 pt
* (Question 13) Thoughtful answer based on summaries: 1 pt
