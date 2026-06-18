# DocuSense

Semantic Search Engine Berbasis Transformer untuk Optimasi Pencarian Literatur Akademik.

## Team PJK-GM070

| Nama                        | Role                      |
| --------------------------- | ------------------------- |
| Muhammad Mishbahul Muflihin | Machine Learning Engineer |
| Jauhan Ahmad                | Data Engineer             |
| Nero Caesar Suprobo         | Project Manager & QA      |
| Raffa Arvel Nafi'Nadindra   | Cloud & Database Engineer |
| Muhammad Rafi Aditya        | Frontend Engineer         |

---

## Project Overview

DocuSense adalah platform Semantic Search yang dirancang untuk membantu mahasiswa, peneliti, dan akademisi menemukan literatur ilmiah secara lebih relevan berdasarkan makna semantik, bukan hanya pencocokan kata kunci.

Sistem memanfaatkan Transformer Embedding Model (BGE Base v1.5), Vector Retrieval menggunakan FAISS, serta Cross Encoder Reranking untuk meningkatkan kualitas hasil pencarian dokumen akademik.

---

## Key Features

* Semantic Search for Academic Literature
* Transformer-based Embedding (BGE Base v1.5)
* Vector Similarity Search with FAISS
* Cross Encoder Reranking
* Academic Paper Discovery
* Evaluation using Information Retrieval Metrics

---

## Dataset

Dataset yang digunakan berasal dari Cornell University arXiv Dataset.

Kategori yang digunakan:

* cs.AI (Artificial Intelligence)
* cs.LG (Machine Learning)
* stat.ML (Machine Learning Statistics)
* cs.CL (Computation and Language)
* cs.IR (Information Retrieval)
* cs.CV (Computer Vision)
* cs.NE (Neural and Evolutionary Computing)

---

## Architecture

arXiv Dataset

↓

Preprocessing

↓

BGE Base v1.5 Embedding

↓

FAISS Vector Index

↓

Top-K Retrieval

↓

Cross Encoder Reranking

↓

Final Search Results

---

## Evaluation Metrics

* Precision@10
* Recall@10
* Mean Reciprocal Rank (MRR)
* NDCG@10
* Search Latency

---

## Technologies

* Python
* Sentence Transformers
* HuggingFace Transformers
* FAISS
* Pandas
* NumPy
* Scikit-Learn
* PyTorch

---

## Authors

Capstone Project Team PJK-GM070

