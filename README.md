# CodeAgent 🤖

An Agentic RAG system for understanding GitHub repositories through natural language questions.

## 🎯 What is this?

CodeAgent lets you ask questions about any codebase in plain English:
- "How does authentication work in this repo?"
- "Where should I add a new API endpoint?"
- "Explain the database models"

## 🚀 Project Journey

This project is built in phases, documenting my learning journey from beginner to advanced:

| Phase | Name | Status | Tag |
|-------|------|--------|-----|
| Phase 1 | Naive RAG | ✅ Complete | [v0.1.0](https://github.com/pushwithak/codeagent/releases/tag/v0.1.0) |
| Phase 2 | Advanced RAG | ⏳ Upcoming | - |
| Phase 3 | Agentic RAG | ⏳ Upcoming | - |
| Phase 4 | Production RAG | ⏳ Upcoming | - |

## 🛠️ Tech Stack

- **Language:** Python 3.11+
- **LLM:** OpenAI GPT-4o-mini
- **Embeddings:** OpenAI text-embedding-3-small
- **Vector DB:** ChromaDB
- **Agent Framework:** LangGraph (Phase 3)
- **UI:** Streamlit (Phase 4)

## 📁 Project Structure
```
codeagent/
├── notebooks/         # Jupyter notebooks
│   └── 01_naive_rag.ipynb  # Phase 1 implementation
├── src/               # Main source code (Phase 2+)
├── app/               # Streamlit UI (Phase 4)
├── tests/             # Unit tests
└── docs/              # Documentation
```

## 🚦 Getting Started

### Prerequisites
- Python 3.11+
- OpenAI API key

### Installation
```bash
# Clone the repo
git clone https://github.com/pushwithak/codeagent.git
cd codeagent

# Create virtual environment with uv
uv venv
source .venv/bin/activate

# Install dependencies
uv pip install -r requirements.txt

# Create .env file
echo "OPENAI_API_KEY=your-key-here" > .env
```

### Usage
```bash
# Start Jupyter
jupyter notebook

# Open notebooks/01_naive_rag.ipynb
```

## 📚 What I Learned

### Phase 1: Naive RAG
- Vector embeddings and similarity search
- Chunking strategies for documents
- ChromaDB for vector storage
- LangChain for building RAG pipelines
- Prompt engineering for code Q&A

