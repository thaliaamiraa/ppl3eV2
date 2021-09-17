# Rangkuman PPL Pertemuan 3
#  Bab 5 Black Box
Black Box Testing atau yang lebih sering dikenal dengan sebutan pengujian fungsional merupakan metode pengujian perangkat lunak yang digunakan untuk menguji perangkat tanpa mengetahui struktur internal kode program.
Tujuannya adalah memeriksa apakah perangkat lunak atau aplikasi berfungsi dengan baik, dan melayani penggunanya secara efisien.
Di bawah ini merupakan contoh teknik-teknik black box
-	Equivalence Partitioning : melakukan partition atau pembagian menjadi beberapa partisi dari input data.
-	Boundary Value Analysis  : adakah error dari luar atau sisi dalam software, minimum, maupun maksimum nilai dari error di dapat.
-	Decision Table Testing   : teknik pendekatan pengujian dengan mengidentifikasi dua buah output untuk dua kondisi yang berbeda (true/false).
-	State Transition Testing : menggunakan model ‘state’ pada sebuah diagram transisi dalam melakukan pengujian perangkat lunak. Sebuah ‘state’ menggambarkan sebuah kondisi yang akan terjadi ketika sistem diuji.
-	Graph Based Testing      : dibangun menggunakan beberapa object. Setiap object diidentifikasikan sebagai graph.
- 	Error Guessing		 : sebuah pendekatan pengujian perangkat lunak yang membutuhkan pengalaman dari personil yang melakukan pengujian.
-	CommonComparison	 : teknik yang membandingkan secara umum perangkat lunak yang dibuat atau fitur dari software terhadap perangkat lunak lain 

Kelebihan Black Box Testing
-	Programmer dan tester memiliki ketergantungan satu sama lain
-	Efisien untuk segmen kode besar
-	Akses kode tidak diperlukan

Kekurangan Black Box Testing
-	Uji kasus sulit di desain tanpa spesifikasi yang jelas
-	Kemungkinan pengulangan tes yang dilakukan oleh programmer
-	Beberapa bagian back end tidak diuji.

Manfaat Black Box Testing
-	Kesederhanaan
-	Kejelasan
-	Ketidakberpihakan

**Materi tambahan berasal  dari pertanyaan mahasiswa** 

- Maksud dari penjelasan sudut pandang ketidakberpihakan antara pengguna dan pengembang tersebut ialah keputusan disetujui atau tidak hasil pengujian boleh dari pengguna, namun tetap dilakukan oleh pengembang

# Bab 7 Pelaporan Bug
Laporan bug berisi log perangkat, pelacakan tumpukan, dan informasi diagnostik lainnya untuk membantu Anda menemukan dan memperbaiki bug dalam aplikasi.
Di bawah ini Karakteristik Pelaporan Bug:
- Objektif  : berdasarkan penilaian
- Spesifik  : dilakukan per bug
- Ringkas   : harus jelas dan ringkas sesuai dengan bug yang didapatkan
- Persuasif : mempengaruhi pengembang perangkat lunak untuk segera memperbaiki

Di bawah ini Tingkatan Bug:
- Severity-1 : berhenti berjalan
- Severity-2 : tidak sesuai namun tetap berjalan
- Severity-3 : kesalahan tidak terduga
- Severity-4 : usulan baru terhdap perangkat lunak

Di bawah ini Status Bug:
- New      	: bug baru dan menunggu
- Assigned 	: bug sudah ditugaskan ke pengembang untuk diperbaiki 
- Rejected 	: bug ditolak dan dikembalikan ke penguji
- Fixed    	: bug selesai diperbaiki
- Ready to test : bug rilis untuk dilakukan pengujian kembali
- Failed retest : bug masih ditemukan pada tahap pengujian  
- Closed        : bug selesai diperbaiki

Di bawah ini Komponen Pelaporan Bug:
- ID  
- Judul
- Tingkatan
- Status
- Deskripsi singkat
- Langkah untuk menemukan bug
- Hasil diharapkan
- Hasil didapat
- Screenshoot
- Penguji

**Materi tambahan berasal  dari pertanyaan mahasiswa** 

- Yang dimaksud probabilitas dan dampak pada tingkatan bug yaitu menggambarkan seberapa sering bug muncul pada perangkat lunak dan dimensi dampak menggambarkan seberapa besar dampak bug terhadap perangkat lunak

# Bab 8 Metriks Pengujian Perangkat Lunak
Metriks Pengujian Perangkat Lunak adalah pengukuran kuantitatif yang digunakan untuk memperkirakan kemajuan, kualitas, produktivitas, dan  kesehatan proses pengujian perangkat  lunak.
Tujuannya adalah meningkatkan efisiensi dalam proses pengujian dan membantu membuat keputusan yang lebih baik.
Di bawah ini Tipe Metrik Pengujian Perangkat Lunak:
-	Process Metrics : digunakan untuk memperbaiki efisiensi dari tahap SDLC 
- 	Product Metrics : mengukur berbagai karakteristik produk perangkat lunak
- 	Project Metrics : tester yang bekerjasama dengan alat yang digunakan untuk mengukur seberapa bagus peningkatan efisiensi 

**Materi tambahan berasal  dari pertanyaan mahasiswa** 

- Pada jenis metriks tidak harus semua dilakukan, karena dalam pengujian perangkat lunak tidak selalu semua permasalahan dapat ditemukan.

# Bab 6 Skenario Pengujian dan Kasus Uji
A. Skenario Pengujian
Aktivitas untuk menentukan hal yang perlu diuji. skenario pengujian mengacu spesifikasi kebutuhan perangkat lunak. 
Di bawah ini Komponen Dokumen Skenario PPL :
- ID Skenario Pengujian
- ID Kebutuhan 
- Deskripsi skenario pengujian 

B. Kasus Uji
Melakukan pengujian perangkat lunak secara singkat
Di bawah ini Komponen Kasus Uji :
- ID Test Case
- ID Skenario Pengujian
- Test case
- Kondisi pra
- Langkah Pengujian
- Data Uji
- Hasil Diharapkan
- Kondisi Pasca
- Hasil yang terjadi
- Status

Kegunaan Test Case sebagai berikut
- Black Box Testing : Melakukan testing sesuai komponen terhadap spesifikasi
- White Box Testing : Melakukan testing sesuai komponen terhadap desain

# Bab 3 White Box Testing
White Box Testing atau glass box testing merupakan testing yang berorientasi pada menganalisa kode program dan logika dari perangkat lunak yang dibuat
Di bawah ini jenis-jenis White Box Testing :
- Statement Coverage
Metode untuk memvalidasi bahwa kode program yang ditulis di eksekusi paling tidak sekali sesuai dengan logika kode program yang berjalan
- Branch Coverage
Langkah yang dibutuhkan untuk mealkukan pengujian branch coverage dimuali dengan mengubah kode program menjadi sebuah flowchart 
- Path Covergae
Menguji semua path yang ada di program dan semua jalur pada algoritma. Pada program setidaknya dieksekusi satu kali tes
