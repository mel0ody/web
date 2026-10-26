# Portofolio Hosana Melody

Website portofolio statis (HTML + CSS + JavaScript murni, tanpa build tool).

## Struktur folder

```
portofolio/
├── index.html            ← kerangka halaman
├── css/
│   └── style.css         ← semua gaya + tema warna
├── js/
│   ├── config.js         ← DATA/BIODATA (edit di sini saja)
│   ├── icons.js          ← ikon SVG + fungsi bantu
│   └── main.js           ← render, animasi, pemutar lagu, form
├── images/
│   ├── foto/             ← taruh foto profil (mis. foto.jpg)
│   ├── projects/         ← gambar project (sudah ada 1 gambar)
│   └── posters/          ← poster film asli (opsional)
├── files/                ← taruh CV di sini (mis. cv.pdf)
└── README.md
```

## Cara menjalankan
Buka `index.html` langsung di browser (double-click). Butuh internet untuk
font Inter dan pratinjau lagu.

## Cara mengubah isi
Semua teks ada di `js/config.js`:
- Ganti tema: `theme: "mauve"` (pilihan: mauve, mauvelight, rose, rosecream, navy, iceblue, espresso, neapolitan, emerald, ocean, sunset, amber)
- Foto profil: simpan di `images/foto/foto.jpg`, lalu isi `foto: "images/foto/foto.jpg"`
- CV: simpan di `files/cv.pdf`, lalu isi `cv: "files/cv.pdf"`
- Poster film: simpan di `images/posters/`, lalu isi `poster: "images/posters/nama.jpg"`
- Project baru: tambah objek di array `projects`, gambar di `images/projects/`

## Urutan script (jangan dibalik)
`config.js` → `icons.js` → `main.js`

## Deploy gratis
Upload seluruh folder ke GitHub Pages, Netlify, atau Vercel.
