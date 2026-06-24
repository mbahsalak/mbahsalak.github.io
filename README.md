# mbahsalak.github.io

Portfolio pribadi — simpel, gelap, dan cepat.

## Deploy ke GitHub Pages

1. Buat repo baru di GitHub dengan nama: `mbahsalak.github.io`
2. Upload semua file ini (index.html, style.css, main.js) ke repo tersebut
3. Pergi ke **Settings → Pages → Source: Deploy from branch → main**
4. Tunggu 1-2 menit, lalu buka: https://mbahsalak.github.io

## Kustomisasi

### Ganti info kontak
Edit bagian `<!-- CONTACT -->` di `index.html`:
- Ganti `href="mailto:..."` dengan email kamu
- Ganti link GitHub sesuai username asli

### Tambah proyek baru
Copy salah satu blok `<article class="project-card">` di `index.html` dan isi dengan info proyekmu.

### Ganti warna aksen
Di `style.css`, cari:
```css
--accent: #00e5a0;
```
Ganti dengan warna yang kamu mau.

## Struktur File

```
mbahsalak.github.io/
├── index.html     ← halaman utama
├── style.css      ← semua styling
├── main.js        ← scroll animation
└── README.md      ← ini
```
