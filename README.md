# Budget Wise - Aplikasi Perencana Keuangan (React Native)

**Budget Wise** adalah aplikasi mobile perencana keuangan yang dirancang untuk membantu pengguna mengelola keuangan pribadi dengan lebih cerdas dan mudah. Ambil alih kendali atas pemasukan dan pengeluaran Anda, buat anggaran yang efektif, dan capai tujuan finansial Anda.

Proyek ini merupakan hasil dari **Ujian Akhir Semester (UAS) mata kuliah Mobile Cross-Platform**. Tujuan utamanya adalah untuk menerapkan konsep pengembangan aplikasi mobile secara menyeluruh, mulai dari perancangan hingga implementasi fungsionalitas, menggunakan React Native dan Supabase.

## Unduh Aplikasi (.apk)

Anda bisa mengunduh dan mencoba aplikasi versi rilis langsung melalui tautan berikut:

➡️ **[Unduh Budget Wise APK dari Google Drive](https://drive.google.com/file/d/1y3wcmpvNRDBC1CpprK1GKltn3IkyUSCj/view?usp=sharing)**

## Fitur Utama
-   💸 **Manajemen Transaksi Lengkap**: Catat, edit, hapus, dan filter pemasukan/pengeluaran dengan kategori yang bisa disesuaikan.
-   📊 **Anggaran & Peringatan Cerdas**: Buat budget per kategori, monitor progres secara visual (🟢🟡🔴), dan dapatkan notifikasi otomatis saat mendekati atau melebihi batas.
-   🎯 **Sistem Tantangan Menabung**: Ikuti tantangan menabung yang ada atau buat tantangan custom untuk memotivasi pencapaian tujuan finansial.
-   📈 **Analisis & Visualisasi Data**: Pahami kebiasaan finansial melalui dashboard interaktif, grafik tren, dan peta lokasi pengeluaran (*expense map*).
-   🔐 **Keamanan Berlapis**: Login aman dengan email/password, dukungan autentikasi biometrik, dan fitur *privacy mode* untuk menyembunyikan saldo.
-   ☁️ **Backup & Notifikasi**: Sistem backup otomatis/manual dan notifikasi cerdas untuk pengingat harian, update budget, dan pencapaian tantangan.

## Teknologi yang Digunakan
* **Framework**: **React Native**
* **Bahasa**: **JavaScript / TypeScript**
* **Backend & Database**: **Supabase**
    * **PostgreSQL Database**: Untuk menyimpan semua data transaksi, budget, dan pengguna.
    * **Supabase Auth**: Mengelola autentikasi pengguna, termasuk login via email/password.
    * **Realtime APIs**: Untuk sinkronisasi data secara langsung antar perangkat.
* **Library Pendukung Utama**:
    * **React Navigation**: Untuk manajemen navigasi dan perpindahan antar layar.
    * **React Native Maps**: Untuk menampilkan fitur peta lokasi pengeluaran (*Expense Map*).
    * **React Native Chart Kit**: Untuk membuat grafik dan chart visualisasi data keuangan.
    * **React Native Biometrics**: Untuk mengimplementasikan fitur login dengan sidik jari atau wajah.

## Cara Penggunaan Aplikasi
### Memulai Aplikasi
* **Registrasi**: Masukkan email dan password (minimal 6 karakter), lalu tap tombol **"Daftar"**.
* **Login**: Gunakan email dan password yang terdaftar. Anda juga dapat mengaktifkan dan menggunakan autentikasi biometrik (sidik jari/wajah) dari menu pengaturan.

### Navigasi Utama
* 🏠 **Dashboard**: Menampilkan ringkasan saldo, transaksi terbaru, dan status budget.
* 💰 **Transaksi**: Halaman untuk melihat seluruh riwayat transaksi. Dilengkapi fitur filter dan pencarian.
* 📊 **Budget**: Mengelola semua anggaran yang telah Anda buat dan memonitor progresnya.
* 🎯 **Tantangan**: Berisi daftar tantangan menabung yang bisa diikuti atau dibuat sendiri.
* ⚙️ **Lainnya**: Akses ke menu Pengaturan, Profil Pengguna, Keamanan, dan fitur lainnya.

### Mengelola Transaksi
* **Tambah Transaksi**: Tap ikon **"+"** di menu navigasi, pilih jenis (Pemasukan/Pengeluaran), lalu isi detail seperti nominal, kategori, dan deskripsi. Tap **"Simpan"**.
* **Edit & Hapus**: Pada daftar transaksi, tap pada salah satu item untuk melihat detail. Gunakan ikon *edit* untuk mengubah atau ikon *hapus* untuk menghilangkannya.
* **Filter Transaksi**: Gunakan opsi di bagian atas halaman Transaksi untuk memfilter berdasarkan tanggal, kategori, atau mencari berdasarkan deskripsi.

### Manajemen Budget
* **Buat Budget**: Masuk ke tab **Budget**, tap **"Tambah Budget"**, lalu isi nama, kategori, jumlah, dan periode (misal: Bulanan).
* **Monitor Progress**: Setiap budget akan menampilkan progress bar dengan status warna:
    * 🟢 **On Track**: Pengeluaran masih aman.
    * 🟡 **Warning**: Pengeluaran sudah mencapai 80% dari batas.
    * 🔴 **Over Budget**: Pengeluaran telah melebihi batas.
* **Peringatan Otomatis**: Aplikasi akan mengirim notifikasi saat budget mencapai 80% dan saat sudah terlampaui.

### Sistem Tantangan
* **Pilih Tantangan**: Jelajahi daftar tantangan yang tersedia di tab **Tantangan**, pilih yang Anda suka, dan tap **"Ikuti Tantangan"**.
* **Buat Tantangan Sendiri**: Gunakan opsi **"Buat Tantangan"**, lalu tentukan nama, target nominal, dan durasi.
* **Update Progress**: Untuk setiap tantangan aktif, Anda dapat memperbarui progress pencapaian Anda secara manual.

### Analisis Keuangan
* **Laporan di Dashboard**: Cek total saldo, ringkasan pemasukan/pengeluaran bulan ini, dan penggunaan budget secara cepat.
* **Grafik Visual**: Lihat tren pemasukan vs. pengeluaran, perbandingan pengeluaran per kategori, dan performa budget dalam bentuk grafik.
* **Expense Map**: Fitur untuk melihat visualisasi lokasi geografis di mana saja Anda melakukan pengeluaran (jika data lokasi diaktifkan).

## Keterangan Tambahan
### Fitur Keamanan
* **Biometric Login**: Aktifkan melalui menu **Pengaturan > Keamanan** untuk login lebih cepat dan aman.
* **Privacy Mode**: Sembunyikan nominal saldo dan detail transaksi di dashboard dengan satu tombol untuk menjaga privasi Anda di tempat umum.
* **Auto Logout**: Atur durasi logout otomatis (1-30 menit) untuk keamanan tambahan jika aplikasi tidak digunakan.

### Backup & Restore
* **Auto Backup**: Atur frekuensi backup data otomatis (harian, mingguan, atau bulanan) ke cloud.
* **Manual Backup**: Lakukan backup kapan saja melalui **Pengaturan > Backup & Restore > "Backup Sekarang"**.
* **Restore Data**: Pulihkan data dari riwayat backup yang tersimpan atau unggah file backup secara manual.

### Notifikasi
* Atur jenis notifikasi yang ingin Anda terima melalui **Pengaturan > Notifikasi**.
* Dapatkan peringatan budget, pengingat pencatatan harian, rangkuman mingguan, serta update dari tantangan menabung Anda.

## Tautan Penting
-   **Laporan Proyek Lengkap**: [Lihat Laporan di Google Docs](https://docs.google.com/document/d/1KYdBS9cgr81RGXawtq6-iBWXcn8XGmpwa__3UokjsIk/edit?usp=sharing)
-   **Repository**: [Lihat Kode di GitHub](https://github.com/batarah07d0/Budget-Wise-MCP-Project)
---
