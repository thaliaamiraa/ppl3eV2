# Pertemuan 03

Buatlah Rangkuman Pertemuan Ketiga

## Bab 5 Black Box Testing 
Metode pengujian perangkat lunak tanpa mengetauhi struktur internal, didasarkan pada detail aplikasi seprerti tampilan, fungsi, dan kesesuain pada alur fungsi business proses. black box testing lebih menguji ke tampilan interface agar mudah digunakan oleh pengguna. ada 7 teknik teknik blackbox testing equivalence partitioning, boundary value analysis, Decision Table Testing, State Transtition Testing, Graph Based Testing, Error guessing, dan common comparision. salah satu kekurangan black box testing adalah beberapa backend tidak diuji

Pertanyaan :
1. Dita Nur A. : Maksud dari penggunaan satu proses daripada yang lain, tergantung pada pendapat pengembang

    Jawab : pengujian boleh dari pengguna tapi pengembang sebagai perancang.

## Bab 7 Pelaporan Bug 
Bug merupakan kegagalan yang mengakibatkan kesalahan dalam perangkat lunak. penting dilakukan agar ketidak sesuaian dalam perangkat lunak dapat segera ditemukan dan diperbaiki

karakteristik pelaporan bug: objektif, spesifik, ringkas, dapat diulang, eksplisit dan persuasif. 

tingkatan bug ada 4 tingkat mulai dari severity-1 errors, severity-2 errors, severity-3 errors, dan severity-4 errors.

status bug : new, assigned, rejected, fixed, ready to test, failed re-test, dan closed.


Pertanyaan :
1. Fransiska L. : maksud dari probabilitas dari pengklasifian 

    jawab : Dimensi probabilitas menggambarkan seberapa sering bug muncul pada perangkat lunak. Sedangkan dimensi dampak menggambarkan seberapa besar dampak bug terhadap perangkat lunak baik dari segi teknis maupun proses bisnis yang terjadi. Dari dimensi dan tingkatan tersebut, dihasilkan 4 tingkatan bug, yaitu trivial, minor, dan major.

## Bab 8 Metriks pengujian perangkat lunak 

Daur kerja software testing metrics terdiri dari analysis, communicate, evaluation dan reports. jenis metriks ada 17 macam yang nantinya digunakan untuk mengujikan angka lalu dianalisis berdasarkan klasifikasinya.

pertanyaan :
1. thalia : penjelasan jenis metriks lalu contoh salah satu penggunaan.

    jawab : rumus yang digunakan untuk menghitung berdasarkan klasifikasinya
    
    Rework Effort Ratio = (Actual rework  efforts spent in that phase/ total actual efforts spent in that phase) X 100

    Total Effort for Rework = 10 

    Total Effort for Project = 200 
    Rework Effort % =(10/200)*100= 5 %

    rumus untuk menghitung rasio effort dari pengerjaan ulang suatu perangkat lunak.
2. ardila : apakah semua rumus dalam jenis metriks harus dimasukkan semua dalam laporan?

    jawab : semua jenis metrik tidak di hitung, karen a dalam pengujian perangkat lunak tidak mesti semua permasalahan di temukan. jadi misal ketika pengujian menemukan 3 permasalahan, hanya 3 metrik yg bisa digunakan untuk menghitung penyelesaian dari permasalahan

## Bab 6 Skenario Pengujian dan Kasus Uji 
Skenario pengujian adalah aktivitas yang menentukan hal hal apa saja yang perlu diuji dalam pengujian perangkat lunak. dokumen skenario PPL ada 3 yaitu ID skenario pengujian, ID kebutuhan, dan deskripsi skenario pengujian.

kasus uji adalah bentuk detail dari skenario pengujian. komponen kasus uji meliputi id testcase, id skenario pengujian, test case, pra kondisi, langkah pengujian, data uji, hasil yang diharapkan, pasca kondisi,hasil yang terjadi, dan testcase. kegunaan testcase melakukan blackbox dan whitebox testing.

## Bab 3 Pengujian White Box 

White box testing adalah testing yang berdasarkan dari kode programnya. terdapat 3 teknik utama yaitu statement coverage, branch coverage, dan path coverage. Statement coverage merupakan metode untuk memvalidasi  bahwa kode program yang ditulis di eksekusi paling tidak sekali sesuai dengan logika kode program yang berjalan. branch coverage metode testing yang dilakukan untuk memastikan bahwa setiap branch pada kode program di eksekusi. Path coverage digunakan untuk menguji semua path yang ada pada program.