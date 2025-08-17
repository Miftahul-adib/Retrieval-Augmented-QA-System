# 📊 Retrieval-Augmented Question Answering (RAG) with FAISS + TAPAS

This project implements a **Retrieval-Augmented Question Answering (RAG)** pipeline for **structured tabular data**. Using a student dataset (CSV), the system allows **natural language queries** over the data.

## 🔄 Workflow

1. **Data Ingestion** – Load and preprocess the student dataset (CSV).  
2. **Vector Indexing** – Store embeddings in a **FAISS vector database** for fast similarity search.  
3. **Retrieval** – Fetch relevant rows from the dataset based on the query.  
4. **Question Answering** – Use Google’s **TAPAS model** (Table-based Transformer) to answer natural language questions.

## 🛠 Tech Stack

- **Python**  
- **FAISS** (vector database)  
- **Hugging Face Transformers** – TAPAS model  
- **Pandas** – dataset processing  
- **Jupyter Notebook** – development environment  

## 📌 Use Cases

- Educational data analytics  
- Natural language querying over student databases  
- Prototype for tabular RAG systems

## 📂 Dataset

The student dataset used in this project is available on Kaggle:  
[Students Grading Dataset (Biased)](https://www.kaggle.com/datasets/mahmoudelhemaly/students-grading-dataset?select=Students_Grading_Dataset_Biased.csv)
