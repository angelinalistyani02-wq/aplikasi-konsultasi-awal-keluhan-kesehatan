# Processing Logic  

## Document Purpose  
Dokumen ini bertujuan menjelaskan logika pemrosesan data yang dilakukan sistem untuk menghasilkan informasi. 

## Processing Logic Oveerview  
Logika pemrosesan sistem dibangun melalui hubungan logis antar data. Data Gejala dihubungkan dengan Data Relasi Diagnosis yang berperan sebagai Basis Pengetahuan untuk menghasilkan diagnosis. Sementara itu, Data Penyakit digunakan untuk menyediakan informasi detail berdasarkan penyakit yang dipilih pengguna.  

## Logika Pemrosesan Konsultasi Awal  
### Input  
Sistem menerima Data Gejala sebagai masukan proses konsultasi awal. Data Gejala tersebut digunakan oleh sistem sebagai dasar untuk melakukan identifikasi penyakit. 

### Processing  
Identifikasi penyakit dilakukan dengan memanfaatkan hubungan antara Data Gejala dan Data Relasi Diagnosis dalam sistem. Data Relasi Diagnosis dalam sistem berperan sebagai Basis Pengetahuan yang menghubungkan gejala dengan penyakit untuk mendukung proses identifikasi. 
Dalam pemanfaatan Basis Pengetahuan, Data Gejala digunakan sebagai dasar untuk menganalisis kecocokan gejala dengan penyakit. Hasil analisis tersebut kemudian digunakan untuk menghasilkan diagnosis. 

### Data Preparation  
Diagnosis mempresentasikan penyakit yang diidentifikasi berdasarkan hasil pemrosesan. Selanjutnya, diagnosis tersebut digunakan dalam penyajian kepada pengguna.  

## Logika Penyajian Informasi Penyakit  
### Input   
Pengguna memilih penyakit yang diinginkan pada sistem. Pilihan tersebut menjadi dasar bagi sistem untuk menggunakan Data Penyakit sebagai sumber informasi penyakit. 

### Processing 
Sistem memuat dan menyusun Data Penyakit agar dapat digunakan dalam proses penyajian informasi penyakit. Data Penyakit yang dipilih kemudian digunakan untuk menyediakan informasi detail penyakit. 

### Output  
Informasi detail penyakit menjadi output dari pemrosesan yang dapat digunakan untuk penyajian kepada pengguna.

