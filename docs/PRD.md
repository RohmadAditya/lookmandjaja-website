# PRD — Lookman Djaja Website

- **Nama proyek:** `lookmandjaja-website`
- **Versi dokumen:** 0.1
- **Tanggal:** 2 Oktober 2026
- **Status:** Draft untuk validasi bisnis dan persetujuan struktur
- **Pemilik produk:** PT Lookman Djaja Logistics
- **Jenis produk:** Website company profile dan lead generation untuk bisnis ekspedisi serta angkutan darat

## 1. Ringkasan Produk

Website baru Lookman Djaja berfungsi sebagai pusat informasi resmi perusahaan, katalog layanan dan armada, pintu masuk permintaan pengiriman, serta titik awal fitur pelacakan kiriman. Website harus memperbarui persepsi terhadap situs lama yang masih menampilkan footer tahun 2016, tanpa mengubah fakta bisnis menjadi klaim baru yang belum dikonfirmasi.

Website ditujukan untuk calon pelanggan bisnis yang membutuhkan pengiriman kargo melalui truk di koridor Sumatera, Jawa, Bali, dan rute lain yang tersedia. Konten harus mengutamakan kejelasan operasional: jenis muatan, pilihan layanan, kapasitas armada, area layanan, proses permintaan, dan kanal kontak.

## 2. Latar Belakang dan Masalah

### Masalah pengguna

- Informasi layanan dan armada belum disajikan dalam hierarchy yang modern dan mudah dipindai.
- Calon pelanggan perlu memahami perbedaan FTL, LTL, kargo, dan layanan armada khusus sebelum menghubungi perusahaan.
- Data kapasitas armada, lokasi kantor, dan proses pengiriman perlu disajikan tanpa mencampur data terverifikasi dan klaim yang belum dikonfirmasi.
- Fitur Shipment ID perlu memiliki jalur yang jelas, tetapi endpoint dan alur integrasinya belum terdokumentasi.

### Masalah bisnis

- Situs lama perlu diperbarui secara visual dan teknis.
- Perusahaan membutuhkan lebih banyak permintaan penawaran yang berkualitas.
- Aset resmi perusahaan sudah tersedia, tetapi hak publikasi ulang dan hak pengubahan masih perlu dikonfirmasi.
- Perbedaan alamat Jakarta dan angka jumlah armada harus diselesaikan sebelum dipublikasikan sebagai fakta utama.

## 3. Tujuan Produk

1. Meningkatkan kredibilitas digital PT Lookman Djaja Logistics sebagai operator ekspedisi dan angkutan darat.
2. Menjelaskan layanan dan armada secara cepat kepada calon pelanggan bisnis.
3. Mengarahkan pengunjung ke permintaan penawaran atau kontak kantor yang relevan.
4. Menyediakan entry point pelacakan berdasarkan Shipment ID tanpa menampilkan status palsu.
5. Membuat sistem konten yang mudah diperbarui oleh tim internal.
6. Menjaga seluruh klaim publik tetap bersumber, jelas status verifikasinya, dan tidak melebih-lebihkan kapasitas.

## 4. Bukan Tujuan MVP

- Membuat sistem TMS atau dashboard operasional internal.
- Membuat login pelanggan dan portal multi-akun.
- Menghitung tarif final secara otomatis.
- Menampilkan jumlah armada aktual sebelum angka resmi dikonfirmasi.
- Membuat aplikasi pengemudi; aplikasi LD Luar Kota hanya dicatat sebagai ekosistem digital terkait.
- Menyalin source code, layout, logo, atau copy dari situs lama maupun referensi pihak lain.

## 5. Target Pengguna

### Persona utama: Pengambil keputusan logistik

- Procurement, supply chain, warehouse, atau logistics manager.
- Membutuhkan kapasitas truk, rute, estimasi proses, dan kontak yang cepat.
- Mengutamakan reliabilitas, keamanan muatan, dan kepastian operasional.

### Persona kedua: Admin pengiriman

