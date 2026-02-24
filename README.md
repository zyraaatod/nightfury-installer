🔥 NightFury Installer

<div align="center">  




Installer Tool untuk NightFury - Web Scanning Utility

Features • Installation • Usage • Documentation

</div>  
---

📖 Tentang Proyek

NightFury Installer adalah tool otomatis untuk menginstal NightFury, sebuah utility scanning web yang powerful dan user-friendly. Tool ini dirancang khusus untuk environment Termux dan memudahkan pengguna dalam setup dan menjalankan NightFury dengan cepat.

> 🎯 Tujuan: Menyediakan instalasi otomatis yang mudah dan cepat untuk NightFury di Termux




---

✨ Fitur

✅ Instalasi Otomatis - Setup NightFury dengan sekali perintah

✅ Termux Compatible - Berjalan sempurna di Termux

✅ Lightweight - Ukuran kecil, tidak berat

✅ Easy to Use - Interface yang user-friendly

✅ Fast Setup - Instalasi cepat dan efisien

✅ Web Scanning Tool - Terintegrasi dengan NightFury untuk scanning web



---

📋 Persyaratan

Termux (atau Linux environment lainnya)

Bash Shell

Python 3.x (untuk menjalankan script Python)

Git (untuk clone repository)

Koneksi Internet yang stabil



---

🔧 Instalasi

Metode 1: Menggunakan Bash Script (Recommended)

# Clone repository  
git clone https://github.com/zyraaatod/nightfury-installer.git  
cd nightfury-installer  
  
# Jalankan installer script  
bash n.sh  
  
# Navigasi ke direktori NightFury  
cd $HOME/nightfury-max  
  
# Jalankan aplikasi  
./run.sh

Metode 2: Menggunakan Python

# Clone repository  
git clone https://github.com/zyraaatod/nightfury-installer.git  
cd nightfury-installer  
  
# Jalankan dengan Python  
python nightfury_max.py

Metode 3: One-Liner (Quick Start)

git clone https://github.com/zyraaatod/nightfury-installer.git && cd nightfury-installer && bash n.sh


---

🚀 Cara Penggunaan

Setelah Instalasi:

1. Buka NightFury

cd $HOME/nightfury-max  
./run.sh


2. Ikuti instruksi yang ditampilkan di terminal


3. Masukkan target URL yang ingin di-scan


4. Tunggu hasil scanning dan analisis keamanan web




---

📁 Struktur Direktori

nightfury-max/  
├── run.sh                 # Main installer script  
├── nightfury_max.py       # Python installer script  
├── quick.txt              # Dokumentasi  
└── ...

NOTES

> untuh hasil / result masih terlalu rumit [nightfury_report_20260223_133851.txt] anda bisa mengedit dan mengubah nya sendiri




---

🛠️ Troubleshooting

Masalah: Permission Denied

Solusi:

chmod +x n.sh  
chmod +x ./run.sh

Masalah: Script tidak ditemukan

Solusi:

# Pastikan Anda di direktori yang benar  
pwd  
  
# Coba dengan path lengkap  
bash ./n.sh

Masalah: Python not found

Solusi:

# Install Python  
apt update  
apt install python3  
  
# Jalankan script lagi  
python3 nightfury_max.py


---

📚 Dokumentasi

Untuk dokumentasi lengkap, silakan kunjungi NightFury Documentation


---

📝 Lisensi

Project ini dilisensikan di bawah MIT License - lihat file LICENSE untuk detail lengkap.


---

👨‍💻 Author

zyraaatod

GitHub: @zyraaatod

Email: kudaterbang1441@gmail.com



---

<div align="center">  Made with ❤️ by zyraaatod

</div>  
.  buat kan README.md ini supaya bisa 2 mode bahasa inggris dan Indonesia