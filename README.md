# Multimodal-RAG with Ollama, and Langchain

![Demo Image](img/Untitled%20design.png)

A Multimodal Retrieval-Augmented Generation (RAG) system that supports text, audio, and PDF document processing using advanced LLMs and vector databases.

## Features
- Chait with your own documents (PDF, audio, etc.)
- Uses Ollama for local LLM inference
- Vector database support (Pinecone)
- Streamlit web interface

## Quickstart

1. **Clone the repository**
   ```sh
   git clone https://github.com/Anweshbyte/chAIGPT.git
   cd chAIGPT
   ```

2. **Set up the environment**
   ```sh
   python3 -m venv mrag
   source mrag/bin/activate
   pip install -r requirements.txt
   ```

3. **Download Ollama models**
   ```sh
   ollama pull <model>
   ```

4. **Configure your settings**
   - Edit `config.yaml` to set your preferred model and database.

5. **Run the app**
   ```sh
   streamlit run app.py
   ```

## Folder Structure
- `src/` - Source code for chains, vectorstore, utils, etc.
- `maxresdefault.jpg` - Demo image for the app
- `config.yaml` - Configuration file
- `requirements.txt` - Python dependencies

## Requirements
- Python 3.10+
- Ollama (for local LLMs)
- Streamlit
- Pinecone/Chroma (for vector DB)

## License
MIT
---