- Membutuhkan detail jenis layanan, lokasi kantor, nomor telepon, dan format permintaan yang jelas.
- Membutuhkan jalur tracking yang sederhana berdasarkan Shipment ID.

### Persona ketiga: Pemilik atau pengelola bisnis

- Membutuhkan gambaran singkat tentang sejarah, cakupan rute, layanan, dan cara meminta penawaran.

## 6. Fakta Bisnis dan Status Verifikasi

| Topik | Data yang digunakan | Status publikasi |
|---|---|---|
| Nama publik | Lookman Djaja | Siap digunakan |
| Entitas profesional | PT Lookman Djaja Logistics | Siap digunakan, cek legal copy sebelum launch |
| Bisnis | Ekspedisi dan angkutan darat berbasis truk | Siap digunakan |
| Berdiri | 1985 | Didukung riset dan publikasi industri; minta konfirmasi perusahaan sebelum hero/stat utama |
| Rute | Sumatera, Jawa, Bali | Siap digunakan berdasarkan situs perusahaan |
| Rute tambahan | NTB | Perlu konfirmasi sebelum ditampilkan sebagai cakupan utama |
| Teknologi | GPS dan Shipment ID | Tampilkan sebagai fitur hanya setelah endpoint dan scope operasional dikonfirmasi |
| Keamanan | Pengamanan khusus sesuai kebutuhan | Tampilkan sebagai opsi layanan, bukan jaminan universal |
| Armada resmi | Fuso, Tronton, Super Tronton, Big Mama | Siap digunakan dengan verifikasi spesifikasi akhir |
| Jumlah armada | Sekitar 250 atau lebih dari 300 | Jangan dipublikasikan; angka resmi terbaru belum terverifikasi |
| CEO | Kyatmaja Lookman | Jangan jadikan elemen utama MVP tanpa persetujuan nama dan foto |
| Surabaya | Jl. Raya Putat Gede Timur 3; 031-7340245; 031-7340246 | Perlu konfirmasi sebelum launch |
| Jakarta | Jl. Raya Karang Bolong 4, Ancol, Jakarta Utara; 021-69833201; 021-69833202 | Perlu konfirmasi sebelum launch |
| Kantor pusat alternatif | Gedung Buncit 36, Ragunan, Jakarta Selatan | Konflik sumber; jangan dipublikasikan sebelum dikonfirmasi |
| Tahun footer lama | 2016 | Anggap sebagai sinyal situs lama, jangan dibawa ke desain baru |

## 7. Nilai Produk dan Pesan Utama

### Pesan utama

**Solusi angkutan darat untuk menjaga pengiriman bisnis tetap berjalan.**

### Pilar pesan

1. **Pengalaman operasional:** berdiri sejak 1985, setelah dikonfirmasi oleh perusahaan.
2. **Pilihan kapasitas:** Fuso, Tronton, Super Tronton, dan Big Mama.
3. **Fleksibilitas muatan:** FTL, LTL, kargo, barang konsumen, serta layanan closed-box dan wingbox food-grade.
4. **Cakupan rute:** Sumatera, Jawa, Bali, dan rute tambahan sesuai ketersediaan operasional.
5. **Kontrol pengiriman:** GPS, Shipment ID, dan pengamanan khusus jika benar-benar tersedia untuk layanan yang dipilih.

### Gaya bahasa

- Bahasa Indonesia profesional, lugas, dan operasional.
- Tidak memakai jargon berlebihan atau klaim superlatif tanpa bukti.
- Hindari kalimat seperti "terbaik", "nomor satu", atau "paling besar" kecuali ada bukti resmi.
- Gunakan istilah teknis FTL, LTL, closed-box, wingbox, ritase, bongkar-muat, dan Shipment ID dengan penjelasan singkat.

## 8. Arsitektur Informasi dan Sitemap MVP

### Navigasi utama

1. Beranda
2. Profil
3. Layanan
4. Armada
5. Lacak Kiriman
6. Kontak

