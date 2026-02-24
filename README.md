🔥 NightFury Installer

<div align="center">

https://img.shields.io/badge/version-1.0.0-blue.svg
https://img.shields.io/badge/license-MIT-green.svg
https://img.shields.io/badge/Termux-Compatible-brightgreen.svg
https://img.shields.io/badge/Python-3.x-yellow.svg

Installer Tool untuk NightFury - Web Scanning Utility
Multilingual Documentation (EN/ID)

</div>

---

🌐 Language / Bahasa

<details open>
<summary><b>🇮🇩 Indonesia</b></summary>

📖 Tentang Proyek

NightFury Installer adalah tool otomatis untuk menginstal NightFury, sebuah utility scanning web yang powerful dan user-friendly. Tool ini dirancang khusus untuk environment Termux dan memudahkan pengguna dalam setup dan menjalankan NightFury dengan cepat.

🎯 Tujuan: Menyediakan instalasi otomatis yang mudah dan cepat untuk NightFury di Termux

✨ Fitur

Fitur Deskripsi
✅ Instalasi Otomatis Setup NightFury dengan sekali perintah
✅ Termux Compatible Berjalan sempurna di Termux
✅ Lightweight Ukuran kecil, tidak berat
✅ Easy to Use Interface yang user-friendly
✅ Fast Setup Instalasi cepat dan efisien
✅ Web Scanning Tool Terintegrasi dengan NightFury untuk scanning web

📋 Persyaratan Sistem

· Termux (direkomendasikan) atau Linux environment lainnya
· Bash Shell (versi 4.0+)
· Python 3.x (untuk menjalankan script alternatif)
· Git (untuk clone repository)
· Koneksi Internet yang stabil
· Storage minimal 100MB

🔧 Metode Instalasi

Metode 1: Bash Script (Direkomendasikan)

```bash
# Clone repository
git clone https://github.com/zyraaatod/nightfury-installer.git
cd nightfury-installer

# Beri izin eksekusi
chmod +x n.sh

# Jalankan installer
bash n.sh

# Navigasi ke NightFury
cd $HOME/nightfury-max

# Jalankan aplikasi
chmod +x run.sh
./run.sh
```

Metode 2: Python Script

```bash
# Clone repository
git clone https://github.com/zyraaatod/nightfury-installer.git
cd nightfury-installer

# Jalankan dengan Python
python3 nightfury_max.py
```

Metode 3: One-Liner (Instalasi Cepat)

```bash
git clone https://github.com/zyraaatod/nightfury-installer.git && cd nightfury-installer && bash n.sh
```

🚀 Cara Penggunaan

1. Buka NightFury
   ```bash
   cd $HOME/nightfury-max
   ./run.sh
   ```
2. Ikuti instruksi yang ditampilkan di terminal
3. Masukkan target URL yang ingin di-scan
   ```
   Contoh: https://example.com
   ```
4. Tunggu proses scanning dan analisis keamanan web selesai
5. Lihat hasil scan yang akan tersimpan dalam format:
   ```
   nightfury_report_YYYYMMDD_HHMMSS.txt
   ```

📁 Struktur Direktori

```
nightfury-max/
├── run.sh                 # Main script untuk menjalankan NightFury
├── nightfury_max.py       # Python installer alternatif
├── core/                  # Direktori core modules
├── modules/               # Modul-modul scanning
├── reports/               # Hasil scan tersimpan disini
├── config/                # File konfigurasi
├── quick.txt              # Dokumentasi cepat
└── README.md              # Dokumentasi utama
```

Catatan: Hasil report masih dalam format [nightfury_report_YYYYMMDD_HHMMSS.txt] yang bisa Anda edit sesuai kebutuhan.

🛠️ Troubleshooting

Masalah Solusi
Permission Denied chmod +x n.sh && chmod +x run.sh
Script tidak ditemukan pwd untuk cek direktori, lalu bash ./n.sh
Python not found apt update && apt install python3
Git not found apt update && apt install git
Dependency error pip install -r requirements.txt
Connection timeout Periksa koneksi internet atau gunakan VPN

📚 Dokumentasi Lengkap

Untuk dokumentasi lebih detail, fitur-fitur, dan panduan penggunaan lanjutan:

· 📖 NightFury Documentation
· 💬 Discord Community
· 🐛 Issue Tracker

</details>

---

<details>
<summary><b>🇬🇧 English</b></summary>

📖 About The Project

