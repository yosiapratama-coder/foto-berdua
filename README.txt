DUA • LDR Photobooth (prototype)
===================================
Cara pakai:
1. Extract ZIP.
2. Buka index.html di Chrome/Edge. Kamera biasanya butuh localhost/HTTPS.
3. Login:
   Tio / 240626
   Yosia / 240626
4. Aktifkan kamera, ambil foto, pilih filter/layout/stiker/caption, klik Bikin kolase, lalu Simpan.
5. Room: akun pertama klik Buat room, bagikan kode ke pasangan. Pasangan login dan klik Gabung room lalu masukkan kode.

PENTING:
- Ini prototype frontend: kode room hanya disimpan lokal per browser dan belum menyambungkan kamera/foto secara live lintas perangkat.
- Untuk benar-benar publik dan room 2 perangkat real-time, deploy ke HTTPS dan tambahkan backend signaling/storage (misalnya Firebase Realtime Database + WebRTC). Jangan gunakan password sederhana ini untuk akun sensitif; ganti sebelum publik.
- Browser tidak mengizinkan kamera di halaman HTTP biasa kecuali localhost. Gunakan hosting HTTPS.
