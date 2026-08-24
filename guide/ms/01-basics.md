# 1. Asas

[← Kandungan](./README.md)

---

## Kalendar

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/calendar.png" alt="Kalendar" width="280">

Grid bulanan ialah skrin utama. Leret ke kiri dan ke kanan untuk berpindah antara bulan, ketik satu hari untuk membuka senarai acaranya di bawah.

- Setiap hari memaparkan satu bar berwarna bagi setiap acara, serta penunjuk **+N** apabila ada lebih banyak daripada yang muat.
- Susunan senarai harian ialah tugasan tanpa waktu → tugasan berwaktu → jadual → cuti umum → acara kalendar luaran.
- Ketik pengepala untuk melompat ke mana-mana tarikh, atau guna **Alihkan tarikh** untuk memilihnya terus.

Betapa padat grid itu — tinggi baris, saiz teks acara, teks tebal, bar warna, nama cuti, kalendar lunar — semuanya boleh ditukar. Lihat [Pemperibadian](./05-personalization.md).

---

## Tugasan dan jadual

Aplikasi ini mempunyai dua jenis acara, dan bezanya ialah sama ada perkara itu boleh *diselesaikan*.

| | Tugasan | Jadual |
|---|---|---|
| Waktu | Pilihan | Wajib |
| Penyelesaian | Ada — tandakan selesai | Tiada |
| Tanpa waktu | Kekal dalam **Senarai Tugasan Semasa** sehingga anda menyelesaikannya | Tidak boleh |

**Tugasan tanpa waktu** ialah untuk sesuatu yang perlu anda buat tidak lama lagi tetapi belum dijadualkan. Ia duduk di bahagian atas kalendar dan dalam widget Senarai Tugasan Semasa sehingga selesai.

Anda boleh menukarnya ke mana-mana arah pada bila-bila masa — **Tukar kepada jadual** / **Tukar kepada tugasan** daripada menu Lagi bagi acara itu. Menukar tugasan kepada jadual memerlukan waktu.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-detail.png" alt="Perincian acara" width="280">

Setiap acara boleh membawa **Lokasi** (dengan pratonton peta dan pembukaan sekali ketik dalam aplikasi peta pilihan anda), **Pautan** dengan pratonton, dan **Nota**.

---

## Menambah acara

Tiga cara masuk, bergantung pada berapa banyak yang anda mahu taip:

- **Tambah pantas** — medan input di bahagian bawah senarai harian. Taip nama, tekan return, dan tugasan pun jadi.
- **Perincian penuh** — ketik **+** untuk membuka editor dengan waktu, pengulangan, peringatan, jenis acara, lokasi, pautan dan nota.
- **Input pantas AI** — huraikannya dalam bahasa harian dan biar aplikasi membina acara itu. Lihat [Input pantas AI](./02-ai-input.md).

Tugasan hanya perlukan nama. Jadual perlukan nama dan waktu.

---

## Acara berulang

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/repeat-options.png" alt="Pilihan pengulangan" width="240">

Daripada meminta anda mencantum peraturan daripada senarai juntai, aplikasi membaca tarikh yang anda pilih dan menawarkan pilihan siap sedia untuknya. Pilih hari Khamis dan senarai itu benar-benar menulis **Setiap Khamis** dan **Khamis ketiga setiap bulan**.

**Selang biasa**

- Setiap hari
- Setiap minggu · Setiap 2 minggu · Setiap 3 minggu · Setiap 4 minggu — pada hari minggu yang sama dengan acara
- Setiap bulan — pada tarikh yang sama setiap bulan
- Setiap tahun
- Setiap tahun (kalendar lunar) — untuk hari lahir dan ulang tahun yang dikira mengikut kalendar lunar

**Mengikut kedudukan dalam bulan**

- Setiap hari bekerja — Isnin hingga Jumaat. Ditawarkan apabila acara bermula pada hari bekerja
- Semua hari pada minggu terakhir setiap bulan
- *Hari* pertama / kedua / ketiga / keempat / terakhir setiap bulan — untuk perkara seperti "Jumaat terakhir setiap bulan"

**Tamat Pengulangan**

Setelah anda memilih pengulangan, pilih cara ia berhenti: **Tidak sekali-kali**, **Pada** tarikh tertentu, atau **Selepas** sekian **kali**.

Tugasan berulang berkelakuan berbeza daripada jadual berulang:

