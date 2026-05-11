# Portfolio Assets

Repository ini digunakan sebagai media storage untuk seluruh asset portfolio pribadi saya.

Tujuan utama repository ini adalah untuk menyimpan image dan static assets yang digunakan pada website portfolio, lalu mengambilnya melalui CDN link agar dapat digunakan secara langsung tanpa backend atau image server sendiri.

---

## 📦 Contents

Repository ini berisi:

- Project thumbnails
- Markdown images
- Author avatars
- OG images
- Misc assets

---

## 📁 Structure

```txt
portfolio-assets/
│
├── thumbnails/
├── markdown/
├── avatars/
├── og/
└── misc/
```

---

## 🚀 Usage

Asset di repository ini digunakan melalui CDN:

```txt
https://cdn.jsdelivr.net/gh/USERNAME/REPO@main/path/file.webp
```

Contoh:

```txt
https://cdn.jsdelivr.net/gh/anugerahgari/portfolio-assets@main/thumbnails/project-1.webp
```

---

## 🖼 Recommended Image Format

Disarankan menggunakan:

```txt
WEBP
```

karena:

- ukuran lebih kecil
- loading lebih cepat
- kualitas tetap bagus
- cocok untuk portfolio modern

---

## 📐 Recommended Sizes

| Asset | Recommended Size |
|---|---|
| Thumbnail | 960×540 |
| Markdown Image | 1200×675 |
| Avatar | 256×256 |
| OG Image | 1200×630 |

---

## 🎯 Purpose

Repository ini dibuat khusus untuk kebutuhan pribadi sebagai static asset storage untuk portfolio project.

Karena portfolio masih menggunakan static data dan belum menggunakan backend/storage service sendiri, repository ini berfungsi sebagai lightweight CDN source melalui jsDelivr.

---

## 🔗 CDN Provider

Asset delivery menggunakan:

- jsDelivr CDN
- GitHub Repository

---

## 📄 Notes

Repository ini bukan media storage umum atau public image hosting platform.

Seluruh asset di dalam repository ini digunakan khusus untuk project dan portfolio pribadi.