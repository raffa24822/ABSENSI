# Absensi Hari & Cek Kesehatan 2026

## PENTING: upload isi folder, bukan file ZIP

GitHub dan Render harus menerima file project yang sudah diekstrak. Repository harus memiliki `index.html` di root.

### Struktur repository

```text
absensi-hari/
├── index.html
├── render.yaml
└── README.md
```

### GitHub

1. Buat repository baru.
2. Extract ZIP ini di komputer.
3. Upload **isi** folder ke repository, sehingga `index.html` langsung berada di root repository.
4. Commit ke branch `main`.

### Render

Di Render pilih **New → Static Site**, hubungkan repository GitHub, lalu:

- Branch: `main`
- Build Command: kosong
- Publish Directory: `.`

Klik Deploy.

### Catatan data

Aplikasi menggunakan `localStorage`, sehingga data absensi tersimpan di browser/perangkat masing-masing dan tidak menjadi database bersama.
