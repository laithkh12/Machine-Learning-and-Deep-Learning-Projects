# 🌟 Yelp Reviews Classification using Naive Bayes & NLP

## 📌 Project Overview

This project applies **Natural Language Processing (NLP)** and **Naive Bayes Classification** to analyze **Yelp customer reviews**. The goal is to classify whether a review is **positive** or **negative** based on its textual content. The dataset includes user ratings and the number of 'Cool', 'Useful', and 'Funny' votes provided by the Yelp community.

---

## 🗂️ Dataset Summary

- Each review includes:
  - `text`: the actual review content
  - `stars`: rating from 1 to 5
  - `cool`, `useful`, `funny`: number of votes received for each tag

- Labeling:
  - For binary classification, star ratings can be grouped (e.g., 1–2 as negative, 4–5 as positive)

---

## 🤖 Techniques Used

### NLP Techniques:
- Tokenization with **NLTK**
- Text preprocessing: lowercase conversion, punctuation removal, etc.
- Feature extraction using `CountVectorizer`

### Classification:
- **Naive Bayes Classifier** (`MultinomialNB`)
- Evaluation with metrics like accuracy, precision, recall, F1-score

---

## 🛠️ Tools & Libraries

- Python 3.x
- Jupyter Notebook
- Pandas / NumPy
- scikit-learn
- NLTK
- Matplotlib / Seaborn

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/yelp-reviews-classifier.git
cd yelp-reviews-classifier
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch the notebook:
```bash
jupyter notebook "Project 7 - Yelp Reviews Classification.ipynb"
```

4. Follow the cells to clean data, extract features, train and evaluate the model.

---

## 📈 Evaluation Metrics

- Confusion Matrix
- Accuracy
- Precision / Recall / F1 Score
- Classification Report

---

## 📚 Further Reading

- [NLTK Documentation](https://www.nltk.org/)
- [Scikit-learn Naive Bayes](https://scikit-learn.org/stable/modules/naive_bayes.html)
- [CountVectorizer Docs](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html)

---

## 📝 License

This project is licensed under the MIT License.
