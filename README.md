# Language-Detection-From-Text---Bi-gram-based
Language-Detection-From-Text---Bi-gram-based It uses Bi-gram language model and bi-gram frequency addition classifier for language identification task.  
Trained over 6 languages namely German, English, Spanish, French, Italian and Dutch.  
The original source of the text corpus is wortschatz leipzig corpora. Both the train and test corpus were taken from this corpora. 
The training corpus consists of 30000 sentences from news/web domain. 
Test corpus 10000 unseen sentences from news/web domain.  Also, the chosen six languages were such that the same languages are present in the LIGA twitter dataset which consists of 9066 tweets.  

Note : Directory path used for train and test corpus in code language-test.py, language-train.py and liga_test.py needs to be properly set accordingly.

# Installation
You only need to install these (tested):

Install Anaconda 64 bit Python 2.7 version. (https://www.continuum.io/downloads)
Install NLTK data using interactive installer (http://www.nltk.org/data.html)
