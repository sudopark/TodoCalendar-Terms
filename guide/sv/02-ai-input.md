# 2. AI-snabbinmatning

[← Innehåll](./README.md)

---

Beskriv det du vill ha med vanliga ord så bygger appen det åt dig – "lunch med Sara på fredag kl. 12", "flytta tandläkaren till nästa tisdag", "markera tvätten som klar". Inga formulär, inget datumhjul att snurra på.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/sv/ai-input.png" alt="AI-snabbinmatning" width="280">

AI-snabbinmatning kräver att du är inloggad. Allt annat i appen fungerar utan konto.

---

## Vad den klarar

- Skapa uppgifter och möten, med tid, upprepning och händelsetyp uttolkade ur det du sa
- Ändra en befintlig händelse – flytta den, byta namn, ge den en ny tid
- Slutföra en uppgift, eller ångra ett slutförande
- Ta bort en händelse
- Hantera flera saker i samma begäran ("lägg till gympa måndag, onsdag och fredag kl. 7")

---

## Sätt att skicka en begäran

### I appen

Tryck på AI-knappen i kalendervyn. Inmatningsvyn öppnas med två lägen som du kan växla mellan när som helst:

- **Röst** – prata och se texten tolkas live. Kräver behörighet för mikrofon och taligenkänning; nekas någon av dem erbjuder appen att öppna iOS-inställningarna eller att **Skriv istället** med tangentbordet.
- **Tangentbord** – skriv det. Bra när du är någonstans där du inte kan prata.

### Från en bild

**Läs från bild** förvandlar en bild till händelser. **Ta en bild** eller **Välj från bibliotek**; appen läser texten i den – ett schema, en evenemangsaffisch, en skärmbild av ett meddelande – och visar vad den hittade så att du kan rätta det som blev fel innan du skickar.

Du kan lägga till **Ytterligare instruktioner (valfritt)** för att styra resultatet, som "lägg till dessa som uppgifter". Finns det ingen läsbar text i bilden säger appen till i stället för att skicka en tom begäran.

### Siri

Säg **"Lägg till med AI i To-do Calendar"** – eller "Lägg till ett möte i To-do Calendar" / "Lägg till en uppgift i To-do Calendar". Siri frågar vad du vill lägga till, och begäran körs **i bakgrunden utan att appen öppnas**. Siri svarar "Uppfattat. Jag meddelar dig när det är klart." och du får en avisering när resultatet är färdigt.

### Åtgärdsknappen

Koppla Åtgärdsknappen till genvägen **Lägg till med AI**. Ett tryck, säg saken, klart – appen behöver aldrig komma fram i förgrunden.

### Widget och Kontrollcenter

- **Widgeten Lägg till med AI** – en widget för hemskärmen eller låsskärmen som öppnar AI-inmatningen med ett tryck.
- **Kontrollcenter** (iOS 18 och senare) – lägg till samma reglage i Kontrollcenter för en ingång som alltid är ett svep bort.

### Delningsmenyn

Dela **text eller en bild från vilken annan app som helst** direkt till To-do Calendars AI. Läser du ett meddelande med detaljerna om en träff, eller tittar på en affisch i Bilder – tryck på dela, välj To-do Calendar, lägg till en instruktion om du vill, och skicka.

Även begäran från delningsmenyn körs i bakgrunden. Du får en bekräftelse på att den skickades, och resultatet ser du i appen.

---

## Så körs en begäran

1. **Skickat** – din begäran ger sig av. Kom den från Siri, Åtgärdsknappen eller delningsmenyn behöver du inte hålla appen öppen.
2. **Bearbetar** – appen visar förloppet. Du kan trycka **Stopp** medan den körs, men då kasseras det påbörjade arbetet och det kan inte återupptas.
3. **Bekräftelse krävs** – skulle begäran ändra något betydelsefullt ber appen dig godkänna först och visar exakt vad den tänker göra. Det finns en nedräkning; går den ut är det bara att fråga igen.
4. **Kommandot slutfört** – resultatet landar i kalendern direkt, med en sammanfattning av vad som ändrades.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/sv/ai-result.png" alt="AI-resultat" width="280">

Bara en begäran körs åt gången. Skickar du en till medan en annan väntar på ditt godkännande säger appen till att du behöver ta hand om den första.

---

## Krediter

AI-begäranden drar från **dagliga krediter som återställs varje dag**. Hur mycket som är kvar visas högst upp i AI-inmatningen, så du vet alltid var du står innan du skickar.

Tar krediterna slut pausar AI-snabbinmatning till nästa återställning. Allt annat i appen fungerar som vanligt.

---

## Behörigheter den kan be om

| Behörighet | Används till |
|---|---|
| Mikrofon + taligenkänning | Röstinmatning |
| Kamera | Att ta en bild för **Läs från bild** |
| Fotobibliotek | Att välja en befintlig bild |
| Aviseringar | Att berätta resultatet av en begäran som körts i bakgrunden |

Var och en frågas om först när du använder funktionen som behöver den, och appen fungerar utan dem – röstinmatning faller tillbaka på tangentbordet, bildinmatning på att skriva själv.

---

[← Innehåll](./README.md) · [Nästa: Widgetar och låsskärm →](./03-widgets.md)
