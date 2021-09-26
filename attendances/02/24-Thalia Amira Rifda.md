# Pertemuan 02
Buatlah Rangkuman Pertemuan Kedua

# BAB 9 - TEST PLAN
    DOKUMEN TEST PLAN 
    -> Dokumen yang mendefinisikan aktifitas yang dilakukan saat pengujian software atau sistem.

    Terdapat 19 standart IEEEE Test Plan :
    1. Test Plan identifier
    2. REFERENCES
    3. Introduction
    4. test Items
    5. Software Risk Issues
    6. Features To Be Tested
    7. Features Not To Be Tested
    8. Aproach
    9. Item Pass/ Fail Criteria
    10. SUspension Criteria And Resumption Requerments
    11. Test Deliverables
    12. Remaining Test Tasks
    13. Enviromental Needs
    14. Schedule
    15. Approvals
    16. Staffing And Training Needs
    17. Planning Risk And Contigencies
    18. Responsiblities
    19. Glossary

### Pertanyaan bab 9
1.Thalia Amira R.

Jelaskan secara singkat apa saja manfaat dan tujuan dari test plan ?

Jawaban: 

Test plan digunakan untuk tujuan agar testing dilakukan sesuai arah, baik dari segi bagian yang diujikan, rentang waktu maupun penanggung jawab dari testing. dokumen ini juga tergantung kesepakatan antara pihak developer dengan tester

2.M Yudha Erian S.

Sebutkan apa saja contoh dari glossary ?

Jawaban:

Dokumen test plan merupakan dokumen umum yang dapat dibaca oleh orang TI maupun non-TI, sehingga terdapat istilah awam orang yang non-TI tidak memahami beberapa kalimat dalam suatu dokumen. contoh: hardware, requirement, software.

# BAB 2 - KLASIFIKASI PENGUJIAN PERANGKAT LUNAK
Klasifikasi pengujian perangkat lunak dibagi menjadi 2 tipe pendekatan :
### 1. Pengujian Fungsional
    -> Merupakan pengujian dengan memvalidasi fungsi/ fitur-fitur yang terdapat didalam perangkat yang dibuat, apakah sesuai dengan kebutuhan fungsional yang sudah ditetapkan.
    Ex : Validasi fitur login, CRUD dll 
    
    Pengujian dilakukan dengan menggunakan :
    Black Box Testing dan White Box Testing
### 2. Pengujian Non-Fungsional
    -> Merupakan pengujian kinerja sistem.
    Ex : Kecepatan sistem, manajemen memori dll

### Pertanyaan bab 2 :
1.Zalna Rahma

Apa persamaan pengujian fungsional dan non-fungsional ?

*Jawaban* : 

Sama-sama pengujiannya dapat menggunakan cara Manual Testing(Uji secara manual) dan Automated Testing (Pengujian secara otomatis)

2.Devi Puspita Sari

Apa kelemahan dari pengujian fungsinal dan non-fungsional ?

*Jawaban* : 

Kelemahan dari kedua pengujian yakni di bagian biaya uji sistem. Sama-sama Mahal.

# BAB 4 - UNIT TESTING DENGAN JEST
### A. Instalasi NodeJS
    Berikut merupakan langkah-langkah installasi NodeJS
    1. Buka website NodeJs
    2. Melakukan Instalasi NodeJS sampai selesai
    3. Melakukan Pengecekan versi node dan npm menggunakan cmd

### B. Membuat Proyek NodeJS
    Berikut merupakan langkah-langkah mebuat proyek NodeJS
    1. Buat folder bernama *sesuai yang diinginkan, kemudian pada address bar folder ketik cmd kemudian enter
    2. Muncul layar cmd ketik perintah npm init untuk membuat proyek
    3. Kemudian ketikan nama package *sesuai dengan yang dinginkan
    4. Entry point
    5. Git Repository
    6. File package.json berhasil dibuat

### C. Installasi Jest
    -> Jest merupakan framework untuk menguji unit testing pada proyek dengan bahasa pemrograman java script khususnya berbasis NodeJS.
    Berikut merupakan langkah-langkah installasi Jest
    1. Membuka folder yang sudah dibuat sebelumnya
    2. Pada address bar ketikkan cmd, akan tampil halaman cmd kemudian
    3. ketikkan npm install --save-dev jest
    4. Tunggu installasi selesai
    5. Ketika sudah selesai buat file di Visual Studio Code

### D. Membuat Unit Test Sederhana
    Berikut merupakan langkah-langkah membuat unit test sederhana
    1. Buka VSCode, buatlah file dengan nama tambah.js
    2. Ketikkan coding sederhana
    3. Lalu membuat file dengan nama tambah.js
    4. Ubah coding pada package.json
    5. Pada Jest dapat menggunakan flag --coverage untuk informasi tentang code coverage, branch, function, dan line 

### Pertanyaan bab 4 :
1.Fransiska

Apakah pada penamaan file tambah.test.js harus default nama test atau bisa ditentukan dan juga apa sintak function dapat diubah-ubah ?

*Jawaban* : 

Untuk penamaan file tambah.test.js dapat diubah akan tetapi pada .test harus sesuai mengacu pada file package.json yang dimana disana ada code sintak test yang digunakan untuk eksekusi pada terminal/cmd dan kemudian pada penamaan code sintak function dapat diubah dengan ketentuan pada code sintak berkutnya harus mengikuti nama function yang di ubah.


