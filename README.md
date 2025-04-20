# Skripsi-LSTM
Kumpulan kode, data, dan hasil eksperimen skripsi yang berfokus pada prediksi harga saham menggunakan arsitektur Long Short-Term Memory (LSTM). Termasuk inisialisasi bobot &amp; bias, proses training, hasil prediksi, serta evaluasi model.
# Skripsi-LSTM 📈🤖

Repositori ini berisi seluruh komponen skripsi yang berfokus pada prediksi harga saham menggunakan model Long Short-Term Memory (LSTM). Tujuan utama dari penelitian ini adalah untuk mengevaluasi efektivitas model LSTM dalam memprediksi harga saham dan mengoptimasi portofolio dengan pendekatan Mean-Absolute Deviation (MAD).

## 📂 Struktur Folder
├── Data/ # File .csv harga saham (8 saham) ├── Models/ │ ├── Bobot_Bias_Awal/ # File bobot dan bias awal tiap saham │ ├── Bobot_Bias_Akhir/ # File bobot dan bias hasil training tiap saham │ └── Forward_Propagation/ # Output proses forward tiap saham ├── Scripts/ # Notebook .ipynb untuk masing-masing saham ├── Hasil_Prediksi.pdf # Hasil akhir prediksi dalam bentuk PDF └── README.md # Deskripsi proyek ini

## 🔧 Tools & Library

- Python (Google Colab)
- TensorFlow / Keras
- Pandas, NumPy, Matplotlib
- Scikit-learn

## 🔍 Metodologi

1. **Preprocessing Data**: Data harga saham ditransformasi dan dinormalisasi.
2. **Modeling dengan LSTM**: Setiap saham dibuat modelnya sendiri menggunakan arsitektur LSTM.
3. **Evaluasi & Optimasi**: Hasil prediksi dievaluasi dan digunakan dalam strategi optimasi portofolio berbasis MAD.

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
