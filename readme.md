# DocuSense

Semantic Search Engine Berbasis Transformer untuk Optimasi Pencarian Literatur Akademik.

## Team PJK-GM070

| Nama | Role |
|--------|--------|
| Muhammad Mishbahul Muflihin | Machine Learning Engineer |
| Jauhan Ahmad | Data Engineer |
| Nero Caesar Suprobo | Project Manager & QA |
| Raffa Arvel Nafi'Nadindra | Cloud & Database Engineer |
| Muhammad Rafi Aditya | Frontend Engineer |

## Project Overview

DocuSense adalah sistem semantic search berbasis Transformer yang memungkinkan pencarian paper akademik berdasarkan makna semantik, bukan hanya pencocokan keyword.

## Features

- BGE Base v1.5 Embedding
- FAISS Vector Search
- Cross Encoder Reranking
- Semantic Retrieval
- Evaluation Metrics

## Dataset

Dataset yang digunakan pada proyek ini adalah Cornell University arXiv Dataset yang tersedia di Kaggle.

Dataset Link:
https://www.kaggle.com/datasets/Cornell-University/arxiv

### Selected Categories

Untuk kebutuhan semantic search literatur AI, dataset difilter pada kategori:

- cs.AI (Artificial Intelligence)
- cs.LG (Machine Learning)
- cs.CL (Computation and Language)
- cs.CV (Computer Vision)

## Evaluation Metrics

- Precision@10
- Recall@10
- MRR
- NDCG@10
- Latency

## Repository Structure

```text
docs/
notebooks/
data/
assets/
src/
```

## Notebook

Kaggle Notebook:
https://www.kaggle.com/code/nerocaesarsuprobo/semantic/notebook?scriptVersionId=327507737

## Authors

PJK-GM070 Team