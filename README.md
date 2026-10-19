# YouTube Comment Analysis and Automated Reply Generation

> **An end-to-end Machine Learning and NLP pipeline for extracting, clustering, analyzing YouTube comments, and generating context-aware automated replies.**

---

## 📌 Overview
Managing community engagement on YouTube can become overwhelming as a channel grows. This project provides an automated solution that leverages Natural Language Processing (NLP) and Machine Learning to:
* Extract comments directly from YouTube videos.
* Clean text, filter out spam, and parse emojis.
* Group comments into meaningful semantic clusters using embedding techniques.
* Analyze audience sentiment, recurring questions, and key feedback topics.
* Automatically generate context-aware replies to streamline viewer engagement.

---

## 🚀 Key Features
- **YouTube Data API Integration:** Seamlessly fetches top-level comments, author details, like counts, and timestamps.
- **Robust Text Preprocessing Pipeline:** Cleans raw text, handles URLs, filters repetitive spam patterns, and extracts/normalizes emojis for sentiment preservation.
- **Semantic Sentence Embeddings:** Converts comments into dense vector spaces using models like Sentence-BERT (`all-MiniLM-L6-v2`).
- **Unsupervised Clustering:** Implements clustering algorithms (such as K-Means or DBSCAN) to categorize feedback into clear topic groups.
- **Automated Insight Generation:** Extracts top keywords and themes per cluster to highlight what your audience cares about most.
- **Automated Reply Module:** Generates smart, contextual responses to common viewer remarks or queries.

---

## 🛠️ Tech Stack & Dependencies
* **Core Libraries:** `pandas`, `numpy`
* **NLP & Machine Learning:** `scikit-learn`, `sentence-transformers`, `transformers`, `torch`, `nltk`
* **API & Utilities:** `google-api-python-client`, `emoji`, `tqdm`
* **Visualization:** `matplotlib`, `seaborn`, `wordcloud`

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/ayushgaikwad1210/YouTube-Comment-Analysis-and-Automated-Reply-Generation.git](https://github.com/ayushgaikwad1210/YouTube-Comment-Analysis-and-Automated-Reply-Generation.git)
   cd YouTube-Comment-Analysis-and-Automated-Reply-Generation
   
