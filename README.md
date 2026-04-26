_Nama : Arofah Raudlatul Hasanah_  
_Kelas : I241B_  
_NIM : 312410231_

## LokaBuku - Book Explorer  
Aplikasi penjelajah buku cerdas berbasis Android dengan fitur rekomendasi AI (Groq API), live cover fetching, dan koleksi buku favorit.  
## Tampilan Aplikasi (User Interface)  
1. Splash Screen
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/e3566c42-3de5-40f3-9012-abda16b90c5f" />

Penjelasan: Layar pembuka aplikasi yang simpel namun elegan. Disertai sapaan selamat datang yang pintar, karena teks sapaannya bisa menyesuaikan secara otomatis dengan bahasa yang sedang digunakan pada perangkat HP pengguna.  

2. Halaman Login
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/5b003499-e3a0-4b75-8950-d000ed68db12" />  
Penjelasan: Tampilan masuk yang bersih dan user-friendly. Pengguna cukup memasukkan email dan password untuk mengakses fitur utama. Setelah berhasil masuk, sistem akan menyimpan sesi pengguna agar emailnya bisa ditampilkan di halaman profil nantinya.


4. Dashboard Utama (Menu Eksplor)
<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/91ca363b-f1bf-4456-8920-99c379fbd978" />  
Penjelasan: Ini adalah halaman utama atau "jantung" dari LokaBuku. Di sini pengguna bisa melihat deretan buku yang sedang tren. Fitur unggulannya adalah kolom pencarian AI (terintegrasi dengan Groq API). Pengguna bisa mengetik suasana atau genre buku yang diinginkan, lalu AI akan memberikan rekomendasi judul beserta gambar sampul aslinya yang ditarik langsung (fetching) menggunakan Google Books API.  

5. Halaman Detail Buku


Penjelasan: Jika pengguna menekan salah satu cover buku di Dashboard, halaman detail ini akan muncul. Di sini pengguna bisa melihat sampul buku dengan ukuran yang lebih besar, membaca sinopsis lengkapnya, dan menekan ikon 'Hati' (Love) untuk menyimpan buku tersebut ke dalam daftar koleksi pribadi.  

5. Halaman Profil & Koleksi
<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/6023dca4-e16c-4e45-b1d6-8db11ecb0206" />   
Penjelasan: Halaman personal yang merangkum data pengguna. Di bagian atas terdapat informasi akun (email yang digunakan saat login), dan di bawahnya terdapat daftar buku (list view) yang sudah disimpan dari halaman detail tadi. Tersedia juga tombol untuk Logout yang akan menghapus sesi dan mengembalikan pengguna ke halaman awal.
