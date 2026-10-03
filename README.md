Tugas pertama, yaitu Tata Letak Dasar, tersimpan di dalam file TataLetak.kt dan menampilkan antarmuka berupa kotak kuning berisi susunan teks dari kombinasi Column dan Row, serta kotak cyan yang berisi gambar not balok dan tulisan "My Music". 
Tampilan ini dibuat menggunakan komponen dasar seperti Column, Row, Box, Spacer, Image, dan Text, dengan pengaturan warna latar belakang melalui Modifier.
<img width="307" height="637" alt="Screenshot 2026-10-03 202158" src="https://github.com/user-attachments/assets/85d05a81-f3da-4c11-9ddf-e25ec953afc1" />
Tugas kedua, yaitu Halaman Login, tersimpan di dalam file TugasLogin.kt yang menampilkan halaman login dengan latar belakang gambar masjid, logo Universitas Muhammadiyah Yogyakarta (UMY), teks nama dan NIM, serta gambar Ka'bah yang dipotong menjadi bulat. 
Pembuatan halaman ini memanfaatkan Box sebagai lapisan dasar untuk menumpuk background dan konten, Column untuk menyusun elemen secara vertikal ke bawah, serta modifier clip(CircleShape) untuk membuat gambar Ka'bah menjadi bulat sempurna.
<img width="265" height="581" alt="Screenshot 2026-10-03 210702" src="https://github.com/user-attachments/assets/61e68736-d6d2-4084-8605-b25cd191a3e4" />

Untuk menjalankan kedua tampilan tersebut, file MainActivity.kt berfungsi sebagai pintu masuk aplikasi yang memanggil fungsi dari masing-masing file. 
Selain file kode Kotlin tersebut, project ini juga menggunakan empat file gambar pendukung yang disimpan di dalam folder res/drawable, yaitu notasibolok.png untuk Tugas 1, serta bg_masjid.png, logo_umy.png, dan gambar_kaabah.png untuk Tugas 2.
