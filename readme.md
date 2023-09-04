# Personalized Bot with Memory

## Introduction

This is a Streamlit application that allows you to interact with your PDF files using `Conversational Buffer Memory`. It utilizes various Python libraries and APIs, including `openai`, `langchain`, `tiktoken`, `pypdf`, and `faiss-cpu`.

## Installation Requirements

Before running this application, make sure you have the following libraries and APIs installed:

- `openai`
- `langchain`
- `tiktoken`
- `pypdf`
- `faiss-cpu`

## Usage

### Steps

1. **Upload PDF File**: Upload your PDF file to get started.
2. **Enter Your Secret Key for Embeddings**: Provide your OpenAI API Key, which you can obtain [here](https://platform.openai.com/account/api-keys).
3. **Perform Q&A**: After uploading the PDF and entering your API Key, you can perform question-answering tasks.

### Features

- Parse PDF files and extract text content.
- Convert text content into a list of documents.
- Perform embeddings with OpenAI.
- Implement a conversational agent with memory capabilities.

### Instructions

1. Upload your PDF file.
2. Enter your OpenAI API Key.
3. Ask questions related to the uploaded PDF.

**Note**: File content and API key are not stored in any form.
