# Machine-learning
A_simple_chatbot_using _python

Chatbots have been a major buzz the last couple of years. Since 2015, chatbots started popping up like corn in big and small companies and this on many different channels. Facebook Messenger, Skype (for business), Slack, Team or as a traditional web chat hosted on a website.. you name it!
![Alt text](https://reactjsexample.com/content/images/2018/07/React-Simple-Chatbot.gif)

# Outline
* [Motivation](#motivation)
* [Pre-requisites](#pre-requisites)
* [How to run](#how-to-run)
## Motivation
 The project was built by learning from cognitive classes in the course of how to build a chatbot
 
## Pre-requisites
**NLTK(Natural Language Toolkit)**

[Natural Language Processing with Python](http://www.nltk.org/book/) provides a practical introduction to programming for language processing.

For platform-specific instructions, read [here](https://www.nltk.org/install.html)

### Installation of NLTK
```
pip install nltk
```
### Installing required packages
After NLTK has been downloaded, install required packages
```
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 
```

## How to run

* Through Terminal in linux
```
python chatbot.py
```
