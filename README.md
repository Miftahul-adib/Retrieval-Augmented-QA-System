# Retrieval-Augmented-Question-Answering-QA-System-using-FAISS-TAPAS
This project implements a Retrieval-Augmented Question Answering (RAG) pipeline for structured tabular data. Using a student dataset (CSV), the system enables natural language queries over the data.

## Workflow

1)Data Ingestion – Load and preprocess student dataset (CSV).

2)Vector Indexing – Store embeddings in a FAISS vector database for fast similarity search.

3)Retrieval – Retrieve relevant rows from the dataset based on the user’s query.

4)Question Answering – Use Google’s TAPAS model (Table-based Transformer) to answer natural language questions from retrieved data.

## Tech Stack

Python

FAISS (vector database)

Transformers (Hugging Face) – TAPAS model

Pandas for dataset processing

Jupyter Notebook for development



# Use Cases

Educational data analytics

Natural language querying over student databases

Prototype for tabular RAG systems
