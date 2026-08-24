# 2. Saisie rapide par IA

[← Sommaire](./README.md)

---

Décrivez ce que vous voulez en langage courant et l'application le construit pour vous — « déjeuner avec Sara vendredi à midi », « décale le dentiste à mardi prochain », « marque la lessive comme faite ». Pas de formulaire, pas de date à faire tourner dans une roulette.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ai-input.png" alt="Saisie rapide par IA" width="280">

La saisie rapide par IA demande d'être connecté à un compte. Tout le reste de l'application fonctionne sans.

---

## Ce qu'elle sait faire

- Créer des tâches et des rendez-vous, avec l'heure, la répétition et le type d'événement déduits de ce que vous avez dit
- Modifier un événement existant — le déplacer, le renommer, changer son heure
- Terminer une tâche, ou annuler sa réalisation
- Supprimer un événement
- Traiter plusieurs choses en une seule demande (« ajoute sport lundi, mercredi et vendredi à 7 h »)

---

## Comment envoyer une demande

### Dans l'application

Appuyez sur le bouton IA depuis l'écran du calendrier. La feuille de saisie s'ouvre avec deux modes entre lesquels vous pouvez basculer à tout moment :

- **Voix** — parlez et regardez la transcription s'afficher en direct. Nécessite l'autorisation d'accès au micro et à la reconnaissance vocale ; si l'une des deux est refusée, l'application vous propose d'ouvrir les réglages d'iOS ou de **Saisir du texte** à la place.
- **Clavier** — tapez votre demande. Utile quand vous êtes dans un endroit où l'on ne parle pas.

### Depuis une image

**Lire depuis une image** transforme une photo en événements. Choisissez **Prendre une photo** ou **Choisir depuis la photothèque** ; l'application lit le texte qu'elle contient — un emploi du temps, une affiche, la capture d'écran d'un message — et vous montre ce qu'elle a trouvé pour que vous corrigiez ce qui est mal passé avant d'envoyer.

Vous pouvez joindre des **Instructions supplémentaires (facultatif)** pour orienter le résultat, du genre « ajoute-les comme tâches ». S'il n'y a aucun texte lisible dans l'image, l'application vous le dit plutôt que d'envoyer une demande vide.

### Siri

Dites **« Ajouter avec l'IA dans To-do Calendar »** — ou « Ajouter un rendez-vous dans To-do Calendar » / « Ajouter une tâche dans To-do Calendar ». Siri vous demande ce que vous voulez ajouter, et la demande part **en arrière-plan sans ouvrir l'application**. Siri répond « Compris. Je vous préviendrai une fois terminé. », et vous recevez une notification quand le résultat est prêt.

### Bouton Action

Associez le bouton Action au raccourci **Ajouter avec l'IA**. Une pression, vous dites la chose, c'est réglé — l'application n'a jamais besoin de passer au premier plan.

### Widget et centre de contrôle

- **Widget Ajouter avec l'IA** — un widget d'écran d'accueil ou d'écran verrouillé qui ouvre l'écran de saisie IA en un geste.
- **Centre de contrôle** (iOS 18 et versions ultérieures) — ajoutez la même commande au centre de contrôle pour y accéder d'un simple balayage vers le bas.

### Feuille de partage

Partagez **du texte ou une image depuis n'importe quelle autre application** directement vers l'IA de To-do Calendar. Vous lisez un message qui contient les détails d'un rendez-vous, ou vous regardez une affiche dans Photos : appuyez sur Partager, choisissez To-do Calendar, ajoutez une instruction si besoin, et envoyez.

La demande envoyée depuis la feuille de partage part elle aussi en arrière-plan. Vous recevez la confirmation qu'elle est partie, et vous consultez le résultat dans l'application.

---

## Le déroulement d'une demande

1. **Envoi** — votre demande part. Si elle vient de Siri, du bouton Action ou de la feuille de partage, inutile de garder l'application ouverte.
2. **Traitement en cours** — l'application affiche la progression. Vous pouvez **Arrêter** une demande pendant qu'elle tourne, sachant que l'arrêt annule la commande en cours et qu'elle ne pourra pas être reprise.
3. **Confirmation requise** — si la demande doit changer quelque chose d'important, l'application vous demande de l'approuver d'abord et vous montre exactement ce qu'elle s'apprête à faire. Un compte à rebours défile ; s'il expire, il suffit de redemander.
4. **Commande terminée** — le résultat arrive immédiatement sur votre calendrier, avec un résumé de ce qui a changé.

<img src="https://raw.githubusercontent.com/sudopark/TodoCalendar-Terms/main/guide/images/ai-result.png" alt="Résultat de l'IA" width="280">

Une seule demande est traitée à la fois. Si vous en envoyez une autre pendant que la première attend votre approbation, l'application vous invite à régler la première.

---

## Crédits

Les demandes IA puisent dans un **quota quotidien réinitialisé chaque jour**. Ce qu'il vous reste s'affiche en haut de l'écran de saisie IA, donc vous savez toujours où vous en êtes avant d'envoyer.

Si le quota est épuisé, la saisie rapide par IA se met en pause jusqu'à la prochaine réinitialisation. Tout le reste de l'application continue de fonctionner.

---

## Autorisations qu'elle peut demander

| Autorisation | Sert à |
|---|---|
| Micro + reconnaissance vocale | La saisie vocale |
| Appareil photo | Prendre une photo pour **Lire depuis une image** |
| Photothèque | Choisir une image existante |
| Notifications | Vous annoncer le résultat d'une demande en arrière-plan |

Chacune n'est demandée qu'au premier usage de la fonction concernée, et l'application continue de marcher sans — la saisie vocale se replie sur le clavier, et l'image sur la frappe au clavier.

---

[← Sommaire](./README.md) · [Suivant : Widgets et écran verrouillé →](./03-widgets.md)
