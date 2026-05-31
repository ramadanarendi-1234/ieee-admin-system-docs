# 05 — Sistem Pengarsipan Digital

| Atribut | Keterangan |
|---------|-----------|
| **Nama Dokumen** | Panduan Sistem Pengarsipan Digital |
| **Kode Dokumen** | SOP-ADM-003 |
| **Versi** | 1.0 |
| **Tanggal Berlaku** | 1 Januari 2026 |
| **Dibuat Oleh** | Rendi Ramadana |

---

## 5.1 Prinsip Pengarsipan

Sistem pengarsipan IEEE Student Branch IPB mengikuti prinsip **DART**:

| Prinsip | Keterangan |
|---------|------------|
| **D**iscoverable | Mudah ditemukan melalui penamaan dan struktur folder yang konsisten |
| **A**ccessible | Dapat diakses oleh pihak yang berwenang kapan saja |
| **R**eliable | Terjamin keaslian dan kelengkapannya |
| **T**raceable | Setiap dokumen memiliki jejak yang dapat ditelusuri |

---

## 5.2 Struktur Folder Google Drive

```
📁 IEEE SB IPB — Arsip Administrasi/
│
├── 📁 2026/
│   ├── 📁 Surat Masuk/
│   │   ├── 📁 01-Januari/
│   │   ├── 📁 02-Februari/
│   │   ├── 📁 03-Maret/
│   │   ├── 📁 04-April/
│   │   ├── 📁 05-Mei/
│   │   └── ...
│   ├── 📁 Surat Keluar/
│   │   ├── 📁 01-Januari/
│   │   ├── 📁 02-Februari/
│   │   └── ...
│   └── 📄 Agenda Surat 2026.xlsx
│
├── 📁 2025/
│   └── [struktur sama]
│
└── 📄 Panduan Pengarsipan.pdf
```

---

## 5.3 Konvensi Penamaan File

### Surat Masuk

```
SM-[NomorAgenda]-[PerihalSingkat].pdf
```

| Komponen | Keterangan | Contoh |
|----------|-----------|--------|
| `SM` | Kode surat masuk | SM |
| `NomorAgenda` | 3 digit nomor urut | 001 |
| `PerihalSingkat` | Maksimal 5 kata, pisah dengan tanda hubung | Undangan-Workshop-AI |

**Contoh lengkap:** `SM-001-Undangan-Workshop-AI.pdf`

### Surat Keluar

```
SK-[NomorUrut]-[PerihalSingkat].pdf
```

**Contoh lengkap:** `SK-003-Permohonan-Sponsorship-Dies-Natalis.pdf`

---

## 5.4 Agenda Surat (Spreadsheet)

### Struktur Spreadsheet Agenda Surat Masuk

| No. Agenda | Tgl. Terima | Tgl. Surat | Asal Surat | Perihal | Disposisi Kepada | Status | Link File |
|------------|-------------|------------|------------|---------|-----------------|--------|-----------|
| SM-001/2026 | 05/01/2026 | 03/01/2026 | Dekanat FMIPA IPB | Undangan Rapat Koordinasi | Ketua | ✅ Selesai | [Link] |

### Struktur Spreadsheet Agenda Surat Keluar

| No. Surat | Tgl. Terbit | Ditujukan Kepada | Perihal | Metode Kirim | Status | Link File |
|-----------|-------------|-----------------|---------|-------------|--------|-----------|
| 001/IEEE-SB-IPB/ADM/I/2026 | 10/01/2026 | Direktur PT. XYZ | Permohonan Sponsorship | Email | ✅ Terkirim | [Link] |

---

## 5.5 Hak Akses

| Level Akses | Pihak | Hak |
|-------------|-------|-----|
| **Editor** | Sekretaris, VP Administration | Tambah, edit, hapus file |
| **Commenter** | Ketua, Wakil Ketua | Lihat & beri komentar |
| **Viewer** | Anggota aktif IEEE SB IPB | Lihat saja |
| **No Access** | Pihak eksternal | Tidak dapat mengakses |

---

## 5.6 Retensi Dokumen

| Jenis Dokumen | Masa Simpan |
|---------------|-------------|
| Surat masuk umum | Minimum 3 tahun |
| Surat keluar resmi | Minimum 5 tahun |
| Surat perjanjian/MOU | Selama perjanjian aktif + 5 tahun |
| Laporan kegiatan | Permanen |

---

## 5.7 Backup

- Seluruh arsip di Google Drive otomatis ter-backup oleh Google
- Lakukan **backup manual** ke hard drive lokal setiap akhir semester
- Dokumentasi sistem (Markdown) di-backup di **GitHub repository** ini