NightFury Installer is an automated tool to install NightFury, a powerful and user-friendly web scanning utility. This tool is specifically designed for the Termux environment and makes it easy for users to set up and run NightFury quickly.

🎯 Purpose: Provide easy and fast automated installation for NightFury on Termux

✨ Features

Feature Description
✅ Automatic Installation Setup NightFury with a single command
✅ Termux Compatible Runs perfectly on Termux
✅ Lightweight Small footprint, not resource-intensive
✅ Easy to Use User-friendly interface
✅ Fast Setup Quick and efficient installation
✅ Web Scanning Tool Integrated with NightFury for web scanning

📋 System Requirements

· Termux (recommended) or other Linux environment
· Bash Shell (version 4.0+)
· Python 3.x (for alternative script)
· Git (for cloning repository)
· Stable Internet Connection
· Storage minimum 100MB

🔧 Installation Methods

Method 1: Bash Script (Recommended)

```bash
# Clone repository
git clone https://github.com/zyraaatod/nightfury-installer.git
cd nightfury-installer

# Give execute permission
chmod +x n.sh

# Run installer
bash n.sh

# Navigate to NightFury
cd $HOME/nightfury-max

# Run the application
chmod +x run.sh
./run.sh
```

Method 2: Python Script

```bash
# Clone repository
git clone https://github.com/zyraaatod/nightfury-installer.git
cd nightfury-installer

# Run with Python
python3 nightfury_max.py
```

Method 3: One-Liner (Quick Installation)

```bash
git clone https://github.com/zyraaatod/nightfury-installer.git && cd nightfury-installer && bash n.sh
```

🚀 Usage Guide

1. Open NightFury
   ```bash
   cd $HOME/nightfury-max
   ./run.sh
   ```
2. Follow the instructions displayed in the terminal
3. Enter the target URL you want to scan
   ```
   Example: https://example.com
   ```
4. Wait for the scanning process and web security analysis to complete
5. View scan results which will be saved in format:
   ```
   nightfury_report_YYYYMMDD_HHMMSS.txt
   ```

📁 Directory Structure

```
nightfury-max/
├── run.sh                 # Main script to run NightFury
├── nightfury_max.py       # Alternative Python installer
├── core/                  # Core modules directory
├── modules/               # Scanning modules
├── reports/               # Scan results saved here
├── config/                # Configuration files
├── quick.txt              # Quick documentation
└── README.md              # Main documentation
```

Note: The report format [nightfury_report_YYYYMMDD_HHMMSS.txt] can be edited according to your needs.

🛠️ Troubleshooting

Problem Solution
Permission Denied chmod +x n.sh && chmod +x run.sh
Script not found pwd to check directory, then bash ./n.sh
Python not found apt update && apt install python3
Git not found apt update && apt install git
Dependency error pip install -r requirements.txt
Connection timeout Check internet connection or use VPN

📚 Complete Documentation

For more detailed documentation, features, and advanced usage guides:

· 📖 NightFury Documentation
· 💬 Discord Community
· 🐛 Issue Tracker

</details>

---

📝 License / Lisensi

<div align="center">

MIT License • Copyright (c) 2024 zyraaatod

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions...

</div>

---

👨‍💻 Author

<div align="center">

zyraaatod

https://img.shields.io/badge/GitHub-zyraaatod-181717?style=for-the-badge&logo=github
https://img.shields.io/badge/Email-kudaterbang1441%40gmail.com-red?style=for-the-badge&logo=gmail
https://img.shields.io/badge/Telegram-@zyraaatod-2CA5E0?style=for-the-badge&logo=telegram

</div>

---

🤝 Contributing / Berkontribusi

<div align="center">

Contributions, issues, and feature requests are welcome!
Kontribusi, issue, dan permintaan fitur sangat diterima!

https://img.shields.io/github/issues/zyraaatod/nightfury-installer
https://img.shields.io/github/forks/zyraaatod/nightfury-installer
https://img.shields.io/github/stars/zyraaatod/nightfury-installer

</div>

---

💖 Support

<div align="center">

If you find this project helpful, consider giving it a ⭐ on GitHub!
Jika Anda merasa proyek ini bermanfaat, berikan ⭐ di GitHub!

https://img.shields.io/github/stars/zyraaatod/nightfury-installer?style=social

---

Made with ❤️ by zyraaatod
Dibuat dengan ❤️ oleh zyraaatod

© 2024 NightFury Installer • All Rights Reserved

</div>