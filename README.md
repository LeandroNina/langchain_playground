# LangChain Playground
Practical RAG + tools/agents + evaluation with LangChain.

## Highlights
- Retrieval (FAISS/Chroma) + rerank
- Tools/Agents (search, calculator, file QA)
- Tracing + evals (`langsmith`)

## Quickstart
conda create -n lc python=3.11 -y
conda activate lc
pip install langchain langchain-community chromadb pydantic sentence-transformers

python demos/rag_basic.py
