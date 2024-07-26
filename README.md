# AI-Chatbot-RAG-with-LangChain-Streamlit

Document Genie is a powerful Streamlit application designed to extract and analyze text from PDF documents, leveraging the advanced capabilities of Google's Generative AI, specifically the Gemini-PRO model. This tool uses a Retrieval-Augmented Generation (RAG) framework to offer precise, context-aware answers to user queries based on the content of uploaded documents.

## Prerequisites
- Google API Key: Obtain a Google API key to interact with Google's Generative AI models. Visit [Google API Key Setup](https://makersuite.google.com/app/apikey) to get your key.
- Streamlit: This application is built with Streamlit. Ensure you have Streamlit installed in your environment.

## Requirements
streamlit

google-generativeai

langchain

PyPDF2

chromadb

faiss-cpu

langchain_google_genai

os 


## Technical Overview
PDF Processing: Utilizes PyPDF2 for extracting text from PDF documents.

Text Chunking: Employs the RecursiveCharacterTextSplitter from LangChain for dividing the extracted text into manageable chunks.

Vector Store Creation: Uses FAISS for creating a searchable vector store from text chunks.

Answer Generation: Leverages ChatGoogleGenerativeAI from LangChain for generating answers to user queries using the context provided by the uploaded documents.
