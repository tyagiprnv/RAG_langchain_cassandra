## RAG PDF Question Answering System

## Overview

The **RAG PDF Question Answering System** is designed to extract answers from PDF documents using Retrieval Augmented Generation. This project uses Apache Cassandra, DataStax's Astra DB as a vector database, LangChain, Python, and GPT-3.5 to deliver accurate and efficient responses to user queries.

## Features

- **PDF Parsing**: Extract text from PDF documents.
- **Vector Database**: Utilize DataStax's Astra DB for efficient storage and retrieval of vectorized data.
- **LLMs**: Leverage GPT-3.5 to provide sophisticated question-answering capabilities.
- **Scalable Architecture**: Built with Apache Cassandra for high availability and scalability.
- **LangChain Integration**: Used langchain as the main framework for the application.

## Technologies Used

- **Apache Cassandra**: A highly scalable NoSQL database designed to handle large amounts of data across many commodity servers.
- **DataStax Astra DB**: A managed database-as-a-service offering built on Apache Cassandra that provides a vector database for efficient data retrieval.
- **LangChain**: A framework for building applications with language models that simplifies the integration of various components.

## Usage

- **Upload Pdf**: Upload and read pdf.
- **Add your DB and OpenAI tokens**: replace your tokens. (for DB setup follow this tutorial [here](https://docs.datastax.com/en/astra-db-serverless/get-started/quickstart.html#_prepare_for_using_your_vector_database))