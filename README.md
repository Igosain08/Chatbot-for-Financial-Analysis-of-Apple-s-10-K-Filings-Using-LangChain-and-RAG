# Chatbot-for-Financial-Analysis-of-Apple-s-10-K-Filings-Using-LangChain-and-RAG
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

## **Installation**

### **Clone the Repository**
```bash
git clone https://github.com/your-username/apple-10k-financial-chatbot.git
cd apple-10k-financial-chatbot

Install Dependencies
bash
Copy code
pip install -r requirements.txt
Set Up Environment Variables
Create a .env file in the root directory and add your API keys:

plaintext
Copy code
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=your_huggingface_api_key
Run the Streamlit App
bash
Copy code
streamlit run app.py
Usage
Open the Streamlit App: After running the above command, the app will be available at http://localhost:8501/.
Interact with the Chatbot: Use the input box to ask financial questions related to Apple's 10-K filings. The chatbot will retrieve and analyze relevant sections of the document to provide answers.
Example Questions:
"What was Apple's total revenue for the most recent fiscal year?"
"How does Apple's net income compare to the previous year?"
"What are the key risks highlighted in Apple's latest 10-K?"
Project Structure
bash
Copy code
apple-10k-financial-chatbot/
│
├── app.py              # Main application file for running the Streamlit app
├── requirements.txt    # List of dependencies required for the project
├── .env                # Environment variables file (not included in the repository)
├── README.md           # Project documentation
└── data/
    └── apple_10k.pdf   # PDF file containing Apple's 10-K filing (ensure proper file path)
Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Special thanks to the creators of LangChain, Streamlit, and the various open-source libraries used in this project.
This project was inspired by the need for automated financial analysis tools tailored to specific companies' financial documents.
