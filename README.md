# 🧠 RAG Workshop

A hands-on workshop demonstrating how to build a Retrieval-Augmented Generation (RAG) system using Elasticsearch, OpenAI, and Gradio. You’ll learn how to embed documents, search semantically, and generate grounded responses using a modern AI pipeline.

---

## 🚀 Features

- Document ingestion
- Embedding with Elastic's E5 model via inference pipeline
- Response generation using OpenAI's GPT API
- Interactive Gradio UI for conversational querying

---

## 🧱 Project Structure

```
RAG_Workshop/
├── Slides/                  # Final slide deck in PDF format
│   └── RAG_Workshop_Slides.pdf
├── app/                     # Source code for ingestion, embedding, and UI
├── elastic-start-local/     # Elasticsearch Docker configuration
├── pdfs/                    # Sample PDFs for document ingestion
├── .env.example             # Example environment variable template
├── requirements.txt         # Python dependencies
└── README.md                # This file
```

---

## 🛠️ Setup Instructions

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/) and Docker Compose
- Python 3.10 or newer
- An OpenAI API key

---

### 1. Clone the Repository

```bash
git clone https://github.com/justincastilla/RAG_Workshop.git
cd RAG_Workshop
```

### 2. Configure Environment Variables
```bash
cp .env.example .env
```
Edit `.env` to include your OpenAI API key and Elasticsearch credentials

### 3. Set Up Python Environment (Optional but Recommended)
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 4. Head to [00-Iinstallation](./00-Installation.md) to continue the installation

## 📘 Workshop Slides

The complete slide deck for this workshop is available as a PDF:

    Slides/RAG_Workshop_Slides.pdf

You can view it in GitHub or download it directly.

## 🤝 Contributing

Contributions are welcome! To suggest changes or add improvements:

    Fork the repository

    Create a feature branch

    Submit a pull request with clear context and reasoning

## 📄 License

Apache License 2.0 © 2024–2025 Justin Castilla