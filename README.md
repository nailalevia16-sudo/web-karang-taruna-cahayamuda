# 🌟 Web Portal & Sistem Informasi Inventaris Karang Taruna Cahaya Muda

Portal web resmi berbasis PHP Native, MySQL, dan Tailwind CSS yang dirancang modern, responsif, dan interaktif untuk Karang Taruna Cahaya Muda (Njitengan Pogung, Cawas). Sistem ini memfasilitasi publikasi kegiatan kepemudaan, profil organisasi, serta layanan peminjaman aset inventaris desa secara digital dan transparan.

---

## 🎨 Fitur Utama

- **Beranda (Landing Page Modern)**:
  - Tampilan *Hero Section* interaktif dengan *ambient glow*, *dot grid pattern*, dan kartu statistik *real-time*.
  - Pilar fokus kegiatan dengan integrasi foto asli pemuda desa.
- **Profil & Struktur Organisasi**:
  - Visi & Misi Karang Taruna dengan kartu *glassmorphism*.
  - Susunan pengurus inti (Ketua, Wakil, Sekretaris, Bendahara) lengkap dengan avatar inisial berwarna dan tugas pokok.
- **Agenda & Galeri Kegiatan**:
  - Dokumentasi kegiatan sosial, gotong royong bersih masjid, persiapan bendera HUT RI, dan posyandu warga dengan desain galeri bulat modern.
- **Katalog Inventaris & Form Peminjaman Warga**:
  - Katalog barang transparan beserta jumlah stok dan kondisi aset.
  - Form pengajuan peminjaman digital untuk warga secara *real-time*.
- **Dashboard Admin (CRUD & Transaction Monitoring)**:
  - Manajeman data barang/aset (Tambah, Edit, Hapus, Cari).
  - Monitoring sirkulasi transaksi peminjaman warga beserta nomor WhatsApp kontak dan konfirmasi pengembalian barang.

---

## 🛠️ Tech Stack & Alat Pengembangan

- **Language**: PHP 8.x (PHP Native dengan PDO)
- **Database**: MySQL / MariaDB
- **Styling**: Tailwind CSS (via CDN) + Glassmorphism Styling
- **Icons & Fonts**: FontAwesome 6, Google Fonts (Plus Jakarta Sans)
- **Local Server**: Laragon / XAMPP
- **Code Editor**: Visual Studio Code

---

## 🗂️ Struktur File Proyek

```text
project karang_taruna/
├── index.php                 # Halaman Utama (Beranda)
├── profil.php                # Halaman Profil & Pengurus Inti
├── kegiatan.php              # Halaman Agenda & Galeri Kegiatan
├── katalog.php               # Halaman Katalog Inventaris
├── peminjaman.php            # Form Pengajuan Peminjaman Aset Warga
├── admin.php                 # Dashboard Admin (CRUD & Monitoring Peminjaman)
├── koneksi.php               # Konfigurasi Koneksi Database (PDO)
├── karangtaruna.jpeg         # Logo Resmi Karang Taruna
├── profilkartar.jpeg         # Foto Banner Utama
├── gotongroyongkartar.jpeg   # Foto Kegiatan Gotong Royong
├── gotongroyongkartar2.jpeg  # Foto Kegiatan Persiapan Bambu Bendera
├── rapatkartar.jpeg          # Foto Musyawarah Pemuda
└── posyandukartar.jpeg       # Foto Layanan Posyandu
