# Generative-AI-Financial-Report-Summarizer

## Overview
This project is an AI-powered tool that searches and summarizes financial earnings call transcripts for investment teams, enabling quick insights into financial performance metrics like revenue, EPS, and market growth.

## Features
- Semantic search for transcripts using Pinecone vector database.
- AI-generated summaries with a fine-tuned T5-small model.
- Interactive Gradio UI with customizable summary lengths (Short, Medium, Long).

## Technologies Used
- Python
- Pinecone (vector search)
- Hugging Face Transformers (T5-small)
- Sentence Transformers (all-MiniLM-L6-v2)
- Gradio (UI)

## Setup Instructions
1. Clone this repository.
2. Install dependencies: `pip install pinecone-client sentence-transformers transformers gradio pandas`
3. Set up a Pinecone API key and update the script.
4. Ensure the fine-tuned T5 model is available at `/content/t5_finetuned`.

## Usage
Run the script in Google Colab, enter a query (e.g., "Agilent Q4 2021 earnings"), select a summary length, and view the search result and AI-generated summary.