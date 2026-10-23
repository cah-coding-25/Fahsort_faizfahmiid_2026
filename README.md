# Fahsort (Desktop Edition)
> **Solusi Cerdas Usaha Fotokopi & Percetakan Digital**
> *Diproduksi dan dikembangkan oleh: **Faiz_Fahmi_Id***

---

## 📋 Daftar Isi
1. [Tentang Fahsort](#-tentang-fahsort)
2. [✨ Fitur Unggulan](#-fitur-unggulan)
3. [⚙️ Cara Kerja Algoritma Deteksi Warna](#-cara-kerja-algoritma-deteksi-warna)
4. [🛠️ Panduan Instalasi (Unduh Versi Terbaru)](#-panduan-instalasi-unduh-versi-terbaru)
5. [🖥️ Panduan Penggunaan Bisnis Fotokopi](#%EF%B8%8F-panduan-penggunaan-bisnis-fotokopi)
6. [💡 Tips & Optimalisasi Operasional](#-tips--optimalisasi-operasional)
7. [🤝 Kontribusi & Hak Cipta](#-kontribusi--hak-cipta)

---

## 📖 Tentang Fahsort

**Fahsort** adalah aplikasi berbasis desktop inovatif yang dirancang khusus untuk memecahkan masalah efisiensi utama pada industri usaha fotokopi, digital printing, dan administrasi perkantoran. Masalah klasik yang sering dihadapi oleh operator fotokopi adalah keharusan memilah secara manual satu per satu halaman dokumen PDF yang berisi warna (*full color*) dan halaman yang hanya berisi hitam putih (*grayscale*). Proses manual ini sangat menyita waktu, rawan kesalahan (*human error*), dan menurunkan produktivitas kerja.

Hadir sebagai solusi otomatis, **Fahsort** secara instan melakukan pemindaian cerdas ke setiap halaman dokumen PDF Anda. Menggunakan mesin analisis spektrum piksel RGB tingkat tinggi, aplikasi ini mampu mendeteksi keberadaan elemen warna, stempel toko/instansi, grafik, hingga teks berwarna terkecil sekalipun, kemudian memisahkannya menjadi dua dokumen PDF berkualitas tinggi yang siap dicetak. 

Dengan **Fahsort**, Anda dapat menghemat waktu operasional hingga 90%, mengoptimalkan biaya produksi cetak, dan meningkatkan omzet harian usaha Anda.

---

## ✨ Fitur Unggulan

*   **Pemisahan Halaman Otomatis (Auto-Splitter):** Memisahkan halaman Berwarna dan Hitam Putih secara instan tanpa intervensi manual dari operator.
*   **Analisis Piksel RGB Akurat:** Menggunakan mesin deteksi canggih yang menganalisis spektrum warna pada setiap koordinat halaman untuk memastikan akurasi deteksi yang maksimal.
*   **Pendeteksi Stempel & Grafik Cerdas:** Mampu mengenali stempel berwarna atau logo kecil pada dokumen resmi yang sering kali terlewat oleh mata manusia.
*   **Panel Kontrol Deteksi Kustom:** Menyediakan pengaturan sensitivitas warna, ambang batas proporsi halaman, hingga toleransi *noise* kertas hasil cetak ulang/scan.
*   **Ekspor Output Fleksibel:** Dokumen hasil pemisahan diekstrak langsung dari file asli dengan mempertahankan format vektor, jenis font, ukuran halaman, dan orientasi tetap terjaga 100%. Anda dapat mengunduh:
    *   Dokumen Khusus Berwarna saja
    *   Dokumen Khusus Hitam Putih saja
    *   Kedua file sekaligus dalam format kompresi (ZIP)
*   **Antarmuka Tarik & Lepas (Drag & Drop):** Pengoperasian super mudah, cukup seret file PDF Anda ke dalam aplikasi dan biarkan Fahsort bekerja.

---

## ⚙️ Cara Kerja Algoritma Deteksi Warna

Fahsort dilengkapi dengan **Pengaturan Deteksi Warna** yang dapat dikalibrasi sesuai dengan karakteristik mesin fotokopi dan kebutuhan bisnis Anda. Berikut adalah detail parameter algoritma yang dapat Anda sesuaikan di panel pengaturan:

| Parameter Pengaturan | Deskripsi Fungsi | Rekomendasi Penggunaan |
| :--- | :--- | :--- |
| **Sensitivitas Warna (Ambang Perbedaan RGB)** | Mengatur perbedaan minimum antara kanal warna `|R-G|`, `|G-B|`, dan `|B-R|` agar halaman dapat dianggap sebagai halaman berwarna. Semakin kecil nilainya, semakin sensitif terhadap warna tipis. | **Nilai Standar: 22**.
Turunkan nilai ke arah angka lebih kecil (misal: 18) jika Anda ingin mendeteksi coretan pulpen atau stempel samar. |
| **Ambang Batas Proporsi Halaman (% Luas)** | Persentase minimum luas halaman yang harus terdeteksi memiliki elemen warna agar seluruh halaman tersebut dikelompokkan ke dalam kategori Berwarna. | **Nilai Standar: 0.08%**.
Membantu mengabaikan titik warna mikro yang tidak sengaja muncul akibat bercak dokumen asli. |
| **Toleransi Noise & Kertas Scan Kuning** | Fitur khusus untuk mengabaikan bias warna kertas tua atau hasil *scanner* fotokopi terdahulu yang cenderung agak kekuningan atau memiliki *background noise* kelabu. | **Nilai Standar: 18**.
Mencegah halaman hitam putih yang discan buruk terdeteksi salah sebagai halaman berwarna. |

---

## 🛠️ Panduan Instalasi (Unduh Versi Terbaru)

Untuk memastikan Anda mendapatkan performa terbaik, fitur paling mutakhir, dan perbaikan keamanan terbaru, ikuti langkah-langkah instalasi berikut ini:

1. Buka browser web Anda dan masuk ke repositori resmi aplikasi di GitHub.
2. Navigasikan ke bagian **Releases** yang terletak di sisi sebelah kanan halaman repositori, atau langsung masuk ke menu rilis versi.
3. Di halaman rilis tersebut, Anda akan selalu melihat **Versi Terbaru (Latest Release)** di bagian paling atas.
4. Cari bagian *Assets* di bawah deskripsi rilis versi terbaru tersebut.
5. Unduh file penginstal yang sesuai dengan sistem operasi Anda (contoh: `Fahsort-Setup-x64.exe` untuk sistem operasi Windows).
6. Setelah proses pengunduhan selesai, buka file installer tersebut dan ikuti instruksi pemasangan di layar komputer Anda hingga selesai.
7. Aplikasi **Fahsort (Desktop Edition)** siap digunakan langsung dari pintasan desktop Anda!

---

## 🖥️ Panduan Penggunaan Bisnis Fotokopi

1.  **Impor File:** Tarik file PDF yang ingin dipilah dan lepas tepat di area bertuliskan **"Tarik & Lepas File PDF ke Sini"**.
2.  **Proses Analisis:** Aplikasi akan membaca secara otomatis semua halaman (Contoh: Semua Halaman: 51). Sistem akan langsung menampilkan hasil kategorisasi secara *real-time*:
    *   Halaman Berwarna (Contoh: 47 halaman)
    *   Halaman Hitam Putih (Contoh: 4 halaman)
    *   Perlu Diperiksa (Jika ada halaman ambigu)
3.  **Verifikasi Visual:** Anda dapat melihat *thumbnail* pratinjau di panel sebelah kiri untuk memastikan label `BERWARNA` atau `HITAM PUTIH` sudah sesuai dengan keinginan Anda.
4.  **Ekspor Dokumen:** Klik tombol **"Unduh Berwarna"** untuk mencetak halaman warna di mesin printer warna, dan klik **"Unduh Hitam Putih"** untuk mencetaknya secara ekonomis di mesin fotokopi/printer laser monokrom.

---

## 💡 Tips & Optimalisasi Operasional

*   **Kalibrasi untuk Dokumen Resmi:** Saat memproses dokumen legalitas hukum atau korporat yang menggunakan stempel resmi, pastikan nilai *Sensitivitas Warna* berada pada angka rendah untuk menjamin stempel biru atau merah instansi terdeteksi sempurna dan tidak tercetak hitam putih.
*   **Dokumen Hasil Scan:** Jika dokumen masukan Anda adalah hasil scan buku tua yang kertasnya mulai menguning, naikkan nilai *Toleransi Noise & Kertas Scan Kuning* ke angka 23-25 agar background kuning kertas tidak dibaca sebagai elemen grafis berwarna.

---

## 🤝 Kontribusi & Hak Cipta

Aplikasi ini dikembangkan secara penuh oleh **Faiz_Fahmi_Id**. Hak cipta dilindungi undang-undang. Jika Anda menemukan *bug*, kendala sistem, atau memiliki ide pengembangan fitur silakan buat laporan melalui menu *Issues* pada repositori GitHub resmi kami.

*Terima kasih telah menggunakan Fahsort untuk memajukan efisiensi bisnis digital printing Anda!*
