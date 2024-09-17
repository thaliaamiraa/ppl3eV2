# Rangkuman PPL Pertemuan 5
# Clone Repository yang disepakati oleh 1 kelompok

Pada Pertemuan 5 Mata Kuliah Pengujian Perangkat Lunak ini, kita 1 kelompok menggunakan projek laravel yang telah didiskuiskan. Setelah mendapatkan projek laravel yang akan diujikan kita mengclone dan membuat folder baru di dalam folder integration dan file baru bertipe .js yang isinya adalah sintaks-sintaks yang digunakan untuk melakukan automatic test case. Beberapa sintaks diantaranya :
- cy.visit  : Membuka halaman website .
- cy.get    : Pengambilan seelctor.
- cy.click  : Mengklik selector
- cy.should : Digunakan dalam assersion
#
# Menguji Fitur Login dan membuat 5 skenario

1. Email dan password valid

Pada skenario ini menggunakan sintaks cy.visit, cy.get dan cy.should. Sistem akan otomatis membuka web dan memasukkan email dan password secara benar.

2. Email dan Password invalid

Pada skenario ini menggunakan sintaks cy.visit, cy.get dan cy.should. Sistem akan otomatis membuka web dan memasukkan email dan password secara salah dan tidak bisa membuka halaman selanjutnya.

3. Login dengan kolom kosong

Pada skenario ini menggunakan sintaks cy.visit, cy.get dan cy.should. Sistem akan otomatis membuka web dan memasukkan email benar dan tanpa memasukkan password, namun yang terjadi cypress masih error.

4. Login dengan keyboard enter

Pada skenario ini menggunakan sintaks cy.visit, cy.get dan cy.should. Sistem akan otomatis membuka web dan memasukkan email dan password secara benar lalu langsung klik enter, bukan klik button login.

5. Menu create new account

Pada skenario ini menggunakan sintaks cy.visit, cy.get dan cy.contains. Sistem akan masuk halaman login lalu pilih create new account dan menampilkan halaman membuat akun.

#
# Tugas

Membuat Test Case dan Test Scenario di dalam projek laravel. Satu mahasiswa harus membuat test case dan test skenario satu fitur dan tidak boleh sama dengan mahasiswa lain. 
