# TP4DPBO2526C1
Tugas Praktikum 4 DPBO 2026

Janji Saya Bozorov Huseyn (NIM: 2521812) mengerjakan evaluasi Tugas Praktikum 4 dalam mata kuliah Desain dan Pemrograman Berbasis Objek untuk keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

Aplikasi desktop Java Swing untuk mengelola data orang dengan operasi CRUD (Create, Read, Update, Delete).

## Desain / Fungsi Program

- **Person.java**: class model dengan atribut `id`, `nama`, `tahunLahir`, `kategori`, dan `kota` (atribut baru, berupa `JComboBox`).
- **PeopleMenu.java**: class utama berisi listener dan logika CRUD.
- **PeopleMenu.form**: desain GUI (form input di kiri, tabel data di kanan).

Fitur tambahan:
- Konfirmasi Yes/No sebelum data dihapus.
- Validasi: tahun lahir harus berupa angka.

## Penjelasan Alur

1. Saat program dibuka, data awal dimasukkan ke `ArrayList<Person>` dan ditampilkan di tabel.
2. **Create**: isi form, tekan **Add**. Data masuk ke list, tabel diperbarui.
3. **Read**: data tampil di tabel. Klik sebuah baris, datanya masuk ke form, tombol berubah menjadi **Update**, dan tombol **Delete** muncul.
4. **Update**: ubah isi form, tekan **Update**. Data pada list diperbarui.
5. **Delete**: tekan **Delete**, konfirmasi dengan **Yes**, data dihapus dari list dan tabel.
6. **Cancel**: mengosongkan form dan mengembalikan tombol ke **Add**.


## Dokumentasi

[Video Dokumentasi](PeopleData/Dokumentasi/Screen Recording tp4.mov) ⁠
