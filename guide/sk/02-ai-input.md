# 2. Rýchle zadávanie AI

[← Obsah](./README.md)

---

Opíšte bežnou rečou, čo chcete, a aplikácia to za vás zostaví — „obed so Sárou v piatok napoludnie“, „presuň zubára na budúci utorok“, „označ pranie ako hotové“. Žiadne formuláre, žiadne vyberanie dátumu z kolieska.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/sk/ai-input.png" alt="Rýchle zadávanie AI" width="280">

Rýchle zadávanie AI vyžaduje prihlásený účet. Všetko ostatné v aplikácii funguje aj bez neho.

---

## Čo dokáže

- Vytvárať úlohy a termíny, pričom čas, opakovanie aj typ udalosti odvodí z toho, čo ste povedali
- Zmeniť existujúcu udalosť — presunúť ju, premenovať, prečasovať
- Splniť úlohu alebo vrátiť dokončenie späť
- Odstrániť udalosť
- Vybaviť viac vecí naraz („pridaj posilňovňu v pondelok, stredu a piatok o 7:00“)

---

## Ako poslať požiadavku

### V aplikácii

Klepnite na tlačidlo AI na obrazovke kalendára. Otvorí sa vstupný hárok s dvoma režimami, medzi ktorými môžete kedykoľvek prepínať:

- **Hlas** — hovorte a sledujte, ako sa prepis objavuje naživo. Potrebuje povolenie na mikrofón a rozpoznávanie reči; ak je ktorékoľvek z nich zamietnuté, aplikácia ponúkne otvorenie Nastavení iOS alebo prepnutie na klávesnicu.
- **Klávesnica** — napíšte to. Hodí sa, keď ste tam, kde sa nedá hovoriť.

### Z obrázka

**Čítať z obrázka** premení fotku na udalosti. **Odfotiť** alebo **Vybrať z knižnice** — aplikácia prečíta text na obrázku (rozvrh hodín, plagát podujatia, snímku správy) a ukáže vám, čo našla, aby ste pred odoslaním opravili, čo vyšlo nesprávne.

K výsledku môžete pripojiť **Ďalšie pokyny (voliteľné)**, napríklad „pridaj toto ako úlohy“. Ak v obrázku nie je čitateľný text, aplikácia vám to povie namiesto toho, aby poslala prázdnu požiadavku.

### Siri

Povedzte **„Pridať pomocou AI v To-do Calendar“** — alebo „Pridať termín v To-do Calendar“ / „Pridať úlohu v To-do Calendar“. Siri sa opýta, čo chcete pridať, a požiadavka beží **na pozadí bez otvorenia aplikácie**. Siri odpovie „Rozumiem. Dám vám vedieť, keď to bude hotové.“ a keď je výsledok pripravený, príde vám upozornenie.

### Tlačidlo Akcia

Priraďte tlačidlu Akcia skratku **Pridať pomocou AI**. Jedno stlačenie, poviete tú vec a hotovo — aplikácia sa vôbec nemusí dostať do popredia.

### Widget a Ovládacie centrum

- **Widget Pridať pomocou AI** — widget na ploche alebo uzamknutej obrazovke, ktorý jedným klepnutím otvorí obrazovku zadávania AI.
- **Ovládacie centrum** (iOS 18 a novší) — pridajte si rovnaký ovládací prvok do Ovládacieho centra a máte vstup na potiahnutie zhora.

### Hárok zdieľania

Pošlite **text alebo obrázok z ktorejkoľvek inej aplikácie** rovno do AI v To-do Calendar. Čítate správu s podrobnosťami o stretnutí alebo si vo Fotkách prezeráte plagát? Klepnite na zdieľanie, vyberte To-do Calendar, prípadne pridajte pokyn a odošlite.

Aj požiadavka z hárka zdieľania beží na pozadí. Dostanete potvrdenie, že bola odoslaná, a výsledok si pozriete v aplikácii.

---

## Ako požiadavka prebieha

1. **Odoslané** — vaša požiadavka odchádza. Ak prišla zo Siri, tlačidla Akcia alebo hárka zdieľania, aplikáciu nemusíte nechať otvorenú.
2. **Spracúva sa** — aplikácia ukazuje priebeh. Bežiacu požiadavku môžete **zastaviť**, hoci zastavením sa rozpracovaná práca zruší a nebude sa dať obnoviť.
3. **Vyžaduje sa potvrdenie** — ak by požiadavka zmenila niečo podstatné, aplikácia vás najprv požiada o schválenie a presne ukáže, čo sa chystá urobiť. Beží pri tom odpočet; ak vyprší, jednoducho požiadate znova.
4. **Príkaz dokončený** — výsledok pristane v kalendári okamžite, spolu so zhrnutím toho, čo sa zmenilo.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/sk/ai-result.png" alt="Výsledok AI" width="280">

Naraz beží iba jedna požiadavka. Ak pošlete ďalšiu, kým predchádzajúca stále čaká na vaše schválenie, aplikácia vám povie, aby ste najprv vybavili tú prvú.

---

## Kredity

Požiadavky AI čerpajú z **denného limitu, ktorý sa každý deň obnoví**. Koľko vám zostáva, vidíte navrchu obrazovky zadávania AI, takže vždy viete, ako na tom pred odoslaním ste.

Keď sa limit vyčerpá, rýchle zadávanie AI si dá pauzu až do ďalšieho obnovenia. Všetko ostatné v aplikácii funguje ďalej.

---

## Povolenia, o ktoré môže požiadať

| Povolenie | Na čo slúži |
|---|---|
| Mikrofón + rozpoznávanie reči | Hlasové zadávanie |
| Fotoaparát | Odfotenie fotky pre **Čítať z obrázka** |
| Knižnica fotiek | Výber existujúceho obrázka |
| Upozornenia | Oznámenie výsledku požiadavky bežiacej na pozadí |

Aplikácia si o každé z nich povie až vtedy, keď prvýkrát použijete funkciu, ktorá ho potrebuje, a funguje aj bez neho — hlasové zadávanie sa vráti ku klávesnici a zadávanie z obrázka k písaniu.

---

[← Obsah](./README.md) · [Ďalej: Widgety a uzamknutá obrazovka →](./03-widgets.md)
