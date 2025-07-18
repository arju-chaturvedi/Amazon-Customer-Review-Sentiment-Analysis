# 🛍️ Amazon Customer Review Sentiment Analysis

This project analyzes Amazon product reviews and classifies them into **Positive**, **Negative**, or **Neutral** sentiment using NLP and machine learning.

---

## 📌 Objectives

- Analyze the tone and polarity of customer feedback
- Build classification models using supervised ML
- Explore and visualize key trends in review data

---

## 🧠 Techniques Used

- Text preprocessing (stopwords removal, stemming)
- TF-IDF Vectorization
- Logistic Regression, Naive Bayes, and SVM
- Confusion matrix & classification report
- WordCloud and sentiment score analysis

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core scripting |
| Pandas / NumPy | Data manipulation |
| Matplotlib / Seaborn | Visualization |
| NLTK | NLP pre-processing |
| Scikit-learn | ML model training |
| WordCloud | Text visualization |

---

## 📊 Dataset

The dataset contains thousands of Amazon product reviews with their associated text and sentiment labels (Positive, Neutral, Negative).

_Source_: Public Amazon Review Dataset (Kaggle or UCI)

---

## 🚀 Project Pipeline

1. **Load & clean review data**
2. **Preprocess text** (lowercasing, punctuation removal, stopwords, stemming)
3. **Vectorize** using TF-IDF
4. **Train Models**:
   - Logistic Regression
   - Naive Bayes
   - Support Vector Machine (SVM)
5. **Evaluate performance**
6. **Visualize results**
   - Word cloud
   - Sentiment distribution
   - Confusion matrix

---

## 📈 Example Output

- Accuracy: ~85% (Logistic Regression)
- Precision / Recall / F1 scores detailed in report
- Visual sentiment breakdown

---

## ✅ Future Improvements

- Add deep learning models (LSTM, BERT)
- Create a Streamlit web app for live review scoring
- Connect to real-time Amazon reviews via API
- Deploy as a REST API or demo site

---

## 🙋‍♂️ Author

**Arju Chaturvedi**  
🎓 M.Sc. Data Science & AI | 📍 Berlin  
📎 [Portfolio](https://www.notion.so/Arju-Chaturvedi-Data-AI-Project-Portfolio-1d03da61e3e880cd8da5db7353cb6200)

---

## 🤝 Contributions

Pull requests are welcome. For major changes, please open an issue first.

---

## 📥 Clone the Repo

```bash
git clone https://github.com/arju-chaturvedi/Amazon-Customer-Review-Sentiment-Analysis.git
cd Amazon-Customer-Review-Sentiment-Analysis
pip install -r requirements.txt
