# Agentic RAG

A tutorial project demonstrating **Agentic Retrieval-Augmented Generation (RAG)** workflows using Large Language Models (LLMs). This project is part of the [awesome-llm-apps](https://github.com/) collection and showcases how to build agentic RAG pipelines for advanced question answering and knowledge retrieval.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

**Agentic RAG** combines the power of LLMs with external data sources, enabling the model to retrieve relevant information and reason over it in an agentic (multi-step, tool-using) manner. This tutorial guides you through setting up a basic agentic RAG pipeline, including document ingestion, retrieval, and LLM-based answer generation.

---

## Features

- Document ingestion and indexing
- Semantic search/retrieval
- LLM-powered answer generation
- Agentic reasoning (multi-step tool use)
- Modular and extensible codebase

---

## Project Structure

```
agentic_rag/
├── data/               # Sample documents and datasets
├── src/                # Source code for RAG pipeline
│   ├── ingest.py
│   ├── retrieve.py
│   ├── agent.py
│   └── ...
├── notebooks/          # Jupyter notebooks for tutorials and demos
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
└── ...
```

---

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Yavic2024/agentic_rag.git
   cd agentic_rag
   ```

2. **Create a virtual environment (optional but recommended):**
   ```sh
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

---

## Usage

1. **Prepare your data:**  
   Place your documents in the `data/` directory.

2. **Ingest and index documents:**
   ```sh
   python src/ingest.py
   ```

3. **Run retrieval and agentic RAG pipeline:**
   ```sh
   python src/agent.py --query "Your question here"
   ```

4. **Explore with Jupyter Notebooks:**  
   Open and run the notebooks in the `notebooks/` folder for interactive tutorials.

---

## Configuration

- Edit configuration parameters (e.g., model names, data paths) in `src/config.py` or as command-line arguments.
- API keys for LLM providers (OpenAI, etc.) should be set as environment variables.

---

## Examples

```sh
python src/agent.py --query "What is Retrieval-Augmented Generation?"
```

---

## Contributing

Contributions are welcome! Please open issues or pull requests for improvements, bug fixes, or new features.

---

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

