# FastDocs 📠

This is an automated programming language and framework documentation scraper 
for usage in local and online software development IDEs with AI assisted or 
autonomous coding capabilities.

created by Vertinski
(oc) 2024

## Description

FastDocs is a tool that allows automated search for programming framework documentation. It finds documents by user description and includes them in AI context for RAG. 
It supports multiple programming languages and uses DuckDuckGo search, Jina reader and Groq AI to find and process relevant documentation. 

## Features

- Supports multiple programming languages and frameworks
- Uses DuckDuckGo search for finding documentation
- Utilizes Groq AI for processing search results
- Retrieves most relevant documents with Jina reader
- Stores documentation in a buffer file for easy access by IDE's AI
- Provides a simple command-line interface for interaction

## Installation

The script automatically installs required modules:
- duckduckgo-search
- groq

## Usage

1. Run the script
2. Set your programming language when prompted
3. Use the following commands:
   - Search for documentation by entering your query
   - Type 'exit' to quit the program
   - Type 'help' for explanation of available commands

## Commands

- 'lang': Change your programming language
- 'clear': Clear the 'doc_buffer' file to free AI context space
- 'exit': Quit the program
- 'help': Show the help message

## Note

Replit allows a very small AI context size. The 'doc_buffer' file is limited to 21k characters or 5,200 tokens. The buffer contains only the most recent search result. 
Larger context length allows for more document storage in buffer file. FIFO rotation is encouraged unless you are building google v2.0. 


## Disclaimer

The software is provided as is. This tool is intended for development, educational and research use. It gets constantly improved. The author does not endorse or encourage any misuse or violation of terms of service of the APIs or services used in this project.
