# BAB 10 - User Acceptance Test

Tujuan utama dari pengembangan perangkat lunak adalah membuat perangkat lunak  yang sesuai dengan kebutuhan penggunanya, baik keinginan dan fungsi. 
Untuk  memenuhi kebutuhan tersebut, maka diperlukan acceptance criteria. 

### A. KONSEP UAT

Acceptance testing adalah metode pengujian formal yang dilakukan oeh pengguna untuk mengetahui apakah aplikasi yang dikembangkan sesuai dengan kriteria yang ditetnutkn oleh pengguna. 
UAT biasanya menjadi kesempatan terakhir bagi pengguna untuk memastikan kesesuaian perangkat lunak yang dikembangkan dengan kebutuhan yang diinginkan. 
Meskipun secara formal acceptance test dilakukan sebelum perangkat lunak digunakan  oleh pengguna.

Proses pengujian harus memenuhi kriteria kelayakan yang ditentukan (degree  of fit), yaitu:

1. DataReliabilitas, ketepatan waktu, konsistensi, kemanfaatan dari data yang digunakan dalam perangkat lunak.
2. Orang Orang dalam hal ini adalah seorang pengguna perangkat lunak yg memiliki kemampuan dan kemauan untuk menggunakan perangkat lunak.
3. StrukturMaksud dari struktur adalah pengembangan perangkat lunak yang tepat dengan mengoptimalkan teknologi untuk memenuhi kebutuhan.
4. AturanProsedur yang harus diikuti dalam mengolah data pada perangkat lunak

### B. Syarat melakukan UAT

1. Harus ada kebutuhan bisnis
2. perangkat lunak sudah harus dikembangkan
3. bug dengan sifat minor masih dapat ditoleransi
4. bug ynag ditemukan harus diperbaiki sebelum UAT

### C. Acceptance Test Plan

Dokumen berisi perencana sebelum acceptance test

1. Deskripsi proyek
- Resiko
- Hambatan
2. Tanggung jawab pengguna
- Kebutuhan sumber daya
- Penyediaan data
- Pelatihan penggunaan sistem perangkat lunak
3. Prosedur administrative
- Pelaporan insiden 
- Pencatatan 
- Komunikasi antara pengembang dan pengguna 
4. Deskripsi penerimaan perangkat lunak
- Tujuan dari keseluruhan proyek
- Kebutuhan informasi
- Bentuk keputusan penerima

### D. USE CASE TEST DATA

digunakan acceptance test tidak jauh berbeda dengan yang digunakan pada pengujian unit maupun sistem. Namun, pada konteks pengujian, use case menurut merupakan sebuah test case yang merepresentasikan bagaimana perangkat lunak bekerja.

komponen acceptance test :

- kondisi use case dijalankan
- langkah langkah menjalankan use case

# PERTANYAAN 
-
# Materi Hari Ini
cara instal
buat folder 
buka folder d cmd
install cypress depedency
kemudian open
perintah ada di github

### Tugas
1. Cari project Laravel 8 yang open source
2. Buat test scenario dan test case untuk proses login
3. Buat proses testing otomatis pake cypress untuk test case dan test scenario tersebut
