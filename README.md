# Simple Gen AI App Using LangChain

## A Retrieval-Augmented Generation Application RAG
## Overview
This project demonstrates a **Generative AI Application** using **LangChain**. The focus is on **data ingestion** and **data transformation**, particularly breaking data into manageable chunks. The implementation is designed to help AI-based applications preprocess textual data efficiently, making it more structured for downstream tasks such as retrieval-augmented generation (RAG) and chatbot development.

## Features
- **Data Ingestion**: Load and preprocess textual data. from Website -https://platform.openai.com/docs/models#gpt-4o-audio
- **Data Transformation**: Segment large data into smaller, structured chunks for better processing.
- **Data Transformation**: Performed Vector Embedding- Used OpenAIEmbeddings "text-embedding-3-large" model to convert words to numerical vectors. 
- **Data Transformation**: Stored the Vectors into FAISS Vector store db 
- **Model Building** :From ChatOpenAI used LLM model ="gpt-4o" for data processing
- **Model Testing**: Retrived the chained documents from the data from the vector db based on context. Also tested Model Performance 

## Model Applications Use Case
This project can be used for:
- **Chatbots & Conversational AI**: Preparing data for conversational agents.
- **Retrieval-Augmented Generation (RAG)**: Structuring data for knowledge retrieval.
- **AI-powered Document Processing**: Handling large-scale text documents efficiently.

## Contributing
Feel free to fork this repository, raise issues, and submit pull requests to improve the project.

