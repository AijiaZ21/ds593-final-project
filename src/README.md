# DS593 SRC

## Notebooks Overview

### 1. dataset_chunks.ipynb
This notebook processes the raw course materials.  
It combines lecture content, splits it into pages, and further divides the text into smaller chunks for retrieval.

### 2. baseline.ipynb
This notebook implements the baseline model.  
It directly uses a language model to answer questions without retrieval.

### 3. RAG_pipeline.ipynb
This notebook implements the RAG system.  
It retrieves relevant chunks using embeddings and generates answers based on the retrieved content.

### 4. Prompt.ipynb
This notebook is used to test and design prompts for the language model.  
It have 50 prompt questions and used for the evaluation.

### 5. evaluation.ipynb
This notebook generates answers for both the baseline and RAG models on the test questions and stores the results.

### 6. evaluation_metrics_&_error_analysis.ipynb
This notebook computes evaluation metrics such as accuracy and similarity.  
It also includes error analysis based on manual labeling.
