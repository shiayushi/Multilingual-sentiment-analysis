# Multilingual-sentiment-analysis
# 🌍 Multilingual Sentiment Analyzer 😄

Analyze the **sentiment** of text in multiple languages (like English, Hindi, Hinglish, French, etc.) using a fine-tuned BERT model.

✅ Built with HuggingFace Transformers  
✅ Supports multilingual inputs  
✅ Deployed with Streamlit Cloud  

![image](https://github.com/user-attachments/assets/7efa388d-2247-42db-8e5c-106c13586c24)


---

## 🚀 Try it Live  
🔗 [Click here to open the app](https://multilingual-sentiment-analysiss.streamlit.app)

---

## 🧠 What It Does

- Detects the sentiment of a sentence from multiple languages
- Uses a star-based model to map rating → emoji sentiment
- Simple, clean UI built using Streamlit

---
## 📌 Example Output

Input: "I love this project"
Model Rating: 5 stars
Sentiment: 😊 Positive
---

## 🛠 Tech Stack

- 🐍 Python
- 🤗 Transformers (`nlptown/bert-base-multilingual-uncased-sentiment`)
- 🔎 Streamlit
- 🧠 HuggingFace Pipelines

---

## 📁 Folder Structure
📦 Multilingual-Sentiment-Analyzer
┣ sentiment_app.py
┣ requirements.txt
┗ README.md


---

## 🧪 How to Run Locally

```bash
git clone https://github.com/shiayushi/Multilingual-sentiment-analysis.git
cd Multilingual-sentiment-analysis
pip install -r requirements.txt
streamlit run sentiment_app.py


