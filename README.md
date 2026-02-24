

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/zyraaatod/nightfury-installer?style=social)](https://github.com/zyraaatod/nightfury-installer)
[![Termux Compatible](https://img.shields.io/badge/Termux-Compatible-green)](https://f-droid.org/id/packages/com.termux/)
[![Version](https://img.shields.io/badge/Version-1.0-blue)](https://github.com/zyraaatod/nightfury-installer)

**Installer Tool untuk NightFury - Web Scanning Utility**

[Features](#-fitur) • [Installation](#-instalasi) • [Usage](#-cara-penggunaan) • [Documentation](#-dokumentasi)

</div>

---

## 📖 Tentang Proyek / About the Project

**NightFury Installer** adalah tool otomatis untuk menginstal **NightFury**, sebuah utility scanning web yang powerful dan user-friendly. Tool ini dirancang khusus untuk environment **Termux** dan memudahkan pengguna dalam setup dan menjalankan NightFury dengan cepat.

> 🎯 **Tujuan**: Menyediakan instalasi otomatis yang mudah dan cepat untuk NightFury di Termux

---

### English Version:

**NightFury Installer** is an automated tool to install **NightFury**, a powerful and user-friendly web scanning utility. This tool is specially designed for the **Termux** environment and makes setting up and running NightFury fast and easy.

> 🎯 **Goal**: Provide an easy and fast installation for NightFury on Termux.

---

## ✨ Fitur / Features

- ✅ **Instalasi Otomatis / Automatic Installation** - Setup NightFury dengan sekali perintah / One command setup for NightFury
- ✅ **Termux Compatible** - Berjalan sempurna di Termux / Works perfectly on Termux
- ✅ **Lightweight** - Ukuran kecil, tidak berat / Small in size, lightweight
- ✅ **Easy to Use** - Interface yang user-friendly / User-friendly interface
- ✅ **Fast Setup** - Instalasi cepat dan efisien / Fast and efficient installation
- ✅ **Web Scanning Tool** - Terintegrasi dengan NightFury untuk scanning web / Integrated with NightFury for web scanning

---

### English Version:

- ✅ **Automatic Installation** - Set up NightFury with one command
- ✅ **Termux Compatible** - Runs perfectly on Termux
- ✅ **Lightweight** - Small size, not resource-heavy
- ✅ **Easy to Use** - User-friendly interface
- ✅ **Fast Setup** - Quick and efficient installation
- ✅ **Web Scanning Tool** - Integrated with NightFury for web scanning

---

## 📋 Persyaratan / Requirements

- **Termux** (atau Linux environment lainnya / or other Linux environment)
- **Bash Shell**
- **Python 3.x** (untuk menjalankan script Python / to run Python scripts)
- **Git** (untuk clone repository)
- **Koneksi Internet** yang stabil / Stable internet connection

---

### English Version:

- **Termux** (or any Linux environment)
- **Bash Shell**
- **Python 3.x** (to run Python scripts)
- **Git** (to clone the repository)
- **Stable internet connection**

---

## 🔧 Instalasi / Installation

### Metode 1: Menggunakan Bash Script (Recommended) / Method 1: Using Bash Script (Recommended)

```bash
# Clone repository
git clone https://github.com/zyraaatod/nightfury-installer.git
cd nightfury-installer

# Jalankan installer script / Run the installer script
bash n.sh

# Navigasi ke direktori NightFury / Navigate to the NightFury directory
cd $HOME/nightfury-max

# Jalankan aplikasi / Run the application
./run.sh
Metode 2: Menggunakan Python / Method 2: Using Python
Salin kode
Bash
# Clone repository
git clone https://github.com/zyraaatod/nightfury-installer.git
cd nightfury-installer

# Jalankan dengan Python / Run with Python
python nightfury_max.py
Metode 3: One-Liner (Quick Start) / Method 3: One-Liner (Quick Start)
Salin kode
Bash
git clone https://github.com/zyraaatod/nightfury-installer.git && cd nightfury-installer && bash n.sh
English Version:
Method 1: Using Bash Script (Recommended)
Salin kode
Bash
# Clone repository
git clone https://github.com/zyraaatod/nightfury-installer.git
cd nightfury-installer

# Run the installer script
bash n.sh

# Navigate to the NightFury directory
cd $HOME/nightfury-max

# Run the application
./run.sh
Method 2: Using Python
Salin kode
Bash
# Clone repository
git clone https://github.com/zyraaatod/nightfury-installer.git
cd nightfury-installer

# Run with Python
python nightfury_max.py
Method 3: One-Liner (Quick Start)
Salin kode
Bash
git clone https://github.com/zyraaatod/nightfury-installer.git && cd nightfury-installer && bash n.sh
🚀 Cara Penggunaan / Usage
Setelah Instalasi / After Installation:
Buka NightFury / Open NightFury
Salin kode
Bash
cd $HOME/nightfury-max
./run.sh
Ikuti instruksi yang ditampilkan di terminal / Follow the instructions displayed in the terminal
Masukkan target URL yang ingin di-scan / Enter the target URL you want to scan
Tunggu hasil scanning dan analisis keamanan web / Wait for the scan results and web security analysis
English Version:
Open NightFury
Salin kode
Bash
cd $HOME/nightfury-max
./run.sh
Follow the instructions displayed in the terminal
Enter the target URL you want to scan
Wait for the scan results and web security analysis
📁 Struktur Direktori / Directory Structure
Salin kode

nightfury-max/
├── run.sh                 # Main installer script
├── nightfury_max.py       # Python installer script
├── quick.txt              # Dokumentasi / Documentation
└── ...
🛠️ Troubleshooting
Masalah: Permission Denied / Problem: Permission Denied
Solusi / Solution:
Salin kode
Bash
chmod +x n.sh
chmod +x ./run.sh
Masalah: Script tidak ditemukan / Problem: Script Not Found
Solusi / Solution:
Salin kode
Bash
# Pastikan Anda di direktori yang benar / Ensure you're in the right directory
pwd

# Coba dengan path lengkap / Try with full path
bash ./n.sh
Masalah: Python not found / Problem: Python not found
Solusi / Solution:
Salin kode
Bash
# Install Python / Install Python
apt update
apt install python3

# Jalankan script lagi / Run the script again
python3 nightfury_max.py
English Version:
🛠️ Troubleshooting
Problem: Permission Denied
Solution:
Salin kode
Bash
chmod +x n.sh
chmod +x ./run.sh
Problem: Script Not Found
Solution:
Salin kode
Bash
# Ensure you're in the right directory
pwd

# Try with full path
bash ./n.sh
Problem: Python Not Found
Solution:
Salin kode
Bash
# Install Python
apt update
apt install python3

# Run the script again
python3 nightfury_max.py
📚 Dokumentasi / Documentation
Untuk dokumentasi lengkap, silakan kunjungi NightFury Documentation�
English Version:
For full documentation, please visit NightFury Documentation�
📝 Lisensi / License
Project ini dilisensikan di bawah MIT License - lihat file LICENSE untuk detail lengkap.
English Version:
This project is licensed under the MIT License - see the LICENSE file for full details.
👨‍💻 Author
zyraaatod
GitHub: @zyraaatod�
Email: kudaterbang1441@gmail.com
�

Made with ❤️ by zyraaatod
�
```
Dengan format ini, pembaca dapat dengan mudah memilih mode bahasa yang mereka inginkan, baik itu dalam bahasa Indonesia atau bahasa Inggris.