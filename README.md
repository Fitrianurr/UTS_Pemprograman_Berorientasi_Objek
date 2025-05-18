# UTS_Pemprograman_Berorientasi_Objek
# 🍽️ Sistem Pemesanan Makanan UTS Java

Sistem ini merupakan aplikasi berbasis Java Console yang dibuat untuk memenuhi tugas Ujian Tengah Semester (UTS) pada mata kuliah Pemprograman Berorientasi Objek dengan Dosen Pengampu Cahyo Hermanto, M. Kom.

## 📋 Fitur Utama

- Input nama pemesan
- Pemesanan menu makanan dan minuman
- Pilihan metode pembayaran (Tunai / Kartu)
- Fitur diskon 10%
- Pembatalan pesanan
- Pencetakan struk
- Reset pesanan setelah dibatalkan

## 🧱 Struktur File

| File               | Deskripsi                                                                 |
|--------------------|--------------------------------------------------------------------------|
| `Main.java`        | Program utama (menu interaktif pengguna)                                 |
| `Menu.java`        | Kelas abstrak untuk item makanan/minuman                                 |
| `Makanan.java`     | Subkelas dari `Menu`, mewakili item makanan                              |
| `Minuman.java`     | Subkelas dari `Menu`, mewakili item minuman                              |
| `ItemPesanan.java` | Menyimpan informasi tiap item yang dipesan                               |
| `Pesanan.java`     | Menyimpan keseluruhan pesanan, termasuk diskon dan metode cetak struk    |

## 🚀 Cara Menjalankan Program
##💡 Prasyarat
- Sudah menginstall **Java JDK** (versi 8 atau lebih baru)
- Terminal atau command prompt tersedia

## 🔧 Langkah-langkah Menjalankan:
1. Buka terminal, masuk ke direktori project:
   ```bash
   cd path/ke/folder/UTS_SistemPemesananMakanan
2. Compile semua file Java di dalam folder uts_sistempemesananmakanan
3. Jalankan program utama (Main.java)
⚠️ Karena program menggunakan package uts_sistempemesananmakanan, maka saat compile dan run, wajib menyertakan nama package tersebut.

##🧠 Catatan Logika
1. Setelah pesanan dibatalkan, pesanan akan otomatis di-reset. Pengguna bisa memesan lagi dan mencetak struk seperti biasa.
2. Diskon hanya berlaku jika pengguna mengaktifkannya sebelum mencetak struk.
3. Program akan menolak mencetak struk jika belum ada nama pemesan, metode pembayaran, atau pesanan kosong.

##✍️ Pembuat
1. Ai Puji Saripah
2. Astrid Aulia
3. Fitria Nurhayati
4. Galib Sajad
5. Khairan Fathan
6. Rifda Marini Juwita

##🖼️ Tampilan Menu Program
![Tampilan Awal](https://github.com/user-attachments/assets/10836299-801d-4a19-9543-e106de8370b5)

##🖼️ Tampilan Cetak Struk
![Tampilan cetak Struk](https://github.com/user-attachments/assets/45a0ad98-0afd-43f1-b93b-0c569dfceacc)
