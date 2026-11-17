# Repositori Tugas Akhir DKV ITEBA

Website statis repositori karya Tugas Akhir mahasiswa Program Studi Desain Komunikasi Visual, Institut Teknologi Batam.

## Publikasi ke GitHub Pages
1. Buat repository baru di GitHub, misalnya `repositori-ta-dkv` (Public).
2. Upload semua file di folder ini (index.html, karya.js, gambar NIM.jpg) lewat **Add file → Upload files**, lalu Commit.
3. Buka **Settings → Pages** → Source: *Deploy from a branch* → Branch `main`, folder `/ (root)` → Save.
4. Dalam 1–2 menit situs aktif di `https://<username>.github.io/repositori-ta-dkv/`.

## Menambah / mengubah karya
Edit `karya.js`. Setiap karya berisi:
```js
{ "id": 97, "nama": "Nama Mahasiswa", "nim": "21230xx",
  "judul": "PERANCANGAN ...", "semester": "Ganjil 2026-2027",
  "kategori": "Branding & Identitas",   // atau: Ilustrasi & Buku, Game & Interaktif, UI/UX & Aplikasi, Animasi & Motion, Video & Film, Lainnya
  "karya": "https://link-karya",        // Drive/Figma/YouTube/Behance
  "thumbnail": "21230xx.jpg",  // opsional, rasio 16:9, taruh di folder utama
  "pembimbing": "", "abstrak": "" }
```
Kategori awal diisi otomatis dari kata kunci judul — mohon diperiksa.

## Privasi
Data yang ditampilkan hanya nama, NIM, judul, semester, dan tautan karya. Dokumen pribadi (KTP, ijazah, email, data wisudawan) sengaja **tidak** dimasukkan.
