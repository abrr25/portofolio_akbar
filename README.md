portfolio-akbar/
│
├── biografi.html      
├── tentang.html       
├── style.css         
└── foto/             
    ├── foto_akbar.jpg
    ├── foto1.jpg
    ├── foto2.jpg
    ├── foto3.jpg
    └── foto4.jpg
# 🌐 Portofolio Sederhana - Muhammad Akbar Rizqiullah Razak

Repositori ini berisi kodingan sederhana untuk membuat **website portofolio pribadi** dengan HTML & CSS.  
Website terdiri dari dua halaman: **Biografi** dan **Tentang Saya**.

---

## 📂 Struktur File
- **biografi.html** → Halaman utama yang menampilkan nama, foto profil, deskripsi singkat, dan tombol menuju halaman "Tentang Saya".
- **tentang.html** → Halaman lanjutan berisi riwayat pendidikan, daftar hobi, dan galeri foto.
- **style.css** → File stylesheet yang mengatur tampilan halaman agar lebih menarik.
- **/foto** → Folder gambar (foto profil dan foto galeri).

---

## 📝 Penjelasan kode

 1. biografi.html
- Bagian utama berisi:
  - **Foto profil** berbentuk lingkaran yang diletakkan di pojok kiri atas.
  - **Kontainer (card)** berisi nama, deskripsi singkat, dan tombol navigasi.
- Menggunakan CSS eksternal dari `style.css`.

 2. tentang.html
- Bagian utama berisi:
  - **Deskripsi pribadi** dalam elemen paragraf `<p>`.
  - **Riwayat Pendidikan** dalam list `<ul>`.
  - **Hobi** yang ditampilkan dengan gaya serupa.
  - **Galeri Foto** menggunakan CSS Grid.
  - **Tombol kembali** ke halaman biografi.

 3. style.css
Beberapa aturan penting:
- `font-family` → untuk menentukan jenis font yang dipakai.
- `background: linear-gradient(...)` → memberi efek gradasi pada latar.
- `color` → mengatur warna teks.
- `text-align` → untuk meratakan teks (tengah).
- `min-height: 100vh` → agar kontainer memenuhi layar.
- `display: flex` dan `grid` → untuk mengatur tata letak (foto, galeri).
- `border-radius` dan `box-shadow` → membuat tampilan lebih modern dan tidak monoton.
- `.btn` → styling tombol dengan warna gradasi + animasi hover.

 4. foto/
- Menyimpan gambar yang dipanggil oleh `<img src="...">` pada HTML.

---

