# Entraîneur psychomoteur SECPIL

**Suivi de trajectoire · palonnier · réaction F1–F4 · calcul mental — en simultané, comme à l'épreuve.**

Un outil web gratuit, en un seul fichier HTML, pour s'entraîner à l'épreuve psychomotrice multitâche de la sélection pilote de l'armée de l'air française (EOPN). Aucune installation, aucun compte, aucun serveur : on ouvre le fichier dans un navigateur et on s'entraîne.

Construit avec [Claude Code](https://claude.com/claude-code).

---

## Pourquoi ce projet existe

Le SECPIL est l'une des épreuves les plus sélectives du parcours EOPN. Elle ne teste pas des connaissances mais une capacité : tenir plusieurs tâches de front sans qu'aucune ne se dégrade pendant que les autres progressent. C'est une compétence qui s'entraîne — mais qui, jusqu'ici, ne s'entraînait nulle part en dehors du jour de l'épreuve elle-même.

Les plateformes de préparation à l'EOPN sont payantes, et aucune ne propose d'entraînement réaliste à cette épreuve précise. Ce projet part d'un principe simple : la préparation à un concours public ne devrait pas dépendre de ce qu'on peut payer. Ce que la sélection teste réellement doit pouvoir s'entraîner gratuitement, par quiconque a un ordinateur et, si possible, un manche et des pédales.

---

## Ce qu'on y trouve

Quatre tâches à mener de front, comme au SECPIL :

- **Suivi de trajectoire (∞)** — une cible à poursuivre en continu au manche, à la souris, au clavier ou à la manette
- **Palonnier** — un suivi latéral indépendant, pour qui dispose de pédales
- **Réaction F1–F4** — des stimuli à traiter vite, assignables aux boutons de son propre HOTAS
- **Calcul mental** — des opérations à résoudre sans lâcher le reste
- **Mémoire (nombres)** — des chiffres à retenir et additionner, en vocal, en visuel, ou les deux

Chaque tâche se règle et se travaille isolément. L'ensemble se combine progressivement, puis totalement, à la manière de l'épreuve réelle.

### Trois modes

**Séance libre** — chaque paramètre est réglable : vitesse, orientation, cadence, sensibilité du manche et du palonnier, assignation des touches, mode et rythme de la mémoire de nombres. Des aides optionnelles (répétition audio, assistance visuelle) permettent d'apprivoiser une tâche avant de la durcir.

**Campagne** — une progression en douze paliers, de la tâche isolée à l'ensemble complet :

> Suivi seul → Suivi + Réaction → Suivi + Calcul → Suivi + Palonnier → Suivi + Nombres → Suivi + Réaction + Calcul → Suivi + Palonnier + Réaction → Suivi + Palonnier + Calcul → Suivi + Nombres + Réaction → Suivi + Nombres + Calcul → Suivi + Nombres + Palonnier → **Tout ensemble**

Chaque palier reprend les réglages standardisés du mode examen — sans assistance, règles du jeu non modifiables — pour qu'on sache exactement à quel niveau de charge on se situe, sans confondre progrès réel et réglages facilités.

**Examen** — le format officiel reconstitué autant que les informations publiques le permettent : les cinq tâches en simultané, vingt minutes, épreuve unique, sans aucune assistance et sans aucun réglage de jeu modifiable. Seuls restent ajustables les éléments qui dépendent du matériel de chacun — sensibilité du manche et du palonnier, choix des axes, assignation des boutons — puisqu'un examen standardisé n'a pas à désavantager qui n'a pas exactement le même équipement.

### Score et suivi

Chaque séance se conclut par une note détaillée sur 20, pondérée par tâche, avec un historique conservé localement pour suivre sa progression dans le temps.

---

## Honnêteté sur ce que c'est — et ce que ce n'est pas

Le SECPIL n'est pas un test public. Son barème exact, le rythme précis de ses stimuli et le détail de son déroulé ne sont pas publiés par l'armée de l'air. Ce projet s'appuie sur les informations disponibles publiquement — durée officielle, structure en tâches combinées, retours recoupés de sites de préparation EOPN — et comble le reste par des estimations raisonnables, toujours signalées comme telles dans l'outil lui-même.

Un écart connu, assumé dans l'interface : au SECPIL réel, la mémoire de nombres se restitue en cumul annoncé à voix haute à chaque chiffre ; ici, seule la mémorisation finale est testée, saisie au clavier en fin de séance. L'entraînement à la mémorisation sous charge reste valable ; l'exercice de verbalisation simultanée, lui, ne l'est pas.

Ce n'est donc pas une reproduction certifiée de l'épreuve. C'est un entraînement sérieux à ce qu'elle mesure : la capacité à répartir son attention sans qu'aucune tâche ne s'effondre quand les autres montent en charge.

---

## Utilisation

1. Télécharger le fichier `secpil-multitask-trainer.html`
2. L'ouvrir dans n'importe quel navigateur récent
3. Brancher un manche et des pédales si on en a — sinon, clavier ou souris suffisent
4. Commencer en séance libre pour régler son matériel, puis progresser en campagne, puis se tester en examen

Aucune donnée ne quitte l'appareil : tout tourne localement, dans le navigateur.

---

## Licence

Projet libre et gratuit, sans aucune contrepartie. À partager avec quiconque prépare ce concours.
