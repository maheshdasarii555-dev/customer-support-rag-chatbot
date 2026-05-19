# Customer Support RAG Chatbot

## Project Overview
This project is an AI-powered Customer Support Chatbot built using Retrieval-Augmented Generation (RAG).

The chatbot retrieves relevant customer support information from stored documents and provides answers to user queries.

---

## Technologies Used
- Python
- LangChain
- FAISS
- HuggingFace Embeddings
- Jupyter Notebook

---

## Features
- Loads customer support documents
- Splits text into chunks
- Creates embeddings
- Stores vectors using FAISS
- Performs similarity search
- Answers customer support questions

---

## Example Questions
- How do I reset password?
- What is refund policy?
- Why payment failed?
- Why is delivery delayed?

---

## Project Workflow

Customer Support Data  
↓  
Document Loader  
↓  
Text Splitter  
↓  
Embeddings  
↓  
FAISS Vector Database  
↓  
User Question  
↓  
Similarity Search  
↓  
Retrieve Relevant Context  
↓  
Generate Answer

---

## Example Output

Ask Question: How do I reset password?

Retrieved Context:
Password Reset:
Users can reset password using Forgot Password option.

Answer:
Use the Forgot Password option to reset your password.

---

## Files Included

- customer_support_rag.ipynb
- support_data.txt
- README.md

---

## Author
Mahesh Kumar
