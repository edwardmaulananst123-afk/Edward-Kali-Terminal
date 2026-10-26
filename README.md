# Edward Kali Terminal

Aplikasi terminal **Kali Linux untuk Android**. Jalankan Kali langsung di HP tanpa komputer.

## Fitur
- Mode **Root** (chroot) dan **Tidak Root** (proot)
- Install tool Kali dengan sekali pilih
- Desktop **XFCE + VNC**
- **Backup dan restore** Kali
- Terminal dengan tombol ESC, TAB, CTRL, ALT, dan panah

## Unduh
Buka tab **Releases** di repo ini, lalu unduh file `.apk` terbaru.

## Syarat
- Android 7.0 ke atas
- HP **arm64** (kebanyakan HP sekarang)
- Ruang kosong sekitar 2 GB atau lebih dan koneksi internet untuk install pertama

## Kenapa app ini meminta izin?
| Izin | Dipakai untuk |
|---|---|
| Internet | Mengunduh Kali dan menjalankan `apt` |
| Penyimpanan | Menautkan folder HP ke Kali (`~/storage`) dan menyimpan backup |
| Notifikasi dan layanan latar | Menjaga sesi terminal tetap hidup |
| Wake lock dan abaikan optimasi baterai | Supaya proses tidak dimatikan sistem saat layar mati |

App ini **tidak meminta** akses kontak, SMS, kamera, mikrofon, atau lokasi.

## Keamanan
- Saat install, app mengunduh rootfs Kali dari server resmi: `kali.download`.
- Tidak ada iklan dan tidak perlu membuat akun.
- Mode Root hanya berjalan kalau HP Anda sudah di-root dan Anda memberi izin sendiri. Tanpa root, app berjalan di mode proot.
- Source code tidak dipublikasikan. Kalau ragu, Anda bisa memindai APK di [VirusTotal](https://www.virustotal.com) sebelum install.

## Cara install
1. Unduh APK dari **Releases**.
2. Buka file APK. Kalau diminta, aktifkan **Izinkan install dari sumber ini**.
3. Buka app, pilih **Install Kali**, lalu tunggu sampai selesai.

## Catatan
- Peringatan "aplikasi tidak dikenal" dari Android muncul karena APK ini tidak dari Play Store. Itu normal untuk APK di luar Play Store.
- Gunakan hanya di perangkat dan jaringan milik sendiri atau yang Anda punya izin untuk mengujinya.

## Masalah atau saran
Buka tab **Issues** di repo ini.