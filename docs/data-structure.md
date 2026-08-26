# Data Structure

## 1. Document Purpose  
Dokumen ini bertujuan untuk memberikan gambaran mengenai data yang digunakan dalam sistem, fungsi masing - masing data, serta hubungan antar data. 

## 2. Data Structure Overview  
Sistem ini menggunakan tiga jenis data yaitu Data Penyakit, Data Gejala, dan Data Relasi Diagnosis. Masing - masing data memiliki peran yang berbeda dalam sistem. Data Penyakit digunakan sebagai sumber informasi penyakit yang ditampilkan kepada pengguna, Data Gejala digunakan sebagai input dalam proses konsultasi, sedangkan Data Relasi Diagnosis digunakan untuk menghubungkan Data Gejala dan Data Penyakit dalam proses konsultasi. Ketiga data tersebut saling mendukung proses konsultasi dan penyampaian informasi kepada pengguna. 

## 3. Struktur Data Penyakit  
**Purpose**  
Data Penyakit digunakan sebagai sumber informasi penyakit yang ditampilkan kepada pengguna. 

**Stored Information**  
- Nama Penyakit digunakan sebagai identitas penyakit yang ditampilkan kepada pengguna.
- Deskripsi Penyakit digunakan untuk memberikan gambaran umum mengenai penyakit.
- Penanganan Awal Penyakit digunakan untuk menyediakan informasi penanganan awal yang dapat dipahami pengguna.

**System Usage**  
1. Digunakan untuk menampilkan informasi penyakit pada fitur Informasi Penyakit.
2. Digunakan untuk menampilkan informasi penyakit berdasarkan hasil analisis gejala pada fitur Hasil Konsultasi.

**Data Relationships**  
Data Penyakit terhubung dengan Data Gejala melalui Data Relasi Diagnosis untuk mendukung proses konsultasi. 

## 4. Struktur Data Gejala  
**Purpose**  
Data Gejala digunakan sebagai daftar gejala yang tersedia untuk dipilih pengguna saat melakukan konsultasi.  

**Stored Information**  
- Kode Gejala digunakan sebagai identitas untuk membedakan setiap gejala yang tersimpan dalam sistem.
- Nama Gejala digunakan untuk menampilkan pilihan gejala yang dapat dipilih oleh pengguna saat melakukan konsultasi.
- Bobot Gejala merupakan atribut Data Gejala yang digunakan sistem sebagai nilai masukan dalam perhitungan diagnosis.

**System Usage**  
1. Menampilkan daftar gejala pada fitur Konsultasi Gejala.
2. Menyediakan daftar gejala yang dapat dipilih pengguna dalam proses konsultasi.

**Data Relationships**  
Data Gejala terhubung dengan Data Penyakit melalui Data Relasi Diagnosis untuk mendukung proses konsultasi. 

## 5. Struktur Data Relasi Diagnosis  
**Purpose**  
Data Relasi Diagnosis digunakan sebagai basis pengetahuan yang menghubungkan Data Gejala dan Data Penyakit.  

**Stored Information**  
1. Relasi Penyakit digunakan untuk menunjukkan penyakit yang berhubungan dengan gejala tertentu dalam basis pengetahuan diagnosis.
2. Relasi Gejala digunakan untuk menunjukkan gejala yang berhubungan dengan penyakit tertentu dalam basis pengetahuan diagnosis.
3. Nilai Belief digunakan sebagai tingkat keyakinan pakar terhadap hubungan antara penyakit dan gejala.

**System Usage**  
1. Menyediakan basis pengetahuan yang digunakan sistem dalam proses konsultasi.

**Data Relationships**  
Data Relasi Diagnosis menghubungkan Data Penyakit dengan Data Gejala dalam sistem. 

## 6. Gambaran Struktur Data  
Bagian ini menunjukkan representasi visual yang menunjukkan struktur data utama dalam sistem.

<p align="center">
  <img src="/assets/structure-data-diagram.png" width="600">
</p>

<p align="center">
  <em>Gambaran Struktur Data</em>
</p>

Diagram di atas menunjukkan struktur data utama dalam sistem. Dalam struktur tersebut, Data Relasi Diagnosis menjadi penghubung antara Data Penyakit dan Data Gejala sehingga membentuk basis pengetahuan yang digunakan oleh sistem. 
