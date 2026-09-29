# 🎓 Web Profil & Sistem Kelengkapan Data Mahasiswa - Universitas Pelita Bangsa

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v3-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vanilla JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)

Aplikasi web profil responsif dan sistem pengelolaan kelengkapan data mahasiswa interaktif dengan estetika **Monokrom Minimalis Modern**, dibangun untuk memenuhi tugas **Pemrograman Visual** di **Universitas Pelita Bangsa**.

---

## 🌟 Fitur Utama

- 🎨 **Desain Monokrom Minimalis Modern**: Tampilan visual gelap (*Zinc/Dark theme*) dengan efek *glassmorphism*, aksen batas halus, serta tipografi elegan menggunakan font **Plus Jakarta Sans** dan **Outfit**.
- 📱 **Tata Letak Responsif (Desktop & Mobile)**:
  - **Mode Desktop (`≥ lg`)**: Tata letak *split-screen* modern. Kiri memuat header logo Universitas Pelita Bangsa & form data, kanan memuat foto profil berbingkai melengkung lengkap dengan *Quick Social Badges* di bawahnya.
  - **Mode Mobile (`< lg`)**: Foto profil bertransisi otomatis menjadi **Avatar Melingkar (`rounded-full`)** warna asli di atas header form.
- 🔒 **Data Mahasiswa Terkunci (Read-Only)**:
  - Nama Lengkap: **Aris Maulana**
  - NIM: **312410466**
  - Fakultas: **Fakultas Teknik (FT)**
  - Program Studi: **Teknik Informatika (S1)**
  - Semester / Angkatan: **Semester 5 / Angkatan 2024**
- 📝 **Formulir Data Pelengkap & Akun Sosial Media (Mode Edit)**:
  - Input untuk Email, Nomor WhatsApp, Peminatan Akademik (Dropdown), Jenis Kelas (Reguler/Karyawan), Tempat Tanggal Lahir, Alamat Domisili, dan Portofolio.
  - Section khusus untuk memasukkan tautan akun **GitHub**, **Instagram**, **Threads**, dan **WhatsApp** lengkap dengan icon vektor brand resmi.
- 🔄 **Mode Switcher (Mode Profil ↔ Mode Edit)**:
  - Tampilan awal berupa **Mode Profil** (Teks Rapi & Read-Only).
  - Mengeklik **Edit Data** akan mengubah tampilan menjadi form input aktif dengan tombol **Simpan Perubahan** dan **Batal**.
- 💾 **Data Persistence (`localStorage`)**:
  - Seluruh data pelengkap dan link sosial media tersimpan secara otomatis pada `localStorage` browser (`aris_profile_data`) sehingga tidak hilang saat halaman di-refresh.
- ⚡ **Dynamic Quick Social Badges**:
  - Badges sosial media di bawah foto profil akan memperbarui tautan dan label secara real-time berdasarkan input sosial media yang diisi pengguna.
- 🔔 **Toast Notification System**:
  - Memberikan umpan balik visual (*notification toast*) saat data berhasil disimpan ke browser.

---

## 🛠️ Teknologi & Libs Used

- **HTML5**: Struktur semantic web.
- **Tailwind CSS v3 (via CDN)**: Framework CSS utility-first untuk styling responsif & animasi custom.
- **Vanilla JavaScript (ES6+)**: Logika interaksi UI, manipulasi DOM, dan penyimpanan `localStorage`.
- **Lucide Icons & Official Brand SVGs**: Ikonografi modern monokrom & logo resmi platform sosial media.
- **Google Fonts**: Font *Plus Jakarta Sans* & *Outfit*.

---

## 📂 Struktur Berkas Proyek

```text
Tugas Pemograman Visual/
├── index.html                                  # Halaman web utama
├── foto-aris.jpg                               # Foto profil Aris Maulana
├── logo-universitas-pelita-bangsa-upb-png-svg.webp  # Logo resmi Universitas Pelita Bangsa
├── original-f6896a76278d895813e5619352ee27ba.webp  # Gambar acuan referensi desain
└── README.md                                   # Dokumentasi proyek (GitHub)
```

---

## 🚀 Cara Menjalankan Proyek

Tidak diperlukan instalasi *build step* atau Node.js! Proyek ini berjalan langsung di browser modern.

### Opsi 1: Buka Langsung di Browser
1. *Clone* atau unduh repositori ini.
2. Buka berkas `index.html` langsung menggunakan browser favorit Anda (Google Chrome, Firefox, Edge, Safari, dll).

### Opsi 2: Menggunakan Local Development Server
Jika ingin menjalankan menggunakan server lokal (contoh via Python atau extension VS Code Live Server):

```bash
# Clone repositori
git clone https://github.com/username/tugas-pemrograman-visual.git

# Masuk ke direktori proyek
cd tugas-pemrograman-visual

# Jalankan HTTP server lokal (Python 3)
python3 -m http.server 8080
```
Buka `http://localhost:8080` pada browser Anda.

---

## 👤 Informasi Pengembang

| Detail | Keterangan |
| :--- | :--- |
| **Nama** | **Aris Maulana** |
| **NIM** | **312410466** |
| **Fakultas** | Fakultas Teknik (FT) |
| **Program Studi** | Teknik Informatika (S1) |
| **Semester / Angkatan** | Semester 5 / Angkatan 2024 |
| **Perguruan Tinggi** | Universitas Pelita Bangsa (UPB) |

---

## 📄 Lisensi

Proyek ini dibuat untuk keperluan akademik tugas kuliah Pemrograman Visual di Universitas Pelita Bangsa. Bebas digunakan dan dikembangkan kembali di bawah lisensi [MIT License](LICENSE).
