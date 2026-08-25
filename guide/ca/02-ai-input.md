# 2. Entrada ràpida amb IA

[← Índex](./README.md)

---

Descriviu el que voleu en llenguatge natural i l'aplicació us ho munta: «dinar amb la Sara divendres al migdia», «mou el dentista a dimarts vinent», «marca la bugada com a feta». Sense formularis ni haver de triar la data en una roda.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ca/ai-input.png" alt="Entrada ràpida amb IA" width="280">

L'entrada ràpida amb IA requereix haver iniciat sessió. Tota la resta de l'aplicació funciona sense compte.

---

## Què pot fer

- Crear tasques i cites, amb l'hora, la repetició i el tipus d'esdeveniment deduïts del que heu dit
- Canviar un esdeveniment existent: moure'l, canviar-li el nom, canviar-li l'hora
- Completar una tasca, o desfer-ne la finalització
- Suprimir un esdeveniment
- Resoldre diverses coses en una sola petició («afegeix gimnàs dilluns, dimecres i divendres a les 7 del matí»)

---

## Maneres d'enviar una petició

### Dins de l'aplicació

Toqueu el botó d'IA a la pantalla del calendari. El full d'entrada s'obre amb dos modes entre els quals podeu anar canviant quan vulgueu:

- **Veu** — parleu i mireu com apareix la transcripció en directe. Cal el permís de micròfon i de reconeixement de veu; si es denega qualsevol dels dos, l'aplicació us ofereix obrir la configuració d'iOS o passar al teclat.
- **Teclat** — escriviu-ho. Va bé quan sou en un lloc on no podeu parlar.

### Des d'una imatge

**Llegeix des d'una imatge** converteix una fotografia en esdeveniments. **Fes una foto** o **Tria de la biblioteca**; l'aplicació llegeix el text que hi ha —un horari de classes, un cartell d'un acte, una captura d'un missatge— i us ensenya què hi ha trobat perquè pugueu corregir el que hagi sortit malament abans d'enviar-ho.

Podeu afegir-hi unes **Instruccions addicionals (opcional)** per orientar el resultat, com ara «afegeix-ho com a tasques». Si a la imatge no hi ha text llegible, l'aplicació us ho diu en comptes d'enviar una petició buida.

### Siri

Digueu **«Afegeix amb IA a To-do Calendar»**, o bé «Afegeix una cita a To-do Calendar» / «Afegeix una tasca a To-do Calendar». La Siri us pregunta què hi voleu afegir, i la petició s'executa **en segon pla sense obrir l'aplicació**. La Siri respon «Entesos. Us avisaré quan estigui llest.» i rebeu una notificació quan el resultat és a punt.

### Botó d'Acció

Assigneu al botó d'Acció la drecera **Afegeix amb IA**. Una premuda, ho dieu i llestos: l'aplicació no ha de passar mai a primer pla.

### Widget i Centre de Control

- **Widget Afegeix amb IA** — un widget per a la pantalla d'inici o la pantalla bloquejada que obre la pantalla d'entrada d'IA amb un sol toc.
- **Centre de Control** (iOS 18 i posteriors) — afegiu-hi el mateix control per poder-hi entrar lliscant cap avall des de qualsevol lloc.

### Full de compartir

Compartiu **text o una imatge de qualsevol altra aplicació** directament amb la IA de To-do Calendar. Si esteu llegint un missatge amb els detalls d'una quedada, o mirant un cartell a Fotos, toqueu Comparteix, trieu To-do Calendar, afegiu-hi una instrucció si voleu i envieu-ho.

La petició des del full de compartir també s'executa en segon pla. Rebreu la confirmació que s'ha enviat, i el resultat el consulteu a l'aplicació.

---

## Com s'executa una petició

1. **Enviada** — la petició surt. Si venia de la Siri, del botó d'Acció o del full de compartir, no cal que tingueu l'aplicació oberta.
2. **Processant** — l'aplicació mostra el progrés. Podeu aturar-la amb **Atura** mentre s'executa, tot i que aturar-la descarta la feina en curs i no es pot reprendre.
3. **Confirmació, quan cal** — si la petició ha de canviar alguna cosa important, l'aplicació us demana que ho aproveu primer i us ensenya exactament què està a punt de fer. Hi ha un compte enrere; si caduca, només cal que ho torneu a demanar.
4. **Feta** — el resultat arriba al calendari a l'instant, amb un resum del que ha canviat.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ca/ai-result.png" alt="Resultat de la IA" width="280">

Només s'executa una petició alhora. Si n'envieu una altra mentre n'hi ha una esperant la vostra aprovació, l'aplicació us diu que primer resolgueu la primera.

---

## Crèdits

Les peticions d'IA consumeixen una **assignació diària que es reinicia cada dia**. El que queda es mostra a la part de dalt de la pantalla d'entrada d'IA, així sempre sabeu com aneu abans d'enviar res.

Si l'assignació s'esgota, l'entrada ràpida amb IA fa una pausa fins al reinici següent. La resta de l'aplicació continua funcionant.

---

## Permisos que us pot demanar

| Permís | Per a què |
|---|---|
| Micròfon + reconeixement de veu | Entrada per veu |
| Càmera | Fer una foto per a **Llegeix des d'una imatge** |
| Fototeca | Triar una imatge existent |
| Notificacions | Dir-vos el resultat d'una petició en segon pla |

Cadascun es demana només el primer cop que feu servir la funció que el necessita, i l'aplicació continua funcionant sense ell: l'entrada per veu recorre al teclat, i la d'imatge, a escriure-ho.

---

[← Índex](./README.md) · [Següent: Widgets i pantalla bloquejada →](./03-widgets.md)
