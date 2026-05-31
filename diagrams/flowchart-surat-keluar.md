# Diagram Alur — Surat Keluar

## Flowchart Penerbitan Surat Keluar IEEE Student Branch IPB

```mermaid
flowchart TD
    A([📝 Permintaan Surat\ndari Divisi]) --> B[Divisi Mengisi Form\nPermintaan Surat]

    B --> C[Sekretaris Menyusun\nDraft Surat]

    C --> D[Kirim Draft ke\nVP Administration & Ketua\nuntuk Review]

    D --> E{Review\nDisetujui?}

    E -->|Perlu Revisi| F[Sekretaris Merevisi\nDraft Surat]
    F --> D

    E -->|Disetujui| G[Penomoran Surat Resmi\nNNN/IEEE-SB-IPB/DIV/BLN/THN]

    G --> H[Catat di Agenda\nSurat Keluar]

    H --> I{Metode\nPengiriman?}

    I -->|Fisik| J[Cetak Surat\n& Siapkan Amplop]
    I -->|Digital| K[Ekspor ke PDF Final]

    J --> L[Penandatanganan\noleh Ketua]
    K --> L

    L --> M{Metode Kirim}

    M -->|Fisik| N[Kirim via Ekspedisi /\nSerahkan Langsung]
    M -->|Email| O[Kirim dari Email Resmi\nIEEE SB IPB]
    M -->|Platform Digital| P[Kirim via Kanal Resmi]

    N --> Q[Simpan Bukti Terima /\nTanda Terima]
    O --> Q
    P --> Q

    Q --> R[Update Status di\nAgenda Surat Keluar\nStatus: Terkirim]

    R --> S[(📁 Simpan Salinan di Google Drive\nArsip/Tahun/Surat Keluar/Bulan/)]

    S --> T([✅ Selesai])

    style A fill:#2196F3,color:#fff
    style T fill:#4CAF50,color:#fff
    style E fill:#FF9800,color:#fff
    style M fill:#FF9800,color:#fff
    style S fill:#9C27B0,color:#fff
```

---

## Format Penomoran Surat Keluar

```
[NomorUrut] / IEEE-SB-IPB / [KodeDivisi] / [BulanRomawi] / [Tahun]

Contoh:
001 / IEEE-SB-IPB / ADM / I / 2026
002 / IEEE-SB-IPB / EXT / III / 2026
```

### Kode Divisi

| Kode | Divisi |
|------|--------|
| `ADM` | Administration |
| `EXT` | External Relations |
| `INT` | Internal Affairs |
| `FIN` | Finance |
| `TEC` | Technical |

---

## Waktu Proses Target

| Tahapan | Target Waktu |
|---------|-------------|
| Penyusunan draft | ≤ 2 hari kerja |
| Proses review & revisi | ≤ 1 hari kerja |
| Penandatanganan | ≤ 1 hari kerja |
| Pengiriman & pengarsipan | ≤ 1 hari kerja |
| **Total** | **≤ 5 hari kerja** |
