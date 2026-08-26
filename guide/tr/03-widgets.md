# 3. Widget'lar ve Kilit Ekranı

[← İçindekiler](./README.md)

---

Bir widget, sırada ne olduğunu görmek için uygulamayı açmak zorunda kalmayasınız diye vardır. To-do Calendar geniş bir set sunar; böylece gününüze gerçekte nasıl baktığınıza uyanı seçebilirsiniz — tek bir sonraki etkinlik, bütün bir ay ya da dokunarak işaretleyebileceğiniz görev listeniz.

---

## Ana Ekran widget'ları

### Bugün ve Sıradakiler

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/tr/widget-today-and-next.png" alt="Bugün ve Sıradakiler widget'ı" width="360">

Solda bugünün tarihi ve günden kalanlar, sağda sırada ne olduğu. Hiçbir widget bir seferde bu kadarını göstermez.

*Orta.*

### Etkinlikler

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/tr/widget-event-list.png" alt="Etkinlik listesi widget'ı" width="300">

Güne göre gruplanmış, akıp giden bir yaklaşan etkinlik listesi; güncel görevleriniz de dahil. Üç boyutu var ve büyüdükçe daha çok gün gösterir.

*Küçük · Orta · Büyük.*

### BUGÜN

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/tr/widget-today.png" alt="BUGÜN widget'ı" width="200">

Yalnızca bugün — tarih, varsa tatil ve kaç göreviniz ile randevunuz olduğu.

*Küçük.*

### En Önemli Etkinlik

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/tr/widget-foremost.png" alt="En önemli etkinlik widget'ı" width="200">

En önemli diye sabitlediğiniz tek etkinlik, hep göz önünde. Bkz. [En önemli etkinlik](./01-basics.md#en-önemli-etkinlik).

*Kilit Ekranı satır içi · Küçük · Orta.*

### Takvim ve haftalar

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/tr/widget-month.png" alt="Takvim widget'ı" width="360">

İstediğiniz aralıkta takvimin kendisi:

| Widget | Boyut |
|---|---|
| Takvim | Küçük |
| Bu hafta · 2 hafta | Orta |
| 3 hafta · 4 hafta | Büyük |
| Geçen ay · Bu ay · Gelecek ay | Büyük |

### Kombinasyonlar

Tek görünüm yetmediğinde, bir widget'ta iki panel:

| Widget | Gösterdiği | Boyut |
|---|---|---|
| BUGÜN + Takvim | Aylık takvimin yanında bugünün özeti | Orta |
| Etkinlikler + Takvim | Aylık takvimin yanında yaklaşan etkinlikler | Orta |
| Etkinlikler + En Önemli | Sabitlediğiniz etkinliğin yanında yaklaşan etkinlikler | Orta |
| Takvim + Takvim | Yan yana iki ay | Orta |

### AI ile Ekle

Tek dokunuşla doğrudan [hızlı AI girişine](./02-ai-input.md).

*Kilit Ekranı dairesel · Küçük.*

---

## Bir widget'tan neler yapabilirsiniz

- **Bir görevi işaretleyin** — widget'taki herhangi bir görevin yuvarlağına dokunun, uygulama açılmadan tamamlansın.
- **Etkinliğe geçin** — bir etkinliğe dokunmak onu doğrudan ayrıntı ekranında açar.
- **Etkinlik türüne göre süzün** — widget'a uzun basıp Widget'ı Düzenle'yi seçin ve onu belirli etkinlik türleriyle sınırlayın. Hem kendi türleriniz hem de bağlı harici takvimler seçim listesinde çıkar.

---

## Kilit Ekranı

### Kilit Ekranı widget'ları

Birkaç widget'ın Kilit Ekranı biçimi var: **Sonraki etkinlik** (satır içi ve dikdörtgen), **Bugünün kalan etkinlikleri** (dikdörtgen), **En Önemli Etkinlik** (satır içi) ve **AI ile Ekle** (dairesel).

### Canlı Etkinlik geri sayımı

Bir etkinliği Kilit Ekranınıza koyun ve ona kalan sürenin geri sayışını izleyin; aynı görünüm Dynamic Island'da da olur. Etkinliğin diğer seçenekler menüsünden **Kilit Ekranı'nda göster**'i seçin.

- Önümüzdeki 8 saat içinde başlayan etkinlikler için kullanılabilir.
- Aynı anda tek etkinlik — yenisini seçtiğinizde mevcut olanla değiştirilsin mi diye sorulur.
- Görevler doğrudan Canlı Etkinlik üzerinden tamamlanabilir.

---

## Kontrol Merkezi

iOS 18 ve sonrasında **AI ile Ekle** denetimini Kontrol Merkezi'ne ekleyebilirsiniz; böylece bir aşağı kaydırma ve tek dokunuşla her yerden AI giriş ekranına ulaşırsınız.

---

## Görünüm

Widget'lar varsayılan olarak sistemin açık/koyu ayarını izler; dilerseniz seçtiğiniz bir arka plan rengine sabitleyebilirsiniz — uygulama, o rengin ne kadar parlak olduğuna bakarak okunaklı metin rengini kendisi belirler. **Ayarlar › Görünüm › Widget teması**'ndan ayarlayın. Bkz. [Kişiselleştirme](./05-personalization.md).

Widget'lar gün boyunca kendiliğinden yenilenir ve uygulamada bir şeyi değiştirdiğinizde hemen güncellenir.

---

[← İçindekiler](./README.md) · [Sıradaki: Harici takvimler →](./04-external-calendars.md)
