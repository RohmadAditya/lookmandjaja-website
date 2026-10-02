# Frontend Structure

## Routes

- `/index.html` — Beranda
- `/profil.html` — Profil
- `/layanan.html` — Layanan
- `/armada.html` — Armada
- `/tracking.html` — Lacak Kiriman
- `/kontak.html` — Kontak

## Shared system

- `css/site.css` — design tokens, layout, components, responsive styles
- `js/site.js` — mobile navigation dan submit inquiry ke WhatsApp
- `assets/official/` — logo dan foto resmi

## WhatsApp form

Submit form kontak diarahkan ke `https://wa.me/6281213283987` dengan seluruh value field dirangkum sebagai pesan. Nomor dapat diganti dari satu lokasi di `js/site.js`.


## Contact page benchmark

Halaman Kontak menjadi benchmark visual untuk refinemen halaman lain: hero ringkas dengan satu pesan, palet biru-abu, kartu informasi terang, layout utilitas yang jelas, CTA foto HD, dan motion entry yang halus. Halaman lain akan mengikuti prinsip ini pada iterasi visual berikutnya tanpa menyalin struktur secara mekanis.
