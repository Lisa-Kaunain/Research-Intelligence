# Semantic Research Paper Intelligence System

## Project Overview
This project implements an intelligent search system for Machine Learning research papers. Unlike traditional keyword search, it retrieves papers based on semantic similarity using transformer-generated embeddings and a FAISS vector index, then automatically summarizes each result, extracts its key topics, and classifies important technical terms.

## Problem Statement
Finding relevant research papers using keyword search often misses semantically related work, and reading full abstracts to judge relevance is slow. This project addresses both problems by representing papers and queries as dense embeddings for semantic retrieval, and by automatically condensing and annotating each result.

## Features

* Exploratory Data Analysis (EDA)
* Data preprocessing
* Semantic embeddings using all-MiniLM-L6-v2
* FAISS vector indexing
* Natural language search
* Top-k relevant paper retrieval
* Automatic summarization using BART
* Keyword/keyphrase extraction using KeyBERT
* Named Entity Classification (NER) — tags technical terms such as models, frameworks, languages, and algorithms found in the query and results

## Tech Stack
Python, Pandas, NumPy, Hugging Face Datasets, Sentence Transformers, FAISS, Transformers (BART), KeyBERT, spaCy, Jupyter Notebook

## Repository Structure

```
notebooks/
    NLP_Project_Final.ipynb
README.md
requirements.txt
```

## Installation

```
pip install -r requirements.txt
```

## How to Run

1. Open NLP_Project_Final.ipynb (recommended: Google Colab with GPU runtime)
2. Run all cells in order
3. Call search_paper_full("your query") to get search results with summaries, keywords, and entity classifications

## Future Improvements

* Streamlit Web App
* Filters by author/year
* PDF upload
* Expand entity gazetteer to cover more technical terms

## Author
Lisa Kaunain P
