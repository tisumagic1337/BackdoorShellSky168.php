Dokumentasi BackdoorSky168-VersiSiluman.php

⚠️ Disclaimer: Segala bentuk penyalahgunaan, baik yang bersifat ilegal maupun merusak, sepenuhnya menjadi tanggung jawab pengguna.

1. Pendahuluan

BackdoorSky168-VersiSiluman.php ini merupakan backdoor shell berbasis web yang dilengkapi dengan fitur siluman bypass WAF, autentikasi, manajemen file, terminal, dan pemindai backdoor. Tampilan antarmuka (UI) sederhana menggunakan latar belakang hitam dan font monospace.

2. Konfigurasi

Beberapa konfigurasi penting pada BackdoorSky168-VersiSiluman.php ini meliputi:

- Direktori utama.

- Password default kabel168.

- Update password untuk pertama kali akses.

- Opsi untuk mengaktifkan terminal.

- Batas waktu eksekusi command.

- Batas maksimum output command.

3. Fungsi Helper

BackdoorSky168-VersiSiluman.php ini menyediakan fungsi helper sebagai berikut:

- Mengecek apakah pengguna sudah login.

- Mengamankan string agar aman ditampilkan di HTML.

4. Autentikasi

- Bagian autentikasi menangani:

- Pengaturan password baru jika password default digunakan [untuk keamananpengguna/tidak menggunakan password default].

- Login pengguna dengan password yang sudah diupdate yang tersimpan.

- Pembuatan session untuk pengguna yang berhasil login.

5. Direktori Kerja

- Fungsi terkait direktori kerja meliputi:

- Menentukan direktori kerja aktif ($cwd).

- Menangani proses logout dengan menghancurkan session.

- Mengambil informasi sistem, seperti nama pengguna, OS, dan software server.

6. Manajemen File

- Fitur manajemen file mencakup:

- Membuat file baru.

- Membuat folder baru.

- Mengunggah file (upload).

- Membuat file ZIP dari beberapa file.

- Mengekstrak file ZIP.

- Menghapus file atau folder.

- Mengunduh (download) file.

- Mengubah nama file (rename).

- Mengedit file dengan penyorotan syntax untuk keyword berbahaya.

7. Terminal

- Jika ENABLE_SHELL diaktifkan, pengguna dapat menjalankan command sistem melalui form web. Output dibatasi oleh SHELL_MAX_BYTES dan memiliki batas waktu eksekusi (SHELL_TIMEOUT_SEC).

8. Pemindai Backdoor

- Script ini dapat memindai direktori kerja untuk menemukan file yang mengandung keyword berbahaya, antara lain:
eval, base64_decode, system, exec, shell_exec, passthru, popen, proc_open, assert, preg_replace.

9. Antarmuka Pengguna

Antarmuka BackdoorSky168-VersiSiluman.php mencakup:

- Tampilan berbasis HTML dan CSS sederhana.

- Breadcrumb untuk navigasi direktori.

- Tabel untuk menampilkan daftar file/folder beserta aksi seperti Edit, Download, Delete, dan Rename.

- Form inline untuk upload file, membuat file/folder, dan membuat ZIP.

- Area terminal dan pemindai backdoor.

10. Kesimpulan

- BackdoorSky168-VersiSiluman.php dilengkapi fitur untuk menghindari deteksi oleh WAF (Web Application Firewall) seperti LiteSpeed, Imunify360, dan sejenisnya, sehingga script ini tidak mudah terhapus.
Versi ini juga menambahkan kemampuan bagi pengguna untuk mengubah password default, untuk memperkuat kontrol akses.
Tampilan login dibuat menyerupai halaman 404 Not Found, Pengguna dapat login dengan menekan tombol Tab pada PC atau laptop.

Akhir kata: [Keamanan Hanyalah Sebuah Ilusi !!!]

Salam, Sky168

Hiduplah Indonesia Raya.
