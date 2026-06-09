# 🎬 Movie Recommender System

A content-based movie recommendation engine built using Python, Scikit-Learn, and Streamlit. It analyzes movie metadata (plots, genres, cast, and crew) to provide relevant suggestions.

---

## 🚀 Features
* **Content-Based Filtering:** Recommends movies based on text similarity.
* **Interactive UI:** Built with Streamlit for a seamless user experience.
* **Dynamic Posters:** Fetches real-time movie posters using the TMDB API.
* **Data-Driven:** Trained on the TMDB 5000 Movies & Credits dataset.

---

## 🛠️ Tech Stack
* **Frontend:** Streamlit
* **Data:** Pandas, NumPy
* **NLP:** NLTK (PorterStemmer)
* **ML:** Scikit-Learn (CountVectorizer, Cosine Similarity)

---

## 📂 Project Structure
```text
├── movie-recommender-system.ipynb  # Data cleaning & model training logic
├── movieapp.py                     # Streamlit web application
├── movie_dict.pkl                  # Serialized movie metadata
└── similarity.pkl                  # Serialized similarity matrix
