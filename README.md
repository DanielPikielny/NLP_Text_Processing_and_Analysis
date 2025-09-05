# NLP_Text_Processing_and_Analysis

This repository contains a Jupyter notebook that provides a comprehensive overview of Natural Language Processing (NLP) techniques, focusing on text processing and analysis. The notebook demonstrates how to handle different languages and data sources, including an English SMS spam dataset, scraped web content, and a Hebrew WhatsApp chat. It showcases key NLP concepts like tokenization, lemmatization, and stemming using both NLTK and SpaCy.

How to Run the Notebook

This notebook was developed in a Google Colab environment.

Prerequisites

    A Google Colab environment.

    An active internet connection to download the dataset and web content.

    A local WhatsApp chat file named WhatsApp Chat.txt to be uploaded manually.

Dependencies

The following Python libraries are required to run the notebook:

    pandas and numpy: For data manipulation and numerical operations.

    nltk: The Natural Language Toolkit for various NLP tasks.

    spacy: A library for advanced NLP.

    requests and BeautifulSoup: For web scraping.

    kagglehub: To download the SMS Spam Collection dataset.

The notebook includes code to install and download the necessary packages and data files.

Execution

    Open the NLP_ex1.ipynb file in Google Colab.

    Run the cells sequentially.

    The notebook will automatically download the SMS dataset.

    When prompted, you will need to manually upload the WhatsApp Chat.txt file from your local machine to the Colab environment.

    The final cells will demonstrate the tokenization and stemming process for both the English and Hebrew texts.

Code Overview

The notebook is divided into several sections to showcase different NLP tasks:

    Data Download & Loading: The code downloads the SMS Spam Collection Dataset and loads it into a pandas DataFrame.

    Initial Data Analysis: It calculates and prints basic statistics about the dataset, such as the number of messages and the frequency of the most common words.

    Text Processing (English): This section demonstrates tokenization, lemmatization, and stemming on the English SMS messages using both NLTK and SpaCy and then computes and compares statistics for each processed version of the data.

    Web Scraping: The code scrapes and extracts the title and paragraph text from a Wikipedia page about "Duck". It then applies the same NLTK and SpaCy processing pipelines to the scraped text to provide an example of text processing on a different kind of data.

    Text Processing (Hebrew): The notebook concludes by processing a Hebrew WhatsApp chat text. It uses NLTK with a simple heuristic stemmer and a blank SpaCy model to tokenize the text, acknowledging the limitations of these libraries for non-English languages.
