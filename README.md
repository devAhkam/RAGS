# 🤖 Agentic RAG — Question Answering Bot

A Question Answering Bot built using Agentic RAG (Retrieval-Augmented Generation) 
that retrieves relevant information from documents and generates accurate, 
context-aware answers using Large Language Models.

---

## 🚀 What It Does

- Upload documents (PDF, JSONL, TXT)
- Ask questions in natural language
- Agent retrieves the most relevant chunks from the document
- LLM generates accurate answers based on retrieved context
- Reduces hallucinations through retrieval-grounded responses

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| LangChain | RAG pipeline & agent framework |
| FAISS / Chroma | Vector database for embeddings |
| OpenAI API | LLM for answer generation |
| Jupyter Notebook | Experimentation & testing |
| Typesense | Search & retrieval engine |

---

## 📁 Project Structure
RAGS/
├── agenticrag/        # Core agentic RAG logic
├── data/              # Sample documents & datasets
├── notebook/          # Jupyter notebooks for testing
├── main.py            # Main entry point
├── Requirement.txt    # Dependencies
└── README.md

---

## ⚙️ Setup & Installation

```bash
# Clone the repo
git clone https://github.com/devAhkam/RAGS.git
cd RAGS

# Install dependencies
pip install -r Requirement.txt

# Add your API key
cp .env.example .env
# Edit .env and add: OPENAI_API_KEY=your_key_here

# Run the bot
python main.py
```
