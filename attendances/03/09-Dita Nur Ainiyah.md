RANGKUMAN PERTEMUAN MINGGU KE-3

BAB 5 : BLACK BOX TESTING

black box testing/pengujian fungsional : metode pengujian software yang digunakan 
untuk menguji software tanpa harus mengetahui struktur kode/program.
pengujiannya didasarkan pada detail aplikasi seperti tampilan, fungsi yang ada,
dan kesesuaian alur fungsi dengan proses yang diinginkan customer.


tujuan : memeriksa setelah tahap akhir proyek untuk mengetahui apakah software berfungsi dengan baik
dan melayani customer dengan efisien.
untuk melakukan black box testing, seseorang tidak harus memiliki kemampuan coding


teknik teknik black box testing :
-equivalence partitioning (melakukan partisi untuk membagi beberapa input data)
- boundary value analysis (fokus untuk menemukan error, entah dari sisi luar atau
dalam software)
- decision table testing (menggunakan dua buah output untuk kondisi berbeda(true/false)
dibuat sesuai scenario pengujian untuk membuat test case dalam pengujian)
- state transition testing (menggunakan model 'state'(kondisi yang akan terjadi)
pada sebuah diagram transisi saat melakukan pengujian software.)
- graph based testing (graph merupakan identifikasi dari object yang ada pada
aplikasi, dari graph ini dapat ditentukan relasi antar object dan test case ysng
dibuat menyesuaikan relasi antar object untuk menemukan error)
- error guessing (pendekatan dalam oengujian software yang mebutuhkan pengalaman
dari anggota penguji untuk mendiagnosa error)
- common comparison (teknik yang membandingkan secara umum fitur dari software
yang dibuat dengan software lain atau versi sebelumnya dari software
 yang memiiki fitur sama)


Kelebihan Black Box Testing :
- Penguji tidak perlu memiliki pengetahuan tentang bahasa pemrograman tertentu
- Pengujian yang dilakukan berdasarkan sudut pandang user agar dapat mengungkapkan 
  konsistensi atau ambiguitas dalam spesifikasi.
- Programmer dan tester memiliki ketergantungan satu sama lain
- Efisien untuk segmen kode besar
- Akses kode tidak diperlukan
- Pemisahan antara perspektif pengguna dan pengembang


Kekurangan Black Box Testing:
- Uji kasus sulit di desain tanpa spesifikasi yang jelas
- Kemungkinan memiliki pengulangan tes yang sudah dilakukan oleh programmer
- Beberapa bagian back end tidak diuji sama sekali.
- Cakupan terbatas karena hanya sebagian kecil dari skenario pengujian yang dilakukan
- Pengujian tidak efisien karena keberuntungan tester dari pengetahuan tentang perangkat lunak internal


Manfaat dari metode Black Box testing:
- Kesederhanaan
- Kejelasan
- Ketidakberpihakan 

pertanyaan:
maksud dari sudut pandang ketidakpihakan antara pengguna dan pengembang  
jawaban : pengujian boleh dari pengguna tapi pengembang sebagai perancang




BAB 7: PELAPORAN BUG

bug : bug dapat dedifinisikan sebagai keselahan (error), kecacatan (flaw), atau kegagalan (fault) yang mengakibatkan kesalahan dalam perangkat lunak. 
Sering juga disebut sebagai defect dalam konteks pengujian perangkat lunak.

Karakteristik Pelaporan Bug yang Baik:
1. Objektif : berdasarkan fakta menyeluruh
2. Spesifik: dilakukan secara terperinci dengan pelaporan yang harus dilakukan per bug
3. Ringkas: dilakukan dengan jelas dan ringkas (tidak bertele-tele) sesuai dengan bug yang didapatkan.
4. Dapat diulang (reproducible): setiap pelaporan bug harus disertai langkah demi langkah hingga bug ditemukan  
5. Eksplisit: Pelaporan harus jelas dan dapat diamati
6. Persuasif: mempengaruhi pengembang perangkat lunak untuk segera memperbaiki bug yang ditemukan.

