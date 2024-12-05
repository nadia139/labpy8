Kelas Mahasiswa
Inisialisasi (__init__):

Kelas Mahasiswa memiliki atribut daftar_mahasiswa, yang merupakan list kosong untuk menyimpan data mahasiswa.
Metode tambah:
Metode ini digunakan untuk menambahkan data mahasiswa baru ke dalam daftar_mahasiswa.
Data mahasiswa disimpan dalam bentuk dictionary yang berisi nama, nim, dan nilai.
Setelah menambahkan data, program mencetak pesan konfirmasi.

Metode tampilkan:
Metode ini menampilkan semua data mahasiswa yang ada dalam daftar_mahasiswa.
Jika daftar kosong, program akan mencetak pesan bahwa daftar mahasiswa kosong.
Jika ada data, program akan mencetak setiap mahasiswa dengan nomor urut.

Metode hapus:
Metode ini digunakan untuk menghapus data mahasiswa berdasarkan nama.
Program mencari mahasiswa dengan nama yang diberikan, dan jika ditemukan, data tersebut dihapus dari daftar_mahasiswa.
Jika tidak ditemukan, program mencetak pesan bahwa data mahasiswa tidak ditemukan.

Metode ubah:
Metode ini digunakan untuk mengubah data mahasiswa yang sudah ada.
Program mencari mahasiswa berdasarkan nama, dan jika ditemukan, NIM dan nilai mahasiswa tersebut diubah sesuai input baru.
Jika tidak ditemukan, program mencetak pesan bahwa data mahasiswa tidak ditemukan.
Contoh Penggunaan
Bagian ini adalah antarmuka pengguna yang memungkinkan pengguna untuk berinteraksi dengan program melalui menu:

Menu Pilihan:
Program menampilkan menu dengan pilihan untuk menambah, menampilkan, mengubah, menghapus mahasiswa, atau keluar dari program.
Input Pilihan:

Pengguna diminta untuk memilih menu dengan memasukkan angka dari 1 hingga 5.
Proses Berdasarkan Pilihan:

Jika pengguna memilih untuk menambah mahasiswa, program meminta input nama, NIM, dan nilai, lalu memanggil metode tambah.
Jika memilih untuk menampilkan mahasiswa, program memanggil metode tampilkan.
Jika memilih untuk mengubah data mahasiswa, program meminta nama, NIM baru, dan nilai baru, lalu memanggil metode ubah.
Jika memilih untuk menghapus mahasiswa, program meminta nama mahasiswa yang ingin dihapus dan memanggil metode hapus.
Jika memilih untuk keluar, program mencetak pesan dan menghentikan eksekusi.

Validasi Input:
Jika pengguna memasukkan pilihan yang tidak valid, program akan mencetak pesan dan meminta input lagi.
