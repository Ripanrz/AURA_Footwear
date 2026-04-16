# AURA Footwear 👟

> ![Screenshot AURA Footwear](SS_Aura_Footwear)

AURA Footwear adalah template *landing page* e-commerce yang dirancang khusus untuk merek sepatu olahraga premium. Mengusung gaya modern, minimalis, dan berfokus pada konversi penjualan, antarmuka ini terinspirasi oleh merek-merek ternama namun dengan pendekatan visual yang lebih bersih dan estetika aksen neon yang tajam.

---

## ✨ Fitur Utama

* **Desain Glassmorphism:** Navigasi atas (header) menggunakan efek kaca yang elegan saat di-*scroll*.
* **Animasi Scroll Halus:** Elemen-elemen halaman akan muncul secara perlahan (*fade-in up*) saat pengguna menggulir ke bawah, memberikan kesan dinamis.
* **Interaksi Mikro (Micro-interactions):** Efek *hover* yang mulus pada tombol, kartu produk, dan gambar.
* **Kaca Pembesar Produk (Custom Image Zoom):** Pengguna dapat mengarahkan kursor ke gambar utama produk untuk melihat detail material sepatu dari jarak dekat.
* **Pemilih Ukuran Interaktif:** Logika JavaScript sederhana untuk memilih ukuran sepatu dan mengabaikan opsi ukuran yang kehabisan stok.
* **Responsif Penuh:** Tampilan menyesuaikan secara otomatis untuk perangkat seluler, tablet, dan desktop (*Mobile-First approach*).

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun seringan mungkin tanpa memerlukan proses *build* yang rumit:

* **HTML5:** Struktur semantik.
* **Tailwind CSS (via CDN):** *Utility-first* CSS framework untuk gaya yang cepat dan konsisten.
* **Vanilla JavaScript:** Logika fungsionalitas (Intersection Observer untuk animasi, kalkulasi koordinat untuk *zoom*, dan logika pemilihan produk).
* **Google Fonts:** Menggunakan font **Inter** untuk tipografi yang bersih dan tingkat keterbacaan yang tinggi.

## 🚀 Cara Menjalankan Secara Lokal

Karena proyek ini hanya terdiri dari file statis, Anda tidak perlu menginstal Node.js atau *package manager* lainnya.

1.  **Clone Repositori ini:**
    ```bash
    git clone [https://github.com/Ripanrz/AURA_Footwear.git](https://github.com/Ripanrz/AURA_Footwear.git)
    ```
2.  Buka folder proyek yang baru saja di-clone.
3.  Klik ganda pada file `index.html` untuk membukanya di browser web favorit Anda (Chrome, Firefox, Safari, Edge).

**Opsional:** Jika Anda menggunakan VS Code, Anda bisa menginstal ekstensi **Live Server** dan mengklik "Go Live" untuk pengalaman pengembangan yang lebih baik (halaman akan *refresh* otomatis jika Anda mengubah kode).

## 📂 Struktur File

```text
aura-footwear/
│
├── index.html     # File utama (merangkum HTML, konfigurasi Tailwind, CSS kustom, dan JS)
└── README.md      # Dokumentasi proyek ini
