# ChromaDB Python Examples

This project demonstrates the use of ChromaDB, a vector database for AI applications, to perform similarity searches on different datasets.

## Features

- Book similarity search with metadata filtering
- Employee data similarity search
- Uses SentenceTransformer embeddings for semantic search
- Cosine distance metric for similarity calculations

## Requirements

- Python 3.10+
- chromadb
- sentence-transformers

## Installation

1. Create a virtual environment:
   ```
   python3 -m venv .venv
   source .venv/bin/activate
   ```

2. Install dependencies:
   ```
   pip install chromadb sentence-transformers
   ```

## Usage

Run the book search example:
```
python advanced_book_search.py
```

Run the employee search example:
```
python similarity_employeedata.py
```

## Files

- `advanced_book_search.py`: Demonstrates book similarity search with filtering
- `similarity_employeedata.py`: Demonstrates employee data similarity search