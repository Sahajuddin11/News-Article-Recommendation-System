# 📰 Hybrid News Recommendation System (Flask)

A Flask-based web application that recommends news articles using a **Hybrid Recommendation System** combining:

- 🧠 Content-Based Filtering (TF-IDF + Cosine Similarity)
- 👥 Collaborative Filtering (User-Item Similarity)
- 🔀 Hybrid Recommendation Strategy

The system suggests personalized news articles based on both:
- User reading behavior
- Similarity between news titles/content

---

## 📌 Project Overview

This project implements a Hybrid News Recommendation System using:

- TF-IDF Vectorization for text similarity
- Cosine Similarity for content-based filtering
- User-Item Interaction Matrix for collaborative filtering
- Label Encoding for user and news indexing
- Flask for web deployment

The hybrid approach improves recommendation quality by combining both content similarity and user interaction patterns.

---

## 🚀 Features

- Content-Based Recommendation (Title similarity)
- Collaborative Filtering (User similarity)
- Hybrid recommendation combining both methods
- Clean Flask web interface
- Returns:
  - News Title
  - Category
  - Subcategory
  - URL
  - Abstract

---

## 🛠️ Technologies Used

- Python 3.8+
- Flask
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- LabelEncoder
- HTML (Jinja2 Templates)
