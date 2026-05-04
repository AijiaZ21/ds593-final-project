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

### Baseline
As a baseline, I will compare the RAG system with direct prompting (no retrieval) to see if RAG improves answer quality.

### Evaluation
I created a small test set of around 50 questions based on the course materials.
The answers are evaluated based on accuracy using manual labeling (Yes / Partial / No).
The RAG model achieves higher accuracy than the baseline (89% vs 53%), showing that retrieval improves answer quality.

### Expected Outcome
The goal is to determine:
- Whether RAG improves answer quality compared to direct prompting
- Which retrieval and chunking methods perform better

### Tech Stack
- Python
- Large Language Model
- Embedding model for semantic retrieval

## How to Run
1. Run dataset_chunks.ipynb to process the data  
2. Run baseline.ipynb to generate baseline answers  
3. Run RAG_pipeline.ipynb to generate RAG answers  
4. Run evaluation.ipynb to generate results  
5. Run evaluation_metrics_&_error_analysis.ipynb to compute metrics  

### Future Work
- Improve retrieval quality
- Explore better evaluation methods
- Expand dataset
