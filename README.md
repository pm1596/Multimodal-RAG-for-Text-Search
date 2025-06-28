# Multimodal-RAG-for-Text-Search

A Retrieval-Augmented Generation (RAG) system that enables **text and image-based search**, combining CLIP embeddings for multimodal retrieval and an LLM for answer generation.

![Demo](assets/demo.gif)

## Features ✨
- **Multimodal Queries**: Search using **text** or **images**.
- **Hybrid Retrieval**: FAISS-based vector search for text and image embeddings.
- **LLM-Augmented Answers**: Generate context-aware responses using retrieved documents.
- **Gradio UI**: Interactive web interface for easy testing.

## Tech Stack 🛠️
- **Embeddings**: OpenAI's CLIP (text + image)
- **Vector DB**: FAISS (or Pinecone/Weaviate for scale)
- **LLM**: Llama 2 / GPT-3.5-turbo (via Hugging Face/OpenAI)
- **Framework**: Python, PyTorch, Hugging Face Transformers

## Installation 🚀

1. **Clone the repository**:
   ```bash
   git clone https://github.com/user-name/multimodal-rag.git
   cd multimodal-rag
