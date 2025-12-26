<p align="center">
  <img src="{{asset("LandingPage/images/logo_bumdes.png")}}" width="160" alt="Logo BumDes Pakukerto">
</p>

<h1 align="center">Sistem Informasi BumDes Pakukerto</h1>

<p align="center">
  Platform digital untuk pengelolaan layanan, usaha, dan administrasi BumDes Pakukerto (web app berbasis Laravel).
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Laravel-Framework-red" alt="Laravel"></a>
  <a href="#"><img src="https://img.shields.io/badge/PHP-8.x-blue" alt="PHP"></a>
  <a href="#"><img src="https://img.shields.io/badge/Database-MySQL-orange" alt="MySQL"></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-Development-yellow" alt="Status"></a>
</p>

---

## Tentang Proyek

**Sistem Informasi BumDes Pakukerto** adalah aplikasi web untuk membantu BumDes dalam:
- Mengelola data usaha/produk/jasa BumDes
- Mengelola transaksi & pencatatan pemasukan/pengeluaran
- Publikasi informasi kegiatan & layanan kepada masyarakat
- Manajemen pengguna (admin/petugas/masyarakat)
- Laporan & rekap data (per periode)

> Catatan: fitur bisa menyesuaikan kebutuhan BumDes (unit usaha, layanan, dan alur administrasi).

---

## Fitur Utama

### 1) Landing Page (Publik)
- Profil BumDes Pakukerto
- Daftar unit usaha / layanan / produk
- Berita/kegiatan
- Kontak & lokasi
- Testimoni (opsional)

### 2) Dashboard Admin
- CRUD Unit Usaha / Produk / Layanan
- Manajemen transaksi (penjualan/pemesanan)
- Manajemen pelanggan / data warga (opsional)
- Manajemen pengguna & role
- Laporan (harian/mingguan/bulanan)

### 3) Laporan
- Rekap pemasukan & pengeluaran
- Rekap transaksi per unit usaha
- Export (opsional: PDF/Excel)

---

## Tech Stack

- **Framework**: Laravel
- **Database**: MySQL / MariaDB
- **Frontend**: Blade + Bootstrap/Tailwind (sesuaikan project kamu)
- **Auth**: Laravel Auth (opsional: role middleware)
- **Deployment**: Shared hosting / VPS

---

## Persyaratan

- PHP 8.x
- Composer
- MySQL / MariaDB
- Node.js & NPM (jika pakai Vite/Tailwind/Bootstrap)

---

## Instalasi

1. Clone repository
```bash
git clone <repo-url> bumdes-pakukerto
cd bumdes-pakukerto
