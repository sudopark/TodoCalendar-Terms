# 1. Temel özellikler

[← İçindekiler](./README.md)

---

## Takvim ekranı

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/tr/calendar.png" alt="Takvim" width="280">

Aylık takvim ana ekrandır. Aylar arasında geçmek için sağa sola kaydırın, bir güne dokunun ve o günün etkinlik listesi hemen altında açılsın.

- Her gün, etkinlik başına bir renkli çubuk gösterir; o güne satıra sığacağından fazla etkinlik düştüğünde bir **+N** göstergesi çıkar.
- Gün listesinin sırası şudur: saatsiz görevler → saatli görevler → randevular → tatiller → harici takvim etkinlikleri.
- İstediğiniz tarihe atlamak için başlığa dokunun ya da doğrudan seçmek için **Tarihi taşı**'yı kullanın.

Her günün ne kadarını göstereceğine siz karar verirsiniz — etkinlik başına ne kadar ayrıntı görüneceği, yazı boyutu, renkler, tatil adları ve ay takvimi. [Kişiselleştirme](./05-personalization.md) her ayarı adıyla tek tek anlatır.

---

## Görevler ve randevular

Uygulamada iki tür etkinlik var ve aradaki fark tek bir şeyde: onu işaretleyip tamamlıyor musunuz.

| | Görev | Randevu |
|---|---|---|
| Saat | İsteğe bağlı | Zorunlu |
| Tamamlama | Var — işaretleyerek | Yok |
| Saatsiz olarak | Siz bitirene kadar **Güncel Görev Listesi**'nde kalır | Mümkün değil |

**Saatsiz bir görev**, yakında yapmanız gereken ama henüz planlamadığınız işler içindir. Tamamlanana kadar takvimin en üstünde ve **Güncel Görev Listesi** widget'ında durur.

İstediğiniz zaman iki yöne de dönüştürebilirsiniz — etkinliğin diğer seçenekler menüsündeki **Randevuya dönüştür** / **Göreve dönüştür**. Bir görevi randevuya dönüştürmek için saat bilgisi gerekir.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/tr/event-detail.png" alt="Etkinlik ayrıntısı" width="280">

Her etkinlik bir **Konum** (harita önizlemesi ve tercih ettiğiniz harita uygulamasında tek dokunuşla açma ile), önizlemeli bir **Bağlantı** ve bir **Not** taşıyabilir.

---

## Etkinlik ekleme

Bir etkinlik eklemenin, ne kadar yazmak istediğinize göre üç yolu var:

- **Hızlı ekleme** — gün listesinin altındaki giriş alanı. Bir ad yazın, return tuşuna basın, görev oluşturulur.
- **Ayrıntılı giriş** — saat, tekrarlama, hatırlatmalar, etkinlik türü, konum, bağlantı ve not içeren düzenleyiciyi açmak için **+**'ya dokunun.
- **Hızlı AI girişi** — günlük dille anlatın, etkinliği uygulama kursun. Bkz. [Hızlı AI girişi](./02-ai-input.md).

Bir görev için yalnızca ad yeterlidir; bir randevu için ad ve saat gerekir.

---

## Tekrarlayan etkinlikler

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/tr/repeat-options.png" alt="Tekrarlama seçenekleri" width="240">

Uygulama sizden açılır menülerden bir tekrarlama kuralı kurmanızı istemez; seçtiğiniz tarihi okur ve ona uygun hazır seçenekler sunar. Bir perşembe seçin, liste size **Her Perşembe** ve **Her ayın üçüncü Perşembe günü** seçeneklerini sunar.

**Yaygın aralıklar**

- Her gün
- Her hafta · Her 2 haftada bir · Her 3 haftada bir · Her 4 haftada bir — etkinlikle aynı hafta gününde
- Her ay — her ay aynı tarihte
- Her yıl
- Her yıl (ay takvimi) — ay takvimine göre kutlanan doğum günleri ve yıl dönümleri için

**Ay içindeki konuma göre**

- Her hafta içi gün — pazartesiden cumaya. Etkinlik bir hafta içi günde başladığında sunulur
- Her ayın son haftasının tüm günleri
- Her ayın ilk / ikinci / üçüncü / dördüncü / son **Perşembe** günü — hafta günü seçtiğiniz tarihten doldurulur, yani cuma günkü bir etkinlik **Her ayın son Cuma günü** seçeneğini sunar

**Tekrarlama Bitişi**

Bir tekrarlama seçtiğinizde nasıl duracağını da belirlersiniz: **Asla**, belirli bir **Tarihte** ya da belirli sayıda tekrardan **Sonra**.

Tekrarlayan görevler, tekrarlayan randevulardan farklı davranır:

