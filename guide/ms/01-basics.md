# 1. Asas

[← Kandungan](./README.md)

---

## Kalendar

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ms/calendar.png" alt="Kalendar" width="280">

Kalendar bulanan ialah skrin utama. Leret ke kiri dan ke kanan untuk berpindah antara bulan, ketik satu hari untuk membuka senarai acaranya di bawah.

- Setiap hari memaparkan satu bar berwarna bagi setiap acara, serta penunjuk **+N** apabila hari itu ada lebih banyak acara daripada yang muat pada barisnya.
- Susunan senarai harian ialah tugasan tanpa waktu → tugasan berwaktu → jadual → cuti umum → acara kalendar luaran.
- Ketik pengepala untuk melompat ke mana-mana tarikh, atau guna **Alihkan tarikh** untuk memilihnya terus.

Berapa banyak yang dipaparkan pada setiap hari terpulang kepada anda — tahap perincian bagi setiap acara, saiz teks, warna, nama cuti dan kalendar lunar. [Pemperibadian](./05-personalization.md) menerangkan setiap tetapan mengikut namanya.

---

## Tugasan dan jadual

Aplikasi ini mempunyai dua jenis acara, dan bezanya ialah sama ada ia sesuatu yang anda tandakan selesai.

| | Tugasan | Jadual |
|---|---|---|
| Waktu | Pilihan | Wajib |
| Penyelesaian | Ada — tandakan selesai | Tiada |
| Tanpa waktu | Kekal dalam **Senarai Tugasan Semasa** sehingga anda menyelesaikannya | Tidak boleh |

Gunakan **tugasan tanpa waktu** untuk sesuatu yang perlu anda buat tidak lama lagi tetapi belum dijadualkan. Ia duduk di bahagian atas kalendar dan dalam widget Senarai Tugasan Semasa sehingga selesai.

Anda boleh menukar satu kepada satu lagi pada bila-bila masa — **Tukar kepada jadual** / **Tukar kepada tugasan** daripada menu lanjutan acara itu. Menukar tugasan kepada jadual memerlukan waktu.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ms/event-detail.png" alt="Perincian acara" width="280">

Setiap acara boleh membawa **Lokasi** — dengan pratonton peta, dan sekali ketik untuk membukanya dalam aplikasi peta pilihan anda — serta **Pautan** dengan pratontonnya sendiri, dan **Nota**.

---

## Menambah acara

Tiga cara untuk menambah acara, bergantung pada berapa banyak yang anda mahu taip:

- **Tambah pantas** — medan input di bahagian bawah senarai harian. Taip nama, tekan Enter, dan tugasan itu tercipta.
- **Perincian penuh** — ketik **+** untuk membuka editor dengan waktu, pengulangan, peringatan, jenis acara, lokasi, pautan dan nota.
- **Input pantas AI** — huraikannya dalam bahasa harian dan biar aplikasi membina acara itu. Lihat [Input pantas AI](./02-ai-input.md).

Tugasan hanya perlukan nama. Jadual perlukan nama dan waktu.

---

## Acara berulang

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ms/repeat-options.png" alt="Pilihan pengulangan" width="240">

Daripada meminta anda membina peraturan pengulangan daripada menu lungsur, aplikasi membaca tarikh yang anda pilih dan menawarkan pilihan siap sedia untuknya. Pilih hari Khamis dan senarai itu menawarkan **Setiap Khamis** dan **Khamis ketiga setiap bulan**.

**Selang biasa**

- Setiap hari
- Setiap minggu · Setiap 2 minggu · Setiap 3 minggu · Setiap 4 minggu — pada hari minggu yang sama dengan acara
- Setiap bulan — pada tarikh yang sama setiap bulan
- Setiap tahun
- Setiap tahun (kalendar lunar) — untuk hari lahir dan ulang tahun yang dikira mengikut kalendar lunar

**Mengikut kedudukan dalam bulan**

- Setiap hari bekerja — Isnin hingga Jumaat. Ditawarkan apabila acara bermula pada hari bekerja
- Semua hari pada minggu terakhir setiap bulan
- **Khamis** pertama / kedua / ketiga / keempat / terakhir setiap bulan — hari minggu diisi daripada tarikh yang anda pilih, jadi acara pada hari Jumaat menawarkan "Jumaat terakhir setiap bulan" pula

**Tamat Pengulangan**

Setelah anda memilih pengulangan, pilih cara ia berhenti: **Tidak sekali-kali**, **Pada** tarikh tertentu, atau **Selepas** bilangan **kali** yang anda tetapkan.

Tugasan berulang berkelakuan berbeza daripada jadual berulang:

