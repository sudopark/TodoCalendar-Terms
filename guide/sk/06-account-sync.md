# 6. Účet a synchronizácia

[← Obsah](./README.md)

---

## Účet nepotrebujete

To-do Calendar funguje **primárne offline**. Každá udalosť, ktorú vytvoríte, sa najprv zapíše do zariadenia, takže aplikácia sa otvorí okamžite, funguje aj v lietadle a nikdy vás nenechá čakať na sieť.

Nie je to obmedzený režim — vytváranie udalostí, pravidlá opakovania, upozornenia, typy udalostí, sviatky, widgety aj externé kalendáre fungujú úplne bez účtu. Nič nie je zamknuté, kým sa nezaregistrujete.

---

## Čo pridáva prihlásenie

Prihláste sa cez **Google** alebo **Apple** a získate navyše:

- **Zálohu** — vaše udalosti žijú vo vašom účte, nielen v tomto telefóne
- **Synchronizáciu medzi zariadeniami** — rovnaký kalendár na každom zariadení s iOS, na ktorom ste prihlásení
- **[Rýchle zadávanie AI](./02-ai-input.md)** — jediná funkcia, ktorá účet potrebuje, pretože požiadavka beží na serveri

---

## Udalosti, ktoré ste už vytvorili

Ak ste aplikáciu používali bez účtu, prihlásením o tú prácu neprídete. Všetko, čo ste vytvorili predtým, sa **automaticky migruje do vášho účtu** — najprv typy udalostí, potom úlohy, termíny, detaily udalostí a splnené úlohy — a aplikácia vám povie, koľko udalostí presúva a kedy je hotová.

Nemusíte robiť nič a po ceste sa nič nemaže.

---

## Udržiavanie synchronizácie

Synchronizácia beží sama na pozadí — po zmenách, keď sa aplikácia vráti do popredia, a priebežne medzi tým. Keď skončí, obnovia sa aj widgety.

Ak niečo vyzerá zastarane, **Vynútiť synchronizáciu** v nastaveniach udalostí zmaže to, čo už aplikácia synchronizovala, a stiahne všetko nanovo od začiatku.

Ak sa tá istá udalosť zmenila na dvoch miestach, vyhráva verzia zo servera.

---

## Správa účtu

V **Nastavenia › Účet** vidíte, akým spôsobom ste sa prihlásili, aký e-mail je k účtu pripojený a kedy ste sa prihlásili naposledy.

- **Odhlásiť sa** — aplikácia sa vráti do režimu offline a pracuje ďalej s lokálnymi údajmi.
- **Vymazať účet** — odstráni váš účet aj jeho údaje. Nedá sa to vrátiť späť, preto vás aplikácia pred vykonaním požiada o potvrdenie.

---

[← Obsah](./README.md)
