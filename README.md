# DS593 Final Project
##  RAG-based Question Answering over Course Materials

### Project Overview
This project builds a Retrieval-Augmented Generation (RAG) question-answering system over course materials such as lecture slides, notes, and assignments. The goal is to help students quickly find key information when preparing for exams or completing homework.

### Motivation
During studying, important concepts are often spread across different documents, making it difficult and time-consuming to find relevant information. This project aims to improve efficiency by providing accurate and relevant answers grounded in course materials.

### Method
The system follows a basic RAG pipeline:
1. Convert course materials into text and split them into chunks
2. Retrieve relevant chunks based on a user question
3. Use a large language model (LLM) to generate answers based on retrieved content

I will experiment with:
- Different retrieval methods (keyword-based vs semantic search)
- Different chunking strategies (small vs large chunks)

### Baseline
As a baseline, I will compare the RAG system with direct prompting (no retrieval) to see if RAG improves answer quality.

### Evaluation
I will create a small test set of around 10–20 questions based on the course materials.  
The answers will be evaluated based on:
- Accuracy
- Relevance
- Completeness

### Expected Outcome
The goal is to determine:
- Whether RAG improves answer quality compared to direct prompting
- Which retrieval and chunking methods perform better

### Tech Stack
- Python
- Large Language Model (e.g., OpenAI API)
- Embedding model for semantic retrieval

### Future Work
- Improve retrieval quality
- Explore better evaluation methods
- Expand dataset
