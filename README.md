# RAG-Based-Intelligent-Document-Q-A-System

This project implements a Retrieval-Augmented Generation (RAG) pipeline using LangChain and Mistral AI. It processes PDF documents by splitting them into chunks, generating embeddings, and storing them in a Chroma vector database.

At query time, the system retrieves the most relevant chunks using MMR (Max Marginal Relevance) and feeds them into a language model to generate context-aware responses. The architecture ensures that answers are grounded in the source document, minimizing hallucinations.
