# 2. Input pantas AI

[← Kandungan](./README.md)

---

Huraikan apa yang anda mahu dalam bahasa harian dan aplikasi akan membinanya untuk anda — "makan tengah hari dengan Sara Jumaat tengah hari", "alihkan temu janji doktor gigi ke Selasa depan", "tandakan cucian selesai". Tiada borang, tiada memilih tarikh daripada roda.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ms/ai-input.png" alt="Input pantas AI" width="280">

Input pantas AI memerlukan akaun yang telah log masuk. Semua yang lain dalam aplikasi berfungsi tanpa akaun.

---

## Apa yang boleh dilakukannya

- Cipta tugasan dan jadual, dengan waktu, pengulangan dan jenis acara disimpulkan daripada apa yang anda katakan
- Ubah acara sedia ada — alihkannya, tukar namanya, tukar waktunya
- Selesaikan satu tugasan, atau buat asal penyelesaian
- Buang acara
- Uruskan beberapa perkara dalam satu permintaan ("tambah senaman Isnin, Rabu dan Jumaat jam 7 pagi")

---

## Cara menghantar permintaan

### Dalam aplikasi

Ketik butang AI pada skrin kalendar. Helaian input akan terbuka dengan dua mod yang boleh anda tukar pada bila-bila masa:

- **Suara** — bercakap dan lihat transkripsi muncul secara langsung. Memerlukan keizinan mikrofon dan pengecaman pertuturan; jika salah satu ditolak, aplikasi menawarkan untuk membuka Tetapan iOS atau **Taip sebagai gantinya**.
- **Papan Kekunci** — taip sahaja. Berguna apabila anda berada di tempat yang tidak membolehkan anda bercakap.

### Daripada imej

**Baca daripada imej** menukar gambar menjadi acara. **Ambil gambar** atau **Pilih dari perpustakaan**; aplikasi membaca teks padanya — jadual waktu kelas, poster acara, tangkapan skrin mesej — dan menunjukkan apa yang ditemuinya supaya anda boleh membetulkan apa-apa yang tersasar sebelum menghantar.

Anda boleh melampirkan **Arahan tambahan (pilihan)** untuk mengarahkan hasilnya, seperti "tambah ini sebagai tugasan". Jika tiada teks yang boleh dibaca dalam imej itu, aplikasi memberitahu anda dan bukannya menghantar permintaan kosong.

### Siri

Sebut **"Tambah dengan AI dalam To-do Calendar"** — atau "Tambah jadual dalam To-do Calendar" / "Tambah tugasan dalam To-do Calendar". Siri bertanya apa yang anda mahu tambah, dan permintaan itu berjalan **di latar belakang tanpa membuka aplikasi**. Siri menjawab "Baik. Saya akan maklumkan apabila selesai," dan anda menerima pemberitahuan apabila hasilnya sedia.

### Butang Tindakan

Petakan Butang Tindakan kepada pintasan **Tambah dengan AI**. Sekali tekan, sebut perkaranya, selesai — aplikasi tidak perlu muncul ke hadapan langsung.

### Widget dan Pusat Kawalan

- **Widget Tambah dengan AI** — widget Skrin Utama atau Skrin Kunci yang membuka skrin input AI dengan sekali ketik.
- **Pusat Kawalan** (iOS 18 dan ke atas) — tambah kawalan yang sama ke Pusat Kawalan untuk pintu masuk yang boleh dicapai dengan leret ke bawah.

### Helaian Kongsi

Kongsi **teks atau imej daripada mana-mana aplikasi lain** terus kepada AI To-do Calendar. Sedang membaca mesej yang mengandungi butiran pertemuan, atau sedang melihat poster dalam Foto — ketik kongsi, pilih To-do Calendar, tambah arahan jika perlu, dan hantar.

Permintaan daripada helaian Kongsi juga berjalan di latar belakang. Anda akan mendapat pengesahan bahawa ia telah dihantar, dan anda menyemak hasilnya dalam aplikasi.

---

## Bagaimana permintaan diproses

1. **Dihantar** — permintaan anda pun bergerak. Jika ia datang daripada Siri, Butang Tindakan atau helaian Kongsi, anda tidak perlu membiarkan aplikasi terbuka.
2. **Sedang memproses** — aplikasi menunjukkan kemajuannya. Anda boleh menekan **Henti** semasa permintaan berjalan, tetapi menghentikannya akan membuang kerja yang sedang berjalan dan ia tidak boleh disambung semula.
3. **Pengesahan diperlukan** — jika permintaan itu akan mengubah sesuatu yang penting, aplikasi meminta kelulusan anda dahulu dan menunjukkan dengan tepat apa yang bakal dilakukannya. Ada kira detik; jika ia tamat tempoh, anda mohon semula sahaja.
4. **Arahan selesai** — hasilnya mendarat pada kalendar anda serta-merta, dengan ringkasan tentang apa yang berubah.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ms/ai-result.png" alt="Hasil AI" width="280">

Hanya satu permintaan berjalan pada satu masa. Jika anda menghantar satu lagi sedang yang lain masih menunggu kelulusan anda, aplikasi memberitahu anda supaya menguruskan yang pertama dahulu.

---

## Kredit

Permintaan AI menggunakan **kredit harian yang ditetapkan semula setiap hari**. Baki yang tinggal dipaparkan di bahagian atas skrin input AI, jadi anda sentiasa tahu kedudukan anda sebelum menghantar.

Jika kredit habis, input pantas AI berehat sehingga tetapan semula berikutnya. Semua yang lain dalam aplikasi terus berfungsi.

---

## Kebenaran yang mungkin diminta

| Kebenaran | Digunakan untuk |
|---|---|
| Mikrofon + Pengecaman Pertuturan | Input suara |
| Kamera | Mengambil gambar untuk **Baca daripada imej** |
| Perpustakaan Foto | Memilih imej sedia ada |
| Pemberitahuan | Memberitahu anda hasil permintaan latar belakang |

Setiap satu diminta hanya apabila anda mula-mula menggunakan ciri yang memerlukannya, dan aplikasi terus berfungsi tanpanya — input suara berundur kepada papan kekunci, input imej kepada menaip.

---

[← Kandungan](./README.md) · [Seterusnya: Widget dan Skrin Kunci →](./03-widgets.md)
