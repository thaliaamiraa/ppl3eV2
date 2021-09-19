# Bab 5 - Black Box Testing
Black Box Testing atau yang lebih sering dikenal dengan sebutan pengujian fungsional merupakan metode pengujian 
perangkat lunak yang digunakan untuk menguji perangkat lunak tanpa mengetahui struktur internal kode atau program.

### Teknik-Teknik Black-box Testing
- Equivalence Partitioning
Cara kerja teknik ini adalah dengan melakukan partition atau pembagian menjadi beberapa partisi dari input data.

- Boundary Value Analysis
Teknik ini lebih fokus kepada boundary, adakah error dari luar atau sisi dalam software, minimum, maupun maksimum nilai dari error yang didapat.

- Decision Table Testing 
Decision Table merupakan teknik pendekatan pengujian dengan mengidentifikasi dua buah output untuk dua kondisi yang berbeda (true/false).

- State Transition Testing 
Teknik State Transition menggunakan model ‘state’ pada sebuah diagram transisi dalam melakukan pengujian perangkat lunak. 
Sebuah ‘state’ menggambarkan sebuah kondisi yang akan terjadi ketika sistem diuji.

- Graph Based Testing 
Setiap aplikasi biasanya dibangun menggunakan beberapa object. Setiap object diidentifikasikan sebagai graph. 
Dari object graph ini, dapat ditentukan relasi antar object dan test case dapat dibuat menyesuaikan relasi antar object ini untuk menemukan error.

- Error Guessing 
Teknik Error Guessing adalah sebuah pendekatan pengujian perangkat lunak yang membutuhkan pengalaman dari personil yang melakukan pengujian. 

- CommonComparison 
Common comparison adalah teknik yang membandingkan secara umum perangkat lunak yang dibuat atau fitur dari software terhadap perangkat lunak lain yang mirip. 
Selain membandingkan sebuah sistem dengan sistem lainnya yang sama, kita dapat mengkomparasi perangkat lunak yang dibuat dengan versi perangkat lunak sebelumnya.

### Kelebihan dari Black-box Testing
Penguji tidak perlu memiliki pengetahuan tentang bahasa pemrograman tertentu

### Kekurangan Black-box Testing
Uji kasus sulit di desain tanpa spesifikasi yang jelas
Kemungkinan memiliki pengulangan tes yang sudah dilakukan oleh programmer

### Pertanyaan
Dita : pada manfaat metode blackbox testing pada ketidakberpihakan kenapa mengikuti sudut pandang pengguna dan 
bukan sudut pandang perngambang sedangkan penggunaan satu proses tergantung pada pedndapat pengambang ?

Jawaban : maksud dari sudut pandang ketidakpihakan antara pengguna dan pengembang  jawaban pengujian boleh dari pengguna tapi pengembang sebagai perancang




# BAB 7 - Pelaporan bug
Secara umum, bug dapat dedifinisikan sebagai keselahan (error), kecacatan (flaw), atau kegagalan (fault) yang mengakibatkan kesalahan dalam perangkat lunak. 

- karakteristik pelaporan bug yang baik objektif, spesifiik, ringkas , dapat diulang (reproducible), eksplisit dan persuasif

- tingkatan (Severity Ranking) bug ada 4 dimulai dari severity-1 errors, severity-2 errors, severity-3 errors, dan severity-4 errors.

- status pada bug new, assigned, rejected, fixed, ready to test, dan failed re-test, closed.

### Pertanyaan bab 7
Fransiska : Apa yang dimaksud probabilitas dan jelaskan dampak pada tiap tingkatan bug? 

Jawaban : Jadi Pengklasifikasian bug juga dapat dilakukan secara relatif sesuai dengan dimensi probabilitas dan dampak. Dimensi probabilitas 
menggambarkanseberapa sering bug muncul pada perangkat lunak. Sedangkan dimensi dampakmenggambarkan seberapa besar dampak bug terhadap perangkat lunak baik dari segi teknis 
maupun proses bisnis yang terjadi. Dari dimensi dan tingkatan tersebut, dihasilkan 4 tingkatan bug, yaitu trivial, minor, major dan critical.




# bab 8 -  Metriks Pengujian Perangkat Lunak
Metriks Pengujian Perangkat Lunak adalah pengukuran kuantitatif yang digunakan untuk memperkirakan kemajuan, 
kualitas, produktivitas, dan  kesehatan proses pengujian perangkat lunak.

TIPE METRIK PENGUJIAN PERANGKAT LUNAK

1. process metrics untuk memperbaiki efisiensi dari tahap SDLC

2. Product metrics untuk mengukur berbagai karakteristik produk perangkat lunak.

3. project metrics untuk mengukur seberapa bagus peningkatan efektifitas perangkat lunak.

LIFE CYCLES OF SOFTWARE TESTING METRICS

analysis > communicate > Evaluation > Reports

Jenis Metriks :
Jenis metriks ada banyak seperti Rework Effort Ratio, Requirment Creep, Schedule Variance, Cost of finding a defect in testing,
Schedule slippage, Passed Test Cases Precentage. Setiap jenis Metriks ini memiliki rumus yang digunakan dalam pengujian.

### Pertanyaan :
Thalia Amira: Tolong contohkan perhitungan rumus menggunakan jenis metriks ?

Jawaban : Jadi ketika ada pengerjaan terjadi kesalahan akan di kerjakan ulang dengan menggunakan rumus Rework Effort Ratio.

Rework Effort Ratio = (Actual rework  efforts spent in that phase/ total actual efforts spent in that phase) X 100


Ardila : Terdapat rumus 17 pengujian metrik dalam pengujian apa semua rumus dimasukan dalam pengujian ?

Jawaban : untuk jenis metrik tidak dapat ditentukan, karen saat pengujian perangkat lunak tidak memiliki permasalahan yang sama.
jika ada permasahalan di pertemukan ada beberapa software maka hanya butuh rumus metrix yang sesaui dengan data pada software/perangkat lunak.




# Bab 6 - Skenario Pengujian dan Kasus uji

Terdapat 2 Pembaahasan yaitu Skenario Pengujian (Test Scenario) dan Kasus Uji (Test Case)

Skenario Pengujian (Test Scenario) adalah sebuah aktivitas untuk menentukan hal-hal apa saja yang perlu untuk diuji.
### Komponen Dokumen Skenario PPL (ID Skenario Pengujian, ID Kebutuhan, Deskripsi Skenario Pengujian)

Kasus uji atau test case adalah tentang bagaimana kita melakukan pengujian perangkat lunak. 
### Komponen Kasus Kasus Uji (ID Test Case, ID Skenario Pengujian, Test Case/kasus uj, Kondisi pra(pre condition), Langkah Pengujian, Data Uji, 
Hasil Yang diharapkan, KOndisi pasca(post-condition), Hasil yang terjadi(Actual Result), Status)

### Kegunaan dari Test Case
Untuk melakukan testing kesesuaian suatu komponen terhadap spesifikasi   ( Black Box Testing ) dan ( White Box Testing ).




# Bab 3 - pengujian whitebox
White box testing atau glass box testing merupakan testing yang berorientasi pada menganalisa kode program dan logika dari perangkat lunak yang dibuat.

dalam white box terdapat statement yang terkenal yaitu 

statement coverage adalah teknik yang dilakukan untuk melewati semua pernyataan setidaknya satu kali. Setiap jalur coding akan diuji.

branch coverage untuk melakukan pengujian dengan mengubah kode program menjadi sebuah flowchart sederhana yang menunjukkan cabang / branch yang ada pada kode program.

path coverage untuk menguji path yang ada di program dengan meninjau jalur alur algoritma.
