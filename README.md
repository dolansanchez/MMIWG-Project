MMIWG-Project:
A repository for code used in my Capstone Project at the University of Arizona iSchool. The project analyzes a corpus of Tweets related to the movement behind Missing and Murdered Indigenous Women and Girls, #MMIWG. The tweets were collected from Twitter's Premium Search API using twarc, a command line tool and Python library for archiving Twitter JSON data: https://github.com/DocNow/twarc

The dataset is avaialable as tweet IDs in the file mmiwg-tweet-ids.txt. The tweet IDs can be hydrated using twarc's Hydrator: https://github.com/DocNow/hydrator Learn about why: https://medium.com/on-archivy/on-forgetting-e01a2b95272#.lrkof12q5

This code was written to clean Twitter data and run a simple dictionary based affect analysis.

Getting Started:
Go to https://github.com/DocNow/twarc or https://www.tweepy.org/ to learn how to collect Twitter data. Or, create a .txt file of any corpus you would like to analyze for affect.

How It Works:
Load data files - a lexicon of your choice in .csv format and a .txt file containing the corpus you want to analyze

The code creates a dataframe with the lexicon, cleans the .txt file, and counts occurences of the word from the lexicon within the corpus. Then it creates a bar graph (you must manually fill in the data values to update the graph) showing the occurences of each affect.

Built With and Versioning:
This code was written using Python 3.8 with the Anaconda distribution.

Authors:
Danielle Dolan-Sanchez

Acknowledgements and Sources:
The base code is derived from Neal Caren's workshop on Word Lists and Sentiment Analysis, May 2019
https://nealcaren.org/lessons/wordlists/

The MMIWG lexicon used in this analysis was created by myself, Dr. Lindsay M. Montgomery of the School of Anthropology at UA, and Anthropology PhD student Jennifer Byram.

Links for additional inspiration and resources:
https://machinelearningmastery.com/clean-text-machine-learning-python/
https://www.geeksforgeeks.org/python-count-occurrences-of-each-word-in-given-text-file-using-dictionary/
https://github.com/attreyabhatt/Sentiment-Analysis
https://pythonexamples.org/python-count-occurrences-of-word-in-text-file/
https://github.com/darlastill/ResBaz-UA-Python-Twitter
http://www.nltk.org/book/
https://methodi.ca/recipes/dictionary-based-sentiment-analysis-python
