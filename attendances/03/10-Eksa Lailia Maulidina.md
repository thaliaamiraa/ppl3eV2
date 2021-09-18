#Bab 5
##Black box testing
Black box testing adalah pengujian sistem merupakan pengujian program perangkat lunak yang lengkap dan terintegrasi. Black Box Testing atau yang lebih sering dikenal dengan sebutan pengujian fungsional merupakan metode pengujian perangkat lunak yang digunakan untuk menguji perangkat lunak tanpa mengetahui struktur internal kode atau program. 

Teknik-Teknik Black-box Testing :
1.	Equivalence Partitioning
Cara kerja teknik ini adalah dengan melakukan partition atau pembagian menjadi beberapa partisi dari input data.
2.	Boundary Value Analysis
Teknik ini lebih fokus kepada boundary, adakah error dari luar atau sisi dalam software, minimum, maupun maksimum nilai dari error yang didapat.
3.	Decision Table Testing 
Decision Table merupakan teknik pendekatan pengujian dengan mengidentifikasi dua buah output untuk dua kondisi yang berbeda (true/false). 
4.	State Transition Testing 
Teknik State Transition menggunakan model ‘state’ pada sebuah diagram transisi dalam melakukan pengujian perangkat lunak. Sebuah ‘state’ menggambarkan sebuah kondisi yang akan terjadi ketika sistem diuji.
5.	Graph Based Testing 
Setiap aplikasi biasanya dibangun menggunakan beberapa object. Setiap object diidentifikasikan sebagai graph. Dari object graph ini, dapat ditentukan relasi antar object dan test case dapat dibuat menyesuaikan relasi antar object ini untuk menemukan error.
6.	Error Guessing 
Teknik Error Guessing adalah sebuah pendekatan pengujian perangkat lunak yang membutuhkan pengalaman dari personil yang melakukan pengujian. 
7.	Common Comparison 
Common comparison adalah teknik yang membandingkan secara umum perangkat lunak yang dibuat atau fitur dari software terhadap perangkat lunak lain yang mirip

Kelebihan :
•	Penguji tidak perlu memiliki pengetahuan tentang bahasa pemrograman tertentu
•	Pengujian yang dilakukan berdasarkan sudut pandang user agar dapat mengungkapkan konsistensi atau ambiguitas dalam spesifikasi.
•	Programmer dan tester memiliki ketergantungan satu sama lain
•	Efisien untuk segmen kode besar
•	Akses kode tidak diperlukan
•	Pemisahan antara perspektif pengguna dan pengembang

Kelemahan :
•	Uji kasus sulit di desain tanpa spesifikasi yang jelas
•	Kemungkinan memiliki pengulangan tes yang sudah dilakukan oleh programmer
•	Beberapa bagian back end tidak diuji sama sekali.
•	Cakupan terbatas karena hanya sebagian kecil dari skenario pengujian yang dilakukan
•	Pengujian tidak efisien karena keberuntungan tester dari pengetahuan tentang perangkat lunak internal

Manfaat :
•	Kesederhanaan
Tes ini mudah dilakukan, karena seseorang berfokus pada input dan output. 
•	Kejelasan
Waktu persiapan tes ini sangat singkat, karena sedikit pengetahuan tentang sistem yang dibutuhkan. Membuat dan menguji skenario membutuhkan sedikit waktu, karena ia mengikuti jalur pengguna, yang relatif sedikit, tergantung pada ukuran sistem.
•	Ketidakberpihakan 
Di sini mengikuti sudut pandang “pengguna” dan bukan sudut pandang “pengembang”. Hasil pengujian netral: sistem berfungsi, atau tidak. Tidak ada kemungkinan kontestasi, seperti penggunaan satu proses daripada yang lain, tergantung pada pendapat pengembang.

#Bab 6
##Skenario Pengujian dan Kasus Uji

I.	Scenario pengujian
Scenario pengujian adalah skenario pengujian dalam ranah pengujian perangkat lunak adalah sebuah aktivitas untuk menentukan hal-hal apa saja yang perlu untuk diuji.
•	Komponen Dokumen Skenario PPL
-	ID scenario pengujian
Sebagai identifier indeks nomor
-	ID kebutuhan
Sebagai indetifier dokumen spesifikasi kebutuhan software
-	Deskripsi scenario pengujian
Gambaran pengujian dalam bentuk kalimat singkat.
II.	Kasus uji
Kasus uji adalah Kasus uji atau test case adalah tentang bagaimana  kita melakukan pengujian perangkat lunak.
•	Komponen Kasus Uji
-	ID test case
Sebagai identifier pada setiap test case
-	ID scenario pengujian
Menjadi acuan dalam membuat case
-	Test case/kasus uji
Deskripsi kasus uji yang akan dilakukan
-	Kondisi pra
Gambaran kondisi sebelum dilakukan langkah kasus uji
-	Langkah pengujian
Langkah pelaksanaan pengujian secara detail
-	Data uji
Berisi data yang diperlukan untuk setiap langkah yang dilakukan
-	Hasil yang diharapkan
Kalimat yang menggambarkan hasil yang diharapkan dalam melakukan kasus uji
-	Kondisi pasca
Gambaran kondisi yang terjadi setelah pengujian
-	Hasil yang terjadi
Gambaran hasil yang terjadi ketika pengujian dilakukan
-	Status
Kesesuaian antara expected result dan actial result (kesimpulan status  berhasil/gagal)

