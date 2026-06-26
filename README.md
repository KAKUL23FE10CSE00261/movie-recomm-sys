# 🎬 Movie Recommendation System

An AI-powered **Movie Recommendation System** built using **Python**, **Streamlit**, **FastAPI**, **Scikit-learn**, and the **TMDB API**.

The application recommends similar movies using **Content-Based Filtering (TF-IDF + Cosine Similarity)** while fetching real-time movie information such as posters, ratings, genres, release dates, and descriptions from TMDB.

---

## 🚀 Live Demo

**🌐 Streamlit App**

https://movie-recomm-sys-kgyzrv6qvq96bp8pqmbxul.streamlit.app/?view=home

---

## ✨ Features

* 🎬 Browse Trending, Popular, Top Rated, Upcoming and Now Playing movies
* 🔍 Smart movie search with autocomplete suggestions
* 🤖 Content-based movie recommendations using TF-IDF and Cosine Similarity
* 🎭 Genre-based recommendations
* ⭐ Movie ratings
* 📅 Release dates
* 🖼️ High-quality movie posters
* 📖 Detailed movie overview
* ⚡ Responsive Streamlit interface
* 🌐 TMDB API integration

---

## 🛠️ Tech Stack

### Frontend

* Streamlit

### Backend

* FastAPI
* Uvicorn

### Machine Learning

* Scikit-learn
* TF-IDF Vectorizer
* Cosine Similarity

### Libraries

* Pandas
* NumPy
* SciPy
* Requests

### API

* TMDB API

---

## 📂 Project Structure

```
movie-recomm-sys/
│
├── app.py
├── main.py
├── movies.ipynb
│
├── df.pkl
├── tfidf.pkl
├── tfidf_matrix.pkl
├── indices.pkl
│
├── requirements.txt
├── .env
├── README.md
└── LICENSE
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/<YOUR_GITHUB_USERNAME>/movie-recomm-sys.git
cd movie-recomm-sys
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Virtual Environment

**Windows**

```bash
.venv\Scripts\activate
```

**Linux/macOS**

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file.

```env
TMDB_API_KEY=YOUR_TMDB_API_KEY
```

Get your free API key from:

https://www.themoviedb.org/settings/api

---

## ▶️ Run the Backend

```bash
uvicorn main:app --reload
```

FastAPI Docs:

```
http://127.0.0.1:8000/docs
```

---

## ▶️ Run the Frontend

```bash
streamlit run app.py
```

---

## 🧠 Recommendation Pipeline

1. Data preprocessing
2. Text cleaning
3. TF-IDF Vectorization
4. Cosine Similarity computation
5. Content-based recommendations
6. TMDB API integration
7. Genre-based recommendations

---

## 📊 Dataset

TMDB Movies Metadata Dataset

Dataset includes:

* Movie Titles
* Genres
* Overview
* Ratings
* Vote Count
* Release Date
* Tagline

---

## 📸 Screenshots

### 🏠 Home Page

<img width="960" height="504" alt="image" src="https://github.com/user-attachments/assets/fe4ad167-7a42-4b09-bb36-2b48c463677f" />

### 🔍 Search Results

<img width="960" height="504" alt="image" src="https://github.com/user-attachments/assets/33dc84bf-3e13-4a26-8c88-53f3a78fc5ab" />

<img width="960" height="504" alt="image" src="https://github.com/user-attachments/assets/b32f148f-c890-454b-ba15-eaa881beb591" />

### 🎬 Movie Details

<img width="960" height="504" alt="image" src="https://github.com/user-attachments/assets/0d2a46fa-d636-46a3-ba68-5c03153be2ee" />

### 🤖 Recommendations

<img width="960" height="504" alt="image" src="https://github.com/user-attachments/assets/f5b30fd4-444f-4fbc-b0c2-9fbe73f5e61b" />

---

## 🚀 Future Improvements

* User authentication
* User watchlist
* Favorite movies
* Hybrid recommendation system
* Collaborative filtering
* Personalized recommendations
* Movie trailers
* User reviews

---

## 👩‍💻 Author

**Kakul Barsaiya**

B.Tech Computer Science Engineering

Machine Learning & Data Science Enthusiast

GitHub: https://github.com/KAKUL23FE10CSE00261

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is licensed under the MIT License.
