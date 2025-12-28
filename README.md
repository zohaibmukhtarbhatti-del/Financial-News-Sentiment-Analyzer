# 📈 Financial News Sentiment Analyzer

An NLP-based Deep Learning project that predicts whether financial news headlines are **Positive** or **Negative** and analyzes their potential impact on stock prices.

## 🚀 Project Overview
This project uses **Long Short-Term Memory (LSTM)** neural networks to classify financial text. It includes a full pipeline from data cleaning and automated labeling (using VADER) to model training and deployment via a web interface.

## ✨ Key Features
* **Deep Learning Model:** Built using TensorFlow/Keras with Bi-Directional LSTM layers.
* **High Accuracy:** Achieved **~98% accuracy** on the test dataset.
* **Automated Labeling:** Used NLTK VADER to generate sentiment labels for unlabeled data.
* **Stock Correlation:** Analyzed the relationship between news sentiment and actual stock price movements (using `yfinance`).
* **Interactive UI:** Deployed a user-friendly web app using **Gradio** for real-time predictions.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** TensorFlow, Keras, NLTK, Spacy, Scikit-learn, Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **API/Data:** YFinance (Yahoo Finance API)
* **Interface:** Gradio

## 📊 Results
* **Accuracy:** 98%
* **Confusion Matrix:** showed strong performance in distinguishing positive vs. negative news.
* **Correlation:** Found positive correlation (0.17) for stocks like 'KEY' (KeyCorp).

## 🖥️ How to Run
1.  Clone the repository.
2.  Install dependencies: `pip install tensorflow spacy gradio yfinance`
3.  Run the notebook or python script.
4.  Launch the Gradio interface to test headlines manually.

---
*Created by [Zohaib Mukhtar]*
