# TUGAS-1-SISTEM-OPERASI-SK3B

  **TUGAS INSTALASI LINUX UBUNTU 24.0.4 LTS DI VIRTUAL BOX**
  
  **Nama : Miki Purnawan**
  
  **Kelas : SK3B**
  
  **NIM : 09011282328122**


  **NOMOR 1. BUATLAH TATA CARA INSTALASI LINUX UBUNTU**

  1.   Download terlebih dahulu file iso linux ubuntu deskop 24.0.4 LTS dan Software VirtualBox

     A. Link file iso linux : https://ubuntu.com/download/desktop

     B. Link software VirtualBox : https://www.virtualbox.org/wiki/Downloads

  2. Setelah mendownload dan menginstall VirtualBox. Langkah selanjutnya adalah membuka VirtualBox, kemudian klik new
     ![vb1](https://github.com/user-attachments/assets/fe65780e-eb0f-4052-b867-ee66c864cce3)

  3. ![vb2](https://github.com/user-attachments/assets/3b3910b1-6411-46b0-805f-a85357169c49)

     Pada gambar di atas, isi nama, pilih lokasi folder untuk menyimpan linux dan pilih iso linux yang sudah didownload

  4. ![vb3](https://github.com/user-attachments/assets/66dd4505-fa3e-4872-b783-7bf3b7fa0fd4)

     di bagian ini bisa langsung next saja tapi jika mengalami error pada bagian hostname, coba untuk mengubah nama nya tanpa spasi contohnya jika ingin nama Miki Purnawan maka nama hostname nya itu Miki-Purnawan

  5. ![vb4](https://github.com/user-attachments/assets/4e9fce31-266f-4fb9-bf48-5f1ba27d13ca)

     Di bagian ini saya sarankan untuk mengubah memory base nya ke minimal 3000MB agar tidak terlalu ngelag dan di bagian processor nya ganti ke 2 atau lebih

  6. ![vb5](https://github.com/user-attachments/assets/1e502457-cf86-4199-8f62-10cfa3c8ff5d)

     ini adalah bagian virtual storage atau penyimpanan virtual yang berarti semakin besar storage yang diatur maka storage yang tersedia itu lebih besar, kemudian klik next dan finish maka virtual machine akan berjalan/running

  7. ![l1](https://github.com/user-attachments/assets/19337cd8-13c0-4010-b709-92177b361f78)

     pilih bahasa yang diinginkan, ada Bahasa Indonesia dan Bahasa Inggris dll kemudian next next saja

  8. ![l2](https://github.com/user-attachments/assets/3e343395-2991-44b5-97f8-2f8c48edcaf1)

     di bagian ini bisa pilih no connection atau wired connection(jika perangkat terkoneksi internet) kemudian next
     
  9. ![l3](https://github.com/user-attachments/assets/38ff7b1d-0429-4083-8963-e475578f3092)

      pilih install ubuntu kemudian next next saja

  10. ![l4](https://github.com/user-attachments/assets/f669f54c-5545-47a5-8b25-0a482e0c4f9a)

      di bagian ini centang install third party, bisa juga centang download and install support jika perangkat terkoneksi internet
      
  11. ![l5](https://github.com/user-attachments/assets/404c2dce-815e-4310-a7fd-fc10d0c079be)

      di bagian instalasi partisi ini, saya pribadi langsung next karena saya memakai virtualbox yang sudah ada 1 storage virtual yang kosong
      
  12. ![l6](https://github.com/user-attachments/assets/de345947-ee05-4abb-bedb-b4f1c7ec43b5)

      kemudian di bagian ini username linux dan password untuk login
      
  13. ![l7](https://github.com/user-attachments/assets/3e4204b0-aeaa-4e71-bdc9-7bfefe1dccdd)

      ini pilih titik lokasi di Jakarta lalu klik next dan kemudian finish
      
  14. ![l8](https://github.com/user-attachments/assets/076d9408-1c9a-46f9-bd70-3165bf5aea3b)

      sekarang proses instalasi sudah dimulai, ini memerlukan waktu yang agak lama jadi bisa ditinggal pushrank terlebih dahulu

  15. ![l9](https://github.com/user-attachments/assets/3995f213-ba87-443e-802c-1d03fac54929)

      Setelah proses instalasi selesai, kita bisa klik continue ataupun restart tapi saya sarankan restart saja agar lebih aman

  16. ![l10](https://github.com/user-attachments/assets/6d57dab3-1780-4d61-acf9-4b37935ab06f)

      Setelah restart maka akan muncul menu login username dan password linux, kita harus masukkan username dan password sesuai dengan yang sudah kita isi ketika proses instalasi dan itulah tata cara instalasi linux ubuntu di virtualbox



  **NOMOR 2. Analisislah pada gambar kenapa saat instalasi perlu dipilih “/” pada opsi Mount Point ?**

  ![L12](https://github.com/user-attachments/assets/bdcb5230-ade0-4354-881b-42decbe35d8a)

  Jawab : Saat instalasi Linux Ubuntu, memilih "/" sebagai Mount Point penting karena:

A. Root Filesystem: "/" adalah direktori utama dari sistem file Linux. Memilihnya berarti partisi akan menjadi tempat penyimpanan utama untuk semua file sistem.

B. Pengaturan Sistem: Tanpa memilih "/", sistem tidak akan tahu di mana file-file penting harus disimpan.

C. Organisasi: "/" adalah titik awal dari struktur direktori, sehingga semua file dan folder lainnya berada di bawahnya.

  **NOMOR 3. Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs**

  Jawab :

 A. ext4: Sistem file utama di Linux, cepat dan stabil, mendukung ukuran file besar dan fitur canggih seperti journaling.

 B. ext3: Sistem file Linux yang lebih tua dengan fitur journaling, tetapi dengan keterbatasan ukuran volume dan performa dibandingkan ext4.

 C. swap: Ruang tambahan di Linux yang digunakan saat RAM hampir penuh, membantu menjaga sistem tetap berjalan lancar.

 D. NTFS: Sistem file utama untuk Windows dengan dukungan untuk ukuran file besar, izin file, dan fitur keamanan.

 E. FAT32: Sistem file kompatibel luas, sering digunakan di media penyimpanan portabel, dengan batas ukuran file maksimum 4 GB.

 F. btrfs: Sistem file Linux canggih dengan fitur seperti snapshot dan manajemen volume yang efisien, menawarkan kemampuan pemulihan data yang kuat.







  
