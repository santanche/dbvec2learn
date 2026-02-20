# dbvec2learn
Vector Database to Learn

# Medical Vector Database with DuckDB

This repository demonstrates:

- Normalized relational schema
- Disease ↔ Symptom modeling
- Vector embeddings using SentenceTransformers
- Similarity search
- Hybrid SQL + vector queries

## Run with Docker

```bash
docker build -t medical-db .
docker run -p 8888:8888 -v $(pwd):/app medical-db

## Run with Binder
[dbvec2learn on Binder](https://mybinder.org/v2/gh/santanche/dbvec2learn/main)