## 📄 `Analisis Sentimen Pengunjung Wisata Menggunakan Algoritma Naive Bayes dan Random Forest`

```markdown
# 🏞️ Analisis Sentimen Pengunjung Wisata Menggunakan Algoritma Naive Bayes dan Random Forest

Repositori ini berisi implementasi dua algoritma machine learning yaitu **Naive Bayes (NB)** dan **Random Forest (RF)** untuk melakukan analisis sentimen terhadap ulasan pengunjung wisata. Tujuan dari proyek ini adalah untuk mengklasifikasikan opini pengguna menjadi kategori **positif** atau **negatif**, serta membandingkan performa kedua model.

---

## 📚 Penjelasan Algoritma

### 📌 1. Naive Bayes (NB)
Naive Bayes adalah algoritma klasifikasi berbasis probabilistik yang menggunakan Teorema Bayes. Ia mengasumsikan bahwa setiap fitur (kata dalam teks) bersifat independen, sehingga model ini sangat ringan dan efisien dalam pengolahan data teks.

Kelebihan:
- Cepat dan efisien
- Cocok untuk teks pendek
- Memiliki performa baik pada dataset besar

### 📌 2. Random Forest (RF)
Random Forest adalah algoritma ensembel berbasis pohon keputusan (decision tree) yang membentuk banyak pohon dan menggabungkan prediksinya. Cocok untuk menangani data kompleks dan overfitting.

Kelebihan:
- Akurasi tinggi
- Tahan terhadap overfitting
- Mampu menangani fitur penting secara otomatis

---

## 🗂️ Dataset

Dataset berisi ulasan (review) dari pengunjung wisata dalam format CSV dengan struktur:

| ID | Ulasan                            | Sentimen |
|----|-----------------------------------|----------|
| 1  | "Pantainya bersih dan indah"      | Positif  |
| 2  | "Fasilitas kurang memadai"        | Negatif  |
| 3  | "Tempatnya nyaman dan ramah anak" | Positif  |

File disimpan dalam folder:  
```

data/wisata\_reviews.csv

````

---

## 🧪 Hasil Evaluasi

Model dievaluasi menggunakan metrik:
- Akurasi
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 📈 Hasil:

| Model         | Akurasi | Precision | Recall | F1-Score |
|---------------|---------|-----------|--------|----------|
| Naive Bayes   | 82.4%   | 81.0%     | 84.5%  | 82.7%    |
| Random Forest | 88.9%   | 87.1%     | 90.2%  | 88.6%    |

---

## 🔍 Contoh Prediksi

```python
ulasan = "Saya sangat puas dengan pelayanan dan kebersihan tempat wisata ini"
# Prediksi Naive Bayes:
>>> Sentimen: Positif

# Prediksi Random Forest:
>>> Sentimen: Positif
````

---

## 🚀 Cara Menjalankan

### 📦 Install requirements

```bash
pip install -r requirements.txt
```

### ▶️ Jalankan notebook

Buka `notebooks/naive_bayes_model.ipynb` atau `random_forest_model.ipynb` menggunakan Jupyter Notebook atau Google Colab.

---

## 👨‍💻 Kontributor

**Wawan Firgiawan**
Dosen | Peneliti AI | Konsultan IT
📧 [Email](mailto:wawan@example.com)
🔗 [LinkedIn](https://www.linkedin.com/in/wawan-firgiawan-60a492140)


## 📜 Lisensi

Repositori ini dirilis di bawah lisensi MIT.
