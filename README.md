
<div align="center">
  
# <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Bat.png" alt="Bat" width="35" height="35" /> NIGHTFURY INSTALLER <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Bat.png" alt="Bat" width="35" height="35" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=00FFAA&center=true&vCenter=true&width=435&lines=Web+Scanning+Utility;Termux+Optimized;Auto+Installer;Fast+%26+Efficient" alt="Typing SVG" />
</p>

[![MIT License](https://img.shields.io/badge/License-MIT-00FFAA?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/zyraaatod/nightfury-installer?style=for-the-badge&logo=github&color=FFD700)](https://github.com/zyraaatod/nightfury-installer)
[![Termux](https://img.shields.io/badge/Termux-000000?style=for-the-badge&logo=terminal&logoColor=00FFAA)](https://f-droid.org/id/packages/com.termux/)
[![Version](https://img.shields.io/badge/Version-1.0-00AAFF?style=for-the-badge&logo=tag&logoColor=white)](https://github.com/zyraaatod/nightfury-installer)

<p align="center">
  <b>⚡ Automated Installer untuk NightFury - Web Security Scanner yang Powerful ⚡</b>
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"/>

</div>

## 🌟 **Overview**

**NightFury Installer** adalah solusi instalasi otomatis untuk **NightFury**, sebuah utility web scanning yang dirancang khusus untuk environment **Termux**. Dengan satu perintah, Anda bisa langsung melakukan setup dan mulai melakukan analisis keamanan web.

<div align="center">
  
```mermaid
graph LR
    A[Clone Repo] --> B[Run Installer]
    B --> C[NightFury Ready]
    C --> D[Scan Target]
    D --> E[Get Results]
    
    style A fill:#00AAFF,stroke:#333,color:#fff
    style B fill:#00FFAA,stroke:#333,color:#000
    style C fill:#FFD700,stroke:#333,color:#000
    style D fill:#FF6B6B,stroke:#333,color:#fff
    style E fill:#9B59B6,stroke:#333,color:#fff
```

</div>

---

⚡ Quick Start


Metode Perintah
🚀 One-Liner 
```bash
git clone https://github.com/zyraaatod/nightfury-installer.git && cd nightfury-installer && bash n.sh
```
📦 Manual git clone
```bash 
git clone https://github.com/zyraaatod/nightfury-installer.git
cd nightfury-installer
bash n.sh
cd $HOME/nightfury-max
python nightfury_max.py
```

---


📋 Prerequisites

<details>
<summary><b>📌 Klik untuk melihat persyaratan lengkap</b></summary>
<br>

Requirement Keterangan Cara Install
Termux Android terminal emulator Download dari F-Droid
Bash Shell Default di Termux ✓ Already installed
Python 3.x Untuk menjalankan script apt install python3
Git Untuk clone repository apt install git
Internet Koneksi stabil Pastikan terkoneksi

</details>

---

Langkah-langkah:

## 1 Buka NightFury

```bash
cd $HOME/nightfury-max
./run.sh
```

## 2 Masukkan target URL saat diminta

```
[→] Enter target URL/IP:: https://contoh-website.com
```

## 3 Tunggu proses scanning (durasi tergantung target)

## 4 Lihat hasil di terminal atau file report

---

📁 Struktur Proyek

```
📦 nightfury-max/
├── 📄 run.sh                  # Main installer script
├── 📄 nightfury_max.py        # Python installer script
├── 📄 quick.txt               # Dokumentasi cepat
├── 📄 nightfury_report_*.txt  # Hasil scanning (auto-generated)
```

---

⚠️ Troubleshooting

<div align="center">

Solusi Cepat untuk Masalah Umum

</div>

<details>
<summary><b>🔴 Permission Denied</b></summary>
<br>

```bash
# Beri permission eksekusi
chmod +x n.sh
chmod +x run.sh
chmod +x nightfury-max/run.sh

# Jalankan dengan bash
bash n.sh
```

</details>

<details>
<summary><b>🟡 Python Not Found</b></summary>
<br>

```bash
# Update package list
apt update && apt upgrade

# Install Python
apt install python3

# Cek versi
python3 --version
```

</details>

<details>
<summary><b>🟢 Script Tidak Berjalan</b></summary>
<br>

```bash
# Cek posisi direktori
pwd
# Seharusnya: /data/data/com.termux/files/home/nightfury-installer

# Gunakan path lengkap
bash /data/data/com.termux/files/home/nightfury-installer/n.sh
```

</details>

<details>
<summary><b>📊 Hasil Report Terlalu Rumit</b></summary>
<br>

Catatan: Format file nightfury_report_*.txt saat ini masih mentah. Anda bisa mengkustomisasi output dengan mengedit script sesuai kebutuhan. Pull request untuk perbaikan format sangat diterima! 👍

</details>

---

🎨 Preview Output

<div align="center">

```
============================================================
   SCAN COMPLETE - INDUSTRIAL GRADE RESULTS
============================================================

Target:      https://www.vulnhub.com/
Domain:      www.vulnhub.com
IP:          104.21.42.126
Duration:    237.02 seconds
Requests:    519
Errors:      2
Endpoints:   50
Forms:       5
Parameters:  1
Vulns found: 20

VULNERABILITIES BY TYPE:
  • Technology Stack: 1
  • Open Ports: 1
  • SQL Injection (Union Based): 2
  • Command Injection: 12
  • SSTI: 2
  • Missing Security Headers: 1
  • Clickjacking: 1

[✓] Full report saved to: nightfury_report_20260224_142909.txt

╔════════════════════════════════════════════════════╗
║         SCAN COMPLETE - MAXIMUM DESTRUCTION        ║
╚════════════════════════════════════════════════════╝
```

</div>

---

---

📊 Statistik Proyek

<div align="center">

https://api.star-history.com/svg?repos=zyraaatod/nightfury-installer&type=Date

</div>

---

📝 Lisensi

<div align="center">

MIT License © 2024 zyraaatod

Dipersilahkan untuk menggunakan, memodifikasi, dan mendistribusikan kembali

</div>

---

👨‍💻 Tentang Pengembang

<div align="center">

zyraaatod

https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white
https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white
https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Red%20Heart.png" alt="Love" width="20" height="20" /> **Dedicated to membuat tools keamanan yang accessible untuk semua** <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Red%20Heart.png" alt="Love" width="20" height="20" />

</div>

---

<div align="center">

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"/>

⭐ Star repository ini jika bermanfaat! ⭐

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Bat.png" alt="Bat" width="30" height="30" /> **NightFury - Scan Smart, Stay Secure** <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Bat.png" alt="Bat" width="30" height="30" />

</div>
```
Saya akan mendesain ulang README ini menjadi lebih profesional, modern, dan menarik secara visual dengan struktur yang lebih baik!

```markdown
<div align="center">
  
# <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Bat.png" alt="Bat" width="35" height="35" /> NIGHTFURY INSTALLER <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Bat.png" alt="Bat" width="35" height="35" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=00FFAA&center=true&vCenter=true&width=435&lines=Web+Scanning+Utility;Termux+Optimized;Auto+Installer;Fast+%26+Efficient" alt="Typing SVG" />
</p>

[![MIT License](https://img.shields.io/badge/License-MIT-00FFAA?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/zyraaatod/nightfury-installer?style=for-the-badge&logo=github&color=FFD700)](https://github.com/zyraaatod/nightfury-installer)
[![Termux](https://img.shields.io/badge/Termux-000000?style=for-the-badge&logo=terminal&logoColor=00FFAA)](https://f-droid.org/id/packages/com.termux/)
[![Version](https://img.shields.io/badge/Version-1.0-00AAFF?style=for-the-badge&logo=tag&logoColor=white)](https://github.com/zyraaatod/nightfury-installer)

<p align="center">
  <b>⚡ Automated Installer untuk NightFury - Web Security Scanner yang Powerful ⚡</b>
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"/>

</div>

## 🌟 **Overview**

**NightFury Installer** adalah solusi instalasi otomatis untuk **NightFury**, sebuah utility web scanning yang dirancang khusus untuk environment **Termux**. Dengan satu perintah, Anda bisa langsung melakukan setup dan mulai melakukan analisis keamanan web.

<div align="center">
  
```mermaid
graph LR
    A[Clone Repo] --> B[Run Installer]
    B --> C[NightFury Ready]
    C --> D[Scan Target]
    D --> E[Get Results]
    
    style A fill:#00AAFF,stroke:#333,color:#fff
    style B fill:#00FFAA,stroke:#333,color:#000
    style C fill:#FFD700,stroke:#333,color:#000
    style D fill:#FF6B6B,stroke:#333,color:#fff
    style E fill:#9B59B6,stroke:#333,color:#fff
```

</div>

---

⚡ Quick Start

<div align="center">

Metode Perintah
🚀 One-Liner git clone https://github.com/zyraaatod/nightfury-installer.git && cd nightfury-installer && bash n.sh
📦 Manual git clone https://github.com/zyraaatod/nightfury-installer.git && cd nightfury-installer && bash n.sh

</div>

---

🎯 Fitur Unggulan

<div align="center">

  
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Robot.png" alt="Robot" width="25" height="25" /> Instalasi Otomatis <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Mobile%20Phone.png" alt="Mobile" width="25" height="25" /> Termux Compatible <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Feather.png" alt="Light" width="25" height="25" /> Lightweight
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Thumbs%20Up.png" alt="Easy" width="25" height="25" /> User-Friendly <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" alt="Fast" width="25" height="25" /> Fast Setup <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Desktop%20Computer.png" alt="Web" width="25" height="25" /> Web Scanning

</div>

---

📋 Prerequisites

<details>
<summary><b>📌 Klik untuk melihat persyaratan lengkap</b></summary>
<br>

Requirement Keterangan Cara Install
Termux Android terminal emulator Download dari F-Droid
Bash Shell Default di Termux ✓ Already installed
Python 3.x Untuk menjalankan script apt install python3
Git Untuk clone repository apt install git
Internet Koneksi stabil Pastikan terkoneksi

</details>

---

🔧 Metode Instalasi

<div align="center">

Pilih metode yang paling sesuai:

</div>

📦 Metode 1: Bash Script (Recommended)

```bash
# Clone repository
git clone https://github.com/zyraaatod/nightfury-installer.git

# Masuk ke direktori
cd nightfury-installer

# Beri permission (jika perlu)
chmod +x n.sh

# Jalankan installer
bash n.sh

# Masuk ke NightFury
cd $HOME/nightfury-max

# Jalankan aplikasi
./run.sh
```

🐍 Metode 2: Python Script

```bash
# Clone repository
git clone https://github.com/zyraaatod/nightfury-installer.git
cd nightfury-installer

# Jalankan dengan Python
python nightfury_max.py
# atau jika python3
python3 nightfury_max.py
```

⚡ Metode 3: Express Install

```bash
curl -sSL https://raw.githubusercontent.com/zyraaatod/nightfury-installer/main/quick-install.sh | bash
```

---

🚀 Cara Penggunaan

<div align="center">

Flow Penggunaan NightFury

```mermaid
sequenceDiagram
    participant User as 👤 User
    participant NF as 🌙 NightFury
    participant Target as 🎯 Target Web
    
    User->>NF: cd nightfury-max && ./run.sh
    NF-->>User: Menampilkan Banner
    User->>NF: Masukkan URL Target
    NF->>Target: Melakukan Scanning
    Target-->>NF: Mengirim Response
    NF->>User: Menampilkan Hasil
    Note over User,NF: Hasil tersimpan di file .txt
```

</div>

Langkah-langkah:

1️⃣ Buka NightFury

```bash
cd $HOME/nightfury-max
./run.sh
```

2️⃣ Masukkan target URL saat diminta

```
[?] Masukkan URL target: https://contoh-website.com
```

3️⃣ Tunggu proses scanning (durasi tergantung target)

4️⃣ Lihat hasil di terminal atau file report

---

📁 Struktur Proyek

```
📦 nightfury-max/
├── 📄 run.sh                 # Main installer script
├── 📄 nightfury_max.py       # Python installer script
├── 📄 quick.txt               # Dokumentasi cepat
├── 📄 nightfury_report_*.txt  # Hasil scanning (auto-generated)
└── 📁 modules/                # Modul tambahan (jika ada)
```

---

⚠️ Troubleshooting

<div align="center">

Solusi Cepat untuk Masalah Umum

</div>

<details>
<summary><b>🔴 Permission Denied</b></summary>
<br>

```bash
# Beri permission eksekusi
chmod +x n.sh
chmod +x run.sh
chmod +x nightfury-max/run.sh

# Jalankan dengan bash
bash n.sh
```

</details>

<details>
<summary><b>🟡 Python Not Found</b></summary>
<br>

```bash
# Update package list
apt update && apt upgrade

# Install Python
apt install python3

# Cek versi
python3 --version
```

</details>

<details>
<summary><b>🟢 Script Tidak Berjalan</b></summary>
<br>

```bash
# Cek posisi direktori
pwd
# Seharusnya: /data/data/com.termux/files/home/nightfury-installer

# Gunakan path lengkap
bash /data/data/com.termux/files/home/nightfury-installer/n.sh
```

</details>

<details>
<summary><b>📊 Hasil Report Terlalu Rumit</b></summary>
<br>

Catatan: Format file nightfury_report_*.txt saat ini masih mentah. Anda bisa mengkustomisasi output dengan mengedit script sesuai kebutuhan. Pull request untuk perbaikan format sangat diterima! 👍

</details>

---

🎨 Preview Output

<div align="center">

```
┌─────────────────────────────────────────────┐
│            NIGHTFURY SCANNER v1.0           │
├─────────────────────────────────────────────┤
│ Target    : https://example.com             │
│ Waktu     : 2026-02-23 13:38:51             │
│ Status    : Scanning Completed ✅           │
├─────────────────────────────────────────────┤
│ Ports Open : 80, 443, 8080                  │
│ Services   : Apache, Nginx                   │
│ Vulnerabilities: 3 found                     │
├─────────────────────────────────────────────┤
│ Report saved: nightfury_report_20260223.txt  │
└─────────────────────────────────────────────┘
```

</div>

---

🤝 Kontribusi

Kami sangat terbuka untuk kontribusi! Berikut cara Anda dapat membantu:

<div align="center">

Cara Deskripsi
🐛 Laporkan Bug Buat issue dengan template yang tersedia
💡 Saran Fitur Diskusikan ide di Discussions
📝 Perbaiki Dokumentasi Bantu perjelas panduan
🔧 Pull Request Kirim perbaikan kode

</div>

---

📊 Statistik Proyek

<div align="center">

https://api.star-history.com/svg?repos=zyraaatod/nightfury-installer&type=Date

</div>

---

📝 Lisensi

<div align="center">

MIT License © 2024 zyraaatod

Dipersilahkan untuk menggunakan, memodifikasi, dan mendistribusikan kembali

</div>

---