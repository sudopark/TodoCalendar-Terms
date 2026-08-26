# 1. Podstawy

[← Spis treści](./README.md)

---

## Kalendarz

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pl/calendar.png" alt="Kalendarz" width="280">

Kalendarz miesiąca jest ekranem głównym. Przesuwaj w lewo i w prawo, żeby zmieniać miesiące, a stuknij dzień, żeby otworzyć pod spodem listę jego wydarzeń.

- Każdy dzień pokazuje kolorowy pasek dla każdego wydarzenia, a gdy w wierszu nie mieszczą się wszystkie — wskaźnik **+N**.
- Lista dnia ma stałą kolejność: zadania bez godziny → zadania z godziną → terminy → święta → wydarzenia z kalendarzy zewnętrznych.
- Stuknij nagłówek, żeby przeskoczyć do dowolnej daty, albo wybierz ją wprost przez **Przenieś datę**.

To, ile pokazuje każdy dzień, zależy od Ciebie: ilość szczegółów przy wydarzeniu, wielkość tekstu, kolory, nazwy świąt i kalendarz księżycowy. [Personalizacja](./05-personalization.md) omawia każde ustawienie z nazwy.

---

## Zadania i terminy

Aplikacja zna dwa rodzaje wydarzeń, a różnica polega na tym, czy daną rzecz się odhacza.

| | Zadanie | Termin |
|---|---|---|
| Czas | Opcjonalny | Wymagany |
| Ukończenie | Tak — odhaczasz je | Nie |
| Bez godziny | Zostaje w sekcji **Bieżąca lista zadań**, dopóki go nie skończysz | Niemożliwe |

**Zadanie bez godziny** jest dla czegoś, co trzeba zrobić wkrótce, ale nie ma jeszcze swojej pory. Siedzi na górze kalendarza i w widżecie **Bieżąca lista zadań**, dopóki go nie ukończysz.

W każdej chwili przejdziesz z jednego na drugie — **Zmień na termin** / **Zmień na zadanie** w menu wydarzenia. Zmiana zadania w termin wymaga podania czasu.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pl/event-detail.png" alt="Szczegóły wydarzenia" width="280">

W każdym wydarzeniu mogą się znaleźć **Miejsce**, **Link** i **Notatka**. Miejsce pokazuje podgląd mapy i jednym stuknięciem otwiera się w ulubionej aplikacji map, a Link ma własny podgląd.

---

## Dodawanie wydarzeń

Trzy sposoby na dodanie wydarzenia — zależnie od tego, ile chcesz wpisać:

- **Szybkie dodawanie** — pole na dole listy dnia. Wpisz nazwę, zatwierdź i masz zadanie.
- **Pełne szczegóły** — stuknij **+**, żeby otworzyć edytor z czasem, powtarzaniem, przypomnieniami, typem wydarzenia, miejscem, linkiem i notatką.
- **Szybkie wprowadzanie AI** — opisz to zwykłym językiem i pozwól aplikacji zbudować wydarzenie. Zobacz [Szybkie wprowadzanie AI](./02-ai-input.md).

Zadaniu wystarczy nazwa. Termin potrzebuje nazwy i czasu.

---

## Wydarzenia powtarzające się

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pl/repeat-options.png" alt="Opcje powtarzania" width="240">

Zamiast kazać Ci składać regułę powtarzania z rozwijanych list, aplikacja czyta wybraną datę i podsuwa opcje gotowe właśnie dla niej. Wybierz czwartek, a lista poda **Co tydzień: czwartek** i **Trzeci czwartek każdego miesiąca**.

**Typowe cykle**

- Codziennie
- Co tydzień · Co 2. tydzień · Co 3. tydzień · Co 4. tydzień — w ten sam dzień tygodnia co wydarzenie
- Co miesiąc — tego samego dnia każdego miesiąca
- Co rok
- Co rok (kalendarz księżycowy) — dla urodzin i rocznic liczonych według kalendarza księżycowego

**Według pozycji w miesiącu**

- Każdego dnia roboczego — od poniedziałku do piątku. Pojawia się, gdy wydarzenie zaczyna się w dzień roboczy
- Wszystkie dni ostatniego tygodnia każdego miesiąca
- Pierwszy / Drugi / Trzeci / Czwarty / Ostatni **czwartek** każdego miesiąca — dzień tygodnia bierze się z wybranej daty, więc wydarzenie w piątek dostanie **Ostatni piątek każdego miesiąca**

**Koniec powtarzania**

Gdy już wybierzesz powtarzanie, zdecyduj, kiedy ma się skończyć: **Nigdy** zostawia je bez końca, **W dniu** ustala stałą datę zakończenia, a **Po** ogranicza liczbę wystąpień.

