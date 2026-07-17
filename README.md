<div align="center">

<!-- GIF DI TENGAH ATAS -->
<img src="https://media.giphy.com/media/V4NSR1NG2p0KeJJyr5/giphy.gif" width="600" alt="Cybersecurity Banner GIF">

# 🛠️ Project Name

<p align="center">
  <img src="https://img.shields.io/badge/Category-Social%20Engineering-red?style=for-the-badge&logo=hackthebox" alt="Social Engineering">
  <img src="https://img.shields.io/badge/Category-Spam%20Tools-orange?style=for-the-badge&logo=maildotru" alt="Spam Tools">
</p>

<p align="center">
  A highly optimized Social Engineering & Spam Framework built with modular architecture and runtime protection.
</p>

---
</div>

## 📂 Project Structure

Berikut adalah visualisasi komponen utama dari tools ini:

*   **`main.py`** & **`main_engine.py`** — *Entry point* utama aplikasi dan mesin eksekusi inti untuk serangan spam/social engineering.
*   **`handlers.py`** & **`utils.py`** — Mengatur logika alur kerja, interaksi CLI, dan fungsi pembantu (*helper functions*).
*   **`targets.py`** & **`useragents.py`** — Manajemen target serangan dan rotasi User-Agent untuk menghindari proteksi/deteksi *rate-limiting*.
*   **`license.py`** & **`license_enc.py`** — Modul enkripsi dan validasi lisensi penggunaan script.
*   **`main_protected.py`** & **`protected_script.py`** — Lapisan proteksi tambahan untuk mengamankan *source code* dari modifikasi ilegal.

---

## 🚀 Getting Started

### Prerequisites

Pastikan perangkat kamu sudah terinstal Python 3.x dan Git.

### Installation

```bash
# Clone repositori
git clone [https://github.com/username/project-name.git](https://github.com/username/project-name.git)

# Masuk ke folder project
cd project-name

# Install seluruh library python yang dibutuhkan
pip install -r requirements.txt
