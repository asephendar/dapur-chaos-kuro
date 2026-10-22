# Dapur Chaos Kuro

Game co-op masak chaos untuk 1–3 pemain, terinspirasi Overcooked! 2 — semua nama, karakter, dan visual orisinal (digambar pakai kode HTML/CSS/Canvas, bukan aset AI). Dibangun sebagai artifact web (satu file HTML mandiri).

## Main sekarang

**https://asephendar.github.io/dapur-chaos-kuro/**

Di HP wajib landscape — putar HP bila diminta.

## Mode

- **Solo** — dapur kompak sendiri (lebih kecil/simple): 1 koki aktif bergaya Kuro Adventure, partner membeku, ganti kendali kapan saja (Tab/C di keyboard, tombol GANTI KOKI di HP).
- **Multiplayer online (maks 3 pemain)** — dapur besar, host-authoritative via PeerJS (WebRTC): host Raka (merah), tamu Gora (biru) & Mika (hijau). Satu orang BUAT ROOM, teman GABUNG ROOM pakai kode 5 karakter. Tampilan & alur layar mengikuti Kuro Adventure (BUAT ROOM / GABUNG ROOM / KEMBALI → layar room & form terpisah).

## Cara main

Ambil bahan dari krat → cincang di talenan → masak patty di kompor (jangan sampai gosong) → rakit di piring sesuai tiket → antar ke meja saji sebelum tiket hangus. Piring kotor kembali ke wastafel untuk dicuci. Tiket selesai memberi koin + tip; tiket hangus −30. Level 150 detik, bintang 1–3 dari total koin (300/550/800). Ada DASH dan JEDA (P/Esc atau tombol ❚❚).

## Kontrol

- **Keyboard:** WASD/panah (Raka), E interaksi, Shift dash; solo: Tab/C ganti koki; P/Esc jeda.
- **HP/tablet (otomatis):** joystick virtual + tombol AMBIL/TARUH, DASH, GANTI KOKI (solo), dan jeda — muncul sendiri di perangkat sentuh.

## Teknologi

Satu file `index.html` (HTML/CSS/JS + Canvas), audio prosedural WebAudio, multiplayer WebRTC via PeerJS Cloud (gratis, tanpa server sendiri). Deploy: GitHub Pages dari branch `main` (push = auto-deploy). Font pixel "Press Start 2P" + PeerJS termuat dari CDN (butuh internet).

Sumber kebenaran: artifact web `dapur-chaos-kuro` di Muse (file ini hasil ekspornya).
