# RAG-Based AI Teaching Assistant

This project implements a Retrieval-Augmented Generation (RAG) based AI Teaching Assistant that enables question answering over educational video content.

## Features
- Video-to-text transcription using Whisper with timestamps
- Text chunking with metadata storage
- Embedding generation for semantic search
- Retrieval of top relevant chunks based on user queries
- Context-aware response generation using a Large Language Model (LLM)
- Efficient data handling using Pandas and Joblib

## Tech Stack
- Python
- Whisper (Speech-to-Text)
- Pandas
- Joblib
- Vector Embeddings
- Large Language Models (LLMs)

## Workflow
1. Convert videos to audio and transcribe using Whisper
2. Chunk transcribed text and store metadata in JSON
3. Generate embeddings for each text chunk
4. Retrieve relevant chunks based on query similarity
5. Generate final response using retrieved context + LLM

This system demonstrates how RAG improves factual accuracy by grounding LLM responses in external knowledge sources.
