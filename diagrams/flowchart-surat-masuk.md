# Diagram Alur — Surat Masuk

## Flowchart Penanganan Surat Masuk IEEE Student Branch IPB

```mermaid
flowchart TD
    A([📨 Surat Diterima]) --> B{Jenis Surat?}

    B -->|Fisik| C[Periksa Keutuhan Surat]
    B -->|Digital/Email| D[Unduh & Simpan Sementara]

    C --> E[Scan / Digitalisasi Surat]
    D --> E

    E --> F[Catat di Agenda Surat Masuk\nFormat: SM-NNN/YYYY]

    F --> G[Beri Nama File\nSM-NomorAgenda-Perihal.pdf]

    G --> H[Sampaikan ke Ketua\nuntuk Disposisi]

    H --> I{Disposisi\noleh Ketua}

    I -->|Perlu Tindak Lanjut| J[Distribusikan ke\nDivisi Terkait]
    I -->|Untuk Diketahui Saja| K[Arsipkan Langsung]

    J --> L[Konfirmasi Penerimaan\noleh Divisi]

    L --> M[Divisi Menindaklanjuti Surat]

    M --> N{Selesai?}

    N -->|Belum| O[Sekretaris Mengingatkan\nDivisi Terkait]
    O --> M

    N -->|Selesai| P[Update Status di\nAgenda Surat Masuk]

    P --> Q[(📁 Simpan di Google Drive\nArsip/Tahun/Surat Masuk/Bulan/)]
    K --> Q

    Q --> R([✅ Selesai])

    style A fill:#2196F3,color:#fff
    style R fill:#4CAF50,color:#fff
    style I fill:#FF9800,color:#fff
    style N fill:#FF9800,color:#fff
    style Q fill:#9C27B0,color:#fff
```

---

## Keterangan Simbol

| Simbol | Keterangan |
|--------|-----------|
| ⬭ (Oval) | Titik awal / akhir proses |
| ▭ (Persegi panjang) | Aktivitas / langkah |
| ◇ (Berlian) | Keputusan / kondisi |
| ⬠ (Silinder) | Penyimpanan data |

---

## Waktu Proses Target

| Tahapan | Target Waktu |
|---------|-------------|
| Pencatatan & digitalisasi | ≤ 1 hari kerja |
| Disposisi oleh Ketua | ≤ 2 hari kerja |
| Distribusi ke divisi | ≤ 1 hari kerja setelah disposisi |
| Pengarsipan final | Segera setelah selesai |
