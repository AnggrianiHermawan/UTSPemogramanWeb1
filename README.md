# UTS PEMOGRAMAN WEB 1 

**Nama:** Anggriani Hermawan  
**NIM:** 312410175  
**Kelas:** TI.24.A2  

## (Proyek Web: Aplikasi Pemesanan Buku Sederhana)
Proyek ini adalah simulasi front-end aplikasi pemesanan buku, dikembangkan menggunakan HTML, CSS, dan JavaScript Murni (Vanilla JS). Proyek ini memenuhi semua kriteria UTS, dengan fokus pada Manipulasi DOM dan Logika Interaksi UI.

## 1. Struktur File Modular
Data dan logika dipisahkan untuk menjaga modularitas dan keterbacaan kode.

<img width="405" height="223" alt="Cuplikan layar 2025-11-03 203640" src="https://github.com/user-attachments/assets/d5fa748f-3e7c-4e1e-a6a5-c2fcf43f7d12" />

---

## 2. Penjelasan Detail File HTML (5 Halaman Utama)
Setiap halaman memiliki class body unik yang digunakan oleh JavaScript untuk menginisiasi fungsi yang relevan.

<img width="413" height="232" alt="Cuplikan layar 2025-11-03 203659" src="https://github.com/user-attachments/assets/ba680d0d-9003-4c7f-92b4-02252b610e06" />

---

## 3. Implementasi JavaScript (Logika dan Manipulasi DOM)
A. js/data.js (Data Source)
File ini berisi dataPengguna, dataKatalogBuku, dan dataTracking. Data ini bersifat statis di sisi klien (tidak terhubung ke server).

B. js/script.js (Logika Aplikasi)
File ini berisi semua fungsi yang mengelola interaksi (Manipulasi DOM - Kriteria C) dan Validasi (Kriteria D).

<img width="418" height="173" alt="Cuplikan layar 2025-11-03 204120" src="https://github.com/user-attachments/assets/48965838-e3ba-4d3c-a431-8352a8243f77" />

---

## 4. File css/style.css
File ini mengatur tampilan visual proyek.

- Tema Warna: Menggunakan variabel CSS (--color-primary, --color-secondary) untuk kemudahan kustomisasi.
- Tata Letak: Menggunakan Grid dan Flexbox untuk mengatur layout utama (misalnya nav-grid).
- Kreativitas (Kriteria F): Memberikan styling untuk pop-up (Modal Box), hover effect pada tabel, dan styling khusus untuk status low stock dan status pengiriman.

## Alur Berpikir Utama
Logika proyek berpusat pada DOM Driven Development: Setiap interaksi pengguna (klik tombol, ubah input) memicu JavaScript untuk mengubah data atau struktur DOM (HTML) yang sedang ditampilkan, memastikan aplikasi selalu interaktif dan up-to-date.

## Tampilan
Halaman login
<img width="1920" height="1080" alt="Cuplikan layar 2025-11-04 172249" src="https://github.com/user-attachments/assets/2d716e8c-d9ee-41b1-99c7-7345ab6a80b8" />

Dashboard
<img width="1920" height="1080" alt="Cuplikan layar 2025-11-04 172324" src="https://github.com/user-attachments/assets/76547a7d-e7b2-49cf-8701-aed6dbb5ccb0" />

Stok
<img width="1920" height="1080" alt="Cuplikan layar 2025-11-04 172337" src="https://github.com/user-attachments/assets/88ef0a84-5f4b-4a5e-a6c1-759be6012f69" />

Checkout
<img width="1920" height="1080" alt="Cuplikan layar 2025-11-04 172402" src="https://github.com/user-attachments/assets/6bbcfcab-74c4-4872-b302-8cc75ef20b14" />

Tracking
<img width="1920" height="1080" alt="Cuplikan layar 2025-11-04 172438" src="https://github.com/user-attachments/assets/fa382e5c-faa2-47a3-a27f-132bc3e5d62f" />

