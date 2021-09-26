# Pertemuan 03
Buatlah Rangkuman Pertemuan Ketiga

# BAB 5 - BLACK BOX TESTING
    Pengujian perangkat lunak dibedakan menjadi 2:
    1. Black Box Testing dan 
    2. White Box Testing
    Pembahasan kali ini adalah Black Box Testing.
    Black box testing merupakan salah satu pengujian program  perangkat lunak yang lengkap dan terintregritas, sering dikenal dengan pengujian Fungsional. Yakni metode pengujian tanpa mengetahui struktur internal kode/program dari perangkat lunak tersebut.
    Black Box Testing lebih ke pengujian bagian interface aplikasi.
    Beberapa pengujiannya meliputi : tampilan aplikasi, fungsi/fitur2 yang ada, serta kesesuaiaan alur fungsi yang diinginkan oleh customer. 
    
## Teknik-Teknik Black Box Testing
    1. Equivalence Partitioning : dengan melakukan pembagian menjadi beberapa partisi dari input data.
    2. Boundary Value Analysis : dengan melakukan pengujian error dari luar sisi aplikasi.
    3. Decision Table Testing : dengan mengidentifikasi 2 buah output kondisi (true/false).
    4. State Transition Testing : dengan menggambarkan sebuah kondisi akan terjadi kepada sistem setelah di uji.
    5. Graph Based Testing : dengan menemukan eror menggunakan beberapa object.
    6. Error Guessing : dengan melakukan pendekatan pengalaman dari personil yang melakukan pengujian.
    7. Common Comparison : dengan membandingkan fitur perangkat lunak yang dibuat dengan perangkat lunak yang mirip yang telah dibuat sebelunya 



### Pertanyaan Bab 5
1.Dita : 

Pada manfaat metode blackbox testing pada ketidakberpihakan kenapa mengikuti sudut pandang pengguna dan bukan sudut pandang perngambang sedangkan penggunaan satu proses tergantung pada pedndapat pengambang ?

Jawaban.

maksud dari sudut pandang ketidakpihakan antara pengguna dan pengembang  jawaban pengujian boleh dari pengguna tapi pengembang hanya sebagai perancang

# BAB 7 - PELAPORAN BUG
    Bug secara umum merupakan kesalahan(error), kecacatan(flaw), atau kegagalan(fault) dalam suatu perangkat lunak.

## Karakteristik Pelaporan Bug
    1. Objektif         : sesuai fakta
    2. Spesifik         : terperinci
    3. Ringkas          : tidak bertele tele
    4. Dapat diulang    : disertai langkah
    5. Eksplisit        : pelaporan jelas
    6. Persuatif        : mempengaruhi pengembang 
## Tingkatan Bug (Severity Ranking)
    Severity-1 Errors --> Menyebabkan perangkat lunak berhenti berjalan. 
    Severity-2 Errors --> Menyebabkan kegagalan operasional/ketidak sesuaiaan, namun perangkat lunak masih dapat berjalan.
    Severity-3 Errors --> Kesalahan yang tidak terduga/ tidak konsisten
    Severity-4 Errors --> Usulan baru terhadap perangkat lunak
## Pengklasifikasian Bug 
    1. TRIVAL --> tingkatan paling rendah yakni memiliki tingkat kesalahan paling rendah yang tidak berpengaruh pada jalannya sebuah sistem
    2. MINOR --> tingakatan menengah(bisa dianggap penting) walaupun tidak berpengaruh besar pada jalannya sebuah sistem
    3. MAJOR --> tingkatan menengah atas. Bug yang paling berpengaruh tehadap fungsional sistem
## Status Pada Bug
    New -> Assigred -> Rejected -> Fixed -> Ready to text -> Failed re-test -> Closed


### Pertanyaan Bab 7
1.Fransiska : 

Apa yang dimaksud probabilitas dan jelaskan dampak pada tiap tingkatan bug? 

Jawaban : 

Jadi Pengklasifikasian bug juga dapat dilakukan secara relatif sesuai dengan dimensi probabilitas dan dampak. Dimensi probabilitas menggambarkanseberapa sering bug muncul pada perangkat lunak. Sedangkan dimensi dampakmenggambarkan seberapa besar dampak bug terhadap perangkat lunak baik dari segi teknis 
maupun proses bisnis yang terjadi. Dari dimensi dan tingkatan tersebut, dihasilkan 4 tingkatan bug, yaitu trivial, minor, major dan critical.

