# Praktikum 6: DOM dan Event JavaScript - Pemrograman Web
Repository ini dibuat untuk menyelesaikan tugas Praktikum 6 Pemrograman Web.
 
## Identitas Mahasiswa
 
| Keterangan      | Data                 |
| --------------- | -------------------- |
| **Nama**        | Muhammad Al Fajri    |
| **Kelas**       | I251D                |
| **NIM**         | 312510353            |
| **Mata Kuliah** | Pemrograman Web      |
| **Dosen**       | Agung Nugroho, S.Kom., M.Kom. |
 
---
 
## Struktur File Proyek
 
```
Project/
│
├── lab6_dom_event/
│   ├── index.html
│   ├── script.js
│   ├── style.css
│   └── README.md
│
└── MiniProject/
    ├── index.html
    ├── script.js
    └── style.css
```

<img width="217" height="154" alt="Screenshot 2026-10-29 161050" src="https://github.com/user-attachments/assets/600835fd-7b64-4ac3-8955-2fe51afb00ea" />

---
 ## Langkah-langkah Praktikum
 
### 1. Menyiapkan Dokumen HTML dan Mengubah Teks dengan DOM
 
Membuat dokumen `index.html` dengan judul "Praktikum DOM dan Event" yang berisi `<h1 id="judul">`, `<p id="pesan">`, dan `<button id="tombolAksi">`.
 
<img width="458" height="235" alt="Screenshot 2026-10-29 144621" src="https://github.com/user-attachments/assets/51f4eb56-bc86-4044-8509-4b8b775dcd26" />

Hasil sebelum menggunakan `script.js`:
 
<img width="205" height="122" alt="Screenshot 2026-10-29 144601" src="https://github.com/user-attachments/assets/a456f4ba-a1a1-46e1-880d-893b10681dc5" />


Kemudian dibuat `script.js` untuk mengambil elemen dengan `getElementById()` dan mengubah isinya menggunakan `textContent`.
 
<img width="434" height="89" alt="Screenshot 2026-10-29 144913" src="https://github.com/user-attachments/assets/45501bbe-6f48-4652-8eb9-3210b58bd74e" />

 
Hasil di browser: judul berubah menjadi "Belajar JavaScript DOM" dan pesan menjadi "Konten berhasil diubah oleh JavaScript."
 
<img width="206" height="122" alt="Screenshot 2026-10-29 144818" src="https://github.com/user-attachments/assets/1c43482b-01c9-43a8-bb7e-6698d693d095" />

---
 
### 2. Event Click
 
Menambahkan `addEventListener("click", ...)` pada tombol "Klik saya" untuk menampilkan waktu saat tombol ditekan.

<img width="508" height="76" alt="Screenshot 2026-10-29 145058" src="https://github.com/user-attachments/assets/9516048e-aac5-44ee-8538-4b2f47979ba9" />

Hasil di browser: setelah tombol diklik, muncul teks "Tombol diklik pada 18.34.36" (sesuai waktu saat diklik).
 
<img width="213" height="113" alt="Screenshot 2026-10-29 145558" src="https://github.com/user-attachments/assets/5954e103-cf95-4e4b-9d30-ab1173d93db3" />

---
 
### 3. Mengubah Kelas dan Gaya CSS
 
Menambahkan paragraf `#teksGaya` dan tombol `#tombolGaya` pada HTML. Saat tombol diklik, class `highlight` dan `teks-besar` di-*toggle* menggunakan `classList.toggle()`.
 
<img width="729" height="157" alt="image" src="https://github.com/user-attachments/assets/b7aacaea-69d1-4594-b0af-288abef84fca" />

<img width="401" height="89" alt="Screenshot 2026-10-29 150605" src="https://github.com/user-attachments/assets/2ab8797c-278c-4801-8f77-6578f3f556cc" />

CSS yang digunakan pada `style.css`:
-
 
<img width="268" height="144" alt="Screenshot 2026-10-29 150656" src="https://github.com/user-attachments/assets/da4bfb4e-ffbf-426c-9182-da44a92f41b3" />

 
Hasil di browser: teks berubah menjadi bergaya highlight dengan ukuran font lebih besar, dan kembali normal jika tombol diklik lagi.
 
<img width="218" height="81" alt="Screenshot 2026-10-29 150101" src="https://github.com/user-attachments/assets/59724b2d-f662-46bf-8be0-a0d85e6e4465" />

<img width="210" height="101" alt="Screenshot 2026-10-29 150112" src="https://github.com/user-attachments/assets/ab8424b2-5f38-4f64-8fa1-1767227e9df4" />

---
 
### 4. Event Input dan Penghitung Karakter
 
Menambahkan `<input type="text" id="namaInput" maxlength="40">` dan `<span id="jumlahKarakter">`. Event `input` digunakan agar jumlah karakter terupdate setiap kali pengguna mengetik.
 
<img width="451" height="43" alt="Screenshot 2026-10-29 150502" src="https://github.com/user-attachments/assets/9d164492-70f7-4768-9c17-15dbedf5ea1e" />

