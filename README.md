# Nama   : Meita Sahara
# Nim    : 09011182328006
# Kelas  : SK3C

# Tugas File System

# 1. Lihat peralatan I/O, character device, yang ada pada system komputer.
#    menggunakan peritah ls -l /dev | grep "^c"
![no1](https://github.com/user-attachments/assets/f9e8c23d-80e5-42c3-83ce-06de28384aaa)
# * ls -l /dev: Perintah ini menampilkan daftar perangkat di direktori /dev dengan format yang lebih rinci. 
# * grep ^c: Memfilter output untuk hanya menampilkan baris yang dimulai dengan huruf c, yang menandakan perangkat karakter.

# 2. Buatlah sub direktori januari, februari dan maret sekaligus pada direktori latihan5. 
#    menggunakan mkdir -p latihan5/{januari, februari, maret}
![no2](https://github.com/user-attachments/assets/efbbb76e-70bf-4059-8ba5-83810865e78b)
# mkdir : untuk membuat direktori baru di dalam sistem file

#  3. Buatlah file dataku yang berisi nama, nim dan alamat anda pada sub direktori januari dan copy-kan file tersebut ke sub direktori februari dan maret.
![no3](https://github.com/user-attachments/assets/aad5b5a1-792a-42e4-a6b9-07199167add6)
#  cp : untuk menyalin berkas dari satu lokasi ke lokasi lain.

# 4. ubahlah ijin akses file dataku pada sub direktori januari sehingga group dan others dapat melakukan write.
![no4](https://github.com/user-attachments/assets/07a0f6e4-6d9f-4aa7-8a5d-1f85cc7ce817)
# chmod 666 : untuk memberikan izin baca dan tulis kepada semua pengguna, tetapi tidak dapat mengeksekusi file atau folder.

# 5. Ubahlah ijin akses file dataku pada sub direktori pebruari sehingga user dapat melakukan baik write, read maupun execute, tetapi group dan others hanya bisa read dan execute.
![no5](https://github.com/user-attachments/assets/0b1e9aa6-0146-4b82-aad2-959d3708856c)
#  User memiliki izin penuh, group dan others hanya bisa read dan execute.

# 6. Ubahlah ijin akses file dataku pada sub direktori maret sehingga semua dapat melakukan write, read dan execute.
![no6](https://github.com/user-attachments/assets/d1b4e8eb-3638-41fa-b898-86f7d7577450)
#   chmod 777 : untuk memberikan izin penuh (baca,tulis, dan eksekusi kepada semua pengguna (pemilik, grup, dan lainnya) untuk suatu berkas atau direktori.

# 7. Hapuslah direktori maret.
![no7](https://github.com/user-attachments/assets/515fc68e-2fbd-47cb-8d36-390413603f5e)
# perintah rm dan opsi -r digunakan untuk menghapus file atau direktori.

# 8. Ubahkan kepemilikan sub direktori februari sehingga user dan group hanya dapat melakukan read, dan cobalah untuk membuat direktori baru haha pada sub direktori februari.
![no8](https://github.com/user-attachments/assets/113d2ed1-ca88-420a-b2af-06f74a722675)
# chmod 44 : untuk mengatur izin sehingga user dan group hanya bisa read.
![no8 2](https://github.com/user-attachments/assets/e8dfc7e6-306d-46c8-b1bf-c13b8c236d8c)
# Karena izin telah diubah sehingga user hanya memiliki akses read, perintah untuk membuat direktori baru gagal.
![no8 1](https://github.com/user-attachments/assets/a79b170b-e2ea-4d02-8e49-1ae710c0e062)
# ls -ld : untuk memeriksa apakah izin sudah diubah dengan benar.

# 9. Modifikasi umask dari file dataku pada sub direktori januari menjadi 027 dan berapakan nilai default-nya?
![no9](https://github.com/user-attachments/assets/91141a4f-a1e5-4fa8-ab7d-aa2b2c98bf12)
# Umask : untuk mengatur izin default file dan direktori baru. default umask= 0002.
![no9 1](https://github.com/user-attachments/assets/3fe0d3d4-d48a-43fc-9269-7599c0333ca3)
# ubah umask menjadi 027/0027.

# 10. Buatlah link dari file dataku ke file dataku.ini dan file dataku.juga dan dengan perintah list perhatikan berapa link yang terjadi?
![no10](https://github.com/user-attachments/assets/4357c8e4-5cc5-4380-b844-1eb26cd690b6)
# ln : untuk membuat tautan keras atau tautan simbolik(symlink) ke berkas atau direktori yang sudah ada.
![no10 1](https://github.com/user-attachments/assets/79c586d3-576b-4bde-9c87-30397b4281d0)
# Gunakan perintah ls -l untuk melihat berapa banyak link yang ada pada file dataku.

# File Januari, Februari, dan Maret
![file Januari,Februari,Maret](https://github.com/user-attachments/assets/a9022ca5-5273-4fd3-bf9a-795cae8b2a6b)

# File Januari, Februari
![file Januari,Februari](https://github.com/user-attachments/assets/bbd9eec1-098e-41d6-aa39-4736e5e79f40)

# Isi File Januari
![isi file Januari](https://github.com/user-attachments/assets/8a689f3f-7c2c-403a-88c8-0d7ae1ab4a71)

# Isi File Februari
![file Februari](https://github.com/user-attachments/assets/11bcf88c-3e26-4d96-9f44-03cc06f1ad5d)

# Isi File dataku
![isi file dataku](https://github.com/user-attachments/assets/5032a72a-50b0-4057-8c3b-94ef81447613)

# Isi File dataku.ini
![isi file dataku ini](https://github.com/user-attachments/assets/e9c1c514-c6ad-4568-8f06-a493050370ad)

# Isi File dataku.juga
![isi file dataku juga](https://github.com/user-attachments/assets/43d0e231-3f70-4fe4-8b2f-a89579ee35dc)
