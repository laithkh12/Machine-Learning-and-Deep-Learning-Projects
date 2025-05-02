# 🎬 Movie Recommender System using Collaborative Filtering

## 📌 Project Overview

This project demonstrates a **movie recommender system** built using **collaborative filtering** techniques. These systems aim to enhance user experience by suggesting movies based on user preferences and behavior patterns. The system learns from historical interactions to recommend relevant content.

---

## 🧠 Techniques Used

### 1. **User-Based Collaborative Filtering**
- Finds similar users based on movie ratings
- Recommends movies liked by similar users that the current user hasn't seen

### 2. **Item-Based Collaborative Filtering**
- Calculates similarity between movies instead of users
- Recommends movies that are similar to those the user liked in the past
- More scalable as items (e.g., movies) are more stable and fewer than users

---

## 📁 Dataset

The project uses a movie rating dataset structured as:
- `User ID`
- `Movie Title`
- `Rating`

A pivot table is created for the collaborative filtering matrix (users × movies), and cosine similarity is used to find nearest neighbors.

---

## 🛠️ Tools & Libraries

- Python 3.x
- Jupyter Notebook
- Pandas / NumPy
- scikit-learn
- Seaborn / Matplotlib

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/movie-recommender.git
cd movie-recommender
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch the notebook:
```bash
jupyter notebook "Movie Recommender System.ipynb"
```

4. Run all cells to explore the recommendation engine in action.

---

## 📈 Evaluation

The model is assessed based on:
- Similarity metrics (e.g., cosine similarity)
- Precision of recommendations
- Manual testing with sample user inputs

---

## 📚 Further Reading

- [Collaborative Filtering on scikit-learn](https://scikit-learn.org/stable/modules/neighbors.html)
- [Understanding Recommender Systems](https://en.wikipedia.org/wiki/Recommender_system)

---

## 📝 License

This project is licensed under the MIT License.