<img width="482" height="71" alt="Screenshot 2026-10-29 150410" src="https://github.com/user-attachments/assets/435b2a0e-9b34-47d2-b561-6912a86ee600" />

Hasil di browser: saat mengetik "Muhammad Al Fajri", tampil "Jumlah karakter: 17".
 
<img width="213" height="101" alt="Screenshot 2026-10-29 150339" src="https://github.com/user-attachments/assets/f0a8240f-8b1e-4499-8b4f-3ea2c19b2d5f" />

<img width="213" height="96" alt="Screenshot 2026-10-29 150353" src="https://github.com/user-attachments/assets/2320cce6-fc3a-4496-859e-cf443c14a687" />

---
 
### 5. Validasi Form Pendaftaran
 
<img width="458" height="143" alt="Screenshot 2026-10-29 151443" src="https://github.com/user-attachments/assets/d7194301-7bb4-4abb-b80e-4f25c09c3e96" />

<img width="479" height="371" alt="Screenshot 2026-10-29 151505" src="https://github.com/user-attachments/assets/729977da-4c2f-4df7-a246-b026b3414343" />

Hasil di browser:
 
- Input valid → muncul pesan "Validasi berhasil. Formulir siap diproses."
- Email tidak valid (`emailtidakvalid`) → muncul pesan "Masukkan email yang valid."
<img width="385" height="17" alt="Screenshot 2026-10-29 151103" src="https://github.com/user-attachments/assets/6ae2d70d-3906-4547-ad29-7d8baafe95c0" />

<img width="385" height="19" alt="Screenshot 2026-10-29 151131" src="https://github.com/user-attachments/assets/9620c3fd-ee88-48ac-be8d-d44ce45ee3d2" />

<img width="383" height="39" alt="Screenshot 2026-10-29 151143" src="https://github.com/user-attachments/assets/d76b8dd3-682f-4973-bbf6-482104bbc34c" />

<img width="391" height="41" alt="Screenshot 2026-10-29 151226" src="https://github.com/user-attachments/assets/ac7da788-a352-4a52-a46f-511977a0e1cb" />

---
 
### 6. Daftar Tugas Sederhana (To-do List)
 
<img width="399" height="113" alt="Screenshot 2026-10-29 151906" src="https://github.com/user-attachments/assets/25ee086d-61c7-4d17-9bde-324ee7fd2a65" />

<img width="449" height="400" alt="Screenshot 2026-10-29 151806" src="https://github.com/user-attachments/assets/76eb5761-90d0-49e6-894b-276ffadf58a8" />

Hasil di browser:
<img width="214" height="58" alt="Screenshot 2026-10-29 151921" src="https://github.com/user-attachments/assets/1204740e-b27c-4b1c-92b3-ba58592843e6" />

<img width="202" height="92" alt="Screenshot 2026-10-29 151947" src="https://github.com/user-attachments/assets/9f405f56-d972-4d85-8a0b-5ba200f14b0e" />

<img width="220" height="104" alt="Screenshot 2026-10-29 151955" src="https://github.com/user-attachments/assets/7ef886e1-aa8a-4b93-82be-eee57227af71" />

---
 
## Mini Project: Form Pendaftaran Workshop

<img width="627" height="491" alt="Screenshot 2026-10-29 163103" src="https://github.com/user-attachments/assets/b179bfbc-5019-4d67-903c-147cec6b9f63" />

<img width="595" height="386" alt="Screenshot 2026-10-29 163125" src="https://github.com/user-attachments/assets/4a5540f5-a3ac-44b9-b101-eb5c90a51ab2" />

<img width="593" height="191" alt="Screenshot 2026-10-29 163140" src="https://github.com/user-attachments/assets/d832a2da-c134-4798-965f-b0d6f0695622" />

Code Script.Js
---
<img width="624" height="491" alt="Screenshot 2026-10-29 163315" src="https://github.com/user-attachments/assets/af89478e-e366-440c-ac12-14b538d678dd" />
<img width="617" height="461" alt="Screenshot 2026-10-29 163332" src="https://github.com/user-attachments/assets/8d5aaefd-7c94-4726-b3ee-67d5fd7c705d" />
<img width="611" height="464" alt="Screenshot 2026-10-29 163350" src="https://github.com/user-attachments/assets/e74838da-3136-469b-986b-3cdb26b4f022" />
<img width="625" height="160" alt="Screenshot 2026-10-29 163403" src="https://github.com/user-attachments/assets/dca204a4-c55d-4932-b879-4f2619d40f57" />

**Code Style.css**
<img width="626" height="488" alt="Screenshot 2026-10-29 163611" src="https://github.com/user-attachments/assets/c1fa1938-b6c8-4db5-a102-f6d1b399aec2" />
<img width="617" height="459" alt="Screenshot 2026-10-29 163631" src="https://github.com/user-attachments/assets/fb02ba70-661d-4866-b8e6-84430c3cd8ef" />
<img width="614" height="445" alt="Screenshot 2026-10-29 163647" src="https://github.com/user-attachments/assets/6c1f4c54-019e-4a89-ab01-eb9f55431572" />
<img width="623" height="419" alt="Screenshot 2026-10-29 163703" src="https://github.com/user-attachments/assets/dd50df16-020e-406d-920b-b6d5c7ec0a8e" />


