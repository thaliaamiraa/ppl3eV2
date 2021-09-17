# Rangkuman Pertemuan 3

## -----Kelompok 5 : Black Box Testing-----

Black box testing adalah metode pengujian perangkat lunak yang digunakan untuk menguji perangkat lunak tanpa mengetahui struktur internal kode atau program. Pada Black Box Testing dilakukan pengujian yang didasarkan pada detail aplikasi seperti tampilan aplikasi, fungsi-fungsi yang ada pada aplikasi, dan kesesuaian alur fungsi dengan bisnis proses yang diinginkan oleh customer. metode ini bertujuan untuk memeriksa apakah perangkat lunak atau aplikasi berfungsi dengan baik, dan melayani penggunanya secara efisien.

### Teknik-teknik black box testing :
-	Equivalence Partitioning -> melakukan pembagian menjadi beberapa partisi dari input data.
-	Boundary Value Analysis -> adakah error dari luar atau sisi dalam software, minimum, maupun maksimum nilai dari error yang didapat.
-	Decision Table Testing -> teknik pendekatan pengujian dengan mengidentifikasi dua buah output untuk dua kondisi yang berbeda.
-	State Transition Testing  -> menggunakan model ‘state’ pada sebuah diagram transisi dalam melakukan pengujian perangkat lunak.
-	Graph Based Testing -> dapat ditentukan relasi antar object dan test case dapat dibuat menyesuaikan relasi antar object ini untuk menemukan error.
- Error Guessing  -> sebuah pendekatan pengujian perangkat lunak yang membutuhkan pengalaman dari personil yang melakukan pengujian. 
-	CommonComparison -> teknik yang membandingkan secara umum perangkat lunak yang dibuat atau fitur dari software terhadap perangkat lunak lain yang mirip. 

### Kelebihan
-	Penguji tidak perlu memiliki pengetahuan tentang bahasa pemrograman tertentu
-	Pengujian yang dilakukan berdasarkan sudut pandang user 
-	Programmer dan tester memiliki ketergantungan satu sama lain
-	Efisien untuk segmen kode besar
-	Akses kode tidak diperlukan
-	Pemisahan antara perspektif pengguna dan pengembang

### Kekurangan
•	Uji kasus sulit di desain
•	Memiliki pengulangan tes yang sudah dilakukan oleh programmer
•	Beberapa bagian back end tidak diuji sama sekali.
•	Cakupan terbatas 
•	Pengujian tidak efisien 

### Manfaat
-	Kesederhanaan -> tes mudah dilakukan
-	Kejelasan -> waktu persiapan yang sangat singkat
-	Ketidakberpihakan -> Hasil pengujian netral

### Pertanyaan :
1.	Dita : pada poin ketidakberpihakan dijelaskan mengikuti sudut “pengguna”, tetapi penggunaan satu proses tergantung pada pendapat pengembang, bisa dijelaskan maksud dari kalimat tersebut !
Jawab : Pengujian boleh dari pengguna tapi pengembang sebagai perancang

## -----Kelompok 7 : Pelaporan Bug-----

Bug -> keselahan (error), kecatatan (flaw), atau kegagalan (fault) yang mengakibatkan kesalahan dalam perangkat lunak.

### Karakteristik pelaporan bug
1.	Objektif -> berdasarkan fakta
2.	Spesifik -> secara terperinci
3.	Ringkas  -> jelas dan singkat
4.	Dapat diulang (reproducible) -> bisa ditemukan ulang oleh pengembang perangkat lunak
5.	Eksplisit -> merujuk kepada hal yang jelas dan dapat diamati
6.	Persuasif -> pelaporan yang mempengaruhi pengembang perangkat lunak untuk segera memperbaiki bug yang ditemukan.

### Tingkatan bug
1.	Severity-1 Errors -> menyebabkan perangkat lunak berhenti berjalan
2.	Severity-2 Errors -> Menyebabkan kegagalan operasi atau ketidak sesuaian namun perangkat lunak masih dapat berjalan
3.	Severity-3 Errors -> Kesalahan yang tidak terduga atau kesalahan yang tidak konsisten
4.	Severity-4 Errors -> Usualan baru terhadap perangkat lunak

### Pengklasifikasian bug
1.	Trivial : lever terendah yang memiliki tingkat kesalahan terendah
2.	Minor : lever menengah yang bisa dianggap penting meski tidak berpengarung besar
3.	Major : Kesalahan yang mmeberikan pengaruh cukup besar terhadap fungsionalitas system.

### Status pada bug
1.	New -> status untuk bug baru untuk ditugaskan ke pengembang
2.	Assigned -> sudah ditugaskan kepada pengembang untuk diperbaiki
3.	Rejected -> Bug ditolak dan dikembalikan ke penguji karena pengembang tidak dapat melakukan reproduce berdasarkan langkah-langkah yang diberikan oleh penguji.
4.	Fixed -> Bug telah selesai diperbaiki oleh pengembang perangkat lunak
5.	Ready to test -> Bug sudah selesai diperbaiki dan rilis untuk dilakukan pengujian kembali oleh penguji.
6.	Failed retest -> Bug masih ditemukan pada tahap pengujian ulang oleh penguji.
7.	Closed -> Bug telah selesai diperbaiki dan telah melalui proses pengecekan ulang sehingga status dapat ditutup.

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
Jawab : Dimensi probabilitas menggambarkan seberapa sering bug muncul pada perangkat lunak. Sedangkan dimensi dampak menggambarkan seberapa besar dampak bug terhadap perangkat lunak baik dari segi teknis maupun proses bisnis yang terjadi. Dari dimensi dan tingkatan tersebut, dihasilkan 4 tingkatan bug, yaitu trivial, minor, dan major.

