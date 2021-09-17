# Pertemuan 3

## Bab 5 – Black Box Testing

-	Black box testing : pengujian program perangkat lunak yg lengkap dan reintegrasi.
-	Black Box Testing disebut pengujian fungsional merupakan metode pengujian perangkat lunak yang digunakan untuk menguji perangkat lunak tanpa mengetahui struktur internal kode atau program. 
-	Metode Black Box Testing ini bertujuan untuk memeriksa, setelah tahap akhir proyek, apakah perangkat lunak atau aplikasi berfungsi dengan baik, dan melayani penggunanya secara efisien.

Teknik-teknik black box testing :
1.	Equivalence Partitioning

    Cara kerja teknik ini adalah dengan melakukan partition atau pembagian menjadi beberapa partisi dari input data.

2.	Boundary Value Analysis
    
    Lebih focus ke boundary.

3.	Decision Table Testing

    Teknik pendekatan pengujian dengan mengidentifikasi dua buah output untuk dua kondisi yang berbeda (true/false).

4.	State Transition Testing

    menggunakan model ‘state’ pada sebuah diagram transisi dalam melakukan pengujian perangkat lunak.

5.	Graph Based Testing 

    dibangun menggunakan beberapa object. Setiap object diidentifikasikan sebagai graph.

6.	Error Guessing

    sebuah pendekatan pengujian perangkat lunak yang membutuhkan pengalaman dari personil yang melakukan pengujian.

7.	Common Comparison

    teknik yang membandingkan secara umum perangkat lunak yang dibuat atau fitur dari software terhadap perangkat lunak lain yang mirip.

    Kekurangan Black Box Testing

    •	Uji kasus sulit di desain tanpa spesifikasi yang jelas

    •	Kemungkinan memiliki pengulangan tes yang sudah dilakukan oleh programmer

    •	Beberapa bagian back end tidak diuji sama sekali.

    •	Cakupan terbatas karena hanya sebagian kecil dari skenario pengujian yang dilakukan

    •	Pengujian tidak efisien karena keberuntungan tester dari pengetahuan tentang perangkat lunak internal

    **Petanyaan :**

    Dita : maksud dari sudut pandang ketidakpihakan antara pengguna dan pengembang  jawaban pengujian boleh dari pengguna tapi pengembang sebagai perancang


## Bab 6 – Pengujian Skenario dan Kasus Uji

A.	Skenario Pengujian 
    
Skenario pengujian dalam ranah pengujian perangkat lunak adalah sebuah aktivitas untuk menentukan hal-hal apa saja yang perlu untuk diuji. Komponen-komponen skenario PPL :

1.	ID Skenario Pengujian 
Digunakan untuk mengenali indeks nomor dari sebuah skenario ppl.

2.	ID Kebutuhan
Digunakan sebagai dokumen spesifikasi kebutuhan perangkat lunak.

3.	Deskripsi skenario pengujian
Gambaran pengujian dalam bentuk kalimat secara singkat.

B.	Kasus Uji

Kasus uji atau test case adalah tentang bagaimana  kita melakukan pengujian perangkat lunak. Secara singkat, test case menjadi bentuk detail  dari skenario pengujian. Artinya setiap poin skenario pengujian  akan dapat diderivasi menjadi beberapa test case.  Komponen-komponen pada kasus uji atau test case .

1.	ID Test Case

	ID test case berfungsi untuk memberikan identifier pada setiap test case yang dibuat. Tidak ada format penomoran yang baku, namun yang diperlukan adalah penomoran yang jelas serta disepakati  bersama oleh tim pengembang perangkat lunak.
2.	ID skenario pengujian

	Komponen ini penting untuk dimasukkan karena menjadi acuan dalam membuat test case. Pada poin ini, jika tidak menggunakan ID skenario pengujian,  dapat menggunakan deskripsi skenario pengujian.
3.	Test case/kasus uji

	Komponen ini berisi deskripsi kasus uji atau test case yang akan  dilakukan dan dibuat dengan kalimat yang singkat, padat, dan jelas.
4.	Kondisi pra (pre-condition)

	Komponen ini menggambarkan kondisi yang harus ada sebelum dilakukan langkah-langkah dalam kasus uji.
5.	Langkah pengujian (test steps)

	Komponen ini berisi langkah-langkah pelaksanaan pengujian secara detail. langkah dapat digambarkan dengan kalimat yang spesifik, karena akan menjadi aktivitas yang dilakukan ketika pengujian dilakukan.
6.	Data uji (test data)

	Komponen ini berisi data yang diperlukan untuk dimasukkan oleh penguji pada setiap langkah yang dilakukan. Data uji ini dapat dikosongkan apabila dalam langkah pengujian tidak memerlukan data tertentu.
7.	Hasil yang diharapkan (expected result)

	Komponen ini berisi kalimat yang menggambarkan hasil yang diharapkan dalam melakukan sebuah kasus uji. Komponen ini menjadi acuan bahwa sebuah pengujian dalam kasus uji dapat dinyatakan berhasil atau gagal.
8.	Kondisi pasca (post condition)

	Komponen ini berisi gambaran kondisi yang seharusnya terjadi setelah pengujian dilakukan.

9.	Hasil yang terjadi

    Gambaran hasil yang terjadi Ketika pengujian dilakukan.

10.	Status

    Kesesuaian antara ecpected result dan actial result akan menghasilkan kesimpulan berupa status (berhasil/gagal).

## Bab 8 – Metriks Pengujian Perangkat Lunak

-	Merupakan pengukuran kuantitatif yang digunakan untuk memperkirakan kemajuan, kualitas dan Kesehatan proses pengujian perangkat lunak.
-	Tujuan : untuk meningkatkan efisiensi dan efektivitas dalam proses pengujian software
-	Tipe metrik pengujian pl :

a.	Proses metrik = digunakan untuk memperbaiki efisiensi dari tahap SDLC.

b.	Product metrics = untuk mengukur berbagai karakteristik produk perangkat lunak.

c.	Project metrics = untuk mengukur seberapa bagus peningkatan efisiensi tim.

Pertanyaan :

Thalia : Berikan 1 contoh diantara beberapa jenis metriks! rework effort ratio itu apa?

Jawaban : 
Rework Effort Ratio = (Actual rework  efforts spent in that phase/ total actual efforts spent in that phase) X 100

Total Effort for Rework = 10 
Total Effort for Project = 200 
Rework Effort % =(10/200)*100= 5 %
rumus untuk menghitung rasio effort dari pengerjaan ulang suatu perangkat lunak.


Lala:
Apakah semua jenis metrik diitung dalam pengujian

Jawaban : 
semua jenis metrik tidak di hitung, karen a dalam pengujian perangkat lunak tidak mesti semua permasalahan di temukan. jadi misal ketika pengujian menemukan 3 permasalahan, hanya 3 metrik yg bisa digunakan untuk menghitung penyelesaian dari permasalahan

## Bab 3 - Pengujian White Box
-	White box testing atau glass box testing merupakan testing yang berorientasi pada menganalisa kode program dan logika dari perangkat lunak yang dibuat.
