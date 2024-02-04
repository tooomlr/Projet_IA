
# Projet_IA
This project comprises a custom AI chatbot implemented using PyTorch. The chatbot is designed to handle contextual conversations effectively.

## Chatbot 2: Pytorch Chatbot
This chatbot uses PyTorch and NLTK (Natural Language Toolkit) to develop a contextual chatbot from scratch.
## Installation

### Create an environment
```
 python3 -m venv venv
```

### Activate it
Mac / Linux:
```
. venv/bin/activate
```
Windows:
```
venv\Scripts\activate
```
### Install PyTorch and dependencies
 ```
pip install nltk
 ```

If you get an error during the first run, you also need to install `nltk.tokenize.punkt`:
Run this once in your terminal:
 ```
$ python
>>> import nltk
>>> nltk.download('punkt')
```

## Usage
You can train the model using the script 'train.py'. Run the following command in your terminal:
```
python train.py
```
After the model is trained successfully, you can use the chatbot by executing 'chat.py'. Run the following command:
```
python chat.py
```
Now, your contextual chatbot is ready to chat. Just type in a message and get a reply from your AI chatbot.
