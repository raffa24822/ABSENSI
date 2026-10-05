# Absensi Hari & Cek Kesehatan 2026

Aplikasi web absensi berbasis HTML/JavaScript.

## Deploy ke GitHub

1. Buat repository baru di GitHub, misalnya `absensi-hari`.
2. Upload `index.html`, `README.md`, dan `render.yaml`.
3. Commit ke branch utama (`main`).

## Deploy ke Render

1. Masuk ke Render.
2. Pilih **New +** → **Static Site**.
3. Hubungkan repository GitHub ini.
4. Render akan membaca konfigurasi `render.yaml`.
5. Setelah deploy selesai, Render akan memberikan URL publik.

## Catatan penyimpanan data

Aplikasi saat ini menyimpan data absensi menggunakan `localStorage` browser. Data tidak tersimpan sebagai database server dan tidak otomatis dibagikan antar perangkat/browser.

Gunakan fitur ekspor JSON di aplikasi untuk membuat backup data.

## Struktur

- `index.html` — aplikasi utama
- `render.yaml` — konfigurasi deployment Render
- `README.md` — panduan
