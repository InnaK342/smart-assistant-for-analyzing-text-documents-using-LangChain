# Smart Assistant for Analyzing Text Documents Using LangChain

This project implements a **smart assistant** capable of analyzing text documents and answering questions based on their content. The assistant leverages the **LangChain** framework, **Hugging Face embeddings**, and **FAISS** for semantic search and efficient vector-based storage. 

## Features
- **Dynamic PDF Input**: Upload any PDF document for processing and analysis.
- **Semantic Search**: Extract relevant information by querying the content.
- **Scalable Storage**: Utilize FAISS for fast and efficient vector management.

## How It Works
1. **Text Extraction**: Extract text from uploaded PDF documents.
2. **Text Chunking**: Split the text into manageable chunks for processing.
3. **Vector Database**: Generate embeddings using Hugging Face models and store them in a FAISS database.
4. **Question Answering**: Retrieve answers to user queries based on the document's content.

## Example Data
This assistant was tested on the document [**"Text Classification Algorithms"**](https://www.mdpi.com/2078-2489/10/4/150?source=post_page---------------------------), which covers various methods and steps in text classification.

## Usage
1. Open the notebook `Smart_assistant_for_analyzing_text_documents_using_LangChain.ipynb`.  
2. Run the cells to upload a PDF, process the content, and interact with the assistant.
