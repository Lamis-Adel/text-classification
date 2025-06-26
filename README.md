#  Spam Message Classifier

This project is a simple **Text Classification** model built with Python to classify SMS messages as either **Spam** or **Ham (Not Spam)** using the **Multinomial Naive Bayes** algorithm.

---

# Technologies Used

- Python
- Pandas
- Scikit-learn
- TfidfVectorizer
- Naive Bayes Classifier

---

# Dataset

- The dataset used is [`spam.csv`] which contains labeled SMS messages.
- Columns used:
  - `v1`: Label (`spam` or `ham`)
  - `v2`: The actual message

---

# How it works

1. Load and clean the dataset.
2. Encode labels (`spam` = 1, `ham` = 0).
3. Split the data into training and testing sets.
4. Transform messages using **TF-IDF Vectorizer**.
5. Train a **Multinomial Naive Bayes** model.
6. Evaluate the model with **Confusion Matrix** and **Classification Report**.

---


