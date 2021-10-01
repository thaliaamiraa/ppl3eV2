# Test Case & Scenario Case
Membuat Test Case & Scenario Case Menggunakan excel dab di implementasikan ke cypres. Dalam Test Case & Scenario Case Login yang dibutuhkan web laravel 8 dan data yang di uji berupa email dan password.

## Aturan Penggunaan Cypress
1. Pada pembuatan coding cypress setidaknya ada 1 describe dan 1 it agar dapat berjalan. 
2. saat melaukan test laravel harus di run dengan "php artisan serve".
3. saat ingin akses halaman laravel pada cypress bisa menggunakan cy.visit('isi tujuan web yang ingin di kunjungi').
5. saat ingin assert link yang dikunjungi bisa menggunakan cy.url('isi link halaman web laravel yang sedang dikunjungi').should
6. saat ingin cek kalimat pada halaman web bisa menggunalan cy.contains('isi kandungan kata pada halaman web');
7. saat ingin mengambil css/id bisa menggunakan cy.get('isi id pada html yang tertera').
8. saat ingin menuliskan pada input text bisa menggunakan type('isi inputan');

## Tugas Pertemuan Selanjutnya
Untuk penugasan minggu depan melakukan install laravel dab set up cypress ke laravel dan membuat cypress untuk menjalankan fitur pada laravel(masing-masing 1 orang membuat 1 fitur).
