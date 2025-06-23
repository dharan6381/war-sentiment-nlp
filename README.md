# 🇮🇳 War Sentiment Analysis Using NLP (India–Pakistan Tension)

This project uses Natural Language Processing (NLP) to classify public sentiment related to India–Pakistan border tensions. The goal is to understand how people express emotions during moments of national conflict using real-looking text samples.

---

## 📌 Project Objective

To build a machine learning model that can automatically classify text statements as:

- Positive 😊
- Neutral 😐
- Negative 😠

---

## 🗂️ Dataset

A custom dataset was created with 25+ text entries simulating social media reactions and news statements related to India–Pakistan border tensions. Each text is manually labeled with a sentiment class (`positive`, `neutral`, `negative`).

**File:** `updated_india_pakistan_tension_sentiment.csv`

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- TfidfVectorizer
- Logistic Regression
- Matplotlib, Seaborn

---

## 🧠 Steps Involved

1. Load and preview dataset
2. Clean text (remove punctuation, lowercase, etc.)
3. Convert text into TF-IDF vectors
4. Encode sentiment labels
5. Train/test split
6. Train logistic regression model
7. Evaluate performance using classification report
8. Predict sentiment of new input text

---

## 📊 Example Output

```bash
              precision    recall  f1-score   support

    negative       1.00      1.00      1.00         2
     neutral       1.00      1.00      1.00         2
    positive       1.00      1.00      1.00         1

    accuracy                           1.00         5
