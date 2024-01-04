# Code Explainer with Retrieval-Augmented Generation (RAG)

This repository contains a Python script that leverages the power of Retrieval-Augmented Generation (RAG) to explain and understand code snippets. It integrates Transformers, LLaMA index, Langchain embeddings, and custom embeddings to provide comprehensive and understandable explanations of code.

## Features

- **Transformers Integration**: Uses AutoModelForCausalLM and AutoTokenizer from the Hugging Face's Transformers library.
- **Efficient Indexing with LLaMAIndex**: Utilizes VectorStoreIndex and SimpleDirectoryReader for efficient indexing and retrieval.
- **Custom Embeddings**: Supports Sentence Transformers, BGE, UAE, and Instructor embeddings for better understanding and contextual representation of code.
- **Flexible Configuration**: Argument parsing allows for easy customization and control over the script's behavior.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x
- Pip (Python package installer)

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/Asad-Ismail/RAF_CODE-QA.git
```