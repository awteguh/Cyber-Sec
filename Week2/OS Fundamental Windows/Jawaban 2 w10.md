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
   `mkdir mystuff`cd
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

## File Permision Review
- Tidak
- Tidak
- Ya

## Exercise
- Menampilkan Semua Akun dalam Grup Administrators
  ![Image](https://github.com/user-attachments/assets/e792c1e3-c3f5-4fde-a976-a4a5ab76ca9a)
- Membuat Pengguna Baru "Alice"
- Menambahkan Alice ke Grup Administrators
- Memulai Command Prompt sebagai Alice Menggunakan RunAs
  ![Image](https://github.com/user-attachments/assets/c7fe6768-d4b3-4228-b3bb-f3d9c650f86d)
- Mencoba Membuat Pengguna dari Shell Alice
- Menambahkan Pengguna "Bob"
  ![Image](https://github.com/user-attachments/assets/47cbaa88-2a05-4ea9-b2b0-5f3958a240be)

- Membuat Grup "Developers"
  ![Image](https://github.com/user-attachments/assets/8e1495b5-7949-40f9-8591-5d3938301991)
  
- Menambahkan Bob dan Alice ke Grup Developers
  ![Image](https://github.com/user-attachments/assets/7710141f-cd41-4933-8a27-9f7918b26e9e)
  
- Menampilkan Anggota Grup Developers
  ![Image](https://github.com/user-attachments/assets/576b2668-62d8-43d8-af12-aa09be162818)
  
- Menghapus Grup Developers, Bob, dan Alice
  ![Image](https://github.com/user-attachments/assets/837ecaf4-b938-4352-a268-2660ef0a2110)

## Security Police Review
- User Right Assignment
- Security Options

## REG.EXE Exercise
- reg
  ![Image](https://github.com/user-attachments/assets/11ed3e6b-65af-4e4d-9980-9b502fef9765)
- reg query
  ![Image](https://github.com/user-attachments/assets/bd605d5d-837c-471e-88c8-41b522deadee)

## REG.EXE Exercise (2)
- HKCU Current User
  ![Image](https://github.com/user-attachments/assets/1899e389-f107-40b2-96b3-45585ae5bec8)
  
- Current User's Software Key
  ![Image](https://github.com/user-attachments/assets/1c3759bc-2e4c-4bc0-a5d2-b938d42c810b)
  
- This key is commonly used by malware
  ![Image](https://github.com/user-attachments/assets/40936498-414c-4904-9036-b0f2864b710c)

## NET USE & VIEW Review
- Net use z:\\server\files
- Dir\\servername\share

## EXERICE WMIC

   
