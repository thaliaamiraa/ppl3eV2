# Rangkuman BAB 10
# ------     UAT (User Acceptance Test )   ------


## UAT (User Acceptance Test )
    User Acceptance Test atau yang biasa disebut dengan UAT ialah salah satu tahapan dalam testing perangkat lunak yang akan melakukan proses verifikasi bahwa solusi yang dibuat dalam sistem sudah sesuai dengan requirement dan kebutuhan user / pengguna.
#

Tujuan utama dari pengembangan perangkat lunak ialah pada dasarnya untuk membuat perangkat lunak yang sesuai dengan kebutuhan para user / pengguna, baik itu dari segi keinginan maupun fungsi dari sistem itu sendiri. Dalam memenuhi kebutuhan pengguna, diperlukan acceptance criteria.

#

## Hubungan Acceptance Criteria & User Acceptance Test (UAT)

-  Acceptance criteria merupakan acuan utama dalam UAT, yang mana di dalam proses pengujian perangkat lunak yang dilakukan oleh pengguna untuk mengetahui apakah perangkat lunak yang sudah dikembangkan tersebut sesuai dengan requirement yang sebelumnya sudah disepakati atau tidak.

#

## Konsep UAT
User Acceptance Test (UAT) ini sendiri biasanya menjadi tahapan sekaligus kesempatan terakhir bagi para user / pengguna untuk memastikan apakah sistem / perangkat lunak yang dikembangkan sudah sesuai dengan keinginan mereka atau belum, meskipun pada dasarnya / secara formal UAT dilakukan sebelum perangkat lunak digunakan oleh para user / pengguna.

#

## Tahapan Terakhir Dalam UAT
UAT sendiri memiliki tahapan terakhir berupa pengambilan keputusan apakah aplikasi yang dikembangkan dapat diterima oleh pengguna atau tidak. Untuk itu, pada tahapan terakhir ini akan ada proses pengujian yang dilakukan untuk menguji kelayakan sistem dengan menggunakan "degree of fit" diantaranya :
1. <b>Data reliabilitas</b>, menguji ketepatan waktu, konsistensi, kebermanfaatan data yang digunakan dalam sistem / perangkat lunak.
2. <b>Orang</b>, disini yang dimaksud ialah user / pengguna sistem / perangkat lunak yang mmeiliki kemampuan dan kemauan untuk menggunakan perangkat lunak.
3. <b>Struktur</b>, pengembangan perangkat lunak yang tepat dengan mengoptimalkan teknologi untuk memenuhi kebutuhan.
4. <b>Aturan prosedur</b>, salah satu bagian yang harus diikutkan saat proses pengelolaan data pada perangkat lunak.

#

## Syarat Melakukan UAT
1. Kebutuhan bisnis (business requirement) harus sudah jelas.
2. Perangkat lunak sudah selesai dikembangkan.
3. Tidak ditemukan bug dengan tingkat medium atau high.
4. Bug dengan sifat minor masih dapat di toleransi.
5. Tidak ditemukan bug major saat proses regression testing.
6. Bug yang ditemnukan harus diperbaiki sebelum tahapan UAT.
7. Seluruh matriks pengujian harus sesuai dengan batas toleransi yang sudah disepakati bersama.
8. Proses pengujian unit, integrasi, dan sistem telah terselesaikan dengan baik.
9. Menyiapkan lingkungan khusus untuk UAT.
10. Menghapus akses pengembang dan penguji perangkat lunak dari sistem. 

#

## Dokumen Acceptance Test Plan
Terdapat beberapa bagian yang harus ada dalam dokumen UAT, diantaranya :

1. Deskripsi proyek :
-  Tipe sistem atau perangkat lunak
-  Siklus hidup perangkat lunak
-  Deskripsi pengguna perangkat lunak
-  Kebutuhan fungsional
-  Antarmuka utama dari perangkat lunak
-  Ekspektasi pengguna dalam keadaan normal
-  Potensi penyalahgunaan perangkat lunak
-  Risiko
-  Hambatan
-  Standar dan penggunaan

2. Tanggung jawab pengguna :
-  Deskripsi peranan masing - masing organisasi / perorangan
-  Kebutuhan sumber daya
-  Automatic support
-  Penyedia data
-  Pelatihan penggunaan sistem

3. Prosedur administrative :
-  Pelaporan insiden
- Pencatatan
- Komunikasi pengembang dan user

4. Deskripsi penerimaan perangkat lunak :
-  Tujuan proyek
-  Ringkasan UAT
-  Kegiatan utama UAT
-  Kebutuhan informasi
-  Bentuk keputusan UAT
-  Tnaggung jawab terhadap keputusan yang ada

#

## Use Case Test Data
Use case pada UAT dibangun oleh beberapa komponen meliputi :
1. Kondisi sebelum use case dijalankan.
2. Langkah dalam menjalankan use case.
3. Kondisi setelah use case dijalankan.