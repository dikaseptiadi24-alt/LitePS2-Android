# LitePS2 Android

Proyek emulator PlayStation 2 untuk Android, dengan target pengujian awal pada Realme C53 (ARM64).

## Status
Repositori ini berisi workflow untuk membangun APK debug dari source open-source Ametrine dan core ARMSX2. APK belum diuji pada Realme C53 dan performa tiap game berbeda; tidak ada jaminan semua game berjalan lancar.

## Membuat APK
1. Buka tab **Actions**.
2. Pilih **Build LitePS2 APK**.
3. Tekan **Run workflow**.
4. Setelah workflow selesai, unduh artifact APK pada halaman hasil workflow.

## Penggunaan
- Android 10 atau lebih baru, ARM64.
- Tambahkan BIOS hasil dump dari konsol PS2 milik sendiri.
- Pilih folder berisi game yang dimiliki sendiri.
- Mulai dengan resolusi internal 1x dan pengaturan grafis rendah jika tersedia.

BIOS dan game tidak disertakan. Gunakan hanya salinan yang kamu miliki haknya.

## Sumber dan lisensi
Menggunakan source [Ametrine](https://github.com/kiraponz/Ametrine) dan core [ARMSX2](https://github.com/kiraponz/ARMSX2), berbasis PCSX2. Periksa lisensi GPL-3.0-or-later dan sertakan source serta pemberitahuan lisensi yang diwajibkan sebelum mendistribusikan APK.

LitePS2 adalah proyek tidak resmi dan tidak berafiliasi dengan Sony.
