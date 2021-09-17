# Rangkuman Pertemuan 3

## Kelompok 5 Black Box Testing: Aji, Farid, Syifak

Black box testing adalah metode pengujian perangkat lunak yang digunakan untuk menguji perangkat lunak tanpa mengetahui struktur internal kode atau program.
Pada Black Box Testing dilakukan pengujian yang didasarkan pada detail aplikasi seperti tampilan aplikasi, fitur-fitur yang ada pada aplikasi,
dan kesesuaian alur fungsi dengan bisnis proses yang diinginkan oleh customer.

### Teknik-teknik black box testing :
1. Equivalence Partitioning = Pembagian menjadi beberapa partisi dari proses input data.
2. Boundary Value Analysis = Mencari ada error atau tidak dari luar atau sisi dalam software, minimum, maupun maksimum nilai dari error yang didapat.
3. Decision Table Testing = Pendekatan pengujian dengan mengidentifikasi dua buah output untuk dua kondisi yang berbeda.
4. State Transition Testing  = Menggunakan model ‘state’ pada sebuah diagram transisi dalam melakukan pengujian perangkat lunak.
5. Graph Based Testing = Dapat ditentukan relasi antar object dan test case dapat dibuat menyesuaikan relasi antar object ini untuk menemukan error.
6. Error Guessing  = Pendekatan PPL yang membutuhkan pengalaman dari tim yang melakukan pengujian. 
7. Common Comparison = Membandingkan perangkat lunak yang dibuat atau fitur dari software terhadap perangkat lunak lainnya.

### Kelebihan
1. Tester tidak perlu mempunyai pengetahuan tentang bahasa pemrograman tertentu
2. Pengujian yang dilakukan berdasarkan sudut pandang pengguna 
3. Programmer dan tester memiliki ketergantungan satu sama lain
4. Efisien untuk segmen kode berskala besar
5. Akses kode tidak diperlukan
6. Pemisahan antara perspektif pengguna dan pengembang

### Kekurangan
1. Uji kasus sulit di desain
2. Memiliki pengulangan tes yang sudah dilakukan oleh programmer
3. Beberapa bagian back end tidak diuji sama sekali
4. Cakupan sangat terbatas 
5. Pengujian tidak efisien

### Manfaat
1. Kesederhanaan = Tes mudah dilakukan
2. Kejelasan = Waktu persiapan yang sangat singkat
3. Ketidakberpihakan = Hasil pengujian netral

### Pertanyaan :
1.	Dita : Pada poin ketidakberpihakan dijelaskan mengikuti sudut “pengguna”, tetapi penggunaan satu proses 
tergantung pada pendapat pengembang, bisa dijelaskan maksud dari kalimat tersebut!

    Jawab : Pengujian boleh dari pengguna tapi pengembang sebagai perancang

## Kelompok 7 Pelaporan Bug: Alfin, Fathin, Zalna

Bug adalah keselahan (error), kecatatan (flaw), atau kegagalan (fault) yang mengakibatkan kesalahan dalam perangkat lunak.

### Karakteristik pelaporan bug
1. Objektif = Berdasarkan fakta
2. Spesifik = Secara terperinci atau detail
3. Ringkas  = Jelas dan singkat
4. Dapat diulang (reproducible) = Bisa ditemukan ulang oleh pengembang perangkat lunak
5. Eksplisit = Merujuk kepada hal yang jelas dan dapat diamati
6. Persuasif = Pelaporan yang mempengaruhi pengembang perangkat lunak untuk segera memperbaiki bug yang ditemukan

### Tingkatan bug
1. Severity-1 Errors = Menyebabkan perangkat lunak berhenti berjalan
2. Severity-2 Errors = Menyebabkan kegagalan operasi atau ketidaksesuaian, namun perangkat lunak masih dapat berjalan
3. Severity-3 Errors = Kesalahan yang tidak terduga atau kesalahan yang tidak konsisten
4. Severity-4 Errors = Usualan baru terhadap perangkat lunak

### Pengklasifikasian bug
1. Trivial = Memiliki tingkat kesalahan terendah
2. Minor = Bisa dianggap penting meski tidak berpengaruh besar pada sistem
3. Major = Memberikan pengaruh cukup besar terhadap fungsionalitas sistem

### Status pada bug
1. New = Bug baru untuk ditugaskan ke pengembang
2. Assigned = Sudah ditugaskan kepada pengembang untuk diperbaiki
3. Rejected = Bug ditolak dan dikembalikan ke tester karena pengembang tidak dapat melakukan reproduce
4. Fixed = Bug telah selesai diperbaiki oleh pengembang perangkat lunak
5. Ready to test = Bug sudah selesai diperbaiki dan siap rilis untuk dilakukan pengujian kembali oleh tester
6. Failed retest = Bug masih ditemukan pada tahap pengujian ulang oleh tester
7. Closed = Bug telah selesai diperbaiki dan telah melalui proses pengecekan ulang sehingga status dapat ditutup

### Komponen pelaporan bug
1.	Id bug
2.	Judul bug
3.	Tingkat bug
4.	Status
5.	Deskripsi singkat
6.	Langkah untuk menemukan bug
7.	Hasil yang diharapkan
8.	Hasil yang didapat saat pengujian
9.	Tangkapan layar perangkat lunak
10.	Penguji
11.	Komentar dari penguji

