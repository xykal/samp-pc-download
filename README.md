# XversSamp — Download APK

Engine Wine/Box64 (Winlator) + frontend SA-MP jadi **satu APK**.
Paket data tidak ikut di repo ini — app mengunduhnya sendiri dari link Drive
yang sudah **ditanam di dalam APK**, lalu mengekstrak RAR-nya **di HP**.

## Unduh

**[v1.6.0 — XversSamp](../../releases/download/v1.6.0/xverssamp-v1.6.0-merged.apk)** — 501 MB (terbaru)
[v1.5.0](../../releases/download/v1.5.0/xverssamp-v1.5.0-merged.apk) — 501 MB
[v1.4.0](../../releases/download/v1.4.0/samp-pc-v1.4.0-merged.apk) — 501 MB

- **arm64-v8a** (satu-satunya ABI yang didukung engine), Android 9+ (minSdk 28), debug-signed
- Tanpa langkah PC, tanpa tempel link

## Cara pakai

1. Install APK.
2. Buka **XversSamp** → pilih penyimpanan (SD/internal) → pilih tier.
3. **Unduh paket** (712 MB, sekali saja) — progress bar ada di dalam app, boleh ditinggal.
   Kalau koneksi putus, app lanjut sendiri (resume, sampai 6x percobaan).
4. **Jalankan SA-MP**.

## Kalau unduhan gagal

Buka **Diagnostik (kalau gagal)** di app:

- lihat baris `TES KE SERVER` — HTTP code, tipe, ukuran, waktu;
- tekan **Salin** lalu kirim isinya (berisi versi app, ABI, HP, ruang bebas, URL, log terakhir).

Kalau pesannya soal kuota Drive, pakai **Ganti link paket** dan tempel link salinanmu sendiri.

## Isi rilis

| File | Ukuran | Keterangan |
|---|---|---|
| `xverssamp-v1.6.0-merged.apk` | 501 MB | install ini |
| `xverssamp-v1.5.0-merged.apk` | 501 MB | sebelumnya |
| `samp-client.zip` | 24 MB | client SA-MP (diunduh otomatis oleh app) |

## Catatan

- Helio G36 / RAM 2–3 GB: main di 640×360 tier SAFETY, realistis 5–12 fps.
- Butuh ruang kosong ±3 GB saat instalasi (RAR sementara + hasil ekstrak).
- **ARM64** diperlukan untuk menjalankan engine (emulator x86 butuh ARM translation, hasil tidak dijamin).
- armeabi-v7a (32-bit) butuh engine terpisah (Wine 32-bit + Box86) — belum dikerjakan.

---
sha256 v1.6.0: `65945de3c27f62f17b2119f69369bacbd4f920ce5a709d68f64e93388a79eee2`
