# BAB 5 : blackbox testing

blackbox testing adalah pengujian perangkat lunak yang fungsional dugunakan untuk menguji perankat lunak tanpa menggunakan kode program.

teknik balcbox testing 
- quilanence partitioning dengan cara melakukan partition atau pembagian menjadi beberapa partisi


- Boundary Value Analysis dengan cara fokus kepada boundary, adakah error dari luar atau sisi dalam perangkat lunak

- Decision Table Testing degan cara pendekatan pengujian dengan mengidentifikasi dua buah output untuk dua kondisi yang berbeda (true/false). 

- State Transition Testing dengan cara menggunakan model ‘state’ pada sebuah diagram transisi dalam melakukan pengujian perangkat lunak. 

- Graph Based Testing dengan cara menggunakan beberapa objek, Setiap object diidentifikasikan sebagai graph.

- Error Guessing dengan cara pendekatan pengujian perangkat lunak yang membutuhkan pengalaman dari personil yang melakukan pengujian. 

- CommonComparison dengan cara membandingkan secara umum perangkat lunak yang dibuat atau fitur dari software terhadap perangkat lunak lain yang mirip.


kelebihan black-testing saat pengujian tidak memerlukan pengetahuan tentang bahasa pemrograman/kode program pada perangkat lunak

kekurangan black-box testing saat pengujian sulit melakukan desain spesifikasi dan sering terjadi error saat pengujian menggunakan kode program oleh programmer.


### Pertanyaan
Dita : 
pada manfaat metode blackbox testing pada ketidakberpihakan kenapa mengikuti sudut pandang pengguna dan bukan sudut pandang perngambang sedangkan penggunaan satu proses tergantung pada pedndapat pengambang ?

Jawaban.

maksud dari sudut pandang ketidakpihakan antara pengguna dan pengembang  jawaban pengujian boleh dari pengguna tapi pengembang sebagai perancang




# BAB 7 : Pelaporan bug

bug merupakan suatu kesalahan/kegagalan pada perangkat lunak.

- karakteristik pelaporan bug yang baik objektif, spesifiik, ringkas , dapat diulang, eksplisit dan peruasif

- tingkatan bug ada 4 tingkat mulai dari severity-1 errors, severity-2 errors, severity-3 errors, dan severity-4 errors.

- status pada bug ada new assigned rejected fixed ready to test dan failed re-test closed.


### Pertanyaan bab 7
Fransiska : 
Apa yang dimaksud probabilitas dan jelaskan dampak pada tiap tingkatan bug? 

Jawaban : 

Jadi Pengklasifikasian bug juga dapat dilakukan secara relatif sesuai dengan dimensi probabilitas dan dampak. Dimensi probabilitas menggambarkanseberapa sering bug muncul pada perangkat lunak. Sedangkan dimensi dampakmenggambarkan seberapa besar dampak bug terhadap perangkat lunak baik dari segi teknis 
maupun proses bisnis yang terjadi. Dari dimensi dan tingkatan tersebut, dihasilkan 4 tingkatan bug, yaitu trivial, minor, major dan critical.



# bab 9 :  Metriks Pengujian Perangkat Lunak

metriks pengujian perangkat lunak untuk mengukur secara kuantitatif untuk memperkirakan kemajuan, kualitas, produktivitas, dan kesehatan proses pengujian perangkat lunak.

tipe metrik pengujian pearnkat lunak

1. process metrics untuk memperbaiki efisiensi dari tahap SDLC

2. Product metrics untuk mengukur 

3. project metrics untuk mengukur seberapa bagus penginkatan efektifitas perangkat lunak.

### Life Cycles OF Software Testing Metrics 

analysis -> communicate -> Evaluation -> Reports.


### Jenis Metriks :
Jenis metriks ada banyak seperti Rework Effort Ratio, Requirment Creep, Schedule Variance dan lain-lain

jadi dengan Jenis Metriks memiliki rumus yang digunakan untuk pengujian.


Pertanyaan :

Thalia Amira:
Tolong contohkan perhitungan rumus menggunakan jenis metriks ?

Jawaban: 
Jadi ketika ada pengerjaan terjadi kesalahan akan di kerjakan ulang dengan menggunakan rumus Rework Effort Ratio.

Rework Effort Ratio = (Actual rework  efforts spent in that phase/ total actual efforts spent in that phase) X 100


Ardila :
Terdapat rumus 17 pengujian metrik dalam pengujian apa semua rumus dimasukan dalam pengujian ?

Jawaban :
untuk jenis metrik tidak dapat ditentukan, karen saat pengujian perangkat lunak tidak memiliki permasalahan yang sama.jika ada permasahalan di pertemukan ada beberapa software maka hanya butuh rumus metrix yang sesaui dengan data pada software/perangkat lunak.


# Bab 6 Skenario Pengujian dan Kasus uji

dalam uji skenario ini ada 2 pokok pembahasan yaitu 
1. skenario pengujian
suatu aktivitas untuk menentukan hal apa saja yang akan di ujikan pada perangkat lunak.

komponen Dokumen Skenario PPL :

- ID Skenario Pengujian
- ID Kebutuhan
- Deskripsi Skenario Pengujian


2. Kasus uji

suatu cara bagaimana kita melakukan pengujian perangkat lunak.

Komponen Kasus Kasus Uji

- ID Test Case
- ID Skenario Pengujian
- Test Case/kasus uji.
- Kondisi pra(pre condition)
- Langkah Pengujian
- Data Uji
- Hasil Yang diharapkan
- KOndisi pasca(post-condition)
- Hasil yang terjadi(Actual Result)
- Status

Kegunaan dari Test Case
untuk melakukan testing komponen dengan menggunakan Black box testing dan white box testing

Membuat Test Case:

hal yeng perlu diperhatikan membuat test case membuat test case dengan menggunaan prepektif pengguna akhir/end user dan hindari pengulangan test uji.


# Bab 3 : pengujian whitebox

White box testing merupakan pengujian terhadap kode program pada pembuatan perangkat lunak.

dalam white box terdapat statement yang terkenal yaitu 

statement coverag untuk melakukan pengujian pernyataan dari kode dengan perumpamaan if else.

branch coverage untuk melakukan pengujian dengan mengubah kode program menjadi sebuah flowchart.

path coverage untuk menguji path yang ada di program dengan meninjau jalur alur algoritma.











