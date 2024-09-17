# Rangkuman PPL Pertemuan 4
# Bab 10 UAT ( User Acceptance)
TUJUAN : Mengembangkan perangkat lunak yang sesuai kebutuhan pengguna baik keinginan atau fungsi. Untuk memenuhi kebutuhan tersebut maka diperlukan kriteria kriteria yang dapat menggambarkan kebutuhan dari pengguna atau disebut dengan acceptan criteria.

A. KONSEP UAT

Acceptance testing adalah metode pengujian formal yang dilakukan oeh pengguna untuk mengetahui apakah aplikasi yang dikembangkan sesuai dengan kriteria yang ditetnutkn oleh pengguna. UAT biasanya menjadi
kesempatan terakhir bagi pengguna untuk memastikan kesesuaian perangkat lunak yang
dikembangkan dengan kebutuhan yang diinginkan.

Kriteria kelayakan yang ditentukan :
1. Data Realibilitas : ketetapan waktu konsistensi dari data yang digunakan
2. Orang: seorang pengguna perangkat lunak
3. Struktur : pengembangan perangkat lunak yang tepat dengan
mengoptimalkan teknologi untuk memenuhi kebutuhan

B. Syarat melakukan UAT
1. Harus ada kebutuhan bisnis
2. perangkat lunak sudah harus dikembangkan
3. bug dengan sifat minor masih dapat ditoleransi
4. bug ynag ditemukan harus diperbaiki sebelum UAT

C. Acceptance Test Plan

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

4. Deskripsi penerimaan perangkat lunak
- Tujuan dari keseluruhan proyek
- Kebutuhan informasi
- Bentuk keputusan penerima

D. USE CASE TEST DATA

digunakan acceptance test tidak jauh berbeda dengan yang digunakan pada pengujian unit maupun sistem. Namun, pada konteks pengujian, use
case menurut merupakan sebuah test case yang merepresentasikan bagaimana perangkat
lunak bekerja.

komponen acceptance test :
- kondisi use case dijalankan
- langkah langkah menjalankan use case

#
# MATERI PPL 24 SEPTEMBER 2021 
## Menginstal Cypress
1. Mengetikkan **npm init -y** di sebuah folder yang akan kita jadikan projek
2. Mengetikkan **npm install cypress --save-dev** untuk menginstall cypress
3. Membuka Cypress dengan kode **npx cypress open**
4. Setelah keluar tools Cypress sudah dipastikan kita sudah berhasil
#
