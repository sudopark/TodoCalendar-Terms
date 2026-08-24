# 2. Input cepat AI

[← Daftar isi](./README.md)

---

Jelaskan apa yang Anda inginkan dengan bahasa sehari-hari, dan aplikasi akan menyusunnya untuk Anda — "makan siang dengan Sara Jumat pukul 12", "pindahkan dokter gigi ke Selasa depan", "tandai cucian sudah selesai". Tanpa formulir, tanpa memutar roda tanggal.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ai-input.png" alt="Input cepat AI" width="280">

Input cepat AI memerlukan akun yang sudah masuk. Semua fitur lain di aplikasi ini berjalan tanpa akun.

---

## Apa yang bisa dilakukan

- Membuat tugas dan jadwal, lengkap dengan waktu, pengulangan, dan jenis acara yang disimpulkan dari ucapan Anda
- Mengubah acara yang sudah ada — memindahkan, mengganti nama, menyetel ulang waktunya
- Menyelesaikan sebuah tugas, atau membatalkan penyelesaiannya
- Menghapus sebuah acara
- Menangani beberapa hal sekaligus dalam satu permintaan ("tambahkan olahraga Senin, Rabu, dan Jumat pukul 7 pagi")

---

## Cara mengirim permintaan

### Di dalam aplikasi

Ketuk tombol AI di layar kalender. Lembar input akan terbuka dengan dua mode yang bisa Anda tukar kapan saja:

- **Suara** — bicara dan lihat hasil pengenalannya muncul seketika. Butuh izin mikrofon dan pengenalan suara; kalau salah satunya ditolak, aplikasi menawarkan untuk membuka Pengaturan iOS atau beralih ke papan ketik.
- **Papan Ketik** — ketik saja. Berguna kalau Anda sedang berada di tempat yang tidak memungkinkan bicara.

### Dari sebuah gambar

**Baca dari gambar** mengubah sebuah foto menjadi acara. **Ambil foto** atau **Pilih dari galeri**; aplikasi membaca teks di dalamnya — jadwal pelajaran, poster acara, tangkapan layar sebuah pesan — lalu menunjukkan apa yang ditemukannya supaya Anda bisa memperbaiki bagian yang meleset sebelum mengirim.

Anda juga bisa melampirkan **Instruksi tambahan (opsional)** untuk mengarahkan hasilnya, misalnya "Tambahkan ini sebagai tugas". Kalau tidak ada teks yang terbaca di gambar itu, aplikasi memberi tahu Anda alih-alih mengirim permintaan kosong.

### Siri

Ucapkan **"Tambah dengan AI di To-do Calendar"** — atau "Tambah jadwal di To-do Calendar" / "Tambah tugas di To-do Calendar". Siri menanyakan apa yang ingin Anda tambahkan, lalu permintaannya berjalan **di latar belakang tanpa membuka aplikasi**. Siri menjawab "Baik. Saya akan memberi tahu Anda saat selesai," dan Anda menerima notifikasi begitu hasilnya siap.

### Tombol Aksi

Petakan Tombol Aksi ke pintasan **Tambah dengan AI**. Sekali tekan, ucapkan hal yang dimaksud, selesai — aplikasi tidak perlu muncul ke depan sama sekali.

### Widget dan Pusat Kontrol

- **Widget Tambah dengan AI** — widget Layar Utama atau Layar Terkunci yang membuka layar input AI dengan sekali ketuk.
- **Pusat Kontrol** (iOS 18 ke atas) — tambahkan kontrol yang sama ke Pusat Kontrol sebagai jalan masuk sekali usap ke bawah.

### Lembar berbagi

Bagikan **teks atau gambar dari aplikasi mana pun** langsung ke AI milik To-do Calendar. Sedang membaca pesan berisi detail sebuah pertemuan, atau sedang melihat poster di Foto — tekan bagikan, pilih To-do Calendar, tambahkan instruksi kalau perlu, lalu kirim.

Permintaan dari lembar berbagi juga berjalan di latar belakang. Anda hanya menerima konfirmasi bahwa permintaannya terkirim, dan hasilnya Anda periksa di aplikasi.

---

## Bagaimana sebuah permintaan diproses

1. **Terkirim** — permintaan Anda berangkat. Kalau berasal dari Siri, Tombol Aksi, atau lembar berbagi, Anda tidak perlu membiarkan aplikasi terbuka.
2. **Memproses** — aplikasi menampilkan progresnya. Anda bisa **Hentikan** permintaan yang sedang berjalan, tapi menghentikannya akan membatalkan perintah yang sedang berjalan dan tidak dapat dilanjutkan.
3. **Perlu konfirmasi** — kalau permintaan itu akan mengubah sesuatu yang penting, aplikasi meminta persetujuan Anda lebih dulu sambil menunjukkan persis apa yang hendak dilakukannya. Ada hitung mundurnya; kalau waktunya habis, tinggal minta lagi.
4. **Perintah selesai** — hasilnya langsung mendarat di kalender Anda, lengkap dengan ringkasan apa saja yang berubah.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ai-result.png" alt="Hasil AI" width="280">

Hanya satu permintaan yang berjalan pada satu waktu. Kalau Anda mengirim permintaan lain saat masih ada yang menunggu persetujuan, aplikasi meminta Anda menuntaskan yang pertama dulu.

---

## Kredit

Permintaan AI memakai **jatah harian yang direset setiap hari**. Sisanya ditampilkan di bagian atas layar input AI, jadi Anda selalu tahu posisinya sebelum mengirim.

Kalau jatahnya habis, input cepat AI beristirahat sampai reset berikutnya. Semua fitur lain di aplikasi tetap berjalan.

---

## Izin yang mungkin diminta

| Izin | Dipakai untuk |
|---|---|
| Mikrofon + Pengenalan Suara | Input suara |
| Kamera | Mengambil foto untuk **Baca dari gambar** |
| Galeri Foto | Memilih gambar yang sudah ada |
| Notifikasi | Memberi tahu hasil permintaan yang berjalan di latar belakang |

Masing-masing hanya diminta saat pertama kali Anda memakai fitur yang membutuhkannya, dan aplikasi tetap berjalan tanpa izin itu — input suara jatuh kembali ke papan ketik, input gambar ke pengetikan biasa.

---

[← Daftar isi](./README.md) · [Berikutnya: Widget dan Layar Terkunci →](./03-widgets.md)
