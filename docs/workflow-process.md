# Workflow Process

## Document Purpose 
Dokumen ini bertujuan mendokumentasikan proses operasional utama dalam sistem, sehingga pembaca dapat memahami bagaimana pengguna dan administrator berinteraksi dengan sistem untuk mencapai tujuan tertentu. 

## Process Summary  
Proses operasional dalam sistem saling berkaitan untuk mendukung penyediaan informasi kesehatan awal kepada pengguna. Proses pemeliharaan data oleh administrator memastikan informasi penyakit dan gejala tetap tersedia dan mutakhir, sedangkan proses yang dilakukan pengguna memanfaatkan data tersebut untuk memperoleh informasi penyakit dan melakukan konsultasi awal berdasarkan gejala yang dipilih.  

### Proses Penyediaan Informasi Penyakit  
**Purpose**   
Menyediakan akses terhadap informasi penyakit yang tersedia dalam sistem sehingga pengguna dapat memperoleh pemahaman awal mengenai kondisi kesehatan tertentu. 

**Actors**  
Pengguna.  

**Preconditions**  
Pengguna telah mengakses aplikasi.  

**Workflow Steps:**  
1. Pengguna mengakses menu Daftar Penyakit.
2. Sistem menampilkan daftar penyakit yang tersedia.
3. Pengguna memilih salah satu penyakit.
4. Sistem menampilkan informasi detail penyakit.

**Expected Outcome**  
Sistem menampilkan informasi detail mengenai penyakit yang dipilih kepada pengguna. 

### Proses Konsultasi Pengguna  
**Purpose**  
Membantu pengguna memperoleh informasi awal mengenai kemungkinan kondisi kesehatan berdasarkan gejala yang dipilih. 

**Actors**  
Pengguna. 

**Preconditions**    
Data gejala, data penyakit, dan relasi gejala yang terkait telah tersedia dalam sistem. 

**Workflow Steps:**  
1. Pengguna mengakses menu konsultasi.
2. Sistem menampilkan daftar gejala yang tersedia.
3. Pengguna memilih gejala sesuai dengan kondisi yang dirasakan.
4. Pengguna mengirimkan pilihan gejala untuk melanjutkan proses konsultasi.
5. Sistem memproses gejala yang dipilih.
6. Sistem menampilkan hasil konsultasi pengguna.

**Alternative Flow (Diagnosa Ulang) :**  
1. Pengguna memilih untuk melakukan diagnosa ulang.
2. Sistem menghapus gejala yang dipilih sebelumnya.
3. Pengguna kembali ke tahap pemilihan gejala.
4. Proses konsultasi berlangsung kembali dari tahap pemilihan gejala.

**Expected Outcome**  
Pengguna memperoleh hasil konsultasi berdasarkan gejala yang dipilih. 

### Proses Pemeliharaan Data Penyakit  
**Purpose**  
Memastikan informasi penyakit yang digunakan dalam sistem tetap tersedia dan terbarui untuk mendukung penyampaian informasi kepada pengguna.

**Actors**  
Administrator.  

**Preconditions**  
Administrator telah berhasil login ke sistem.

**Workflow Steps:**  
1. Administrator mengakses menu Data Penyakit.
2. Sistem menampilkan data penyakit yang tersedia.
3. Administrator melakukan pemeliharaan data penyakit sesuai kebutuhan.
4. Sistem menyimpan perubahan data penyakit.
5. Sistem menampilkan data penyakit yang telah diperbarui.

**Expected Outcome**  
Data penyakit dalam sistem tetap terpelihara dan dapat digunakan untuk mendukung penyampaian informasi kepada pengguna.

### Proses Pemeliharaan Data Gejala  
**Purpose**  
Memastikan informasi gejala yang digunakan dalam proses konsultasi tetap tersedia dan terbarui. 

**Actors**  
Administrator.

**Preconditions**  
Administrator telah berhasil melakukan login ke sistem. 

**Workflow Steps:**  
1. Administrator mengakses menu Data Gejala.
2. Sistem menampilkan data gejala yang tersedia.
3. Administrator melakukan pemeliharaan data gejala sesuai kebutuhan.
4. Sistem menyimpan perubahan data gejala.
5. Sistem menampilkan data gejala yang telah diperbarui.

**Expected Outcome**  
Data gejala dalam sistem tetap terpelihara dan dapat digunakan dalam proses konsultasi.  
