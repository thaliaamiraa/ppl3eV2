# UAT (User Acceptance Test)

## Konsep UAT

Acceptance testing merupakan metode pengujian formal yang dilakukan oleh pengguna untuk mengetahui apakah aplikasi yang dikembangkan sesuai dengan kriteria yang  ditentukan oleh pengguna sehingga pengguna dapat menerima aplikasi tersebut
Proses pengujian harus memenuhi kriteria kelayakan yang ditentukan (degree  of fit), yaitu:
1.	DataReliabilitas
2.	Orang Orang dalam hal ini adalah seorang pengguna perangkat lunak
3.	Struktur
4.	AturanProsedur

## Syarat Melakukan UAT
1.	Harus ada kebutuhan bisnis
2.	Perangkat lunak sudah harus selesai dikembangkan
3.	Proses pengujian unit, integrasi, dan sistem telah diselesaikan
4.	Tidak ditemukan bug dengan tingkatan menengah (medium), atau tinggi (high)  
5.	Bug dengan sifat minor
6.	Tidak ditemukan bug pada tingkatan major setelah melakukan regression testing.
7.	Bug yang ditemukan harus diperbaiki sebelum UAT
8.	Seluruh matrix pengujian sudah sesuai dengan batas toleransi
9.	Menyiapkan lingkungan (environment) khusus
10.	Menghapus akses pengembanga perangkat lunak

## Acceptance Test Plan
Terdapat beberapa  informasi atau bagian (section) yang harus ada dalam dokumen acceptance test plan
1.	Terdapat beberapa  informasi atau bagian (section) yang harus ada dalam dokumen acceptance test plan
    a.	Tipe sistem atau perangkat lunak 
    b.	Siklus hidup perangkat lunak 
    c.	 Deskripsi pengguna perangkat lunak 
    d.	Kebutuhan fungsional yang harus dipenuhi
    e.	Antarmuka utama dari perangkat lunak 
    f.	Ekspektasi penggunaan dalam keadaan normal 
    g.	Potensi penyalahgunaan perangkat lunak 
    h.	Resiko 
    i.	Hambatan 
    j.	Standar dan penggunaan 
2.	Tanggung jawab pengguna 
    a.	Organisasi atau perorangan yang bertanggung jawab pada proses 	acceptance test beserta peran dan tanggung jawabnya 
    b.	Kebutuhan sumber daya 
    c.	Kebutuhan untuk bantuan otomatis (automatic support) 
    d.	Penyediaan data 
    e.	Pelatihan penggunaan sistem perangkat lunak
3.	Prosedur administrative 
    a.	Pelaporan insiden 
    b.	Pencatatan 
    c.	Komunikasi antara pengembang dan pengguna 
4.	Deskripsi penerimaan perangkat lunak
    a.	Tujuan dari keseluruhan proyek
    b.	Ringkasan acceptance criteria 
    c.	Kegiatan utama dalam proses acceptance test 
    d.	Kebutuhan informasi 
    e.	Bentuk keputusan penerimaan (acceptance decision) 
    f.	Tanggung jawab terhadap keputusan penerimaan 
    
 ## Use Case Test Data 
Terdapat perbedaan yang mendasar antara use case yang digunakan pada pengujian sistem dan pada acceptance test. Pengujian pada unit, integrasi, dan sistem lebih fokus kepada fungsionalitas komponen, sedangkan pada acceptance test lebih fokus kepada  transaksi bisnis yang terjadi pada perangkat lunak. 
Use case pada acceptance test juga dideskripsikan dengan komponen yang terdiri dari:
1.	Kondisi sebelum use case dijalankan. 
2.	Langkah-langkah menjalankan use case. 
3.	Kondisi setelah use case dijalankan.




