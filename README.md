<div align="center">
  
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Awesome%20Project&fontSize=60&fontColor=fff&animation=twinkling&desc=Make%20Something%20Amazing&descSize=20&descAlignY=70"/>


<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"/>

</div>

---

<div align="center">
  
# <img  src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Bat.png" alt="Bat" width="35" height="35" />

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

## ⚡ Quick Start


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


## 📋 Prerequisites

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

 1 Buka NightFury

```bash
cd $HOME/nightfury-max
./run.sh
```

 2 Masukkan target URL saat diminta

```
[→] Enter target URL/IP: https://contoh-website.com
```

 3 Tunggu proses scanning (durasi tergantung target)

 4 Lihat hasil di terminal atau file report

---

## 📁 Struktur Proyek

```
📦 nightfury-max/
├── 📄 run.sh                  # Main installer script
├── 📄 nightfury_max.py        # Python installer script
├── 📄 quick.txt               # Dokumentasi cepat
├── 📄 nightfury_report_*.txt  # Hasil scanning (auto-generated)
```

---

## ⚠️ Troubleshooting

<div align="center">

Solusi Cepat untuk Masalah Umum

</div>

<details>
<summary><b> Permission Denied</b></summary>
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
<summary><b> Python Not Found</b></summary>
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
<summary><b> Script Tidak Berjalan</b></summary>
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
<summary><b> Hasil Report Terlalu Rumit</b></summary>
<br>

Catatan: Format file nightfury_report_*.txt saat ini masih mentah. Anda bisa mengkustomisasi output dengan mengedit script sesuai kebutuhan. Pull request untuk perbaikan format sangat diterima! 👍

</details>

---

## 🎨 Preview Output

<div align="left">

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

## 📊 Statistik Proyek

<div align="center">

[![Star History Chart](https://api.star-history.com/svg?repos=zyraaatod/nightfury-installer&type=Date&theme=dark)](https://star-history.com/#zyraaatod/nightfury-installer&Date)

</div>

---
## Repository Card
<div align="center">
  
![GitHub release (latest by date)](https://img.shields.io/github/v/release/zyraaatod/nightfury-installer?style=for-the-badge&color=00FFAA)
![GitHub Release Date](https://img.shields.io/github/release-date/zyraaatod/nightfury-installer?style=for-the-badge&color=00AAFF)
![GitHub last commit](https://img.shields.io/github/last-commit/zyraaatod/nightfury-installer?style=for-the-badge&color=FF6B6B)

![GitHub commits since latest release](https://img.shields.io/github/commits-since/zyraaatod/nightfury-installer/latest?style=for-the-badge&color=9B59B6)
![GitHub contributors](https://img.shields.io/github/contributors/zyraaatod/nightfury-installer?style=for-the-badge&color=FFD700)
![GitHub issues](https://img.shields.io/github/issues/zyraaatod/nightfury-installer?style=for-the-badge&color=FF4444)

</div>


## 📝 Lisensi

<div align="center">

MIT License © 2024 zyraaatod

Dipersilahkan untuk menggunakan, memodifikasi, dan mendistribusikan kembali

</div>

---
