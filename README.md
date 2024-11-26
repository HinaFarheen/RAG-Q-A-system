# Retrieval-Augmented Generation (RAG) Question-Answering System

This project implements a Retrieval-Augmented Generation (RAG)-based Question-Answering (QA) system designed to answer questions related to the Travel and Tourism domain. The system combines the power of large language models (LLMs) with information retrieval techniques to provide accurate and contextually relevant answers. It retrieves information from a curated corpus of documents specific to travel destinations, tips, itineraries, female travel and tourism services, enabling it to respond to user queries in natural language. The system leverages keyword-based search techniques like TF-IDF, BM25 and semantic search techniques like MMR, FAISS for effective information retrieval and integrates with the multiple LLMs hosted on Hugging Face for generation. Key features include processing user questions, fetching relevant document snippets, and generating coherent answers that reflect the latest insights from the travel domain. This system can be adapted to various use cases, including customer support for travel agencies, personalized travel recommendations, and tourism-related information retrieval.

## 📂 Project Structure
- `Corpus/`: Contains domain-specific PDF files used for information retrieval.
- `RAG_QA_System.ipynb`: Jupyter Notebook with the implementation of the RAG-based QA system.
- `Report.docx`: Detailed report documenting the project approach, methodologies, and results.

