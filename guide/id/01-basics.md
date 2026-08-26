# 1. Dasar-dasarnya

[← Daftar isi](./README.md)

---

## Layar kalender

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/id/calendar.png" alt="Kalender" width="280">

Kalender bulanan adalah layar utamanya. Geser ke kiri dan ke kanan untuk berpindah bulan, ketuk sebuah tanggal untuk membuka daftar acaranya di bawah.

- Tiap tanggal menampilkan satu batang warna per acara, ditambah penanda **+N** kalau acara pada hari itu lebih banyak daripada yang muat dalam satu baris.
- Urutan daftar harian: tugas tanpa waktu → tugas berwaktu → jadwal → hari libur → acara kalender eksternal.
- Ketuk bagian atas untuk melompat ke tanggal mana pun, atau pakai **Pindahkan tanggal** untuk memilihnya langsung.

Seberapa banyak yang ditampilkan tiap tanggal, Anda sendiri yang menentukan — seberapa rinci tiap acara ditampilkan, ukuran teks, warna, nama hari libur, dan kalender lunar. [Personalisasi](./05-personalization.md) membahas tiap pengaturan satu per satu dengan namanya.

---

## Tugas dan jadwal

Aplikasi ini punya dua jenis acara, dan bedanya cuma satu: apakah Anda mencentangnya atau tidak.

| | Tugas | Jadwal |
|---|---|---|
| Waktu | Opsional | Wajib |
| Penyelesaian | Ya — tinggal dicentang | Tidak |
| Tanpa waktu | Tetap di **Daftar Tugas Saat Ini** sampai Anda menuntaskannya | Tidak bisa |

**Tugas tanpa waktu** cocok untuk sesuatu yang harus segera dikerjakan tapi belum dijadwalkan. Ia duduk di bagian atas kalender dan di widget **Daftar Tugas Saat Ini** sampai selesai.

Anda bisa mengubahnya bolak-balik kapan saja — **Ubah menjadi jadwal** / **Ubah menjadi tugas** dari menu lainnya pada acara tersebut. Mengubah tugas menjadi jadwal membutuhkan informasi waktu.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/id/event-detail.png" alt="Detail acara" width="280">

Setiap acara bisa membawa **Lokasi** (dengan pratinjau peta dan sekali ketuk untuk membukanya di aplikasi peta pilihan Anda), **Tautan** berikut pratinjaunya, dan **Catatan**.

---

## Menambahkan acara

Ada tiga cara menambahkan acara, tergantung seberapa banyak yang ingin Anda ketik:

- **Tambah cepat** — kolom input di bawah daftar harian. Ketik nama, tekan enter, dan tugasnya langsung dibuat.
- **Detail lengkap** — ketuk **+** untuk membuka editor berisi waktu, pengulangan, notifikasi, jenis acara, lokasi, tautan, dan catatan.
- **Input cepat AI** — jelaskan dengan bahasa sehari-hari dan biarkan aplikasi yang menyusun acaranya. Lihat [Input cepat AI](./02-ai-input.md).

Tugas cukup butuh nama. Jadwal butuh nama dan waktu.

---

## Acara berulang

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/id/repeat-options.png" alt="Opsi pengulangan" width="240">

Alih-alih meminta Anda merakit aturan pengulangan dari menu-menu pilihan, aplikasi membaca tanggal yang Anda pilih dan menyodorkan opsi yang sudah jadi untuk tanggal itu. Pilih hari Kamis, dan daftarnya menawarkan **Setiap Kamis** dan **Kamis ketiga setiap bulan**.

**Interval umum**

- Setiap hari
- Setiap minggu · Setiap 2 minggu · Setiap 3 minggu · Setiap 4 minggu — pada hari yang sama dengan acaranya
- Setiap bulan — pada tanggal yang sama tiap bulan
- Setiap tahun
- Setiap tahun (kalender lunar) — untuk ulang tahun dan peringatan yang dihitung dengan kalender lunar

**Berdasarkan posisi dalam bulan**

- Setiap hari kerja — Senin sampai Jumat. Muncul kalau acaranya dimulai pada hari kerja
- Semua hari di minggu terakhir setiap bulan
- **Kamis** pertama / kedua / ketiga / keempat / terakhir setiap bulan — hari dalam minggunya diisi dari tanggal yang Anda pilih, jadi acara pada hari Jumat menawarkan **Jumat terakhir setiap bulan**

**Akhir Pengulangan**

Setelah memilih pengulangan, tentukan kapan ia berhenti: **Tidak pernah**, **Pada tanggal** tertentu, atau **Setelah** sekian kali.

