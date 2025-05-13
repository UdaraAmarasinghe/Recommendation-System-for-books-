# 📚 Book Recommendation System

A **Book Recommendation System** built using Python, Flask, and MongoDB, designed to provide personalized book suggestions using **Content-Based Filtering**, **Collaborative Filtering**, and **Hybrid Approaches**.

This project demonstrates how modern recommendation techniques can enhance the reading experience by analyzing user preferences, past behaviors, and book features to deliver highly relevant suggestions.

## 🚀 Features

- ✅ Personalized recommendations using:
  - Content-Based Filtering
  - Collaborative Filtering
  - Hybrid Methods
- ✅ RESTful API endpoints for integration and scalability
- ✅ MongoDB used for storing user profiles, ratings, and book metadata
- ✅ Clean and interactive frontend via Flask templates or API integration
- ✅ Visualization and logic walkthrough in Jupyter Notebook (`.ipynb`)

## 🛠️ Tech Stack

| Component        | Technology          |
|------------------|---------------------|
| Language         | Python              |
| Backend          | Flask (RESTful API) |
| Database         | MongoDB             |
| Algorithms       | Scikit-learn, Pandas, Numpy |
| Data Viz         | Matplotlib, Seaborn |
| Development      | Jupyter Notebook    |

## 📂 Project Structure

📁 Recommendation-System-for-books/
├── book\_recommender.ipynb       # Main notebook with logic, training, and results
├── app.py                       # Flask backend for API or web frontend
├── requirements.txt             # Python dependencies
├── static/                      # Optional: CSS or images
├── templates/                   # Optional: HTML pages for Flask
└── README.md                    # This file

## 📊 How It Works

### 📌 Content-Based Filtering
Recommends books similar to those the user has liked, based on:
- Book title
- Author
- Genre
- Description features (TF-IDF or cosine similarity)

### 👥 Collaborative Filtering
Recommends books based on user behavior:
- Matrix factorization using rating patterns
- Similar users’ preferences

### 🔁 Hybrid Approach
Combines both methods to improve recommendation diversity and accuracy.

## 💻 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/Recommendation-System-for-books.git
cd Recommendation-System-for-books
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

If you're running from Jupyter Notebook, make sure you have:

* `pandas`
* `numpy`
* `scikit-learn`
* `flask`
* `pymongo`
* `seaborn`, `matplotlib`

### 3. Run Flask App

```bash
python app.py
```

Go to `http://localhost:5000` to see the app running.

## 📘 Dataset

The project uses a curated dataset of books with:

* Titles, genres, authors, and descriptions
* User ratings matrix


