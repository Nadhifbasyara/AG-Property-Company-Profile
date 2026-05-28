# AG Property Company Profile

Landing page company profile untuk AG Property dengan tampilan hero, layanan unggulan, section about, alasan memilih kami, kontak, dan peta lokasi.

## Fitur

- Hero section dengan background properti
- Layanan unggulan dengan ikon dari folder `assets`
- Section About, Visi, dan Misi
- Section keunggulan dan alasan memilih AG Property
- Contact section dengan nomor telepon, email, dan Google Maps
- Footer informasi perusahaan

## Struktur Folder

```text
e:\ag-property
├── assets/
├── index.html
├── styles.css
└── README.md
```

## Menjalankan Secara Lokal

Cara paling mudah:

1. Buka `index.html` langsung di browser.

Kalau ingin lewat local server:

```bash
python -m http.server 8000
```

Lalu buka:

```text
http://localhost:8000
```

## Push ke GitHub

Folder ini belum menjadi git repository. Setelah kamu siap, jalankan:

```bash
git init
git add .
git commit -m "Initial company profile site"
git branch -M main
git remote add origin <URL_REPO_GITHUB>
git push -u origin main
```

Kalau kamu mau, aku juga bisa bantu siapkan file tambahan seperti `CNAME`, `favicon`, atau versi yang lebih siap deploy ke GitHub Pages.