Tingkat Bug:
- Severity-1 Errors (Menyebabkan perangkat lunak berhenti berjalan)
- Severity-2 Errors (Menyebabkan kegagalan operasi atau ketidak sesuaian namun perangkat lunak masih dapat berjalan)
- Severity-3 Errors (Kesalahan yang tidak terduga atau kesalahan yang tidak konsisten)
- Severity-4 Errors (Usualan baru terhadap perangkat lunak)

Klasifikasi bug:
1. Trivial: level terendah dari sebuah bug, yang artinya memiliki tingkat kesalahan paling rendah. 
2. Minor: level menengah yang bisa dianggap penting, meski tidak berpengaruh besar terhadap jalannya sebuah sistem.
3. Major: level menengah atas yang sangat terasa sekali terhadap fungsionalitas sistem. Bug ini paling diperhatikan oleh developer.

Status pada bug :
- new
- assigned
- rejected
- fixed
- ready to test
- failed re-test
- closed

Komponen Pelaporan Bug:
1.Id bug
2.Judul bug
3.Tingkatan bug/severity
4.Status
5.Deskripsi singkat
6.Langkah untuk menentukan bug(step to reproduce)
7.Hasil yang diharapkan(expected behavior)
8.Hasil yangdidapt saat pengujian(actual behavior)
9.Tangkapan layar perangkat lunak(screenshot)
10.Penguji
11.Komentar dari penguji gambar

Pertanyaan:
Apa yang dimaksud probabilitas dan dampak pada tingkatan bug? 
Jawaban : Pengklasifikasian bug juga dapat dilakukan secara relatif berdasarkan dimensi 
probabilitas (probability) dan dampak (impact) [2]. Dimensi probabilitas menggambarkan
seberapa sering bug muncul pada perangkat lunak. Sedangkan dimensi dampak 
menggambarkan seberapa besar dampak bug terhadap perangkat lunak baik dari segi teknis 
maupun proses bisnis yang terjadi. Dari dimensi dan tingkatan tersebut, dihasilkan 4 
tingkatan bug, yaitu trivial, minor, dan major.




BAB 8: METRIKS PENGUJIAN PERANGKAT LUNAK

Makna : pengukuran kuantitatif yangdigunakan untuk memperkirakankemajuan, kualitas, produktivitas, 
dan  kesehatan proses pengujian perangkat  lunak.
Tujuan:
- meningkatkan efisiensi dan efektivitas dalam proses pengujian software
- membantu membuat keputusan yang lebih baik dalam proses pengujian software
- menyediakan data yang dapat diandalkan dalam proses pengujian
contoh :jarak tempuh mingguan mobil dibandingkan dengan jarak tempuh 
ideal yang direkomendasikan oleh pabrik.

Tipe Metriks :
1. Process Metrics (digunakan untuk memperbaiki efisiensi dari tahap SDLC (Software Development Life Cycle))
2. Product Metrics (untuk mengukur berbagai karakteristik produk perangkat lunak.)
3. Project Metrics (untuk mengukur seberapa bagus peningkatan efisiensi tim.)

Life cycles :
- Analysis (identifikasi metrik untuk software yg diuji)
- Communicate (menjelaskan kepada stakeholder dan testing team terkait pentingnya digunakan metrik)
- Evaluation (verifikasi dan validasi data)
- Report (memberikan laporan dengan kesimpulan yang jelas serta mudah dicerna)

Cara Menghitung Metrik :
1. Identifikasi software testing process utama yang akan diukur
2. Tester menggunakan data untuk bahan dasar penentuan metrik
3. Menentukan informasi yang harus diikuti, frekuensi pelacakan dan orang yang bertanggung jawab atas tugas tersebut
4. Penghitungan, pengelolaan, dan interpretasi yang efektif dari metrik yang ditentukan
5. Identifikasi area peningkatan tergantung pada interpretasi metrik yang ditentukan