- Tamamlanmamış bir tekrar, saati geçse bile bugünün takviminde görünmeye devam eder — kendiliğinden bir sonraki tekrara geçmez.
- Onu tamamladığınızda o tekrar, tamamlanan görevler listesine geçer ve bir sonraki tekrar oluşturulur.
- **Bu görevi atla**, tamamlandı olarak işaretlemeden sizi bir sonraki tekrara götürür.
- Tekrarlamanın bir bitiş koşulu varsa ve sıradaki tekrar kalmamışsa seri sona erer.

Tekrarlayan bir etkinliğin bir tekrarını düzenlerken veya silerken kapsamı siz seçersiniz: **Yalnızca bu sefer**, **Bu andan itibaren** ya da **Tüm etkinlikler**.

Bağlı bir harici takvimdeki etkinliklerde ay takvimi seçeneği sunulmaz — harici takvimlerin ay takvimine göre bir tekrarlama kuralını saklayacak yeri yoktur.

---

## Etkinlik türleri ve renkler

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/tr/event-type-list.png" alt="Etkinlik türleri" width="280">

Etkinlik türleri sizin kategorilerinizdir ve etkinliğin takvimde göründüğü rengi de onlar taşır. Her birine kendi rengini vererek dilediğiniz kadar tür oluşturun.

- Bir türü kapattığınızda o türdeki bütün etkinlikler takvimden gizlenir — yoğun bir iş takvimini bağlantısını kesmeden susturmak için kullanışlıdır.
- Bir türü silerken ona bağlı etkinlikleri saklamayı ya da silmeyi seçebilirsiniz.
- Bir **Varsayılan Etkinlik Türü** belirleyin ki yeni etkinlikler her seferinde seçim yapmadan doğru yere düşsün.

Tatillerin ve bağlı harici takvimlerin de kendi türleri vardır; böylece onları da ayrı ayrı gizleyebilirsiniz.

---

## Hatırlatmalar

Her etkinlik için ihtiyacınız kadar hatırlatma kurun.

- **Saatli etkinlikler** — etkinlik saatinde ya da 1 / 5 / 10 / 15 / 30 dakika, 1 / 2 saat, 1 / 2 / 7 gün önce.
- **Tüm gün süren etkinlikler** — o gün saat 9.00'da veya öğlen, ya da 1 / 2 / 7 gün önce saat 9.00'da.
- **Özel** — istediğiniz herhangi bir zamanı seçin.

Saatli ve tüm gün süren etkinliklerin varsayılanları Ayarlar'da ayrı ayrı belirlenir, böylece yeni etkinlikler hazır hatırlatmalarla gelir. Hatırlatmalar için bildirim izni gerekir; izin kapalıysa uygulama sizi iOS Ayarlar'a yönlendirir.

---

## En önemli etkinlik

Kaçırmayı göze alamadığınız tek şeyi sabitleyin. En önemli etkinlik, hangi tarihe bakıyor olursanız olun takvimin en üstünde kalır ve kendi widget'ı vardır.

Görevler ve tekrarlamayan randevular en önemli olarak ayarlanabilir. Tekrarlayan randevular ayarlanamaz.

---

## Tamamlanmamış görevler

Saati geçtiği hâlde tamamlanmamış görevler, takvimin en üstündeki **Tamamlanmamış Görevler** bölümünde toplanır; böylece kaçırdığınız bir görev geçmiş bir tarihte gömülü kalmaz.

Saatsiz görevler ve gelecekteki görevler tamamlanmamış sayılmaz — henüz vakti gelmemiştir. Görmek istemiyorsanız bu bölümü Ayarlar'dan tümüyle gizleyebilirsiniz.

---

## Tamamlanan görevler

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/tr/done-todos.png" alt="Tamamlanan görevler" width="280">

İşaretlediğiniz her şey saklanır ve ne zaman bitirdiğinize göre gruplanır — bugün, dün, bu ay, sonrası ay ve yıl bazında.

- Bir tamamlamayı geri alarak görevi geri getirin.
- Toplu temizleyin: tümünü silin ya da yalnızca 1 / 3 / 6 aydan veya 1 yıldan eski olanları.

---

## Paylaşma

**Bir günü, bir haftayı veya bir ayı** metin olarak ya da görsel kart olarak paylaşın.

Paylaşmadan önce hangi etkinlik türlerinin dahil edileceğini süzebilir ve tür adlarının görünüp görünmeyeceğini seçebilirsiniz; böylece haftanızı, içindeki her şeyi açık etmeden gönderirsiniz.

---

[← İçindekiler](./README.md) · [Sıradaki: Hızlı AI girişi →](./02-ai-input.md)
