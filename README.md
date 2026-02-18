# YouTube Sentiment Analysis
Aplikasi untuk menganalisis sentimen komentar menggunakan tautan YouTube. 
Aplikasi dibuat untuk memahami respon audiens melalui hasil persentase sentimen.

## 🚀 Live Demo
-> https://nlpproject-sentiment-dashboard.streamlit.app/

## Fitur Utama
* **YouTube Scraping**: Mengambil top 100 komentar via YouTube Data API v3.
* **Deep Learning Analysis**: Klasifikasi sentimen (Positif, Netral, Negatif) menggunakan model transformer.
* **Text Preprocessing**: Data cleaning mencakup HTML unescape, URL removal, mention removal, lowercasing, dan penghapusan karakter berulang.
* **Interactive Dashboard**: Visualisasi distribusi sentimen menggunakan Plotly Express.

## 📊 Model & Dataset
Model ini berbasis **IndoRoBERTa** yang telah melalui proses *fine-tuning* menggunakan:
* **Dataset**: SmSA (IndoBenchmark) dari IndoNLU.
* **Jumlah Data**: 11.000+ baris data komentar berbahasa Indonesia.
* **Label**: Klasifikasi 3 kelas (Positif, Netral, dan Negatif).

## ⚙️ Tech Stack
* **Language**: Python 3.10
* **Framework**: Streamlit
* **AI Model**: Hugging Face Transformers (IndoRoBERTa)
* **API**: YouTube Data API v3
* **Visualisasi**: Plotly

