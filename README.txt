TRADING ANALYZER PRO V1.1 — FOREX + XAUUSD + CRYPTO

Isi:
- index.html: aplikasi chart responsif, indikator teknikal, kalkulasi entry/SL/TP.
- manifest.webmanifest dan sw.js: dukungan instalasi PWA.

DATA LIVE:
1) Crypto: Binance public REST + WebSocket untuk pasangan spot yang tersedia.
2) Forex dan XAUUSD: Twelve Data REST time_series; masukkan API key sendiri pada aplikasi. Data diperbarui berkala (polling 15 detik). Streaming intraday/real-time dan jumlah request bergantung paket/kuota Twelve Data.
   Simbol gold: XAU/USD. Pasangan forex menggunakan format EUR/USD, GBP/USD, dll.

CARA PAKAI ANDROID:
1. Ekstrak ZIP.
2. Hosting folder ini pada HTTPS (contoh GitHub Pages atau hosting pribadi).
3. Buka URL di Chrome Android.
4. Menu ⋮ > Install app / Tambahkan ke layar utama.

CATATAN:
- Ini PWA/source project, bukan APK native hasil kompilasi.
- API key dimasukkan sendiri di halaman; jangan bagikan perangkat/halaman yang berisi key. Untuk aplikasi publik sebaiknya pindahkan pemanggilan API ke backend proxy agar key tidak terekspos.
- Pastikan paket Twelve Data Anda memberi akses simbol dan interval yang dipilih. Harga bisa tertunda/terbatas sesuai paket dan lisensi.
- Entry/SL/TP adalah estimasi ATR/indikator, bukan jaminan profit. Uji akun demo; spread, slippage, contract size dan digit broker berbeda.
