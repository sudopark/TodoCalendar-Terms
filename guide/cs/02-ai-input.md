# 2. Rychlé zadávání AI

[← Obsah](./README.md)

---

Popište běžnou řečí, co chcete, a aplikace to za vás sestaví — „oběd se Sárou v pátek v poledne“, „přesuň zubaře na příští úterý“, „označ prádlo jako hotové“. Žádné formuláře, žádné výběry data.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/cs/ai-input.png" alt="Rychlé zadávání AI" width="280">

Rychlé zadávání AI vyžaduje přihlášený účet. Všechno ostatní v aplikaci funguje i bez něj.

---

## Co to umí

- Vytvářet úkoly a termíny — čas, opakování i typ události odvodí z toho, co jste řekli
- Měnit existující událost — přesunout ji, přejmenovat, přečasovat
- Dokončit úkol nebo dokončení vrátit zpět
- Smazat událost
- Zvládnout víc věcí v jednom požadavku („přidej posilovnu v pondělí, ve středu a v pátek v 7 ráno“)

---

## Jak poslat požadavek

### V aplikaci

Klepněte na tlačítko AI na obrazovce kalendáře. Otevře se vstupní panel se dvěma režimy, mezi kterými můžete kdykoli přepínat:

- **Hlas** — mluvte a sledujte, jak se přepis objevuje naživo. Potřebuje oprávnění k mikrofonu a rozpoznávání řeči; když je některé odepřené, aplikace nabídne otevřít Nastavení, nebo přejít na **Místo toho psát**.
- **Klávesnice** — napište to. Hodí se tam, kde nemůžete mluvit.

### Z obrázku

**Číst z obrázku** promění fotku v události. **Vyfotit**, nebo **Vybrat z knihovny** — aplikace přečte text na obrázku (rozvrh hodin, plakát na akci, snímek zprávy) a ukáže vám, co našla, abyste před odesláním mohli opravit, co se nepovedlo.

Výsledek můžete nasměrovat přes **Další pokyny (volitelné)**, třeba „přidat jako úkoly“. Když v obrázku není žádný čitelný text, aplikace vám to řekne, místo aby poslala prázdný požadavek.

### Siri

Řekněte **„Hej, To-do Calendar“** — fungují i „Požadavek v To-do Calendar“, „Zeptat se aplikace To-do Calendar“, „Poslat požadavek aplikaci To-do Calendar“ a „Přidat pomocí AI v To-do Calendar“. Můžete říct i „Todo Calendar“ bez spojovníku. Siri se zeptá, co má udělat, a požadavek běží **na pozadí, aniž by se aplikace otevřela**. Siri odpoví „Rozumím. Dám vám vědět, až to bude hotové.“ a jakmile je výsledek připravený, přijde upozornění.

### Tlačítko Akce

Přiřaďte tlačítku Akce zkratku **Poslat**. Jedno stisknutí, řeknete to a hotovo — aplikace se vůbec neotevře.

### Widget a Ovládací centrum

- **Widget Přidat pomocí AI** — widget na ploše nebo na uzamčené obrazovce, který jedním klepnutím otevře obrazovku zadávání AI.
- **Ovládací centrum** (iOS 18 a novější) — přidejte si stejný ovládací prvek do Ovládacího centra a máte vstup na jedno přejetí dolů.

### Nabídka sdílení

Sdílejte **text nebo obrázek z jakékoli jiné aplikace** rovnou do AI v To-do Calendar. Čtete zprávu s podrobnostmi o srazu nebo se díváte na plakát ve Fotkách — dejte sdílet, vyberte To-do Calendar, případně přidejte pokyn a odešlete.

I požadavek z nabídky sdílení běží na pozadí. Dostanete potvrzení, že odešel, a výsledek zkontrolujete v aplikaci.

---

## Jak požadavek probíhá

1. **Odesláno** — požadavek odejde. Když přišel ze Siri, z tlačítka Akce nebo z nabídky sdílení, nemusíte mít aplikaci otevřenou.
2. **Zpracovává se** — aplikace ukazuje průběh. Běžící požadavek můžete **Zastavit**, jenže zastavení zruší rozdělanou práci a obnovit ji nejde.
3. **Vyžadováno potvrzení** — když by požadavek změnil něco podstatného, aplikace si nejdřív řekne o schválení a přesně ukáže, co se chystá udělat. Běží k tomu odpočet; když vyprší, prostě požádáte znovu.
4. **Příkaz dokončen** — výsledek se okamžitě propíše do kalendáře a k tomu dostanete shrnutí, co se změnilo.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/cs/ai-result.png" alt="Výsledek AI" width="280">

Naráz běží jen jeden požadavek. Když pošlete další, zatímco jeden pořád čeká na vaše schválení, aplikace vám řekne, ať nejdřív vyřídíte ten první.

---

## Kredity

Každý požadavek AI spotřebuje **kredity** a ty se vám každý den doplní. Kolik jich zbývá, vidíte nahoře na obrazovce zadávání AI, takže to víte ještě před odesláním.

Když kredity dojdou, rychlé zadávání AI počká na doplnění další den. Všechno ostatní v aplikaci funguje dál.

---

## Oprávnění, o která si může říct

| Oprávnění | K čemu slouží |
|---|---|
| Mikrofon + rozpoznávání řeči | Hlasové zadávání |
| Fotoaparát | Pořízení fotky pro **Číst z obrázku** |
| Fotky | Výběr existujícího obrázku |
| Upozornění | Oznámení výsledku požadavku, který běžel na pozadí |

O každé z nich si aplikace řekne teprve tehdy, když poprvé použijete funkci, která ho potřebuje, a i bez něj funguje dál — hlasové zadávání ustoupí klávesnici, zadávání z obrázku psaní.

---

[← Obsah](./README.md) · [Další: Widgety a uzamčená obrazovka →](./03-widgets.md)
