# 🌐 Tugas Bootstrap - Layout Responsif

Proyek ini merupakan implementasi halaman web **responsif** menggunakan **Bootstrap 5**.  
Halaman ini dirancang dengan tampilan **clean, profesional, dan modern**, menampilkan dua gambar berbeda—  
satu menggambarkan *Naruto & Sasuke*, dan satu lagi dari *Solo Leveling*—untuk memperlihatkan kemampuan tata letak fleksibel di berbagai ukuran layar.

---

## 📁 Struktur Proyek
📦 project-folder
├── index.html
├── tugas.jpg ← Gambar Naruto & Sasuke
├── tugas1.jpg ← Gambar Solo Leveling
└── README.md



---

## 🧩 Deskripsi Halaman

### 1. Header & Navbar
Bagian atas halaman menggunakan **navbar Bootstrap** dengan warna putih dan bayangan lembut.  
Navbar berisi tautan navigasi:
- **Beranda**
- **Konten**
- **Kontak**

Navbar bersifat **responsif**, sehingga otomatis berubah menjadi tombol menu di layar kecil.

---

### 2. Bagian Utama (Main Content)
Bagian utama halaman berisi **dua kolom responsif** yang menampilkan konten berbeda:

#### 🌀 Kolom 1 – Naruto & Sasuke
Menampilkan gambar `tugas.jpg` yang menggambarkan dua karakter legendaris dari serial *Naruto*.  
Keduanya melambangkan keseimbangan antara tekad dan ambisi.  
Dalam konteks desain web, ini merepresentasikan keseimbangan antara sisi kreatif (Naruto) dan logika teknis (Sasuke) dalam proses pengembangan web.

#### ⚡ Kolom 2 – Solo Leveling
Menampilkan gambar `tugas1.jpg` yang menggambarkan karakter utama *Sung Jin-Woo* dari seri *Solo Leveling*.  
Gambar ini merepresentasikan **semangat berkembang dan evolusi diri**, sama seperti pengembang web yang terus belajar memperbaiki tampilan dan fungsionalitas situsnya.

Setiap kolom menggunakan komponen **`card`** dari Bootstrap yang memiliki:
- Sudut lembut (`border-radius`)
- Bayangan halus (`box-shadow`)
- Efek hover ringan (`transform: translateY(-4px)`)

Layout dua kolom ini otomatis berubah menjadi satu kolom ketika dibuka di perangkat mobile berkat sistem grid Bootstrap (`col-12 col-md-6`).

---

### 3. Footer
Bagian bawah halaman menampilkan informasi hak cipta dengan gaya minimalis.  
Footer berwarna putih, memiliki garis tipis di atasnya, dan teks berwarna abu-abu lembut agar tidak mencolok.

---