# DefaceGeneratorNCS

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](#license)  
[![Version](https://img.shields.io/badge/version-1.0.0-brightgreen)](#)

## 🔥 Deskripsi Singkat  
**DefaceGeneratorNCS** adalah tool berbasis web UI/UX modern untuk membuat halaman deface secara **otomatis, responsif, dan profesional**. Ideal digunakan sebagai generator deface elite untuk kebutuhan pentest dan demonstrasi keamanan.

## ⭐ Fitur Utama  

| Fitur                      | Deskripsi |
|---------------------------|-----------|
| ✏️ **Template Generator**         | Pilihan template HTML elite dan modern untuk halaman deface |
| 🎨 **Kustomisasi Dinamis**       | Edit teks, judul, warna, gambar background langsung via UI |
| 🖼️ **Live Preview**             | Lihat tampilan hasil secara real-time saat kustomisasi |
| 🔧 **Ekspor HTML Satu Klik**     | Download halaman deface dalam satu file `.html` siap host |
| 🌐 **UI/UX Responsif**          | Desain mobile-friendly dan desktop-ready |
| 🧩 **Integrasi Script Ringan**   | Support custom CSS dan JS eksternal |
| 🛡️ **Keamanan Minimal**          | Sanitasi input pengguna untuk mencegah XSS dan kode berbahaya |
| 📂 **Output Rapi & Terstruktur** | HTML hasil kustomisasi tersusun bersih dan mudah modifikasi |

## 🚀 Instalasi & Persyaratan  

1. **Clone repository**  
   ```bash
   git clone https://github.com/RamaFounderNCS/DefaceGeneratorNCS.git
   cd DefaceGeneratorNCS
   ```
2. **Setup environment (opsional)**  
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
3. **Persiapan `.env` (jika diperlukan)**  
   - Salin `.env.example` ke `.env` dan isi variabel: `FLASK_ENV`, `SECRET_KEY`, dll.
4. **Migrasi/pembuatan database** (jika ada)  
   ```bash
   flask db upgrade
   ```
5. **Jalankan aplikasi**  
   ```bash
   flask run --host=0.0.0.0 --port=5000
   ```

## 🛠️ Cara Menggunakan  

1. Akses `http://localhost:5000` di browser
2. Masuk ke menu **Generator**
3. Pilih template deface favorit
4. Edit konten seperti judul, gambar, warna, dll.
5. Lihat preview hasil instan
6. Klik **Download HTML** untuk menyimpan hasil akhir

## 🧩 Kontribusi  

Kontribusi sangat kami hargai:

1. Fork repo  
2. Buat branch (`feature/fitur-baru`)  
3. Commit (`git commit -m "Tambah fitur X"`)  
4. Push & buat Pull Request  
5. Sertakan dokumentasi & test jika memungkinkan  

## 📄 Lisensi  

Tool ini menggunakan **MIT License** — lihat file [LICENSE](LICENSE) untuk detail lengkap.

## 🧑‍💻 Maintainer & Kontak  

- **RamaFounderNCS** – Inisiator & UI/UX Designer  
- **MR.M05T3R** – Architect & Reviewer  

Jika ada masalah atau ide fitur baru, silakan open an issue atau diskusi.  
Untuk komunikasi langsung, hubungi WhatsApp: [MR.M05T3R](https://wa.me/6283846681933)
