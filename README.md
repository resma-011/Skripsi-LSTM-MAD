# Skripsi-LSTM
Kumpulan kode, data, dan hasil eksperimen skripsi yang berfokus pada prediksi harga saham menggunakan arsitektur Long Short-Term Memory (LSTM). Termasuk inisialisasi bobot &amp; bias, proses training, hasil prediksi, serta evaluasi model.
# Skripsi-LSTM 📈🤖

Repositori ini berisi kode, data, dan hasil eksperimen skripsi menggunakan data harga saham dengan model Long Short-Term Memory (LSTM). Tujuan utama dari penelitian ini adalah untuk mendapatkan hasil prediksi harga saham menggunakan model LSTM.

## 📂 Struktur Folder
- `data/`: Dataset harga saham dalam format `.csv`
- `models/`: Berisi hasil training model LSTM berupa bobot dan bias dan output pada forward propagation batch pertama`(.xlsx)`
- `scripts/`: Notebook Jupyter untuk masing-masing saham`(.ipynb)`
- `hasil_prediksi/`: Output hasil prediksi yang telah dirender ke PDF
  
## 🔧 Tools & Library

- Python (Google Colab)
- TensorFlow / Keras
- Pandas, NumPy, Matplotlib
- Scikit-learn

## 🔍 Metodologi

1. **Preprocessing Data**: Data harga saham dinormalisasi.
2. **Modeling dengan LSTM**: Setiap saham dibuat modelnya sendiri menggunakan arsitektur LSTM.
3. **Evaluasi & Optimasi**: Hasil prediksi dievaluasi menggunakan MAPE.

## 📊 Hasil Akhir

- Visualisasi hasil prediksi per saham
- Return harian saham aktual vs hasil prediksi
- Bobot optimal tiap saham dalam portofolio

## 📌 Catatan

- Semua bobot & bias dicatat untuk transparansi proses training.
- Notebook terpisah per saham agar lebih modular.

## 👤 Author

Resma Damayanti. — [GitHub](https://github.com/resma-011)  
Universitas Padjadjaran, 2025

---

> Untuk pertanyaan atau kolaborasi, feel free buat open issue atau kontak langsung.  
