# Aplikasi Konversi Suhu

## Deskripsi Program
Aplikasi ini adalah program GUI menggunakan Java Swing yang berfungsi untuk mengonversi nilai suhu antara berbagai skala suhu. Fitur utama aplikasi ini:

- Pengguna memasukkan nilai suhu dan memilih jenis konversi yang diinginkan.
- Hasil konversi ditampilkan setelah tombol "Konversi" ditekan.
- Mendukung konversi otomatis saat nilai input berubah.

## Komponen GUI
Aplikasi ini menggunakan komponen berikut:

- `JFrame`: Jendela utama aplikasi.
- `JPanel`: Panel untuk tata letak komponen GUI.
- `JLabel`: Menampilkan hasil konversi dan informasi lainnya.
- `JTextField`: Input nilai suhu dari pengguna.
- `JComboBox`: Memilih jenis konversi (misalnya, Celsius ke Fahrenheit).
- `JButton`: Tombol untuk memulai konversi.
- `JRadioButton`: Pilihan untuk menentukan arah konversi.

## Logika Program
- **Rumus Konversi**:
  - Celsius ke Fahrenheit: `(C × 9/5) + 32`
  - Fahrenheit ke Celsius: `(F - 32) × 5/9`
  - Mendukung konversi suhu lainnya (Reamur, Kelvin) sebagai variasi tambahan.
- **Validasi Input**: Menggunakan KeyAdapter untuk memastikan hanya angka yang bisa dimasukkan.

## Events
- **ActionListener**: Digunakan untuk menangani klik pada tombol "Konversi".
- **ItemListener**: Digunakan pada JRadioButton untuk memilih arah konversi.
- **KeyAdapter**: Membatasi input pada JTextField hanya untuk angka.
- Konversi otomatis saat input nilai berubah.

## Fitur Tambahan
- Tambahkan skala suhu lain seperti **Reamur** dan **Kelvin**.
- Implementasi **ItemListener** pada JRadioButton untuk memilih arah konversi.
- Opsi untuk **konversi otomatis** ketika pengguna mengubah nilai input.

## Cara Menggunakan
1. Masukkan nilai suhu ke dalam JTextField.
2. Pilih jenis konversi (misalnya, Celsius ke Fahrenheit) dari JComboBox.
3. Klik tombol "Konversi" atau biarkan aplikasi melakukan konversi otomatis saat nilai input berubah.
4. Hasil konversi akan ditampilkan pada JLabel.

## Teknologi yang Digunakan
- **Java Swing**: Untuk antarmuka GUI.
- **NetBeans IDE**: Pengembangan proyek dilakukan menggunakan NetBeans.

## Penulis
Muhammad Hidayat (NPM: 2210010354).
Tugas 2
