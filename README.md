# HIMAKSI — Dari Sejarah Menuju Arah Perubahan

Website statis responsif untuk GitHub Pages. Versi ini menggunakan struktur file terpisah agar source code lebih rapi dan mudah diedit.

## Struktur folder

```text
himaksi/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    ├── slide-01.jpg
    ├── slide-02.jpg
    ├── ...
    └── slide-10.jpg
```

**Penting:** `index.html`, `style.css`, `script.js`, dan folder `assets/` harus berada di lokasi seperti di atas. Jangan upload `index.html` saja karena file CSS, JavaScript, dan gambar dipanggil dari file/folder terpisah.

## Cara upload / memperbaiki repository GitHub

1. Download dan ekstrak ZIP ini di komputer.
2. Buka repository GitHub kamu.
3. Klik **Add file → Upload files**.
4. Upload **semua isi folder** hasil ekstrak: `index.html`, `style.css`, `script.js`, `README.md`, dan folder `assets` beserta seluruh gambar.
5. Pastikan file `index.html` berada langsung di root repository, bukan di folder tambahan.
6. Isi pesan commit, misalnya `Fix and organize HIMAKSI website`, lalu klik **Commit changes**.
7. Buka **Settings → Pages**. Pilih **Deploy from a branch**, branch `main`, folder `/(root)`, lalu klik **Save** jika belum sesuai.
8. Buka tab **Actions** dan periksa proses deployment. Jika berhasil, buka URL GitHub Pages yang tertera di Settings → Pages.
9. Jika masih melihat tampilan lama, lakukan hard refresh dengan `Ctrl + F5`.

## Fitur

- Landing page editorial dengan palet navy, biru, dan emas
- Perjalanan sejarah dan refleksi HIMAKSI
- Bagian tim: **“Kami Juga Terus Bertumbuh”**
- Galeri 10 slide dan mode presentasi
- Navigasi keyboard dan swipe di perangkat sentuh
- Tampilan responsif untuk desktop dan ponsel

## Catatan konten

Visual slide dipertahankan sebagai gambar untuk menjaga desain. Slide 3 memuat ringkasan sejarah HIMAKSI dari dokumen sumber. Nama pendiri, ketua pertama, dan detail lain yang belum terverifikasi tidak ditambahkan.


## Perbaikan tampilan layar
Versi ini membatasi lebar halaman ke viewport, mengurangi risiko konten bergeser/terpotong secara horizontal, dan menyesuaikan hero section untuk layar desktop lebar, laptop, tablet, serta ponsel.
