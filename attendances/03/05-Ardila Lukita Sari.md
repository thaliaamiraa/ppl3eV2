# Rangkuman BAB 3
# ------     White Box Testing   ------

#

## White Box Testing / Glass Box Testing
    Testing yang bertujuan untuk menganalisa kode program dan logika yang dibuat.
#

### Code Coverage
Code coverage adalah suatu metrik yang dimaksudkan untuk mengukur usaha pengujian yang diterapkan pada aplikasi software. Dengan adanya code coverage ini kita bisa tahu mana kode sistem yang perlu dieksekusi dan mana yang tidak. Adapun jenis-jenis code coverage ini sendiri ialah :
1. Statement coverage, membantu mengisolasi bagian dari kode yang tidak bisa dieksekusi. <br>
<b> Rumus : </b> <br>
(Jumlah statement yang dieksekusi / jumlah statement) * 100
2. Branch coverage atau decision coverage, bagian yang lebih spesifik dalam menguji kode program dibanding statement coverage, yang mana branch coverage ini nantinya akan melakukan pengukuran terhadap hasil keputusan yang mengalami pengujian.
3. Path coverage, penggambaran jalan eksekusi melalui suatu cara yang tepat dari awal sampai akhir.

#
# Rangkuman BAB 5
# ------     Black Box Testing   ------

### 

    Pengujian perangkat lunak merupakan salah satu proses yang penting dalam proses pengembangan perangkat lunak, yang mana pengujian perangkat lunak ini sendiri nantinya akan membantu tim pengembang dalam mengetahui kelengkapan dan juga integritas sistem yang dibuat.  

#

## Black Box Testing
Black box testing atau pengujian fungsional, yaitu suatu metode pengujian perangkat lunak yang akan menguji perangkat lunak dengan tanpa mengetahui struktur internal program. 
Dengan begitu black box testing ini akan lebih berfokus pada pengujian tampilan aplikasi, fungsi-fungsi yang ada pada aplikasi, dan kesesuaian alur fungsi dengan bisnis proses apakah sudah sesuai dengan requirements yang ada atau belum. Jadi, tidak heran jika metode ini sering digunakan di tahap akhir proyek.
Kemudian, dikarenakan black box testing ini hanya akan lebih berfokus pada pengujian sistem apakah sudah berfungsi dengan efektif dan efisien atau belum, maka untuk pengujinya sendiri tidak harus memiliki kemampuan coding atau TTD (Test Driven Development), mereka yang dari tim marketing atau bahkan user bisa melakukan ikut testing.

#
## Teknik - Teknik Dalam Box Testing
1. Equivalence partitioning, teknik yang akan melakukan pembagian input data menjadi beberapa partisi.
2. Boundary value analysis, teknik yang berfokus pada penemuan error dari luar atau sisi dalam software, baik yang tingkatan errornya minimum maupun maksimum.
3. Decision table testing, teknik pendekatan pengujian yang akan mengidentifikasi 2 buah output untuk 2 kondisi yang berbeda, yaitu True / False. Untuk decision table ini sendiri terdiri atas 3 bagian, yaitu kondisi, rule, dan aksi.
4. State transition testing, teknik yang akan menggambarkan kondisi sistem pada waktu diuji dengan memanfaatkan grafik atau diagram transisi.
5. Graph based testing, mewakili relasi antar object dalam sistem, sehingga dengan begitu tiap object dan relasinya dapat dilakukan pengujian lebih lanjut.
6. Error guessing, salah satu teknik pengujian yang dilakukan dengan tujuan untuk mengantisipasi kesalahan yang mungkin terjadi saat proses pengujian. Untuk teknik ini sendiri pelaksanaannya membutuhkan pengalaman dari orang - orang yang terlibat dalam tim pengujian.
 7. Common Comparison, teknik yang digunakan untuk membandingkan kondisi fitur software yang dikembangkan dengan software lain yang serupa atau bisa juga dibandingkan dengan software versi sebelumnya.

 #
## Kelebihan Black Box Testing
1. Penguji tidak harus paham mengenai bahasa pemrograman.
2. Pengujian dilakukan dengan berdasar sudut pandang user, sehingga secara tidak langsung bisa tahu kekurangan dan kelebihan dari sudut pandang user secara spesifik.
3. Programmer dan tester saling bergantung satu sama lain / kerjasama terbangun dengan baik.
4. Efisien, bahkan untuk segmen kode yang cukup besar.
5. Tidak memerlukan kode akses.
6. Perspektif pengguna dan pengembang terpisah.

 #
## Kekurangan Black Box Testing
1. Tanpa spesifikasi yang jelas, uji kasus akan sulit di desain.
2. Tidak ada pengujian terhadap beberapa bagian back end.
3. Skenario pengujian yang dilakukan terbatas.
4. Pengujian yang dilakukan kurang efisien.
5. Adanya peluang untuk melakukan pengulangan tes yang sebelumnya sudah dilakukan programmer.

 #
