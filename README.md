# 🎓 Danusin — Marketplace Dana Usaha Mahasiswa UNJ

![Danusin Banner](https://via.placeholder.com/1200x400?text=Danusin+-+Platform+Danus+Digital+UNJ)

[![Status](https://img.shields.io/badge/Status-In_Development-brightgreen)](#)
[![University](https://img.shields.io/badge/Campus-Universitas_Negeri_Jakarta-blue)](#)

**Danusin** adalah platform web *marketplace* hiper-lokal yang dirancang khusus untuk mempermudah dan mendigitalisasi kegiatan Dana Usaha (Danus) program kerja maupun *event* kemahasiswaan di lingkungan Universitas Negeri Jakarta (UNJ).

Proyek ini dikembangkan berdasarkan hasil riset pengguna (*User Research*) pada mata kuliah Desain Web (PTIK UNJ) untuk mengatasi hambatan jualan konvensional, risiko kerugian barang basi, serta ketidakpastian lokasi *pick-up* pesanan.

---

## ✨ Fitur Utama

- 🔍 **Filter Hiper-Lokal Kampus:** Cari produk danus berdasarkan tingkat kepanitiaan (Prodi, Fakultas, Universitas), nama BEM/UKM, hingga *event* spesifik.
- 📦 **Manajemen Pre-Order (PO) & Kuota:** Sistem PO terstruktur dengan batas waktu (*deadline*) dan pelacak kuota stok otomatis untuk mencegah kerugian produk sisa/basi.
- 💳 **Gateway QRIS dengan Countdown Timer:** Pembayaran *cashless* instan via QRIS dilengkapi batas waktu pembayaran 15 menit.
- 📍 **Peta Denah UNJ Interaktif:** Penjual dapat menandai titik kumpul (*Pick-up Spot*) langsung di peta kampus UNJ untuk kemudahan serah-terima barang.
- 💬 **Live Chat Terintegrasi:** Fitur obrolan langsung antara pembeli dan panitia danus dilengkapi *widget* peta lokasi *real-time*.
- 🛡️ **Verifikasi Legalitas Kepanitiaan:** Alur pendaftaran penjual wajib mengunggah Surat Keterangan Kegiatan resmi (disetujui Dosen Pembimbing/Ketuplak) untuk mendapatkan *Verified Badge* (✓) guna mencegah penipuan proker fiktif.
- 📊 **Dashboard Penjual (Seller Dashboard):** Panel kelola stok, pencatatan transaksi otomatis, dan rekapitulasi laporan penjualan kas danus.

---

## 🛠️ Tech Stack & Tools

- **Frontend:** HTML5, CSS3 / Tailwind CSS, JavaScript (React / Vue)
- **Backend & Database:** Node.js / PHP / Firebase Realtime Database
- **UI/UX Design:** Figma
- **Maps Integration:** Leaflet.js / Custom Interactive SVGs (Denah Kampus UNJ)

---

## 📸 Tampilan UI / Mockup

| Katalog & Filter | Gateway QRIS | Peta Tikum UNJ & Chat |
| :---: | :---: | :---: |
| ![Katalog](https://via.placeholder.com/300x200?text=Katalog+Danusin) | ![QRIS](https://via.placeholder.com/300x200?text=QRIS+Payment) | ![Map](https://via.placeholder.com/300x200?text=Peta+UNJ+%26+Chat) |

---

## 📌 Alur Verifikasi Penjual

```text
[Dashboard Penjual] ──> [Upload Surat Resmi (Dosen/Ketuplak)] ──> [Review Admin] ──> [Verified Badge (✓)]