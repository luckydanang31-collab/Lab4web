# Laporan Praktikum Pemrograman Web
**Praktikum 4: CSS Layout & Semantics Element**

* **Nama:** [Nama Anda]
* **NIM:** [NIM Anda]
* **Kelas:** [Kelas Anda]
* **Dosen Pengampu:** Agung Nugroho
* **Instansi:** Universitas Pelita Bangsa

---

## 📌 Deskripsi Praktikum
Praktikum ini bertujuan untuk memahami dan mengimplementasikan konsep dasar pembuatan layout halaman web menggunakan HTML5 dan CSS. Fokus pembahasan meliputi:
1. Konsep **Box Model** (Margin, Border, Padding, dan Content).
2. Properti **CSS Float** dan teknik **Clearfix**.
3. Penggunaan **HTML5 Semantic Elements** (`<header>`, `<nav>`, `<section>`, `<aside>`, `<article>`, `<footer>`).
4. Pembuatan Halaman Web Sederhana multi-halaman (`Home`, `About`, dan `Contact`).

---

## 📁 Struktur Folder Project
```text
Lab4Web/
├── lab4_box.html     # Latihan dasar Box Model & CSS Float
├── lab4_layout/
│   ├── home.html     # Halaman utama (Home)
│   ├── about.html    # Halaman profil & portofolio (About)
│   ├── kontak.html   # Halaman formulir kontak (Contact)
│   └── style.css     # File stylesheet CSS
└── README.md         # Dokumentasi laporan praktikum
```

---

## 🚀 Langkah-Langkah Praktikum & Penjelasan

### 1. Praktikum Box Model dan CSS Float (`lab4_box.html`)
Pada tahap awal, dibuat latihan sederhana untuk memahami elemen kotak (`div`), pengaturan float `left`, serta teknik penghentian alur mengambang (*clearfix*) menggunakan properti `clear`.

* **Langkah Kerja:**
  * Membuat struktur dasar file `lab4_box.html`.
  * Menambahkan elemen `div1`, `div2`, dan `div3` dengan properti `float: left`.
  * Menambahkan `div4` dengan properti `clear: left` untuk menguji efek clearfix agar tidak berdampak ke baris berikutnya.

* **Screenshot:**
  *(Sematkan screenshot hasil tampilan browser lab4_box.html di bawah ini)*
  ![Hasil Box Element](screenshots/box_element.png)

---

### 2. Membuat Kerangka Layout Sederhana (`home.html` & `style.css`)
Selanjutnya adalah merancang kerangka halaman web menggunakan tag semantik HTML5 agar struktur dokumen mudah dipahami dan lebih akseptabel secara SEO/web standar.

* **Elemen Semantik yang digunakan:**
  * `<header>`: Bagian judul web.
  * `<nav>`: Menu navigasi utama.
  * `<section id="hero">`: Area promosi/banner utama.
  * `<section id="wrapper">`: Wadah utama konten dan sidebar.
    * `<section id="main">`: Tempat artikel dan konten utama.
    * `<aside id="sidebar">`: Menu/widget samping.
  * `<footer>`: Bagian catatan kaki website.

* **Screenshot Halaman Utama:**
  *(Sematkan screenshot tampilan Halaman Home)*
  ![Tampilan Halaman Home](screenshots/home_layout.png)

---

### 3. Tugas 1: Membuat Layout Menu About (`about.html`)
Membuat halaman pendukung **About** yang menyajikan deskripsi profil singkat, latar belakang, dan daftar keahlian/portofolio pembuat web.

* **Fitur Halaman:**
  * Navigasi aktif berpindah ke tab **About**.
  * Hero section khusus yang mendeskripsikan halaman tentang.
  * Bagian konten utama berisi deskripsi gambar, biografi singkat, serta *un-ordered list* berisi keahlian.
  * Tetap mempertahankan sidebar dan footer agar konsisten dengan tema utama.

* **Screenshot Halaman About:**
  *(Sematkan screenshot tampilan Halaman About)*
  ![Tampilan Halaman About](screenshots/about_page.png)

---

### 4. Tugas 2: Membuat Layout Menu Contact (`kontak.html`)
Membuat halaman **Contact** yang berisi formulir untuk menerima masukan atau pesan dari pengunjung web.

* **Fitur Halaman:**
  * Formulir interaktif dengan *input field*: Nama Lengkap, Email, dan Pesan (Textarea).
  * Tombol kirim (*submit button*) yang diberi gaya khusus melalui CSS.
  * Informasi alamat dan kontak tambahan pada area sidebar.

* **Screenshot Halaman Kontak:**
  *(Sematkan screenshot tampilan Halaman Kontak)*
  ![Tampilan Halaman Kontak](screenshots/contact_page.png)

---

## 🔍 Kesimpulan
Melalui praktikum ini, dapat disimpulkan bahwa:
1. **HTML5 Semantic Elements** mempermudah penataan kode HTML menjadi lebih terstruktur dan berstandar ketimbang menggunakan `<div>` secara berlebihan.
2. Penggunaan **CSS Float** bersama **Box Model** sangat membantu dalam penataan kolom tata letak (seperti layout dua kolom: *Main Content* dan *Sidebar*).
3. Konsistensi tampilan (*look & feel*) antarhalaman dapat dicapai secara efisien dengan memanfaatkan satu file external stylesheet (`style.css`).

---
*© 2026 Universitas Pelita Bangsa - Pemrograman Web*