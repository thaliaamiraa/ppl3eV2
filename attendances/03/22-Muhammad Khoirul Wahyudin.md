# RANGKUMAN PERTEMUAN 2 PENGUJIAN PERANGKAT LUNAK
# BLACK BOX TESTING - Bab 5
pada black box testing adalah pengujian pada detail2 aplikasi seperti fungsi, fitur2
dan dan kesesuaian alur fungsi aplikasi
untuk melakukan black box testing seseorang tidak harus memiliki kemampuan coding atau TTD (Test Driven Development)
Teknik2 blackbox testing
1.	Equivalence partitioning
Cara kerja : dengan melakukan partition atau pembagian menjadi beberapa partisi dari input data.
2.	Boundary Value Analisis
3.	State Transition Testing
4.	Graph based testing
Mencari relasi antar objek unutk menemukan eror
5.	Eror Guessing
6.	Common Comparison
Adalah Teknik membandingkan sebuah sistem 
Kelebihan dari Black BOX testing
1.	Penguji tidak perlu memiliki pengetahan
2.	Akses kode tidak diperlukan
3.	Pemisahan antara 
Kekurangan dari black box testing
1.	Uji kasus sulit di desain
2.	Beberapa bagian backend tidak di uji
Manfaat dari blackbox testing
1.	Kesederhanaan
2.	Kejelasan
3.	Ketidakberpihakan.
Pertanyaan
•	Disitu terdapat mengikuti sudut pandang pengguna dan bukan suut pandang pengembang , tetapi disitu ada penggunaan suatu proses dari pada yang lain tergantung pada pengembang.
Jawab : karena pengembang hanya sebagai perancang sedangkan pengujian boleh dilakukan oleh pengguna.
# PELAPORAN BUG - Bab 7
Bug adalah kesalahan, kecacatan yang mengakibatkan kesalahan dalam perangkat lunak
Karakteristik perlaporan bug yang baik
1.	Objektif 
Berdasarkan fakta menyeluruh
2.	Spesifik
3.	Ringkas
4.	Dapat diulang
5.	Persuasif
Penglklasifikasian Bug
1.	Trivial
Adalah lv terendah sebuah bug
2.	Minor 
Lv mengarah yang dianggap penting.
3.	Major
Lv menengah keatas yang sangat terasa sekali terhadap fungsionalitas sistem.
Status pada Bug
New, Assigned, Rejected, Fixed, Ready to test, Failed re-test, Closed.
Komponen pelaporan bug
	Idbug, judul bug, tingkatan bug, sgtatus, deskripsi singkat, Langkah untuk menentukan bug, Hasil diharapkan, hasil di dapat, tangkapan layer, dilaporkan oleh, komentar.
PERTANYAAN
Pertanyaan bab 7
-Fransiska 
Apa yang dimaksud probabilitas dan dampak pada tingkatan bug? 
Jawaban : Pengklasifikasian bug juga dapat dilakukan secara relatif berdasarkan dimensi 
probabilitas (probability) dan dampak (impact) [2]. Dimensi probabilitas menggambarkan
seberapa sering bug muncul pada perangkat lunak. Sedangkan dimensi dampak 
menggambarkan seberapa besar dampak bug terhadap perangkat lunak baik dari segi teknis 
maupun proses bisnis yang terjadi. Dari dimensi dan tingkatan tersebut, dihasilkan 4 
tingkatan bug, yaitu trivial, minor, dan major.
# METRIKS PENGUJIAN PERANGKAT LUNAK - Bab 8
Makna
Adalah pengukuran kuantitatif yang digunakan untuk memprakirakan kemajuan kualitas, produktifitas
Tipe Metriks Pengujian Perangkat Lunak
1.	Proses Metrics
2.	Product Metriks
3.	Project Metrics
LIVE CYCLES OF SOFTWARE TESTING METRICS
Analisis : mengidentifikasi metrics untuk pengujian perangkat lunak.
Communicate, Evaluation, Reports
HOW TO CALCULATES TEST METRICS
1.	Identifikasi software testing proses utama yang akan di ukur
2.	Tester menggunakan data.
3.	Menenntukan infotmasi yang harus di ikuti
JENIS METRIKS
1.	Rework effort Ratio
2.	Requirement Creep
3.	Schedule Variance
4.	Cost Of finding a detect
5.	Test design efficiency
6.	Buh find rote or number of defects per test hour
PERTANYAAN
 
Thalia : Berikan 1 contoh diantara beberapa jenis metriks! 
rework effort ratio itu apa?
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
# SKENARIO PENGUJIAN - BAB 6
1.	Skenario Pengujian
Adalah sebuah aktivitas untuk menentukan hal hal apa saja yang perlu di uji.
Komponen Dokumen Skenario PPL
-	ID Skenario Pengujian
-	ID kebutuhan
-	Deskripsi Skenario

2.	Kasus Uji
Adalah tentang bagaimana kita melakukan pengujian perangkat lunak(Test case menjadi bentuk detail dari scenario pengujian.
-	ID Test Case
Digunakan sbg identifier pada setiap test case
-	ID Skenario pengujian
Komponen penting karena menajadi acuan dalam membuat test case
-	Test Case
Berisi deskripsi kasus uji yang akan dilakukan.
-	Kondisi Pra
-	Langkah pengujian
Berisi langkah2 pengujian secara detail.
-	Data Uji
Berisi data yang diperlukan untuk dimasukkan di setiap Langkah yang dilakukan
-	Hasil yang diharapkan
Berisi kalimat yang menggambarkan hasil yang diharapakan dalam melakukan kasus uji
-	Kondisi Pasca
Gambaran kondisi yang seharusnya terjadi
-	Hasil yang terjadi
Gamabran hasil yang terjadi Ketika pengujian dilakukan
-	Status
Berisi Kesimpulan.
Kegunaan dari test case
1.	Untuk melakukan testing kesesuaian suatu komponen terhadap spesifikasi
2.	Untuk melakukan testing, kesusaian suatu komponen terhadap desain.
 
Membuat test case
1.	Membuat test case dengan sederhana dan transparan
2.	Memuat test case engan end user in mind
3.	Hindari pengulangan kasus uji
4.	Test case harus dapat di identifikasi

