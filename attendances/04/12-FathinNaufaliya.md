# Rangkuman Pertemuan 4

## BAB 10

**UAT (User Acceptance Test)**

Tujuan utama dari pengembangan perangkat lunak adalah membuat perangkat lunak yang sesuai dengan kebutuhan penggunanya. Untuk 
memenuhi kebutuhan tersebut, maka diperlukan kriteria-kriteria yang dapat menggambarkan 
kebutuhan dari pengguna atau disebut dengan acceptance criteria.

Acceptance criteria secara teori dibuat oleh pengguna. Hal ini karena pengguna yang 
lebih tau tentang kebutuhan yang mereka inginkan. Namun, pengembang perangkat lunak juga 
dapat ikut dalam proses penggalian acceptance criteria. Penentuan kriteria-kriteria yang 
digunakan dalam acceptance criteria dapat dilakukan sejak awal proses pengembangan 
perangkat lunak.

Apa hubungan antara acceptance criteria dengan user acceptance test (UAT)? 
Acceptance criteria merupakan acuan utama pada UAT. UAT dapat didefiniskan sebagai 
proses pengujian perangkat lunak yang dilakukan oleh pengguna untuk mengetahui apakah 
perangkat lunak yang kembangkan sesuai dengan kriteria-kriteria yang telah disepakati.

**Konsep UAT**

Acceptance testing merupakan metode pengujian formal yang dilakukan oleh pengguna 
(user) untuk mengetahui apakah aplikasi yang dikembangkan sesuai dengan kriteria yang 
ditentukan oleh pengguna sehingga pengguna dapat menerima aplikasi tersebut. Proses 
pengujian mengedepankan penerimaan perangkat lunak dari sudut pandang pengguna, 
sehingga dapat disebut dengan user acceptance test (UAT).

Proses acceptance test sendiri dilakukan selama proses pengembangan 
perangkat lunak. Proses ini dapat dilakukan pada setiap tahapan pengembangan perangkat 
lunak dan dapat dilakukan secara incremental. Dilakukan secara incremental maksudnya 
adalah penerimaan atau penolakan perangkat lunak terus dilakukan selama proses 
pengembangan perangkat lunak.

Acceptance test juga digunakan untuk memastikan kelayakan penggunaan perangkat 
lunak (fit for use). Sedangkan pada 
proses pengujian, proses pengujian harus memenuhi kriteria kelayaka yang ditentukan (degree 
of fit). Menurut [5], terdapat 4 komponen dalam kelayakan, yaitu :

1. Data

Reliabilitas (reliability), ketepatan waktu (timeliness), konsisitensi (consistency), 
kemanfaatan (usefulness) dari data yang digunakan dalam perangkat lunak.

2. Orang (People)

Orang dalam hal ini adalah seorang pengguna perangkat lunak. Pengguna harus 
memilik kemampuan dan kemauan untuk menggunakan perangkat lunak yang 
dikembangka.

3. Struktur

Maksud dari struktur adalah pengembangan perangkat lunak yang tepat dengan 
mengoptimalkan teknologi untuk memenuhi kebutuhan.

4. Aturan (Rules)

Prosedur yang harus diikuti dalam mengolah data pada perangkat lunak.

**Syarat Melakukan UAT**

1. Harus ada kebutuhan bisnis (business requirement) yang jelas.
2. Perangkat lunak sudah harus selesai dikembangkan.
3. Proses pengujian unit, integrasi, dan sistem telah diselesaikan.
4. Tidak ditemukan bug dengan tingkatan menengah (medium), atau tinggi (high) 
yang dapat menggangu berjalannya perangkat lunak.
5. Bug dengan sifat minor masih dapat ditoleransi.
6. Tidak ditemukan bug pada tingkatan major setelah melakukan regression testing.
7. Bug yang ditemukan harus diperbaiki sebelum UAT.
8. Seluruh matric pengujian sudah sesuai dengan batas toleransi yang disepakati.
9. Menyiapkan lingkungan (environment) khusus untuk UAT.
10. Menghapus akses pengembanga perangkat lunak ataupun penguji dari sistem 
sebelum melakukan UAT.

**Peran dan Tanggung Jawab Pada Proses UAT**

