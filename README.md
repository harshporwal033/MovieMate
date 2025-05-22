
# 🎬 Intelligent Movie Recommender System

A personalized movie recommendation engine powered by collaborative filtering using **SVD** (via `surprise` library) and a lightweight Flask frontend. Built as a hands-on AI project to learn real-world recommender system implementation.

## 📦 Features

- 📊 Collaborative filtering with matrix factorization (SVD)
- 🎯 Predicts top-N movies per user with scores
- 🧠 Smart fallback for user-movie mapping
- 🌐 Flask-based web interface
- 🧪 Clean modular code for learning and customization

## 🛠️ Tech Stack

- Python 3.11
- Flask
- scikit-surprise
- pandas / NumPy / Matplotlib
- HTML / CSS (Jinja templates)

## 📁 Project Structure

```

movie-recommender-python/
├── data/                   # ratings.csv, movies.csv
├── notebooks/              # EDA and preprocessing notebooks
├── src/                    # Modular Python scripts
├── web/                    # Flask app + templates
│   ├── app.py
│   └── templates/
├── requirements.txt
└── README.md

````

## 🧪 Sample User IDs

Try the following user IDs to explore recommendations:

- `1`
- `10`
- `20`
- `50`
- `75`

## ⚙️ How to Run

### 1. Install dependencies

```bash
pip install -r requirements.txt
````

### 2. Start the Flask app

```bash
cd web
python app.py
```

Then open your browser at [http://127.0.0.1:5000](http://127.0.0.1:5000)

## 🧪 Try the API

```bash
curl http://127.0.0.1:5000/api/recommend?userId=1
```

## 📚 Dataset Source

MovieLens 100K
[https://grouplens.org/datasets/movielens/100k](https://grouplens.org/datasets/movielens/100k)

---

> 🔧 Built by **Harsh Porwal** for educational purposes.

```

---

Let me know if you'd like to convert it into a `.md` file directly or need help pushing it to your GitHub repo.
```
