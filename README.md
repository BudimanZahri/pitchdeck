## Aplikasi Web

### Fitur untuk User (Publik)
1. **Beranda**
   - Menampilkan informasi utama, banner, dan navigasi ke fitur-fitur penting.
2. **Tentang Kami**
   - Menjelaskan visi, misi, dan informasi tentang PMPS/DLH.
3. **Kegiatan**
   - Galeri kegiatan atau event terkait pengelolaan sampah, lengkap dengan deskripsi.
4. **Edukasi**
   - Artikel dan video edukasi tentang pengelolaan sampah dan daur ulang.
5. **Panduan**
   - Tutorial langkah-langkah untuk menggunakan aplikasi, dari registrasi hingga transaksi.
6. **Mitra**
   - Menampilkan daftar mitra kerja sama, seperti perusahaan daur ulang atau organisasi lingkungan.

### Fitur untuk Admin (Setelah Login)
1. **Dashboard**
   - Statistik/Reportin:
     - Jumlah user aktif.
     - Data pelanggan.
     - Jumlah pengunjung website.
     - Total reward yang telah ditransfer.
     - Total sampah yang diterima (berat/volume).
2. **Manajemen Sampah**
   - **Data Sampah:**
     - Menambahkan/mengedit data barang (misal: botol plastik biru).
     - Harga per satuan (gram/kg).
     - UOM (Unit of Measurement).
   - **Kategori Sampah:**
     - Membuat kategori baru (plastik, kaca, besi, dll).
   - **Satuan Ukur:**
     - Menentukan dan mengelola konversi satuan (gram <-> kg).
3. **Transaksi**
   - Input data transaksi dari user:
     - Nama user yang submit.
     - Barang yang disubmit dan beratnya.
   - **Konfirmasi Transaksi:**
     - Tombol *Confirm* untuk validasi.
     - Tombol *Transfer* untuk memasukkan nominal reward yang dikirimkan (pop-up konfirmasi).
     - Rekam metode pembayaran.
   - **Pencatatan Otomatis:**
     - Data transfer otomatis dicatat dalam log.
4. **Peta dan Lokasi**
   - Mengupdate lokasi TPS, TPA, atau tempat daur ulang lainnya secara real-time.
   - Lokasi ditampilkan di peta yang bisa diakses oleh user.
5. **Pengguna**
   - Membuat akun admin baru.
   - Melihat/mengelola data akun admin dan user.

---

## Aplikasi Mobile

### Fitur untuk User
1. **Chatbot (AskResikel)**
   - Membantu user menjawab pertanyaan seputar:
     - Cara menggunakan aplikasi.
     - Cara pengelolaan sampah.
2. **Image Classify**
   - Deteksi kategori sampah berdasarkan gambar yang diunggah oleh user.
   - Memberikan informasi detail seperti nama kategori.
3. **Lapor Sampah**
   - Formulir untuk melaporkan lokasi sampah yang perlu ditindaklanjuti.
   - Fitur geotagging untuk mengirim lokasi GPS.
   - Notifikasi status laporan: *Diterima, Sedang Diproses, Selesai*.
