# Pesan Cinta Interaktif

Sebuah halaman web interaktif yang romantis untuk mengungkapkan perasaan cinta kepada seseorang yang spesial. Halaman ini menampilkan animasi hati yang mengambang, pesan manis, dan tombol "Gamau" yang akan bergerak saat dihover.

![Preview Pesan Cinta](https://i.imgur.com/JR8qMSe.jpg)

## Fitur

- 💖 Animasi hati yang mengambang di latar belakang
- ✨ Efek animasi yang menarik pada elemen-elemen halaman
- 💬 Pesan cinta yang romantis dan manis
- 🎵 Musik latar yang otomatis diputar saat tombol "Mau" diklik
- 📱 Responsif untuk perangkat mobile dan desktop
- 😄 Tombol "Gamau" yang bergerak saat dihover, tidak bisa diklik!
- ❤️ Pesan spesial yang muncul setelah tombol "Mau" diklik

## Cara Menggunakan

1. Buka file `index.html` di browser web apa pun
2. Halaman akan menampilkan pesan cinta dan dua tombol: "Mau" dan "Gamau"
3. Jika mencoba menekan tombol "Gamau", tombol akan bergerak menjauh
4. Ketika tombol "Mau" diklik, pesan cinta spesial akan muncul dengan animasi hati tambahan

## Kustomisasi

### Mengubah Pesan

Untuk mengubah pesan yang ditampilkan:

1. Buka file `index.html` dengan editor teks
2. Cari bagian dengan class `message` dan ubah teksnya
3. Untuk pesan setelah tombol "Mau" diklik, cari elemen dengan id `love-response`

### Mengubah Gambar

Untuk mengubah gambar:

1. Buka file `index.html` dengan editor teks
2. Cari tag `<img>` dan ubah atribut `src` ke URL gambar yang diinginkan
3. Pastikan juga mengubah URL gambar di array `preloadImages` dalam script JavaScript

### Mengubah Warna

Untuk mengubah skema warna:

1. Buka file `index.html` dengan editor teks
2. Cari bagian `:root` dalam tag `<style>` dan ubah nilai variabel warna
   ```css
   :root {
       --primary-color: #ff6b88;
       --secondary-color: #ff8fab;
       --accent-color: #ffc2d1;
       --text-color: #5e5e5e;
       --light-bg: #fff5f7;
   }
   ```

## Kompatibilitas Mobile

Halaman web ini sepenuhnya responsif dan bekerja dengan baik di perangkat mobile:

- Layout menyesuaikan dengan ukuran layar
- Tombol lebih besar untuk memudahkan interaksi sentuh
- Pada perangkat mobile, tombol "Gamau" akan berubah posisi saat disentuh

## Teknologi yang Digunakan

- HTML5
- CSS3 dengan animasi dan transisi
- JavaScript untuk interaktivitas
- Font Google (Poppins dan Dancing Script)
- Animate.css untuk animasi elemen
- SVG untuk ikon hati yang mengambang

## Tips Penggunaan

- Untuk pengalaman terbaik, gunakan browser modern seperti Chrome, Firefox, atau Edge
- Pastikan JavaScript diaktifkan di browser
- Jika musik tidak otomatis diputar, ini mungkin karena kebijakan browser yang memblokir autoplay

---

Dibuat dengan ❤️ untuk mengungkapkan perasaan cinta
