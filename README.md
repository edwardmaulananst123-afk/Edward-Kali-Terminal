# Edward Kali Terminal

[Bahasa Indonesia](#bahasa-indonesia) · [English](#english)

---

## Bahasa Indonesia

Aplikasi terminal **Kali Linux untuk Android**. Jalankan Kali langsung di HP tanpa komputer.

### Tentang app ini
Edward Kali Terminal memasang sistem **Kali Linux (versi minimal, arm64)** di dalam HP Android Anda, lalu membuka terminal untuk memakainya. Anda mendapat lingkungan Linux lengkap dengan `apt`, `sudo`, bash/zsh, dan bisa memasang tool Kali sesuai kebutuhan.

**Cara kerjanya:**
- Saat pertama dibuka, app mengunduh rootfs Kali dari server resmi (`kali.download`), lalu mengekstraknya ke penyimpanan internal app.
- **Mode Root (chroot):** dipakai kalau HP Anda sudah di-root dan Anda mengizinkannya. Hasilnya paling cepat dan paling lengkap.
- **Mode Tidak Root (proot):** untuk HP tanpa root. Semua berjalan di dalam app, tanpa mengubah sistem Android.
- Mode dipilih otomatis, dan bisa diganti manual dari menu app.

**Cocok untuk:**
- Belajar Linux dan command line di HP
- Menjalankan tool Kali dan program Linux lain
- Menjalankan desktop XFCE lewat VNC
- Latihan keamanan jaringan di perangkat atau jaringan milik sendiri

### Fitur
- Mode **Root** (chroot) dan **Tidak Root** (proot)
- Mendukung `sudo` dan `apt install`
- Install tool Kali dengan sekali pilih
- Desktop **XFCE + VNC**
- **Backup dan restore** Kali
- Terminal dengan tombol ESC, TAB, CTRL, ALT, dan panah
- Akses file HP lewat `~/storage`

### Unduh
Buka tab **Releases** di repo ini, lalu unduh file `.apk` terbaru.

### Syarat
- Android 7.0 ke atas
- HP **arm64** (kebanyakan HP sekarang)
- Ruang kosong sekitar 2 GB atau lebih dan koneksi internet untuk install pertama

### Kenapa app ini meminta izin?
| Izin | Dipakai untuk |
|---|---|
| Internet | Mengunduh Kali dan menjalankan `apt` |
| Penyimpanan | Menautkan folder HP ke Kali (`~/storage`) dan menyimpan backup |
| Notifikasi dan layanan latar | Menjaga sesi terminal tetap hidup |
| Wake lock dan abaikan optimasi baterai | Supaya proses tidak dimatikan sistem saat layar mati |

App ini **tidak meminta** akses kontak, SMS, kamera, mikrofon, atau lokasi.

### Keamanan
- Saat install, app mengunduh rootfs Kali dari server resmi: `kali.download`.
- Tidak ada iklan dan tidak perlu membuat akun.
- Mode Root hanya berjalan kalau HP Anda sudah di-root dan Anda memberi izin sendiri. Tanpa root, app berjalan di mode proot.
- Source code tidak dipublikasikan. Kalau ragu, Anda bisa memindai APK di [VirusTotal](https://www.virustotal.com) sebelum install.

### Cara install
1. Unduh APK dari **Releases**.
2. Buka file APK. Kalau diminta, aktifkan **Izinkan install dari sumber ini**.
3. Buka app, pilih **Install Kali**, lalu tunggu sampai selesai.

### Catatan
- Peringatan "aplikasi tidak dikenal" dari Android muncul karena APK ini tidak dari Play Store. Itu normal untuk APK di luar Play Store.
- Gunakan hanya di perangkat dan jaringan milik sendiri atau yang Anda punya izin untuk mengujinya.

### Masalah atau saran
Buka tab **Issues** di repo ini.

---

## English

**Kali Linux terminal app for Android.** Run Kali directly on your phone, no computer needed.

### About this app
Edward Kali Terminal installs a **Kali Linux system (minimal, arm64)** on your Android phone and opens a terminal to use it. You get a full Linux environment with `apt`, `sudo` and bash/zsh, and you can install Kali tools as you need them.

**How it works:**
- On first launch, the app downloads the Kali rootfs from the official server (`kali.download`) and extracts it into the app's internal storage.
- **Root mode (chroot):** used when your phone is rooted and you allow it. This is the fastest and most complete option.
- **Non-root mode (proot):** for phones without root. Everything runs inside the app and nothing on Android itself is changed.
- The mode is chosen automatically, and you can switch it manually from the app menu.

**Good for:**
- Learning Linux and the command line on your phone
- Running Kali tools and other Linux programs
- Running an XFCE desktop over VNC
- Network security practice on devices or networks you own

### Features
- **Root** (chroot) and **non-root** (proot) modes
- Works with `sudo` and `apt install`
- One-tap Kali tool installer
- **XFCE + VNC** desktop
- Kali **backup and restore**
- Terminal with ESC, TAB, CTRL, ALT and arrow keys
- Access phone files through `~/storage`

### Download
Go to the **Releases** tab of this repo and download the latest `.apk`.

### Requirements
- Android 7.0 or newer
- **arm64** phone (most modern phones)
- About 2 GB of free space or more, and an internet connection for the first install

### Why does the app ask for permissions?
| Permission | Used for |
|---|---|
| Internet | Downloading Kali and running `apt` |
| Storage | Linking phone folders into Kali (`~/storage`) and saving backups |
| Notifications and foreground service | Keeping the terminal session alive |
| Wake lock and ignore battery optimization | Stopping Android from killing the process when the screen is off |

The app does **not** request access to contacts, SMS, camera, microphone or location.

### Security
- On install, the app downloads the Kali rootfs from the official server: `kali.download`.
- No ads, no account required.
- Root mode only works if your phone is already rooted and you grant access yourself. Without root, the app runs in proot mode.
- The source code is not published. If you are unsure, you can scan the APK on [VirusTotal](https://www.virustotal.com) before installing.

### How to install
1. Download the APK from **Releases**.
2. Open the APK. If asked, enable **Allow from this source**.
3. Open the app, tap **Install Kali**, and wait until it finishes.

### Notes
- Android shows an "unknown app" warning because this APK is not from the Play Store. This is normal for APKs from outside the Play Store.
- Use it only on devices and networks you own or have permission to test.

### Issues and suggestions
Open the **Issues** tab of this repo.