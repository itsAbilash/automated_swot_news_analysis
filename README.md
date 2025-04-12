# 🧠 Automated SWOT Analysis from Business News

This project leverages **Natural Language Processing (NLP)** and **semantic similarity** to automatically categorize business news articles into SWOT categories — **Strengths, Weaknesses, Opportunities, and Threats** — and generate contextual summaries using a simple web interface.

Developed as part of *IDS 572 – Deep Learning & Modern Applications* at the University of Illinois Chicago.

---

## 🚀 Key Features

- 🧹 Clean and preprocess large-scale business news data
- 🤖 Generate semantic embeddings using `SentenceTransformer`
- 🧠 Classify content into SWOT buckets using cosine similarity
- 📝 Generate keyword-driven, category-wise summaries
- 🌐 Interactive Flask web app for querying insights
- 📊 EDA visualizations to explore publication trends and content themes

---

## 🧰 Tech Stack

- **Languages**: Python 3.8+
- **NLP**: `sentence-transformers`, `nltk`, `spacy`, `scikit-learn`
- **Data Viz**: `matplotlib`, `seaborn`, `wordcloud`
- **Web App**: `Flask`, `HTML/Jinja2`
- **Backend**: SQLite for initial dataset extraction
