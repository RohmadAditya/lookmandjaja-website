# Lookman Djaja Website

PRD dan fondasi proyek redesign website company profile untuk PT Lookman Djaja Logistics.

## Status

- Fase: frontend multipage prototype
- Dokumen utama: `docs/PRD.md`
- Inventaris aset: `docs/ASSET-INVENTORY.md`
- Homepage dan multipage frontend prototype sudah tersedia
- Tracking API masih ditunda; form inquiry mengarah ke WhatsApp dengan value form

## Struktur saat ini

```text
lookmandjaja-website/
├── assets/
│   └── official/          # logo dan foto resmi dari arsip aset
├── docs/
│   ├── PRD.md
│   └── ASSET-INVENTORY.md
└── README.md
```

## Rencana halaman MVP

- Beranda
- Profil
- Layanan
- Armada
- Lacak Kiriman
- Kontak

## Catatan penting

Aset resmi diarsipkan untuk riset/internal. Jangan mempublikasikan aset sebelum hak penggunaan tertulis dikonfirmasi. Jangan menampilkan angka armada, alamat Jakarta, nomor kontak, rute NTB, atau status tracking sebagai fakta final sebelum approval bisnis.

## Menjalankan tahap berikutnya

Setelah PRD disetujui dan data terbuka dikonfirmasi, tahap berikutnya adalah membuat design system, struktur HTML/CSS/JS, lalu membangun halaman MVP secara bertahap.


## Preview lokal

```bash
python3 -m http.server 8021
```

Halaman: `index.html`, `profil.html`, `layanan.html`, `armada.html`, `tracking.html`, `kontak.html`.
