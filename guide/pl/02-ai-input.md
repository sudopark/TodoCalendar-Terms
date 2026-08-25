# 2. Szybkie wprowadzanie AI

[← Spis treści](./README.md)

---

Opisz zwykłym językiem, czego chcesz, a aplikacja to zbuduje — „obiad z Sarą w piątek w południe”, „przenieś dentystę na przyszły wtorek”, „odhacz pranie”. Bez formularzy i bez kręcenia datą na kółku.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pl/ai-input.png" alt="Szybkie wprowadzanie AI" width="280">

Szybkie wprowadzanie AI wymaga zalogowania. Cała reszta aplikacji działa bez konta.

---

## Co potrafi

- Tworzyć zadania i terminy, wyłuskując czas, powtarzanie i typ wydarzenia z tego, co powiesz
- Zmieniać istniejące wydarzenie — przenosić je, zmieniać nazwę, przestawiać godzinę
- Ukończyć zadanie albo cofnąć ukończenie
- Usunąć wydarzenie
- Załatwić kilka rzeczy w jednym poleceniu („dodaj siłownię w poniedziałek, środę i piątek o 7:00”)

---

## Sposoby wysłania polecenia

### W aplikacji

Stuknij przycisk AI na ekranie kalendarza. Otworzy się arkusz wprowadzania z dwoma trybami, między którymi przeskoczysz w każdej chwili:

- **Głos** — mów i patrz, jak na bieżąco pojawia się rozpoznany tekst. Potrzebne są uprawnienia do mikrofonu i rozpoznawania mowy; jeśli któregoś brakuje, aplikacja proponuje otwarcie Ustawień iOS albo przejście na klawiaturę.
- **Klawiatura** — po prostu wpisz. Przydaje się tam, gdzie nie da się mówić.

### Ze zdjęcia

**Odczytaj z obrazu** zamienia zdjęcie w wydarzenia. **Zrób zdjęcie** albo **Wybierz z biblioteki**, a aplikacja odczyta widniejący na nim tekst — plan zajęć, plakat wydarzenia, zrzut wiadomości — i pokaże Ci, co znalazła, żebyś przed wysłaniem poprawił to, co wyszło nie tak.

Możesz dołączyć **Dodatkowe polecenia (opcjonalnie)**, żeby pokierować wynikiem, na przykład „dodaj to jako zadania”. Jeśli na obrazie nie ma czytelnego tekstu, aplikacja powie Ci o tym, zamiast wysyłać puste polecenie.

### Siri

Powiedz **„Dodaj z AI w To-do Calendar”** — albo „Dodaj termin w To-do Calendar” czy „Dodaj zadanie w To-do Calendar”. Siri zapyta, co chcesz dodać, a polecenie pójdzie **w tle, bez otwierania aplikacji**. Siri odpowie „Rozumiem. Dam Ci znać, gdy będzie gotowe”, a gdy wynik będzie gotowy, dostaniesz powiadomienie.

### Przycisk Akcji

Przypisz do przycisku Akcji skrót **Dodaj z AI**. Jedno naciśnięcie, wypowiedziane zdanie i gotowe — aplikacja nawet nie musi wyjść na wierzch.

### Widżet i Centrum sterowania

- **Widżet Dodaj za pomocą AI** — widżet na ekran początkowy albo ekran blokady, który jednym stuknięciem otwiera ekran wprowadzania AI.
- **Centrum sterowania** (iOS 18 i nowsze) — dodaj element sterujący **Dodaj z AI** do Centrum sterowania, żeby wchodzić tam jednym przesunięciem z góry.

### Arkusz udostępniania

Udostępnij **tekst albo obraz z dowolnej innej aplikacji** prosto do AI w To-do Calendar. Czytasz wiadomość ze szczegółami spotkania albo oglądasz plakat w Zdjęciach — stuknij udostępnianie, wybierz To-do Calendar, w razie potrzeby dopisz polecenie i wyślij.

Polecenie z arkusza udostępniania też idzie w tle. Dostaniesz potwierdzenie wysłania, a wynik sprawdzisz w aplikacji.

---

## Jak przebiega polecenie

1. **Wysłanie** — polecenie rusza w drogę. Jeśli poszło z Siri, przycisku Akcji albo arkusza udostępniania, nie musisz trzymać aplikacji otwartej.
2. **Przetwarzanie** — aplikacja pokazuje postęp. W trakcie możesz **Zatrzymać** polecenie, ale zatrzymanie odrzuca rozpoczętą pracę i nie da się jej wznowić.
3. **Wymagane potwierdzenie** — jeśli polecenie zmieniłoby coś istotnego, aplikacja najpierw prosi o zgodę i pokazuje dokładnie, co zamierza zrobić. Jest na to odliczanie; gdy czas upłynie, po prostu poproś jeszcze raz.
4. **Polecenie wykonane** — wynik ląduje w kalendarzu od razu, wraz z podsumowaniem tego, co się zmieniło.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pl/ai-result.png" alt="Wynik AI" width="280">

Naraz przetwarzane jest tylko jedno polecenie. Jeśli wyślesz kolejne, gdy poprzednie wciąż czeka na Twoją zgodę, aplikacja poprosi, żebyś najpierw zajął się tamtym.

---

## Kredyty

Polecenia AI czerpią z **dziennej puli, która odnawia się każdego dnia**. Ile zostało, widzisz na górze ekranu wprowadzania AI, więc przed wysłaniem zawsze wiesz, na czym stoisz.

Gdy pula się skończy, szybkie wprowadzanie AI robi przerwę do następnego odnowienia. Reszta aplikacji działa dalej.

---

## Uprawnienia, o które może poprosić

| Uprawnienie | Do czego służy |
|---|---|
| Mikrofon + rozpoznawanie mowy | Wprowadzanie głosowe |
| Aparat | Zrobienie zdjęcia dla **Odczytaj z obrazu** |
| Biblioteka zdjęć | Wybranie istniejącego obrazu |
| Powiadomienia | Poinformowanie Cię o wyniku polecenia z tła |

O każde z nich aplikacja pyta dopiero przy pierwszym użyciu funkcji, która go potrzebuje, i działa dalej także bez niego — wprowadzanie głosowe zastąpi klawiatura, a obraz zwykłe pisanie.

---

[← Spis treści](./README.md) · [Dalej: Widżety i ekran blokady →](./03-widgets.md)