### Pertanyaan :
1.	Fransiska : Apa yang dimaksud probabilitas dan dampak pada tingkatan bug?

    Jawab : Dimensi probabilitas menggambarkan seberapa sering bug muncul pada perangkat lunak. 
    Sedangkan dimensi dampak menggambarkan seberapa besar dampak bug terhadap perangkat lunak baik dari segi teknis maupun proses bisnis yang terjadi.
    Dari dimensi dan tingkatan tersebut, dihasilkan 4 tingkatan bug, yaitu trivial, minor, dan major.

## Kelompok 8 Metriks Pengujian Perangkat Lunak: Dita, Eksa, Dwima
- Makna = Pengukuran kuantitatif yang digunakan untuk memperkirakan kemajuan, kualitas, produktivitas, dan kesehatan proses pengujian perangkat  lunak.
- Tujuan = Untuk meningkatkan efisiensi dan efektivitas dalam proses pengujian software, untuk membantu membuat keputusan yang lebih baik dalam
  proses pengujian software, Untuk menyediakan data yang dapat diandalkan dalam proses pengujian.

### Tipe metriks pengujian perangkat lunak
1. Process Metrics = Memperbaiki tahap SDLC
2. Product Metrics = Mengukur berbagai karakteristik produk perangkat lunak
3. Project Metrics = Berpacu pada orang-orang dalam team tester yang bekerja sama dengan alat yang digunakan untuk mengukur seberapa bagus peningkatan efisiensi tim

### Life cycles of software testing metriks
1. Analysis
2. Communicate
3. Evaluation
4. Reports

### How to calculate test metrics
1. Identifikasi software testing proses utama yang akan diukur 
2. Tester menggunakan data untuk bahan dasar penentuan metriks
3. Menentukan informasi yang harus diikuti, frekuensi pelacakan, dan orang yang bertanggung jawab atas tugas tersebut
4. Penghitungan, pengelolaan, dan interpretasi yang efektif dari metriks yang ditentukan
5. Identifikasi area peningkatan tergantung pada interpretasi metriks yang ditentukan

### Jenis metriks
1. Rework effort Ratio
2. Requirement Creep 
3. Schedule Variance 
4. Cost of finding a defect in testing
5. Schedule slippage
6. Passed Test Cases Percentage
7. Failed Test Cases Percentage
8. Blocked Test Cases Percentage
9. Fixed Defects Percentage
10. Accepted Defects Percentage
11. Defects Deferred Percentage
12.	Critical Defects Percentage
13.	Average time for a development team to repair defects
14.	Number of tests run per time period
15.	Test design efficiency
16.	Test review efficiency
17.	Bug find rote or Number of defects per test hour

### Pertanyaan : 
1.	Thalia : Berikan satu contoh perhitungan dari jenis metriks!

    Jawab :  Rework Effort Ratio = (Actual rework  efforts spent in that phase/ total actual efforts spent in that phase) X 100

    Total Effort for Rework = 10 
    Total Effort for Project = 200 
    Rework Effort %  = (10/200)*100= 5 %
    rumus untuk menghitung rasio effort dari pengerjaan ulang suatu perangkat lunak.

2.	Ardila : Apakah semua rumus metriks digunakan dalam pengujian?

    Jawab : Tidak harus semua, karena dalam pengujian perangkat lunak tidak pasti semua permasalahan ditemukan. 
    Jadi semisal ketika pengujian ditemukan 3 permasalahan, hanya 3 metriks yg bisa digunakan untuk menghitung penyelesaian dari permasalahan.
    
## Kelompok 6 Skenario Pengujian dan Kasus Uji: Devi, Fitri, Zhabiyan

### Skenario Pengujian (Test Scenario)
Sebuah aktivitas untuk menentukan hal-hal apa saja yang perlu untuk diuji.

### Komponen-komponen Skenario Pengujian :
1. ID skenario pengujian = Untuk mengenali indeks nomor dari sebuah skenario pengujian perangkat lunak
2. ID kebutuhan = Sebagai identifier pada dokumen spesifikasi kebutuhan perangkat lunak
3. Deskripsi skenario pengujian = Menggambarkan pengujian yang akan dilakukan dalam bentuk kalimat yang singkat, padat, dan jelas

### Kasus Uji (Test Case)
Test case menjadi bentuk detail dari skenario pengujian.

### Komponen-komponen test case :
1.	ID Test Case
2.	ID skenario pengujian
3.	Test case/kasus uji
4.	Kondisi pra (pre-condition)
5.	Langkah pengujian (test steps)
6.	Data uji (test data)
7.	Hasil yang diharapkan (expected result)
8.	Kondisi pasca (post condition)
9.	Hasil yang terjadi (actual result)
10.	Status

### Kegunaan Test Case :
1.	Untuk melakukan testing, kesesuaian suatu komponen terhadap spesifikasi (Black Box Testing).
2.	Untuk melakukan testing, kesesuaian suatu komponen terhadap desain (White Box Testing).

### Yang Harus Diperhatikan Dalam Membuat Test Case :
1.	Membuat test case dengan sederhana dan transparan
2.	Membuat test case dengan End User in Mind
3.	Hindari Pengulangan Kasus Uji
4.	Test Case Harus Dapat Diidentifikasi

## Kelompok 3 Pengujian White Box: Khoirul, Irul, Hamdan

White box testing adalah testing yang berorientasi pada menganalisa kode program dan logika dari perangkat lunak yang dibuat.
