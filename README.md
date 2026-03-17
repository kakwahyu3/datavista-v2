<div align="center">

<img src="icons/icon-192.png" alt="DataVista Logo" width="100"/>

# DataVista V2

### Media Pembelajaran Interaktif Statistika Kelas VIII SMP

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-0BAF7A?style=for-the-badge&logo=github)](https://setiawanw78.github.io/datavistaV2/)
[![PWA Ready](https://img.shields.io/badge/PWA-Ready-0BAF7A?style=for-the-badge&logo=pwa)](https://setiawanw78.github.io/datavistaV2/)
[![Offline](https://img.shields.io/badge/Offline-Support-0BAF7A?style=for-the-badge)](https://setiawanw78.github.io/datavistaV2/)

</div>

---

## 📌 Tentang Media

**DataVista** adalah media pembelajaran statistika berbasis web interaktif yang dikembangkan untuk siswa **SMP Kelas VIII / Fase D** menggunakan model **Project-Based Learning (PjBL)**. Media ini merupakan bagian dari penelitian disertasi di Program S3 Pendidikan Matematika, Universitas Pendidikan Indonesia.

> *Pengembangan Bahan Ajar Project-Based Learning Berbantuan Media Digital DataVista untuk Penguatan Literasi Statistik serta Resiliensi Siswa SMP*

---

## 👨‍🎓 Identitas Pengembang

| | |
|---|---|
| **Nama** | Wahyu Setiawan |
| **NIM** | 2211397 |
| **Program Studi** | S3 Pendidikan Matematika |
| **Institusi** | Universitas Pendidikan Indonesia |

### Dosen Pembimbing

| No | Nama | Jabatan |
|---|---|---|
| 1 | Prof. Dr. H. Nanang Priatna, M.Pd | Pembimbing I |
| 2 | Prof. Drs. Suhendra, M.Ed., Ph.D | Pembimbing II |
| 3 | Dr. Bambang Avip Priatna, M.Si | Pembimbing III |

---

## 🌐 Akses Media

| Platform | Link |
|---|---|
| 🌍 **Web Browser** | [setiawanw78.github.io/datavistaV2](https://setiawanw78.github.io/datavistaV2/) |
| 📱 **Android (PWA)** | Buka link → Install App |
| 🍎 **iPhone (PWA)** | Buka di Safari → Share → Add to Home Screen |
| 💻 **Desktop** | Buka link → ikon install di address bar |

---

## ✨ Fitur Unggulan

### 🏠 Beranda
- Identitas kelompok **cukup diisi sekali** — tampil otomatis di seluruh pertemuan
- Tujuan pembelajaran 5 butir menggunakan kata kerja operasional Bloom
- **Data tersimpan otomatis** via `localStorage`

### 📁 Proyek — 5 Pertemuan

| Pertemuan | Topik | Fitur |
|---|---|---|
| **P1** | Pertanyaan Mendasar | Observasi fenomena, prediksi awal |
| **P2** | Perencanaan & Penjadwalan | Instrumen, jadwal, pembagian tugas |
| **P3** | Pengumpulan Data | Tabel 40 responden (No · Kode · Durasi · Tujuan · Waktu) |
| **P4** | Pengolahan & Penyajian | Turus otomatis · Hitung statistik · Grafik interaktif · Analisis data kategori |
| **P5** | Presentasi & Evaluasi | Kesimpulan, rekomendasi, refleksi akhir |

### 📚 Materi

| Materi | Status | Keterangan |
|---|---|---|
| Mean (Rata-rata) | ✅ Wajib | Rumus, langkah, contoh |
| Median | ✅ Wajib | Data ganjil & genap |
| Modus | ✅ Wajib | Satu & lebih dari satu modus |
| Jangkauan | ✅ Wajib | Ukuran penyebaran sederhana |
| Penyajian Data | ✅ Wajib | Batang, garis, lingkaran, tabel frekuensi |
| Kuartil | ⭐ Pengayaan | Q1, Q2, Q3, Simpangan Kuartil |

### 🧮 Kalkulator Statistik Interaktif
- Siswa **mengisi langkah sendiri** — hasil hanya muncul setelah jawaban benar
- Feedback langsung: ✓ hijau (benar) / merah (coba lagi)
- Tab perhitungan: **Mean · Median · Modus · Jangkauan · Kuartil**
- Tabel distribusi frekuensi dengan **turus otomatis**

### 📊 Pengolahan Data Pertemuan 4
- **Data Numerik (Durasi):** Mean, Median, Modus, Jangkauan, Kuartil Q1/Q2/Q3 + Simpangan Kuartil
- **Data Kategori — Tujuan Penggunaan HP:**
  - Games · Belajar/Sekolah · Media Sosial · Hiburan/Streaming · Komunikasi · Belanja Online · Lainnya
  - Tabel frekuensi + turus + persentase + peringkat kategori otomatis dari data P3
- **Data Kategori — Waktu Penggunaan HP:**
  - Pagi (06.00–11.00) · Siang (11.01–15.00) · Sore (15.01–19.00) · Malam (19.01–23.00)
  - Analisis modus kategori, peringkat, persentase

### 📱 PWA (Progressive Web App)
- Install seperti aplikasi HP — muncul di layar utama
- **100% offline** setelah diinstall
- Service Worker cache-first strategy
- Banner install otomatis muncul saat membuka di browser

### 💾 Penyimpanan Otomatis
- Semua data tersimpan ke `localStorage` secara real-time
- Toast notifikasi "✓ Data tersimpan otomatis"
- Data tidak hilang saat berpindah halaman atau menutup browser

---

## 🎯 Capaian & Tujuan Pembelajaran

**Capaian Pembelajaran — Kurikulum Merdeka Fase D:**

> *Peserta didik dapat menentukan dan menafsirkan rerata (mean), median, modus, dan jangkauan (range) dari data tersebut untuk menyelesaikan masalah — termasuk membandingkan suatu data terhadap kelompoknya, membandingkan dua kelompok data, memprediksi, dan membuat keputusan.*

**Tujuan Pembelajaran (5 butir — kata kerja operasional Bloom):**

| No | Tujuan | Kata Kerja |
|---|---|---|
| 1 | Membaca data dalam tabel dan grafik dengan benar | Membaca |
| 2 | Menghitung mean, median, modus, jangkauan, dan kuartil secara sistematis | Menghitung |
| 3 | Menyajikan data ke dalam bentuk tabel dan diagram yang sesuai | Menyajikan |
| 4 | Menganalisis data nyata penggunaan HP menggunakan ukuran pemusatan & penyebaran | Menganalisis |
| 5 | Menyimpulkan hasil analisis untuk membuat keputusan sederhana | Menyimpulkan |

---

## 🚀 Cara Penggunaan

### Untuk Guru (Setup Awal)
```
1. Buka https://setiawanw78.github.io/datavistaV2/ di browser
2. Bagikan link ke siswa via WhatsApp / Google Classroom
3. Minta siswa install PWA untuk akses offline
4. Pantau progres via checklist di akhir setiap pertemuan
```

### Untuk Siswa
```
1. Buka link yang diberikan guru di Chrome/Edge
2. Tap "Install DataVista" pada banner yang muncul (offline support)
3. Isi identitas kelompok di menu Beranda — cukup sekali!
4. Pilih Proyek → Pertemuan sesuai jadwal
5. Kerjakan aktivitas bersama kelompok
6. Gunakan menu Kalkulator untuk menghitung statistik
7. Unduh PDF di akhir setiap pertemuan
```

### Cara Install PWA

| Platform | Langkah |
|---|---|
| **Android (Chrome)** | Buka link → tunggu 3 detik → tap banner "Install Sekarang" |
| **iPhone (Safari)** | Buka link → tap ikon Share → "Add to Home Screen" → Add |
| **Laptop (Chrome/Edge)** | Buka link → klik ikon ⊕ di address bar → Install |

---

## 📂 Struktur Repository

```
datavistaV2/
│
├── index.html          ← Aplikasi utama (single-file, self-contained)
├── manifest.json       ← PWA manifest (nama, ikon, warna)
├── sw.js               ← Service Worker (cache offline)
├── README.md           ← Dokumentasi ini
│
└── icons/              ← Ikon aplikasi PWA (semua ukuran)
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-192.png
    ├── icon-384.png
    └── icon-512.png
```

---

## 🛠️ Teknologi

| Teknologi | Versi | Kegunaan |
|---|---|---|
| HTML5 + CSS3 | — | Struktur & tampilan responsif |
| Vanilla JavaScript | ES2020 | Logika interaktif & data management |
| Chart.js | 4.4.1 | Grafik interaktif (batang, garis, lingkaran) |
| Google Fonts | — | Sora + Plus Jakarta Sans |
| localStorage API | — | Penyimpanan data otomatis |
| Service Worker API | — | Cache offline (PWA) |
| Web App Manifest | — | Install sebagai aplikasi |

> ✅ **Tidak memerlukan server, database, framework, atau instalasi apapun.**
> Cukup satu file `index.html` — buka langsung di browser, jalan offline.

---

## 📋 Persyaratan Sistem

| Komponen | Minimum |
|---|---|
| Browser | Chrome 80+ / Edge 80+ / Firefox 75+ / Safari 13+ |
| Koneksi | Diperlukan pertama kali untuk Google Fonts & Chart.js |
| Layar | Mobile: 360px+ · Tablet: 600px+ · Desktop: 900px+ |
| Storage | ~5 MB localStorage untuk menyimpan data kelompok |

> 💡 Logo UPI dan DataVista sudah di-embed sebagai base64 — tampil meski tanpa internet.

---

## 📝 Catatan Teknis & Pengembangan

- **Kuartil** ditempatkan sebagai materi **opsional/pengayaan** karena tidak termasuk dalam materi wajib kelas VIII Kurikulum Merdeka Fase D (lebih tepat untuk kelas IX atau SMA)
- Tujuan pembelajaran menggunakan **kata kerja operasional Bloom** yang terukur dan dapat dinilai
- Beban kognitif per pertemuan dibatasi **3 aktivitas + 2 pertanyaan refleksi** untuk menghindari cognitive overload
- Identitas kelompok hanya diisi sekali untuk menghindari pengisian berulang di 5 pertemuan
- Data kategori (Tujuan & Waktu) diolah otomatis dari tabel pengumpulan P3 ke analisis P4
- Layout **responsif penuh**: Mobile (bottom nav) · Tablet · Desktop (sidebar nav)

---

## 🔄 Changelog

### V2.0 (2025)
- ✅ Redesain UI/UX — font Sora + Plus Jakarta Sans, palet teal konsisten
- ✅ Navigasi 5 menu: Beranda · Proyek · Materi · Kalkulator · Tentang
- ✅ Layout responsif: mobile bottom nav + desktop sidebar
- ✅ Identitas kelompok sekali isi, tampil di semua pertemuan
- ✅ Tujuan pembelajaran dipangkas dari 14 → 5 butir terukur
- ✅ Petunjuk disederhanakan dari 9 → 5 langkah
- ✅ Pertemuan 3: tabel 40 baris (No · Kode · Durasi · Tujuan · Waktu)
- ✅ Pertemuan 4: tabel turus otomatis + kalkulator isian mandiri + grafik + analisis data kategori
- ✅ Kalkulator: Mean · Median · Modus · Jangkauan · Kuartil (Q1/Q2/Q3 + Simpangan Kuartil)
- ✅ PWA support: Service Worker, manifest, install prompt
- ✅ Penyimpanan data otomatis via localStorage
- ✅ Halaman Tentang: identitas pengembang & dosen pembimbing
- ✅ Logo UPI & DataVista embed base64 (offline-safe)

### V1.0
- Versi awal media pembelajaran DataVista

---

## 📄 Lisensi & Hak Cipta

```
© 2025 Wahyu Setiawan — Universitas Pendidikan Indonesia

Media ini dikembangkan untuk keperluan penelitian pendidikan.
Penggunaan untuk keperluan pembelajaran diperbolehkan dengan
menyertakan atribusi kepada pengembang.

Dilarang: Distribusi komersial tanpa izin tertulis dari pengembang.
```

---

<div align="center">

**DataVista V2** · Statistika Kelas VIII · Universitas Pendidikan Indonesia · 2025

*Mengembangkan literasi statistik dan resiliensi siswa SMP melalui pembelajaran berbasis proyek*

</div>