- Pengulangan yang belum selesai kekal kelihatan pada kalendar hari ini walaupun waktunya sudah berlalu — ia tidak bergerak ke hadapan secara senyap.
- Menyelesaikannya akan memfailkan pusingan itu di bawah tugasan selesai dan mencipta pusingan seterusnya.
- **Langkau tugasan ini** membawa anda ke pusingan seterusnya tanpa menandakannya selesai.
- Apabila pengulangan mempunyai syarat tamat dan tiada pusingan seterusnya, siri itu pun berakhir.

Apabila anda mengedit atau membuang satu pusingan acara berulang, anda memilih skopnya: **Kali ini sahaja**, **Mulai sekarang**, atau **Semua acara**.

Bagi acara pada kalendar luaran yang disambungkan, pilihan lunar tidak ditawarkan — kalendar itu tiada cara untuk menyatakannya.

---

## Jenis acara dan warna

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-type-list.png" alt="Jenis acara" width="280">

Jenis acara ialah kategori anda sendiri, dan ia membawa warna yang dipaparkan oleh acara pada kalendar. Cipta seberapa banyak yang anda mahu, setiap satu dengan warnanya sendiri.

- Matikan satu jenis untuk menyembunyikan setiap acara jenis itu daripada kalendar — berguna untuk mendiamkan kalendar kerja yang sibuk tanpa memutuskan sambungannya.
- Membuang satu jenis membolehkan anda mengekalkan atau membuang acara yang terlekat padanya.
- Tetapkan **Jenis Acara Lalai** supaya acara baharu mendarat di tempat yang betul tanpa perlu memilih setiap kali.

Cuti umum dan kalendar luaran yang disambungkan mendapat jenisnya sendiri, jadi anda boleh menyembunyikannya secara berasingan juga.

---

## Peringatan

Tetapkan seberapa banyak peringatan bagi setiap acara mengikut keperluan anda.

- **Acara berwaktu** — pada waktu acara, atau 1 / 5 / 10 / 15 / 30 minit, 1 / 2 jam, 1 / 2 / 7 hari sebelum.
- **Acara sepanjang hari** — jam 9 pagi atau tengah hari pada hari itu, atau jam 9 pagi 1 / 2 / 7 hari sebelum.
- **Tersuai** — pilih sebarang jarak waktu yang anda mahu.

Nilai lalai bagi acara berwaktu dan acara sepanjang hari ditetapkan secara berasingan dalam Tetapan, jadi acara baharu datang siap bersedia. Peringatan memerlukan keizinan pemberitahuan; aplikasi akan menunjukkan jalan ke Tetapan iOS jika ia dimatikan.

---

## Acara paling penting

Sematkan satu perkara yang anda tidak boleh terlepas. Acara paling penting kekal di bahagian atas kalendar tidak kira tarikh mana yang anda lihat, dan ia mempunyai widgetnya sendiri.

Tugasan dan jadual yang tidak berulang boleh ditetapkan sebagai paling penting. Jadual berulang tidak boleh.

---

## Tugasan belum selesai

Tugasan yang waktunya sudah berlalu tanpa diselesaikan dikumpulkan dalam bahagian **Tugasan Belum Selesai** di bahagian atas kalendar, supaya perkara yang terlepas tidak menggelongsor hilang ke minggu lepas.

Tugasan tanpa waktu dan tugasan akan datang tidak dikira belum selesai — ia memang belum sampai waktunya. Anda boleh menyembunyikan bahagian itu sepenuhnya dalam Tetapan jika anda tidak mahu melihatnya.

---

## Tugasan selesai

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/done-todos.png" alt="Tugasan selesai" width="280">

Semua yang anda tandakan selesai akan disimpan, dikumpulkan mengikut bila anda menyelesaikannya — hari ini, semalam, bulan ini, kemudian mengikut bulan dan tahun.

- Buat asal penyelesaian untuk membawa tugasan itu kembali.
- Kemas secara pukal: buang **Semua tugasan yang telah selesai**, atau yang **Lebih lama daripada 1 bulan** / **3 bulan** / **6 bulan** / **1 tahun**.

---

## Perkongsian

Kongsi **satu hari, satu minggu, atau satu bulan** sebagai teks atau sebagai kad imej.

Sebelum berkongsi, anda boleh menapis jenis acara yang mahu disertakan dan memilih sama ada nama jenis dipaparkan, jadi anda boleh menghantar minggu anda kepada seseorang tanpa mendedahkan semua yang ada di dalamnya.

---

[← Kandungan](./README.md) · [Seterusnya: Input pantas AI →](./02-ai-input.md)
