# WA Finance Bot Automation

<div align="center">

# 🤖 WhatsApp Personal Finance Bot
**Asisten Keuangan Pribadi Berbasis AI (Gemini) + WhatsApp + Google Sheets**

[![n8n](https://img.shields.io/badge/n8n-Automation-FF6D5A?style=for-the-badge&logo=n8n)](https://n8n.io/)
[![WAHA](https://img.shields.io/badge/WAHA-WhatsApp_API-25D366?style=for-the-badge&logo=whatsapp)](https://waha.devlike.pro/)
[![Google Sheets](https://img.shields.io/badge/Google_Sheets-Database-34A853?style=for-the-badge&logo=googlesheets)](https://workspace.google.com/)
[![Docker](https://img.shields.io/badge/Docker-Container-2496ED?style=for-the-badge&logo=docker)](https://www.docker.com/)

---

Bot WhatsApp otomatis yang berfungsi untuk mencatat setiap pengeluaran dan pemasukan harian kamu langsung ke Google Sheets cukup dengan chat biasa. Dilengkapi dengan **Google Gemini AI Agent**, bot ini juga cerdas dan bisa diajak ngobrol santai! 💬

[Fitur Utama](#-fitur-utama) • [Prasyarat](#-prasyarat-sebelum-mulai) • [Cara Install](#-panduan-instalasi-langkah-demi-langkah) • [Format Sheet](#-format-google-sheets)

</div>

---

## ✨ Fitur Utama

- 📝 **Pencatatan Otomatis dari Chat:** Ketik pesan santai seperti `"nasi goreng 15rb"`, AI akan otomatis mengekstraksi jenis transaksi, kategori, dan nominalnya.
- 📊 **Terintegrasi Google Sheets:** Semua data transaksi tersimpan rapi dan aman di spreadsheet milikmu sendiri.
- 💰 **Cek Saldo Real-Time:** Cukup tanyakan `"saldoku berapa?"` di WA, bot akan membaca data riil dari baris paling bawah spreadsheet.
- 🧠 **Smart AI Agent:** Bot tidak hanya sekadar bot pencatat, tapi juga bisa diajak berdiskusi atau diajak ngobrol topik umum secara alami.

---

## 🧰 Prasyarat Sebelum Mulai

Pastikan di komputer / VPS kamu sudah terinstall software berikut:
1. **Docker & Docker Compose**
2. **Akun Google** (untuk Google Sheets & Google Gemini API)
3. **Nomor WhatsApp** (yang akan dijadikan bot)

---

## 🚀 Panduan Instalasi (Langkah demi Langkah)

### 1. Clone Repositori Ini
Buka terminal kamu dan jalankan perintah:
```bash
git clone [https://github.com/halfaruq/n8n-finance-agent.git](https://github.com/halfaruq/n8n-finance-agent.git)
cd n8n-finance-agent
