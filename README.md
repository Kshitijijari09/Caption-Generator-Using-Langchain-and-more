# Readme File Generator App

## Overview

This Streamlit app, built with the LangChain library and OpenAI's language models, automatically generates README.md files for technology topics. It incorporates Wikipedia research to enrich the content, offering a unique blend of AI-driven text generation and factual data integration.

## Features

- **Interactive Input:** Enter technology-related prompts.
- **Dynamic README Generation:** Automatically crafts titles and README.md content.
- **Wikipedia Research Integration:** Enhances content with relevant data.

## Setup

1. **Installation:** Clone the repo and install dependencies:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   pip install streamlit langchain openai chromadb tiktoken wikipedia
   ```

2. **Confirgure OpenAPI apikey**
```bash
export OPENAI_API_KEY='your_api_key_here'
```
3. **Execution**
```bash
streamlit run app.py
```


