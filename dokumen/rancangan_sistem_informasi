# Rancangan Basis Data Sistem Informasi Akademik

## 1. Gambaran Umum

Sistem Informasi Akademik dirancang untuk mengelola data mahasiswa, dosen, mata kuliah, Kartu Rencana Studi (KRS), dan nilai. Data tersebut disimpan dalam tabel yang saling berhubungan agar informasi akademik lebih mudah dicari dan dikelola.

## 2. Pengguna Sistem

### Mahasiswa
- Melihat identitas mahasiswa.
- Melihat daftar mata kuliah.
- Mengakses informasi KRS.
- Melihat jadwal perkuliahan dan nilai.
- Mengetahui hasil studi.

### Dosen
- Melihat mahasiswa yang mengikuti mata kuliah.
- Melihat mata kuliah yang diajar.
- Mengakses daftar kelas dan data KRS.
- Mengelola nilai mahasiswa.

## 3. Tabel Basis Data

| No. | Tabel | Primary Key | Fungsi |
|---|---|---|---|
| 1 | Mahasiswa | NIM | Menyimpan data mahasiswa. |
| 2 | Dosen | NIDN | Menyimpan data dosen. |
| 3 | Mata Kuliah | Kode_MK | Menyimpan data mata kuliah. |
| 4 | KRS | ID_KRS | Menyimpan data pengambilan mata kuliah oleh mahasiswa. |
| 5 | Nilai | ID_Nilai | Menyimpan data nilai mahasiswa. |

## 4. Hubungan Antar Tabel

- Dosen dengan Mata Kuliah memiliki hubungan One-to-Many (1:N).
- Mahasiswa dengan KRS memiliki hubungan One-to-Many (1:N).
- Mata Kuliah dengan KRS memiliki hubungan One-to-Many (1:N).
- KRS dengan Nilai memiliki hubungan One-to-One (1:1).
- Mahasiswa dengan Mata Kuliah memiliki hubungan Many-to-Many (M:N) melalui tabel KRS.

## 5. Informasi yang Dihasilkan

Hubungan antar tabel dapat digunakan untuk menghasilkan daftar mata kuliah yang diambil mahasiswa, daftar mahasiswa pada suatu mata kuliah, informasi dosen pengampu, daftar nilai, dan riwayat hasil studi.

## 6. Kesimpulan

Rancangan basis data Sistem Informasi Akademik terdiri dari lima tabel utama yang saling berhubungan. Rancangan ini menjadi dasar untuk menyimpan dan mengolah informasi akademik secara terstruktur, konsisten, dan mudah diakses sesuai kebutuhan pengguna.
