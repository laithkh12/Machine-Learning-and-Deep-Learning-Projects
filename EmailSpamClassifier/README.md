# 📧 Spam Classifier using Naive Bayes

## 📌 Project Overview

This project implements a **spam email classifier** using the **Naive Bayes algorithm**, a fundamental approach in Natural Language Processing (NLP). The model is trained on the **SMS Spam Collection Dataset**, which includes thousands of SMS messages labeled as **spam** or **ham** (legitimate).

---

## 🗂️ Dataset Summary

- **Total messages**: 5,574
- **Labels**: 
  - `ham`: non-spam (legitimate)
  - `spam`: unsolicited message
- **Columns**:
  - `v1`: label (`ham` or `spam`)
  - `v2`: message content (raw text)
- 📦 **Source**: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---

## 🤖 Model: Naive Bayes Classifier

The Naive Bayes model uses Bayes' Theorem with the assumption that input features (words in the message) are **conditionally independent**.

### Key Concepts:
- **Prior Probability**: How likely a label (spam or ham) is overall
- **Likelihood**: How likely a word appears in a label
- **Posterior Probability**: Final probability combining both, used for classification

We use:
- `CountVectorizer` for converting text to numerical form
- `MultinomialNB` for classification

---

## 🛠️ Tools & Libraries

- Python 3.x
- Jupyter Notebook
- Pandas / NumPy
- scikit-learn
- NLTK (for optional text preprocessing)
- Matplotlib / Seaborn

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/spam-classifier.git
cd spam-classifier
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch the notebook:
```bash
jupyter notebook EmailSpamFilter.ipynb
```

4. Run all cells to train and evaluate the classifier.

---

## 📈 Evaluation Metrics

- **Confusion Matrix**
- **Accuracy**
- **Precision / Recall / F1 Score**
- **Classification Report**

These metrics help assess how well the classifier distinguishes spam from ham messages.

---

## 📚 Further Reading

- [Understanding Naive Bayes](https://scikit-learn.org/stable/modules/naive_bayes.html)
- [NLP Basics with scikit-learn](https://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html)

---

## 📝 License

This project is licensed under the MIT License.
