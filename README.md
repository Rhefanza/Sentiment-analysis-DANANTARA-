# Analisis Sentimen Publik terhadap Danantara

Proyek NLP untuk menganalisis opini publik di platform X mengenai Badan Pengelola Investasi Danantara menggunakan preprocessing teks, klasifikasi sentimen, dan visualisasi.

## Pipeline

1. Mengumpulkan data publik terkait Danantara.
2. Membersihkan teks, URL, mention, tanda baca, dan duplikasi.
3. Melakukan case folding, tokenisasi, stopword removal, serta stemming.
4. Menyiapkan fitur teks.
5. Melatih dan mengevaluasi Naive Bayes.
6. Membuat visualisasi distribusi sentimen dan kata yang dominan.

## Teknologi

- Python
- Pandas dan NumPy
- scikit-learn
- NLTK dan Sastrawi
- Matplotlib, Seaborn, dan WordCloud

## File

- `Danantara_sentiment_Analysis.ipynb` — notebook utama.
- `Data Sentiment.csv` — data analisis.
- `Analisis Sentimen Danantara .pdf` — laporan proyek.

## Menjalankan

```bash
git clone https://github.com/Rhefanza/Sentiment-analysis-DANANTARA-.git
cd Sentiment-analysis-DANANTARA-
pip install pandas numpy scikit-learn nltk Sastrawi matplotlib seaborn wordcloud jupyter
jupyter notebook Danantara_sentiment_Analysis.ipynb
```

## Evaluasi

Performa model perlu dibaca menggunakan precision, recall, F1-score, dan confusion matrix per kelas. Distribusi sentimen aktual serta metrik final mengikuti output notebook dan laporan, sehingga tidak ditulis sebagai angka tetap di README.

## Catatan Etika

Data media sosial dapat memuat bahasa informal, sarkasme, dan konteks yang sulit ditangkap oleh model. Hasil klasifikasi perlu diperlakukan sebagai estimasi analitis, bukan representasi mutlak opini masyarakat.
