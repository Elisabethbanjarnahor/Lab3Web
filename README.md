# Lab3Web
## Nama    :Elisabeth Erni Banjarnahor ##
## Kelas   : Ti.24.A5##
## Matakul : Pemograman Web ##


## foto pertama ##
![codingan pertama](https://github.com/Elisabethbanjarnahor/Lab3Web/blob/9071ada0d95979c64bd334bbd5dc735b4029617c/Screenshot%202025-10-08%20105947.png
)

lab3_list.html — Membuat List
🔹 Tujuan:
Belajar tiga jenis daftar di HTML: ordered list, unordered list, dan description list.

🔹 Penjelasan Koding:
<ol type="A" start="1"> ... </ol>
Membuat ordered list (A, B, C) — daftar berurutan.
type="A" = huruf besar, start="1" = mulai dari A.
<ul type="square"> ... </ul>
➡ Membuat unordered list (pakai simbol kotak).
type="square" = simbolnya kotak, bisa juga circle, disc, dll.
<dl> <dt>...</dt> <dd>...</dd> </dl>
Membuat description list (daftar dengan keterangan).
<dt> = istilah (contoh: Fakultas Teknik),
<dd> = penjelasan dari istilahnya.

🔹 Hasil:
Menampilkan daftar dengan berbagai bentuk penomoran dan keterangan — sama kayak di contoh modul halaman awal.

## foto kedua ##
![codingan pertama](https://github.com/Elisabethbanjarnahor/Lab3Web/blob/22b906e8936bf1b28d7fd1f01a7c5a9218f95254/Screenshot%202025-10-08%20110631.png
)

lab3_tabel.html — Membuat Table
🔹 Tujuan:
Belajar menyusun data ke dalam bentuk baris dan kolom.
🔹 Penjelasan Koding:
<table border="1" cellpadding="6" cellspacing="0">

➡ Membuat tabel dengan garis, jarak antar teks (cellpadding), dan tanpa jarak antar sel (cellspacing).
<thead> ... </thead>  dan  <tbody> ... </tbody>
Pisahin antara kepala tabel dan isi tabel biar rapi.

<td rowspan="3">Teknik</td>

➡ rowspan menggabungkan sel secara vertikal (ke bawah).
Dipakai di kolom Fakultas biar “Teknik” bisa mencakup 3 baris jurusan.

🔹 Hasil:

Tabel dengan kolom No, Fakultas, Program Studi.
Bagian “Teknik” digabung di tiga baris pertama — tampilannya rapi dan berstruktur

## foto ketiga ##
![kodingan ke tiga](https://github.com/Elisabethbanjarnahor/Lab3Web/blob/9ce5b985ee44e6ca5553934adea2dde34b4504be/Screenshot%202025-10-08%20110928.png
)

lab3_form.html — Membuat Form
🔹 Tujuan:
Belajar membuat form input data dan menambahkan CSS sederhana biar tampilannya bagus.
🔹 Penjelasan Koding:
<form action="proses.php" method="post">
➡ Awal form.
action = alamat file tujuan (tempat data dikirim),
method="post" = metode pengiriman data (aman dan umum dipakai).
Penjelasan Koding:
<form action="proses.php" method="post">
➡ Awal form.
action = alamat file tujuan (tempat data dikirim),
method="post" = metode pengiriman data (aman dan umum dipakai).
<fieldset> <legend>Data Pelanggan</legend> ... </fieldset>
➡ fieldset bikin kotak form, legend jadi judulnya (“Data Pelanggan”).
<input type="text"> dan <textarea>
➡ Untuk mengisi nama dan alamat.
html
Salin kode
<input type="radio" name="kelamin" value="L">
➡ Tombol pilihan jenis kelamin (Laki-laki / Perempuan).
Dikasih titik (Laki-laki.) biar sama kayak di modul.
html
Salin kode
<input type="submit" value="Login">
➡ Tombol untuk kirim form (berwarna hijau dari CSS).

Tambahan (Tugas Akhir):
Dropdown menu (<select>) untuk pilih kota
Listbox multiple (<select multiple>) untuk pilih hobi lebih dari satu
🔹 CSS-nya:
form input[type="text"], form textarea {
    border: 1px solid #197a43;
}
form input[type="submit"] {
    background-color: #197a43;
    color: white;
}
➡ Memberi warna hijau pada garis form dan tombol “Login”.
Hasil:
Form dengan kotak “Data Pelanggan”, isi: Nama, Alamat, Jenis Kelamin, Dropdown Kota, Listbox Hobi, dan Tombol Login hijau. ✅

## foto keemppat ##
![kodingan keempat](https://github.com/Elisabethbanjarnahor/Lab3Web/blob/bc470445005c12d2c57f5ee02a963421745f0766/Screenshot%202025-10-08%20112110.png
)

## sekian dan terimakasih ##
