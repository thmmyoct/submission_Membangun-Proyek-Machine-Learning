
---

# Analisis Data Publik E-Commerce dengan Python - Dicoding
## Ringkasan

Proyek ini merupakan analisis dan visualisasi data yang berfokus pada data publik e-commerce. Di dalamnya terdapat kode untuk proses data wrangling, analisis data eksploratori (EDA), serta pembuatan dasbor interaktif menggunakan Streamlit. Tujuan utama proyek ini adalah menganalisis dataset publik E-Commerce.

---

## Struktur Proyek

* `dashboard/`: Folder yang berisi `dashboard.py`, digunakan untuk membuat dasbor hasil analisis data.
* `data/`: Folder berisi file data mentah berformat CSV.
* `notebook.ipynb`: Notebook utama untuk melakukan analisis data.
* `notebook_ID.ipynb`: Versi bahasa Indonesia dari notebook.ipynb.
* `README.md`: File dokumentasi proyek ini.

---

## Instalasi

1. Salin repositori ini ke komputermu dengan perintah:

```
git clone https://github.com/thmmoct/submission_Membangun-Proyek-Machine-Learning.git
```

2. Masuk ke direktori proyek:

```
cd submission
```

3. Instal semua pustaka Python yang diperlukan:

```
pip install -r requirements.txt
```

---

## Cara Menggunakan

1. **Data Wrangling**: Script untuk membersihkan dan menyiapkan data bisa ditemukan di file `notebook.ipynb`.

2. **Analisis Data Eksploratori (EDA)**: Gunakan script Python yang disediakan untuk mengeksplorasi dan memahami pola-pola dalam data publik e-commerce.

3. **Visualisasi**: Jalankan dasbor interaktif dengan Streamlit untuk eksplorasi data secara langsung:

```
cd submission/dashboard
streamlit run dashboard.py
```

Buka dasbor ini melalui browser di `http://localhost:8501`.

---

## Sumber Data

Proyek ini memanfaatkan **E-Commerce Public Dataset** dari proyek akhir [Belajar Analisis Data dengan Python](https://drive.google.com/file/d/1MsAjPM7oKtVfJL_wRp1qmCajtSG1mdcK/view) yang disediakan oleh [Dicoding](https://www.dicoding.com/).

---
