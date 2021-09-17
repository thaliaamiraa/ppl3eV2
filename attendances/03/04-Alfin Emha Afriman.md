# Pertemuan 03

# Blackbox Testing (Kelompok 5)

Black Box Testing ini dilakukan pengujian yang didasarkan pada detail aplikasi seperti tampilan aplikas, black box testing ini lebih menguji ke tampilan luar (Interface) dari suatu aplikasi agar mudah digunakan oleh pengguna.  Metode ini berjutujan untuk memeriksa, setelah tahap akhir proyek, apakah perangkat lunak / aplikasi berfungsi dengan baik, dan melayani penggunanya secara efisien.Jadi untuk melakukan black box testing seseorang tidak harus memiliki kemampuan coding / TDD (Test Driven Development) coding, tes ini bisa dilakukan oleh pengguna, tim marketing bahkan user sebagai kuisionernya

Terdapat teknik - teknik Black-box Testing

1. Equivalence Partitioning
Cara kerjanya denga melakukan partition / pembagian menjadi beberapa partisi dari input data

2. Boundary Value Analysis
Teknik ini lebih fokus kepada boundary, yaitu error dari luar / sisi dalam software, minimum maupun maksimum nilai dari error yang didapat

3. Decision Table Testing
Teknik pendekatan pengujian dengan mengidentifikasi 2 buah output untuk 2 buah kondisi yang berbeda (true / false).

4. State Transition Testing
Teknik ini menggunakan model 'state' pada sebuah diagram transisi dalam melakukan pengujian perangkat lunak.

5. Graph Based Testing
Setiap aplikasi biasanya dibangun menggunakan 2 object. setiap object diidentifikasikan sebagai graph. Dari graph ditentukan relasi antar object & test case dapat dibuat menyesuaikan relasi.

6. Error Guessing
Adalah sebuah pendekatan pengujian perangkat lunak yang membutuhkan pengalaman dari personil yang melakukan pengujian.

7. Common Comparison
Teknik yang membandingkan secara umum perangkat lunak yang dibuat / fitur dari software terhadap perangkat lunak lain yang mirip.

Manfaat dari metode Black-box Testing

- Kesederhanaan
Tes mudah dilakukan, karena seseorang berfokus pada input dan output.

- Kejelasan 
Waktu persiapan tes ini sangat singkat, karena sedikit pengetahuan tentang sistem yang dibutuhkan.

- Ketidakberpihakan
Di sini mengikuti sudut pandang pengguna dan bukan sudut pandang pengembang. Hasil pengujian netral: sistem berfungsi, atau tidak.


Pertanyaan :

A. Dita Nur : Maksud dari sudut pandang ketidakpihakan antara pengguna dan pengembang?  
Jawab : pengujian boleh dari pengguna tapi pengembang sebagai perancang.


# Pelaporan Bug (Kelompok 7)

Bug dapat dedifinisikan sebagai keselahan (error), kecacatan (flaw), atau kegagalan (fault) yang mengakibatkan kesalahan dalam perangkat lunak. Sering juga disebut sebagai defect dalam konteks pengujian perangkat lunak. Sehingga mencoba mendefinisikan bug sebagai sebuah defect yang menciptakan perbedaan antara hasil yang diharapkan dengan hasil pengujian perangkat lunak.

Karateristik Pelaporan Bug :
1. Objektif
Berdasarkan fakta menyeluruh

2. Spesifik
Dilakukan secara terperinci dengan pelaporan yang harus dilakukan per bug.

3. Ringkas 
Dilakukan dengan jelas dan ringkas (tidak bertele-tele) sesuai dengan bug yang didapatkan.

4. Reproducible (Dapat Diulang)
Setiap pelaporan bug harus disertai langkah demi langkah hingga bug ditemukan. 

5. Eksplisit
Pelaporan harus jelas dan dapat diamati.

6. Persuasif
Mempengaruhi pengembang perangkat lunak untuk segera memperbaiki bug yang ditemukan.

Pertanyaan :

A. Fransiska Lidya : Apa yang dimaksud probabilitas dan dampak pada tingkatan bug? 
Jawab : Pengklasifikasian bug juga dapat dilakukan secara relatif berdasarkan dimensi probabilitas (probability) dan dampak (impact). Dimensi probabilitas menggambarkan seberapa sering bug muncul pada perangkat lunak. Sedangkan dimensi dampak  menggambarkan seberapa besar dampak bug terhadap perangkat lunak baik dari segi teknis maupun proses bisnis yang terjadi. Dari dimensi dan tingkatan tersebut, dihasilkan 4 tingkatan bug, yaitu trivial, minor, dan major.


# Matriks Pengujian Perangkat Lunak (Kelompok 8)

Matriks pengujian perangkat lunak adalah pengukuran kuantitaf yang digunakan untuk memperkirakan kemajuan, kualitas, produktivitas, dan kesehatan proses pengujian perangkat lunak.
Tujuan :
1. Untuk meningkatkan efisiensi & efektivitas dalam proses pengujian software.
2. Untuk membantu membuat keputusan yang lebih baik dalam proses pengujian software.
3. Untuk menyediakan data yang dapat diandalkan dalam proses pengujian.

