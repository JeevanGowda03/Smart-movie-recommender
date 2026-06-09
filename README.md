# 🎬 Smart Movie Recommendation System

A content-based movie recommendation engine that suggests the top 10 most similar 

films using **TF-IDF Vectorization** and **Cosine Similarity**. Built with Python, 

Scikit-learn, and Streamlit.

## ⚡ Features

- **1,000 curated movies** (2006-2016) with rich metadata

- **Content-based filtering** using genre, plot, director, and cast

- **TF-IDF + Cosine Similarity** for semantic matching

- **Cold-start safe** — no user history required

- **Live web app** deployed on Streamlit Cloud

- **Sub-second recommendations** with pre-computed similarity matrix

## 🛠️ Tech Stack

- **Python 3.10+** | **Scikit-learn** | **Pandas** | **NumPy**

- **Streamlit** (web UI) | **Pickle** (model serialization)

## 📊 How It Works

1. Concatenate movie features (genre + description + director + actors)

2. Transform into 5,000-dimensional TF-IDF vectors

3. Compute 1,000×1,000 cosine similarity matrix

4. Serve recommendations via interactive Streamlit interface

## 📦 Installation process

```bash

pip install -r requirements.txt

python model.py      # Train model & generate pickles

streamlit run app.py # Launch web app

```

## 🎯 Use Cases

Perfect for streaming platforms, film discovery tools, and personalized content curation 

without dependency on user behavioral data.

---
