# 1. Les bases

[← Sommaire](./README.md)

---

## Le calendrier

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/calendar.png" alt="Calendrier" width="280">

La grille mensuelle est l'écran d'accueil. Balayez vers la gauche ou la droite pour changer de mois, appuyez sur un jour pour ouvrir la liste de ses événements en dessous.

- Chaque jour affiche une barre de couleur par événement, plus un **+N** quand il y en a plus que la place disponible.
- La liste du jour est ordonnée : tâches sans heure → tâches avec heure → rendez-vous → jours fériés → événements des calendriers externes.
- Appuyez sur l'en-tête pour sauter à la date de votre choix, ou passez par **Déplacer la date** pour la sélectionner directement.

La densité de la grille — hauteur des lignes, taille du texte, gras, barres de couleur, noms des jours fériés, calendrier lunaire — se règle entièrement. Voir [Personnalisation](./05-personalization.md).

---

## Tâches et rendez-vous

L'application distingue deux sortes d'événements, et la différence tient à une seule question : est-ce que ça se *termine* ?

| | Tâche | Rendez-vous |
|---|---|---|
| Heure | Facultative | Obligatoire |
| Réalisation | Oui — il suffit de la cocher | Non |
| Sans heure | Reste dans **Liste des tâches en cours** jusqu'à ce que vous la terminiez | Impossible |

Une **tâche sans heure** sert à ce que vous devez faire bientôt sans l'avoir encore casé quelque part. Elle reste en haut du calendrier et dans le widget des tâches en cours jusqu'à ce qu'elle soit faite.

Vous pouvez passer de l'un à l'autre à tout moment — **Convertir en rendez-vous** / **Convertir en tâche** depuis le menu « plus » de l'événement. Convertir une tâche en rendez-vous demande une heure.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-detail.png" alt="Détail d'un événement" width="280">

