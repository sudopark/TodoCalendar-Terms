# 2. Introducere rapidă AI

[← Cuprins](./README.md)

---

Descrieți ce doriți în limbaj obișnuit și aplicația construiește totul pentru dvs. — „prânz cu Sara vineri la ora 12”, „mută dentistul marțea viitoare”, „marchează rufele ca finalizate”. Fără formulare, fără ales o dată dintr-o rotiță.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ro/ai-input.png" alt="Introducere rapidă AI" width="280">

Introducerea rapidă AI cere un cont autentificat. Tot restul aplicației funcționează și fără.

---

## Ce poate face

- Creează sarcini și programări, cu ora, repetarea și tipul de eveniment deduse din ce ați spus
- Modifică un eveniment existent — îl mută, îl redenumește, îi schimbă ora
- Finalizează o sarcină sau anulează o finalizare
- Șterge un eveniment
- Rezolvă mai multe lucruri într-o singură solicitare („adaugă sală luni, miercuri și vineri la ora 7”)

---

## Moduri de a trimite o solicitare

### În aplicație

Atingeți butonul AI din ecranul calendarului. Se deschide fereastra de introducere, cu două moduri între care puteți comuta oricând:

- **Voce** — vorbiți și priviți cum apare transcrierea în timp real. Are nevoie de permisiunea pentru microfon și recunoaștere vocală; dacă una dintre ele este refuzată, aplicația vă propune să deschideți Setările iOS sau să treceți la tastatură.
- **Tastatură** — o scrieți. Utilă atunci când sunteți undeva unde nu puteți vorbi.

### Dintr-o imagine

**Citește dintr-o imagine** transformă o poză în evenimente. **Fă o fotografie** sau **Alege din bibliotecă**; aplicația citește textul de pe ea — un orar de cursuri, un afiș de eveniment, o captură dintr-o conversație — și vă arată ce a găsit, ca să puteți îndrepta orice a ieșit greșit înainte de trimitere.

Puteți atașa **Instrucțiuni suplimentare (opțional)** ca să orientați rezultatul, de pildă „adaugă-le ca sarcini”. Dacă în imagine nu există text lizibil, aplicația vă spune, în loc să trimită o solicitare goală.

### Siri

Spuneți **„Adaugă cu AI în To-do Calendar”** — sau „Adaugă o programare în To-do Calendar” / „Adaugă o sarcină în To-do Calendar”. Siri vă întreabă ce doriți să adăugați, iar solicitarea rulează **în fundal, fără să deschidă aplicația**. Siri răspunde „Am înțeles. Vă anunț când e gata.”, iar când rezultatul e pregătit primiți o notificare.

### Butonul de Acțiune

Alocați butonului de Acțiune scurtătura **Adaugă cu AI**. O apăsare, spuneți ce aveți de spus, gata — aplicația nu trebuie să iasă niciodată în prim-plan.

### Widget și Centrul de control

- Widgetul **Adăugați cu AI** — pentru ecranul principal sau pentru ecranul de blocare; deschide ecranul de introducere AI dintr-o singură atingere.
- **Centrul de control** (iOS 18 și mai nou) — adăugați același control **Adaugă cu AI** în Centrul de control, ca punct de intrare la o glisare în jos.

### Fereastra de distribuire

Distribuiți **text sau o imagine din orice altă aplicație** direct către AI-ul din To-do Calendar. Citiți un mesaj cu detaliile unei întâlniri sau vă uitați la un afiș în Poze — apăsați pe distribuire, alegeți To-do Calendar, adăugați o instrucțiune dacă vreți și trimiteți.

Și solicitarea din fereastra de distribuire rulează în fundal. Primiți o confirmare că a fost trimisă, iar rezultatul îl verificați în aplicație.

---

## Cum decurge o solicitare

1. **Trimis** — solicitarea pleacă. Dacă a venit de la Siri, de la butonul de Acțiune sau din fereastra de distribuire, nu trebuie să țineți aplicația deschisă.
2. **Se procesează** — aplicația arată progresul. Puteți da **Stop** unei solicitări în timp ce rulează, însă oprirea anulează comanda în desfășurare, iar aceasta nu va putea fi reluată.
3. **Este necesară confirmarea** — dacă solicitarea ar schimba ceva important, aplicația vă cere mai întâi aprobarea și vă arată exact ce urmează să facă. Există o numărătoare inversă; dacă expiră, solicitați pur și simplu din nou.
4. **Comandă finalizată** — rezultatul ajunge imediat în calendar, împreună cu un rezumat al modificărilor.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ro/ai-result.png" alt="Rezultatul AI" width="280">

Rulează o singură solicitare pe rând. Dacă trimiteți alta în timp ce una încă vă așteaptă aprobarea, aplicația vă spune să o rezolvați mai întâi pe prima.

---

## Credite

Fiecare solicitare AI consumă **credite**, iar creditele se reîncarcă în fiecare zi. Cât a rămas se vede în capul ecranului de introducere AI, așa că știți cum stați înainte de a trimite.

Când se epuizează, introducerea rapidă AI așteaptă reîncărcarea de a doua zi. Tot restul aplicației continuă să funcționeze.

---

## Permisiuni pe care le poate cere

| Permisiune | Folosită pentru |
|---|---|
| Microfon + Recunoaștere vocală | Introducerea vocală |
| Cameră | Fotografierea pentru **Citește dintr-o imagine** |
| Bibliotecă foto | Alegerea unei imagini existente |
| Notificări | Anunțarea rezultatului unei solicitări din fundal |

Fiecare este cerută abia când folosiți prima dată funcția care are nevoie de ea, iar aplicația merge mai departe și fără — introducerea vocală se retrage la tastatură, iar cea din imagine la scris.

---

[← Cuprins](./README.md) · [Următorul: Widget-uri și ecranul de blocare →](./03-widgets.md)
