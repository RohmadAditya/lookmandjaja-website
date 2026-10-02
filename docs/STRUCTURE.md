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
