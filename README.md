# 🎬 Movie Recommendation System

This project is a movie recommendation system built with **Streamlit** and powered by a **machine learning model** 🤖. It recommends movies based on a selected title using cosine similarity and displays movie posters fetched from the TMDB API.

File size is larger than 25mb Therefore refer to this Dataset link:
> 📂 Dataset is [HERE](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)  
> 📦 Some large files are hosted [HERE](https://huggingface.co/sujoy0011/Movie-Recommendation-System/tree/main)


## 📌 Overview

The movie recommendation system helps users discover movies similar to their favorites 🎥. By selecting a movie, users receive a list of **top 10 recommended movies along with posters**.

✨ Key highlights:
- Uses **Machine Learning**
- Built with **Streamlit UI**
- Fetches posters via **TMDB API**
- Fast and interactive user experience

---

## 🧠 Theory of Recommendation Systems
A recommendation system is a machine learning technique used to suggest relevant items to users based on their preferences or similarity patterns. It helps reduce information overload by filtering and presenting personalized content.

There are mainly three types of recommendation systems:

- Content-Based Filtering: Recommends items similar to what the user liked based on features.
- Collaborative Filtering: Recommends items based on preferences of similar users.
- Hybrid Methods: Combines both approaches for better accuracy.

In this project, cosine similarity is used to measure similarity between movies by comparing their feature vectors. Movies with higher similarity scores are recommended to the user.

### 🔍 What is a Recommendation System?

A **Recommendation System** is a type of information filtering system that predicts what a user might like based on their preferences, behavior, or similarity with other users.

📌 Common real-world examples:
- Netflix 🍿 (movie suggestions)
- Amazon 🛒 (product recommendations)
- Spotify 🎧 (music playlists)

---

### ⚡ Why are Recommendation Systems Important?

- Improve user experience 😃  
- Save time by filtering content ⏳  
- Increase engagement and retention 📈  
- Help users discover new content 🔎  

---

### 🧩 Types of Recommendation Systems

#### 1. 📌 Content-Based Filtering
- Recommends items **similar to what the user already liked**
- Uses features like genre, cast, keywords

👉 Example:  
If you liked *Avengers*, you’ll get more **action/superhero movies**

---

#### 2. 👥 Collaborative Filtering
- Recommends based on **similar users’ preferences**
- “Users like you also liked this”

👉 Example:  
If many users who liked *Inception* also liked *Interstellar*, it will recommend it

---

#### 3. 🔀 Hybrid Systems
- Combines both approaches for better accuracy
- Used by most modern platforms

---

### 📐 Cosine Similarity (Core Concept Used)

This project uses **Cosine Similarity** to measure how similar two movies are.

🧮 Concept:
- Movies are converted into vectors based on features
- Similarity is calculated using the angle between vectors

📊 Formula (conceptually):Similarity = cos(θ)


📌 Interpretation:
- Value close to **1 → very similar**
- Value close to **0 → not similar**

---

### 🧠 Why Cosine Similarity?

- Works well with **high-dimensional data**
- Ignores magnitude, focuses on **direction (pattern)**
- Efficient for recommendation systems

---

## ⚙️ Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/movie-recommendation-system.git
    cd movie-recommendation-system
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Usage

1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Select a movie 🎬 from the dropdown list and click "Recommend" to get the top 10 recommended movies along with their posters.

## 📊 Dataset

- Contains movie titles, IDs, and metadata
- Stored in movie_data.pkl
- Used for similarity computation

## 🧮 Model
- Based on Cosine Similarity
- Converts movies into feature vectors
- Computes similarity scores
- Returns Top 10 closest matches

## 📈 Results
- Displays Top 10 recommended movies
- Shows movie posters 🎞️ using TMDB API

- 📸 Example Output:![Screenshot 2024-07-12 103743](https://github.com/user-attachments/assets/fbc357a1-a6e6-472a-892b-95fe96767743)

## 🌟 Future Improvements
- Add Collaborative Filtering
- Improve recommendation accuracy
- Deploy online 🌐
- Add user login system 👤

## 💡 Final Note

This project demonstrates how machine learning can be applied to build real-world recommendation systems efficiently 🚀