## Manfaat Black Box Testing
1. Kesederhanaan, testing ini cukup mudah karena hanya berfokus pada input dan output.
2. Kejelasan, waktu untuk testing sangat singkat karena pengetahuan yang dibutuhkan untuk memahami sistem sangat sedikit.
3. Ketidakberpihakkan, dalam pengujian perangkat lunak akan mengikuti sudut pandang pengguna bukan sudut pandang pengembang.

#

# Rangkuman BAB 6
# ------    Skenario Pengujian dan Kasus Uji   ------

### 
## Skenario Pengujian
    Skenario pengujian dan kasus uji merupakan aktivitas yang menentukan hal - hal apa saja yang perlu diuji, dan dalam pengujiannya mengacu pada Spesifikasi Kebutuhan Perangkat Lunak (SKPL).

### Komponen Dokumen Skenario PPL
1. ID skenario pengujian, untuk mengidentifikasi nomor skenario PPL.
2. ID kebutuhan, mengidentifikasi dokumen kebutuhan perangkat lunak.
3. Deskripsi skenario pengujian, gambaran pengujian dalam bentuk kalimat yang ringkas.  

#
## Test Case
Test case adalah bagaimana cara kita melakukan pengujian perangkat lunak (bentuk detail dari skenario pengujian).

### Komponen Test Case
1. ID test case, mengidentifikasi setiap case yang dibuat.
2. ID skenario pengujian, menjadi acuan dalam membuat test case.
3. Test case, deskripsi mengenai kasus uji yang akan dilakukan.
4. Pra-condition, gambaran mengenai kondisi sebelum dilakukan tahapan test case.
5. Test case steps, berupa langkah - langkah pengujian secara detail.
6. Test data, berisi data yang diperluka dalam setiap langkah yang akan dilakukan.
7. Hasil yang diharapkan, penjabaran harapan yang diinginkan selama melakukan test case.
8. Post-condition, berisi gambaran kondisi yang seharusnya terjadi setelah pengujian selesai dilakukan.
9. Hasil yang terjadi, gambaran hasil yang  terjadi ketika pengujian dilakukan.
10. Status, hasil akhir yang didapat apakah gagal atau tidak (dinilai berdasarkan kesesuaian hasil dengan ekspektasi / harapan)

### Kegunaan Test Case
- Untuk dasar melakukan <b>black box testing</b> dan <b>white box testing</b> 

### Hal - Hal yang Harus Diperhatikan Dalam Membuat Test Case
1. Test Case dibuat sederhana.
2. Test Case dibuat dengan End User in Mind.
3. Hindari pengulangan test case.
4. Test case harus dapat diidentifikasi.


#
# Rangkuman BAB 7
# ------    Pelaporan Bug   ------

### 

    Bug adalah kesalahan, kecacatan, atau kegagalan yang mengakibatkan terjadinya galat pada perangkat lunak, sehingga tidak berfungsi dengan sebagaimana mestinya.

#

## Karakteristik Pelaporan Bug yang Baik
1. Objektif, berdasarkan fakta menyeluruh.
2. Spesifik, dilakukan secara rinci.
3. Ringkas, diuraikan dengan jelas tanpa bertele-tele.
4. Reproducible, pelaporan dilakukan langkah demi langkah hingga bug dapat ditemukan.
5. Eksplisit, pelaporan jelas dan mudah diamati
6. Persuasif, mempengaruhi atau meyakinkan tim pengembang untuk segera melakukan perbaikan.

#

## Tingkatan Bug
1. Severity-1, menyebabkan perangkat lunak berhenti berjalan.
2. Severity-2, perangkat lunak gagal beroperasi dengan baik.
3. Severity-3, kesalahan yang tidak konsisten.
4. Severity-4, usulan baru terhadap perangkat lunak.

#

## Pengklasifikasian Bug
1. Trivial, tingkat kesalahan tidak terlalu berpengaruh pada jalannya sebuah sistem.
<b>Contoh:</b> typo penulisan (sing up --> sing pu)
2. Minor, kesalahan yang tidak berpengaruh besar terhadap jalannya sistem, tetapi harus tetap diperhatikan.
<b>Contoh:</b> salah memilih button.
3. Major, kesalahan yang memberikan pengaruh cukup besar terhadap fungsionalitas sistem.
<b>Contoh:</b> saat klik add member kemudian klik save, sistem memunculkan error tertentu yang isinya berupa bahasa mesin.

#

## Status Bug
1. New, status untuk bug baru dan menunggu untuk ditugaskan ke pengembang.
2. Assigned, sudah ditugaskan ke pengembang dan menunggu untuk ditangani.
3. Rejected, ditolak karena pengembang tidak dapat me-reproduce.
4. Fixed, selesai diperbaiki oleh pengembang.
5. Ready to test, selesai diperbaiki dan siap untuk dilakukan pengujian kembali.
6. Failed re-test, bug maish ditemukan saat pengujian ulang.
7. Closed, selesai diperbaiki dan diuji.

