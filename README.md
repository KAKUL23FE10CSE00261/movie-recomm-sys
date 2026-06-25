# 🎬 Movie Recommendation System

A modern AI-powered Movie Recommendation System built using **Machine Learning (TF-IDF + Cosine Similarity)**, **FastAPI**, **Streamlit**, and the **TMDB API**.

The application recommends similar movies based on movie content and enriches recommendations with real-time movie information, posters, ratings, genres, and release dates fetched from TMDB.

---

## 🚀 Features

- 🎥 Search movies by title
- 🤖 Content-based movie recommendation
- 📚 TF-IDF Vectorizer + Cosine Similarity
- 🖼️ Movie posters from TMDB
- ⭐ Movie ratings
- 🎭 Genres
- 📅 Release dates
- 📖 Movie overview/details
- ⚡ FastAPI backend
- 🎨 Streamlit frontend
- 🔍 Autocomplete search
- 📦 Pre-trained recommendation model using Pickle

---

## 🛠️ Tech Stack

### Frontend
- Streamlit

### Backend
- FastAPI
- Uvicorn

### Machine Learning
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity

### Data Processing
- Pandas
- NumPy
- SciPy

### External API
- TMDB (The Movie Database)

---

## 📂 Project Structure

```
movie-recomm-sys/
│
├── app.py                 # Streamlit Frontend
├── main.py                # FastAPI Backend
├── movies.ipynb           # Model Training Notebook
├── movies_metadata.csv    # Movie Dataset
│
├── df.pkl
├── tfidf.pkl
├── tfidf_matrix.pkl
├── indices.pkl
│
├── requirements.txt
├── .env
├── LICENSE
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/movie-recomm-sys.git

cd movie-recomm-sys
```

---

### 2. Create Virtual Environment

```bash
python -m venv .venv
```

Activate it

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux / macOS

```bash
source .venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 TMDB API Key

Create a `.env` file in the project root.

```env
TMDB_API_KEY=YOUR_API_KEY
```

Get your free API key from:

https://www.themoviedb.org/settings/api

---

## ▶️ Running the Backend

```bash
uvicorn main:app --reload
```

Backend URL

```
http://127.0.0.1:8000
```

Swagger Documentation

```
http://127.0.0.1:8000/docs
```

---

## ▶️ Running the Frontend

```bash
streamlit run app.py
```

---

## 🧠 Machine Learning Pipeline

1. Movie metadata preprocessing
2. Feature engineering
3. Text cleaning
4. TF-IDF Vectorization
5. Cosine Similarity
6. Similar movie retrieval
7. TMDB API integration for posters and movie details

---

## 📊 Dataset

Dataset used:

**TMDB Movies Metadata Dataset**

Contains:

- Movie Title
- Overview
- Genres
- Ratings
- Vote Count
- Tagline
- Release Date

---

## 📸 Screenshots

### Home Page

_Add screenshot here_

### Movie Details

_Add screenshot here_

### Recommendations

_Add screenshot here_

---

## 🔮 Future Improvements

- Hybrid Recommendation System
- User Authentication
- User Watchlist
- Collaborative Filtering
- Deep Learning Recommendation Model
- Sentiment-based Recommendations
- Movie Trailer Integration

---

## 👨‍💻 Author

**Kakul Barsaiya**

B.Tech CSE | Machine Learning & Data Science Enthusiast

GitHub:
https://github.com/<your-username>

LinkedIn:
_Add your LinkedIn profile_

---

## ⭐ Support

If you like this project, please consider giving it a ⭐ on GitHub.

---

## 📜 License

This project is licensed under the MIT License.
