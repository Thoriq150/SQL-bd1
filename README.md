# Tugas Praktikum  Basis Data
# A. Buat Table pegawai dan isi datanya seperti berikut:
<img width="960" alt="gambar 1 ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/3caf29b3-da21-428b-b3cc-7fb36496be23">

## 1. Tampilkan pegawai yang gajinya bukan 2.000.000 dan 1.250.000 !
#### - untuk menampilkan tabel bisa menggunakan opperator not in untuk menfilter data yg tidak ingin di tampilkan 

<img width="736" alt="gambar Praktikum 1 ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/c108dd9d-438d-42df-a934-92096374a03f">

## 2. Tampilkan pegawai yang tunjangannya NULL!
#### -untuk menampilkan tabel bisa menggunakan opperator is null untuk menampilkan yg null 
<img width="714" alt="gambar praktikum 2 ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/1916828d-63e7-4fa7-a00e-a235aad55942">

## 3. Tampilkan pegawai yang tunjangannya tidak NULL!
#### -untuk menampilkan tabel bisa menggunakan opperator is not null untuk menampilkan yg bukan null 
<img width="800" alt="gambar praktikum 3 ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/372b7aef-fda5-478a-8b8a-307d760eac65">

## 4. Tampilkan/hitung jumlah baris/record tabel pegawai!
#### -untuk menampilkan tabel bisa menggunakan count untuk menghitung data
![gambar 4 praktikum ok](https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/7232b419-97e6-4ef3-bed9-8528897e0bae)

## 5. Tampilkan/hitung jumlah total gaji di tabel pegawai!
#### --untuk menampilkan tabel bisa menggunakan SUM untuk menjumlahkan 
<img width="625" alt="gambar praktikum 5 ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/c09e86ec-4470-4b24-9eb7-75705aa19697">

## 6. Tampilkan/hitung rata-rata gaji pegawai!
#### -untuk menampilkan tabel bisa menggunakan AVG untuk menghitung rata2  
<img width="772" alt="gambar 6 praktikum ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/46b45923-6389-4a55-b660-938be82f1855">

## 7. Tampilkan gaji terkecil!
#### -untuk menampilkan tabel bisa menggunakan perintah MIN untuk menampilkan bilangan terkecil
<img width="555" alt="gambar 7 praktikum ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/c3f1ee1f-ef9a-41ba-9da2-016c89d60b33">

## 8. Tampilkan gaji terbesar!
#### -untuk menampilkan tabel bisa menggunakan  perintah MAX untuk menampilkan bilangan terbesar
<img width="495" alt="gambar 8 praktikum ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/172a73c8-fe71-466b-bf7d-65da5e304053">

## Kesimpulan
#### quary diatas dapat ditampilkan berdasarkan table pegawai yang telah dibuat

## B. Buat table hewan dan isi datanya seperti berikut:
<img width="371" alt="gambar table hewan" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/1aed8694-0460-4c82-83f8-09e7d3e9c2a8">

## 1. Tampilkan jumlah hewan yang dimiliki setiap owner.
#### - Jumlah hewan berdasarkan pemilik (owner): Dengan menggunakan klausa group by antara kolom "owners" dan "id", serta fungsi COUNT, kita dapat menghitung jumlah hewan yang dimiliki oleh setiap pemilik.

<img width="391" alt="gambar 1 hewan" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/b127c79e-90d7-4851-856a-986e6b0f23ca">

## 2. Tampilkan jumlah hewan berdasarkan spesies
#### - Jumlah hewan berdasarkan spesies: Dengan menggunakan klausa GROUP BY pada kolom "species" dan fungsi COUNT, kita dapat menghitung jumlah hewan untuk setiap spesies.

<img width="364" alt="gambar 2 hewan" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/2caa3c99-d2bb-49e5-8151-eea41518f3c5">

## 3. Tampilkan jumlah hewan berdasarkan jenis kelamin
#### - Jumlah hewan berdasarkan jenis kelamin: Dengan menggunakan klausa GROUP BY pada kolom "sex" dan fungsi COUNT, kita dapat menghitung jumlah hewan untuk setiap jenis kelamin.

<img width="357" alt="gambar 3 hewan" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/01d05899-5d4c-4e03-9f2d-141b30105097">

## 4. Tampilkan jumlah hewan berdasarkan spesies dan jenis kelamin
#### - Jumlah hewan berdasarkan spesies dan jenis kelamin (khusus cat dan dog): Dengan menggunakan klausa WHERE untuk memfilter spesies yang diinginkan dan klausa GROUP BY pada kolom "species" dan "sex" serta fungsi COUNT, kita dapat menghitung jumlah hewan untuk kombinasi spesies dan jenis kelamin tertentu.

<img width="448" alt="gambar 4 hewan" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/ff18abed-5d71-4073-854e-86f7383026ff">

## 5. Tampilkan jumlah hewan berdasarkan spesis (cat dan dog saja) dan jenis kelamin
#### - Jumlah hewan berdasarkan jenis kelamin yang diketahui: Dengan menggunakan klausa WHERE untuk memfilter jenis kelamin yang tidak NULL (diketahui) dan klausa GROUP BY pada kolom "sex" serta fungsi COUNT, kita dapat menghitung jumlah hewan untuk jenis kelamin yang diketahui.

![gambar 5 hewan](https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/a757d651-4a26-4354-b066-d1783e3455ef)

## 6. Tampilkan jumlah hewan berdasarkan jenis kelamin yang diketahui saja
#### Dengan menggunakan query-query ini, kita dapat memperoleh informasi statistik tentang jumlah hewan berdasarkan kriteria yang relevan dalam basis data MySQL.

![gambar 6 hewan](https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/2b1c31c7-e922-4da6-abcd-90a29c98c3be)

## Kesimpulan
#### Dalam MySQL, kita dapat menggunakan query untuk menampilkan jumlah hewan berdasarkan kriteria tertentu.



