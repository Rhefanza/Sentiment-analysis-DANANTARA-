# Sentiment-analysis-DANANTARA-
# Analisis Sentimen Publik Terhadap BP Investasi Danantara 🇮🇩

Proyek ini bertujuan untuk menganalisis opini dan sentimen masyarakat di platform media sosial X (Twitter) mengenai pembentukan **Badan Pengelola Investasi Danantara** menggunakan algoritma **Naive Bayes Classifier**.

## 📌 Ringkasan Proyek
Badan Pengelola Investasi Danantara merupakan institusi baru yang menarik banyak perhatian publik. Analisis ini dilakukan untuk memahami apakah respon masyarakat cenderung positif, negatif, atau netral terhadap inisiatif ini.

### Fitur Utama:
* **Data Crawling**: Mengambil data tweet publik mengenai "Danantara".
* **Text Preprocessing**: Pembersihan data mentah meliputi *Cleansing*, *Case Folding*, *Tokenizing*, *Filtering* (Stopword removal menggunakan Sastrawi), dan *Stemming*.
* **Sentiment Classification**: Menggunakan algoritma **Naive Bayes** untuk mengklasifikasikan teks.
* **Visualisasi Data**: Distribusi sentimen dan *WordCloud* kata-kata yang paling sering muncul.

## 🛠️ Teknologi yang Digunakan
* **Bahasa**: Python
* **Library**: 
    * `Pandas` & `NumPy` (Olah data)
    * `Scikit-Learn` (Model Machine Learning)
    * `NLTK` & `Sastrawi` (Natural Language Processing)
    * `Matplotlib` & `Seaborn` (Visualisasi)

## 📊 Hasil Analisis
Berdasarkan pengujian yang dilakukan:
* **Sentimen Dominan**: Sentimen [Isi di sini, misal: Netral/Positif] menjadi opini yang paling banyak ditemukan.
* **Akurasi Model**: Model Naive Bayes memberikan hasil performa yang cukup stabil dalam mengklasifikasikan opini publik.

## 📂 Struktur File
* `Danantara_sentiment_Analysis.ipynb`: Notebook utama berisi alur kode dari crawling hingga evaluasi model.
* `Analisis Sentimen Danantara.pdf`: Dokumen laporan lengkap mengenai metodologi dan hasil penelitian.

## 🚀 Cara Menjalankan
1. Clone repositori ini:
   ```bash
   git clone [https://github.com/username-kamu/nama-repo.git](https://github.com/username-kamu/nama-repo.git)
