# Graber Keyword Domain V2

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Python](https://img.shields.io/badge/python-3.x-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS%20%7C%20Termux-lightgrey)
![Stars](https://img.shields.io/github/stars/LikeEx01/KewordGraber?style=social)
![Issues](https://img.shields.io/github/issues/LikeEx01/KewordGraber)
![Last Update](https://img.shields.io/github/last-commit/LikeEx01/KewordGraber)

---

![Preview](https://b.top4top.io/p_34800kvez4.jpg)

---

## Deskripsi

**Graber Keyword Domain Finder V2** adalah tool Python untuk mencari domain berdasarkan keyword melalui situs [Website Informer](https://website.informer.com/). Program ini akan menampilkan hasil secara real-time di terminal dan menyimpannya langsung ke file `hasil_domain.txt`. Cocok untuk pencarian data OSINT, digital footprint, atau riset web publik berdasarkan kata kunci.

---

## Fitur Utama

- 🔍 Pencarian domain otomatis dari keyword melalui Website Informer.
- 🎯 Filter domain berdasarkan ekstensi (misal: `.id`, `.ac.id`, `.sch.id`).
- 🌈 Output terminal berwarna agar mudah dibaca.
- 💾 Menyimpan hasil domain langsung ke `hasil_domain.txt` secara real-time (langsung saat ditemukan).
- 🧠 Menghindari duplikasi domain.
- 🎨 Tampilan banner estetis di semua terminal (Windows, Linux, Termux, macOS).
- 🛡️ User-Agent disamarkan untuk menghindari blokir server.

---

## Persyaratan

- Python **3.x**
- Library Python:
  - `requests`
  - `beautifulsoup4`

---

## Dukungan Platform

✅ Windows  
✅ Linux (Ubuntu, Debian, Arch)  
✅ Termux (Android)  
✅ macOS  

---

## Instalasi

### 📱 Termux / Android

```bash
pkg update && pkg upgrade -y
pkg install git python -y
pip install requests beautifulsoup4
git clone https://github.com/LikeEx01/KewordGraber.git
cd KewordGraber
python graber.py
```

### 💻 Windows (CMD / PowerShell)

1. Install Python dari https://python.org
2. Buka Command Prompt atau PowerShell:

```bash
pip install requests beautifulsoup4
git clone https://github.com/LikeEx01/KewordGraber.git
cd KewordGraber
python graber.py
```

### 🐧 Linux / Ubuntu / Debian / Arch

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install git python3 python3-pip -y
pip3 install requests beautifulsoup4
git clone https://github.com/LikeEx01/KewordGraber.git
cd KewordGraber
python3 graber.py
```

---

## Penggunaan

1. Buat file `keyword.txt` yang berisi daftar keyword, satu per baris. Contoh:

```
sekolah
universitas
dinas pendidikan
pemerintah kabupaten
```

2. Jalankan program:

```bash
python graber.py
```

3. Masukkan:
   - Nama file keyword (`keyword.txt`)
   - Filter domain seperti `.id`, `.ac.id` (atau kosongkan untuk semua)

4. Program akan berjalan dan menampilkan domain yang ditemukan secara real-time, serta langsung menyimpannya ke `hasil_domain.txt`.

---

## Contoh Output

```bash
[INFO] https://universitas-jember.ac.id
[INFO] https://pemerintahkota-bogor.go.id
[INFO] https://rsud.bekasikab.go.id
```

---

## Output

- 📄 **hasil_domain.txt** — File berisi daftar domain yang ditemukan dan disimpan saat itu juga (tanpa duplikat).

---

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](https://opensource.org/licenses/MIT).

---

## Penafian

> ⚠️ **Peringatan:** Gunakan tools ini hanya untuk keperluan edukasi, riset, dan pengujian yang sah. Penulis tidak bertanggung jawab atas penyalahgunaan oleh pihak ketiga.

---

## Kontak

- GitHub: [LikeEx01](https://github.com/LikeEx01)
- Telegram: [LikeEx01](https://t.me/usernamee13371)
- Repo: [https://github.com/LikeEx01/KewordGraber](https://github.com/LikeEx01/KewordGraber)

---

## 📢 Bergabung ke Channel WhatsApp!

Ingin update fitur terbaru, diskusi, atau berbagi teknik OSINT dan keyword grabber lainnya?

➡️ **Join Channel WhatsApp kami sekarang!**  
📲 [https://whatsapp.com/channel/0029VaudLHc7YSd9S9c9800c](https://whatsapp.com/channel/0029VaudLHc7YSd9S9c9800c)

---

**Terima kasih telah menggunakan Graber Keyword Domain Finder V2!**  
Jangan lupa ⭐ repo ini jika kamu terbantu 👍
