<p align="center">
  <a href="https://pize.ai/id">
    <img src="assets/pize-logo.svg" width="96" height="96" alt="Pize logo" />
  </a>
</p>

<h1 align="center">pize.ai</h1>

<p align="center"><strong>Asisten pemrograman AI untuk komputasi ilmiah dan analisis statistik.</strong></p>
<p align="center">Pahami data. Bangun analisis. Tinjau hasil.</p>

<p align="center">
  <a href="https://pize.ai/id">Situs resmi</a> &middot;
  <a href="https://pize.ai/docs">Dokumentasi</a> &middot;
  <a href="https://pize.ai/download">Unduh</a>
</p>

<p align="center" dir="ltr">
  <a href="README.md">简体中文</a> &middot;
  <a href="README.en.md">English</a> &middot;
  <a href="README.de.md">Deutsch</a> &middot;
  <a href="README.ja.md">日本語</a> &middot;
  <a href="README.fr.md">Français</a><br />
  <a href="README.ar.md">العربية</a> &middot;
  <a href="README.es.md">Español</a> &middot;
  <a href="README.hi.md">हिन्दी</a> &middot;
  <a href="README.id.md">Bahasa Indonesia</a> &middot;
  <a href="README.ru.md">Русский</a>
</p>

---

## Dirancang untuk penelitian, bukan sekadar melengkapi kode

**Pize adalah asisten pemrograman AI bagi peneliti yang bekerja dengan kode ilmiah dan data statistik.** Pize membantu memahami proyek, menyiapkan analisis, menulis dan menjalankan kode, memeriksa keluaran serta grafik, lalu menyempurnakan langkah berikutnya. Gunakan melalui Pize Code, Positron, CLI, atau SDK.

Kesalahan penelitian sering muncul sebelum pemodelan: pemisah kolom yang salah, nilai hilang yang dianggap angka, atau observasi yang dianggap sebagai header. Pize mengutamakan pemahaman data agar pemrograman berangkat dari struktur masukan, bukan asumsi tentang isi berkas.

