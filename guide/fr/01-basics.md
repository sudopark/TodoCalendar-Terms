# 1. Les bases

[← Sommaire](./README.md)

---

## Le calendrier

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fr/calendar.png" alt="Calendrier" width="280">

Le calendrier du mois est l'écran d'accueil. Balayez vers la gauche ou la droite pour changer de mois, appuyez sur un jour pour ouvrir la liste de ses événements en dessous.

- Chaque jour affiche une barre de couleur par événement, plus un **+N** quand le jour a plus d'événements que la ligne ne peut en montrer.
- La liste du jour est ordonnée : tâches sans heure → tâches avec heure → rendez-vous → jours fériés → événements des calendriers externes.
- Appuyez sur l'en-tête pour sauter à la date de votre choix, ou passez par **Déplacer la date** pour la sélectionner directement.

C'est vous qui décidez ce que chaque jour affiche : la quantité de détail par événement, la taille du texte, les couleurs, les noms des jours fériés et le calendrier lunaire. [Personnalisation](./05-personalization.md) reprend chaque réglage par son nom.

---

## Tâches et rendez-vous

L'application distingue deux sortes d'événements, et la différence tient à une chose : est-ce que vous le cochez une fois fait ?

| | Tâche | Rendez-vous |
|---|---|---|
| Heure | Facultative | Obligatoire |
| Réalisation | Oui — il suffit de la cocher | Non |
| Sans heure | Reste dans **Liste des tâches en cours** jusqu'à ce que vous la terminiez | Impossible |

Une **tâche sans heure** sert à ce que vous devez faire bientôt sans avoir encore décidé quand. Elle reste en haut du calendrier et dans le widget Liste des tâches en cours jusqu'à ce qu'elle soit faite.

Vous pouvez passer de l'un à l'autre à tout moment — **Convertir en rendez-vous** / **Convertir en tâche** depuis le menu « plus » de l'événement. Seule la conversion d'une tâche en rendez-vous demande une heure.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fr/event-detail.png" alt="Détail d'un événement" width="280">

Chaque événement peut porter un **Lieu**, un **Lien** et une **Note**. Le lieu s'accompagne d'un aperçu de la carte et s'ouvre en un geste dans l'application de plans de votre choix ; le lien a son propre aperçu.

---

## Ajouter des événements

Trois façons d'ajouter un événement, selon ce que vous avez envie de saisir :

- **Ajout rapide** — le champ de saisie en bas de la liste du jour. Tapez un nom, validez, et la tâche est créée.
- **Saisie détaillée** — appuyez sur **+** pour ouvrir l'éditeur avec heure, répétition, rappels, type d'événement, lieu, lien et note.
- **Saisie rapide par IA** — décrivez-le en langage courant et laissez l'application construire l'événement. Voir [Saisie rapide par IA](./02-ai-input.md).

Une tâche n'a besoin que d'un nom. Un rendez-vous a besoin d'un nom et d'une heure.

---

## Événements récurrents

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fr/repeat-options.png" alt="Options de répétition" width="240">

Plutôt que de vous faire assembler une règle de répétition à coups de menus déroulants, l'application lit la date que vous avez choisie et vous propose des options toutes faites. Choisissez un jeudi et la liste vous propose **Tous les jeudis** et **Le troisième jeudi de chaque mois**.

**Intervalles courants**

- Tous les jours
- Toutes les semaines · Toutes les 2 semaines · Toutes les 3 semaines · Toutes les 4 semaines — le même jour de la semaine que l'événement
- Tous les mois — à la même date chaque mois
- Tous les ans
- Tous les ans (calendrier lunaire) — pour les anniversaires et les commémorations suivis sur le calendrier lunaire

**Selon la position dans le mois**

- Tous les jours de semaine — du lundi au vendredi. Proposé quand l'événement commence un jour de semaine
- Tous les jours de la dernière semaine de chaque mois
- Le premier / deuxième / troisième / quatrième / dernier **jeudi** de chaque mois — le jour de la semaine se remplit à partir de la date choisie, si bien qu'un événement du vendredi propose **Le dernier vendredi de chaque mois**

**Fin de la répétition**

Une fois la répétition choisie, décidez quand elle s'arrête : **Jamais** pour qu'elle continue indéfiniment, **Le** pour fixer la date à laquelle elle prend fin, ou **Après** un nombre d'**occurrences**.

