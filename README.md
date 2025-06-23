# MedBot-AI

MedBot-AI is a Retrieval Augmented Generation (RAG) based medical Q&A chatbot. This project allows users to get answers to medical questions from provided PDF documents.

## Project Description

This chatbot leverages a RAG architecture to answer user queries. It works by:
1. **Ingesting PDFs:** Providing PDF documents containing medical information.
2. **Retrieving Relevant Information:** Extracting relevant information from the ingested PDFs based on the user's question.
3. **Generating Answers:** Utilizing a language model to generate accurate answers based on the retrieved information.

## Features

*   **RAG-based Q&A:** Answers medical questions using a RAG approach.
*   **PDF Support:** Processes information from PDF documents.
*   **Medical Domain:** Designed for medical Q&A.

## Installation

(Further details on installation would be added here, typically including steps like cloning the repository, installing dependencies from `requirements.txt`, and setting up any necessary environment variables.)

## Usage

(Further details on how to use the chatbot would be added here, including how to provide PDFs and how to interact with the chatbot.)

## Project Structure

The repository includes the following key files and folders:

*   `data/`: Likely contains the PDF documents used for RAG.
*   `vectorstore/db_faiss/`: Stores the FAISS index for efficient similarity search.
*   `connect_memory_with_llm.py`: Connects memory components with the Language Model.
*   `create_memory_for_llm.py`: Handles the creation of memory for the Language Model.
*   `medbot.py`: The main script for the MedBot-AI application.
*   `requirements.txt`: Lists the Python dependencies required for the project.
*   `LICENSE`: The MIT License file.
*   `README.md`: This README file.

## License

This project is licensed under the [MIT License](https://github.com/NITIN9181/MedBot-AI/blob/main/LICENSE).

## Contributions

(Information on how to contribute to the project would be added here.)

## Contact

(Contact information for the project owner would be added here.)~