# **Chatbot for Financial Analysis of Apple's 10-K Filings Using LangChain and RAG**

## **Project Overview**

This project implements an automated chatbot designed to analyze Apple's 10-K filings and provide financial insights. Leveraging LangChain and Retrieval-Augmented Generation (RAG), the chatbot delivers accurate, context-aware responses based on Apple's official financial documents. The chatbot is integrated with a Streamlit web interface for easy interaction.

## **Features**

- **Automated Financial Analysis**: Provides detailed insights into Apple's financial health based on its 10-K filings.
- **Real-time Data Retrieval**: Uses RAG to retrieve relevant information from the 10-K documents dynamically.
- **Contextual Responses**: Generates context-aware responses by integrating LangChain with a history-aware retriever.
- **User-friendly Interface**: Offers a Streamlit-based web interface for easy access and interaction.

## **Technologies Used**

- **LangChain**: For building the chatbot and managing the integration of language models.
- **Retrieval-Augmented Generation (RAG)**: For dynamic retrieval and response generation based on specific user queries.
- **Streamlit**: For creating an interactive web interface.
- **Chroma**: For vector storage and retrieval.
- **HuggingFace**: For generating embeddings.
- **PyPDFLoader**: For loading and processing Apple's 10-K PDF documents.

## **Dependencies**

This project requires the following Python packages:

- `langchain`
- `streamlit`
- `chroma`
- `huggingface-hub`
- `pypdf2`
- `python-dotenv`

You can install all required packages using the `requirements.txt` file included in the repository.

### **Install Dependencies**
```bash
pip install -r requirements.txt
