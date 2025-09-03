# 🎬 Movie Recommender Web App

A **smart and interactive web app** that recommends movies based on content similarity. Built using **Python** and **Streamlit**, it uses a pre-trained model to suggest movies similar to your choice.

---

## 🚀 Live Demo

Check out the app here:  
<!-- 🔗 [Insert your Streamlit app link here] -->

---

## 📌 Key Features

- Suggests **top 5 similar movies**  
- Displays **movie posters** dynamically using **TMDB API**  
- Built with **content-based filtering** and **cosine similarity**  
- Powered by the **TMDB 5000 dataset**  

**Tech Stack:**  
- Python 🐍  
- Pandas & scikit-learn 🧠  
- Streamlit 🌐  
- Pickle (for saving the trained model) 🧵  

---

## 🧠 How It Works

1. Movie data is cleaned and combined into a **single “tags” column**.  
2. Text data is converted into numeric vectors using **TF-IDF / CountVectorizer**.  
3. **Cosine similarity** is computed between all movies.  
4. When you select a movie, the app shows the **5 most similar movies**.  
5. Movie **posters are fetched in real-time** using the TMDB API.  

---

## 📊 Dataset

The app uses the **TMDB 5000 Movie Dataset** from Kaggle:  

- [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)  
- Files used:  
  - `tmdb_5000_movies.csv`  
  - `tmdb_5000_credits.csv`  

> ⚠️ **Note:** Large files like `similarity.pkl` are **not included** in the repo due to GitHub size limits. You can generate them using the notebook provided.  

---

## 🔑 TMDB API Key

A **TMDB API key** is required to fetch movie posters. Add your key in the `.env` file or directly in the script as instructed.  

---

## 🌐 Deployment

This app is built with **Streamlit** and can be deployed on **Streamlit Cloud** or any Python-supported web server.  

---

## ✍️ Author

Created with ❤️ by **Aarav**  

---

⭐ If you find this project helpful, please give it a ⭐ on GitHub! 🙌
