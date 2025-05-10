# 📰 Article Sentiment Analyzer

A simple GUI-based Python application that analyzes the sentiment of any news article given its URL. This tool extracts the article, summarizes its content, and visually displays the overall sentiment using a polarity score and a color-coded bar chart.

![Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)
![TextBlob](https://img.shields.io/badge/NLP-TextBlob-green.svg)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-yellow.svg)

## ✨ Features

- 📰 Extracts and summarizes news articles using `newspaper3k`
- 📊 Performs sentiment analysis with `TextBlob`
- 🎨 Visualizes the sentiment polarity using a bar chart (Matplotlib)
- 🧠 Introduces fundamental NLP concepts like polarity and subjectivity
- 🖼️ User-friendly interface using Tkinter

## 🧰 Technologies Used

- Python 3
- TextBlob
- Newspaper3k
- NLTK
- Matplotlib
- Tkinter (built-in Python GUI)

## 🚀 Getting Started

1. **Install the dependencies:**

```bash
pip install textblob newspaper3k matplotlib
python -m textblob.download_corpora
Run the application:

bash
Copy
Edit
python sentiment_analyzer.py
Paste any news article URL and click "Analyze Sentiment".

📚 Background
This project was an early experiment in exploring how AI and NLP work under the hood. It helped me get hands-on with article parsing, sentiment scoring, and GUI development. Looking back, it’s a simple app—but it laid the foundation for everything I’ve built since then.

🖋️ Author
Designed & developed by Geo Mathew Joseph
