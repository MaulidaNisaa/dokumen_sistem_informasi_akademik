# dokumen_sistem_informasi_akademik
Sistem Informasi Akademik yang mencakup data mahasiswa, dosen, mata kuliah, KRS, nilai, dan hubungan antar tabel basis data.
# Sistem Informasi Akademik

## 1. Deskripsi Sistem
Sistem Informasi Akademik merupakan sistem yang membantu pengelolaan informasi akademik mahasiswa, dosen, mata kuliah, KRS, dan nilai mahasiswa.

## 2. Pengguna Sistem

### Mahasiswa
Mahasiswa membutuhkan informasi identitas diri, daftar mata kuliah, KRS, jadwal perkuliahan, nilai mata kuliah, dan hasil studi.

### Dosen
Dosen membutuhkan informasi mahasiswa yang mengikuti mata kuliah, mata kuliah yang diajar, daftar kelas, data KRS, dan nilai mahasiswa.

## 3. Struktur Basis Data

Sistem Informasi Akademik memiliki lima tabel utama:

1. Mahasiswa — menggunakan NIM sebagai primary key.
2. Dosen — menggunakan NIDN sebagai primary key.
3. Mata Kuliah — menggunakan Kode_MK sebagai primary key.
4. KRS — menggunakan ID_KRS sebagai primary key.
5. Nilai — menggunakan ID_Nilai sebagai primary key.

## 4. Hubungan Antar Tabel
- Satu dosen dapat mengajar beberapa mata kuliah.
- Satu mahasiswa dapat memiliki banyak data KRS.
- Satu mata kuliah dapat muncul pada banyak data KRS.
- Tabel KRS menghubungkan mahasiswa dengan mata kuliah yang diambil.
- Data nilai berhubungan dengan data KRS.

## 5. Tujuan Repository
Repository ini digunakan untuk menyimpan dokumentasi Sistem Informasi Akademik dan mencatat perubahan dokumen selama pengerjaan tugas.
