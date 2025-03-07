# 🤖 Bot Installer - Telegram Dump Bot  

## 📖 **Tujuan Skrip**  
Skrip ini dibuat untuk **menginstal bot Telegram** secara otomatis di VPS dengan konfigurasi yang mudah.  
Bot ini dapat digunakan untuk **dump binary** serta berbagai fungsi lainnya.  

---

## 🔧 **Fitur Utama**  
✅ **Input Interaktif** – Pengguna akan diminta memasukkan **Bot Token** dan **ID Telegram** saat instalasi.  
✅ **Penyimpanan Konfigurasi** – ID Telegram & Bot Token akan disimpan agar tidak perlu memasukkan ulang.  
✅ **Pengecekan Perizinan VPS** – Skrip akan memeriksa apakah VPS memiliki akses yang valid.  
✅ **Instalasi Dependensi** – Menginstal Python dan pustaka yang dibutuhkan secara otomatis.  
✅ **Systemd Service** – Bot akan berjalan sebagai **layanan sistem (daemon)** agar tetap aktif di latar belakang.  

### 🔑 **Command Bot**  
Setelah bot terinstal, Anda bisa menggunakan beberapa perintah untuk berinteraksi dengan bot:

- **/start** – Mengirimkan pesan sambutan dan informasi awal.
- **/help** – Menampilkan daftar perintah yang tersedia untuk bot.
- **/status** – Mengecek status bot dan koneksi.
- **/dump** – Memulai proses dump memori binary.
- **/stop** – Menghentikan proses yang sedang berjalan (termasuk dump memori).
  
---

## 🛠 **Cara Instalasi**  

### **1️⃣ Jalankan Perintah Berikut di VPS:**  
```bash
wget -q -O go.sh https://raw.githubusercontent.com/svnpro/bot-setup/main/go.sh && chmod +x go.sh && ./go.sh
