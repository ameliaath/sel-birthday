# 🎂 Birthday Vault — Sel

Hadiah ulang tahun interaktif berbasis web, siap deploy ke Vercel.

---

## 🚀 Cara Deploy ke Vercel (tanpa coding)

### Opsi 1: Vercel Drop (paling cepat, 2 menit)
1. Buka [vercel.com](https://vercel.com) → login / daftar gratis
2. Di dashboard, klik **"Add New Project"** → pilih **"Deploy from CLI"** atau cukup drag & drop folder ini ke halaman **vercel.com/new**
3. Vercel otomatis detect static site → klik **Deploy**
4. Dapat URL seperti `https://sel-birthday.vercel.app`
5. Generate QR dari URL di [qr.io](https://qr.io) atau [qr-code-generator.com](https://www.qr-code-generator.com)

### Opsi 2: GitHub + Vercel (bisa update kapan saja)
1. Buat repo baru di GitHub (bisa private)
2. Upload semua file di folder ini ke repo tersebut
3. Buka [vercel.com](https://vercel.com) → **"Add New Project"** → pilih repo GitHub kamu
4. Klik **Deploy** — selesai!
5. Setiap kali push ke GitHub, Vercel auto-update

---

## ✏️ Cara Edit Konten

Buka `index.html` dengan text editor (Notepad, VS Code, dll):

### Ganti pesan ucapan
Cari bagian `<h2>Pesan Untuk Sel</h2>` lalu edit teks di paragraf `<p>` di bawahnya.

### Tambah foto asli
Cari `<div class="photo-frame">` lalu ganti seluruh `<div>` tersebut dengan:
```html
<img src="foto-kalian.jpg" style="width:100%;aspect-ratio:16/10;object-fit:cover;border-radius:12px;" alt="Foto kenangan">
```
Letakkan file foto di folder yang sama dengan `index.html`, lalu sesuaikan nama filenya.

### Ganti nama
Cari semua teks `SEL` / `Sel` dan ganti sesuai kebutuhan.

---

## 🎵 Tentang Sound
Sound dihasilkan via Web Audio API — tidak butuh file audio eksternal.
Toggle sound ada di pojok kanan atas layar.

---

Dibuat dengan ❤️ menggunakan HTML, CSS, dan Web Audio API.
