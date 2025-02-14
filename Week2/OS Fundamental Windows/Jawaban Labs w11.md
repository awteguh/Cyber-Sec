# Jawaban Soal Labs w11
https://drive.google.com/file/d/1niJ6FTbeWTrL-NePb4PCMtKxAWp5szyJ/view

1. Sebuah file teks tersembunyi ditemukan di dalam direktori C:\Windows\System32. Administrator meminta bantuan untuk menemukannya dan membaca isinya. (VISIONET{p3san_t3rs3mbunyi_0964})
   ![Image](https://github.com/user-attachments/assets/643dda4b-d9cf-4106-8851-073f99f85081)

2. Administrator menemukan beberapa akun pengguna dalam sistem Windows ini. Anda diberikan salah satu akun yang terdapat sebuah pesan. Mereka meminta bantuan untuk mengidentifikasi akun tersebut. Mungkin pesan tersebut tersembunyi pada comment user. (VISIONET{D3Ta1L_Acc0unt_l1ke_Prop3rti35})
   ![Image](https://github.com/user-attachments/assets/c2323dac-7435-4ce5-8db8-d40ca62107bc)

3. Administrator mencurigai adanya modifikasi pada Windows Registry dengan mengubah entri pada Winlogon, yang memungkinkan sistem melewati proses autentikasi normal.
Tugas Anda adalah menemukan nilai registry yang berisi flag dan melaporkannya.
  ![Image](https://github.com/user-attachments/assets/f8e977e5-a3f7-4afc-baef-32489ee2f679)

4. Administrator menemukan adanya beberapa aktivitas virus pada tanggal 9 Februari 2025 sekitar pukul 6 PM. Hasil temuan adalah proses running service mencurigakan yang berjalan pada port 8992. Untungnya service tersebut Error ketika berjalan sehingga tidak berhasil mengambil alih sistem.
- Menemukan nama service yang berjalan
- Menemukan nama file executable yang menjadi malware
Flag merupakan nama file executable tanpa extensi .exe. ex: Ditemukan file example.exe, flag = VISIONET{example} (VISIONET{threathuntingexecutableapi})
   ![Image](https://github.com/user-attachments/assets/b51a114c-2b68-4bbb-b3d5-91672d4009f1)

5. Administrator menemukan adanya beberapa upaya login gagal terhadap akun visioadmin pada tanggal 9 Februari 2025 sekitar pukul 5 PM, tetapi mereka tidak yakin apakah ini hanya kesalahan pengguna atau bagian dari serangan brute-force.
Tugas Anda adalah menemukan ID Event Log dari percobaan login gagal dan mengidentifikasi alamat IP asal yang melakukan upaya login tersebut.
Format FLAG: VISIONET{EventId_IP} ex-wrong-flag: VISIONET{9999_0.0.0.0} VISIONET{4625_192.168.60.1}
