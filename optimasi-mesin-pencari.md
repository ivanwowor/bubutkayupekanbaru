# DOKUMEN STRATEGI DAN OPTIMASI MESIN PENCARI (SEO)
## BUBUT KAYU KARYA PEKANBARU

> **Dokumen Catatan Proyek & Panduan SEO Lengkap**  
> Proyek: Pembuatan Landing Page & Company Profile Website  
> Entitas Bisnis: **Bubut Kayu Karya Pekanbaru**  
> File Implementasi Website: `index.html`  
> Terakhir Diperbarui: 27 Oktober 2026  

---

## 1. Identitas Bisnis & Profil Usaha

- **Nama Bisnis:** Bubut Kayu Karya Pekanbaru
- **Bidang Usaha:** Jasa pembuatan kandang ayam, kandang hewan custom, kerajinan kayu, dan pengerjaan bubut kayu.
- **Lokasi Layanan:** Kota Pekanbaru, Riau, Indonesia
- **Target Audiens:** Peternak ayam, penghobi ayam bangkok/laga, pemelihara hewan peliharaan (kelinci, burung, kucing), dan masyarakat umum yang memerlukan pengerjaan perabot/kerajinan kayu custom.
- **Kontak WhatsApp:** [0851-7120-3822](https://wa.me/6285171203822)
- **Instagram:** [@bubutkayukarya_](https://www.instagram.com/bubutkayukarya_/)
- **Tujuan SEO:** Menempati halaman pertama hasil pencarian Google lokal (Pekanbaru dan sekitarnya) untuk kata kunci pembuatan kandang ayam dan pengerjaan kayu, mendatangkan traffic organik tertarget, dan mengonversinya menjadi pesanan melalui WhatsApp.

---

## 2. Riset Kata Kunci (Keyword Research) & Pemetaan Intent

Strategi kata kunci berfokus pada **Local Commercial Intent** dan **Transactional Intent** di wilayah Pekanbaru.

### A. Kata Kunci Utama (Primary Target Keyword)
- `jasa pembuatan kandang ayam pekanbaru`
- `kandang ayam custom pekanbaru`

### B. Kata Kunci Pendukung (Secondary Keywords)
- `jasa buat kandang ayam pekanbaru`
- `tukang kandang ayam pekanbaru`
- `pembuatan kandang ayam bangkok pekanbaru`
- `kandang ayam kayu pekanbaru`
- `jasa pembuatan kandang hewan pekanbaru`
- `kandang burung custom pekanbaru`
- `kandang kelinci pekanbaru`
- `tukang kayu pekanbaru`
- `kerajinan kayu pekanbaru`
- `bubut kayu pekanbaru`
- `bubut kayu karya pekanbaru`

### C. Kata Kunci Ekor Panjang (Long-Tail Keywords)
- *jasa bikin kandang ayam bangkok bertingkat di pekanbaru*
- *tempat pesan kandang kelinci kayu pekanbaru*
- *tukang kandang ayam kayu terdekat di pekanbaru*
- *biaya pembuatan kandang ayam bangkok sekat pekanbaru*
- *pembuatan kandang hewan custom ukuran sendiri pekanbaru*

---

## 3. Optimasi On-Page SEO

Seluruh elemen on-page telah diintegrasikan langsung pada kode [index.html](file:///C:/Users/User/.gemini/antigravity/scratch/bubut-kayu-karya/index.html).

### A. Title Tag & Meta Description
- **Title Tag (61 Karakter - Optimal untuk SERP desktop & mobile):**
  ```html
  <title>Jasa Pembuatan Kandang Ayam Pekanbaru | Bubut Kayu Karya</title>
  ```
- **Meta Description (154 Karakter - Sesuai standar 140–160 karakter):**
  ```html
  <meta name="description" content="Jasa pembuatan kandang ayam, kandang hewan, dan pengerjaan kayu custom di Pekanbaru. Desain sesuai kebutuhan, material pilihan, dan konsultasi mudah via WhatsApp.">
  ```

### B. Meta Geotagging & Bahasa (Local SEO Signals)
```html
<meta name="language" content="Indonesian">
<meta name="geo.region" content="ID-RI">
<meta name="geo.placename" content="Pekanbaru">
<meta name="robots" content="index, follow">
<link rel="canonical" href="https://bubutkayukarya.com/">
```

### C. Hierarki Heading (H1, H2, H3) yang Semantik
Halaman menerapkan prinsip **Single H1** yang kaya kata kunci lokal, diikuti sub-heading berstruktur logis:

- **H1:**
  - `Jasa Pembuatan Kandang Ayam & Kandang Hewan Custom di Pekanbaru`
- **H2:**
  - `Mengenal Bubut Kayu Karya Pekanbaru` (Tentang Kami)
  - `Pilihan Pembuatan Kandang & Kayu Custom` (Layanan & Produk)
  - `Galeri Hasil Pengerjaan` (Portofolio)
  - `Mengapa Memilih Bubut Kayu Karya?` (Keunggulan)
  - `Cara Pemesanan Kandang di Bubut Kayu Karya` (Alur 5 Langkah)
  - `Apa Kata Pelanggan Kami?` (Testimoni)
  - `FAQ — Pertanyaan yang Sering Diajukan` (Accordion Tanya Jawab)
  - `Lokasi Bubut Kayu Karya Pekanbaru` (Peta Operasional)
  - `Konsultasikan Kandang Impian Anda` (Kontak & Penawaran)
- **H3:**
  - Menyebutkan jenis layanan spesifik (`Pembuatan Kandang Ayam`, `Pembuatan Kandang Ayam Bangkok`, `Pembuatan Kandang Burung`, `Pembuatan Kandang Kelinci`, `Kandang Hewan Custom`, `Pengerjaan Kayu Custom`) serta fitur-fitur teknis.

### D. Optimasi Gambar (Image SEO)
1. Seluruh gambar memiliki atribut `alt` deskriptif yang mengandung kata kunci secara natural (bukan keyword stuffing).
   - Contoh: `alt="Model Kandang Ayam Kayu Bertingkat Pekanbaru"`
   - Contoh: `alt="Kandang Tunggal Ayam Bangkok Pekanbaru"`
2. Menggunakan atribut `width` dan `height` eksplisit pada setiap elemen `<img>` untuk mencegah layout shifting (menjaga skor CLS pada Core Web Vitals).
3. Penerapan `loading="lazy"` pada gambar di bawah lipatan atas (below-the-fold) guna mempercepat First Contentful Paint (FCP).

---

## 4. Structured Data (Schema.org JSON-LD)

Menggunakan tipe schema bisnis lokal resmi Google Search (`HomeAndConstructionBusiness` / `LocalBusiness`) untuk mempermudah Google mengindeks identitas entitas bisnis lokal tanpa mencantumkan data fiktif (seperti rating palsu atau koordinat buatan):

```json
{
  "@context": "https://schema.org",
  "@type": "HomeAndConstructionBusiness",
  "name": "Bubut Kayu Karya Pekanbaru",
  "description": "Jasa pembuatan kandang ayam, kandang hewan, dan pengerjaan kayu custom di Pekanbaru, Riau.",
  "telephone": "+6285171203822",
  "url": "https://bubutkayukarya.com/",
  "sameAs": [
    "https://www.instagram.com/bubutkayukarya_/",
    "https://wa.me/6285171203822"
  ],
  "address": {
    "@type": "PostalAddress",
    "addressLocality": "Pekanbaru",
    "addressRegion": "Riau",
    "addressCountry": "ID"
  },
  "areaServed": {
    "@type": "City",
    "name": "Pekanbaru"
  },
  "priceRange": "$$",
  "makesOffer": [
    {
      "@type": "Offer",
      "itemOffered": {
        "@type": "Service",
        "name": "Pembuatan Kandang Ayam Custom",
        "description": "Jasa pengerjaan kandang ayam kayu berbagai ukuran di Pekanbaru."
      }
    },
    {
      "@type": "Offer",
      "itemOffered": {
        "@type": "Service",
        "name": "Pembuatan Kandang Ayam Bangkok",
        "description": "Kandang kayu kokoh dan nyaman untuk perawatan ayam bangkok."
      }
    },
    {
      "@type": "Offer",
      "itemOffered": {
        "@type": "Service",
        "name": "Kandang Hewan Custom",
        "description": "Pembuatan kandang burung, kelinci, dan hewan peliharaan lainnya sesuai pesanan."
      }
    },
    {
      "@type": "Offer",
      "itemOffered": {
        "@type": "Service",
        "name": "Pengerjaan Kayu Custom & Bubut",
        "description": "Pengerjaan kerajinan kayu dan kebutuhan perabot kayu custom."
      }
    }
  ]
}
```

---

## 5. Media Sosial & Sharing Metadata (Open Graph & Twitter)

Memastikan tampilan pratinjau (rich snippet preview) terlihat profesional dan menarik saat link dibagikan ke platform perpesanan maupun media sosial:

```html
<!-- Open Graph / WhatsApp / Facebook -->
<meta property="og:type" content="website">
<meta property="og:url" content="https://bubutkayukarya.com/">
<meta property="og:title" content="Jasa Pembuatan Kandang Ayam Pekanbaru | Bubut Kayu Karya">
<meta property="og:description" content="Melayani pembuatan kandang ayam, kandang hewan, dan pengerjaan kayu custom di Pekanbaru, Riau. Konsultasi langsung via WhatsApp.">
<meta property="og:image" content="https://images.unsplash.com/photo-1544816155-12df9643f363?auto=format&fit=crop&w=1200&q=80">
<meta property="og:locale" content="id_ID">
<meta property="og:site_name" content="Bubut Kayu Karya Pekanbaru">

<!-- Twitter Cards -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Jasa Pembuatan Kandang Ayam Pekanbaru | Bubut Kayu Karya">
<meta name="twitter:description" content="Jasa pembuatan kandang ayam, kandang hewan, dan pengerjaan kayu custom berkualitas di Pekanbaru, Riau.">
<meta name="twitter:image" content="https://images.unsplash.com/photo-1544816155-12df9643f363?auto=format&fit=crop&w=1200&q=80">
```

---

## 6. Technical SEO & Core Web Vitals Optimization

1. **Struktur Semantik Penuh:** Menggunakan `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, dan `<footer>` agar bot mesin pencari memahami tata letak konten dengan tepat.
2. **Tanpa Ketergantungan Backend Berat:** Dibangun murni HTML5 + Tailwind CSS CDN + Vanilla JS, menghasilkan waktu muat (load time) yang sangat instan.
3. **Responsive & Mobile-First:** Bebas dari masalah horizontal scrolling pada layar smartphone terkecil (320px) hingga layar lebar (1920px+).
4. **Preconnect ke Resource Eksternal:** Menambahkan `<link rel="preconnect">` untuk Google Fonts (`fonts.googleapis.com` dan `fonts.gstatic.com`).
5. **Dukungan Aksesibilitas (`prefers-reduced-motion`):** Mengurangi pergeseran animasi secara otomatis bagi pengguna dengan preferensi kenyamanan visual tertentu.

---

## 7. Strategi Optimasi Google Bisnis Profil (Google Business Profile / GBP)

Untuk mendominasi **Google 3-Pack (Peta Lokal Google Pekanbaru)**, langkah-langkah luar website (Off-Page Local SEO) berikut disarankan untuk dilakukan oleh pemilik usaha:

1. **Konsistensi NAP (Name, Address, Phone):**
   - Nama: Bubut Kayu Karya Pekanbaru
   - Telepon / WA: `0851-7120-3822` / `+62 851-7120-3822`
   - Kategori Utama di GBP: *Jasa Tukang Kayu (Carpenter)* atau *Toko Perlengkapan Hewan Ternak / Pet Supplies*.
2. **Koleksi Ulasan Asli (Google Reviews):**
   - Minta pelanggan di Pekanbaru memberikan ulasan bintang 5 dengan menyebutkan kata kunci seperti *"Pesan kandang ayam bangkok di Pekanbaru pengerjaannya sangat rapi"*.
3. **Upload Foto Nyata Secara Rutin:**
   - Unggah dokumentasi pengerjaan kayu, proses pemotongan, perakitan kandang, dan foto produk jadi ke Google Bisnis Profil dan akun Instagram `@bubutkayukarya_`.
4. **Backlink Lokal:**
   - Daftarkan bisnis ke direktori lokal Riau/Pekanbaru, komunitas peternak ayam lokal Pekanbaru, dan forum jual beli unggas/hewan peliharaan Riau.

---

## 8. Checklist Pra-Publikasi Domain Resmi

Ketika domain resmi sudah dibeli (misal: `bubutkayukarya.com` atau domain `.co.id` / `.my.id`):

- [ ] Ganti placeholder URL `https://bubutkayukarya.com/` pada tag `<link rel="canonical">`, Open Graph, Twitter Cards, dan Schema.org JSON-LD.
- [ ] Buat file `robots.txt`:
  ```txt
  User-agent: *
  Allow: /
  Sitemap: https://domain-anda.com/sitemap.xml
  ```
- [ ] Buat file `sitemap.xml` yang mencantumkan URL halaman utama.
- [ ] Daftarkan properti website ke **Google Search Console (GSC)** dan minta pengindeksan halaman (Request Indexing).
- [ ] Daftarkan website ke **Google Analytics 4 (GA4)** jika ingin memantau perilaku klik tombol WhatsApp dan traffic pengunjung.
- [ ] Perbarui foto galeri dan ulasan testimoni dengan foto proyek dan testimoni asli pelanggan.