Tipe Matrik PPL :
1. Process Metrics : Digunakan untuk memperbaiki efisiensi dari tahap SDLC(Software Development Life Cycle).
2. Prodcut Metrics : Berguna untuk mengukur berbagai karakteristik produk perangkat lunak.
3. Project Metrics : Berpacu pada orang - orang dalam team tester yang bekerjasama dengan alat yang digunakan untuk mengukur seberapa bagus peningkatan efisiensi tim.

Life Cycles of Software Testing Metrics :
1. Analysis : Mengidentifikasi metrik untuk perangkat lunak yang akan diuji.
2. Communicate : Membantu menjelaskan kepada stakeholder dan testing team terkait pentingnya digunakan metrik.
3. Evaluation : Berguna ketika menangkap data yang diperlukan dan juga memverifikasi serta memvalidasi data yang sudah ditangkap yang kemudian data tersebut akan dihitung hasil metriknya.
4. Reports : Memberikan laporan dengan kesimpulan yang jelas serta mudah dicerna yang selanjutnya disampaikan pada stakeholder, developer, dan testing team.

Jenis Metriks :
1.) Rework Effort Ratio
2.) Requirement Creep
3.) Schedule Varience
4.) Cost of Finding a Defect in Testing
5.) Schedule Slippage
6.) Passed Test Cases Percentage
7.) Failed Test Cases Percentage
8.) Blocked Test Cases Percentage
9.) Fixed Defects Percentage
10.) Accepted Defects Percentage
11.) Defects Deferred Percentage
12.) Critical Defects Percentage
13.) Average Time for a Development Team to Repair Defects
14.) Number of Tests Run per Time Period
15.) Test Design Efficiency
16.) Test Review Efficiency
17.) Bug Find Rate or Number of Defects per Test Hour

Pertanyaan : 

A. Thalia Amira : Apakah jenis - jenis matriks seperti perhitungan?
Jawab : Jadi ini adalah rumus, dan rumus nya digunakan untuk menghitung berdasarkan klasifikasi nya. 
	Contoh : Rework Effort Ratio = (Actual rework efforts spent in that pase/total actual efforts spent in that phase) x 100
		 Total Effort for Rework = 10
		 Total Effort for Project = 200 Rework Effort %=(10/200)*100=5%
	Rework Effort Ratio : Menghitung effort ketika ada suatu perangkat lunak yang diuji lalu dikerjakan ulang / dikerjakan ulang.

# Skenario Pengujian & Kasus Uji(Kelompok 6)

Skenario Pengujian Dalam PPL adalah Sebuah aktivitas untuk menentukan hal - hal apa saja yang perlu untuk diuji. Skenario pengujian perangkat lunak dibuat mengacu pada dokumen spesifikasi kebutuhan perangkat lunak(SKPL).
Komponen Dokumen Skenari PPL : 
1. ID Skenario Pengujian 
2. ID Kebutuhan
3. Deskripsi Scenario Pengujian

Kasus Uji / Test Case adalah tentang bagaimana kita melakukan pengujian perangkat lunak. Secara singkat, test case menjadi bentuk detail dari skenario pengujian.
Komponen Kasus Uji :
1. ID Test Case
2. ID Skenario Pengujian
3. Test case/kasus uji
4. Kondisi Pra (Pre-Condition)
5. Langkah Pengujian (Test Steps)
6. Data Uji (Test Data)
7. Hasil yang Diharapkan (Expected Result)
8. Kondisi Pasca (Post-Condition)
9. Hasil yang terjadi (Actual Result)
10. Status

Kegunaan dari Test Case : 
1. Untuk melakukan testing kesesuaian suatu komponen terhadap spesifikasi (Black Box Testing)
2. Untuk melakukan testing kesesuaian suatu komponen terhadap desain (White Box Testing)

# White Box Testing (Kelompok 3)

White box testing atau glass box testing merupakan testing yang berorientasi pada menganalisa kode program dan logika dari perangkat lunak yang dibuat. Dalam White Box Testing terdapat 3 teknik utama yaitu :

1. Statement Coverage
Sesuai dengan nama nya “Statement Coverage” merupakan metode untuk memvalidasi  bahwa kode program yang ditulis di eksekusi paling tidak sekali sesuai dengan logika kode  program yang berjalan. Jika terdapat kode program yang tidak di eksekusi sama sekali ini menandakan ada kode program yang tidak bermanfaat dalam kode program tersebut.

2. Branch Coverage
Langkah yang dibutuhkan untuk melakukan pengujian branch coverage dimulai dengan mengubah kode program menjadi sebuah flowchart sederhana yang menunjukkan cabang / branch yang ada pada kode program.

3. Path Coverage
Yaitu menguji semua path yang ada di program dan semua jalur pada algoritma. Path Coverage bisa disebut juga dengan Cakupan Jalur dengan menilai proporsi eksekusi jalur program yang diuji oleh sekumpulan testcase yang telah ditentukan.
