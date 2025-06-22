# Analisis Data Penumpang TransJakarta Tahun 2023

# Project Overview

Transportasi publik yang efisien menjadi tulang punggung mobilitas masyarakat urban. Salah satu moda transportasi massal yang penting di DKI Jakarta adalah TransJakarta. Proyek ini bertujuan untuk menganalisis data penumpang TransJakarta tahun 2023 guna menggali wawasan mendalam tentang perilaku pengguna, waktu-waktu sibuk, serta rute dan metode pembayaran yang paling sering digunakan.

Melalui pendekatan berbasis data, diharapkan hasil analisis ini dapat memberikan rekomendasi strategis yang berdampak nyata terhadap perbaikan layanan TransJakarta, mulai dari pengaturan jadwal hingga optimalisasi armada dan rute.

## Raw Dataset

Dataset diperoleh dari sumber terbuka yang berisi informasi transaksi harian TransJakarta selama tahun 2023, termasuk:
- Tanggal transaksi
- Jumlah penumpang
- Kategori usia dan gender
- Metode pembayaran (e-money, QRIS, dsb)
- Nama bank penerbit kartu
- Koridor/rute

> [Link Dataset (https://www.kaggle.com/datasets/dikisahkan/transjakarta-transportation-transaction/datav)
> [Link Dataset (https://drive.google.com/drive/folders/1L2d-hJpiSQhfBJ3Hg8GiPANHWzXBtWPE?usp=drive_link)

# Analysis Process

Analisis dilakukan menggunakan Google Colab dengan bahasa pemrograman Python dan library populer seperti `pandas`, `matplotlib`, dan `seaborn`.

Langkah-langkah yang dilakukan:

1. **Data Cleaning**  
   - Menghapus duplikasi dan data null  
   - Standarisasi format tanggal dan nama kolom  

2. **Exploratory Data Analysis (EDA)**  
   - Visualisasi jumlah penumpang per bulan  
   - Analisis distribusi berdasarkan usia, gender, metode pembayaran, dan koridor  
   - Identifikasi waktu puncak penggunaan

3. **Insight Extraction**  
   - Membandingkan tren antar variabel  
   - Menganalisis pola berdasarkan waktu (mingguan dan harian)  
   - Evaluasi koridor dan bank kartu terbanyak

4. **Visualisasi**  
   - Bar chart, pie chart, heatmap, dan line chart untuk memperkuat pemahaman data


# Insight & Findings

Beberapa insight utama yang diperoleh dari analisis:

- **Jam Tertinggi** penggunaan TransJakarta terjadi pukul **07.00–09.00 pagi**, menunjukkan mobilitas saat berangkat kerja.
- **Kelompok pengguna dominan** adalah perempuan usia **25–35 tahun**.
- **Koridor 1 dan 9** adalah rute paling sibuk, berpotensi untuk ditambah armada.
- **Metode pembayaran** e-money mendominasi, terutama dari **Bank DKI dan BCA**.
- Penggunaan layanan meningkat di hari kerja, dan menurun signifikan pada akhir pekan.


# Conclusion & Recommendation

Berdasarkan insight yang diperoleh, berikut beberapa rekomendasi yang dapat diterapkan:

1. **Penambahan armada dan frekuensi bus** di jam sibuk (07.00–09.00).
2. **Evaluasi dan penyesuaian rute** di koridor sibuk seperti Koridor 1 & 9.
3. **Perluasan kerja sama dengan bank** penyedia e-money untuk integrasi layanan pembayaran.
4. **Kampanye promosi pada akhir pekan** untuk meningkatkan jumlah penumpang.
5. **Peningkatan fasilitas penunjang** di halte dengan lalu lintas tinggi.


# AI Support Explanation

AI digunakan secara relevan dalam proyek ini, terutama dalam bentuk bantuan dari Large Language Model (LLM) seperti ChatGPT untuk:

- Menyusun struktur analisis dan langkah-langkah eksplorasi data.
- Menjelaskan insight yang diperoleh secara logis dan menyeluruh.
- Membantu merancang dokumentasi seperti README.md dan presentasi.
- Memberikan umpan balik dalam menyusun kesimpulan dan rekomendasi.


# Author

- **Nama:** Alfrido Lakhomi Zebua  
- **Email:** didozebua0@gmail.com  
- **GitHub:** [github.com/alfrido16](https://github.com/alfrido16)