- Pengulangan yang belum selesai kekal kelihatan pada kalendar hari ini walaupun waktunya sudah berlalu — ia tidak berpindah ke pusingan seterusnya dengan sendirinya.
- Menyelesaikannya memindahkan pusingan itu ke Senarai Tugasan Selesai dan mencipta pusingan seterusnya.
- **Langkau tugasan ini** membawa anda ke pusingan seterusnya tanpa menandakannya selesai.
- Apabila pengulangan mempunyai syarat tamat dan tiada pusingan seterusnya, siri itu pun berakhir.

Apabila anda mengedit atau membuang satu pusingan acara berulang, anda memilih skopnya: **Kali ini sahaja**, **Mulai sekarang**, atau **Semua acara**.

Bagi acara pada kalendar luaran yang disambungkan, pilihan lunar tidak ditawarkan — kalendar luaran tiada cara untuk menyimpan peraturan pengulangan lunar.

---

## Jenis acara dan warna

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ms/event-type-list.png" alt="Jenis acara" width="280">

Jenis acara ialah kategori anda sendiri, dan ia membawa warna yang dipaparkan oleh acara pada kalendar. Cipta seberapa banyak yang anda mahu, setiap satu dengan warnanya sendiri.

- Matikan satu jenis untuk menyembunyikan setiap acara jenis itu daripada kalendar — berguna untuk mendiamkan kalendar kerja yang sibuk tanpa memutuskan sambungannya.
- Membuang satu jenis membolehkan anda mengekalkan atau membuang acara yang terlekat padanya.
- Tetapkan **jenis acara lalai** supaya acara baharu mendarat di tempat yang betul tanpa perlu memilih setiap kali.

Cuti umum dan kalendar luaran yang disambungkan mendapat jenisnya sendiri, jadi anda boleh menyembunyikannya secara berasingan juga.

---

## Peringatan

Tetapkan seberapa banyak peringatan bagi setiap acara mengikut keperluan anda.

- **Acara berwaktu** — pada waktu acara, atau 1 / 5 / 10 / 15 / 30 minit, 1 / 2 jam, 1 / 2 / 7 hari sebelum.
- **Acara sepanjang hari** — jam 9 pagi atau tengah hari pada hari itu, atau jam 9 pagi 1 / 2 / 7 hari sebelum.
- **Tersuai** — pilih sebarang jarak waktu yang anda mahu.

Nilai lalai bagi acara berwaktu dan acara sepanjang hari ditetapkan secara berasingan dalam Tetapan, jadi peringatan acara baharu sudah pun ditetapkan. Peringatan memerlukan keizinan pemberitahuan; aplikasi akan menunjukkan jalan ke Tetapan iOS jika ia dimatikan.

---

## Acara paling penting

Sematkan satu perkara yang anda tidak boleh terlepas. Acara paling penting kekal di bahagian atas kalendar tidak kira tarikh mana yang anda lihat, dan ia mempunyai widgetnya sendiri.

Tugasan dan jadual yang tidak berulang boleh ditetapkan sebagai paling penting. Jadual berulang tidak boleh.

---

## Tugasan belum selesai

Tugasan yang waktunya sudah berlalu tanpa diselesaikan dikumpulkan dalam bahagian **Tugasan Belum Selesai** di bahagian atas kalendar, supaya tugasan yang terlepas tidak tertimbus pada tarikh yang sudah berlalu.

Tugasan tanpa waktu dan tugasan akan datang tidak dikira belum selesai — ia memang belum sampai waktunya. Anda boleh menyembunyikan bahagian itu sepenuhnya dalam Tetapan jika anda tidak mahu melihatnya.

---

## Tugasan selesai

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ms/done-todos.png" alt="Tugasan selesai" width="280">

Semua yang anda tandakan selesai akan disimpan, dikumpulkan mengikut bila anda menyelesaikannya — hari ini, semalam, bulan ini, kemudian mengikut bulan dan tahun.

- Buat asal penyelesaian untuk membawa tugasan itu kembali.
- Bersihkan secara pukal: buang **Semua tugasan yang telah selesai**, atau yang **Lebih lama daripada 1 bulan** / **3 bulan** / **6 bulan** / **1 tahun**.

---

## Perkongsian

Kongsi **satu hari, satu minggu, atau satu bulan** sebagai teks atau sebagai kad imej.

Sebelum berkongsi, anda boleh menapis jenis acara yang mahu disertakan dan memilih sama ada nama jenis dipaparkan, jadi anda boleh menghantar minggu anda kepada seseorang tanpa mendedahkan semua yang ada di dalamnya.

---

[← Kandungan](./README.md) · [Seterusnya: Input pantas AI →](./02-ai-input.md)