Les tâches récurrentes ne se comportent pas comme les rendez-vous récurrents :

- Une occurrence non terminée reste visible sur le calendrier du jour même après son heure — elle ne passe pas d'elle-même à l'occurrence suivante.
- La terminer classe cette occurrence dans les tâches terminées et crée la suivante.
- **Ignorer cette tâche** vous fait passer à l'occurrence suivante sans la marquer comme faite.
- Quand la répétition a une condition de fin et qu'il n'y a pas d'occurrence suivante, la série s'achève.

Quand vous modifiez ou supprimez une occurrence d'un événement récurrent, vous choisissez la portée : **Uniquement cette fois**, **À partir de maintenant**, ou **Tous les événements**.

Pour les événements d'un calendrier externe connecté, l'option lunaire n'est pas proposée — les calendriers externes n'ont nulle part où stocker une règle de répétition lunaire.

---

## Types d'événement et couleurs

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fr/event-type-list.png" alt="Types d'événement" width="280">

Les types d'événement sont vos catégories, et ils portent la couleur sous laquelle un événement apparaît sur le calendrier. Créez-en autant que vous voulez, chacun avec sa couleur.

- Désactivez un type pour masquer d'un coup tous les événements qui en dépendent — pratique pour mettre en sourdine un calendrier professionnel chargé sans le déconnecter.
- En supprimant un type, vous choisissez de garder ou de supprimer les événements qui y sont rattachés.
- Définissez un **Type d'événement par défaut** pour que les nouveaux événements atterrissent au bon endroit sans avoir à le choisir à chaque fois.

Les jours fériés et les calendriers externes connectés ont leurs propres types, donc vous pouvez les masquer indépendamment eux aussi.

---

## Rappels

Ajoutez autant de rappels que nécessaire par événement.

- **Événements avec heure** — à l'heure de l'événement, ou 1 / 5 / 10 / 15 / 30 minutes, 1 / 2 heures, 1 / 2 / 7 jours avant.
- **Événements toute la journée** — à 9 h ou à midi ce jour-là, ou à 9 h, 1 / 2 / 7 jours avant.
- **Heure personnalisée** — choisissez le décalage qui vous arrange.

Les valeurs par défaut pour les événements avec heure et pour ceux qui durent toute la journée se règlent séparément dans les réglages, si bien que les nouveaux événements ont déjà leurs rappels. Les rappels ont besoin de l'autorisation de notification ; si elle est désactivée, l'application vous renvoie vers les réglages d'iOS.

---

## Événement principal

Épinglez la seule chose que vous ne pouvez pas manquer. L'événement principal reste en haut du calendrier quelle que soit la date que vous regardez, et il a son propre widget.

Les tâches et les rendez-vous non récurrents peuvent être désignés comme principaux. Les rendez-vous récurrents, non.

---

## Tâches non terminées

Les tâches dont l'heure est passée sans qu'elles soient terminées sont regroupées dans une section **Tâches non terminées** en haut du calendrier, pour qu'une tâche oubliée ne reste pas enterrée à une date déjà passée.

Les tâches sans heure et celles à venir ne comptent pas comme non terminées — leur échéance n'est simplement pas passée. Vous pouvez masquer complètement la section dans les réglages si vous préférez ne pas la voir.

---

## Tâches terminées

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/fr/done-todos.png" alt="Tâches terminées" width="280">

Tout ce que vous cochez est conservé et regroupé selon le moment où vous l'avez terminé — aujourd'hui, hier, ce mois-ci, puis par mois et par année.

- Annulez une réalisation pour faire revenir la tâche.
- Faites le ménage en une fois : **Toutes les tâches terminées**, ou seulement celles de **Plus d'un mois**, **Plus de 3 mois**, **Plus de 6 mois** ou **Plus d'un an**.

---

## Partage

Partagez **une journée, une semaine ou un mois** sous forme de texte ou de carte image.

Avant de partager, vous pouvez filtrer les types d'événement à inclure et décider si leurs noms apparaissent, pour envoyer votre semaine à quelqu'un sans en dévoiler tout le contenu.

---

[← Sommaire](./README.md) · [Suivant : Saisie rapide par IA →](./02-ai-input.md)