### Halaman dan tujuan

#### `/`

- Hero dengan value proposition dan CTA utama.
- Ringkasan layanan dan rute.
- Bukti pengalaman sejak 1985 setelah dikonfirmasi.
- Preview armada.
- Alur kerja singkat.
- CTA permintaan penawaran.

#### `/profil.html`

- Sejarah dan profil perusahaan.
- Wilayah operasi.
- Prinsip operasional dan keamanan muatan.
- Teknologi pendukung jika terverifikasi.
- Foto profil resmi.

#### `/layanan.html`

- FTL atau charter satu truk.
- LTL atau penggabungan muatan.
- Pengiriman kargo dan barang konsumen.
- Closed-box dan wingbox food-grade.
- Penjelasan tarif ritase/perjalanan sebagai informasi umum, bukan kalkulator harga final.
- CTA konsultasi kebutuhan.

#### `/armada.html`

- Katalog Fuso, Tronton, Super Tronton, dan Big Mama.
- Volume, kapasitas tonase, tipe box, dan penggunaan yang disarankan.
- Foto armada resmi.
- Disclaimer bahwa ketersediaan aktual perlu dikonfirmasi.

#### `/tracking.html`

- Input Shipment ID.
- Validasi format dasar di sisi klien.
- State loading, berhasil, tidak ditemukan, dan service unavailable.
- Integrasi endpoint tracking hanya setelah API contract diberikan.
- Jangan menampilkan status dummy sebagai data produksi.

#### `/kontak.html`

- Kantor Surabaya dan Jakarta setelah alamat dikonfirmasi.
- Nomor telepon resmi.
- Form permintaan penawaran.
- Peta hanya setelah alamat final ditentukan.
- CTA telepon dan email; WhatsApp hanya jika nomor bisnis resmi diberikan.

## 9. Struktur Beranda yang Diusulkan

1. **Header:** logo Lookman Djaja, navigasi utama, CTA "Minta Penawaran".
2. **Hero:** pesan utama, subcopy singkat, CTA "Konsultasikan Pengiriman" dan "Lacak Kiriman"; gunakan foto profil/truk resmi setelah hak publikasi dikonfirmasi.
3. **Trust strip:** berdiri sejak 1985, koridor Sumatera-Jawa-Bali, pilihan tipe armada, Shipment ID jika aktif.
4. **Masalah yang diselesaikan:** pengiriman rutin, muatan gabungan, barang konsumen, muatan besar.
5. **Layanan utama:** FTL, LTL, kargo, closed-box/wingbox.
6. **Preview armada:** 4 kartu armada dengan kapasitas utama.
7. **Cara kerja:** konsultasi, penyesuaian armada, ritase dan jadwal, pengiriman, monitoring.
8. **Tracking entry point:** form Shipment ID.
9. **CTA penutup:** minta penawaran atau hubungi kantor.
10. **Footer:** alamat yang sudah dikonfirmasi, telepon, email resmi, kebijakan, tahun dinamis.

## 10. Spesifikasi Armada

| Tipe | Volume | Kapasitas | Karoseri | Catatan penggunaan |
|---|---:|---:|---|---|
| Fuso | 25 m3 | 6 ton | Closed-box | Pengiriman umum dengan kapasitas menengah |
| Tronton | 35 m3 | 12 ton | Closed-box | Muatan lebih besar dan pengiriman rutin |
| Super Tronton | 50 m3 | 15 ton | Wingbox | Muatan besar dengan kebutuhan akses bongkar-muat |
| Big Mama | 75 m3 | 32 ton | Wingbox | Muatan volume/berat besar, wajib konfirmasi operasional |

Semua angka spesifikasi wajib diberi sumber internal atau approval perusahaan sebelum launch. Jangan menyimpulkan dimensi panjang, tinggi, atau detail teknis yang tidak ada dalam dossier.

## 11. Persyaratan Fungsional

### FR-01 — Navigasi

