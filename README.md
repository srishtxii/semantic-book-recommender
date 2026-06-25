## ⋆☕︎ ˖ Semantic Book Recommender

A book recommendation system that uses:

- Hugging Face Embeddings
- Chroma Vector Database
- Semantic Search
- Emotion-Based Filtering
- Gradio Dashboard

## About

This project recommends books based on semantic similarity rather than keyword matching. User queries are converted into embeddings using Hugging Face models and searched against a Chroma vector database. Recommendations can be further filtered by category and emotional tone.
## Features

- Search books using natural language
- Filter by category
- Filter by emotional tone
- View book covers and descriptions

## Tech Stack

- Python
- Pandas
- LangChain
- ChromaDB
- Hugging Face
- Gradio

## Run Locally

```bash
pip install -r requirements.txt
python gradio-dashboard.py
```

## Project Structure

```text
├── gradio-dashboard.py
├── books_with_emotions.csv
├── tagged_description.txt
├── requirements.txt
├── README.md
└── .gitignore
```