Kegunaan test case :
1.	Untuk melakukan black box testing
2.	Untuk melakukan white box testing

Membuat test case :
1.	Membuat test case dengan sederhana dan transparan
2.	Membuat test case dengan End User in Mind
3.	Hindari Pengulangan Kasus Uji
4.	Test Case Harus Dapat Diidentifikasi


#Bab 8
##Metriks Pengujian Perangkat Lunak

Metriks pengujian perangkat lunak adalah pengukuran kuantitatif yang digunakan untuk memperkirakan kualitas perangkat lunak.

Tujuan :
1.	Untuk meningkatkan efisiensi dan efektivitas dalam proses pengujian software
2.	Untuk membantu membuat keputusan yang lebih baik dalam proses pengujian software
3.	Untuk menyediakan data yang dapat diandalkan dalam proses pengujian

Contoh :
Jarak tempuh mingguan mobil dibandingkan dengan jarak tempuh ideal yang direkomendasikan oleh pabrikan.

Tipe metriks pengujian perangkat lunak :
1.	Process metrics
Untuk memperbaiki efisiensi dari tahap SDLC
2.	Product metrics
Untuk mengukur berbagai karakteristik produk perangkat lunak
3.	Project metrics
Orang-orang dalam team tester yang bekerjasama dengan alat yang digunakan untuk mengukur seberapa bagus peningkatan efisiensi tim

Life cycles metriks pengujian perangkat lunak :
1.	Analysis
Mengidentifikasi metric untuk software yang akan diuji
2.	Communicate 
Menjelaskan kepada stakeholder dan testing team terkait pentingnya metriks
3.	Evaluation 
Menangkap data yang diperlukan dan memverifikasi serta memvalidasi data yang sudah lengkap
4.	Reports
Memberikan laporan dengan kesimpulan yang jelas

How to calculate test metrics :
1.	Identifikasi software testing process utama yang akan diukur
2.	Tester menggunakan data untuk bahan dasar penentuan metric
3.	Menentukan informasi yang harus diikuti, frekuensi pelacakan dan orang yang bertanggung jawab atas tugas tersebut
4.	Penghitungan, pengelolaan, dan interpretasi yang efektif dari metrik yang ditentukan
5.	Identifikasi area peningkatan tergantung pada interpretasi metrik yang ditentukan

Jenis metriks :
1.	Rework Effort Ratio = (Actual rework efforts spent in that phase/ total actual efforts spent in that phase) X 100 
2.	Requirement Creep = ( Total number of requirements added/No of initial requirements)X100
3.	Schedule Variance = ( Actual efforts – estimated efforts ) / Estimated Efforts) X 100
4.	Cost of finding a defect in testing = ( Total effort spent on testing/ defects found in testing) 
5.	Schedule slippage = (Actual end date – Estimated end date) / (Planned End Date – Planned Start Date) X 100 
6.	Passed Test Cases Percentage = (Number of Passed Tests/Total number of tests executed) X 100
7.	Failed Test Cases Percentage = (Number of Failed Tests/Total number of tests executed) X 100 
8.	Blocked Test Cases Percentage = (Number of Blocked Tests/Total number of tests executed) X 100 
9.	Fixed Defects Percentage = (Defects Fixed/Defects Reported) X 100
10.	Accepted Defects Percentage = (Defects Accepted as Valid by Dev Team /Total Defects Reported) X 100 
11.	Defects Deferred Percentage = (Defects deferred for future releases /Total Defects Reported) X 100 
12.	Critical Defects Percentage = (Critical Defects / Total Defects Reported) X 100 
13.	Average time for a development team to repair defects = (Total time taken for bug fixes/Number of bugs)
14.	Number of tests run per time period = Number of tests run/Total time 
15.	Test design efficiency = Number of tests designed /Total time 47
16.	Test review efficiency = Number of tests reviewed /Total time 
17.	Bug find rote or Number of defects per test hour = Total number of defects/Total number of test hours
Pertanyaan :
1.	Thalia : Berikan 1 contoh diantara beberapa jenis metriks!
Jawaban : 
Rework Effort Ratio = (Actual rework  efforts spent in that phase/ total actual efforts spent in that phase) X 100

Total Effort for Rework = 10 
Total Effort for Project = 200 
Rework Effort % =(10/200)*100= 5 %
2.	Lala: Apakah semua jenis metrik diitung dalam pengujian
Jawaban : 
semua jenis metrik tidak di hitung, karen a dalam pengujian perangkat lunak tidak mesti semua permasalahan di temukan. jadi misal ketika pengujian menemukan 3 permasalahan, hanya 3 metrik yg bisa digunakan untuk menghitung penyelesaian dari permasalahan

#Bab 3
##White box testing
White box testing adalah testing yang berorientasi pada menganalisa kode program dan logika dari perangkat lunak yang dibuat.
Statement coverage = (jumlah statement yang dieksekusi/jumlah statement) x 100
Contoh kode program :
input (int a, int b){		
 sum = a + b		
If (sum>0){
print (This is positive result)
}
 else{
print (This is negative result)
}
}
5 / 9 * 100 = 55,5
7 / 9 * 100 = 77,7
Branch coverage
Langkah yang dibutuhkan untuk melakukan pengujian branch coverage dimulai dengan mengubah kode program menjadi sebuah flowchart sederhana yang menunjukkan cabang / branch yang ada pada kode program 
Path coverage 
Path Coverage yaitu menguji semua path yang ada di program dan semua jalur pada algoritma.







