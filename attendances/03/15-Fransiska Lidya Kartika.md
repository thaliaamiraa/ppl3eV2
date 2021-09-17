# Rangkuman pertemuan ketiga
## 1. BAB 5 Black Box Tesing
Black Box disebut sebagai pengujian fungsional yang menguji perangkat lunak tanpa mengetahui struktur internal
kode program. Tester mengetahui jalannya program akan tetapi tidak memiliki pengetahuan tentang bagaimana melakukannya.
Pengujian ini didasarkan pada detail aplikasi seperti tampilan aplikasi, fungsi-fungsi dan kesesuaian alur fungsi dengan bisnis proses
setiap pengujiam mengikuti skenario, jika input yang valid diterima, yang tidak valid ditolak.
testing dapat dilakukan oleh tim marketing atau user sebagai kuesioner

### Teknik Black Box testing
- Equivalence Partitioning : melakukan pembagian menjadi beberapa partisi dari input data
- Boundary Value Analysis : pengecekan apakah terdapat eror dari luar atau sisi dalam software
- Decision Table Testing : mengidentifikasi dua buah output untuk kondisi berbeda, digunakan untuk membuat test case dalam pengujian
- State Transition Testing : state yang menggambarkan sebuah kondisi yang terjadi ketika sistem diuji
- Graph Based Testing : object diidentifikasi sebagai graph. dari object graph dapat ditemukan relasi antar object dan digunakan untuk menemukan error
- Error Guessing : pendekatan pengujian perangkat lunak yang membutuhkan pengalaman personil untuk melakukan pengujian
- common comparison : teknik membandingkan secara umum perangkat lunak yang dibuat dengan software lain yang mirip

### Kelebihan Black Box Testing
- penguji tidak perlu memiliki pengetahuan pemrograman
- programmer dan tester memiliki saling ketergantungan
- akses kode tidak diperlukan
- efisien untuk segmen kode besar
- pemisahan perspektif pengguna dan pengembang

### Kekurangan 
- Uji kasus sulit didesain tanpa spesifikasi jelas
- kemungkinan pengulangan tes dilakukan oleh programmer
- bagian backend tidak diuji
- cakupan terbatas skenario pengujian


## 2. BAB 7 Pelaporan Bug
### Karakterisitik pelaporan bug
- objektif : berdasarkan fakta
- spesifik : dilakukan terperinci
- ringkas : tidak bertele-tele
- dapat diulang : harus disertai langkah demi langkah hingga bug ditemukan
- eksplisit : jelas dan dapat diamati
- persuasif : Mempengaruhi pengembang untuk memperbaiki bug

### Tingkat Bug 
- severity-1 errors : Menyebabkan perangkat lunak berhenti berjalan
- severity-2 errors : Menyebabkan kegagalan operasi namun software dapat berjalan
- severity-3 errors : kesalahan tidak terduga
- severity-1 errors : usulan baru terhadap perangkat lunak

### Pengklasifikasian Bug
- Trivial : level terendah bug, tidak terpengaruh pada jalannya sistem, contoh salah penulisan sign in menjadi sing in
- Minor : level menengah yang bisa dianggap penting meski tidak mempengaruhi jalannya program. contoh kesalahan alur pada button
- major : level menengah yang terasa dampaknya pada fungsionalitas. contoh saat klik button dan sistem mengeluarkan tampilan bahasa mesin

### status bug
- new : bug baru dan menunggu ditugaskan ke pengembang
- assigned : sudah ditugaskan ke pengembang untuk diperbaiki
- rejected : ditolak dan dikembalikan ke penguji karena pengembang tidak reproduce
- fixed : selesai diperbaiki pengembang
- ready to test : siap diuji kembali setelah perbaikan
- failed re-test : bug ditemukan kembali saat pengujian ulang
- closed : selesai diperbaiki dan melalui pengecekan ulang dari ketua tim penguji

### komponen pelaporan 
- id
- judul
- tingkatan
- status
- deskripsi singkat
- langkah menentukan bug
- hasil yang diharapkan
- hasil yang didapat saat pengujian
- tangkapan layar software
- penguji
- komentar

### pertanyaan
Fransiska : yang dimaksud dengan probabilitas pada pengklasifikasian bug

**jawaban** Dimensi probabilitas menggambarkan
seberapa sering bug muncul pada perangkat lunak. 

## 3. BAB 8 Metriks pengujian software
pengukuran kuantitatif yang digunakan untuk memperkirakan kemajuan, kualitas, produktivitas, dan  kesehatan proses pengujian perangkat  lunak. Metriks bertujuan
untuk meningkatkan efisiensi dan efektivitas dalam proses pengujian software,
 membantu membuat keputusan yang lebih baik dalam proses pengujian software, menyediakan data yang dapat diandalkan dalam proses pengujian

### Tipe Metrik pengujian
- Process Metrics : untuk memperbaiki efisiensi dari tahap SDLC (Software Development Life Cycle). Selain itu, untuk mengukur berbagai karakteristik proses pengembangan perangkat lunak
- Product Metrics : untuk mengukur berbagai karakteristik produk perangkat lunak. Dimana pengukuran tersebut bergantung pada ukuran dan kompleksitas perangkat lunak serta kualitas dan keandalan perangkat lunak.
- Project Metrics : berpacu pada orang-orang dalam team tester yang bekerjasama dengan alat yang digunakan untuk mengukur seberapa bagus peningkatan efisiensi tim.

### pertanyaan
- Thalia : apa yang dimaksud rework effort ratio dan contoh dari jenis metriks?

**jawaban**
Rework Effort Ratio = (Actual rework  efforts spent in that phase/ total actual efforts spent in that phase) X 100.
rumus untuk menghitung rasio effort dari pengerjaan ulang suatu perangkat lunak.

- Ardila : Apakah semua jenis metrik diitung dalam pengujian

**jawaban** Hanya menggunakan metriks yang dibutuhkan saja

## 4. BAB 6 Skenario Pengujian dan Kasus Uji
Skenario pengujian dalam ranah pengujian perangkat lunak adalah sebuah aktivitas untuk menentukan hal-hal apa saja yang perlu untuk diuji.
### Komponen Dokumen Skenario
- ID Skenario Pengujian
- ID Kebutuhan
- Deskripsi scenario pengujian

### Test Case
Test Case menjadi bentuk detail 
dari skenario pengujian

Kegunaan test case :
- untuk melakukan testing kesesuaian komponen terhadap spesifikasi (black box testing)
- Untuk melakukan testing, kesesuaian suatu komponen terhadap desain (white box)

Hal yang harus diperhatikan dalam pembuatan test case, antara lain : Membuat test case dengan sederhana dan transparan, Membuat test case dengan End User in Mind, Hindari Pengulangan Kasus Uji
, Test Case Harus Dapat Diidentifikasi


## 5. BAB 3 White Box
pengujian yang dilakukan dengan menguji kode program

statement coverage : pengujian yang mengeksekusi statement pada source code minimal satu kali
branch coverage: mengubah kode program menjadi flowchart yang menunjukkan adanya cabang
path coverage : menguji pada semua path kode program
