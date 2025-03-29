# Vector Store with Conversational AI and Embedding Visualization

## Overview

This project implements a conversational AI system featuring document embedding storage, retrieval, and visualization. It utilizes OpenAI's language model (GPT-4o-mini) to process markdown documents from a knowledge directory. The system converts these documents into vector embeddings, enables chat-based retrieval, and visualizes the embeddings in 2D and 3D using t-SNE and Plotly.

## Features

* Loads markdown documents from the `knowledge/` directory.
* Splits documents into smaller, manageable chunks for improved processing.
* Generates vector embeddings using `OpenAIEmbeddings`.
* Stores and retrieves embeddings efficiently using the Chroma vector database.
* Visualizes high-dimensional embeddings in 2D and 3D using t-SNE and Plotly.
* Implements a conversational AI interface with memory capabilities.
* Provides a user-friendly Gradio-based chat interface for interaction.

## Requirements

### Prerequisites

* Python 3.8 or higher

### Required Libraries

Install the necessary libraries using pip:

```bash
pip install openai langchain langchain_openai langchain_chroma chromadb gradio numpy scikit-learn pandas plotly python-dotenv

##Author
* Chandan Kumar