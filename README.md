LightRAG: Retrieval-Augmented Generation for Warhammer 40K Rules

**Description**
This project is designed to create a simple Retrieval-Augmented Generation (RAG) system for answering questions about Warhammer 40K rules. It is based on a lightweight quantized LLama 3.2 (1B) model. The goal is to provide accurate and comprehensible answers.

**Features**
- RAG Workflow: Combines retrieval of rule data and context-aware response generation.
- Chunk Reranking: Uses BM25 to improve the relevance of retrieved context.
- Custom Prompt Templates: Employs Jinja2 templates to structure prompts for the language model.
- Chat Interaction: Supports maintaining dialog history with dynamic updates.
- Efficient Models: Uses quantized LLama 3.2 for optimized performance on limited resources.
