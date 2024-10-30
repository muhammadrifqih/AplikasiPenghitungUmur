# Modul Latihan 2 – Aplikasi Penghitung Umur

Langkah 1: Membuat Project Baru di NetBeans
1. Buka **NetBeans**.
2. Pilih **File > New Project**.
3. Pilih **Java > Java Application**, beri nama proyek, misalnya `AplikasiPenghitungUmur`, lalu klik **Finish**.

Langkah 2: Menghubungkan Project ke GitHub
1. Buka **GitHub Desktop**, klik **File > Add Local Repository**.
2. Pilih folder proyek, klik **Add repository**.
3. Klik **Create repository**, isi deskripsi repository, lalu klik **Create repository**.

Langkah 3: Membuat JFrame Form
1. Klik kanan pada **Source Packages > New > JFrame Form**.
2. Beri nama `PenghitungUmurFrame` dan klik **Finish**.
3. Buka **GitHub Desktop**, buat commit dengan pesan "Menambahkan JFrame Form".

Langkah 4: Menambahkan Komponen GUI dan Mendesain Aplikasi
1. **Unduh** [JCalendar](https://toedter.com/jcalendar/) dan tambahkan `jcalendar-1.4.jar` ke folder `lib`.
2. **Tambahkan** JCalendar ke NetBeans melalui **Palette Manager**.
3. **Desain GUI** dengan komponen:
    - **JFrame**: Title `Aplikasi Penghitung Umur`.
    - **JPanel** untuk tempat komponen.
    - **JDateChooser**, **JTextField**, dan **JButton** untuk input dan tampilan umur.
4. Commit perubahan ke GitHub dengan pesan "Menambahkan GUI components dan mendesain aplikasi".

Langkah 5: Menambahkan Logika Program
1. Buat class baru `PenghitungUmurHelper` untuk menghitung umur dan hari ulang tahun berikutnya:
   - **hitungUmurDetail**: Menghitung umur dalam tahun, bulan, dan hari.
   - **hariUlangTahunBerikutnya**: Menghitung tanggal ulang tahun berikutnya.
2. Tambahkan event `ActionListener` pada tombol "Hitung".
3. Tambahkan event `PropertyChangeListener` pada `JDateChooser`.
4. Commit perubahan dengan pesan "Menambahkan event dan logika program untuk menghitung umur".

Langkah 6: Menambahkan Variasi Peristiwa Penting
1. **Tambahkan JTextArea** untuk menampilkan peristiwa penting.
2. **Unduh** [JSON-Java](https://github.com/stleary/JSON-java) dan tambahkan `json-20240303.jar` ke folder `lib`.
3. Tambahkan fungsi `getPeristiwaBarisPerBaris` di `PenghitungUmurHelper` untuk mengambil data peristiwa dari API eksternal.
4. Commit perubahan dengan pesan "Menambahkan variasi untuk menampilkan peristiwa penting".

Langkah 7: Menambahkan Terjemahan ke Bahasa Indonesia
1. Tambahkan fungsi `translateToIndonesian` di `PenghitungUmurHelper` untuk terjemahan deskripsi peristiwa.
2. Panggil fungsi terjemahan saat menampilkan deskripsi peristiwa di `JTextArea`.
3. Commit dengan pesan "Menambahkan variasi untuk terjemah ke Bahasa Indonesia".

Langkah 8: Publish Repository ke Github.com
1. Klik **Publish repository** di GitHub Desktop.
2. Hapus centang pada **Keep this code private** lalu klik **Publish repository**.
3. Setelah selesai, salin URL repository dan kumpulkan di e-learning.


Screenshot
Nama    : Muhammad Rifqi Hidayat

NPM     : 2210010126

Kelas   : 5A Reg BJB


1. Foto Awal
   
![Screenshot 2024-10-30 171823](https://github.com/user-attachments/assets/70eaa5aa-363e-43b8-9602-377ec41d935b)

2. Foto Pilih Tanggal

![Screenshot 2024-10-30 171843](https://github.com/user-attachments/assets/35e91ac3-cb3b-4e9f-bcd3-a6adff47ad35)

3. Foto Klik Hitung

![Screenshot 2024-10-30 171852](https://github.com/user-attachments/assets/c9817f9b-5004-4beb-a744-93039938bafd)




