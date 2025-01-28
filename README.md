# Ransomware Simulator with GUI
Ini adalah simulasi ransomware dengan antarmuka grafis (GUI) yang dibuat untuk tujuan edukasi. Ransomware ini mengenkripsi file menggunakan AES dan meminta pengguna untuk menyelesaikan tantangan matematika sebelum melanjutkan.

---

## Fitur:

- GUI sederhana dengan pesan ransomware dan tombol untuk tantangan matematika.

- Enkripsi file menggunakan AES.

- Mode Dummy untuk simulasi tanpa merusak file asli.

- Penyalinan ransomware ke drive lain atau folder berbagi.

---

## Struktur Proyek
```
/Ransomware-Simulator
│
├── /src
│   ├── RansomGUI.h         # Header untuk GUI
│   ├── RansomGUI.cpp       # Implementasi logika GUI
│   ├── Main.cpp            # Implementasi ransomware
│
└── /ransomware_log.txt     # File log aktivitas ransomware
```
---

## Cara Penggunaan

1. Clone repository ini:
```bash
git clone https://github.com/username/Ransomware-Simulator.git
cd Ransomware-Simulator
```

2. Persiapkan lingkungan:
 - Pastikan Anda memiliki Visual Studio atau kompiler C++ yang mendukung WinAPI.
 - Install library OpenSSL untuk enkripsi AES.

3. Bangun dan jalankan proyek:
 - Buka proyek di Visual Studio dan bangun proyek.
 - Jalankan Main.cpp untuk melihat antarmuka grafis ransomware yang meminta tantangan matematika.
 - 
4. Mode Dummy:
Untuk menggunakan mode dummy (simulasi tanpa mengenkripsi file), ubah variabel dummyMode di Main.cpp menjadi true.

---

## Penting!

Hanya untuk tujuan edukasi. Jangan jalankan pada sistem nyata tanpa izin eksplisit.

Gunakan mesin virtual (VM) untuk menguji proyek ini agar data Anda aman.

Program ini akan mengenkripsi file di direktori yang ditentukan dalam kode (default: C:\\Users\\User\\Documents).

---

## Lisensi

Proyek ini dilisensikan di bawah MIT License - lihat file LICENSE untuk detailnya.
