# Deauter-ESP32

**Repo untuk berbagai firmware dan tools terkait WiFi deauthentication menggunakan ESP8266/ESP32**

> ⚠️ **Disclaimer:** Repo ini dibuat untuk tujuan edukasi dan pembelajaran keamanan jaringan. Dilarang menggunakan konten dalam repo ini untuk kegiatan ilegal atau tanpa izin pemilik jaringan.

## 📦 Isi Repo

Repo ini berisi kumpulan file biner, tools flashing, dan arsip ZIP yang digunakan untuk menjalankan berbagai fungsi "WiFi hacking" seperti:

* **Deauthentication Attack**
* **Fake Access Point (Evil Twin)**
* **SSID Cloning / Broadcasting**

### 📁 File Utama

| File                                                           | Deskripsi                                                |
| -------------------------------------------------------------- | -------------------------------------------------------- |
| `ESP8266_ZeroTwin_1.0.0-alpha_Indonesian.ino.bin`              | Firmware berbasis Evil Twin untuk ESP8266                |
| `esp8266_deauther_V2_1M_Nightly.bin`                           | Firmware nightly build untuk deauther                    |
| `ESP8266-EvilTwin-2.zip`                                       | ZIP berisi source code atau file pendukung untuk fake AP |
| `ESP8266Flasher.exe`                                           | Aplikasi untuk mem-flash firmware ke board ESP8266       |
| `ESP8266_ZeroTwin_1.0.0-alpha_Indonesian (SafefilekU.com).zip` | Versi ZIP firmware dengan nama situs sumber              |

## ⚙️ Cara Menggunakan

1. **Download dan instal driver ESP8266/ESP32** sesuai dengan board yang digunakan.
2. Gunakan `ESP8266Flasher.exe` untuk memilih dan meng-upload firmware `.bin` ke board ESP8266 Anda.
3. Setelah upload selesai, sambungkan ke jaringan WiFi yang disediakan oleh perangkat Anda (biasanya bernama `pwned` atau sesuai firmware).
4. Akses antarmuka pengguna melalui browser (`192.168.4.1`) untuk menggunakan fungsi deauther atau Evil Twin.

## 🧠 Tujuan Edukasi

Project ini bertujuan untuk:

* Memberikan pemahaman cara kerja serangan jaringan WiFi.
* Melatih penggunaan mikrokontroler dalam simulasi keamanan.
* Edukasi ethical hacking bagi peneliti dan pelajar.

## ⚠️ Legalitas

Penggunaan firmware ini hanya diperbolehkan di lingkungan lab atau jaringan pribadi milik sendiri. Penulis dan kontributor **tidak bertanggung jawab atas penyalahgunaan** tool ini untuk aktivitas ilegal.

## 📎 Link Repository

🔗 [https://github.com/Krisnaadityapratama/Deauter-ESP32](https://github.com/Krisnaadityapratama/Deauter-ESP32)