Hasil tampilan di browser (desktop):
--- 
<img width="959" height="535" alt="Screenshot 2026-10-29 155038" src="https://github.com/user-attachments/assets/5f0a8224-8341-4870-9a40-c0468e73cb83" />

<img width="959" height="536" alt="Screenshot 2026-10-29 155129" src="https://github.com/user-attachments/assets/d44722f5-091e-4771-92d5-e28ce614c3b5" />

---
 
## Eksperimen Mandiri
 
### 1. To-do List dengan Tombol Hapus
 
Setiap item tugas diberi tombol "Hapus" (class `btn-hapus`). Saat diklik, item dihapus dari daftar dan muncul pesan "Tugas dihapus."
 
<img width="427" height="238" alt="Screenshot 2026-10-29 152221" src="https://github.com/user-attachments/assets/2e7304d6-9ee3-46a2-9518-5c1010e28e7e" />


code Script.js
---
<img width="423" height="246" alt="Screenshot 2026-10-29 153149" src="https://github.com/user-attachments/assets/0b08525c-eb95-40fc-8a8c-fb400f9bd4fe" />


Sebelum dihapus:
---
 <img width="340" height="219" alt="image" src="https://github.com/user-attachments/assets/87c6ddc5-0012-457d-9d46-7803f1f3a460" />

Sesudah tugas "Pemograman Web" dihapus:
---

<img width="364" height="209" alt="image" src="https://github.com/user-attachments/assets/0c7411d9-98c5-4069-b713-afc302bc2850" />
 
### 3. Validasi Tambahan: Nama Minimal 3 Karakter
 
Pada Form Pendaftaran Workshop ditambahkan validasi tambahan menggunakan `querySelector()` untuk memastikan nama minimal terdiri dari 3 karakter. Jika kurang, `preventDefault()` dan `stopImmediatePropagation()` dipanggil, pesan "Nama minimal terdiri dari tiga karakter." ditampilkan, dan fokus dikembalikan ke input nama.
 
<img width="550" height="91" alt="image" src="https://github.com/user-attachments/assets/b03a5fb4-e4d1-4b70-b133-b190ff4ff4c9" />

Code script.Js
---
<img width="422" height="266" alt="image" src="https://github.com/user-attachments/assets/377c27a3-c0dc-4017-8c98-ce2fcf1816e2" />


Tampilan pilihan sesi pada mobile
--
<img width="279" height="113" alt="Screenshot 2026-10-29 164241" src="https://github.com/user-attachments/assets/08326fbc-777b-4b35-90a4-4af95e8f1005" />

Dropdown pada From Sesi Workshop
---
<img width="280" height="341" alt="Screenshot 2026-10-29 164424" src="https://github.com/user-attachments/assets/dfd10ead-10dc-4cfc-8b56-5b41691ec7d7" />



### 4. Menyembunyikan / Menampilkan Paragraf dengan Class CSS
 
Menambahkan class `.sembunyi { display: none; }` dan tombol `#btnToggleParagraf`. Saat diklik, class `sembunyi` di-*toggle* pada paragraf dan teks tombol berganti antara "Sembunyikan" dan "Tampilkan".
 
<img width="1078" height="136" alt="image" src="https://github.com/user-attachments/assets/6341faa2-a903-4982-be76-f2d3aa769921" />

Code Style.Css
---
<img width="320" height="105" alt="image" src="https://github.com/user-attachments/assets/117ba51a-1f01-4596-b0a0-f49939cbc841" />

Code Script.js
---
<img width="817" height="122" alt="image" src="https://github.com/user-attachments/assets/89f8ce73-d447-479e-81cd-9c7bd0afbaf8" />


 Hasil nya :

 Sebelum di klik 
 ---
<img width="498" height="117" alt="image" src="https://github.com/user-attachments/assets/a1a5bae9-3fcf-4a58-9f6b-d1429af55182" />

Setelah di klik 
---
<img width="267" height="91" alt="image" src="https://github.com/user-attachments/assets/1db171cb-8997-471d-bcba-fd6791a71aa2" />

### 5. Script di `<head>` Tanpa `defer`
 
Tag `<script src="script.js">` dipindahkan ke dalam `<head>` **tanpa** atribut `defer`. Hasilnya, console menampilkan error:

<img width="678" height="169" alt="image" src="https://github.com/user-attachments/assets/4ad8eaca-0b8c-4da7-9e96-1d3519322ab4" />

 
Error terjadi karena script dijalankan sebelum elemen HTML selesai dimuat, sehingga `getElementById()` mengembalikan `null`. Solusinya adalah meletakkan script di akhir `<body>` atau menambahkan atribut `defer` pada tag script.
 
<img width="827" height="334" alt="image" src="https://github.com/user-attachments/assets/7ca377bf-0768-4b60-822e-84c52d3ddbc6" />
