# UAT (User Acceptance Test) (Kelompok 10)
Bertujuan untuk membuat perangkat lunak yang sesuai dengan kebutuhan penggunanya, baik keinginan & fungsi. Untuk memenuhi kebutuhan tersebut, maka diperlukan acceptance criteria.

Konsep UAT
Acceptance testing merupakan metode pengujian formal yang dilakukan oleh pengguna untuk mengetahui apakah aplikasi yang dikembangkan sesuai dengan kriteria yang  ditentukan oleh pengguna sehingga pengguna dapat menerima aplikasi tersebut. UAT biasanya menjadi  kesempatan terakhir bagi pengguna untuk memastikan kesesuaian perangkat lunak yang  dikembangkan dengan kebutuhan yang diinginkan. 

Syarat melakukan UAT:
1. Harus ada kebutuhan bisnis yang jelas.
2. Perangkat lunak sudah harus selesai dikembangkan.
3. Proses pengujian unit, integrasi, dan sistem telah diselesaikan.
4. Tidak ditemukan bug dengan tingkatan menengah (medium), atau tinggi (high)  yangdapat mengganggu berjalannya perangkat lunak.
5. Bug dengan sifat minor masih dapat ditoleransi. 
6. Tidak ditemukan bug pada tingkatan major setelah melakukan regression testing.
7. Bug yang ditemukan harus diperbaiki sebelum UAT. 
8. Seluruh matrix pengujian sudah sesuai dengan batas toleransi yang disepakati.
9. Menyiapkan lingkungan (environment) khusus untuk UAT.
10. Menghapus akses pengembanga perangkat lunak ataupun penguji dari sistem  sebelum melakukan UAT.

Acceptance Test Plan
Acceptance test plan merupakan dokumen yang berisi perencanaan sebelum melakukan acceptance test. Dokumen ini digunakan sebagai acuan agar proses pengujian dapat dikontrol  dan dikondisikan sesuai dengan kondisi yang diharapkan. Terdapat beberapa  informasi atau bagian (section) yang harus ada dalam dokumen acceptance test plan, yaitu:

1. Deskripsi Proyek
2. Tanggung jawab pengguna
3. Prosedur administratif
4. Deskripsi penerimaan perangkat lunak

Use Case Test Data
Data use case yang digunakan dalam acceptance test tidak jauh berbeda dengan yang  digunakan pada pengujian unit, integrasi, maupun sistem.


# Belajar Cypress

Dalam install cypress kita harus memiliki node js & vscode. Setelah kita mempunyai 2 requirement tersebut, kita bisa menginstall cypress dengan cara:
1. Buat Folder Project
2. Buka cmd arahkan ke folder project yang suda kita buat
3. Lalu ketikkan npm init -y
4. Setelah selesai melakukan langkah diatas, ketikkan npm install cypress --save-dev (Install Cypress Dependency)
5. Cypress berhasil diinstall.

Cara membuka cypress:
1. Ketikkan npx cypress open, cypress akan membuka dengan sendirinya.
2. Jika ingin switch to browser ketikkan "npx cypress run --browser {nama-browser}".
3. Jika ingin menggunakan custom script tinggal tambah script ""open":"npx cypress open"" di object "scripts" package.json
4. Jika sudah ada script diatas kita bisa jalankan cypress dengan "npm run open"

Jika ingin membuat file testing baru:
1. Isi kan syntax kedalam json
2. Lalu run cypress
3. Pilih file json yang sudah dibuat
4. Cypress akan otomatis menguji apakah terdapat error di file tersebut.


