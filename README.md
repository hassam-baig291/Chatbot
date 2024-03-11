# Chatbot
AI based chatbot built using PyTorch 2.0.1 . It is trained on a self generated data set based on questions and answers about a construction website. Include a web page for user interactions.
This is a chatbot I created with Flask and JavaScript.

## Initial Setup:
This repo currently contains the starter files.

Install dependencies
```
$ (venv) pip install Flask torch torchvision nltk
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
Modify `intents.json` with different intents and responses for your Chatbot

Run
```
$ (venv) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (venv) python chat.py
```

