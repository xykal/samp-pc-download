# XversSamp — Download APK

Engine Wine/Box64 (Winlator) + frontend SA-MP jadi **satu APK**.
Paket data tidak ikut di repo ini — app mengunduhnya sendiri dari link Drive
yang sudah **ditanam di dalam APK**, lalu mengekstrak RAR-nya **di HP**.

## Unduh

**[v1.5.0 — XversSamp](../../releases/download/v1.5.0/xverssamp-v1.5.0-merged.apk)** — 501 MB (terbaru: nama + ikon baru)
[v1.4.0](../../releases/download/v1.4.0/samp-pc-v1.4.0-merged.apk) — 501 MB (UI sendiri, progress bar, anti force-close)
[v1.3.0](../../releases/download/v1.3.0/samp-pc-v1.3.0-merged.apk) — 501 MB (R8)

- **arm64-v8a** (satu-satunya ABI yang didukung engine), Android 9+ (minSdk 28), debug-signed
- Tanpa langkah PC, tanpa tempel link

## Cara pakai

1. Install APK.
2. Buka **XversSamp** → pilih penyimpanan (SD/internal) → pilih tier.
3. **Unduh paket** (680 MB, sekali saja) — progress bar ada di dalam app, boleh ditinggal.
4. **Jalankan SA-MP**.

## Isi rilis

| File | Ukuran | Keterangan |
|---|---|---|
| `xverssamp-v1.5.0-merged.apk` | 501 MB | install ini |
| `samp-pc-v1.4.0-merged.apk` | 501 MB | sebelumnya |
| `samp-pc-v1.3.0-merged.apk` | 501 MB | R8 |
| `samp-client.zip` | 24 MB | client SA-MP (diunduh otomatis oleh app) |

## Catatan

- Helio G36 / RAM 2–3 GB: main di 640×360 tier SAFETY, realistis 5–12 fps.
- Butuh ruang kosong ±3 GB saat instalasi (RAR sementara + hasil ekstrak).
- **Perangkat harus ARM64** untuk menjalankan engine. Di emulator x86 (MEmu dsb.) APK bisa ke-install
  kalau image-nya punya ARM translation, tapi performa/kompatibilitas engine tidak dijamin.
- armeabi-v7a (32-bit) butuh engine terpisah (Wine 32-bit + Box86) — belum dikerjakan.

---
sha256 v1.5.0: `255aea2bb9d7a5de58a9413ed326dff696ba11d82c8696c9ac545a1007d7dbec`