Tugas berulang berperilaku berbeda dari jadwal berulang:

- Pengulangan yang belum selesai tetap terlihat di kalender hari ini walau waktunya sudah lewat — ia tidak berpindah sendiri ke putaran berikutnya.
- Menyelesaikannya akan memasukkan putaran itu ke daftar tugas yang telah selesai sekaligus membuat putaran berikutnya.
- **Lewati tugas ini** membawa Anda ke putaran berikutnya tanpa menandainya selesai.
- Kalau pengulangan punya syarat akhir dan tidak ada putaran berikutnya, rangkaiannya berakhir.

Saat mengedit atau menghapus satu putaran dari acara berulang, Anda akan memilih cakupannya: **Hanya kali ini**, **Mulai dari sekarang**, atau **Semua acara**.

Untuk acara di kalender eksternal yang terhubung, opsi lunar tidak ditawarkan — kalender eksternal tidak punya tempat untuk menyimpan aturan pengulangan lunar.

---

## Jenis acara dan warna

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/id/event-type-list.png" alt="Jenis acara" width="280">

Jenis acara adalah kategori Anda sendiri, dan dari sanalah warna yang tampil di kalender berasal. Buat sebanyak yang Anda mau, masing-masing dengan warnanya sendiri.

- Matikan satu jenis untuk menyembunyikan semua acara berjenis itu dari kalender — berguna untuk meredam kalender kerja yang padat tanpa memutus koneksinya.
- Saat menghapus sebuah jenis, Anda bisa memilih untuk menyimpan atau ikut menghapus acara yang terkait dengannya.
- Tetapkan **Jenis Acara Default** supaya acara baru langsung mendarat di tempat yang tepat tanpa perlu dipilih tiap kali.

Hari libur dan kalender eksternal yang terhubung punya jenisnya sendiri, jadi keduanya juga bisa disembunyikan secara terpisah.

---

## Notifikasi

Pasang notifikasi sebanyak yang Anda perlukan untuk tiap acara.

- **Acara berwaktu** — saat waktu acara, atau 1 / 5 / 10 / 15 / 30 menit, 1 / 2 jam, 1 / 2 / 7 hari sebelumnya.
- **Acara sepanjang hari** — pukul 9 pagi atau siang hari itu, atau pukul 9 pagi 1 / 2 / 7 hari sebelumnya.
- **Khusus** — tentukan sendiri selisih waktu yang Anda mau.

Nilai bawaan untuk acara berwaktu dan acara sepanjang hari diatur terpisah di Pengaturan, jadi acara baru sudah siap sejak awal. Notifikasi memerlukan izin notifikasi; kalau izinnya mati, aplikasi akan mengarahkan Anda ke Pengaturan iOS.

---

## Acara terpenting

Sematkan satu hal yang tidak boleh Anda lewatkan. Acara terpenting tetap berada di bagian atas kalender apa pun tanggal yang sedang Anda lihat, dan ia punya widget tersendiri.

Tugas dan jadwal yang tidak berulang bisa ditandai sebagai terpenting. Jadwal berulang tidak bisa.

---

## Tugas yang belum selesai

Tugas yang waktunya sudah lewat tanpa diselesaikan dikumpulkan di bagian **Tugas Belum Selesai** di atas kalender, supaya tugas yang terlewat tidak terkubur di tanggal yang sudah lewat.

Tugas tanpa waktu dan tugas yang masih akan datang tidak dihitung sebagai belum selesai — tenggatnya memang belum tiba. Anda bisa menyembunyikan bagian ini sepenuhnya di Pengaturan kalau tidak ingin melihatnya.

---

## Tugas yang sudah selesai

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/id/done-todos.png" alt="Tugas yang sudah selesai" width="280">

Semua yang Anda centang tetap disimpan, dikelompokkan menurut kapan Anda menuntaskannya — hari ini, kemarin, bulan ini, lalu per bulan dan per tahun.

- Batalkan penyelesaian untuk mengembalikan tugasnya.
- Bersihkan sekaligus: hapus semuanya, atau hanya yang lebih lama dari 1 / 3 / 6 bulan atau 1 tahun.

---

## Berbagi

Bagikan **satu hari, satu minggu, atau satu bulan** sebagai teks atau sebagai kartu gambar.

Sebelum berbagi, Anda bisa menyaring jenis acara mana yang ikut disertakan dan memilih apakah nama jenisnya ditampilkan, jadi Anda bisa mengirimkan jadwal seminggu tanpa membeberkan seluruh isinya.

---

[← Daftar isi](./README.md) · [Berikutnya: Input cepat AI →](./02-ai-input.md)
