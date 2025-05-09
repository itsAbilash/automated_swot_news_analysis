![SWOT-AI](https://img.shields.io/badge/project-SWOT--AI-blueviolet)
![Python](https://img.shields.io/badge/python-3.10-blue)
![Status](https://img.shields.io/badge/status-Completed-brightgreen)

# Automated SWOT Analysis from Business News

This project leverages **Natural Language Processing (NLP)** and **semantic similarity** to automatically categorize business news articles into SWOT categories — **Strengths, Weaknesses, Opportunities, and Threats** — and generate contextual summaries using a simple web interface.

Developed as part of *IDS 572 – Deep Learning & Modern Applications* at the University of Illinois Chicago.
Dataset coverage: 2013 to early 2018 | Source: *All the News 1.0*
---

## Key Features

- Clean and preprocess large-scale business news data
- Generate semantic embeddings using `SentenceTransformer`
- Classify content into SWOT buckets using cosine similarity
- Generate keyword-driven, category-wise summaries
- Interactive Flask web app for querying insights
- EDA visualizations to explore publication trends and content themes

---

## Project Objectives

In an era of information overload, this project sets out to transform business news into strategic intelligence. Here's what we set out to do:
 - Turn unstructured news into structure, by building a fully automated pipeline that reads, cleans, and prepares raw news articles for analysis.
 - Make machines think like strategists by using transformer-based NLP models to understand language and group insights into SWOT quadrants: Strengths, Weaknesses, Opportunities, and Threats.
 - Match meaning, not just words, by computing semantic similarity between articles and curated keyword profiles, sentence by sentence.
 - Cut through the noise with summarization logic that distills large volumes of text into sharp, category-wise takeaways.
 - Bring it to life on the web via a Flask-powered interface that lets users explore, filter, and extract insight in real-time.
 - Visualize the unseen through exploratory data analysis that surfaces trends in content, category distribution, and publishing patterns.

## Tech Stack

| Category | Tools & Libraries |
|---------|-------------------|
| **Language** | Python 3.10 |
| **NLP Models** | `sentence-transformers`, `spaCy`, `nltk`, `regex`, `scikit-learn` |
| **Data Processing** | `pandas`, `dask`, `tqdm`, `sqlite3` |
| **Computation** | `PyTorch` (with GPU acceleration) |
| **Visualization** | `matplotlib`, `seaborn`, `wordcloud` |
| **Web App** | `Flask`, `Jinja2`, `HTML`, `Bootstrap` |




## 📂 Project Structure

```bash
.
├── code/                     # Core source code (.py and .ipynb)
│   ├── AllNewsData.py/ipynb       # Extract + clean data from SQLite
│   ├── EDA_Analysis.py/ipynb      # Visualizations and trends
│   ├── Embeddings_optimized.pynb    # Main SWOT categorization logic
│   ├── Summarize.pynb               # Keyword-based summarizer
│   └── app.pynb                    # Flask web app interface
├── output/
│   ├── output2.pdf
├── report/
│   └── Deep_Learning_report_Final.pdf
├── requirements.txt
└── README.md
