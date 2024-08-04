# Gemma Model Document Q&A

This Streamlit application uses the Gemma-7b-it language model and Google's embedding model to perform question-answering based on a set of documents. 
The Gemma 7B model, utilized via the *Groq API* , leverages Groq's advanced hardware accelerators to achieve high-performance and low-latency inference, making it ideal for real-time applications.
The documents are loaded from a directory, processed, and stored in a vector store database. Users can ask questions, and the application retrieves relevant document sections to provide accurate answers.

## Features

- Load and process documents from a specified directory
- Split documents into chunks for better processing
- Embed documents using Google Generative AI embeddings
- Store embeddings in a FAISS vector store
- Retrieve and answer questions based on document content
- Display document sections related to the question for better context
