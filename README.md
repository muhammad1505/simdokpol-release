# Sistem Informasi Manajemen Dokumen Kepolisian (SIMDOKPOL)

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Go Version](https://img.shields.io/badge/Go-1.25%2B-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey.svg)
![Database](https://img.shields.io/badge/Database-SQLite%20%7C%20MySQL%20%7C%20PostgreSQL-blue.svg)

**SIMDOKPOL** adalah aplikasi desktop *cross-platform* modern untuk efisiensi pelayanan Surat Keterangan Tanda Lapor Kehilangan (SKTLK) di kepolisian.

Aplikasi ini mendukung dua mode operasi:
1.  **Standalone (Offline):** Database SQLite portabel, tanpa server. Cocok untuk laptop petugas.
2.  **Client-Server (Online):** Koneksi ke MySQL/PostgreSQL untuk penggunaan jaringan terpusat.

![Dasbor SIMDOKPOL](.github/assets/guide-dashboard.png)

---

## ✨ Fitur Unggulan

### 🚀 Operasional Cerdas
-   **Setup Wizard**: Konfigurasi awal tanpa koding.
-   **Formulir Validasi**: Input NIK, No. HP, dan data barang dengan validasi format otomatis.
-   **Cetak Presisi**: Output PDF standar kepolisian yang rapi.

### 🔐 Keamanan & Audit
-   **Role-Based Access**: Super Admin & Operator.
-   **Audit Log**: Rekam jejak aktivitas lengkap (Siapa, Kapan, Apa).
-   **Lisensi Hardware-Locked**: Proteksi penggunaan aplikasi berbasis ID perangkat (Fitur Pro).

### 📊 Analitik (Pro)
-   **Laporan Agregat**: Ringkasan kinerja bulanan/tahunan.
-   **Grafik Statistik**: Visualisasi tren laporan kehilangan.

---

## 📸 Galeri Aplikasi

### Manajemen Dokumen
<table width="100%">
    <tr>
        <td width="50%" valign="top">
            <strong>Daftar Dokumen Aktif</strong><br>
            <img src=".github/assets/guide-doc-active.png" width="100%">
        </td>
        <td width="50%" valign="top">
            <strong>Formulir Penerbitan</strong><br>
            <img src=".github/assets/guide-doc-form.png" width="100%">
        </td>
    </tr>
</table>

### Administrasi
<table width="100%">
    <tr>
        <td width="50%" valign="top">
            <strong>Pengaturan Sistem</strong><br>
            <img src=".github/assets/guide-settings-general.png" width="100%">
        </td>
        <td width="50%" valign="top">
            <strong>Manajemen Pengguna</strong><br>
            <img src=".github/assets/guide-user-list.png" width="100%">
        </td>
    </tr>
    <tr>
        <td width="50%" valign="top">
            <strong>Fitur Pro: Laporan</strong><br>
            <img src=".github/assets/guide-report.png" width="100%">
        </td>
        <td width="50%" valign="top">
             <strong>Fitur Pro: Template</strong><br>
            <img src=".github/assets/guide-template-list.png" width="100%">
        </td>
    </tr>
</table>

---

## 🚀 Cara Instalasi

1.  Unduh installer dari menu **Releases**.
2.  **Windows**: Jalankan `.exe`.
3.  **Linux**: Install `.deb` atau `.rpm`.
4.  **macOS**: Mount `.dmg` dan drag ke Applications.

---

## 🤝 Kontribusi & Lisensi

Dikembangkan oleh **Muhammad Yusuf Abdurrohman**.
Lisensi: **MIT License** (Open Source).