Jenis Metriks:
1. Rework Effort Ratio = (Actual rework efforts spent in that phase/ total actual efforts spent in that phase) X 100 
2. Requirement Creep = ( Total number of requirements added/No of initial requirements)X100
3. Schedule Variance = ( Actual efforts – estimated efforts ) / Estimated Efforts) X 100
4. Cost of finding a defect in testing = ( Total effort spent on testing/ defects found in testing) 
5. Schedule slippage = (Actual end date – Estimated end date) / (Planned End Date – Planned Start Date) X 100 
6. Passed Test Cases Percentage = (Number of Passed Tests/Total number of tests executed) X 100
7. Failed Test Cases Percentage = (Number of Failed Tests/Total number of tests executed) X 100 
dan masih banyak lagi.

pertanyaan 1:
Berikan 1 contoh diantara beberapa jenis metriks! 
rework effort ratio itu apa?
Jawaban : 
Rework Effort Ratio = (Actual rework  efforts spent in that phase/ total actual efforts spent in that phase) X 100

Total Effort for Rework = 10 
Total Effort for Project = 200 
Rework Effort % =(10/200)*100= 5 %
rumus untuk menghitung rasio effort dari pengerjaan ulang suatu perangkat lunak.

pertanyaan 2:
Apakah semua jenis metrik diitung dalam pengujian
Jawaban : 
semua jenis metrik tidak di hitung, karenaa dalam pengujian perangkat lunak tidak mesti 
semua permasalahan di temukan. jadi misal ketika pengujian menemukan 3 permasalahan, hanya 3 metrik yg bisa 
digunakan untuk menghitung penyelesaian dari permasalahan



BAB 6: SKENARIO PENGUJIAN DAN KASUS UJI

definisi pengujian: sebuah aktivitas untuk menentukan hal-hal apa saja yang perlu untuk diuji. Skenario pengujian perangkat lunak dibuat mengacu pada dokumen spesifikasi kebutuhan perangkat lunak (SKPL).
Komponen Dokumen Skenario Software Test:
1. ID Skenario Pengujian
2. ID Kebutuhan
3. Deskripsi Skenario pengujian

definisi kasus uji : tentang bagaimana 
kita melakukan pengujian perangkat lunak. 
Secara singkat, test case menjadi bentuk detail 
dari skenario pengujian.
Komponen Kasus Uji : 
1. ID Test case
2. ID Skenario Pengujian
3. Test Case/Kasus Uji
4. Kondisi Pra (Pre-condition)
5. Langkah Pengujian
6. Data Uji
7. Hasil yang diharapkan
8. Kondisi Pasca (Post-condition)
9. Hasil yang terjadi
10. Status

Kegunaan Test case:
- melakukan testing kesesuaian suatu komponen terhadap spesifikasi 
- melakukan testing, kesesuaian suatu komponen terhadap desain

Membuat Test Case :
- Membuat test case dengan sederhana dan transparan
- Membuat test case dengan End User in Mind
- Hindari Pengulangan Kasus Uji
- Test Case Harus Dapat Diidentifikasi




BAB 3: PENGUJIAN WHITE BOX

definisi :testing yang berorientasi pada menganalisa kode program dan logika dari perangkat lunak yang dibuat.
Statement coverage : (jumlah statement yang dieksekusi/jumlah statement)x100
Branch coverage : dimulai dengan mengubah kode program menjadi sebuah flowchart sederhana yang menunjukkan cabang / branch yang ada pada kode program
Path coverage : menguji semua path yang ada di program dan semua jalur pada algoritma. Path Coverage bisa disebut juga dengan Cakupan Jalur 
dengan menilai proporsi eksekusi jalur program yang diuji oleh sekumpulan testcase yang telah ditentukan. 

