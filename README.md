# Cyberbullying Detection terhadap Tweet pada Media Sosial X

Repositori ini berisi kode program dan dataset yang digunakan dalam penelitian skripsi berjudul:

> **"Cyberbullying Detection terhadap Tweet pada Media Sosial X Menggunakan Random Forest dengan Feature Selection Information Gain"**  
> oleh Zamzam Miftahul Faoz (2100018381)  
> Universitas Ahmad Dahlan – S1 Informatika – 2025

## 📋 Deskripsi Singkat

Penelitian ini bertujuan untuk membangun dan mengevaluasi model klasifikasi teks guna mendeteksi cyberbullying pada platform **X** (sebelumnya dikenal sebagai Twitter). Model dikembangkan menggunakan algoritma **Random Forest** yang dioptimalkan melalui **Grid Search CV**, serta didukung oleh teknik seleksi fitur **Information Gain**.

### 🔍 Fitur Utama
- Preprocessing teks menggunakan TF-IDF
- Feature selection dengan Information Gain
- Optimasi model menggunakan Grid Search Cross Validation
- Evaluasi dengan skema validasi **5-Fold** dan **10-Fold**
- Metrik evaluasi: Accuracy, Precision, Recall, dan F1-Score

## 📁 Struktur Direktori

```
.
├── dataset/                # Dataset yang digunakan (3 jenis dataset)
├── src/                    # Script Python utama
│   ├── preprocessing.py    # Cleaning, tokenizing, stopwords, dll
│   └── model_training.py
├── results/                # Output hasil evaluasi model
├── README.md               # Dokumen ini
└── requirements.txt        # Daftar dependencies Python
```

## ⚙️ Teknologi yang Digunakan

- Python 3.x
- Scikit-learn
- Pandas
- NumPy
- NLTK / Sastrawi (untuk NLP Bahasa Indonesia)
- Matplotlib / Seaborn (opsional, visualisasi hasil)

## 📊 Dataset

Tiga dataset digunakan dalam penelitian ini:
1. **Cyberbullying Dataset** (Kaggle)
2. **Indonesian Twitter Cyberbullying Detection**
3. **Cyberbullying Tweets** (GitHub Public)

Semua dataset dikategorikan ke dalam dua label: `bullying` dan `non-bullying`.

## 📈 Hasil

Model terbaik dalam validasi:
- **5-Fold CV**: Accuracy 81.2%, F1-Score 80.5%
- **10-Fold CV**: Accuracy 81.3%, F1-Score 81.2%

## 📄 Lisensi

Repositori ini dibagikan untuk tujuan edukasi dan penelitian. Harap mencantumkan sumber jika menggunakan sebagian atau seluruh isi dari repositori ini.