Powtarzające się zadania zachowują się inaczej niż powtarzające się terminy:

- Nieukończone powtórzenie zostaje widoczne w dzisiejszym kalendarzu nawet po swojej godzinie — samo nie przechodzi do następnego wystąpienia.
- Ukończenie odkłada to wystąpienie na listę ukończonych zadań i tworzy kolejne.
- **Pomiń to zadanie** przenosi Cię do następnego wystąpienia bez oznaczania obecnego jako zrobione.
- Gdy powtarzanie ma warunek końca i nie ma już następnego wystąpienia, seria się kończy.

Przy edycji albo usuwaniu jednego wystąpienia wydarzenia powtarzającego się wybierasz zakres: **Tylko tym razem**, **Od teraz** albo **Wszystkie wydarzenia**.

Dla wydarzeń z połączonego kalendarza zewnętrznego opcja księżycowa się nie pojawia — kalendarze zewnętrzne nie mają gdzie zapisać reguły powtarzania według kalendarza księżycowego.

---

## Typy wydarzeń i kolory

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pl/event-type-list.png" alt="Typy wydarzeń" width="280">

Typy wydarzeń to Twoje kategorie i to one niosą kolor, którym wydarzenie pokazuje się w kalendarzu. Utwórz ich tyle, ile chcesz, każdy w swoim kolorze.

- Wyłącz typ, a wszystkie wydarzenia tego typu znikną z kalendarza — przydaje się, gdy chcesz wyciszyć zabiegany kalendarz służbowy, nie rozłączając go.
- Przy usuwaniu typu decydujesz, czy zachować, czy skasować przypisane do niego wydarzenia.
- Ustaw **Domyślny typ wydarzenia**, żeby nowe wydarzenia trafiały na swoje miejsce bez wybierania za każdym razem.

Święta i połączone kalendarze zewnętrzne mają własne typy, więc je też ukryjesz niezależnie.

---

## Przypomnienia

Do każdego wydarzenia ustawisz tyle przypomnień, ile potrzebujesz.

- **Wydarzenia z godziną** — o godzinie wydarzenia albo 1 / 5 / 10 / 15 / 30 minut, 1 / 2 godziny, 1 / 2 / 7 dni wcześniej.
- **Wydarzenia całodniowe** — o 9:00 albo w południe tego dnia, albo o 9:00 na 1 / 2 / 7 dni wcześniej.
- **Niestandardowy** — wybierz dowolny moment.

Domyślne przypomnienia dla wydarzeń z godziną i całodniowych ustawia się osobno w Ustawieniach, więc nowe wydarzenia od razu je mają. Przypomnienia potrzebują uprawnienia do powiadomień; jeśli jest wyłączone, aplikacja pokieruje Cię do Ustawień iOS.

---

## Najważniejsze wydarzenie

Przypnij tę jedną rzecz, której nie możesz przegapić. Najważniejsze wydarzenie zostaje na górze kalendarza niezależnie od tego, na jaką datę patrzysz, i ma własny widżet.

Jako najważniejsze da się ustawić zadania i niepowtarzające się terminy. Powtarzających się terminów — nie.

---

## Niezakończone zadania

Zadania, którym minął czas, a nie zostały ukończone, zbierają się w sekcji **Niezakończone zadania** na górze kalendarza, żeby przeoczone zadanie nie zostało zagrzebane na minionej dacie.

Zadania bez godziny i te z przyszłości nie liczą się jako niezakończone — po prostu ich pora jeszcze nie nadeszła. Jeśli wolisz tego nie oglądać, całą sekcję da się ukryć w Ustawieniach.

---

## Ukończone zadania

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/pl/done-todos.png" alt="Ukończone zadania" width="280">

Wszystko, co odhaczysz, zostaje zachowane i pogrupowane według momentu ukończenia — dziś, wczoraj, ten miesiąc, a dalej według miesięcy i lat.

- Cofnij ukończenie, żeby zadanie wróciło.
- Posprzątaj hurtem: usuń wszystko albo tylko to, co starsze niż 1 miesiąc, 3 miesiące, 6 miesięcy lub 1 rok.

---

## Udostępnianie

Udostępnij **dzień, tydzień albo miesiąc** jako tekst lub jako kartę z obrazem.

Przed wysłaniem wybierzesz, które typy wydarzeń mają wejść, i zdecydujesz, czy pokazywać ich nazwy — dzięki temu wyślesz komuś swój tydzień, nie odsłaniając wszystkiego, co w nim jest.

---

[← Spis treści](./README.md) · [Dalej: Szybkie wprowadzanie AI →](./02-ai-input.md)
