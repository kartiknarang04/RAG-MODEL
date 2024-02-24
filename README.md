# RAG-MODEL
An interactive application that allows users to ask questions about the content of PDF documents they upload. The system utilizes a powerful language model to understand and answer user queries.

# PDF Genie

## Overview

Chat with PDFs is an interactive application that allows users to ask questions about the content of PDF documents they upload. The system utilizes a powerful language model to understand and answer user queries.

## Key Features

1. **Document Processing:** Users can upload PDF documents.
2. **Text Extraction:** The system extracts text from the uploaded PDFs.
3. **Chunking:** The text is divided into manageable chunks for processing.
4. **Question-Answering Model:** A pre-trained language model, such as OpenAI's GPT-3 or Hugging Face's Instructor, is employed for answering user queries.
5. **Vector Representation:** The application creates vector representations of the text chunks.
6. **Conversational Memory:** The system retains a conversation history to provide context-aware responses.
7. **User Interaction:** Users can input questions, and the system generates responses based on the content of the PDFs.
8. **User Interface:** Streamlit is used to create an intuitive and user-friendly interface.
9. **Deployment:** The application is deployable, allowing users to access it through a web interface.

## Technologies Used

- Python
- Streamlit
- PyPDF2 for PDF processing
- Sentence Transformers for embeddings
- OpenAI API or Hugging Face Hub for language model
- Faiss for vector indexing and retrieval

## Instructions for Users

1. Upload PDF documents.
2. Ask questions related to the content of the PDFs.
3. Click "Process" to get real-time responses.

**Note:** Ensure that the OpenAI API key is set up or pass it as a named parameter when using OpenAIEmbeddings.

## Getting Started

1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Set up your OpenAI API key or other required credentials.
4. Run the application: `streamlit run app.py`
