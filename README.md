Objective
Build a conversational AI tutor with:
● RAG-powered backend (LangChain/LangGraph + Vector DB).
Tool Purpose Ollama Run LLMs like Mistral locally LangChain Prompt chaining, memory, and retrieval 
FAISS Vector search for document Q&A 
Streamlit Interactive web UI 
SpeechRecognition Microphone voice input 
pyttsx3 Text-to-speech voice output 
PyPDFLoader & TextLoader Load files for Q&A

🎯 Features
💬 Chat with local LLM using [mistral:7b] from Ollama
📄 Upload PDFs or text files and ask questions about them
🧠 Chat memory that persists across sessions
🎙️ Voice input via mic
🔊 Voice output via TTS
🎨 Personality control with a system prompt
💾 Runs offline — no internet needed

🖼️ The Interface
I built the frontend using Streamlit, which let me:

Display a chat log with user and assistant messages
Upload and parse documents
Toggle voice features from the sidebar
Save chat logs as JSON files behind the scenes

