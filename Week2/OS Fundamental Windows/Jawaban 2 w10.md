# Jawaban soal 2 w10

1.Masuk ke Root Drive C:
   `cd C:\`
2. Kembali ke Direktori Profil Pengguna
  `cd %USERPROFILE%`
3. Membuat Direktori dengan Nama yang Mengandung Spasi
  `mkdir "this directory has a space"`
4. Masuk ke Direktori Baru Menggunakan Tab Completion
  `cd "this directory has a space"`
  ![Image](https://github.com/user-attachments/assets/37612c67-1a02-4784-95af-e9cddc728e8b)

5. Membuat Direktori Tersembunyi Bernama mystuff
   `mkdir mystuff`
   `attrib +h mystuff`
6. Mengubah Nama Direktori this directory has a space Menjadi shortname
   `ren "this directory has a space" shortname`
 ![Image](https://github.com/user-attachments/assets/74bcb176-0f32-4457-a905-ffe99fbdf1d4)
7. Membuka Kalkulator dan Menghentikan Prosesnya
   `calc.exe`
   `tasklist | findstr Calculator.exe`
   `taskkill /PID 6488 /F`
    ![Image](https://github.com/user-attachments/assets/60ef5ed8-683e-4617-81a1-6f37facdfa5f)
8. Mendapatkan Alamat IP Saat Ini
   `ipconfig`
   ![Image](https://github.com/user-attachments/assets/a6ba6e5d-e22b-48a0-89ad-ac450ea5ccbe)
9. Melihat Koneksi Jaringan dengan netstat
   `netstat -an`
   ![Image](https://github.com/user-attachments/assets/d14ab04e-287c-43c7-8b20-d72deee6e231)
   
