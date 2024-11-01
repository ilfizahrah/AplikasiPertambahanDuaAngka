# AplikasiPertambahanDuaAngka
 Latihan1-ilfizahrah-2210010537

---

# Deskripsi

Aplikasi Pertambahan Dua Angka ini memungkinkan pengguna menjumlahkan dua angka secara cepat. Pengguna memasukkan angka di dua kolom input, lalu menekan tombol Tambah untuk melihat hasil penjumlahan. Ada tombol Hapus  untuk mengosongkan kolom input dan mengatur ulang fokus, serta tombol Keluar untuk menutup aplikasi. Aplikasi ini juga memeriksa apakah input adalah angka, dan akan memberi pesan kesalahan jika tidak.

## Fitur Utama

1. Penjumlahan Dua Angka: Menghitung dan menampilkan hasil penjumlahan dari angka pertama dan angka kedua yang dimasukkan pengguna.
2. Validasi Input: Memastikan input hanya berupa angka, dan menampilkan pesan kesalahan jika input tidak valid.
3. Pengaturan Ulang Input: Tombol Hapus untuk mengosongkan semua kolom input dan mengembalikan fokus ke kolom pertama.
4. Tombol Keluar: Tombol Keluar untuk menutup aplikasi dengan cepat. 

## Komponen GUI

- *JFrame*: Jendela utama aplikasi.
- *JPanel*: Panel untuk menampung komponen lainnya.
- *JLabel*: Label teks.
- *JButton*: Tombol untuk melakukan perhitungan umur.
- *JTextField*: Menampilkan hasil perhitungan dua angka

## Logika Program
- Pengguna memasukkan dua angka ke dalam dua kolom input (JTextField).
- Saat tombol Tambah ditekan, aplikasi membaca nilai dari kedua kolom input, mengonversinya menjadi angka (integer). Aplikasi lalu menjumlahkan kedua angka tersebut. Hasil penjumlahan ditampilkan pada kolom hasil.
- Sebelum melakukan penjumlahan, aplikasi memeriksa apakah input valid (harus angka). Jika input tidak valid, aplikasi menampilkan pesan kesalahan menggunakan JOptionPane dan tidak melanjutkan perhitungan.
- Saat tombol Hapus ditekan, aplikasi mengosongkan semua kolom input dan hasil. Fokus kembali ke kolom input pertama untuk memudahkan pengguna.
- Saat tombol Keluar ditekan, aplikasi menutup atau keluar dari program.

## Instalasi

1. *Clone Repository*
   bash
   git clone https://github.com/ilfizahrah/AplikasiPertambahanDuaAngka.git

## Cara Penggunaan

1. *Menjalankan Aplikasi*:
   - Buka project di NetBeans.
   - Jalankan file PertamabahanDuaAngkaFrame.java.

2. *Menghitung Umur*:
   - Masukkan Angka pertama dan Angka kedua.
   - Klik tombol Tambah untuk menampilkan hasil pertambahan dari kedua angka.

## Tampilan Aplikasi Penghitung Umur (Saat Dijalankan)
Hasil Tampilan Aplikasi![Screenshot 2024-11-01 104337](https://github.com/user-attachments/assets/14ee299a-7bbb-48f1-b544-349c826f752f)


---
## Indikator Penilaian

| No  | Komponen           | Persentase |
|-----|---------------------|------------|
| 1   | Komponen GUI       | 10%        |
| 2   | Logika Program     | 10%        |
| 3   | Events             | 20%        |
| 4   | Kesesuaian UI      | 10%        |
| 5   | Memenuhi Variasi   | 50%        |
| *TOTAL* |               | *100%*   |

--- 
## Pembuat

Nama: Ilfi Zahrah

NPM: 2210010537

Kelas: 5B Reguler Pagi

Tugas : Latihan 1 Aplikasi Pertambahan Dua Angka

Fakultas : Fakultas Teknologi Informasi (FTI)

Unversitas : Universitas Islam Kalimantan Muhammad Arsyad Al Banjari Banjarmasin
