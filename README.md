# AI Text Embeddings with LangChain and Hugging Face  

## Overview  
This project demonstrates how to create **text embeddings** using **Hugging Face's Embeddings model** and **LangChain**. The pipeline loads web data from multiple URLs, processes it into manageable chunks, and converts the text into vector format for downstream AI applications.  

## Features  
- **Unstructured Data Ingestion**: Load text from websites using `UnstructuredURLLoader`  
- **Text Preprocessing**: Use `TextSplitter` to break long text into smaller chunks  
- **Embeddings Generation**: Convert text into vector format with `HuggingFaceEmbeddings`  
- **Vectorization**: Prepare text embeddings for use in similarity search, NLP tasks, and retrieval-augmented generation (RAG)  
