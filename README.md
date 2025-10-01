# Pre-processing-Data

Created by: Erny Marito Br Tompul

Institusi: Universitas Negeri Semarang

Repositori ini merupakan dokumentasi proyek untuk mata kuliah Data Mining, yang berfokus pada tahapan penting dalam preprocessing data. Proyek ini mendemonstrasikan alur kerja dalam membersihkan dan menyiapkan dataset mentah (movie_sample_dataset.csv) hingga menjadi dataset yang bersih dan siap untuk dianalisis (movie_dataset_cleaned.csv). Seluruh proses dikerjakan menggunakan Python dengan pustaka Pandas di Google Colab.

Tahapan Pengerjaan
Proses dalam proyek ini dibagi menjadi empat tahap utama yang terdokumentasi dalam file Notebook:

1. Pemuatan Data
Proses dimulai dengan memuat data dari file CSV.

2. Memuat Data
Dilakukan inspeksi awal untuk memahami struktur data, seperti melihat tipe data setiap kolom, serta mengidentifikasi keberadaan nilai yang hilang (null values) dan data duplikat.

3. Pembersihan Data (Data Cleaning)
Kegiatannya meliputi mengecek data duplikat dan menghapusnya, menghapus data yang kosong, pengisian nilai yang kosong dengan metode yang sesuai, serta memperbaiki data yang tidak logis atau tidak valid.

4. Transformasi Data
Untuk memastikan konsistensi data, dilakukan transformasi data yaitu:
- Mengubah beberapa kolom menjadi tipe data numerik.
- Memisahkan (splitting) kolom genres.
- Menyeragamkan (standardize) kolom color dan country.
