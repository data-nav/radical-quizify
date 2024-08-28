# AI Quiz Generator with Google Cloud and Vertex AI

This project is a comprehensive AI-powered quiz generation tool leveraging Google Cloud's Vertex AI and other modern technologies. The project is designed to create an interactive quiz generation application using advanced document processing, embeddings, and data pipelines.

## Features

- **Google Cloud Setup**: Get started with Google Cloud, create a project, enable Vertex AI APIs, and manage service accounts with owner permissions.
- **Development Environment**: Set up your development environment by cloning and forking GitHub repositories, managing service account keys, and handling authentication errors.
- **Document Ingestion**: Implement file handling with Streamlit, including processing PDFs and testing document ingestion with PyPDFLoader.
- **Embedding with Vertex AI & Langchain**: Initialize and test VertexAIEmbeddings, embedding text into Streamlit applications.
- **Data Pipeline to Chroma DB**: Transform and collect data using ChromaDB, split text chunks, and create in-memory collections, tested with small PDFs.
- **Streamlit UI for Data Ingestion**: Build a user-friendly interface for selecting topics and question quantities, using Chroma collections for quiz generation.
- **Quiz Generator**: Utilize the "gemini-pro" model, configure output parameters, and integrate with vector stores for context-driven question generation.
- **Quiz Generation Algorithm**: Implement a robust quiz generation algorithm, ensuring question uniqueness and validating against a question bank.
- **Quiz UI**: Manage and display quiz questions seamlessly, using the QuizManager class with PDF ingestion via Streamlit.
- **Screen State Handling**: Efficiently manage quiz setup, navigation, and display, providing a smooth user experience.

## Installation

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-username/ai-quiz-generator.git
   cd ai-quiz-generator
