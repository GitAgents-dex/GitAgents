# Git Agents

### 🤖 Deploy Autonomous AI Agents

*Landing page & auth demo untuk platform deploy, kelola, dan monetisasi AI agent.*

[![License](https://img.shields.io/badge/license-MIT-brightgreen?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-orange?style=for-the-badge)](CONTRIBUTING.md)
[![Made with HTML/CSS/JS](https://img.shields.io/badge/stack-HTML%2FCSS%2FJS-blueviolet?style=for-the-badge)](index.html)

---

## 📌 Tentang Project

**Git Agents** adalah halaman landing + sistem autentikasi (login & register) untuk sebuah platform fiktif tempat developer bisa deploy, fork, dan memonetisasi AI agent — mirip konsep "marketplace" untuk agent otomatis.

Project ini dibuat sebagai single-file demo (`index.html`) yang berisi:

- 🎨 Landing page dengan animasi hero, grid, dan partikel
- 🔐 Modal Login & Register lengkap dengan validasi form
- 👤 State user login (avatar, dropdown, logout) — disimpan di memory (tanpa backend)
- 📊 Live activity feed yang mensimulasikan aktivitas agent secara real-time
- 💳 Section pricing & statistik dengan counter animasi

> ⚠️ **Catatan:** Ini adalah demo front-end murni. Tidak ada backend/database asli — data user disimpan sementara di memory browser dan akan reset setiap reload halaman.

---

## 🚀 Quick Start

### Opsi 1 — Buka langsung di browser

Cukup buka file `index.html` di browser favorit kamu. Tidak perlu instalasi apa pun.

### Opsi 2 — Clone & jalankan lokal

```bash
# Clone repository
git clone https://github.com/<username>/Git-Agents.git
cd Git-Agents

# Buka langsung
open index.html        # macOS
start index.html       # Windows
xdg-open index.html     # Linux
```

### Opsi 3 — Jalankan dengan local server (disarankan untuk testing font/CDN)

```bash
# Python
python3 -m http.server 8000

# lalu buka
http://localhost:8000
```

---

## 🗂️ Struktur Repo

```
Git-Agents/
├── .github/              # Template issue & workflow (opsional)
├── index.html            # Landing page + auth system (single-file)
├── README.md             # Dokumen ini
├── CONTRIBUTING.md       # Panduan kontribusi
├── CODE_OF_CONDUCT.md    # Etika kontribusi komunitas
├── SECURITY.md           # Kebijakan keamanan & cara report vulnerability
├── LICENSE               # Lisensi project
├── .gitignore            # File/folder yang diabaikan git
└── .nojekyll             # Menonaktifkan Jekyll processing di GitHub Pages
```

---

## ✨ Fitur Utama

| Fitur | Deskripsi |
|---|---|
| 🎨 Hero animasi | Grid bergerak, orb melayang, partikel bintang |
| 🔐 Auth modal | Tab login/register dengan validasi real-time |
| 👤 Session UI | Avatar, dropdown user, status login di navbar |
| 📈 Counter stats | Angka statistik dengan animasi count-up saat scroll |
| 📡 Live feed | Simulasi event agent (deploy, fork, audit) tiap beberapa detik |
| 📱 Responsive | Navbar mobile dengan menu & state login terpisah |

---

## 🌐 Deploy ke GitHub Pages

1. Push repo ini ke GitHub
2. Buka **Settings → Pages**
3. Pilih branch `main` dan folder `/ (root)`
4. Halaman akan live di `https://<username>.github.io/Git-Agents/`

File `.nojekyll` sudah disediakan agar GitHub Pages tidak memproses file dengan Jekyll (karena project ini static HTML murni).

---

## 🤝 Kontribusi

Kontribusi sangat terbuka! Baca [CONTRIBUTING.md](CONTRIBUTING.md) untuk panduan lengkap.

1. **Fork** repo ini
2. **Buat branch**: `git checkout -b fitur/nama-fitur`
3. **Commit**: `git commit -m "feat: tambah fitur X"`
4. **Push**: `git push origin fitur/nama-fitur`
5. **Buka Pull Request**

---

## 📄 Lisensi

Project ini dilisensikan di bawah [MIT License](LICENSE).

---

**⭐ Kalau project ini membantu, jangan lupa beri star ya!**
