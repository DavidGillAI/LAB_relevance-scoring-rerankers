# LAB | Relevance Scoring and Rerankers

## Files

* `relevance_scoring_reranking.ipynb` - Main notebook containing document loading, chunking, embeddings, retrieval, metadata filtering, relevance scoring, reranking, and RAG answer generation.
* `lab_summary.md` - Short summary of findings and recommendations.
* `data/` - Trustworthy AI transcript and Ethics Guidelines PDF used as source documents.

## How to Run

1. Create and activate a Python virtual environment.
2. Install required packages:

   * openai
   * numpy
   * python-dotenv
   * PyPDF2
   * tiktoken
   * ipykernel
3. Create a `.env` file containing:

   * `OPENAI_API_KEY`
4. Run the notebook from top to bottom.

## Features Implemented

* Metadata filtering
* OpenAI embeddings
* Cosine similarity retrieval
* LLM-based relevance scoring
* Reranking
* RAG answer generation
