# 🎨 Roadmap Belajar Fundamental Front-End (Web) untuk Pemula

Roadmap ini dirancang khusus untuk pemula yang ingin terjun ke dunia UI/Web Development namun **belum pernah memegang bahasa pemrograman sama sekali**. 

Di Front-End (FE), kita membangun apa yang *dilihat* dan *disentuh* langsung oleh pengguna di layar. Ibarat membangun sebuah rumah:
- **HTML** adalah fondasi dan batu batanya.
- **CSS** adalah cat warna dan interiornya.
- **JavaScript** adalah aliran listrik yang membuat rumah tersebut hidup (lampu menyala, pintu otomatis, dll).

Mari kita mulai langkah demi langkah!

---

## 🛠️ Fase 1: Persiapan & Cara Kerja Web (Hari 1)
Tujuan: Pahami bagaimana website bekerja dan siapkan alat senjatamu.
- [ ] Pahami konsep sederhana: Apa beda dari *Client* (Browser kita) vs *Server* (Komputer penyedia data web).
- [ ] Instal peramban web modern, disarankan Google Chrome atau Mozilla Firefox.
- [ ] Instal Code Editor: [Visual Studio Code (VS Code)](https://code.visualstudio.com/).
- [ ] Di dalam VS Code, instal ekstensi sangat penting bernama **"Live Server"** (agar saat kamu coding dan menyimpan file, perubahannya otomatis muncul di browser-mu).

---

## 🧱 Fase 2: HTML - Kerangka dan Struktur (Minggu 1)
Tujuan: Membangun struktur kerangka dari sebuah halaman web (tanpa hiasan sama sekali terlebih dahulu).
- [ ] **Struktur Dasar Halaman**: Mengetahui penempatan tag `<html>`, `<head>`, `<title>`, dan `<body>`. (Semua yang akan tayang di website harus masuk dalam `<body>`).
- [ ] **Teks & Paragraf**: Menggunakan Heading (`<h1>` hingga `<h6>`) dan Paragraf (`<p>`).
- [ ] **Daftar/List**: Membuat urutan menggunakan Ordered List (`<ol>`) atau bebas Unordered List (`<ul>`) dan ListItem (`<li>`).
- [ ] **Tautan & Media**:
  - Menyisipkan hipertaut (Link) yang bisa diklik (`<a>`).
  - Menampilkan Gambar (`<img>`).
- [ ] **Form & Input**:
  - Meminta pengguna mengetik teks (`<input>`, `<textarea>`).
  - Menempatkan tombol interaksi (`<button>`).
- [ ] **Semantic HTML**: Konsep membungkus elemen sesuai fungsinya dengan tag khusus (`<header>`, `<nav>`, `<main>`, `<footer>`, `<section>`). Ini penting di masa sekarang agar website dinilai bagus oleh Google!

---

## 🖌️ Fase 3: CSS Fundamental - Pewarnaan & Polesan (Minggu 2)
Tujuan: "Mencat" kerangka monotonmu dengan gaya dan visual yang sedap dipandang mata.
- [ ] **Sintaks Dasar CSS**: Bagaimana menautkan file `.css` ke `html`, dan teori Penyeleksi Dasar (Class `.nama`, ID `#nama`, dan elemen tag).
- [ ] **Warna & Latar**: Mewarnai teks (`color`), mewarnai area latar (`background-color`).
- [ ] **Tipografi / Teks**: Mengganti font (`font-family`), menebalkan/ukuran (`font-weight`, `font-size`), dan letak teks sentral (`text-align`).
- [ ] ⭐️ **Box Model**: *(PERHATIAN! Ini konsep terpenting di dalam CSS seluruh jagat web).*
  - `margin`: Ruang kosong area di *luar* kardus pembatas elemen.
  - `padding`: Ruang kosong area di *dalam* dinding kardus.
  - `border`: Dinding kardus itu sendiri.
  - Pengaturan lebar `width` dan tinggi `height`.

---

## 📐 Fase 4: CSS Layouting Lanjut (Minggu 3)
Tujuan: Menata elemen HTML ke sebelah kiri, kanan, bersebelahan, atau menumpuk dengan mudah dan presisi.
- [ ] **CSS Flexbox** (LENTUR): Pelajari cara membuat item berderet di satu arah sejajar mendatar (baris) atau tegak menurun (kolom). Semua Web Developer menggunakan Flexbox harian!
- [ ] **Responsive Web Design**: Bagaimana desainmu bereaksi dan merapikan tampilannya ketika dibuka via HP (layar sempit) maupun Monitor PC (layar lebar), yakni menggunakan **Media Queries** (`@media`).

---

## 🧠 Fase 5: JavaScript Dasar - Otak Web (Minggu 4 - 5)
Tujuan: Karena sekarang web-mu sudah cakep, saatnya menjadikannya **pintar**. JavaScript lah satu-satunya bahasa pemrograman "sejati" yang dipahami oleh Browser internet manapun.
- [ ] **Variabel**: Cara JS mengingat data menggunakan kunci `let` dan `const`.
- [ ] **Tipe Data**: Nilai text (`String`), nilai Angka (`Number`), dan Benar/Salah (`Boolean`).
- [ ] **Logika Percabangan (Kondisi)**: Melakukan perintah pakai `If / Else` sesuai pertimbangan.
- [ ] **Fungsi (`function`)**: Mewadahi serangkaian kode tugas spesifik agar bisa diaplikasikan/dieksekusi nanti kapanpun mau tanpa perlu menulisnya ulang.
- [ ] **Array & Objek**: Struktur untuk menulis daftar keranjang data dengan rapi.

---

## ⚡ Fase 6: Manipulasi Layar oleh Javascript (DOM) (Minggu 6)
Tujuan: Bagaimana menghubungkan kepintaran si Javascript agar bisa mengubah dan memerintah file si HTML di layar seketika itu juga!
- [ ] **Konsep DOM (Document Object Model)**: Paham bahwa HTML sebenarnya dibaca JS sebagai "kumpulan pohon objek".
- [ ] **Elemen Selektor JS**: Cara "mencomot" elemen paragraf atau tombol dari dokumen HTML agar masuk ke variabel JavaScript (Contoh: `document.getElementById`, `document.querySelector`).
- [ ] **Manipulasi Teks/Styling**: Cara mengganti warna atau mengganti bacaan teks lewat JS.
- [ ] **Event Listeners (`addEventListener`)**: Mendengarkan respon aksi (Contoh: *"Jalankan fungsi X jika tombol Y warna biru ini Di-KLIK"*).

---

## 🏗️ Fase 7: Proyek Nyata Front-End Pertamamu!
Latihlah kepekaan estetika dan logikamu di project terpisah sebelum kamu mencoba mempelajari *Library/Framework* level industri selanjutnya:

1. **Website Portfolio Pribadi Modern** *(HTML + CSS murni)*:
   - Tampilkan foto, biodata, dan tabel riwayat project fiksi milikmu.
   - Web ini 100% *WAJIB* enak dilihat baik dari monitor lebar maupun jika dikerutkan sebesar layar HP. (Melatih CSS `Flexbox` & `@media` query).
2. **Kalkulator BMI (Body Mass Index)** *(HTML + CSS + Javascript)*:
   - Buatlah UI desain yang estetik dengan form input Tinggi dan Berat.
   - Tangkap input dengan Javascript DOM apabila tombol Submit diklik. 
   - Hasil hitungannya ganti isi Teks kosong di bawah menjadi angka BMI-mu!
3. **Menu Tema: Light/Dark Mode Toggle** *(Javascript Dasar + CSS)*:
   - Bikin sebuah tombol matahari/bulan.
   - Bila diklik, JS akan memicu penambahan identitas *Class Styling* ke tag `<body...>` sehingga tampilan webmu seketika berubah elegan jadi gelap!
4. **Mini To-Do List (Pengelola Tugas) dengan UI cantik**:
   - Terdapat kolom input, dan tombol [Tambah].
   - Jika tombol [Tambah] diklik, elemen list html baru akan tercetak memanjang kebawah layar. Lengkap dengan ada tombol asik bertuliskan [Selesai] atau icon Tempat Sampah untuk memusnahkan elemen tersebut kembali via Fungsi JS. 

---

## 🚀 Selanjutnya Apa? (Berlayar lebih jauh)
Bagi yang menamatkan level ini, kamu kini sukses melewati status pemula. Apa target berikutnya?
- **Git & GitHub**: Sistem penyimpanan sejarah *version control* kode standarisasi sedunia. Supaya kerjamu tidak hilang dan bisa berkolaborasi dengan *Devs* di industri (bekerja tim).
- **CSS Framework**: Alat pelontar cepat untuk menata design tanpa pusing dari nol, misalnya **TailwindCSS** (Sedang populer) atau **Bootstrap**.
- **Frontend Framework Modern**: Kamu bisa beralih dari Javascript polos, ke salah satu library tingkat mahir yang mengolah elemen secara dinamis dan super interaktif ala SPA (*Single Page Application*). **React.js** adalah tujuan penguasa pasar, atau **Vue.js**.
