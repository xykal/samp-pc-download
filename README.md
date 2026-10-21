# SAMP PC — Download APK

Engine Wine/Box64 (Winlator) + frontend SA-MP jadi **satu APK**.
Paket data tidak ikut di repo ini — app mengunduhnya sendiri dari link Drive
yang sudah **ditanam di dalam APK**, lalu mengekstrak RAR-nya **di HP**.

## Unduh

**[v1.4.0](../../releases/download/v1.4.0/samp-pc-v1.4.0-merged.apk)** — 501 MB (terbaru: UI sendiri, progress bar, anti force-close)
[v1.3.0](../../releases/download/v1.3.0/samp-pc-v1.3.0-merged.apk) — 501 MB (R8)
[v1.2.0](../../releases/download/v1.2.0/samp-pc-v1.2.0-merged-debug.apk) — 572 MB (debug, cadangan)

- **arm64-v8a** (satu-satunya ABI yang didukung engine), Android 9+ (minSdk 28), debug-signed
- Tanpa langkah PC, tanpa tempel link

## Cara pakai

1. Install APK.
2. Buka app → pilih penyimpanan (SD/internal) → pilih tier.
3. **Unduh paket** (680 MB, sekali saja) — progress bar muncul di dalam app, boleh ditinggal (service jalan sendiri).
4. **Jalankan SA-MP**.

## Isi rilis

| File | Ukuran | Keterangan |
|---|---|---|
| `samp-pc-v1.4.0-merged.apk` | 501 MB | install ini |
| `samp-pc-v1.3.0-merged.apk` | 501 MB | sebelumnya |
| `samp-pc-v1.2.0-merged-debug.apk` | 572 MB | cadangan (tanpa R8) |
| `samp-client.zip` | 24 MB | client SA-MP (diunduh otomatis oleh app) |

## Catatan

- Helio G36 / RAM 2–3 GB: main di 640×360 tier SAFETY, realistis 5–12 fps.
- Butuh ruang kosong ±3 GB saat instalasi (RAR sementara + hasil ekstrak).
- **Perangkat harus ARM64.** Emulator x86 (MEmu/BlueStacks/LDPlayer) tidak bisa menjalankan engine ini.
- v1.4.0: dialog & progress buatan sendiri (bukan UI bawaan Android), service download jalan di proses
  terpisah supaya crash ekstraksi tidak menutup app, dan crash terakhir bisa dilihat dari dalam app.

---
sha256 v1.4.0: `ae5053108b4add2c2763f91db5f09460ab2222cce142f55e0c825cd2d2a9c927`