- Header responsif desktop, tablet, dan mobile.
- Navigasi memiliki enam item utama.
- CTA penawaran terlihat di header desktop dan menu mobile.

### FR-02 — Permintaan penawaran

- Form minimal: nama, perusahaan, email/telepon, asal, tujuan, jenis muatan, volume/berat, jadwal, dan pesan.
- Validasi field wajib.
- Channel submit harus dikonfirmasi: email, CRM, WhatsApp, atau endpoint backend.
- Jangan mengklaim form tersambung sebelum ada endpoint nyata.

### FR-03 — Tracking

- Pengunjung dapat memasukkan Shipment ID.
- UI menyediakan state kosong, loading, hasil, tidak ditemukan, dan error.
- Endpoint, autentikasi, rate limit, dan format respons menjadi dependency eksternal.

### FR-04 — Katalog armada

- Setiap tipe memiliki foto, kapasitas, volume, tipe box, dan CTA.
- Status ketersediaan tidak boleh dikarang.

### FR-05 — Kontak dan lokasi

- Menampilkan hanya alamat dan nomor yang sudah disetujui.
- Peta memakai alamat final, bukan hasil asumsi dari sumber yang konflik.

### FR-06 — Konten dan aset

- Logo dan foto resmi dipakai hanya setelah izin publikasi dikonfirmasi.
- Alt text wajib tersedia.
- Setiap gambar memiliki width dan height untuk mencegah layout shift.

## 12. Persyaratan Nonfungsional

- Responsif pada 375px, 768px, 1024px, dan 1280px ke atas.
- Performa: gambar dikompresi, format modern dipertimbangkan setelah hak aset aman, lazy loading di bawah fold.
- Aksesibilitas: semantic HTML, label form, fokus keyboard, kontras memadai, alt text.
- SEO: title unik, meta description, canonical, Open Graph, sitemap, robots, schema Organization/LocalBusiness setelah data alamat final.
- Keamanan: tidak menaruh API key di frontend; tracking API memakai proxy/backend jika memerlukan secret.
- Privasi: jelaskan data form, tujuan penggunaan, retensi, dan kontak privacy jika form produksi digunakan.
- Maintainability: CSS token, komponen bersama, konten bisnis mudah diganti.

## 13. Design Direction

### Arah visual

- Industrial, terpercaya, modern, dan tidak terasa seperti template generik.
- Gunakan wordmark resmi sebagai sumber identitas utama.
- Palet awal mengikuti logo: biru tua/royal blue, abu-abu, putih, dan warna netral industri.
- Gunakan aksen seperlunya; jangan mengubah simbol atau proporsi logo.
- Foto resmi digunakan sebagai anchor visual untuk hero, profil, layanan, dan armada.
- Hindari membuat ulang logo dalam CSS atau menggabungkan logo dengan efek yang mengubah identitas.

### Komponen utama

- Header sticky.
- Hero dengan overlay yang menjaga keterbacaan.
- Kartu layanan dan armada.
- Tracking panel.
- Contact/inquiry panel.
- CTA penutup konsisten.
- Footer multi-kolom yang ringkas.

## 14. Aset Resmi yang Tersedia

Arsip aset disimpan di `assets/official/` dan berasal dari situs resmi perusahaan. Inventaris rinci ada di `docs/ASSET-INVENTORY.md`.

- `lookman-logo.png` — wordmark resmi.
- `badak-logo.png` — logo pendamping resmi.
- `profile-01.jpg` sampai `profile-03.jpg` — foto profil/brand.
- `service-01.jpg` sampai `service-02.jpg` — foto layanan operasional.
- `truck-01.jpg` sampai `truck-04.jpg` — foto katalog armada.

**Gate hak aset:** arsip menyebut penggunaan untuk riset/internal dan hak publikasi ulang, komersial, atau pengubahan belum diverifikasi. Website produksi tidak boleh dipublikasikan sebelum izin pemegang hak dikonfirmasi.

## 15. Dependency dan Pertanyaan Terbuka

