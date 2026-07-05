# Sistem Admin Data Mahasiswa

Sistem ini merupakan aplikasi web berbasis PHP Native untuk mengelola data mahasiswa dengan fitur CRUD, pagination, pencarian realtime menggunakan AJAX, serta upload gambar.

---

## 🚀 Fitur

- Login admin (session)
- Menampilkan data mahasiswa
- Tambah, edit, dan hapus data
- Upload dan tampilkan gambar mahasiswa
- Relasi tabel mahasiswa, prodi, dan status
- Pagination (5 data per halaman)
- Pencarian data realtime menggunakan AJAX (jQuery)

---

## 🛠️ Teknologi

- PHP Native
- MySQL
- HTML
- CSS
- Bootstrap 4
- JavaScript
- jQuery (AJAX)

---

## 📁 Struktur Database

### Tabel `mahasiswa`
- npm
- nama
- email
- gambar
- id_prodi
- id_status

### Tabel `prodi`
- id_prodi
- nama_prodi

### Tabel `status`
- id_status
- ket
