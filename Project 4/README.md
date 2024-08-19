# Marketing Content Generator

## Overview

This is a web application built with Streamlit that generates marketing content using a language model from Hugging Face. The app allows users to create various types of marketing content, including sales copy, tweets, and product descriptions, tailored to specific age groups such as Kids, Adults, and Senior Citizens.

The application uses the Hugging Face model `huggingfaceh4/zephyr-7b-alpha` for generating content.

## Features

- **Custom Marketing Content**: Generate tailored marketing materials based on user input.
- **Content Type Options**: Choose between Sales Copy, Tweet, or Product Description.
- **Target Audience Selection**: Specify the target age group—Kids, Adults, or Senior Citizens.
- **Word Limit Control**: Adjust the word count for the generated content.

## Example Workflow

1. **Input Query**: For example, "What is a mobile?"
2. **Choose Content Type**: Select "Write a sales copy."
3. **Select Target Audience**: Pick "Kids."
4. **Set Word Limit**: Adjust to 100 words.
5. **Generate Content**: Click "Generate" to receive a playful and engaging sales copy suitable for children.

## Dependencies

Make sure to install the following Python packages:

- `streamlit`: For building interactive web applications.
- `langchain`: A toolkit for developing language model applications.
- `huggingface_hub`: Access and interact with Hugging Face models.
- `python-dotenv`: Load environment variables from a `.env` file.

## Preview

![Screenshot](image.png)
