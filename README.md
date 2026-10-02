# IBM RAG Agentic AI

This repository contains a structured learning path and hands-on notebooks for building a Retrieval-Augmented Generation (RAG) and Agentic AI application using IBM AI tooling and modern multimodal data workflows.

The project is organized into four modules that progressively move from data preparation and vector indexing to multi-agent recommendation systems and Model Context Protocol (MCP) application development.

## What this project covers

- Unstructured data extraction and normalization with LLMs
- Multimodal processing for text, images, and structured metadata
- Vector indexing and similarity retrieval with metadata filtering
- Retrieval ranking and multimodal fusion
- Agent design for recommendation systems
- Multi-agent orchestration and chatbot interfaces
- MCP server/client architecture and full application integration

## Repository structure

```text
IBM-RAG-Agentic-AI/
├── Module 1/
│   ├── Lesson 1 Structure Unstructured Restaurant Data with an LLM
│   ├── Lesson 2 Process Multimodal Data with LLMs
│   └── Lesson 3 Build a Command-Line Data Management UI for Restaurant Data
├── Module 2/
│   ├── Lesson 1 Construct a Multimodal Vector Index
│   ├── Lesson 2 Similarity Retrieval with Metadata Filtering
│   └── Lesson 3 Multimodal Similarity Fusion and Retrieval Ranking
├── Module 3/
│   ├── Lesson 1 Design Specialized Agents for a Recommendation System
│   ├── Lesson 2 Implement and Test a Multi-Agent Recommendation System
│   └── Lesson 3 Build a Chatbot Interface for the Recommendation System
├── Module 4/
│   ├── Lesson 1 Build an MCP Server
│   ├── Lesson 2 Build an MCP Client
│   └── Lesson 3 Build a Full MCP Application
├── .gitattributes
├── README.md
└── LICENSE (if present in your fork)
```

## Module overview

### Module 1: Data preparation and multimodal understanding
Focuses on turning messy restaurant and business data into structured, usable context for AI-powered systems.

- Cleaning and organizing unstructured data using LLMs
- Working with multimodal content
- Building simple command-line data tooling for managing datasets

### Module 2: RAG foundation and retrieval
Builds the retrieval layer that powers grounded AI applications.

- Constructing multimodal vector indexes
- Semantic search with metadata filters
- Similarity fusion and ranking strategies

### Module 3: Agentic AI and recommendation systems
Introduces multi-agent patterns for intelligent recommendation workflows.

- Specialized agents for different decision roles
- Multi-agent orchestration and evaluation
- Chat-based user interfaces for recommendations

### Module 4: MCP and application integration
Expands from single workflows to connected, tool-using systems.

- Building MCP servers
- Creating MCP clients
- Integrating full end-to-end AI applications

## Recommended workflow

1. Start with Module 1 to understand the dataset and preprocessing pipeline.
2. Move to Module 2 to build retrieval and indexing capabilities.
3. Continue to Module 3 to design agent-based reasoning and recommendation logic.
4. Finish with Module 4 to implement connected MCP-based application patterns.

## Prerequisites

Before running the notebooks, make sure you have:

- Python 3.10+ recommended
- Jupyter Notebook or JupyterLab
- A Python environment manager such as venv or conda
- Access to IBM AI services or compatible model endpoints used by the notebooks
- Relevant API keys, credentials, and environment variables for the project configuration

## Getting started

```bash
git clone https://github.com/godspeedmc/IBM-RAG-Agentic-AI.git
cd IBM-RAG-Agentic-AI
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install -U pip
pip install jupyter notebook
```

Then open the notebooks inside each module and follow the lesson flow in order.

## Notes

This repository is primarily notebook-based, so the best way to explore it is by opening each lesson in Jupyter and running cells sequentially.

If you are using this project for learning or experimentation, consider creating a separate environment for each module or a single environment with all required dependencies installed.

## License

Check whether a LICENSE file is present in the repository before using the code in a production or public setting.

## Contributing

Contributions, bug fixes, and improvements are welcome. If you want to extend the project, consider adding:

- setup and dependency files
- reusable utility modules
- project-level documentation for each lesson
- environment configuration templates

