# Local AI Stock Analysis

This project is a series of experiments made to test efficacy of automating web scraping using local AI models using Ollama. This will involve multiple attempts using different methods to find a concrete solution.

Essentially, having the ability to web-scrape with local AI carries many implications and seemingly infinite use cases; all of which would require no expenses other than a computational load.

**Note:** This code requires modern hardware to execute successfully. I am able to run this on a MacBook M4 chip at relatively acceptable speeds. Moreover, the DeepSeek model takes up several gigabytes of storage.

## Setup for ```web_scrape_no_context.ipynb```

1) Install the [latest version Ollama](https://ollama.com/) if not already installed. Ollama must be running in the background for ```smolagents``` to work.
2) Install ```deepseek-r1:14b``` [here](https://ollama.com/library/deepseek-r1:14b). Simply copy the command and paste it in your terminal.
3) Run ```pip install -r requirements.txt``` in your terminal.

## Execution

Simply hit "Run All" in ```stock_analysis.ipynb``` and await the results.

## Setup for ```web_scrape_with_context.ipynb```
