# 02 — Alur Sistem Informasi Administrasi

## 2.1 Gambaran Alur Keseluruhan

Sistem informasi administrasi IEEE Student Branch IPB terdiri dari dua alur utama yang saling berkaitan: **alur surat masuk** dan **alur surat keluar**, keduanya bermuara pada sistem pengarsipan terpusat.

```
PIHAK EKSTERNAL / INTERNAL
         │
         ▼
  ┌─────────────┐
  │ SURAT MASUK │
  └──────┬──────┘
         │
         ▼
  ┌─────────────────────┐
  │  Sekretaris / VP    │ ◄── Pencatatan & Agenda Surat
  │   Administration    │
  └──────────┬──────────┘
             │
             ▼
      ┌──────────────┐
      │    DISPOSISI  │ ◄── Persetujuan Ketua
      └──────┬───────┘
             │
     ┌───────┴────────┐
     ▼                ▼
┌─────────┐     ┌──────────┐
│ Divisi A │     │ Divisi B │  (sesuai disposisi)
└────┬────┘     └─────┬────┘
     │                │
     └────────┬───────┘
              ▼
       ┌────────────┐
       │ TINDAK LANJUT│
       └──────┬─────┘
              │
              ▼
    ┌──────────────────┐
    │ PENGARSIPAN DIGITAL│ ◄── Google Drive + GitHub
    └──────────────────┘
```

---

## 2.2 Alur Surat Masuk

| Langkah | Aktivitas | Pelaksana | Output |
|---------|-----------|-----------|--------|
| 1 | Surat diterima (fisik/digital) | Sekretaris | — |
| 2 | Pencatatan di buku agenda / spreadsheet | Sekretaris | Nomor agenda surat masuk |
| 3 | Scan/digitalisasi surat fisik | Sekretaris | File digital (PDF) |
| 4 | Penyampaian ke Ketua untuk disposisi | Sekretaris | Lembar disposisi |
| 5 | Ketua menuliskan disposisi | Ketua | Arahan tindak lanjut |
| 6 | Surat didistribusikan ke divisi terkait | Sekretaris | Notifikasi internal |
| 7 | Divisi menindaklanjuti surat | Divisi terkait | Laporan tindak lanjut |
| 8 | Pengarsipan di folder Google Drive | Sekretaris | Surat terarsip |

---

## 2.3 Alur Surat Keluar

| Langkah | Aktivitas | Pelaksana | Output |
|---------|-----------|-----------|--------|
| 1 | Permintaan penerbitan surat dari divisi | Divisi | Draft permintaan |
| 2 | Penyusunan draft surat | Sekretaris | Draft surat |
| 3 | Review dan koreksi | VP Administration / Ketua | Draft revisi |
| 4 | Penomoran surat resmi | Sekretaris | Nomor surat |
| 5 | Penandatanganan oleh Ketua | Ketua | Surat resmi bertanda tangan |
| 6 | Pengiriman ke pihak yang dituju | Sekretaris | Bukti pengiriman |
| 7 | Pengarsipan salinan surat | Sekretaris | Surat terarsip |

---

## 2.4 Struktur Folder Arsip Digital (Google Drive)

```
📁 IEEE SB IPB — Arsip Administrasi/
├── 📁 2026/
│   ├── 📁 Surat Masuk/
│   │   ├── 📁 Januari/
│   │   ├── 📁 Februari/
│   │   └── ...
│   └── 📁 Surat Keluar/
│       ├── 📁 Januari/
│       ├── 📁 Februari/
│       └── ...
├── 📁 2025/
│   └── ...
└── 📄 Agenda Surat 2026.xlsx
```

---

## 2.5 Indikator Keberhasilan Sistem

| Indikator | Target |
|-----------|--------|
| Waktu pencatatan surat masuk | ≤ 1 hari kerja setelah diterima |
| Waktu disposisi oleh Ketua | ≤ 2 hari kerja |
| Kelengkapan arsip digital | 100% surat tercatat & tersimpan |
| Konsistensi format penomoran | 100% mengikuti konvensi |
