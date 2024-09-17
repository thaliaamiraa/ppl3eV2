# Pertemuan 03

# Bab 5 Blackbox Testing

## Rangkuman Blackbox Testing
Black Box Testing atau yang lebih sering dikenal dengan sebutan pengujian fungsional merupakan metode pengujian perangkat lunak yang 
digunakan untuk menguji perangkat lunak tanpa mengetahui struktur internal kode atau program. Pada Black Box Testing ini dilakukan 
pengujian yang didasarkan pada detail aplikasi seperti tampilan aplikasi, fungsi-fungsi yang ada pada aplikasi, dan kesesuaian alur 
fungsi dengan bisnis proses yang diinginkan oleh customer.

## Teknik-Teknik Black-box Testing
   
   1. Equivalence Partitioning
   
      Cara kerja teknik ini adalah dengan melakukan partition atau pembagian menjadi beberapa partisi dari input data.

   2. Boundary Value Analysis
   
      Teknik ini lebih fokus kepada boundary, adakah error dari luar atau sisi dalam software, minimum, maupun maksimum nilai dari error yang didapat.

   3. Decision Table Testing 
   
      Decision Table merupakan teknik pendekatan pengujian dengan mengidentifikasi dua buah output untuk dua kondisi yang berbeda (true/false).

   4. State Transition Testing 
   
      Teknik State Transition menggunakan model ‘state’ pada sebuah diagram transisi dalam melakukan pengujian perangkat lunak. Sebuah ‘state’ 
      menggambarkan sebuah kondisi yang akan terjadi ketika sistem diuji.

   5. Graph Based Testing 
   
      Setiap aplikasi biasanya dibangun menggunakan beberapa object. Setiap object diidentifikasikan sebagai graph. Dari object graph ini, 
      dapat ditentukan relasi antar object dan test case dapat dibuat menyesuaikan relasi antar object ini untuk menemukan error.

   6. Error Guessing 
   
      Teknik Error Guessing adalah sebuah pendekatan pengujian perangkat lunak yang membutuhkan pengalaman dari personil yang melakukan pengujian. 

   7. CommonComparison 
  
      Common comparison adalah teknik yang membandingkan secara umum perangkat lunak yang dibuat atau fitur dari software terhadap perangkat lunak lain yang mirip.

## Kelebihan dari Black-box Testing
   •Penguji tidak perlu memiliki pengetahuan tentang bahasa pemrograman tertentu
   •Pengujian yang dilakukan berdasarkan sudut pandang user agar dapat mengungkapkan konsistensi atau ambiguitas dalam spesifikasi.
   •Programmer dan tester memiliki ketergantungan satu sama lain.

## Kekurangan Black-box Testing
   •Uji kasus sulit di desain tanpa spesifikasi yang jelas
   •Kemungkinan memiliki pengulangan tes yang sudah dilakukan oleh programmer
   •Beberapa bagian back end tidak diuji sama sekali.


# Bab 7 Pelaporan Bug
## Rangkuman Pelaporan Bug
  Pelaporan bug dilakukan guna menemukan defect pada perangkat lunak. Setelah defect ditemukan kemudian diperbaiki, maka dari itu 
  kualitas dari pelaporan bug juga menjadi satu elemen yang penting dalam pelaporan bug. Berikut karakteristik pelaporan bug:

## Karakteristik Pelaporan Bug:
•	Objektif : berdasarkan fakta
•	Spesifik : dilakukan per bug
•	Ringkas : jelas, ringkas
•	Persuasif : mempengaruhi pengembang perangkat lunak untuk segera memperbaiki

## Tingkatan Bug:
•	Severity-1 : perangkat lunak berhenti berjalan
•	Severity-2 : kegagalan operasi namun perangkat lunak tetap berjalan
•	Severity-3 : kesalahan tidak terduga
•	Severity-4 : usulan baru terhadap perangkat lunak

## Status Bug:
•	New : bug baru dan menunggu
•	Assigned : bug ditugaskan ke pengembang untuk diperbaiki
•	Rejected : bug ditolak dan dikembalikan ke penguji
•	Fixed : bug selesai diperbaiki oleh pengembang perangkat lunak 
•	Ready to test : bug rilis untuk dilakukan pengujian kembali
•	Failed re-test : bug masih ditemukan pada tahap pengujian
•	Closed : bug selesai diperbaiki setelah pengujian ulang 

## Komponen Pelaporan Bug:
•	ID
•	Judul
•	Tingkatan
•	Status
•	Deskripsi singkat
•	Langkah untuk menemukan bug
•	Hasil diharapkan
•	Hasil didapat
•	Screenshoot
•	Penguji

## Materi tambahan dari mahasiswa
Pengklasifikasian bug juga dapat dilakukan secara relatif berdasarkan dimensi probabilitas (probability) dan dampak (impact)Dimensi 
probabilitas menggambarkan seberapa sering bug muncul pada perangkat lunak. Sedangkan dimensi dampak menggambarkan seberapa besar dampak bug
terhadap perangkat lunak baik dari segi teknis maupun proses bisnis yang terjadi. Dari dimensi dan tingkatan tersebut, dihasilkan 4 tingkatan bug, yaitu 
trivial, minor, dan major.



# Bab 8 Metriks Pengujian Perangkat Lunak
## Rangkuman Bab 8
Metriks Pengujian Perangkat Lunak adalah pengukuran kuantitatif yang digunakan untuk memperkirakan kemajuan, kualitas, produktivitas, dan  
kesehatan proses pengujian perangkat  lunak.

