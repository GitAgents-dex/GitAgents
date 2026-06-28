# Contributing to Git Agents

Terima kasih sudah mau berkontribusi! 🎉 Berikut panduannya.

## Cara Berkontribusi

1. **Fork** repository ini
2. **Clone** hasil fork kamu:
   ```bash
   git clone https://github.com/<username-kamu>/Git-Agents.git
   ```
3. **Buat branch baru**:
   ```bash
   git checkout -b fitur/nama-fitur-kamu
   ```
4. Lakukan perubahan, lalu **commit**:
   ```bash
   git commit -m "feat: deskripsi singkat perubahan"
   ```
5. **Push** ke fork kamu:
   ```bash
   git push origin fitur/nama-fitur-kamu
   ```
6. Buka **Pull Request** ke branch `main` repo ini

## Jenis Kontribusi yang Diterima

- 🐛 Perbaikan bug pada UI/JS (misal validasi form, dropdown, animasi)
- ✨ Fitur baru (misal dark/light mode toggle, integrasi backend asli)
- 📝 Perbaikan dokumentasi (README, komentar kode)
- 🎨 Perbaikan desain/aksesibilitas (kontras warna, ARIA label)
- ♻️ Refactor kode agar lebih rapi/modular

## Standar Kode

- Gunakan indentasi 2 spasi untuk HTML/CSS/JS
- Beri komentar pada bagian logika penting (terutama di `<script>`)
- Pastikan tidak merusak fitur auth yang sudah ada sebelum submit PR
- Test perubahan di minimal 1 browser desktop & 1 ukuran mobile (responsive)

## Format Commit Message

Gunakan prefix berikut agar histori commit konsisten:

- `feat:` — fitur baru
- `fix:` — perbaikan bug
- `docs:` — perubahan dokumentasi
- `style:` — perubahan tampilan/CSS tanpa mengubah logika
- `refactor:` — perubahan struktur kode tanpa mengubah fungsi

## Melaporkan Bug

Gunakan tab **Issues** dan sertakan:
- Langkah untuk mereproduksi bug
- Browser & device yang digunakan
- Screenshot jika memungkinkan

Terima kasih atas kontribusinya! 🙌