1. Apakah perusahaan menyetujui penggunaan 11 aset resmi ini untuk website baru?
2. Alamat final kantor Jakarta yang benar yang mana: Ancol atau Gedung Buncit 36?
3. Apakah alamat Surabaya dan seluruh nomor telepon masih aktif?
4. Berapa jumlah armada terbaru yang boleh dipublikasikan?
5. Apakah rute NTB aktif dan boleh disebutkan sebagai cakupan resmi?
6. Apa endpoint dan format API Shipment ID?
7. Apakah tracking publik membutuhkan autentikasi, captcha, atau rate limit?
8. Ke mana form permintaan penawaran dikirim?
9. Email bisnis resmi yang harus ditampilkan apa?
10. Apakah WhatsApp bisnis resmi tersedia?
11. Apakah nama dan foto Kyatmaja Lookman boleh ditampilkan?
12. Apakah ada dokumen resmi tentang SOP keselamatan, GPS, food-grade, atau pengamanan khusus?
13. Apakah website membutuhkan dua bahasa?
14. Domain, hosting, analytics, dan akses deployment yang akan digunakan apa?

## 16. Acceptance Criteria MVP

- [ ] Enam halaman utama tersedia dan memiliki navigasi konsisten.
- [ ] Setiap halaman memiliki satu H1, title unik, meta description, dan CTA.
- [ ] Semua fakta yang belum dikonfirmasi ditandai di konten internal dan tidak muncul sebagai klaim final.
- [ ] Katalog empat tipe armada menampilkan data volume, tonase, dan tipe box yang disetujui.
- [ ] Tracking UI memiliki seluruh state tanpa data palsu.
- [ ] Form inquiry memiliki validasi dan channel submit yang benar-benar dikonfigurasi.
- [ ] Alamat, telepon, email, dan peta sudah disetujui perusahaan.
- [ ] Aset resmi memiliki izin penggunaan tertulis.
- [ ] QA responsif lulus pada 375, 768, 1024, dan 1280 piksel.
- [ ] Tidak ada broken link, gambar gagal, overflow horizontal, atau error console.
- [ ] Lighthouse/measurement baseline dicatat sebelum launch.
- [ ] Git repository bersih dan commit milestone tersedia.

## 17. KPI Pasca-Launch

- Conversion rate klik CTA penawaran.
- Jumlah form inquiry valid per bulan.
- Jumlah klik telepon/email/WhatsApp.
- Penggunaan tracking entry point dan rasio Shipment ID valid.
- Bounce rate halaman layanan dan armada.
- LCP, CLS, dan INP pada perangkat mobile.
- Persentase traffic organik ke halaman layanan dan armada.

## 18. Rencana Milestone

### Milestone 0 — Validasi bisnis

Konfirmasi aset, alamat, nomor telepon, email, jumlah armada, rute, izin penggunaan, dan tracking API.

### Milestone 1 — Fondasi dan design system

Buat struktur proyek, token warna/typography, layout responsif, header, footer, CTA, dan komponen form.

### Milestone 2 — Halaman konten

Bangun Beranda, Profil, Layanan, Armada, Tracking, dan Kontak dengan konten yang sudah disetujui.

### Milestone 3 — Integrasi

Hubungkan tracking dan form inquiry setelah endpoint serta channel submit tersedia.

### Milestone 4 — QA dan launch readiness

Uji responsive, aksesibilitas, SEO, performa, link, asset loading, console, dan approval final stakeholder.

## 19. Sumber Dasar Dossier

- Situs resmi Lookman Djaja: profil, armada, kontak, dan halaman utama.
- Riset Poltrada Bali tentang Lookman Djaja.
- Direktori bisnis Indonetwork untuk informasi layanan dan skala armada.
- Profil profesional Kyatmaja Lookman.
- Arsip aset resmi yang dikirimkan untuk proyek ini.

Sumber eksternal dipakai untuk riset dan harus diverifikasi ulang oleh pihak perusahaan sebelum menjadi klaim publik final.
