# Judul Program
Kalkulator Sederhana

# Pendahuluan
Program ini adalah aplikasi kalkulator sederhana berbasis Python yang dapat melakukan perhitungan dasar seperti penjumlahan, pengurangan, perkalian, dan pembagian. Aplikasi ini dibuat sebagai bagian dari tugas mata kuliah Pengenalan Pemrograman dan menggunakan konsep dasar logika pemrograman bersama struktur kontrol sederhana.

# Fitur Utama
- Penjumlahan dua angka
- Pengurangan dua angka
- Perkalian dua angka
- Pembagian dua angka
- Input yang mudah dan interaktif di terminal
- Lanjut ke Cara Instalasi:

## Panduan Instalasi
1. Clone repository:
   git clone <https://github.com/reynamanansal026-create/kalkulator_kolaborasiJ2R-.git>

2. Masuk ke folder project:
cd kalkulator_kolaborasiJ2R

4. Pastikan Python sudah terinstal:
python --version

# Panduan Menjalankan
Untuk menjalankan program, buka folder project di VSCode lalu buka terminal (Ctrl + \``) dan pastikan berada pada direktori file program. Jalankan perintah python kalkulator_kolaborasiJ2R.py, maka tampilan menu seperti berikut akan muncul:
===KALKULATOR SEDERHANA===
1. Tambah
2. Kurang
3. Bagi
4. Keluar
Pilih operasi yang diinginkan, masukkan dua angka, dan hasil perhitungan akan ditampilkan di terminal

# Flowchart & penjelasan

![gambar flowchart](<flowchart_kalkulator.drawio.png>)

Flowchart ini menjelaskan alur kerja dari sebuah program kalkulator sederhana yang dirancang untuk melakukan empat jenis operasi aritmatika dasar, yaitu penjumlahan, pengurangan, perkalian, dan pembagian. Proses dimulai dari simbol “Mulai”, yang menandakan bahwa program telah aktif dan siap menerima input dari pengguna. Setelah program berjalan, sistem akan menampilkan menu operasi sebagai bentuk interaksi awal. Menu tersebut berisi daftar pilihan operasi yang dapat digunakan oleh pengguna, yaitu angka 1 untuk tambah, 2 untuk kurang, 3 untuk kali, 4 untuk bagi, serta angka 0 untuk keluar dari program.

Setelah menu tampil, pengguna diminta untuk memilih salah satu operasi yang diinginkan. Program kemudian melakukan pengecekan terhadap input tersebut melalui proses pengambilan keputusan. Jika pengguna memasukkan angka yang sesuai dengan daftar pilihan yang tersedia, maka program akan melanjutkan ke bagian berikutnya. Namun apabila pilihan yang dimasukkan tidak sesuai, sistem akan menampilkan pesan bahwa pilihan tidak valid, lalu alur program dikembalikan ke menu utama agar pengguna dapat memilih ulang.

Jika pilihan operasi yang dimasukkan benar, program akan meminta pengguna untuk memasukkan dua buah angka yang akan diproses. Kedua angka ini menjadi data utama dalam perhitungan aritmatika. Untuk operasi tambah, kurang, dan kali, setelah angka dimasukkan, program langsung melakukan perhitungan sesuai dengan rumus operasi tersebut. Hasilnya kemudian ditampilkan di layar, dan setelah itu program kembali lagi ke menu awal untuk memberikan kesempatan kepada pengguna melakukan perhitungan lain.

Pada operasi pembagian, terdapat proses tambahan yaitu pengecekan validitas nilai pembagi. Program akan memastikan bahwa angka kedua tidak bernilai nol, karena pembagian dengan nol tidak dapat dilakukan dan dapat menyebabkan kesalahan perhitungan. Jika angka pembagi bernilai nol, program memberikan peringatan bahwa pembagian tidak dapat dilakukan, lalu pengguna diarahkan kembali ke menu utama. Sebaliknya, jika angka pembagi valid, program akan melanjutkan perhitungan pembagian dan menampilkan hasilnya sebelum kembali lagi ke menu.

Program juga menyediakan pilihan untuk keluar dari aplikasi. Jika pengguna memilih angka 0 pada menu, maka program langsung menghentikan seluruh alur dan menuju simbol “Selesai”, yang menandakan bahwa program telah berakhir sesuai dengan keinginan pengguna. Keseluruhan alur dalam flowchart ini menunjukkan bahwa kalkulator bekerja dengan sistem perulangan, di mana setelah setiap operasi selesai dilakukan, pengguna selalu dikembalikan ke menu utama tanpa memulai ulang program. Selain itu, adanya pengecekan khusus pada operasi pembagian menunjukkan bahwa program telah dilengkapi dengan penanganan kesalahan, sehingga lebih aman dan mencegah terjadinya error logika dalam proses perhitungan.
