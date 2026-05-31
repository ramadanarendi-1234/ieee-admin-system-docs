# 01 — Gambaran Umum Sistem Administrasi

## 1.1 Latar Belakang

IEEE Student Branch IPB University merupakan organisasi kemahasiswaan bertaraf internasional yang memerlukan sistem administrasi terstruktur untuk mengelola korespondensi internal maupun eksternal. Sistem ini dirancang untuk memastikan setiap surat menyurat tercatat, terarsip, dan dapat ditelusuri secara efisien.

---

## 1.2 Ruang Lingkup Sistem

Sistem Informasi Administrasi & Surat Menyurat ini mencakup:

- **Surat Masuk** — surat dari pihak eksternal (institusi, sponsor, mitra) maupun internal organisasi IPB
- **Surat Keluar** — surat resmi yang diterbitkan atas nama IEEE Student Branch IPB
- **Pengarsipan Digital** — penyimpanan dan pengelolaan dokumen secara terstruktur
- **Disposisi** — mekanisme pendistribusian surat kepada pihak yang berwenang

---

## 1.3 Pemangku Kepentingan (Stakeholders)

| Peran | Tanggung Jawab |
|-------|----------------|
| Sekretaris / VP Administration | Menerima, mencatat, dan mendistribusikan surat masuk; menerbitkan surat keluar |
| Ketua (Chair) | Menandatangani surat resmi; menyetujui disposisi |
| Divisi Terkait | Menindaklanjuti surat sesuai disposisi |
| Anggota Umum | Menerima informasi dari surat yang didistribusikan |

---

## 1.4 Komponen Utama Sistem

```
┌─────────────────────────────────────────────┐
│         SISTEM ADMINISTRASI IEEE SB IPB      │
├──────────────┬──────────────┬───────────────┤
│  Surat Masuk │ Surat Keluar │  Pengarsipan  │
│  (Incoming)  │  (Outgoing)  │   (Archive)   │
└──────────────┴──────────────┴───────────────┘
```

---

## 1.5 Konvensi Penomoran Surat

### Format Nomor Surat

[Nomor Surat]/[Kode Surat]/[Jenis Surat]/IEEESBIPB/[Bulan Romawi]/[Tahun]

Contoh: 001/A.1/SK/IEEESBIPB/I/2026

| Segmen | Keterangan |
|--------|------------|
| `001` | Nomor urut surat dalam tahun berjalan |
| `A.1` | Kode surat (jabatan/divisi penerbit) |
| `SK` | Jenis surat |
| `IEEESBIPB` | Identitas organisasi |
| `I` | Bulan dalam angka Romawi |
| `2026` | Tahun penerbitan |

---

## 1.6 Media & Platform yang Digunakan

| Kebutuhan | Platform |
|-----------|----------|
| Penyusunan surat | Google Docs / Microsoft Word |
| Penyimpanan arsip | Google Drive (terstruktur per folder) |
| Komunikasi internal | WhatsApp Group / LINE |
| Version control dokumentasi | GitHub |
| Format dokumentasi | Markdown (.md) |
