# PDF RAG Assistant

Question-answering system over PDF documents using 
LangChain, OpenAI, and FAISS.

## What it does
Upload any PDF → ask questions → get answers with 
source page references.

## Stack
Python · LangChain · OpenAI API · FAISS · 
Prompt Engineering

## Setup
1. Clone the repo
2. Install dependencies
   pip install -r requirements.txt
3. Create a .env file
   OPENAI_API_KEY=your_key_here
4. Run the notebook

## Architecture
PDF → PyPDFLoader → Chunks → OpenAI Embeddings 
→ FAISS → Retriever → LLM → Answer + Sources
