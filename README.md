# 🍽️ Sistem Pemesanan Makanan di Kantin (SUKA-Canteen)

## 📖 Deskripsi Singkat
Sistem ini memungkinkan mahasiswa/siswa untuk memesan makanan di kantin melalui website sebelum datang ke kantin, sehingga mereka tidak perlu antre lama. Pemesanan dapat dilakukan berdasarkan menu harian yang disediakan oleh kantin. Selain itu, sistem ini memungkinkan pemilik kantin untuk mendaftarkan usaha mereka dan mengelola menu makanan serta pesanan secara mandiri.

---

## 🎯 Apa Tujuan Sistem Dibuat?
- ✅ Mengurangi antrean di kantin
- ✅ Memudahkan pengelola kantin dalam mengelola stok makanan
- ✅ Meningkatkan efisiensi dalam penyajian makanan
- ✅ Memudahkan pemilik kantin untuk mendaftarkan usaha mereka
- ✅ Memberikan variasi pilihan kantin kepada pengguna
  
## 🔥 Fitur Utama

### 👥 Fitur untuk Pengguna (Mahasiswa/Siswa)
🔹 **Registrasi & Login** → Pengguna bisa membuat akun untuk memesan makanan  
🔹 **Melihat Daftar Kantin** → Menampilkan semua kantin yang terdaftar  
🔹 **Melihat Menu Harian** → Menampilkan daftar makanan dari masing-masing kantin  
🔹 **Melakukan Pemesanan** → Pengguna bisa memilih makanan dan menentukan waktu pengambilan  
🔹 **Pembayaran Online/Opsi COD** → Bisa pakai e-wallet, transfer bank, atau bayar di tempat  
🔹 **Riwayat Pemesanan** → Menampilkan daftar pesanan yang pernah dibuat  

### 🏪 Fitur untuk Pemilik Kantin
🔹 **Registrasi & Login sebagai Pemilik Kantin** → Pemilik dapat membuat akun untuk mengelola kantinnya  
🔹 **Mendaftarkan Kantin** → Menambahkan nama kantin, lokasi, jam operasional, dan informasi tambahan  
🔹 **Mengelola Menu** → Menambahkan, mengedit, dan menghapus menu makanan dan minuman  
🔹 **Melihat Daftar Pesanan** → Daftar pesanan masuk, beserta statusnya  
🔹 **Update Status Pesanan** → Misalnya *sedang diproses* atau *siap diambil*  
🔹 **Laporan Harian/Bulanan** → Melihat jumlah pesanan dan keuntungan  

---

## 💻 Instalasi
```bash
# Clone repositori
git clone https://github.com/username/SUKA-Canteen.git

# Masuk ke direktori proyek
cd SUKA-Canteen

# Instal dependensi
npm install

# Konfigurasi lingkungan
cp .env.example .env
# Edit file .env sesuai kebutuhan

# Mulai server pengembangan
npm run dev
```

## 🔄 Bagaimana Alur Dari Sistem Bekerja?
1️⃣ **Pemilik kantin mendaftar dan login** ke sistem  
2️⃣ **Pemilik menambahkan informasi kantin** (nama, lokasi, jam operasional)  
3️⃣ **Pemilik menambahkan menu makanan dan harga**  
4️⃣ **Pengguna login** ke sistem  
5️⃣ **Pengguna melihat daftar kantin yang tersedia**  
6️⃣ **Pengguna memilih kantin lalu melihat menu makanan yang ditawarkan**  
7️⃣ **Pengguna melakukan pemesanan dari kantin tertentu**  
8️⃣ **Pemilik kantin menerima pesanan dan memperbarui statusnya**  
9️⃣ **Pengguna datang ke kantin untuk mengambil makanannya tanpa antre lama**  

---

## 👥 Tim Pengembang
Proyek ini dikembangkan oleh tim kecil yang terdiri dari 3 orang. Kami menggunakan pendekatan Extreme Programming (XP) untuk menjaga kolaborasi, kualitas kode, dan kecepatan pengembangan.

| Posisi | Anggota Tim | Tanggung Jawab |
|--------|-------------|----------------|
| 🎯 **Project Manager / Customer Representative** | Bayu Wicaksono | • Merancang kebutuhan sistem berdasarkan masukan dari pengguna<br>• Menentukan prioritas fitur dan mengatur backlog user stories<br>• Berkomunikasi aktif dengan pihak pengguna untuk validasi hasil<br>• Membantu dalam pengujian fungsional dan pengumpulan feedback |
| ⚙️ **Backend Developer** | Salman Alfauzi Asngari | • Membangun sistem backend: autentikasi, manajemen pesanan, dan database<br>• Menerapkan Test-Driven Development (TDD) dan menulis unit test<br>• Mengelola struktur database dan API endpoint untuk frontend<br>• Mendukung integrasi pembayaran digital dan sistem notifikasi |
| 🎨 **Frontend Developer** | Aisyah Ayudia Inara | • Merancang dan mengembangkan antarmuka pengguna (UI/UX)<br>• Mengintegrasikan UI dengan API backend<br>• Fokus pada pengalaman pengguna untuk kemudahan penggunaan<br>• Melakukan pengujian antarmuka dan optimasi performa frontend |

## 📋 Konvensi Pengembangan
Fusce eleifend metus ac metus commodo, vel ultrices nisi elementum. Nulla facilisi. Maecenas tincidunt justo vel felis sagittis, vel elementum metus dictum. Sed rhoncus dui vel magna placerat, vel ultricies ex imperdiet. Nullam euismod magna vel risus congue, ac faucibus odio tincidunt.

## 🗓️ Roadmap
- **Q2 2025** 🌱: Maecenas tincidunt justo vel felis sagittis
- **Q3 2025** 🌿: Sed rhoncus dui vel magna placerat
- **Q4 2025** 🌳: Vel ultricies ex imperdiet nullam euismod
- **Q1 2026** 🌲: Magna vel risus congue ac faucibus odio

## 🤝 Kontribusi
Donec at sapien vel elit consequat bibendum. Fusce eleifend metus ac metus commodo, vel ultrices nisi elementum. Nulla facilisi. Maecenas tincidunt justo vel felis sagittis, vel elementum metus dictum.

## 📜 Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE):

```
MIT License

Copyright (c) 2025 SUKA-Canteen

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 📞 Kontak
Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Donec at sapien vel elit consequat bibendum.
