# Fake News Analysis

A machine learning-based program for detecting whether a news article is **Real** or **Fake** using text classification.  
The model uses **TF-IDF Vectorization** and the **Multinomial Naive Bayes** algorithm to analyze and classify news content.

---

## 📂 Dataset

This project requires two datasets:

| File | Description |
|------|-------------|
| `True.csv` | Contains real news articles |
| `Fake.csv` | Contains fake news articles |

Download both datasets from the link below:

> https://itdesigners.org/wp-content/uploads/2024/02/Fake-news-datasets.zip

Extract the ZIP file and place both CSV files **in the same folder as the script**.

---

## 🧠 How the Model Works

1. Loads real and fake news datasets.
2. Assigns labels:  
   - `0` → True News  
   - `1` → Fake News
3. Converts text into numerical features using **TF-IDF**.
4. Trains a **Multinomial Naive Bayes** classifier.
5. Evaluates accuracy and classification performance.
6. Allows the user to input any news text for prediction.

---

## 🛠 Requirements

Install required Python libraries:

```bash
pip install pandas scikit-learn
```

### How to Run

1.Download and extract the dataset.

2.Download the script file fake_news.py (your provided code).

3.Place True.csv and Fake.csv in the same folder as the script.

Run the program:
```bash
python fake_news.py
```
5.Enter any news article text when prompted to check if it's real or fake.