## -----Kelompok 8 : Metriks Pengujian Perangkat Lunak-----

### Makna & tujuan
-	Makna -> pengukuran kuantitatif yang digunakan untuk memperkirakan kemajuan, kualitas, produktivitas, dan  kesehatan proses pengujian perangkat  lunak.
-	Tujuan -> Untuk meningkatkan efisiensi dan efektivitas dalam proses pengujian software, untuk membantu membuat keputusan yang lebih baik dalam proses pengujian software, Untuk menyediakan data yang dapat diandalkan dalam proses pengujian.

### Tipe metric pengujian perangkat lunak
1.	Process Metrics -> memperbaiki tahap SDLC.
2.	Product Metrics -> mengukur berbagai karakteristik produk perangkat lunak.
3.	Project Metrics -> berpacu pada orang-orang dalam team tester yang bekerjasama dengan alat yang digunakan untuk mengukur seberapa bagus peningkatan efisiensi tim.

### Life cycles of software testing metrics
1.	Analysis
2.	Communicate
3.	Evaluation
4.	Reports

### How to calculate test metrics
1.	Identifikasi software testing process utama yang akan diukur 
2.	Tester menggunakan data untuk bahan dasar penentuan metrik
3.	Menentukan informasi yang harus diikuti, frekuensi pelacakan dan orang yang bertanggung jawab atas tugas tersebut
4.	Penghitungan, pengelolaan, dan interpretasi yang efektif dari metrik yang ditentukan
5.	Identifikasi area peningkatan tergantung pada interpretasi metrik yang ditentukan

### Jenis metriks
1.	Rework effort Ratio
2.	Requirement Creep 
3.	Schedule Variance 
4.	Cost of finding a defect in testing
5.	Schedule slippage
6.	Passed Test Cases Percentage
7.	Failed Test Cases Percentage
8.	Blocked Test Cases Percentage
9.	Fixed Defects Percentage
10.	Accepted Defects Percentage
11.	Defects Deferred Percentage
12.	Critical Defects Percentage
13.	Average time for a development team to repair defects
14.	Number of tests run per time period
15.	Test design efficiency
16.	Test review efficiency
17.	Bug find rote or Number of defects per test hour

### Pertanyaan : 
1.	Thalia : berikan satu contoh perhitungan dari jenis matriks!
Jawab :  Rework Effort Ratio = (Actual rework  efforts spent in that phase/ total actual efforts spent in that phase) X 100

Total Effort for Rework = 10 
Total Effort for Project = 200 
Rework Effort %  = (10/200)*100= 5 %
rumus untuk menghitung rasio effort dari pengerjaan ulang suatu perangkat lunak.

2.	Ardila : apakah semua rumus metriks digunakan dalam pengujian?
Jawab : tidak harus semua, karena dalam pengujian perangkat lunak tidak mesti semua permasalahan di temukan. jadi misal ketika pengujian menemukan 3 permasalahan, hanya 3 metrik yg bisa digunakan untuk menghitung penyelesaian dari permasalahan.

## -----Kelompok 6 : Skenario Pengujian dan Kasus Uji-----

### Skenario Pengujian (Test Scenario)
Sebuah aktivitas untuk menentukan hal-hal apa saja yang perlu untuk diuji.

### Komponen- komponen Skenario Pengujian :
1.	ID skenario pengujian -> untuk mengenali indeks nomor dari sebuah skenario pengujian perangkat lunak
2.	ID kebutuhan -> sebagai identifier pada dokumen spesifikasi kebutuhan perangkat lunak.
3.	Deskripsi skenario pengujian -> menggambarkan pengujian yang akan dilakukan dalam bentuk kalimat yang singkat, padat, dan jelas.

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
1.	Untuk melakukan testing kesesuaian suatu komponen terhadap spesifikasi ( Black Box Testing ).
2.	Untuk melakukan testing, kesesuaian suatu komponen terhadap desain ( White Box Testing ).

### Yang Harus Diperhatikan Dalam Membuat Test Case :
1.	Membuat test case dengan sederhana dan transparan
2.	Membuat test case dengan End User in Mind
3.	Hindari Pengulangan Kasus Uji
4.	Test Case Harus Dapat Diidentifikasi

## -----Kelompok 3 : Pengujian White Box-----
White box testing -> testing yang berorientasi pada menganalisa kode program dan logika dari perangkat lunak yang dibuat.

### Statement Coverage 
Rumus : (Jumlah statement yang dieksekusi/jumlah statement) * 100

### Branch Coverage
Dimulai dengan mengubah kode program menjadi sebuah flowchart

### Path Coverage
Menguji semua path yang ada di program dan semua jalur pada algoritma.

