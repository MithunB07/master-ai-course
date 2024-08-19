# Find Similar Things App for Kids

## Overview

This Streamlit-based web application helps children discover similar content from a CSV file using embeddings and FAISS for efficient similarity searches. It is tailored for educational activities, offering kids relevant topics or concepts based on their queries.

## Features

- **Data Import**: Load educational data from a CSV file.
- **Semantic Search**: Utilize HuggingFace embeddings to find semantically similar content.
- **Similarity Matching**: Perform quick similarity searches with FAISS to find related topics.
- **User-Friendly Interface**: Simple and engaging interface for kids to input queries and explore results.

## Dependencies

- **streamlit**: Framework for building interactive web applications.
- **langchain**: Tools for creating language model-driven applications.
- **huggingface_hub**: Access to HuggingFace models and embeddings.
- **langchain_community**: Community tools and extensions for LangChain.
- **python-dotenv**: Manage environment variables via a `.env` file.

## Usage

- **Interacting with the App**
    - Launch the app in your browser by navigating to `http://localhost:8501`.
    - Type a query related to educational content in the text area.
    - Click on "Find Similar Things" to receive suggestions based on the CSV data.

## Visual

![Visual Representation](image.jpg)
