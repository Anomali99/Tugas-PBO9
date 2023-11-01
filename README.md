# Tugas-PBO9
Aplikasi ini adalah aplikasi java GUI yang menggunakan Parsisten sebagai koneksi ke database

## Features
- Dapat melakukan insert data ke database
- Dapat melakuakan update data ke database
- Dapat melakukan delete data dari database
- Dapat menampilkan data pada database
- Dapat mencetak laporan data dari database

## Tech
- JDK 8
- NetBeans IDE 15
- PostgreSQL 14

## Installation
Buat Tabel Buku pada database PBO

```sh
CREATE TABLE buku (
ISBN char (13) primary key, 
Judul_Buku varchar (30), 
Tahun_Terbit char (4), 
Penerbit char (30));
```
=======
> Nur Fatiq (09040622071)
