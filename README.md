# 🎬 Movie Recommendation System

A simple and interactive movie recommendation system built using **Streamlit** and **Python**. This app suggests 5 similar movies based on the selected movie using a content-based filtering approach.

## 🚀 Features

- Select a movie from a dropdown list
- Get top 5 similar movies recommended
- Interactive UI built with Streamlit

## 🧠 How It Works

This project uses a content-based filtering method. It calculates the similarity between movies based on their content (like genres, keywords, etc.) using a precomputed similarity matrix.

### Tech Stack:
- Python
- Streamlit
- Pickle (for loading models)
- Pandas

## 📁 Project Structure


- `app.py` – Main Streamlit application
- `movie_list.pkl` – Pickle file containing movie titles and IDs
- `similarity.pkl` – Pickle file containing similarity matrix

## 🛠️ How to Run Locally

1. Clone the repository:

2. Make sure you have the necessary dependencies installed:

3. Run the app:


## 📌 Note

- Make sure the `model/` folder contains `movie_list.pkl` and `similarity.pkl` before running the app.
- This is a basic implementation meant for learning and demonstration purposes.

## 📬 Contact

For any queries or feedback, feel free to reach out to me!

---

Made with ❤️ using Streamlit.



