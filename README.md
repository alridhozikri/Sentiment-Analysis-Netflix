# 🎬 Netflix User Review Sentiment Analysis

## 📌 Deskripsi Project
Project ini berfokus pada analisis sentimen terhadap lebih dari 3.000 ulasan pengguna Netflix yang diambil dari Google Play Store. Project ini menggunakan teknik Natural Language Processing (NLP) dan algoritma Support Vector Machine (SVM) untuk mengklasifikasikan ulasan ke dalam sentimen positif dan negatif.

---

## 🚀 Fitur
- Scraping ulasan pengguna Netflix dari Google Play Store
- Preprocessing dan pembersihan teks
- Normalisasi kata slang
- Stemming bahasa Indonesia menggunakan Sastrawi
- Ekstraksi fitur menggunakan TF-IDF
- Klasifikasi sentimen menggunakan SVM
- Evaluasi model menggunakan accuracy score dan classification report

---

## 🛠️ Teknologi yang Digunakan
- Python
- NLP (Natural Language Processing)
- TF-IDF Vectorizer
- Support Vector Machine (SVM)
- Pandas
- Scikit-learn
- Sastrawi

---

## 📂 Alur Project

```text
Scraping Data
      ↓
Preprocessing Teks
      ↓
Normalisasi Kata Slang
      ↓
Stemming
      ↓
Ekstraksi Fitur TF-IDF
      ↓
Training Model SVM
      ↓
Klasifikasi Sentimen
      ↓
Evaluasi Model
```

---

## 📊 Informasi Model

### Rumus TF-IDF

```math
TF-IDF(t,d)=TF(t,d)\times IDF(t)
```

### Konsep Klasifikasi SVM

```math
f(x)=sign(w^Tx+b)
```

---

## 📈 Hasil
Model berhasil mengklasifikasikan ulasan pengguna Netflix ke dalam:
- Sentimen Positif
- Sentimen Negatif
- Akurasi Testing : 88.39%

Model menunjukkan performa yang baik dengan kombinasi TF-IDF dan algoritma Linear SVM.

---

## 📁 Dataset
- Sumber: Google Play Store Reviews
- Jumlah Data: 3.000+ ulasan pengguna

---

## ▶️ Cara Menjalankan Project

```bash
pip install pandas scikit-learn sastrawi
```

```bash
python main.py
```

---

## 👨‍💻 Author
Mahasiswa Sistem Informasi yang memiliki ketertarikan di bidang Data Analysis, Data Science, dan Machine Learning.
