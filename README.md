[![Pycharm Badge](https://img.shields.io/badge/PyCharm-000000.svg?&style=for-the-badge&logo=PyCharm&logoColor=white)](https://www.jetbrains.com/pycharm/)
[![Python Badge](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3120/)
![LangChain Badge](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=fff&style=for-the-badge)
[![Ollama Badge](https://img.shields.io/badge/Ollama-000000.svg?style=for-the-badge&logo=Ollama&logoColor=white)](https://ollama.com)

## General Information

- Python version is: 3.12.0 (*if you need to download it, click on the Python badge*)
- Ollama is necessary to run this project (*if you need to download it, click on the Ollama badge*)

  - Once Ollama is downloaded, run via terminal:
    ```
    ollama run llama3.2
    ```

## LangGraph RAG agent - Travel planner advisor

This project builds a RAG agent using LangChain, LangGraph, and an open-source LLM from Ollama (llama3.2). 
Retrieves travel-related information by crawling a website, stores the data thanks to Chroma DB, and uses Nomic embeddings for document processing. 
The result is a travel planner advisor that provides personalized travel suggestions.
