# Personal ID Generator

Program Bahasa C sederhana untuk membuat ID unik berdasarkan data masukan pengguna: 
- *Nama*
- *Umur*
- *Kota Asal*
- *Warna Favorit*.

## Deskripsi Singkat
Program ini menerima 4 data masukan dari pengguna dan mengolahnya menjadi kode unik yang terdiri dari kombinasi huruf dan angka menggunakan operasi matematika ASCII serta fungsi `sprintf()`. 

## Logika Pembuatan ID
Format ID: `[Inisial Nama][Angka 1][Inisial Kota Asal][Angka 2][Inisial Warna favorit][Angka 3]`
- **Angka 1:** Perhitungan berbasis umur pengguna.
- **Angka 2 & 3:** Perhitungan berbasis nilai ASCII dari huruf pertama Kota dan Warna.