#

## Komponen Pelaporan Bug
1. ID
2. Judul
3. Tingkatan bug
4. Status
5. Deskripsi singkat
6. Langkah menentukan bug
7. Hasil yang diharapkan.
8. Hasil yang didapat saat pengujian.
9. Tangkapan layar perangkat lunak
10. Penguji
11. Komentar dan penguji gambar

# Rangkuman BAB 8
# ------    Matriks Pengujian Perangkat Lunak   ------

### 

## Metriks Pengujian Perangkat Lunak
--> Suatu pengukuran kuantitatif yang digunakan untuk memperkirakan kualitas dan produktivitas selama proses pengajuan perangkat lunak.

#

## Tujuan
1. Meningkatkan efisiensi dan efektivitas dalam pengujian software.
2. Membantu menentukan keputusan terbaik.
3. Menyediakan data yang dapat diandalkan selama proses pengujian.

#

## Contoh
Jarak tempuh mingguan mobil dibandingkan dengan jarak tempuh ideal yang direkomendasikan oleh pabrik.

#

## Tipe Metriks Pengujian Perangkat Lunak
1. Process metriks, untuk memperbaiki efisiensi tahapan SDLC(Software Development Life Cycle) dan mengukur karakteristik pengembangan perangkat lunak.
2. Product metriks, mengukur karakteristik produk perangkat lunak.
3. Project metriks, untuk mengukur seberapa bagus peningkatan efisiensi tim.

#

## Life Cycles of Software Testing Metrics
1. Analysis, mengidentifikasi metriks untuk perangkat lunak yang diuji.
2. Communicate, menjelaskan pentingnya metriks kepada stakeholder dan tim testing.
3. Evaluation, melakukan perhitungan metriks berdasarkan verifikasi dan validasi data yang sudah dilakukan sebelumnya.
4. Reports, melaporkan hasil yang didapat kepada stakeholder, developer, dan tim testing.

#

## Jenis Metriks
1. Rework Effort Ratio
2. Requirement Creep
3. Schedule Variance
4. Cost of Finding a Defect in Testing
5. Schedule Slippage
6. Passed Test Cases Percentage
7. Failed Test Cases Percentage
8. Blocked Test Cases Percentage
9. Fixed Defects Percentage
10. Accepted Defects Percentage
11. Defects Deferred Percentage
12. Critical Defects Percentage
13. Average Time For a Development Team to Repair Defects
14. Number of Tests Run Per Time Period
15.  Test Design Efficiency
16. Test Review Efficiency
17. Bug Find Rote or Number of Defects Per Test Hours

#

# Bagian Akhir
# ------    Pertanyaan dan Jawaban   ------

### 

- BAB 5<br>
a. Dita 
Pertanyaan: <br>
Pada manfaat metode blackbox testing tepatnya bagian ketidakberpihakan dijelaskan bahwa mengikuti sudut pandang pengguna dan bukan sudut pandang perngambang sedangkan penggunaan satu proses tergantung pada pedndapat pengambang, apakah maksud dari penjelesan tersebut ?
Jawab: <br>
Maksud dari penjelasan sudut pandang ketidakberpihakan antara pengguna dan pengembang tersebut ialah keputusan disetujui atau tidak hasil pengujian boleh dari pengguna, namun dalam proses perncangan tetap dilakukan oleh pengembang.<br>

- KELOMPOK 7 <br>
a. Fransiska
Pertanyaan: <br>
Apa yang dimaksud probabilitas dan dampak pada tingkatan bug? <br>
Jawab: <br>
Dimensi probabilitas menggambarkan seberapa sering bug muncul pada perangkat lunak. Sedangkan dimensi dampak 
menggambarkan seberapa besar dampak bug terhadap perangkat lunak baik dari segi teknis maupun proses bisnis yang terjadi.

- KELOMPOK 8 <br>
a. Thalia Amira : <br> 
Pertanyaan: <br>
Berikan 1 contoh diantara beberapa jenis metriks! Serta apa yang dimaksud rework effort ratio itu apa? <br>
Jawab: <br>
Rework Effort Ratio = (Actual rework  efforts spent in that phase/ total actual efforts spent in that phase) X 100
Total Effort for Rework = 10 
Total Effort for Project = 200 
Rework Effort % =(10/200)*100= 5 %.<br>
Rework Effort Ratio, yaitu rumus untuk menghitung rasio effort dari pengerjaan ulang suatu perangkat lunak.<br>
b. Ardila Lukita:  <br> 
Pertanyaan: <br>
Apakah semua jenis metrik diitung dalam pengujian ?
Jawab: <br>
Untuk semua jenis metrik tersebut tidak harus dilakukan perhitungan, karena dalam pengujian perangkat lunak tidak selalu semua permasalahan dapat ditemukan. Jadi, semisal ketika pengujian menemukan 3 permasalahan, maka hanya 3 metrik yg bisa digunakan untuk menghitung penyelesaian dari permasalahan


