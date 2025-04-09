# RAG-PDF-Reader

A simple LLM project that interacts with PDF files, built using Retrieval-Augmented Generation (RAG), OpenAI API, and ChromaDB.

## Features

- Extracts and processes content from PDF files.
- Leverages RAG for efficient information retrieval.
- Uses OpenAI API for natural language understanding and generation.
- Employs ChromaDB for vector storage and similarity search.

## Requirements

- Python 3.8+
- OpenAI API key
- Required Python libraries (see `requirements.txt`)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/iamkabiru/rag-pdf-reader.git
    cd rag-pdf-reader
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up your OpenAI API key:
    ```bash
    export OPENAI_API_KEY=your_api_key
    ```

## Usage

1. Place your PDF files in the `data/` directory.
2. Run the script:
    ```bash
    python main.py
    ```
3. Interact with the system to query information from the PDFs.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- OpenAI for their API.
- ChromaDB for vector database support.
- The open-source community for their contributions.
