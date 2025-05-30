# Local AI Stock Analysis

This project is a small experiment made to summarize headline information for a single stock. It is mainly meant to test efficacy of local AI for unsupervised web-scraping code generation and article summarization. If the local AI can create a solution without providing a framework, I now have a powerful new tool. If not, then I at least have some knowledge of the ```smolagents``` library for future use.

**Note:** This code requires modern hardware to execute successfully. I am able to run this on a MacBook M4 chip at relatively acceptable speeds. Moreover, the DeepSeek model takes up several gigabytes of storage.

## Setup

1) Install the [latest version Ollama](https://ollama.com/) if not already installed. Ollama must be running in the background for ```smolagents``` to work.
2) Install ```deepseek-r1:14b``` [here](https://ollama.com/library/deepseek-r1:14b). Simply copy the command and paste it in your terminal.
3) Run ```pip install -r requirements.txt``` in your terminal.

## Execution

Simply hit "Run All" in ```stock_analysis.ipynb``` and await the results.

## Conclusions from "Test Web-Scraping Capabilities Without any Framework" Section

The model attempts seemingly random methods of extracting the article information for the given website. The context window also becomes an issue around step 7 or 8 where the model hilariously starts looking up Paris's population density.

In other words (and unsurprisingly), this is not a viable method for web-scraping, as the model needs far more structure to successfully extract the relevant information. I'd be astounded if this worked in the first place, so we now need to investigate methods of extracting web page content to provide to the model.

In essence, if I determine the extraction method and can feed the data to the model in a structure it likes, then I might be onto something here.

