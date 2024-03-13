# PDF Chatbot with Streamlit
This is a simple chatbot application designed to interact with PDF files. 
It uses Streamlit for the user interface and leverages various libraries for PDF processing and natural language understanding.

## Features
`PDF Parsing`: The bot can read and extract text from PDF files using the PyPDF2 library.
`Language Understanding`: Utilizes sentence-transformers and langchain for semantic understanding and sentence similarity calculations.
`Interactive Interface`: The bot is hosted on Hugging Face and can be accessed via a Streamlit web interface.
`Fast Text Search`: Incorporates faiss-cpu for efficient text search within PDF documents.
`OpenAI Integration`: Provides access to OpenAI's powerful language model for enhanced conversation capabilities.

## Usage
Install the required dependencies by running:
bash
Copy code
`pip install -r requirements.txt`
Set up your environment variables. You can use a .env file with the necessary configurations.

Run the application using Streamlit:

bash
Copy code
`streamlit run app.py`
Access the application through your browser at the provided URL.

## Requirements
streamlit
pypdf2
langchain
python-dotenv
faiss-cpu
openai
huggingface-hub==0.14.1
InstructorEmbedding==1.0.1
sentence-transformers==2.2.2

## Deployment
The bot is currently deployed on Hugging Face's infrastructure. You can access it here: https://huggingface.co/spaces/arad1367/ChatPDF_v.1.0.2
