# Personal Branding Masterclass Landing Page

Landing page responsive untuk Rumah IT Indonesia / rumahit.event.

## Struktur
- `index.html` — seluruh konten dan section
- `style.css` — desain responsive desktop/mobile
- `script.js` — CTA dan FAQ
- `assets/rizqiani-speaking.jpg` — foto Rizqiani, dipakai di section "Apa Yang Akan Anda Bawa Pulang?" (benefit peserta)
- `assets/rizqiani-event.jpg` — foto Rizqiani, dipakai di section "Public Speaking" (Knowledge–Communication–Confidence–Perception–Personal Brand)
- `assets/poster.jpg` — poster acara, dipakai di section 2 "Kenapa Ini Penting?"

## Publikasi ke GitHub Pages
1. Buat repository baru, misalnya `PublicSpeaking`.
2. Upload isi folder ini ke branch `main`.
3. GitHub → Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
4. Simpan.

## Pendaftaran via WhatsApp
Tombol "DAFTAR SEKARANG" langsung membuka chat WhatsApp ke nomor **+62 878-2776-0477** dengan pesan otomatis:
> "Saya mau mendaftar acara webinar bersama Kak Rizqiani Putri, mohon bantuannya"

Untuk mengubah nomor atau pesan, edit `REGISTRATION_URL` di `script.js` (dan href tombol di `index.html` sebagai fallback non-JS).

CTA utama hanya satu dan berada di section paling bawah.
