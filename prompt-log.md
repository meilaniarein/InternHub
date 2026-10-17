# Prompt Log - InternHub Modul 6

## 1. Informasi Proyek

- **Nama Proyek:** InternHub
- **Modul:** Modul 6 - Konversi Desain Figma ke HTML5
- **Tujuan:** Mengubah desain dan prototype InternHub menjadi struktur HTML5 semantik yang valid, mudah dibaca, dan mengikuti user flow.
- **Tools:** Visual Studio Code, Figma, AI Assistant, dan W3C Validator.

## 2. Aturan Pengerjaan

Dalam pengerjaan proyek ini, kode HTML mengikuti ketentuan berikut:

- Menggunakan HTML5 semantik.
- Tidak menggunakan file CSS eksternal.
- Tidak menggunakan tag `<style>` atau atribut inline `style`.
- Tidak menggunakan framework seperti Bootstrap atau Tailwind.
- Menggunakan struktur seperti `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, dan `<footer>` sesuai fungsinya.
- Menggunakan heading secara berurutan dan label yang terhubung dengan input formulir.
- Menggunakan path relatif untuk gambar dan ikon.
- Melakukan validasi HTML menggunakan W3C Validator.

## 3. Riwayat Prompt AI

### Tahap 1 - Membuat Struktur HTML Awal

**Tujuan:** Mengubah desain InternHub menjadi struktur HTML tanpa styling.

**Prompt:**

"Bantu saya membuat kode HTML5 berdasarkan desain Figma proyek InternHub. Gunakan HTML semantik yang rapi dan mudah dibaca. Jangan menggunakan CSS, tag style, inline style, Bootstrap, atau Tailwind. Gunakan struktur HTML sesuai fungsi setiap elemen."

**Hasil:**

AI membantu menyusun kerangka halaman, navigasi, heading, paragraf, gambar, daftar, tautan, dan formulir.

### Tahap 2 - Menyesuaikan Halaman dengan Desain Figma

**Tujuan:** Menyusun konten sesuai halaman dan user flow InternHub.

**Prompt:**

"Buat struktur HTML untuk halaman InternHub sesuai desain dan alur prototype. Pertahankan teks, urutan informasi, gambar, ikon, dan navigasi yang dibutuhkan. Gunakan HTML murni tanpa styling."

**Hasil:**

Struktur HTML dikembangkan untuk halaman beranda, daftar lowongan, detail lowongan, formulir lamaran, halaman sukses, halaman error, saved internship, applications, dan resources.

### Tahap 3 - Menyesuaikan Path Aset

**Tujuan:** Memastikan gambar dan ikon dipanggil dari folder yang benar.

**Prompt:**

"Perbaiki path gambar dan ikon pada kode HTML agar menggunakan folder ./assets/images/. Gunakan nama file yang sesuai dengan aset proyek dan tambahkan atribut alt yang tepat."

**Hasil:**

Path relatif diterapkan pada gambar, logo, dan ikon. Nama file diperiksa agar sesuai dengan file yang tersedia di folder aset.

### Tahap 4 - Memperbaiki Navigasi Antarhalaman

**Tujuan:** Memastikan tautan mengarah ke halaman yang sesuai.

**Prompt:**

"Periksa tautan navigasi pada halaman InternHub. Perbaiki atribut href agar tombol Back, Apply Now, View Details, Continue, Try Again, dan navigasi lainnya mengarah ke nama file HTML yang benar. Jangan mengubah bagian lain yang tidak berkaitan."

**Hasil:**

Tautan antarhalaman diperiksa dan diperbaiki, termasuk navigasi dari halaman aplikasi kembali ke detail lowongan dan dari halaman error menuju detail lowongan.

### Tahap 5 - Audit dan Refaktorisasi HTML

**Tujuan:** Memperbaiki struktur HTML dan aksesibilitas.

**Prompt:**

"Audit kode HTML5 saya. Periksa penggunaan elemen semantik, hierarki heading, section yang belum memiliki heading, atribut alt gambar, label formulir, dan struktur elemen yang tidak diperlukan. Pertahankan isi dan alur halaman serta jangan menambahkan CSS atau JavaScript."

**Hasil:**

Struktur heading dan section diperbaiki berdasarkan hasil pemeriksaan. Atribut alt dan hubungan label-input diperiksa. Elemen HTML disesuaikan dengan fungsinya.

### Tahap 6 - Validasi W3C

**Tujuan:** Memeriksa validitas HTML.

**Prompt:**

"Bantu analisis pesan error atau warning dari W3C Validator pada kode HTML saya. Jelaskan penyebabnya dan berikan perbaikan yang sesuai tanpa mengubah desain, konten, dan alur halaman yang sudah benar."

**Hasil:**

Kode diperiksa menggunakan W3C Validator. Warning terkait heading dan section diperiksa, kemudian kode diperbaiki dan divalidasi kembali.

## 4. Perbandingan Kode Sebelum dan Sesudah Revisi

| Aspek | Sebelum Revisi | Sesudah Revisi |
|---|---|---|
| Struktur HTML | Beberapa bagian perlu dirapikan | Menggunakan elemen semantik sesuai fungsi |
| Navigasi | Beberapa tautan belum mengarah ke file yang benar | Atribut href disesuaikan dengan nama file tujuan |
| Heading | Terdapat warning hierarki heading | Heading diperbaiki sesuai struktur konten |
| Section | Beberapa section belum memiliki heading | Heading ditambahkan jika diperlukan |
| Aset | Path dan nama file perlu diperiksa | Path relatif digunakan dan nama aset dicocokkan |
| Validasi | Masih terdapat warning pada beberapa revisi | Halaman diperiksa kembali menggunakan W3C Validator |

## 5. Evaluasi Penggunaan AI

AI digunakan untuk membantu menyusun kode awal, menganalisis warning validator, dan memperbaiki navigasi serta struktur HTML.

Hasil dari AI tidak langsung digunakan tanpa pemeriksaan. Kode diperiksa kembali, disesuaikan dengan desain Figma dan user flow, serta diuji menggunakan W3C Validator.

Proses revisi juga menunjukkan bahwa perubahan kode perlu dibatasi sesuai kebutuhan agar tidak mengubah struktur halaman yang sudah benar.

## 6. Hasil Akhir

- Halaman HTML InternHub telah dibuat sesuai kebutuhan prototype.
- Struktur HTML menggunakan elemen semantik.
- Tidak menggunakan CSS eksternal, tag style, inline style, atau framework CSS.
- Navigasi dan path aset diperiksa.
- Validasi W3C dilakukan pada halaman yang dikerjakan.