Repositori ini adalah halaman publik produk dan komunitas Pize, dikelola oleh pendirinya, [@guopengnaivoc](https://github.com/guopengnaivoc).

## Kemampuan Pize

| Kemampuan | Manfaat dalam pekerjaan |
| --- | --- |
| **Pembacaan yang memahami data** | Mengenali pemisah, header, nilai hilang, dan tipe kolom dari isi berkas; menangani komentar, metadata, serta tabel terkompresi. |
| **Konteks untuk data besar** | Menyediakan kartu data ringkas ketika berkas melampaui batas konteks, berisi skema, pratinjau kecil, dan jumlah baris yang ditandai sebagai perkiraan. |
| **Sesi R / Python nyata** | Di Positron, memeriksa sesi yang sedang difokuskan dan merangkum dataframe. Menjalankan kode serta mengambil grafik setelah persetujuan, lalu memperbaiki analisis berdasarkan keluaran nyata. |
| **Perubahan kode yang dapat ditinjau** | Mengkoordinasikan perubahan lintas berkas, memeriksa perbedaan, membatalkan perubahan, dan kembali ke titik pemeriksaan tugas sebelumnya. |
| **Perencanaan dan eksekusi** | Menjelajahi proyek dalam mode perencanaan, menyepakati pendekatan, lalu menulis kode serta menjalankan perintah terminal dengan persetujuan. |
| **Konteks proyek dan peramban** | Merujuk berkas, folder, masalah, dan URL; menggunakan interaksi peramban, tangkapan layar, serta log saat debugging. |
| **Konvensi yang dapat digunakan kembali** | Menerapkan aturan proyek dan keterampilan untuk definisi statistik, konvensi grafik, serta struktur direktori. |

Untuk format penelitian seperti Parquet, Arrow, RDS, HDF5, h5ad, NumPy, SPSS, dan Stata, Pize mengenali format dan membantu membuat kode pemuatan yang sesuai. Ini berbeda dari mendekode semua format biner langsung ke dalam percakapan. Perilaku dan batasannya dijelaskan dalam [dokumentasi pembacaan data dan runtime](https://pize.ai/docs).

## Bekerja di lingkungan yang sudah Anda gunakan

| Antarmuka | Penggunaan |
| --- | --- |
| **Pize Code** | Bantuan di editor, konteks proyek, peninjauan perubahan, dan alur kerja terminal. |
| **Positron** | Agen yang sama dengan akses ke sesi R atau Python yang sudah difokuskan. |
| **CLI** | Menggunakan Pize melalui baris perintah. |
| **SDK** | Menanamkan agen beserta kemampuan berorientasi datanya ke program sendiri dan alat internal. |

Penghubung ke sesi yang sedang berjalan merupakan fitur khusus Positron. Tidak semua antarmuka memiliki akses runtime yang sama. Petunjuk pemasangan dan rinciannya tersedia dalam [dokumentasi resmi](https://pize.ai/docs).

## Model dan alat yang terhubung

Pize mendukung koneksi ke model cloud dan lokal, termasuk Anthropic, OpenAI, Google Gemini, DeepSeek, AWS Bedrock, OpenRouter, serta endpoint yang kompatibel dengan OpenAI. Pilih penyedia dan konfigurasi yang sesuai dengan lingkungan penelitian Anda.

**SDK menanamkan Pize ke dalam program; MCP menghubungkan Pize ke alat eksternal.** Sebagai klien MCP, Pize dapat terhubung ke server kompatibel untuk basis data, sistem internal, dan alat laboratorium. Operasi yang tersedia bergantung pada server serta izin yang Anda berikan.

## Mulai menggunakan

1. **Pilih antarmuka.** Mulai dari [halaman unduhan resmi](https://pize.ai/download) dan ikuti petunjuk untuk lingkungan Anda.
2. **Konfigurasikan model.** Hubungkan penyedia yang didukung atau endpoint lokal sesuai dokumentasi.
3. **Berikan konteks penelitian.** Buka proyek dan lampirkan skrip atau data yang relevan. Di Positron, fokuskan sesi yang berisi data untuk dianalisis.
4. **Rencanakan, setujui, dan perbaiki.** Sepakati pendekatan, tinjau tindakan yang diusulkan, lalu periksa kode, keluaran, dan grafik sebelum melanjutkan.

<details>
<summary><strong>Contoh permintaan penelitian</strong></summary>

Contoh berikut adalah titik awal, bukan hasil analisis yang telah divalidasi secara independen.

- “Periksa kolom, tipe, dan nilai hilang pada dataset ini sebelum mengusulkan analisis.”
- “Jelaskan pipeline R atau Python ini dan sebutkan asumsi yang perlu saya tinjau.”
- “Bantu revisi skrip analisis ini, jalankan setelah persetujuan, dan jelaskan grafik diagnostiknya.”

</details>

Pize membantu alur kerja, bukan menggantikan pertimbangan ilmiah. Tinjau asumsi metode dan keluaran sebelum mengandalkan hasil. Penanganan data bergantung pada alat dan layanan model yang dikonfigurasi; baca [informasi privasi](https://pize.ai/privacy) serta kebijakan penyedia Anda.

## Yang dipublikasikan di sini

Repositori ini memuat informasi produk, panduan komunitas, dan [penampil protein interaktif](https://guopengnaivoc.github.io/pize.ai/) yang berdiri sendiri. Penampil tersebut adalah demonstrasi visual, bukan layanan prediksi protein atau bukti hasil ilmiah yang tervalidasi. Sumber datanya tercantum dalam [kredit protein](assets/protein-CREDITS.md).

**Kode sumber aplikasi inti Pize tidak dipublikasikan di repositori ini.** Penampil yang terbuka tidak berarti seluruh produk bersifat sumber terbuka. Alat, contoh, dan catatan teknis tertentu dapat diterbitkan terpisah di kemudian hari, dengan cakupan serta lisensi masing-masing. Gunakan situs resmi untuk mengunduh perangkat lunak dan melihat ketersediaan terbaru.

## Pendiri, masukan, dan kolaborasi

Pize didirikan dan dikelola oleh [@guopengnaivoc](https://github.com/guopengnaivoc) dengan nama **pize.ai**. Situs web menjadi pintu masuk produk; repositori ini menyatukan informasi publik proyek dan masukan komunitas.

- **Pertanyaan produk dan usulan fitur:** buat [GitHub Issue](https://github.com/guopengnaivoc/pize.ai/issues).
- **Laporan bug yang berguna:** jelaskan lingkungan, tugas, perilaku yang diharapkan dan yang terjadi, serta contoh minimal. Lihat [panduan kontribusi](CONTRIBUTING.md).
- **Kolaborasi, penggunaan laboratorium, atau pertanyaan pribadi:** pilih alamat email yang sesuai di bawah.

Jangan memublikasikan kunci API, kredensial, dataset pribadi, atau penelitian rahasia dalam Issue publik. Kemampuan terkini dan petunjuk pengaturan tersedia di [pize.ai](https://pize.ai/id) serta [dokumentasinya](https://pize.ai/docs).

## Hubungi Pize

Klik alamat untuk membuka aplikasi email dengan subjek yang disarankan. Alamat ini tercantum di [halaman kontak resmi](https://pize.ai/contact).

| Kontak | Keperluan | Email |
| --- | --- | --- |
| **Pertanyaan umum** | Pertanyaan produk, permintaan media, dan informasi rilis. | [hello@pize.ai](mailto:hello@pize.ai?subject=Pize%20general%20inquiry) |
| **Kontak produk** | Demo produk, pertanyaan penerapan, dan kolaborasi. | [contact@pize.ai](mailto:contact@pize.ai?subject=Pize%20product%20inquiry) |
| **Dukungan teknis** | Akun, dokumentasi, privasi, dan permintaan penghapusan data. | [support@pize.ai](mailto:support@pize.ai?subject=Pize%20support%20request) |
| **Bisnis dan kemitraan** | Pembelian, kemitraan penelitian, dan pertanyaan komersial. | [business@pize.ai](mailto:business@pize.ai?subject=Pize%20business%20inquiry) |
