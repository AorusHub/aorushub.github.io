---
title: Strategi Testing
date: 2025-10-31
categories: [Artikel, Software Testing and Quality Assurance]
tags: [Artikel]
image:
  path: assets/img/post/article/test_strategy_illustration.png
  alt: Strategy Testing Thumbnail
---

##  1. Pengertian Testing

Testing adalah proses **mengevaluasi perangkat lunak** untuk mendeteksi
kesalahan (bug) dan memastikan sistem berfungsi sesuai **kebutuhan
fungsional maupun non-fungsional**.\
Tujuan utama testing yaitu memastikan **kualitas software**, **keamanan
sistem**, **pengalaman pengguna yang baik**, dan **efisiensi biaya
pengembangan**.

  -----------------------------------------------------------------------
  Aspek                    Penjelasan
  ------------------------ ----------------------------------------------
  **Tujuan Testing**       Menemukan bug dan memastikan sistem bekerja
                           sesuai kebutuhan

  **Manfaat**              Mengurangi risiko kegagalan, meningkatkan
                           kepercayaan stakeholder, efisiensi biaya

  **Hasil Akhir**          Software berkualitas tinggi, aman, stabil, dan
                           memenuhi kebutuhan pengguna
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 2. Software Testing Life Cycle (STLC)

STLC adalah **proses sistematis** yang terdiri dari tahapan berurutan
untuk menjamin kualitas perangkat lunak.

  ------------------------------------------------------------------------
  Tahap            Deskripsi                 Hasil Utama
  ---------------- ------------------------- -----------------------------
  **1. Test        Menentukan strategi,      Dokumen rencana pengujian
  Planning**       waktu, biaya, lingkungan, 
                   dan peran pengujian.      

  **2. Test        Membuat test case, data   Daftar test case dan RTM
  Design**         uji, dan skenario         (Requirement Traceability
                   pengujian.                Matrix)

  **3. Test        Menjalankan pengujian     Hasil pelaksanaan uji
  Execution**      (unit, integrasi, sistem, 
                   acceptance).              

  **4. Test        Menganalisis hasil,       Laporan hasil uji dan
  Reporting &      mencatat bug, dan memberi perbaikan
  Analysis**       rekomendasi.              
  ------------------------------------------------------------------------

------------------------------------------------------------------------

## 3. Jenis Pengujian Berdasarkan Abstraksi

  ------------------------------------------------------------------------
  Jenis Testing                      Tujuan            Contoh
  ---------------------------------- ----------------- -------------------
  **Unit Testing**                   Menguji fungsi    Menguji fungsi
                                     atau metode       perhitungan diskon.
                                     tunggal agar      
                                     hasilnya akurat.  

  **Integration Testing**            Memastikan        Modul login dan
                                     interaksi antar   profil saling
                                     modul berjalan    terhubung.
                                     baik.             

  **System Testing**                 Menguji sistem    Aplikasi e-commerce
                                     secara            dapat menangani
                                     keseluruhan       1000 pengguna.
                                     terhadap          
                                     spesifikasi.      

  **Acceptance Testing**             Validasi akhir    Klien menyetujui
                                     oleh              aplikasi sebelum
                                     pengguna/klien    diluncurkan.
                                     sebelum rilis.    
  ------------------------------------------------------------------------

------------------------------------------------------------------------

## 4. Jenis Pengujian Berdasarkan Fungsi

  --------------------------------------------------------------------------
  Jenis              Fokus             Contoh              Tujuan
  ------------------ ----------------- ------------------- -----------------
  **Fungsional       Menguji fungsi    Login, reset        Menjamin fungsi
  Testing**          utama sistem      password,           berjalan dengan
                     sesuai kebutuhan. pembayaran online.  benar.

  **Non-Fungsional   Menguji performa, Uji performa saat   Menilai kualitas
  Testing**          keamanan, dan     flash sale, uji     dan ketahanan
                     reliabilitas.     respon sistem.      sistem.
  --------------------------------------------------------------------------

------------------------------------------------------------------------

## 5. Jenis Pengujian Berdasarkan Domain

  ------------------------------------------------------------------------
  Jenis Testing               Fokus          Contoh          Tujuan
  --------------------------- -------------- --------------- -------------
  **Performance Testing**     Kinerja &      Menguji website Menjamin
                              stabilitas     saat traffic    sistem tetap
                              sistem di      tinggi.         cepat &
                              bawah beban                    stabil.
                              tinggi.                        

  **Security Testing**        Identifikasi   Uji serangan    Melindungi
                              celah          SQL injection,  data pengguna
                              keamanan.      XSS.            dan sistem.

  **Usability Testing**       Kemudahan      Evaluasi        Memastikan
                              penggunaan     kemudahan       aplikasi
                              bagi user.     navigasi dan    ramah
                                             ikon.           pengguna.
  ------------------------------------------------------------------------

------------------------------------------------------------------------

## 6. Jenis Pengujian Berdasarkan Struktur

  -------------------------------------------------------------------------
  Jenis Testing         Penjelasan        Kelebihan       Kekurangan
  --------------------- ----------------- --------------- -----------------
  **Black-Box Testing** Penguji tidak     Mudah           Tidak mendeteksi
                        tahu struktur     dilakukan,      bug dalam logika
                        kode, hanya       sesuai sudut    internal.
                        menguji           pandang user.   
                        input--output.                    

  **White-Box Testing** Penguji memahami  Dapat menemukan Membutuhkan waktu
                        struktur dan      bug tersembunyi dan pengetahuan
                        logika kode.      & meningkatkan  teknis tinggi.
                                          kualitas kode.  
  -------------------------------------------------------------------------

------------------------------------------------------------------------

## 7. Pelaporan & Analisis Testing

Setelah pengujian, hasil perlu dianalisis secara menyeluruh untuk
mengukur kualitas dan menentukan langkah perbaikan.

  -----------------------------------------------------------------------
  Komponen                     Isi Pelaporan
  ---------------------------- ------------------------------------------
  **Ringkasan Hasil**          Jumlah test case yang berhasil, gagal, dan
                               belum dijalankan.

  **Evaluasi Kualitas**        Apakah sistem memenuhi spesifikasi
                               fungsional dan non-fungsional.

  **Identifikasi Bug**         Jenis kesalahan, tingkat keparahan, dan
                               status perbaikan.

  **Rekomendasi**              Saran peningkatan performa, keamanan, dan
                               stabilitas.

  **Analitik & Grafik**        Tren jumlah bug, peningkatan hasil
                               pengujian dari waktu ke waktu.
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 8. Kesimpulan

Testing merupakan **tahap penting dalam SDLC (Software Development Life
Cycle)** yang tidak hanya mencari kesalahan, tetapi juga menjamin
**kualitas dan keandalan sistem** sebelum dirilis ke pengguna.\
Dengan penerapan testing yang baik, pengembang dapat:

-   Menghindari biaya besar akibat bug di tahap akhir\
-   Menjamin performa dan keamanan aplikasi\
-   Meningkatkan kepuasan pengguna dan reputasi sistem

  -----------------------------------------------------------------------
  Aspek Utama                                   Dampak
  --------------------------------------------- -------------------------
  **Kualitas Produk**                           Software lebih stabil,
                                                aman, dan bebas bug.

  **Kepercayaan Pengguna**                      Peningkatan kepuasan dan
                                                loyalitas pengguna.

  **Efisiensi Proyek**                          Waktu perbaikan
                                                berkurang, biaya lebih
                                                terkendali.
  -----------------------------------------------------------------------
