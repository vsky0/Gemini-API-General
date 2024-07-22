# Gemini-API

Accessed the gemini via API using the google-generativeai module.

## Retrieval Augmented Generation (RAG) with Gemini

This notebook demonstrates how to build a Retrieval Augmented Generation (RAG) system using Google Gemini's multimodality. The system is designed to efficiently search and summarize information from various sources, including text, video, and audio.

### Key Features

- **Multimodal Data Processing**:  Handles text (extracted from images using OCR), video, and audio data.
- **Gemini for Summarization**: Leverages Gemini's powerful language capabilities to generate concise summaries of each data modality.
- **Embedding Generation**: Uses Gemini's Text Embedding Model to convert summaries into vector embeddings for efficient similarity search.
- **Chroma DB Integration**: Employs Chroma DB as a vector database to store and retrieve embeddings, enabling fast and accurate document retrieval.
- **Querying and Retrieval**: Allows users to query the RAG system and retrieve the most relevant documents based on semantic similarity.

#### Steps

1. **Data Preparation**: Collect and organize text, video, and audio data related to the Apollo 11 mission.
2. **Data Extraction and Summarization**:
   - Extract text from images using Tesseract OCR.
   - Use Gemini to generate summaries for each data modality.
3. **Embedding Generation**: Convert summaries into vector embeddings using Gemini's Text Embedding Model.
4. **Vector Database Creation**: Create a Chroma DB instance and store the generated embeddings.
5. **Querying**:  Query the RAG system with natural language queries to retrieve relevant documents.

## Usage

This notebook provides a comprehensive example of building and using a RAG system. You can adapt the code and techniques to your specific data and use cases.
