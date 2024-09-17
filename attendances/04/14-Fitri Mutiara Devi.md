# RANGKUMAN PERTEMUAN 4

## BAB 10 : UAT (User Acceptance Test)

Tujuan utama -> membuat perangkat lunak yg sesuai dgn kebutuhan penguna.
 
Konsep UAT -> metode pengujian formal yang dilakukan oleh pengguna (user) untuk mengetahui apakah aplikasi yang dikembangkan sesuai dengan kriteria yang ditentukan oleh pengguna sehingga pengguna dapat menerima aplikasi tersebut. Proses pengujian harus memenuhi kriteria kelayakan yang ditetentukan (degree of fit), yaitu :
1. Data -> Reliabilitas, ketepatan waktu, konsisitensi, kemanfaatan dari data yang digunakan dalam perangkat lunak.
2. Orang -> Pengguna perangkat lunak yang memiliki kemampuan  dan kemauan untuk menggunakan perangkat lunak yang dikembangkan.
3. Sruktur -> pengembangan perangkat lunak yang tepat dengan mengoptimalkan teknologi untuk memenuhi kebutuhan.
4. Aturan -> Prosedur yang harus diikuti dalam mengolah data pada perangkat lunak.

Syarat Melakukan UAT
1. Harus ada kebutuhan bisnis (business requirement) yang jelas.
2. Perangkat lunak sudah harus selesai dikembangkan.
3. Proses pengujian unit, integrasi, dan sistem telah diselesaikan.
4. Tidak ditemukan bug dengan tingkatan menengah (medium), atau tinggi (high)
5. Bug dengan sifat minor masih dapat ditoleransi.
6. Tidak ditemukan bug pada tingkatan major setelah melakukan regression testing.
7. Bug yang ditemukan harus diperbaiki sebelum UAT.
8. Seluruh matric pengujian sudah sesuai dengan batas toleransi yang disepakati.
9. Menyiapkan lingkungan (environment) khusus untuk UAT.
10. Menghapus akses pengembanga perangkat lunak ataupun penguji dari system

Acceptance Test Plan -> dokumen yang berisi perencenaan sebelum melakukan acceptance test. 

3 hal yang harus diperhatikan dalam acceptance test plan, yaitu,
1. Kriteria diterimanya perangkat lunak
2. Perencanaan pengujian penerimaan perangkat lunak
3. Data yang digunakan dalam use case pengujian

Terdapat beberapa informasi atau bagian (section) yang harus ada dalam dokumen acceptance test plan, yaitu :
1. Deskripsi proyek
2. Tanggung jawab pengguna
3. Prosedure admin istrative
4. Deskripsi penerimaan Perangkat lunak

Use Case Test Data
Terdapat perbedaan yang mendasar antara use case yang digunakan pada pengujian sistem dan pada acceptance test. Pengujian pada unit, integrasi, dan sistem lebih fokus kepada fungsionalitas komponen, sedangkan pada acceptance test lebih fokus kepada  transaksi bisnis yang terjadi pada perangkat lunak. 
use case pada acceptance test juga dideskripsikan dengan komponen yang terdiri dari:
1. Kondisi sebelum use case dijalankan. 
2. Langkah-langkah menjalankan use case. 
3. Kondisi setelah use case dijalankan.
