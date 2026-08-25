# System Overview

## Purpose 
Sistem membantu melakukan konsultasi awal kondisi kesehatan berdasarkan gejala yang dipilih oleh pengguna. Gejala yang dipilih akan diproses untuk menghasilkan informasi awal mengenai kemungkinan kondisi kesehatan pengguna sebelum memutuskan konsultasi lebih lanjut dengan layanan kesehatan.

## User Roles 
**User**  
Pengguna Umum yang mengakses aplikasi untuk melakukan konsultasi awal berdasarkan gejala yang dipilih dan memperoleh informasi awal terkait kondisi kesehatan.  

Responsibilities :  
- Melakukan konsultasi berdasarkan gejala yang dipilih.
- Melihat hasil konsultasi terkait kemungkinan kondisi kesehatan.
- Mengakses informasi umum terkait penyakit yang tersedia dalam aplikasi.

**Admin**  
Dokter atau pakar yang bertanggung jawab mengelola data yang digunakan dalam proses konsultasi awal kesehatan. 

Responsibilities :
- Mengelola data gejala.
- Mengelola data penyakit dan informasi penyakit.
- Memelihara data yang digunakan dalam proses konsultasi.

## System Scope
### In Scope
- Menerima gejala yang dipilih pengguna.
- Memproses gejala berdasarkan basis pengetahuan pakar.
- Menyediakan informasi awal mengenai kemungkinan kondisi kesehatan.
- Menyediakan informasi umum penyakit.
- Mengelola data gejala, data penyakit, dan data relasi diagnosis.

### Out Scope
- Menentukan diagnosis medis sebagai pengganti tenaga kesehatan.
- Melakukan konsultasi dengan pengguna secara real-time.
- Memberikan penanganan medis seperti seorang dokter.
- Menghubungkan pengguna dengan tenaga kesehatan secara langsung.
  
## High Level System Flow
1. Pengguna memilih gejala yang tersedia pada aplikasi.
2. Sistem menerima gejala yang dipilih pengguna.
3. Sistem memproses gejala berdasarkan basis pengetahuan yang tersedia.
4. Sistem menganalisis gejala untuk menghasilkan informasi awal mengenai kondisi kesehatan.
5. Sistem menampilkan informasi awal mengenai kemungkinan kondisi kesehatan kepada pengguna.

## Main Data Used  
### Data Gejala  
Digunakan sebagai sumber input dalam proses konsultasi awal. Data ini berisi daftar gejala yang dapat dipilih oleh pengguna.

### Data Penyakit  
Digunakan untuk menyediakan informasi penyakit yang dapat membantu pengguna memahami kondisi kesehatan dan penanganan awal yang sesuai. 

### Data Relasi Diagnosis  
Berisikan relasi antara data gejala dan data penyakit yang digunakan dalam proses analisis untuk menghasilkan informasi awal mengenai kemungkinan kondisi kesehatan.
