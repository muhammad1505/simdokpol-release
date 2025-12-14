# SIMDOKPOL v1.0.3

## 🚀 SIMDOKPOL v1.0.3

Rilis stabil baru untuk **SIMDOKPOL** - Sistem Informasi Manajemen Dokumen Kepolisian.

---

### ✨ Fitur Baru

- feat(icon): implement cross-platform icon system with auto format selection

### 🐛 Bug Fixes

- Update workflow untuk upload hasil build ke simdokpol-release repository
- implement dynamic icon format detection for multiplatform system tray support

### 🔧 Perubahan Lainnya

- update ci build release
- Implementasi garis putus-putus dan perbaikan format PDF

---

---

## 📦 Download Files

### Windows (x64)

**Installer (Recommended)**
- [`simdokpol-windows-x64-v1.0.3-installer.exe`](simdokpol-windows-x64-v1.0.3-installer.exe)
  - ✅ Instalasi otomatis
  - ✅ Shortcut desktop & Start Menu
  - ✅ GUI & Console mode

**Portable**
- [`simdokpol-windows-x64-v1.0.3-portable.zip`](simdokpol-windows-x64-v1.0.3-portable.zip)
  - 📁 Extract & run

---

### Linux (amd64)

**DEB Package (Ubuntu/Debian)**
- [`simdokpol_1.0.3_amd64.deb`](simdokpol_1.0.3_amd64.deb)
  ```bash
  sudo dpkg -i simdokpol_1.0.3_amd64.deb
  sudo apt-get install -f
  ```

**RPM Package (Fedora/RHEL/CentOS)**
- File RPM tersedia dengan pattern: `simdokpol-1.0.3-1.*.rpm`
  ```bash
  sudo rpm -i simdokpol-1.0.3-1.*.rpm
  ```

**Portable**
- [`simdokpol-linux-amd64-v1.0.3-portable.tar.gz`](simdokpol-linux-amd64-v1.0.3-portable.tar.gz)
  ```bash
  tar -xzf simdokpol-linux-amd64-v1.0.3-portable.tar.gz
  cd simdokpol
  ./start.sh
  ```

---

### macOS (amd64)

**DMG Installer (Recommended)**
- [`simdokpol-macos-amd64-v1.0.3-installer.dmg`](simdokpol-macos-amd64-v1.0.3-installer.dmg)
  - ✅ Drag & drop ke Applications
  - ✅ Native macOS App Bundle

**Portable**
- [`simdokpol-macos-amd64-v1.0.3-portable.zip`](simdokpol-macos-amd64-v1.0.3-portable.zip)

---

## 🔐 Verifikasi Integritas

Download file [`checksums.txt`](checksums.txt) untuk memverifikasi integritas:

```bash
# Linux/macOS
sha256sum -c checksums.txt

# Windows PowerShell
Get-Content checksums.txt | ForEach-Object {
    $hash, $file = $_ -split '\s+', 2
    $computed = (Get-FileHash $file -Algorithm SHA256).Hash.ToLower()
    if ($computed -eq $hash) { 
        Write-Host "✓ $file" -ForegroundColor Green 
    } else { 
        Write-Host "✗ $file" -ForegroundColor Red 
    }
}
```

---

## 📚 Dokumentasi

- [Main Repository](https://github.com/muhammad1505/simdokpol)
- [Issues](https://github.com/muhammad1505/simdokpol/issues)
- [Wiki](https://github.com/muhammad1505/simdokpol/wiki)

**Terima kasih telah menggunakan SIMDOKPOL!** 🙏
