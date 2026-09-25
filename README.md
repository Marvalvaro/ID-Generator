# ID Generator

Program Bahasa C sederhana untuk membuat ID unik berdasarkan data pengguna: 
- Nama
- Umur
- Kota
- Warna Favorit

## Deskripsi Singkat
Program ini menerima 4 data masukan dari pengguna melalui terminal, lalu mengolahnya menjadi ID unik yang terdiri dari kombinasi huruf dan angka. Proses pembuatan ID melibatkan operasi matematika dasar dan manipulasi nilai ASCII. Seluruh komponen ID kemudian digabungkan menjadi satu string utuh menggunakan fungsi `sprintf()`.

## Logika Pembuatan ID
**Format Susunan ID:**  
`[Inisial Nama] + [Angka 1] + [Inisial Kota] + [Angka 2] + [Inisial Warna] + [Angka 3]`

**Rincian Komponen ID:**
1. **Inisial Nama (`name[0]`):** Mengambil karakter pertama dari nama
2. **Inisial Kota (`city[0]`):** Mengambil karakter pertama dari kota
3. **Inisial Warna (`color[0]`):** Mengambil karakter pertama dari warna favorit
4. **Angka 1 (`number1`):** Hasil operasi matematika menggunakan nilai umur dengan formula (`1000 - (age * 5)`)
5. **Angka 2 (`number2`):** Hasil operasi matematika menggunakan nilai ASCII dari kota dan warna favorit dengan formula (`city[0] + color[0] + 50`) 
6. **Angka 3 (`number3`):** asil operasi matematika menggunakan nilai ASCII dari kota dan warna favorit dengan formula (`city[0] - color[0] + 200`)

## Lampiran Hasil Running Code
<img width="959" height="497" alt="Hasil Running Code Tugas Asistensi" src="https://github.com/user-attachments/assets/0c8947b7-be1c-4d86-b700-a477489ce571" />
