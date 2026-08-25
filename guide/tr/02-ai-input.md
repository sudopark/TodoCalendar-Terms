# 2. Hızlı AI girişi

[← İçindekiler](./README.md)

---

Ne istediğinizi günlük dille anlatın, uygulama sizin için kursun — "cuma öğlen Sara ile öğle yemeği", "diş hekimini gelecek salıya al", "çamaşırı tamamlandı olarak işaretle". Form yok, tekerlekten tarih seçme yok.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/tr/ai-input.png" alt="Hızlı AI girişi" width="280">

Hızlı AI girişi için giriş yapmış bir hesap gerekir. Uygulamadaki diğer her şey hesapsız çalışır.

---

## Neler yapabilir

- Söylediklerinizden saati, tekrarlamayı ve etkinlik türünü çıkararak görev ve randevu oluşturur
- Var olan bir etkinliği değiştirir — taşır, adını değiştirir, saatini yeniden ayarlar
- Bir görevi tamamlar ya da tamamlamayı geri alır
- Bir etkinliği siler
- Tek istekte birkaç şeyi birden halleder ("pazartesi, çarşamba ve cuma 07.00'ye spor ekle")

---

## İstek gönderme yolları

### Uygulama içinde

Takvim ekranındaki AI düğmesine dokunun. Giriş sayfası, istediğiniz an aralarında geçiş yapabileceğiniz iki kiple açılır:

- **Ses** — konuşun ve yazıya dökülen metni anlık olarak izleyin. Mikrofon ve konuşma tanıma izni gerekir; biri reddedilmişse uygulama iOS Ayarlar'ı açmayı ya da bunun yerine klavyeye geçmeyi önerir.
- **Klavye** — yazarak girin. Konuşamayacağınız yerlerde işe yarar.

### Görselden

**Görselden oku**, bir resmi etkinliklere dönüştürür. **Fotoğraf çek**in veya **Kitaplıktan seç**in; uygulama üzerindeki metni okur — ders programı, etkinlik afişi, bir mesajın ekran görüntüsü — ve bulduklarını size gösterir; böylece yanlış çıkan yerleri göndermeden önce düzeltebilirsiniz.

Sonucu yönlendirmek için "bunları görev olarak ekle" gibi bir **Ek yönergeler (isteğe bağlı)** metni ekleyebilirsiniz. Görselde okunabilir metin yoksa uygulama boş bir istek göndermek yerine size durumu bildirir.

### Siri

**"To-do Calendar uygulamasında AI ile ekle"** deyin — ya da "To-do Calendar uygulamasında randevu ekle" / "To-do Calendar uygulamasında görev ekle". Siri ne eklemek istediğinizi sorar ve istek **uygulama açılmadan arka planda** çalışır. Siri "Anlaşıldı. Tamamlandığında size bildireceğim." diye yanıt verir, sonuç hazır olduğunda da bir bildirim alırsınız.

### Aksiyon Düğmesi

Aksiyon Düğmesi'ne **AI ile Ekle** kısayolunu atayın. Tek basış, söyleyin, bitti — uygulamanın öne gelmesi hiç gerekmez.

### Widget ve Kontrol Merkezi

- **AI ile Ekle widget'ı** — Ana Ekran ya da Kilit Ekranı widget'ı, tek dokunuşla AI giriş ekranını açar.
- **Kontrol Merkezi** (iOS 18 ve sonrası) — aynı denetimi Kontrol Merkezi'ne ekleyip aşağı kaydırarak giriş noktası elde edin.

### Paylaşım sayfası

**Herhangi bir uygulamadaki metni veya görseli** doğrudan To-do Calendar'ın AI'sına paylaşın. Buluşma ayrıntılarını içeren bir mesajı okurken ya da Fotoğraflar'da bir afişe bakarken paylaş'a basın, To-do Calendar'ı seçin, isterseniz bir yönerge ekleyin ve gönderin.

Paylaşım sayfasından gelen istek de arka planda çalışır. Gönderildiğine dair bir onay alırsınız, sonucu ise uygulamada kontrol edersiniz.

---

## Bir istek nasıl işlenir

1. **Gönderildi** — isteğiniz yola çıkar. Siri'den, Aksiyon Düğmesi'nden veya paylaşım sayfasından geldiyse uygulamayı açık tutmanız gerekmez.
2. **İşleniyor** — uygulama ilerlemeyi gösterir. Çalışırken isteği **Durdur**abilirsiniz; ancak durdurmak devam eden işlemi iptal eder ve geri alınamaz.
3. **Gerektiğinde onay** — istek önemli bir şeyi değiştirecekse uygulama tam olarak ne yapacağını gösterir ve önce onayınızı ister. Bir geri sayım vardır; süresi dolarsa yeniden istemeniz yeter.
4. **İşlem tamamlandı** — sonuç, neyin değiştiğinin özetiyle birlikte anında takviminize düşer.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/tr/ai-result.png" alt="AI sonucu" width="280">

Aynı anda yalnızca bir istek çalışır. Biri hâlâ onayınızı beklerken bir yenisini gönderirseniz uygulama önce ilkini halletmenizi söyler.

---

## Krediler

AI istekleri, **her gün sıfırlanan günlük bir krediden** düşer. Kalan miktar AI giriş ekranının üst kısmında görünür, böylece göndermeden önce ne durumda olduğunuzu bilirsiniz.

Krediler biterse hızlı AI girişi bir sonraki sıfırlanmaya kadar duraklar. Uygulamadaki diğer her şey çalışmayı sürdürür.

---

## İsteyebileceği izinler

| İzin | Ne için kullanılır |
|---|---|
| Mikrofon + Konuşma Tanıma | Sesli giriş |
| Kamera | **Görselden oku** için fotoğraf çekme |
| Fotoğraf Kitaplığı | Var olan bir görseli seçme |
| Bildirimler | Arka plandaki bir isteğin sonucunu size bildirme |

Her izin yalnızca ilgili özelliği ilk kez kullandığınızda istenir ve izin verilmese de uygulama çalışmayı sürdürür — sesli giriş klavyeye, görsel girişi ise yazmaya devreder.

---

[← İçindekiler](./README.md) · [Sıradaki: Widget'lar ve Kilit Ekranı →](./03-widgets.md)
