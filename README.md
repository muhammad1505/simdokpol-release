# SIMDOKPOL - Official Releases

![SIMDOKPOL](https://img.shields.io/badge/SIMDOKPOL-v1.0.3-blue)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey)
![License](https://img.shields.io/badge/license-MIT-green)

Repository resmi untuk distribusi binary **SIMDOKPOL** - Sistem Informasi Manajemen Dokumen Kepolisian.

## 🎯 Latest Release

### **[v1.0.3](https://github.com/muhammad1505/simdokpol-release/releases/tag/v1.0.3)** - Latest

**[📥 Download Latest Release](https://github.com/muhammad1505/simdokpol-release/releases/latest)**

---

## 📦 Platform Support

SIMDOKPOL tersedia untuk platform berikut:

### 🪟 Windows
- **Installer (Recommended)**: File `.exe` dengan wizard instalasi lengkap
- **Portable**: File `.zip` untuk menjalankan tanpa instalasi
- **Architecture**: x64 (64-bit)

### 🐧 Linux
- **DEB Package**: Untuk Ubuntu, Debian, dan distribusi berbasis Debian
- **RPM Package**: Untuk Fedora, RHEL, CentOS, dan distribusi berbasis RPM
- **Portable**: File `.tar.gz` untuk distribusi Linux lainnya
- **Architecture**: amd64 (64-bit)

### 🍎 macOS
- **DMG Installer (Recommended)**: Native macOS app bundle
- **Portable**: File `.zip` berisi `.app` bundle
- **Architecture**: amd64 (Intel), kompatibel dengan Apple Silicon via Rosetta 2

---

## 📥 Cara Download

1. **Kunjungi halaman [Releases](https://github.com/muhammad1505/simdokpol-release/releases)**
2. **Pilih versi yang diinginkan** (atau gunakan **Latest** untuk versi terbaru)
3. **Download file sesuai platform:**
   - Windows: `.exe` (installer) atau `.zip` (portable)
   - Linux: `.deb`, `.rpm`, atau `.tar.gz`
   - macOS: `.dmg` (installer) atau `.zip` (portable)
4. **Verifikasi integritas** menggunakan file `checksums.txt`

---

## 🔐 Verifikasi Integritas File

Setiap release dilengkapi dengan file `checksums.txt` yang berisi SHA-256 hash dari semua file.

### Linux/macOS
```bash
# Download checksums.txt dari release
sha256sum -c checksums.txt
```

### Windows PowerShell
```powershell
# Download checksums.txt dari release
Get-Content checksums.txt | ForEach-Object {
    $hash, $file = $_ -split '\s+', 2
    $computed = (Get-FileHash $file).Hash.ToLower()
    if ($computed -eq $hash) {
        Write-Host "✓ $file" -ForegroundColor Green
    } else {
        Write-Host "✗ $file - MISMATCH!" -ForegroundColor Red
    }
}
```

---

## 🚀 Quick Start

### Windows
```cmd
# Download installer
# Jalankan: simdokpol-windows-x64-vX.X.X-installer.exe
# Ikuti wizard instalasi
```

### Linux (Ubuntu/Debian)
```bash
# Download .deb package
sudo dpkg -i simdokpol_X.X.X_amd64.deb
sudo apt-get install -f

# Jalankan aplikasi
simdokpol
```

### Linux (Fedora/RHEL/CentOS)
```bash
# Download .rpm package
sudo rpm -i simdokpol-X.X.X-1.x86_64.rpm

# Jalankan aplikasi
simdokpol
```

### macOS
```bash
# Download .dmg file
# Buka DMG dan drag SIMDOKPOL.app ke folder Applications
# Jalankan dari Launchpad
```

---

## 📋 Daftar Semua Versi

Lihat semua versi yang tersedia di halaman [Releases](https://github.com/muhammad1505/simdokpol-release/releases).

---

## 🔗 Links

- **📖 Source Code**: [github.com/muhammad1505/simdokpol](https://github.com/muhammad1505/simdokpol)
- **📚 Dokumentasi**: [Wiki](https://github.com/muhammad1505/simdokpol/wiki)
- **🐛 Report Issues**: [Issue Tracker](https://github.com/muhammad1505/simdokpol/issues)
- **💬 Discussions**: [GitHub Discussions](https://github.com/muhammad1505/simdokpol/discussions)
- **📧 Contact**: emailbaruku50@gmail.com

---

## 📄 License

SIMDOKPOL dilisensikan di bawah [MIT License](https://github.com/muhammad1505/simdokpol/blob/main/LICENSE).

---

## 🙏 Credits

**SIMDOKPOL** - Sistem Informasi Manajemen Dokumen Kepolisian

Dikembangkan dengan ❤️ untuk memudahkan manajemen dokumen kepolisian.

---

*Repository ini hanya berisi binary releases. Untuk source code, silakan kunjungi [repository utama](https://github.com/muhammad1505/simdokpol).*
