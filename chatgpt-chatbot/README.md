# CHATGPT-ChatBot
This is a simple script to create a conversational chatbot focused on cryptocurrencies such as BTC, ETH, and SOL using the ChatGPT API and your own dataset.

## Installation
 ### Step 1. Clone the repository and navigate to the project folder:
 ```
git clone https://github.com/tooomlr/Projet_IA.git
```
 
 ```
cd chatgpt-chatbot
```
### Step 2. Install Required Packages:
Install Langchain, OpenAI, ChromaDB, tiktoken, unstructured, langchain-community, langchain-openai, and other required packages.
```
pip install langchain openai chromadb tiktoken unstructured langchain-community langchain-openai
```

### Step 3. Setup OpenAI API Key:
Modify constants.py with your own OpenAI API key.

### Example Usage 
Now you can interact with the chatbot, and it will utilize your crypto dataset to provide the responses. Here are a couple of example interactions:

### Query about Bitcoin (BTC)

Let's say, data.txt contains information about Bitcoin:
 ```
python chatgpt.py "what is BTC?"
 ```
Your chatbot will return information about BTC.

### Query about Ethereum (ETH)

In this case, data.txt contains information about Ethereum:
 ```
python chatgpt.py "what is ETH?"
 ```
Your chatbot will return information about ETH.

Each time you interact with your chatbot, it will look through the data files in your data/ directory and use the information in those files to generate a response.
