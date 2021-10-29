# Pertemuan 06 (08 Oktober 2021)

--Kelas Kosong--

## Tugas 2- Automatic test menu
Menginstall laravel cypress integration pada project laravel kita (https://github.com/laracasts/cypress). Kemudian dilanjutkan dengan pembuatan test case dan skenario test berdasar fitur yang sudah ada di dalam project laravel (satu mahasiswa satu fitur). Lakukan penguji fitur-fitur project laravel menggunakan cypress automatic test. 

## Project Laravel + Cypress Integration
1. Installation
    1. Buka file project laravel 
    2. arahkan ke cmd-> buka pada vscode
    3. Tambahkan Cypress direktori ./cypress ke root proyek Anda, serta file konfigurasi cypress.json. Terminal --> (npm install cypress --save-dev && npx cypress open)
    4. Tambahkan Base URL pada cypress.json
    ({"baseUrl": "http://my-app.test"})
    5. Install Composer : terminal --> (composer require laracasts/cypress --dev)
    6. Lanjutkn dengan --> (php artisan cypress:boilerplate)

    That's it! You're ready to go.

    Untuk melakukan pengkodingan test otomatis maka masuk pada folder Project laravel --> Cypress --> Integration.

    Di folder integration lah kita akan meletakkan hasil koding tes otomatis pada project laravel.


## Membuat Test Case & Scenario Fitur Project Laravel yang akan di Uji

https://docs.google.com/spreadsheets/d/1Nveqz5Q3EHeSH96EesipqdXY5xtbA4FU/edit#gid=800814275

Project Laravel = laraschool

|  |  |
|--|--|
| ID Test Case | Skenario |
| TC-01 | Uji coba buka halaman website laraschool |						
| TC-02	| Uji coba login |						
| TC-03	| Uji coba buka halaman navbar tentang, kontak, artikel, pengumuman |				
| TC-04	| Uji coba buka halaman dashboard |				
| TC-05	| Uji coba menu Kategori Artikel |				
| TC-06	| Uji coba logout |
	
Terima Kasih