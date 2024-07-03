# ChatwithPDF

ChatwithPDF is a LangChain and Streamlit application that enables users to interactively query information from uploaded PDF documents. The app utilizes Google Generative AI for embedding text and facilitating conversational Q&A sessions based on the content extracted from PDFs.

## Features

- **PDF Upload:** Users can upload multiple PDF documents.
- **Text Extraction:** Automatically extracts text content from uploaded PDFs.
- **Text Chunking:** Splits extracted text into manageable chunks for efficient processing.
- **Embedding Creation:** Generates embeddings for text chunks using Google Generative AI.
- **Conversational Q&A:** Uses LangChain to answer user questions based on the embedded content of PDFs.
- **User-Friendly Interface:** Built with Streamlit, providing a simple and intuitive user interface.

## Technologies Used

- **LangChain:** Integrates various language processing tasks such as text extraction, chunking, embedding, and conversational AI.
- **Streamlit:** Creates interactive web applications directly from Python scripts.
- **Google Generative AI:** Provides advanced text embedding capabilities.
- **PyPDF2:** Library for extracting text from PDF documents.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ChatPDFApp.git
   cd ChatPDFApp
2. Install the required dependencies:
   ```bash
    pip install -r requirements.txt

3. Set up your Google API key:

    Create a .env file in the root directory of the project.
    Add your Google API key to the .env file:

    ```makefile
    GOOGLE_API_KEY=your_api_key_here

4. Run the Streamlit app:
    ```bash
    streamlit run app.py

Usage

    Open the app in your browser.
    Upload PDF documents containing textual content.
    Ask questions related to the content of the uploaded PDFs.
    View the app's responses based on the extracted information.