Terdapat 2 aktor utama dalam proses UAT, yaitu pengguna dan penguji 
perangkat lunak (software tester). Kedua aktor tersebut memiliki tanggung jawabnya masing-masing pada saat proses UAT. Sebagai seorang pengguna perangkat lunak, dalam proses UAT memiliki tanggung 
jawab sebagai berikut:

1. Mendefinisikan kriteria-kriteria perangkat lunak yang sesuai dengan kebutuhan 
perangkat lunak (acceptance criteria). Kriteria yang dimasukkan dalam daftar kriteria 
haruslah kriteria yang dapat diukur.
2. Menyediakan use case yang menjadi acuan pada proses UAT.
3. Melakukan pelatihan kepada pengguna lain dalam menggunakan perangkat lunak yang 
dikembangkan.
4. Menyediakan sumber daya yang dibutukan UAT, dalam hal ini dapat seorang personil, 
untuk melakukan UAT.
5. Membandingkan hasil pengujian (actual result) dengan apa yang diharapkan (expected 
result).
6. Membuat keputusan terakhir (final decision) apakah perangkat lunak sudah sesuai 
dengan acceptance criteria. Jika telah sesuai, pengguna juga dapat memutuskan apakah 
perangkat lunak yang dihasilkan dapat langsung digunakan tanpa perbaikan, atau 
digunakan dengan perbaikan dikemudian hari.

Berbeda dengan pengguna, menurut CSTE CBOK, seorang penguji perangkat lunak 
dapat memilih salah satu dari 3 peran dan tanggung jawab berikut,
1. Tidak ikut sama sekali dalam proses UAT. Pada kasus ini berarti pengembang dan 
penguji perangkat lunak mempercayakan sepenuhnya proses UAT kepada 
pengguna.
2. Berperan sebagai pendamping pengguna (advisor) pada saat proses UAT dengan 
asumsi, pengguna yang melakukan UAT tidak memiliki cukup kompetensi untuk 
melakukan UAT.
3. Berperan aktif dalam proses UAT secara sebagian maupun secara penuh.

**Acceptance Test Plan**

Terdapat 3 hal yang harus 
diperhatikan dalam acceptance test plan, yaitu,
1. Kriteria diterimanya perangkat lunak (acceptance criteria).
2. Perencanaan pengujian penerimaan perangkat lunak (acceptance test plan).
3. Data yang digunakan dalam use case pengujian (use case test data).

Terdapat beberapa 
informasi atau bagian (section) yang harus ada dalam dokumen acceptance test plan, yaitu,
1. Deskripsi proyek
Dapat berisi,

a. Tipe sistem atau perangkat lunak
b. Siklus hidup perangkat lunak
c. Deskripsi pengguna perangkat lunak
d. Kebutuhan fungsional yang harus dipenuhi
e. Antarmuka utama dari perangkat lunak
f. Ekpekstasi penggunaan dalam keadaan normal
g. Potensi penyalahgunaan perangkat lunak
h. Resiko
i. Hambatan
j. Standar dan penggunaan

2. Tanggung jawab pengguna
Dapat berisi,

a. Organisasi atau perorangan yang bertanggung jawab pada proses 
acceptance test berserta peran dan tanggung jawabnya
b. Kebutuhan sumber daya
c. Kebutuhan untuk bantuan otomatis (automatic support)
d. Penyediaan data
e. Pelatihan penggunaan sistem perangkat lunak

3. Prosedur administrative
Dapat berisi,

a. Pelaporan insiden
b. Pencatatan
c. Komunikasi antaran pengembang dan pengguna

4. Deskripsi penerimaan perangkat lunak
Dapat berisi,

a. Tujuan dari keseluruhan proyek
b. Ringkasan acceptance criteria
c. Kegiatan utama dalam proses acceptance test
d. Kebutuhan informasi
e. Bentuk keputusan penerimaan (acceptance decision)
f. Tanggung jawab terhadap keputusan penerimaan

**Use Case Test Data**

Secara umum, 
use case pada acceptance test juga dideskripsikan dengan komponen yang terdiri dari,
1. Kondisi sebelum use case dijalankan.
2. Langkah-langkah menjalankan use case.
3. Kondisi setelah use case dijalankan