## Tujuan dari Metriks Pengujian Perangkat Lunak
1.	Untuk meningkatkan efisiensi dan efektivitas dalam proses pengujian software
2.	Untuk membantu membuat keputusan yang lebih baik dalam proses pengujian software
3.	Untuk menyediakan data yang dapat diandalkan dalam proses pengujian

## Tipe Metriks Pengujian
a.	Process Metrics : untuk memperbaiki efisiensi dari tahap SDLC (Software Development Life Cycle). Selain itu, untuk mengukur berbagai 
karakteristik proses pengembangan perangkat lunak

b.	Product Metrics : untuk mengukur berbagai karakteristik produk perangkat lunak. Dimana pengukuran tersebut bergantung pada ukuran dan 
kompleksitas perangkat lunak serta kualitas dan keandalan perangkat lunak.

c.	Project Metrics : berpacu pada orang-orang dalam team tester yang bekerjasama dengan alat yang digunakan untuk mengukur seberapa 
bagus peningkatan efisiensi tim.

## Pertanyaan Bab 8 Metriks Pengujian Perangkat Lunak
•	Thalia : apa yang dimaksud rework effort ratio dan contoh dari jenis metriks?

jawaban Rework Effort Ratio = (Actual rework efforts spent in that phase/ total actual efforts spent in that phase) X 100. rumus untuk menghitung 
rasio effort dari pengerjaan ulang suatu perangkat lunak.

•	Ardila : Apakah semua jenis metrik diitung dalam pengujian

jawaban Hanya menggunakan metriks yang dibutuhkan saja


# Bab 6 – Pengujian Skenario dan Kasus Uji
## A. Skenario Pengujian
Skenario pengujian dalam ranah pengujian perangkat lunak adalah sebuah aktivitas untuk menentukan hal-hal apa saja yang perlu untuk diuji. 
Komponen-komponen skenario PPL :
1.	ID Skenario Pengujian yaitu Digunakan untuk mengenali indeks nomor dari sebuah skenario ppl.
2.	ID Kebutuhan yaitu Digunakan sebagai identifier dokumen spesifikasi kebutuhan perangkat lunak.
3.	Deskripsi skenario pengujian Gambaran pengujian dalam bentuk kalimat secara singkat.

## B. Kasus Uji
Kasus uji atau test case adalah tentang bagaimana kita melakukan pengujian perangkat lunak. Secara singkat, test case menjadi bentuk detail dari 
skenario pengujian. Artinya setiap poin skenario pengujian akan dapat diderivasi menjadi beberapa test case. Komponen-komponen pada kasus uji atau test case.

1.	ID Test Case
ID test case berfungsi untuk memberikan identifier pada setiap test case yang dibuat. Tidak ada format penomoran yang baku, namun yang diperlukan 
adalah penomoran yang jelas serta disepakati bersama oleh tim pengembang perangkat lunak.
2.	ID skenario pengujian
Komponen ini penting untuk dimasukkan karena menjadi acuan dalam membuat test case. Pada poin ini, jika tidak menggunakan ID skenario pengujian, 
dapat menggunakan deskripsi skenario pengujian.
3.	Test case/kasus uji
Komponen ini berisi deskripsi kasus uji atau test case yang akan dilakukan dan dibuat dengan kalimat yang singkat, padat, dan jelas.
4.	Kondisi pra (pre-condition)
Komponen ini menggambarkan kondisi yang harus ada sebelum dilakukan langkah-langkah dalam kasus uji.
5.	Langkah pengujian (test steps)
Komponen ini berisi langkah-langkah pelaksanaan pengujian secara detail. langkah dapat digambarkan dengan kalimat yang spesifik, karena akan menjadi
aktivitas yang dilakukan ketika pengujian dilakukan.
6.	Data uji (test data)
Komponen ini berisi data yang diperlukan untuk dimasukkan oleh penguji pada setiap langkah yang dilakukan. Data uji ini dapat dikosongkan apabila 
dalam langkah pengujian tidak memerlukan data tertentu.
7.	Hasil yang diharapkan (expected result)
Komponen ini berisi kalimat yang menggambarkan hasil yang diharapkan dalam melakukan sebuah kasus uji. Komponen ini menjadi acuan bahwa sebuah 
pengujian dalam kasus uji dapat dinyatakan berhasil atau gagal.
8.	Kondisi pasca (post condition)
Komponen ini berisi gambaran kondisi yang seharusnya terjadi setelah pengujian dilakukan.
9.	Hasil yang terjadi
Gambaran hasil yang terjadi Ketika pengujian dilakukan.
10.	Status
Kesesuaian antara ecpected result dan actial result akan menghasilkan kesimpulan berupa status (berhasil/gagal).

# Bab 3 White Box Testing
## Rangkuman Bab 3 White Box Testing
White Box Testing atau glass box testing merupakan testing yang berorientasi pada menganalisa kode program dan logika dari perangkat lunak yang 
dibuat Di bawah ini jenis-jenis White Box Testing :

•	Statement Coverage Metode untuk memvalidasi bahwa kode program yang ditulis di eksekusi paling tidak sekali sesuai dengan logika kode program yang berjalan

•	Branch Coverage Langkah yang dibutuhkan untuk mealkukan pengujian branch coverage dimuali dengan mengubah kode program menjadi sebuah flowchart

•	Path Covergae Menguji semua path yang ada di program dan semua jalur pada algoritma. Pada program setidaknya dieksekusi satu kali tes
