# Real-Time AI Voice Assistant with RAG Pipeline and Memory  

This project is a real-time voice assistant that captures voice input, transcribes it using Whisper, and generates intelligent, context-aware responses via a large language model (Mistral). It uses a RAG (Retrieval-Augmented Generation) pipeline with a vector database (Qdrant) to maintain memory and enhance response relevance.

##  📌 Features

- Voice input in real-time
- Fast and accurate speech-to-text using `faster_whisper`
- Intelligent responses powered by Mistral LLM (via Ollama)
- Context-aware replies using a vector-based knowledge base
- Easily customizable configuration (model, chunk size, etc.)

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **Whisper / Faster-Whisper** – for speech-to-text
- **Mistral LLM via Ollama** – for natural language generation
- **Qdrant** – vector database for memory & RAG
- **PyAudio** – for audio recording
- **NumPy, SciPy** – supporting libraries

---

## 🖼️ Example Use Cases

- Building intelligent voice assistants or chatbots
- Creating voice-based interfaces for custom knowledge bases
- AI-powered search over audio queries
- Educational tools with memory-enhanced conversation
- Virtual assistants for productivity or enterprise support
