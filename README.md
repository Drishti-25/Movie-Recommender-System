# 🎬 Movie Recommender System

A Machine Learning based recommendation system that suggests similar movies using **Content-Based Filtering**, **Natural Language Processing (NLP)**, and **Cosine Similarity** techniques.

This project focuses on understanding how recommendation engines work internally by transforming movie metadata into vector representations and identifying semantic similarities between movies.

---
Check out: https://movie-recommender-system-3ogyozisgcqjr2tq286zcw.streamlit.app/

# 🧠 Machine Learning Concepts Used

- Content-Based Recommendation Systems
- Natural Language Processing (NLP)
- Feature Engineering
- Text Vectorization
- Similarity Learning
- Cosine Similarity
- Data Cleaning & Preprocessing

---

# ⚙️ ML Workflow

## 1. Data Preprocessing

- Cleaned movie metadata
- Handled missing/null values
- Selected important features for recommendation
- Transformed raw data into structured format

---

## 2. Feature Engineering

Multiple textual features were combined into a single representation to create richer semantic context for each movie.

This improves the recommendation quality by capturing:
- movie themes
- genre relationships
- cast similarity
- storyline patterns

---

## 3. Text Vectorization

Used **CountVectorizer** from Scikit-learn to convert textual metadata into numerical vectors.

The vectorized representation allows the ML model to mathematically compare movies in high-dimensional feature space.

---

## 4. Similarity Computation

Cosine similarity was used to measure similarity between movie vectors.

\[
Similarity(A,B)=\frac{A \cdot B}{||A|| ||B||}
\]

Movies with higher cosine similarity scores are recommended as similar movies.

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Fast-API

---

# 📊 What I Learned

- Building recommendation systems from scratch
- Applying NLP techniques in ML projects
- Working with vector space models
- Feature engineering for recommendation systems
- Similarity matrix computation
- Data preprocessing pipelines
- Practical implementation of content-based filtering

---

