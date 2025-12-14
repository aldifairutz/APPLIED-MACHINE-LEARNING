# Sistem Deteksi Dini Penurunan Performa Belajar Siswa   Berdasarkan Analisis Kualitas Infrastruktur Dan Kapasistas Pengajar 
 🎓


## 📋 Deskripsi Proyek
Proyek ini bertujuan untuk membangun model Machine Learning yang dapat memprediksi sekolah-sekolah yang berisiko mengalami penurunan mutu pendidikan (status "WASPADA") berdasarkan analisis data **Kualitas Infrastruktur** dan **Kapasitas Pengajar**.

Sistem ini dibuat untuk memenuhi **Tugas Besar Mata Kuliah Applied Machine Learning**.

## 📂 Dataset
Data yang digunakan berasal dari data terbuka **Kemendikdasmen 2025** (atau tahun terbaru yang tersedia), yang mencakup:
- Data Jumlah Siswa
- Data Jumlah Guru
- Data Kondisi Ruang Kelas
- **Sumber:** [Link ke website data kemendikbud](https://data.kemendikdasmen.go.id/dataset/pendidikan-2)

## 🛠️ Teknologi yang Digunakan
- **Bahasa:** Python
- **Library:** Pandas, Scikit-Learn, Matplotlib, Seaborn
- **Deployment:** Gradio (Web Interface)

## 🚀 Cara Menjalankan Proyek
1. Clone repositori ini atau download file `.ipynb`.
2. Upload file dataset (`.csv` atau `.xlsx`) ke Google Colab / Jupyter Notebook.
3. Install library yang dibutuhkan:
   ```bash
   pip install gradio pandas scikit-learn
