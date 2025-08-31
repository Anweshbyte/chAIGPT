# Multimodal-RAG

![Demo Image](img/Untitled%20design.png)

A Multimodal Retrieval-Augmented Generation (RAG) system that supports text, audio, and PDF document processing using advanced LLMs and vector databases.

## Features
- Chat with your own documents (PDF, audio, etc.)
- Uses Ollama for local LLM inference (DeepSeek, Mistral, Llama, etc.)
- Vector database support (Chroma, Pinecone)
- Streamlit web interface
- Modular and extensible codebase

## Quickstart

1. **Clone the repository**
   ```sh
   git clone <repo-url>
   cd Multimodal-RAG
   ```

2. **Set up the environment**
   ```sh
   python3 -m venv mrag
   source mrag/bin/activate
   pip install -r requirements.txt
   ```

3. **Download Ollama models**
   ```sh
   ollama pull deepseek-r1:1.5b
   # or any other model you want to use
   ```

4. **Configure your settings**
   - Edit `config.yaml` to set your preferred model and database.

5. **Run the app**
   ```sh
   streamlit run app.py
   ```

## Folder Structure
- `src/` - Source code for chains, vectorstore, utils, etc.
- `mrag/` - Python virtual environment (not tracked by git)
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

*For more details, see the code and comments in each module.*
