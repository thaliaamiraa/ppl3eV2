# Pertemuan 05 (01 Oktober 2021) Presentasi Tugas 1
    Tugas 1-Test Skenario & Case
    1. Cari project laravel 8 yang open source
    2. Buat test scenario dan test case untuk proses login
    3. Buat proses testing otomatis pake cypress untuk test case dan test scenario tersebut

## Presentasi Masing-masing Kelompok

## Project Laravel  (Sistem Penyewaan Alat Musik Berbasis Web) 
-->TEST SCENARIO : menetukan hal2 apa saja yang perlu diuji

-->TEST CASE : bagaimana dalam melakukan pengujian perangkat lunak

|  |  |
|--|--|
| No. Skenario | Deskripsi Skenario |
| TS-001 | Uji coba fitur login Valid |
| TS-002 | Uji Coba fitur login Invalid |

### Proses Login Valid 
ID Test Case : Login_TC_001
Skenario : Uji coba fitur login Valid
Test Case : Masukkan username dan password yang sudah terdaftar pada proses register
Langkah Pengujian :
1. Masuk halaman login
2. Masukkan username yang sudah terdaftar pada proses register
3. Masukkan password yang sudah terdaftar pada proses register
4. Klik button “Login”
Hasil yang diharapkan : Berhasil masuk kehalaman dashboard
Kondisi Pasca : username & password yang dimasukkan pada kolom login, berhasil terverifikasi dan masuk ke halaman dashboard
Status : Berhasil


### Proses Login Invalid 
ID Test Case : Login_TC_002
Skenario : Uji coba fitur login Invalid 
Test Case : Masukkan username dan password yang belum terdaftar pada proses register
Langkah Pengujian :
1. Masukkan halaman login
2. Masukkan username yang belum terdaftar pada proses register
3. Masukkan password yang belum terdaftar pada proses register
4. Klik button “Login”

Hasil yang diharapkan : Tetap berada di halaman login dengan pesan record “These credentials do not match our record”
Kondisi Pasca : username & password yang dimasukkan pada kolom login, tidak berhasil terverifikasi dan tetap berada dihalaman login
Status : Berhasil

## Basic Testing Command Pada Cypress
1. cy.visit() buka halaman web
2. cy.get() ambil selector
3. cy.click() click selector
4. cy.should() assersion

## Tugas 2- Automatic test menu
Menginstall laravel cypress integration pada project laravel kita (https://github.com/laracasts/cypress). Kemudian dilanjutkan dengan pembuatan test case dan skenario test berdasar fitur yang sudah ada di dalam project laravel (satu mahasiswa satu fitur). Lakukan penguji fitur-fitur project laravel menggunakan cypress automatic test. 

Terima Kasih