# BAB 9 - METRIKS PENGUJIAN PERANGKAT LUNAK
    Metriks Pengujian Perangkat Lunak adalah pengukuran kuantitatif yang digunakan untuk memperkirakan kemajuan, kualitas, produktivitas, dan kesehatan proses pengujian perangkat lunak.

## Tujuan Metriks Pengujian Perangkat Lunak
    -> Meningkatkan efisiensi dan efektivitas proses pengujian
    -> Membantu membuat keputusan lebih baik
    -> Menyediakan data yang dapat di gunakan dalam proses pengujian
## Tipe Metriks Pengujian Perangkat Lunak
    1. Metrik Proses -> memperbaiki efisiensi proses pengembangan
    2. Metrik Produk -> mengukur karakteristik produk perangkat lunak
    3. Metrik Project -> mengukur peningkatan efisiensi tim
### Alur Metriks Pengujian Perangkat Lunak 
Analisis -> Communicate -> Evaluation -> Reports

### Pertanyaan Bab 9
1.Thalia Amira:

Tolong contohkan perhitungan rumus menggunakan jenis metriks ?

Jawaban: 

Jadi ketika ada pengerjaan terjadi kesalahan akan di kerjakan ulang dengan menggunakan rumus Rework Effort Ratio.

Rework Effort Ratio = (Actual rework  efforts spent in that phase/ total actual efforts spent in that phase) X 100


2.Ardila :

Terdapat rumus 17 pengujian metrik dalam pengujian apa semua rumus dimasukan dalam pengujian ?

Jawaban :

untuk jenis metrik tidak dapat ditentukan, karena saat pengujian perangkat lunak tidak memiliki permasalahan yang sama.jika ada permasahalan di pertemukan ada beberapa software maka hanya butuh rumus metrix yang sesaui dengan data pada software/perangkat lunak.


# BAB 6 - SKENARIO PENGUJIAN DAN KASUS UJI
## 01 Skenario Pengujian (Test Scenario)
    Skenario pengujian merupakan aktivitas untuk menentukan hal-hal apa saja yang perlu diuji. Skenario pengujiannya mengacu pada Spesifikasi Kebutuhan Perangkat Lunak(SKPL).

### Komponen Dokumen Skenario PPL
    01 ID Skenario Pengujian -> sebagai id pengenal skenario pengujian
    02 ID Kebutuhan -> sebagai id pengenal spesifikasi kebutuhan perangkat lunak
    03 Deskripsi Skenario Pengujian -> sebagai gambaran pengujian dalam bentuk kalimat

    
## 02 Kasus Uji (Test Case)
    Kasus uji adalah tentang bagaimana dalam melakukan pengujian perangkat lunak.

### Komponen Kasus Uji
    01 ID Test Case -> sebagai oengenal setiap langkah pengujian
    02 ID Skenario Pengujian -> sebgai komponen acuan dalam membuat test case
    03 Test case/Kasus Uji -> merupakan sekripsi kasus
    04 Kondisi Pra -> merupakan gambaran kondisi sebelum melakukan kasus uji
    05 Langkah Pengujian -> merupakan langkah pelaksanaan pengujian
    06 Data Uji -> merupakan data yag diperlukan dalam setiap langkah dilakukan
    07 Hasil yang diharapkan -> merupakan kalimat gambaran hasil yg diharapkan
    08 Kondisi Pasca -> merupakan gambaran setelah terjadinya pengujian
    09 Hasil yang terjadi -> merupakan gambaran yang terjadi ketika pengujian dilakukan
    10 Status -> merupakan kesesuaian kondisi pasca dengan hasil yang terjadi dan menghasilkan kesimpulan (berhasil/gagal)


### Pertanyaan Bab 6
--Nothing--


# BAB 3 - PENGUJIAN WHITE BOX
    White Box Testing merupakan pengujian yang menganalisa kode program dan logika dari perangkat lunak

## Statement Coverage
    Statement Coverage = Jumlah statement yang dieksekusi/Jumlah statement x 100
## Branch Coverage 
    Langkah yang dibutuhkan :
    -> mengubah kode program menjadi sebuah flowchart sederhana yang menunjukkan cabang / branch yang ada pada kode program.
## Path Coverage
    Path coverage yaitu menguji semua path yang ada di program dan semua jalur pada algoritma.

### Pertanyaan Bab 3
--Nothing--
