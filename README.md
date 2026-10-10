# Sistem Informasi Akademik

## Deskripsi
Sistem Informasi Akademik merupakan sistem yang dirancang untuk membantu pengelolaan data akademik, seperti data mahasiswa, dosen, mata kuliah, Kartu Rencana Studi (KRS), dan nilai mahasiswa.

Repository ini berisi dokumentasi rancangan basis data Sistem Informasi Akademik yang dibuat untuk memenuhi tugas mata kuliah Sistem Informasi.

## Tujuan
- Menyusun data akademik secara terstruktur.
- Memudahkan pengelolaan dan pencarian informasi akademik.
- Menghubungkan data mahasiswa, dosen, mata kuliah, KRS, dan nilai.
- Mengurangi duplikasi serta menjaga konsistensi data.

## Pengguna Sistem

### 1. Mahasiswa
Mahasiswa membutuhkan informasi identitas, daftar mata kuliah, KRS, jadwal perkuliahan, nilai, dan hasil studi.

### 2. Dosen
Dosen membutuhkan informasi mahasiswa yang mengikuti mata kuliah, mata kuliah yang diajar, daftar kelas, data KRS, dan nilai mahasiswa.

## Rancangan Tabel Basis Data

| No. | Nama Tabel | Primary Key |
|---|---|---|
| 1 | Mahasiswa | NIM |
| 2 | Dosen | NIDN |
| 3 | Mata Kuliah | Kode_MK |
| 4 | KRS | ID_KRS |
| 5 | Nilai | ID_Nilai |

## Hubungan Antar Tabel
- **Dosen — Mata Kuliah:** One-to-Many (1:N).
- **Mahasiswa — KRS:** One-to-Many (1:N).
- **Mata Kuliah — KRS:** One-to-Many (1:N).
- **KRS — Nilai:** One-to-One (1:1).
- **Mahasiswa — Mata Kuliah:** Many-to-Many (M:N), yang dihubungkan melalui tabel KRS.

## Informasi yang Dihasilkan
Basis data ini dapat digunakan untuk menghasilkan daftar mata kuliah yang diambil mahasiswa, daftar mahasiswa pada suatu mata kuliah, data dosen pengampu, daftar nilai, dan riwayat hasil studi mahasiswa.

## Penutup
Rancangan basis data ini menjadi dasar pengembangan Sistem Informasi Akademik agar data akademik dapat dikelola secara terstruktur dan saling terhubung.