Chaque événement peut porter un **Lieu** (avec aperçu cartographique et ouverture en un geste dans l'application de plans de votre choix), un **Lien** avec aperçu, et une **Note**.

---

## Ajouter des événements

Trois entrées, selon ce que vous avez envie de saisir :

- **Ajout rapide** — le champ de saisie en bas de la liste du jour. Tapez un nom, validez, et vous avez une tâche.
- **Saisie détaillée** — appuyez sur **+** pour ouvrir l'éditeur avec heure, répétition, notifications, type d'événement, lieu, lien et note.
- **Saisie rapide par IA** — décrivez-la en langage courant et laissez l'application construire l'événement. Voir [Saisie rapide par IA](./02-ai-input.md).

Une tâche n'a besoin que d'un nom. Un rendez-vous a besoin d'un nom et d'une heure.

---

## Événements récurrents

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/repeat-options.png" alt="Options de répétition" width="240">

Plutôt que de vous faire assembler une règle à coups de menus déroulants, l'application lit la date que vous avez choisie et propose les options qui lui correspondent. Choisissez un jeudi et la liste affiche littéralement **Tous les Jeudi** et **Le troisième Jeudi de chaque mois**.

**Intervalles courants**

- Tous les jours
- Toutes les semaines · Toutes les 2 semaines · Toutes les 3 semaines · Toutes les 4 semaines — le même jour de la semaine que l'événement
- Tous les mois — à la même date chaque mois
- Tous les ans
- Tous les ans (calendrier lunaire) — pour les anniversaires et les commémorations suivis sur le calendrier lunaire

**Selon la position dans le mois**

- Tous les jours de semaine — du lundi au vendredi. Proposé quand l'événement commence un jour ouvré
- Tous les jours de la dernière semaine de chaque mois
- Le premier / deuxième / troisième / quatrième / dernier *jour de la semaine* de chaque mois — pour « le dernier vendredi du mois » et compagnie

**Fin de la répétition**

Une fois la répétition choisie, décidez comment elle s'arrête : **Jamais**, **Le** une date précise, ou **Après** un certain nombre d'occurrences.

Les tâches récurrentes ne se comportent pas comme les rendez-vous récurrents :

- Une occurrence non terminée reste visible sur le calendrier du jour même après son heure — elle ne file pas discrètement à la suivante.
- La terminer classe cette occurrence dans les tâches terminées et crée la suivante.
- **Ignorer cette tâche** vous fait passer à l'occurrence suivante sans la marquer comme faite.
- Quand la répétition a une condition de fin et qu'il n'y a pas d'occurrence suivante, la série s'achève.

Quand vous modifiez ou supprimez une occurrence d'un événement récurrent, vous choisissez la portée : **Uniquement cette fois**, **À partir de maintenant**, ou **Tous les événements**.

Pour les événements d'un calendrier externe connecté, l'option lunaire n'est pas proposée — ce calendrier n'a aucun moyen de l'exprimer.

---

## Types d'événement et couleurs

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/event-type-list.png" alt="Types d'événement" width="280">

Les types d'événement sont vos catégories, et ils portent la couleur sous laquelle un événement apparaît sur le calendrier. Créez-en autant que vous voulez, chacun avec sa couleur.

- Désactivez un type pour masquer d'un coup tous les événements qui en dépendent — pratique pour mettre en sourdine un calendrier professionnel chargé sans le déconnecter.
- En supprimant un type, vous choisissez de garder ou de supprimer les événements qui y sont rattachés.
- Définissez un **Type d'événement par défaut** pour que les nouveaux événements atterrissent au bon endroit sans avoir à le choisir à chaque fois.

Les jours fériés et les calendriers externes connectés ont leurs propres types, donc vous pouvez les masquer indépendamment eux aussi.

---

## Rappels

Ajoutez autant de rappels que nécessaire par événement.

- **Événements avec heure** — à l'heure de l'événement, ou 1 / 5 / 10 / 15 / 30 minutes, 1 / 2 heures, 1 / 2 / 7 jours avant.
- **Événements toute la journée** — à 9 h ou à midi ce jour-là, ou à 9 h 00, 1 / 2 / 7 jours avant.
- **Heure personnalisée** — choisissez le décalage qui vous arrange.

Les valeurs par défaut pour les événements avec heure et pour ceux qui durent toute la journée se règlent séparément dans les réglages, si bien que les nouveaux événements arrivent déjà armés. Les rappels ont besoin de l'autorisation de notification ; si elle est désactivée, l'application vous renvoie vers les réglages d'iOS.

---

## Événement principal

Épinglez la seule chose que vous ne pouvez pas manquer. L'événement principal reste en haut du calendrier quelle que soit la date que vous regardez, et il a son propre widget.

Les tâches et les rendez-vous non récurrents peuvent être désignés comme principaux. Les rendez-vous récurrents, non.

---

## Tâches non terminées

Les tâches dont l'heure est passée sans qu'elles soient terminées sont regroupées dans une section **Tâches non terminées** en haut du calendrier, pour qu'un oubli ne disparaisse pas dans la semaine dernière.

Les tâches sans heure et celles à venir ne comptent pas comme non terminées — leur échéance n'est simplement pas passée. Vous pouvez masquer complètement la section dans les réglages si vous préférez ne pas la voir.

---

## Tâches terminées

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/done-todos.png" alt="Tâches terminées" width="280">

Tout ce que vous cochez est conservé et regroupé selon le moment où vous l'avez terminé — aujourd'hui, hier, ce mois-ci, puis par mois et par année.

- Annulez une réalisation pour faire revenir la tâche.
- Faites le ménage en une fois : **Toutes les tâches terminées**, ou seulement celles de **Plus d'un mois**, **Plus de 3 mois**, **Plus de 6 mois** ou **Plus d'un an**.

---

## Partage

Partagez **une journée, une semaine ou un mois** sous forme de texte ou de carte image.

Avant de partager, vous pouvez filtrer les types d'événement à inclure et décider si leurs noms apparaissent, de sorte à envoyer votre semaine à quelqu'un sans en dévoiler chaque détail.

---

[← Sommaire](./README.md) · [Suivant : Saisie rapide par IA →](./02-ai-input.md)
